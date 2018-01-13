<Type Name="TumblingWindowTrigger" FullName="Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger">
  <TypeSignature Language="C#" Value="public class TumblingWindowTrigger : Microsoft.Azure.Management.DataFactory.Models.Trigger" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TumblingWindowTrigger extends Microsoft.Azure.Management.DataFactory.Models.Trigger" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger" />
  <TypeSignature Language="VB.NET" Value="Public Class TumblingWindowTrigger&#xA;Inherits Trigger" />
  <TypeSignature Language="F#" Value="type TumblingWindowTrigger = class&#xA;    inherit Trigger" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.Trigger</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="3ffc8-101">パイプラインをスケジュールするトリガーでは、置かず開始時刻からすべての一定の時間間隔の windows を実行するときし、(開始時刻が過去の場合) もバックフィル シナリオをサポートしています。</span><span class="sxs-lookup"><span data-stu-id="3ffc8-101">Trigger that schedules pipeline runs for all fixed time interval windows from a start time without gaps and also supports backfill scenarios (when start time is in the past).</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TumblingWindowTrigger ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3ffc8-102">TumblingWindowTrigger クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3ffc8-102">Initializes a new instance of the TumblingWindowTrigger class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TumblingWindowTrigger (Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference pipeline, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string description = null, string runtimeState = null, string frequency = null, Nullable&lt;int&gt; interval = null, Nullable&lt;DateTime&gt; startTime = null, Nullable&lt;DateTime&gt; endTime = null, object delay = null, Nullable&lt;int&gt; maxConcurrency = null, Microsoft.Azure.Management.DataFactory.Models.RetryPolicy retryPolicy = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference pipeline, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string description, string runtimeState, string frequency, valuetype System.Nullable`1&lt;int32&gt; interval, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; endTime, object delay, valuetype System.Nullable`1&lt;int32&gt; maxConcurrency, class Microsoft.Azure.Management.DataFactory.Models.RetryPolicy retryPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.#ctor(Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference,System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Object,System.Nullable{System.Int32},Microsoft.Azure.Management.DataFactory.Models.RetryPolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger : Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * string * string * Nullable&lt;int&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * obj * Nullable&lt;int&gt; * Microsoft.Azure.Management.DataFactory.Models.RetryPolicy -&gt; Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger" Usage="new Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger (pipeline, additionalProperties, description, runtimeState, frequency, interval, startTime, endTime, delay, maxConcurrency, retryPolicy)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="pipeline" Type="Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="runtimeState" Type="System.String" />
        <Parameter Name="frequency" Type="System.String" />
        <Parameter Name="interval" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="delay" Type="System.Object" />
        <Parameter Name="maxConcurrency" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="retryPolicy" Type="Microsoft.Azure.Management.DataFactory.Models.RetryPolicy" />
      </Parameters>
      <Docs>
        <param name="pipeline"><span data-ttu-id="3ffc8-103">パイプラインを実行を準備ができているウィンドウのトリガーのイベントが発生したときに作成されます。</span><span class="sxs-lookup"><span data-stu-id="3ffc8-103">Pipeline for which runs are created when an event is fired for trigger window that is ready.</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="3ffc8-104">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="3ffc8-104">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="description"><span data-ttu-id="3ffc8-105">トリガーの説明です。</span><span class="sxs-lookup"><span data-stu-id="3ffc8-105">Trigger description.</span></span></param>
        <param name="runtimeState"><span data-ttu-id="3ffc8-106">トリガーが実行されているかを示します。</span><span class="sxs-lookup"><span data-stu-id="3ffc8-106">Indicates if trigger is running or not.</span></span>
            <span data-ttu-id="3ffc8-107">トリガーで開始/停止 Api が呼び出されたときに更新されます。</span><span class="sxs-lookup"><span data-stu-id="3ffc8-107">Updated when Start/Stop APIs are called on the Trigger.</span></span> <span data-ttu-id="3ffc8-108">使用可能な値が含まれます: 'の開始'、'停止'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="3ffc8-108">Possible values include: 'Started', 'Stopped', 'Disabled'</span></span></param>
        <param name="frequency"><span data-ttu-id="3ffc8-109">時間枠の頻度です。</span><span class="sxs-lookup"><span data-stu-id="3ffc8-109">The frequency of the time windows.</span></span> <span data-ttu-id="3ffc8-110">使用可能な値が含まれます: 'Minute'、'Hour'</span><span class="sxs-lookup"><span data-stu-id="3ffc8-110">Possible values include: 'Minute', 'Hour'</span></span></param>
        <param name="interval"><span data-ttu-id="3ffc8-111">間隔の時間枠です。</span><span class="sxs-lookup"><span data-stu-id="3ffc8-111">The interval of the time windows.</span></span> <span data-ttu-id="3ffc8-112">許可されている最小間隔とは、15 分です。</span><span class="sxs-lookup"><span data-stu-id="3ffc8-112">The minimum interval allowed is 15 Minutes.</span></span></param>
        <param name="startTime"><span data-ttu-id="3ffc8-113">準備ができている windows のイベントが発生するトリガーの期間の開始時刻。</span><span class="sxs-lookup"><span data-stu-id="3ffc8-113">The start time for the time period for the trigger during which events are fired for windows that are ready.</span></span>
            <span data-ttu-id="3ffc8-114">UTC 時刻だけは現在サポートされています。</span><span class="sxs-lookup"><span data-stu-id="3ffc8-114">Only UTC time is currently supported.</span></span></param>
        <param name="endTime"><span data-ttu-id="3ffc8-115">準備ができている windows のイベントが発生するトリガーの期間の終了時刻。</span><span class="sxs-lookup"><span data-stu-id="3ffc8-115">The end time for the time period for the trigger during which events are fired for windows that are ready.</span></span>
            <span data-ttu-id="3ffc8-116">UTC 時刻だけは現在サポートされています。</span><span class="sxs-lookup"><span data-stu-id="3ffc8-116">Only UTC time is currently supported.</span></span></param>
        <param name="delay"><span data-ttu-id="3ffc8-117">期限のトリガーの待機時間を指定新しい実行をトリガするまでの時間。</span><span class="sxs-lookup"><span data-stu-id="3ffc8-117">Specifies how long the trigger waits past due time before triggering new run.</span></span> <span data-ttu-id="3ffc8-118">Alter ウィンドウの開始と終了時刻にしません。</span><span class="sxs-lookup"><span data-stu-id="3ffc8-118">It doesn't alter window start and end time.</span></span> <span data-ttu-id="3ffc8-119">既定値は 0 です。</span><span class="sxs-lookup"><span data-stu-id="3ffc8-119">The default is 0.</span></span> <span data-ttu-id="3ffc8-120">型: 文字列 (または式の resultType 文字列)、パターン: ((\d+)\.)? (\d\d):(60|([0-5][0-9])): (60 |([0-5][0-9])) です。</span><span class="sxs-lookup"><span data-stu-id="3ffc8-120">Type: string (or Expression with resultType string), pattern: ((\d+)\.)?(\d\d):(60|([0-5][0-9])):(60|([0-5][0-9])).</span></span></param>
        <param name="maxConcurrency"><span data-ttu-id="3ffc8-121">新しい実行がトリガーされた並列の時間枠 (実行の準備完了) の最大数。</span><span class="sxs-lookup"><span data-stu-id="3ffc8-121">The max number of parallel time windows (ready for execution) for which a new run is triggered.</span></span></param>
        <param name="retryPolicy"><span data-ttu-id="3ffc8-122">失敗したパイプラインの実行に適用されるポリシーを再試行してください。</span><span class="sxs-lookup"><span data-stu-id="3ffc8-122">Retry policy that will be applied for failed pipeline runs.</span></span></param>
        <summary>
            <span data-ttu-id="3ffc8-123">TumblingWindowTrigger クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3ffc8-123">Initializes a new instance of the TumblingWindowTrigger class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delay">
      <MemberSignature Language="C#" Value="public object Delay { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Delay" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.Delay" />
      <MemberSignature Language="VB.NET" Value="Public Property Delay As Object" />
      <MemberSignature Language="F#" Value="member this.Delay : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.Delay" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.delay")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3ffc8-124">期限のトリガーの待機時間を指定を取得または設定前に、新しい実行をトリガーする時間。</span><span class="sxs-lookup"><span data-stu-id="3ffc8-124">Gets or sets specifies how long the trigger waits past due time before triggering new run.</span></span> <span data-ttu-id="3ffc8-125">Alter ウィンドウの開始と終了時刻にしません。</span><span class="sxs-lookup"><span data-stu-id="3ffc8-125">It doesn't alter window start and end time.</span></span> <span data-ttu-id="3ffc8-126">既定値は 0 です。</span><span class="sxs-lookup"><span data-stu-id="3ffc8-126">The default is 0.</span></span> <span data-ttu-id="3ffc8-127">型: 文字列 (または式の resultType 文字列)、パターン: ((\d+)\.)? (\d\d):(60|([0-5][0-9])): (60 |([0-5][0-9])) です。</span><span class="sxs-lookup"><span data-stu-id="3ffc8-127">Type: string (or Expression with resultType string), pattern: ((\d+)\.)?(\d\d):(60|([0-5][0-9])):(60|([0-5][0-9])).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public Property EndTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.EndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.endTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3ffc8-128">取得または準備ができている windows のイベントが発生するトリガーの期間の終了時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="3ffc8-128">Gets or sets the end time for the time period for the trigger during which events are fired for windows that are ready.</span></span> <span data-ttu-id="3ffc8-129">UTC 時刻だけは現在サポートされています。</span><span class="sxs-lookup"><span data-stu-id="3ffc8-129">Only UTC time is currently supported.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Frequency">
      <MemberSignature Language="C#" Value="public string Frequency { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Frequency" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.Frequency" />
      <MemberSignature Language="VB.NET" Value="Public Property Frequency As String" />
      <MemberSignature Language="F#" Value="member this.Frequency : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.Frequency" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.frequency")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3ffc8-130">取得または時間枠の頻度を設定します。</span><span class="sxs-lookup"><span data-stu-id="3ffc8-130">Gets or sets the frequency of the time windows.</span></span> <span data-ttu-id="3ffc8-131">使用可能な値が含まれます: 'Minute'、'Hour'</span><span class="sxs-lookup"><span data-stu-id="3ffc8-131">Possible values include: 'Minute', 'Hour'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Interval">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Interval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Interval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.Interval" />
      <MemberSignature Language="VB.NET" Value="Public Property Interval As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Interval : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.Interval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.interval")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3ffc8-132">取得または時間帯の期間を設定します。</span><span class="sxs-lookup"><span data-stu-id="3ffc8-132">Gets or sets the interval of the time windows.</span></span> <span data-ttu-id="3ffc8-133">許可されている最小間隔とは、15 分です。</span><span class="sxs-lookup"><span data-stu-id="3ffc8-133">The minimum interval allowed is 15 Minutes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxConcurrency">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxConcurrency { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxConcurrency" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.MaxConcurrency" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxConcurrency As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxConcurrency : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.MaxConcurrency" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.maxConcurrency")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3ffc8-134">取得または新規の実行がトリガーされるの並列の時間枠 (実行の準備完了) の最大数を設定します。</span><span class="sxs-lookup"><span data-stu-id="3ffc8-134">Gets or sets the max number of parallel time windows (ready for execution) for which a new run is triggered.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Pipeline">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference Pipeline { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference Pipeline" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.Pipeline" />
      <MemberSignature Language="VB.NET" Value="Public Property Pipeline As TriggerPipelineReference" />
      <MemberSignature Language="F#" Value="member this.Pipeline : Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.Pipeline" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pipeline")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3ffc8-135">取得または作成対象の実行は準備ができているウィンドウのトリガーのイベントが発生したときにパイプラインを設定します。</span><span class="sxs-lookup"><span data-stu-id="3ffc8-135">Gets or sets pipeline for which runs are created when an event is fired for trigger window that is ready.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.RetryPolicy RetryPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.RetryPolicy RetryPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.RetryPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryPolicy As RetryPolicy" />
      <MemberSignature Language="F#" Value="member this.RetryPolicy : Microsoft.Azure.Management.DataFactory.Models.RetryPolicy with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.RetryPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.retryPolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.RetryPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3ffc8-136">取得または失敗したパイプラインの実行に適用される再試行ポリシーを設定します。</span><span class="sxs-lookup"><span data-stu-id="3ffc8-136">Gets or sets retry policy that will be applied for failed pipeline runs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.startTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3ffc8-137">取得または準備ができている windows のイベントが発生するトリガーの期間の開始時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="3ffc8-137">Gets or sets the start time for the time period for the trigger during which events are fired for windows that are ready.</span></span> <span data-ttu-id="3ffc8-138">UTC 時刻だけは現在サポートされています。</span><span class="sxs-lookup"><span data-stu-id="3ffc8-138">Only UTC time is currently supported.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="tumblingWindowTrigger.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3ffc8-139">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="3ffc8-139">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="3ffc8-140">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="3ffc8-140">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>