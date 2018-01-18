<Type Name="USqlJobProperties" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties">
  <TypeSignature Language="C#" Value="public class USqlJobProperties : Microsoft.Azure.Management.DataLake.Analytics.Models.JobProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit USqlJobProperties extends Microsoft.Azure.Management.DataLake.Analytics.Models.JobProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class USqlJobProperties&#xA;Inherits JobProperties" />
  <TypeSignature Language="F#" Value="type USqlJobProperties = class&#xA;    inherit JobProperties" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataLake.Analytics.Models.JobProperties</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("USql")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="b3c66-101">U-SQL ジョブのプロパティは U SQL ジョブを取得するときに使用します。</span><span class="sxs-lookup"><span data-stu-id="b3c66-101">U-SQL job properties used when retrieving U-SQL jobs.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public USqlJobProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b3c66-102">USqlJobProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b3c66-102">Initializes a new instance of the USqlJobProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public USqlJobProperties (string script, string runtimeVersion = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobResource&gt; resources = null, Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatistics statistics = null, Microsoft.Azure.Management.DataLake.Analytics.Models.JobDataPath debugData = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.Diagnostics&gt; diagnostics = null, string algebraFilePath = null, Nullable&lt;TimeSpan&gt; totalCompilationTime = null, Nullable&lt;TimeSpan&gt; totalPauseTime = null, Nullable&lt;TimeSpan&gt; totalQueuedTime = null, Nullable&lt;TimeSpan&gt; totalRunningTime = null, string rootProcessNodeId = null, string yarnApplicationId = null, Nullable&lt;long&gt; yarnApplicationTimeStamp = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.CompileMode&gt; compileMode = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string script, string runtimeVersion, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobResource&gt; resources, class Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatistics statistics, class Microsoft.Azure.Management.DataLake.Analytics.Models.JobDataPath debugData, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.Diagnostics&gt; diagnostics, string algebraFilePath, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; totalCompilationTime, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; totalPauseTime, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; totalQueuedTime, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; totalRunningTime, string rootProcessNodeId, string yarnApplicationId, valuetype System.Nullable`1&lt;int64&gt; yarnApplicationTimeStamp, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.CompileMode&gt; compileMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.#ctor(System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.DataLake.Analytics.Models.JobResource},Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatistics,Microsoft.Azure.Management.DataLake.Analytics.Models.JobDataPath,System.Collections.Generic.IList{Microsoft.Azure.Management.DataLake.Analytics.Models.Diagnostics},System.String,System.Nullable{System.TimeSpan},System.Nullable{System.TimeSpan},System.Nullable{System.TimeSpan},System.Nullable{System.TimeSpan},System.String,System.String,System.Nullable{System.Int64},System.Nullable{Microsoft.Azure.Management.DataLake.Analytics.Models.CompileMode})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (script As String, Optional runtimeVersion As String = null, Optional resources As IList(Of JobResource) = null, Optional statistics As JobStatistics = null, Optional debugData As JobDataPath = null, Optional diagnostics As IList(Of Diagnostics) = null, Optional algebraFilePath As String = null, Optional totalCompilationTime As Nullable(Of TimeSpan) = null, Optional totalPauseTime As Nullable(Of TimeSpan) = null, Optional totalQueuedTime As Nullable(Of TimeSpan) = null, Optional totalRunningTime As Nullable(Of TimeSpan) = null, Optional rootProcessNodeId As String = null, Optional yarnApplicationId As String = null, Optional yarnApplicationTimeStamp As Nullable(Of Long) = null, Optional compileMode As Nullable(Of CompileMode) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties : string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobResource&gt; * Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatistics * Microsoft.Azure.Management.DataLake.Analytics.Models.JobDataPath * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.Diagnostics&gt; * string * Nullable&lt;TimeSpan&gt; * Nullable&lt;TimeSpan&gt; * Nullable&lt;TimeSpan&gt; * Nullable&lt;TimeSpan&gt; * string * string * Nullable&lt;int64&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.CompileMode&gt; -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties (script, runtimeVersion, resources, statistics, debugData, diagnostics, algebraFilePath, totalCompilationTime, totalPauseTime, totalQueuedTime, totalRunningTime, rootProcessNodeId, yarnApplicationId, yarnApplicationTimeStamp, compileMode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="script" Type="System.String" />
        <Parameter Name="runtimeVersion" Type="System.String" />
        <Parameter Name="resources" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobResource&gt;" />
        <Parameter Name="statistics" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatistics" />
        <Parameter Name="debugData" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.JobDataPath" />
        <Parameter Name="diagnostics" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.Diagnostics&gt;" />
        <Parameter Name="algebraFilePath" Type="System.String" />
        <Parameter Name="totalCompilationTime" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="totalPauseTime" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="totalQueuedTime" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="totalRunningTime" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="rootProcessNodeId" Type="System.String" />
        <Parameter Name="yarnApplicationId" Type="System.String" />
        <Parameter Name="yarnApplicationTimeStamp" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="compileMode" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.CompileMode&gt;" />
      </Parameters>
      <Docs>
        <param name="script"><span data-ttu-id="b3c66-103">スクリプトを実行するには</span><span class="sxs-lookup"><span data-stu-id="b3c66-103">the script to run</span></span></param>
        <param name="runtimeVersion"><span data-ttu-id="b3c66-104">ジョブの実行中の特定の型を使用する Data Lake Analytics エンジンのランタイムのバージョン。</span><span class="sxs-lookup"><span data-stu-id="b3c66-104">the runtime version of the Data Lake Analytics engine to use for the specific type of job being run.</span></span></param>
        <param name="resources"><span data-ttu-id="b3c66-105">ジョブに必要なリソースの一覧</span><span class="sxs-lookup"><span data-stu-id="b3c66-105">the list of resources that are required by the job</span></span></param>
        <param name="statistics"><span data-ttu-id="b3c66-106">ジョブ特定の統計。</span><span class="sxs-lookup"><span data-stu-id="b3c66-106">the job specific statistics.</span></span></param>
        <param name="debugData"><span data-ttu-id="b3c66-107">ジョブの特定のデバッグ データの場所。</span><span class="sxs-lookup"><span data-stu-id="b3c66-107">the job specific debug data locations.</span></span></param>
        <param name="diagnostics"><span data-ttu-id="b3c66-108">ジョブの診断します。</span><span class="sxs-lookup"><span data-stu-id="b3c66-108">the diagnostics for the job.</span></span></param>
        <param name="algebraFilePath"><span data-ttu-id="b3c66-109">ジョブが完了した後は、代数ファイルのパス</span><span class="sxs-lookup"><span data-stu-id="b3c66-109">the algebra file path after the job has completed</span></span></param>
        <param name="totalCompilationTime"><span data-ttu-id="b3c66-110">このジョブは、コンパイルに費やされた時間の合計。</span><span class="sxs-lookup"><span data-stu-id="b3c66-110">the total time this job spent compiling.</span></span> <span data-ttu-id="b3c66-111">この値は、ユーザーによっては設定しないでである場合は無視されます。</span><span class="sxs-lookup"><span data-stu-id="b3c66-111">This value should not be set by the user and will be ignored if it is.</span></span></param>
        <param name="totalPauseTime"><span data-ttu-id="b3c66-112">このジョブの合計時間が一時停止します。</span><span class="sxs-lookup"><span data-stu-id="b3c66-112">the total time this job spent paused.</span></span>
            <span data-ttu-id="b3c66-113">この値は、ユーザーによっては設定しないでである場合は無視されます。</span><span class="sxs-lookup"><span data-stu-id="b3c66-113">This value should not be set by the user and will be ignored if it is.</span></span></param>
        <param name="totalQueuedTime"><span data-ttu-id="b3c66-114">このジョブの合計時間がキューに登録します。</span><span class="sxs-lookup"><span data-stu-id="b3c66-114">the total time this job spent queued.</span></span>
            <span data-ttu-id="b3c66-115">この値は、ユーザーによっては設定しないでである場合は無視されます。</span><span class="sxs-lookup"><span data-stu-id="b3c66-115">This value should not be set by the user and will be ignored if it is.</span></span></param>
        <param name="totalRunningTime"><span data-ttu-id="b3c66-116">このジョブが実行に費やした時間の合計。</span><span class="sxs-lookup"><span data-stu-id="b3c66-116">the total time this job spent executing.</span></span> <span data-ttu-id="b3c66-117">この値は、ユーザーによっては設定しないでである場合は無視されます。</span><span class="sxs-lookup"><span data-stu-id="b3c66-117">This value should not be set by the user and will be ignored if it is.</span></span></param>
        <param name="rootProcessNodeId"><span data-ttu-id="b3c66-118">ジョブの実行を調整するジョブ マネージャーを識別する ID。</span><span class="sxs-lookup"><span data-stu-id="b3c66-118">the ID used to identify the job manager coordinating job execution.</span></span> <span data-ttu-id="b3c66-119">この値は、ユーザーによっては設定しないでである場合は無視されます。</span><span class="sxs-lookup"><span data-stu-id="b3c66-119">This value should not be set by the user and will be ignored if it is.</span></span></param>
        <param name="yarnApplicationId"><span data-ttu-id="b3c66-120">ジョブの実行、yarn アプリケーションを識別する ID。</span><span class="sxs-lookup"><span data-stu-id="b3c66-120">the ID used to identify the yarn application executing the job.</span></span> <span data-ttu-id="b3c66-121">この値は、ユーザーによっては設定しないでである場合は無視されます。</span><span class="sxs-lookup"><span data-stu-id="b3c66-121">This value should not be set by the user and will be ignored if it is.</span></span></param>
        <param name="yarnApplicationTimeStamp"><span data-ttu-id="b3c66-122">(タイマー刻み) で、ジョブを実行して yarn アプリケーション用のタイムスタンプです。</span><span class="sxs-lookup"><span data-stu-id="b3c66-122">the timestamp (in ticks) for the yarn application executing the job.</span></span> <span data-ttu-id="b3c66-123">この値は、ユーザーによっては設定しないでである場合は無視されます。</span><span class="sxs-lookup"><span data-stu-id="b3c66-123">This value should not be set by the user and will be ignored if it is.</span></span></param>
        <param name="compileMode"><span data-ttu-id="b3c66-124">実行中に使用するジョブの特定のコンパイル モードです。</span><span class="sxs-lookup"><span data-stu-id="b3c66-124">the specific compilation mode for the job used during execution.</span></span> <span data-ttu-id="b3c66-125">送信中に指定されていない場合、サーバーは、最適なコンパイル モードを決定します。</span><span class="sxs-lookup"><span data-stu-id="b3c66-125">If this is not specified during submission, the server will determine the optimal compilation mode.</span></span> <span data-ttu-id="b3c66-126">使用可能な値が含まれます: 'セマンティック'、'Full'、'SingleBox'</span><span class="sxs-lookup"><span data-stu-id="b3c66-126">Possible values include: 'Semantic', 'Full', 'SingleBox'</span></span></param>
        <summary>
            <span data-ttu-id="b3c66-127">USqlJobProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b3c66-127">Initializes a new instance of the USqlJobProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AlgebraFilePath">
      <MemberSignature Language="C#" Value="public string AlgebraFilePath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AlgebraFilePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.AlgebraFilePath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AlgebraFilePath As String" />
      <MemberSignature Language="F#" Value="member this.AlgebraFilePath : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.AlgebraFilePath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="algebraFilePath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b3c66-128">ジョブが完了した後に、代数ファイルのパスを取得します。</span><span class="sxs-lookup"><span data-stu-id="b3c66-128">Gets the algebra file path after the job has completed</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompileMode">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.CompileMode&gt; CompileMode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.CompileMode&gt; CompileMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.CompileMode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CompileMode As Nullable(Of CompileMode)" />
      <MemberSignature Language="F#" Value="member this.CompileMode : Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.CompileMode&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.CompileMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="compileMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.CompileMode&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b3c66-129">実行中に使用するジョブの特定のコンパイル モードを取得します。</span><span class="sxs-lookup"><span data-stu-id="b3c66-129">Gets the specific compilation mode for the job used during execution.</span></span> <span data-ttu-id="b3c66-130">送信中に指定されていない場合、サーバーは、最適なコンパイル モードを決定します。</span><span class="sxs-lookup"><span data-stu-id="b3c66-130">If this is not specified during submission, the server will determine the optimal compilation mode.</span></span> <span data-ttu-id="b3c66-131">使用可能な値が含まれます: 'セマンティック'、'Full'、'SingleBox'</span><span class="sxs-lookup"><span data-stu-id="b3c66-131">Possible values include: 'Semantic', 'Full', 'SingleBox'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DebugData">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Analytics.Models.JobDataPath DebugData { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataLake.Analytics.Models.JobDataPath DebugData" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.DebugData" />
      <MemberSignature Language="VB.NET" Value="Public Property DebugData As JobDataPath" />
      <MemberSignature Language="F#" Value="member this.DebugData : Microsoft.Azure.Management.DataLake.Analytics.Models.JobDataPath with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.DebugData" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="debugData")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.JobDataPath</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b3c66-132">取得またはジョブを特定のデバッグ データの場所を設定します。</span><span class="sxs-lookup"><span data-stu-id="b3c66-132">Gets or sets the job specific debug data locations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Diagnostics">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.Diagnostics&gt; Diagnostics { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.Diagnostics&gt; Diagnostics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.Diagnostics" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Diagnostics As IList(Of Diagnostics)" />
      <MemberSignature Language="F#" Value="member this.Diagnostics : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.Diagnostics&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.Diagnostics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="diagnostics")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.Diagnostics&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b3c66-133">ジョブの診断を取得します。</span><span class="sxs-lookup"><span data-stu-id="b3c66-133">Gets the diagnostics for the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Resources">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobResource&gt; Resources { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobResource&gt; Resources" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.Resources" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Resources As IList(Of JobResource)" />
      <MemberSignature Language="F#" Value="member this.Resources : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobResource&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.Resources" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resources")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobResource&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b3c66-134">ジョブに必要なリソースの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="b3c66-134">Gets the list of resources that are required by the job</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RootProcessNodeId">
      <MemberSignature Language="C#" Value="public string RootProcessNodeId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RootProcessNodeId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.RootProcessNodeId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RootProcessNodeId As String" />
      <MemberSignature Language="F#" Value="member this.RootProcessNodeId : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.RootProcessNodeId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="rootProcessNodeId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b3c66-135">ジョブ マネージャーの調整ジョブの実行を識別する ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="b3c66-135">Gets the ID used to identify the job manager coordinating job execution.</span></span> <span data-ttu-id="b3c66-136">この値は、ユーザーによっては設定しないでである場合は無視されます。</span><span class="sxs-lookup"><span data-stu-id="b3c66-136">This value should not be set by the user and will be ignored if it is.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Statistics">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatistics Statistics { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatistics Statistics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.Statistics" />
      <MemberSignature Language="VB.NET" Value="Public Property Statistics As JobStatistics" />
      <MemberSignature Language="F#" Value="member this.Statistics : Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatistics with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.Statistics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="statistics")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatistics</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b3c66-137">取得または特定のジョブの統計を設定します。</span><span class="sxs-lookup"><span data-stu-id="b3c66-137">Gets or sets the job specific statistics.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalCompilationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; TotalCompilationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; TotalCompilationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.TotalCompilationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalCompilationTime As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.TotalCompilationTime : Nullable&lt;TimeSpan&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.TotalCompilationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="totalCompilationTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b3c66-138">このジョブは、コンパイルに費やされた時間の合計を取得します。</span><span class="sxs-lookup"><span data-stu-id="b3c66-138">Gets the total time this job spent compiling.</span></span> <span data-ttu-id="b3c66-139">この値は、ユーザーによっては設定しないでである場合は無視されます。</span><span class="sxs-lookup"><span data-stu-id="b3c66-139">This value should not be set by the user and will be ignored if it is.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalPauseTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; TotalPauseTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; TotalPauseTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.TotalPauseTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalPauseTime As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.TotalPauseTime : Nullable&lt;TimeSpan&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.TotalPauseTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="totalPauseTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b3c66-140">一時停止されたこのジョブの合計時間を取得します。</span><span class="sxs-lookup"><span data-stu-id="b3c66-140">Gets the total time this job spent paused.</span></span> <span data-ttu-id="b3c66-141">この値は、ユーザーによっては設定しないでである場合は無視されます。</span><span class="sxs-lookup"><span data-stu-id="b3c66-141">This value should not be set by the user and will be ignored if it is.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalQueuedTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; TotalQueuedTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; TotalQueuedTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.TotalQueuedTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalQueuedTime As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.TotalQueuedTime : Nullable&lt;TimeSpan&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.TotalQueuedTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="totalQueuedTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b3c66-142">キューに置かれたこのジョブの合計時間を取得します。</span><span class="sxs-lookup"><span data-stu-id="b3c66-142">Gets the total time this job spent queued.</span></span> <span data-ttu-id="b3c66-143">この値は、ユーザーによっては設定しないでである場合は無視されます。</span><span class="sxs-lookup"><span data-stu-id="b3c66-143">This value should not be set by the user and will be ignored if it is.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalRunningTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; TotalRunningTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; TotalRunningTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.TotalRunningTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalRunningTime As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.TotalRunningTime : Nullable&lt;TimeSpan&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.TotalRunningTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="totalRunningTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b3c66-144">このジョブの実行にかかった合計時間を取得します。</span><span class="sxs-lookup"><span data-stu-id="b3c66-144">Gets the total time this job spent executing.</span></span> <span data-ttu-id="b3c66-145">この値は、ユーザーによっては設定しないでである場合は無視されます。</span><span class="sxs-lookup"><span data-stu-id="b3c66-145">This value should not be set by the user and will be ignored if it is.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="uSqlJobProperties.Validate " />
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
            <span data-ttu-id="b3c66-146">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="b3c66-146">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b3c66-147">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b3c66-147">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="YarnApplicationId">
      <MemberSignature Language="C#" Value="public string YarnApplicationId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string YarnApplicationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.YarnApplicationId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property YarnApplicationId As String" />
      <MemberSignature Language="F#" Value="member this.YarnApplicationId : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.YarnApplicationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="yarnApplicationId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b3c66-148">ジョブの実行 yarn アプリケーションを識別するための ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="b3c66-148">Gets the ID used to identify the yarn application executing the job.</span></span> <span data-ttu-id="b3c66-149">この値は、ユーザーによっては設定しないでである場合は無視されます。</span><span class="sxs-lookup"><span data-stu-id="b3c66-149">This value should not be set by the user and will be ignored if it is.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="YarnApplicationTimeStamp">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; YarnApplicationTimeStamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; YarnApplicationTimeStamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.YarnApplicationTimeStamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property YarnApplicationTimeStamp As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.YarnApplicationTimeStamp : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.YarnApplicationTimeStamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="yarnApplicationTimeStamp")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b3c66-150">ジョブの実行、yarn アプリケーションのタイムスタンプ (タイマー刻み) を取得します。</span><span class="sxs-lookup"><span data-stu-id="b3c66-150">Gets the timestamp (in ticks) for the yarn application executing the job.</span></span> <span data-ttu-id="b3c66-151">この値は、ユーザーによっては設定しないでである場合は無視されます。</span><span class="sxs-lookup"><span data-stu-id="b3c66-151">This value should not be set by the user and will be ignored if it is.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>