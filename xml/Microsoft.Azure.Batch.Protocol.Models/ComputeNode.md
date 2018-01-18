<Type Name="ComputeNode" FullName="Microsoft.Azure.Batch.Protocol.Models.ComputeNode">
  <TypeSignature Language="C#" Value="public class ComputeNode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ComputeNode extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.ComputeNode" />
  <TypeSignature Language="VB.NET" Value="Public Class ComputeNode" />
  <TypeSignature Language="F#" Value="type ComputeNode = class" />
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
            <span data-ttu-id="0091f-101">バッチ サービスでコンピューティング ノードです。</span><span class="sxs-lookup"><span data-stu-id="0091f-101">A compute node in the Batch service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ComputeNode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.#ctor" />
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
            <span data-ttu-id="0091f-102">ComputeNode クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0091f-102">Initializes a new instance of the ComputeNode class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ComputeNode (string id = null, string url = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState&gt; state = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.SchedulingState&gt; schedulingState = null, Nullable&lt;DateTime&gt; stateTransitionTime = null, Nullable&lt;DateTime&gt; lastBootTime = null, Nullable&lt;DateTime&gt; allocationTime = null, string ipAddress = null, string affinityId = null, string vmSize = null, Nullable&lt;int&gt; totalTasksRun = null, Nullable&lt;int&gt; runningTasksCount = null, Nullable&lt;int&gt; totalTasksSucceeded = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskInformation&gt; recentTasks = null, Microsoft.Azure.Batch.Protocol.Models.StartTask startTask = null, Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation startTaskInfo = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; certificateReferences = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError&gt; errors = null, Nullable&lt;bool&gt; isDedicated = null, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration endpointConfiguration = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string url, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState&gt; state, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.SchedulingState&gt; schedulingState, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; stateTransitionTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastBootTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; allocationTime, string ipAddress, string affinityId, string vmSize, valuetype System.Nullable`1&lt;int32&gt; totalTasksRun, valuetype System.Nullable`1&lt;int32&gt; runningTasksCount, valuetype System.Nullable`1&lt;int32&gt; totalTasksSucceeded, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskInformation&gt; recentTasks, class Microsoft.Azure.Batch.Protocol.Models.StartTask startTask, class Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation startTaskInfo, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; certificateReferences, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError&gt; errors, valuetype System.Nullable`1&lt;bool&gt; isDedicated, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration endpointConfiguration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.#ctor(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState},System.Nullable{Microsoft.Azure.Batch.Protocol.Models.SchedulingState},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.TaskInformation},Microsoft.Azure.Batch.Protocol.Models.StartTask,Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.CertificateReference},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError},System.Nullable{System.Boolean},Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.ComputeNode : string * string * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState&gt; * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.SchedulingState&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * string * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskInformation&gt; * Microsoft.Azure.Batch.Protocol.Models.StartTask * Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError&gt; * Nullable&lt;bool&gt; * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration -&gt; Microsoft.Azure.Batch.Protocol.Models.ComputeNode" Usage="new Microsoft.Azure.Batch.Protocol.Models.ComputeNode (id, url, state, schedulingState, stateTransitionTime, lastBootTime, allocationTime, ipAddress, affinityId, vmSize, totalTasksRun, runningTasksCount, totalTasksSucceeded, recentTasks, startTask, startTaskInfo, certificateReferences, errors, isDedicated, endpointConfiguration)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="url" Type="System.String" />
        <Parameter Name="state" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState&gt;" />
        <Parameter Name="schedulingState" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.SchedulingState&gt;" />
        <Parameter Name="stateTransitionTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="lastBootTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="allocationTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="ipAddress" Type="System.String" />
        <Parameter Name="affinityId" Type="System.String" />
        <Parameter Name="vmSize" Type="System.String" />
        <Parameter Name="totalTasksRun" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="runningTasksCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="totalTasksSucceeded" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="recentTasks" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskInformation&gt;" />
        <Parameter Name="startTask" Type="Microsoft.Azure.Batch.Protocol.Models.StartTask" />
        <Parameter Name="startTaskInfo" Type="Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation" />
        <Parameter Name="certificateReferences" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt;" />
        <Parameter Name="errors" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError&gt;" />
        <Parameter Name="isDedicated" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="endpointConfiguration" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="0091f-103">コンピューティング ノードの ID。</span><span class="sxs-lookup"><span data-stu-id="0091f-103">The ID of the compute node.</span></span></param>
        <param name="url"><span data-ttu-id="0091f-104">コンピューティング ノードの URL です。</span><span class="sxs-lookup"><span data-stu-id="0091f-104">The URL of the compute node.</span></span></param>
        <param name="state"><span data-ttu-id="0091f-105">コンピューティング ノードの現在の状態。</span><span class="sxs-lookup"><span data-stu-id="0091f-105">The current state of the compute node.</span></span></param>
        <param name="schedulingState"><span data-ttu-id="0091f-106">コンピューティング ノードがタスクのスケジュール設定に使用できるかどうか。</span><span class="sxs-lookup"><span data-stu-id="0091f-106">Whether the compute node is available for task scheduling.</span></span></param>
        <param name="stateTransitionTime"><span data-ttu-id="0091f-107">その現在の状態、コンピューティング ノードになった時刻。</span><span class="sxs-lookup"><span data-stu-id="0091f-107">The time at which the compute node entered its current state.</span></span></param>
        <param name="lastBootTime"><span data-ttu-id="0091f-108">コンピューティング ノードが開始された時刻。</span><span class="sxs-lookup"><span data-stu-id="0091f-108">The time at which the compute node was started.</span></span></param>
        <param name="allocationTime"><span data-ttu-id="0091f-109">この計算ノードがプールに割り当てられ時間。</span><span class="sxs-lookup"><span data-stu-id="0091f-109">The time at which this compute node was allocated to the pool.</span></span></param>
        <param name="ipAddress"><span data-ttu-id="0091f-110">その他のコンピューティング ノードがこの計算ノードとの通信に使用できる IP アドレス。</span><span class="sxs-lookup"><span data-stu-id="0091f-110">The IP address that other compute nodes can use to communicate with this compute node.</span></span></param>
        <param name="affinityId"><span data-ttu-id="0091f-111">渡すことができるスケジュール タスクを要求できるタスクを追加するときにこのノードの識別子です。</span><span class="sxs-lookup"><span data-stu-id="0091f-111">An identifier which can be passed when adding a task to request that the task be scheduled on this node.</span></span></param>
        <param name="vmSize"><span data-ttu-id="0091f-112">コンピューティング ノードをホストする仮想マシンのサイズ。</span><span class="sxs-lookup"><span data-stu-id="0091f-112">The size of the virtual machine hosting the compute node.</span></span></param>
        <param name="totalTasksRun"><span data-ttu-id="0091f-113">コンピューティング ノードで完了したジョブ タスクの合計数。</span><span class="sxs-lookup"><span data-stu-id="0091f-113">The total number of job tasks completed on the compute node.</span></span> <span data-ttu-id="0091f-114">これには、ジョブ マネージャー タスクと通常のタスクがジョブの準備、ジョブのリリースまたは開始タスクではなくが含まれます。</span><span class="sxs-lookup"><span data-stu-id="0091f-114">This includes Job Manager tasks and normal tasks, but not Job Preparation, Job Release or Start tasks.</span></span></param>
        <param name="runningTasksCount"><span data-ttu-id="0091f-115">コンピューティング ノードでは、実行中のジョブのタスクの合計数。</span><span class="sxs-lookup"><span data-stu-id="0091f-115">The total number of currently running job tasks on the compute node.</span></span> <span data-ttu-id="0091f-116">これには、ジョブ マネージャー タスクと通常のタスクがジョブの準備、ジョブのリリースまたは開始タスクではなくが含まれます。</span><span class="sxs-lookup"><span data-stu-id="0091f-116">This includes Job Manager tasks and normal tasks, but not Job Preparation, Job Release or Start tasks.</span></span></param>
        <param name="totalTasksSucceeded"><span data-ttu-id="0091f-117">正常に (exitCode 0) が完了したジョブのタスクの合計数、コンピューティング ノード上。</span><span class="sxs-lookup"><span data-stu-id="0091f-117">The total number of job tasks which completed successfully (with exitCode 0) on the compute node.</span></span>
            <span data-ttu-id="0091f-118">これには、ジョブ マネージャー タスクと通常のタスクがジョブの準備、ジョブのリリースまたは開始タスクではなくが含まれます。</span><span class="sxs-lookup"><span data-stu-id="0091f-118">This includes Job Manager tasks and normal tasks, but not Job Preparation, Job Release or Start tasks.</span></span></param>
        <param name="recentTasks"><span data-ttu-id="0091f-119">状態が最近変更されたタスクの一覧。</span><span class="sxs-lookup"><span data-stu-id="0091f-119">A list of tasks whose state has recently changed.</span></span></param>
        <param name="startTask"><span data-ttu-id="0091f-120">コンピューティング ノードで、プールに参加を実行する指定されたタスク。</span><span class="sxs-lookup"><span data-stu-id="0091f-120">The task specified to run on the compute node as it joins the pool.</span></span></param>
        <param name="startTaskInfo"><span data-ttu-id="0091f-121">コンピューティング ノードで、開始タスクの実行に関するランタイム情報。</span><span class="sxs-lookup"><span data-stu-id="0091f-121">Runtime information about the execution of the start task on the compute node.</span></span></param>
        <param name="certificateReferences"><span data-ttu-id="0091f-122">コンピューティング ノードにインストールされている証明書の一覧です。</span><span class="sxs-lookup"><span data-stu-id="0091f-122">The list of certificates installed on the compute node.</span></span></param>
        <param name="errors"><span data-ttu-id="0091f-123">コンピューティング ノードで現在発生しているエラーの一覧。</span><span class="sxs-lookup"><span data-stu-id="0091f-123">The list of errors that are currently being encountered by the compute node.</span></span></param>
        <param name="isDedicated"><span data-ttu-id="0091f-124">この計算ノードが専用ノードかどうか。</span><span class="sxs-lookup"><span data-stu-id="0091f-124">Whether this compute node is a dedicated node.</span></span> <span data-ttu-id="0091f-125">False の場合、優先度の低いノードです。</span><span class="sxs-lookup"><span data-stu-id="0091f-125">If false, the node is a low-priority node.</span></span></param>
        <param name="endpointConfiguration"><span data-ttu-id="0091f-126">コンピューティング ノードのエンドポイント構成。</span><span class="sxs-lookup"><span data-stu-id="0091f-126">The endpoint configuration for the compute node.</span></span></param>
        <summary>
            <span data-ttu-id="0091f-127">ComputeNode クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0091f-127">Initializes a new instance of the ComputeNode class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AffinityId">
      <MemberSignature Language="C#" Value="public string AffinityId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AffinityId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.AffinityId" />
      <MemberSignature Language="VB.NET" Value="Public Property AffinityId As String" />
      <MemberSignature Language="F#" Value="member this.AffinityId : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.AffinityId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="affinityId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0091f-128">取得または設定の識別子をこのノードでタスクをスケジュールすることを要求するタスクを追加するときに渡すことができます。</span><span class="sxs-lookup"><span data-stu-id="0091f-128">Gets or sets an identifier which can be passed when adding a task to request that the task be scheduled on this node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="0091f-129">これはソフト アフィニティだけであることに注意してください。</span><span class="sxs-lookup"><span data-stu-id="0091f-129">Note that this is just a soft affinity.</span></span> <span data-ttu-id="0091f-130">ターゲット ノードがビジー状態、またはタスクのスケジュール時に使用できない、タスクがスケジュールされる他の場所。</span><span class="sxs-lookup"><span data-stu-id="0091f-130">If the target node is busy or unavailable at the time the task is scheduled, then the task will be scheduled elsewhere.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AllocationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; AllocationTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; AllocationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.AllocationTime" />
      <MemberSignature Language="VB.NET" Value="Public Property AllocationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.AllocationTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.AllocationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="allocationTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0091f-131">取得またはプールにこのコンピューティング ノードが割り当てられた時間を設定します。</span><span class="sxs-lookup"><span data-stu-id="0091f-131">Gets or sets the time at which this compute node was allocated to the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateReferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; CertificateReferences { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; CertificateReferences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.CertificateReferences" />
      <MemberSignature Language="VB.NET" Value="Public Property CertificateReferences As IList(Of CertificateReference)" />
      <MemberSignature Language="F#" Value="member this.CertificateReferences : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.CertificateReferences" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="certificateReferences")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0091f-132">取得または計算ノードにインストールされている証明書の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="0091f-132">Gets or sets the list of certificates installed on the compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="0091f-133">Windows では、ノードを計算するため、バッチ サービスは、場所と指定された証明書ストアに証明書をインストールします。</span><span class="sxs-lookup"><span data-stu-id="0091f-133">For Windows compute nodes, the Batch service installs the certificates to the specified certificate store and location.</span></span> <span data-ttu-id="0091f-134">Linux 計算ノードでは、証明書は、タスクの作業ディレクトリと変数 AZ_BATCH_CERTIFICATES_DIR がこの場所にクエリするタスクに指定された環境の内部ディレクトリに保存されます。</span><span class="sxs-lookup"><span data-stu-id="0091f-134">For Linux compute nodes, the certificates are stored in a directory inside the task working directory and an environment variable AZ_BATCH_CERTIFICATES_DIR is supplied to the task to query for this location.</span></span> <span data-ttu-id="0091f-135">'RemoteUser' の可視性を持つ証明書は、'certs' ディレクトリは、ユーザーのホーム ディレクトリに作成 (など/home/{ユーザー名}/certs) および証明書はそのディレクトリに配置します。</span><span class="sxs-lookup"><span data-stu-id="0091f-135">For certificates with visibility of 'remoteUser', a 'certs' directory is created in the user's home directory (e.g., /home/{user-name}/certs) and certificates are placed in that directory.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EndpointConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration EndpointConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration EndpointConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.EndpointConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property EndpointConfiguration As ComputeNodeEndpointConfiguration" />
      <MemberSignature Language="F#" Value="member this.EndpointConfiguration : Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.EndpointConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="endpointConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0091f-136">取得または計算ノードのエンドポイント構成を設定します。</span><span class="sxs-lookup"><span data-stu-id="0091f-136">Gets or sets the endpoint configuration for the compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Errors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError&gt; Errors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError&gt; Errors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.Errors" />
      <MemberSignature Language="VB.NET" Value="Public Property Errors As IList(Of ComputeNodeError)" />
      <MemberSignature Language="F#" Value="member this.Errors : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.Errors" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="errors")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0091f-137">取得または計算ノードで現在発生しているエラーの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="0091f-137">Gets or sets the list of errors that are currently being encountered by the compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0091f-138">取得または計算ノードの ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="0091f-138">Gets or sets the ID of the compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="0091f-139">プールに追加されるすべてのノードには、一意の ID が割り当てられます</span><span class="sxs-lookup"><span data-stu-id="0091f-139">Every node that is added to a pool is assigned a unique ID.</span></span>
            <span data-ttu-id="0091f-140">ノードは、プールからを削除するたびにすべてのローカル ファイルが削除され、ID が解放され、新しいノードで再利用できます。</span><span class="sxs-lookup"><span data-stu-id="0091f-140">Whenever a node is removed from a pool, all of its local files are deleted, and the ID is reclaimed and could be reused for new nodes.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="IpAddress">
      <MemberSignature Language="C#" Value="public string IpAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IpAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.IpAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property IpAddress As String" />
      <MemberSignature Language="F#" Value="member this.IpAddress : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.IpAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ipAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0091f-141">取得またはその他のコンピューティング ノードがこの計算ノードとの通信に使用できる IP アドレスを設定します。</span><span class="sxs-lookup"><span data-stu-id="0091f-141">Gets or sets the IP address that other compute nodes can use to communicate with this compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="0091f-142">プールに追加されるすべてのノードには、一意の IP アドレスが割り当てられます。</span><span class="sxs-lookup"><span data-stu-id="0091f-142">Every node that is added to a pool is assigned a unique IP address.</span></span>
            <span data-ttu-id="0091f-143">ノードは、プールからを削除するたびにすべてのローカル ファイルが削除され、IP アドレスが解放され、新しいノードで再利用できます。</span><span class="sxs-lookup"><span data-stu-id="0091f-143">Whenever a node is removed from a pool, all of its local files are deleted, and the IP address is reclaimed and could be reused for new nodes.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDedicated">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsDedicated { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsDedicated" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.IsDedicated" />
      <MemberSignature Language="VB.NET" Value="Public Property IsDedicated As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsDedicated : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.IsDedicated" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isDedicated")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0091f-144">取得またはこのコンピューティング ノードは、専用のノードかどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="0091f-144">Gets or sets whether this compute node is a dedicated node.</span></span> <span data-ttu-id="0091f-145">False の場合、優先度の低いノードです。</span><span class="sxs-lookup"><span data-stu-id="0091f-145">If false, the node is a low-priority node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastBootTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastBootTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastBootTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.LastBootTime" />
      <MemberSignature Language="VB.NET" Value="Public Property LastBootTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastBootTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.LastBootTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastBootTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0091f-146">取得または計算ノードを開始した時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="0091f-146">Gets or sets the time at which the compute node was started.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="0091f-147">このプロパティは、ノードの状態が使用できない場合に存在していない可能性があります。</span><span class="sxs-lookup"><span data-stu-id="0091f-147">This property may not be present if the node state is unusable.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RecentTasks">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskInformation&gt; RecentTasks { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskInformation&gt; RecentTasks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.RecentTasks" />
      <MemberSignature Language="VB.NET" Value="Public Property RecentTasks As IList(Of TaskInformation)" />
      <MemberSignature Language="F#" Value="member this.RecentTasks : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskInformation&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.RecentTasks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recentTasks")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskInformation&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0091f-148">取得または状態が最近変更されたタスクの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="0091f-148">Gets or sets a list of tasks whose state has recently changed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="0091f-149">このプロパティは、プールに割り当てられているために、このノード上には、少なくとも 1 つのタスクが実行が場合にのみ存在します。</span><span class="sxs-lookup"><span data-stu-id="0091f-149">This property is present only if at least one task has run on this node since it was assigned to the pool.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RunningTasksCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; RunningTasksCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; RunningTasksCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.RunningTasksCount" />
      <MemberSignature Language="VB.NET" Value="Public Property RunningTasksCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.RunningTasksCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.RunningTasksCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="runningTasksCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0091f-150">取得または計算ノードでは、実行中のジョブのタスクの合計数を設定します。</span><span class="sxs-lookup"><span data-stu-id="0091f-150">Gets or sets the total number of currently running job tasks on the compute node.</span></span> <span data-ttu-id="0091f-151">これには、ジョブ マネージャー タスクと通常のタスクがジョブの準備、ジョブのリリースまたは開始タスクではなくが含まれます。</span><span class="sxs-lookup"><span data-stu-id="0091f-151">This includes Job Manager tasks and normal tasks, but not Job Preparation, Job Release or Start tasks.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SchedulingState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.SchedulingState&gt; SchedulingState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.SchedulingState&gt; SchedulingState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.SchedulingState" />
      <MemberSignature Language="VB.NET" Value="Public Property SchedulingState As Nullable(Of SchedulingState)" />
      <MemberSignature Language="F#" Value="member this.SchedulingState : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.SchedulingState&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.SchedulingState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="schedulingState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.SchedulingState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0091f-152">取得または計算ノードがタスクのスケジュール設定に使用できるかどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="0091f-152">Gets or sets whether the compute node is available for task scheduling.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="0091f-153">使用可能な値が含まれます: 'enabled'、'disabled'</span><span class="sxs-lookup"><span data-stu-id="0091f-153">Possible values include: 'enabled', 'disabled'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.StartTask StartTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.StartTask StartTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.StartTask" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTask As StartTask" />
      <MemberSignature Language="F#" Value="member this.StartTask : Microsoft.Azure.Batch.Protocol.Models.StartTask with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.StartTask" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startTask")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.StartTask</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0091f-154">取得または計算ノードで、プールに参加を実行する指定されたタスクを設定します。</span><span class="sxs-lookup"><span data-stu-id="0091f-154">Gets or sets the task specified to run on the compute node as it joins the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTaskInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation StartTaskInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation StartTaskInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.StartTaskInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTaskInfo As StartTaskInformation" />
      <MemberSignature Language="F#" Value="member this.StartTaskInfo : Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.StartTaskInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startTaskInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0091f-155">取得または計算ノードで、開始タスクの実行に関するランタイム情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="0091f-155">Gets or sets runtime information about the execution of the start task on the compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState&gt; State { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState&gt; State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.State" />
      <MemberSignature Language="VB.NET" Value="Public Property State As Nullable(Of ComputeNodeState)" />
      <MemberSignature Language="F#" Value="member this.State : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0091f-156">取得または計算ノードの現在の状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="0091f-156">Gets or sets the current state of the compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="0091f-157">優先度の低いノードが占有されています。</span><span class="sxs-lookup"><span data-stu-id="0091f-157">The low-priority node has been preempted.</span></span> <span data-ttu-id="0091f-158">別のノードが利用可能になったら、切り替えだった場合、ノード上で実行されているタスクを再スケジュールされます。</span><span class="sxs-lookup"><span data-stu-id="0091f-158">Tasks which were running on the node when it was pre-empted will be rescheduled when another node becomes available.</span></span> <span data-ttu-id="0091f-159">使用可能な値が含まれます: 'アイドル'、'再起動中'、'再イメージ化'、'実行中'、'使用不可'、'作成中'、'開始'、'waitingForStartTask'、'startTaskFailed'、'unknown'、'leavingPool'、'オフライン'、'割り込ま'</span><span class="sxs-lookup"><span data-stu-id="0091f-159">Possible values include: 'idle', 'rebooting', 'reimaging', 'running', 'unusable', 'creating', 'starting', 'waitingForStartTask', 'startTaskFailed', 'unknown', 'leavingPool', 'offline', 'preempted'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StateTransitionTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.StateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StateTransitionTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.StateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="stateTransitionTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0091f-160">取得または計算ノードが、現在の状態を入力する時間を設定します。</span><span class="sxs-lookup"><span data-stu-id="0091f-160">Gets or sets the time at which the compute node entered its current state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalTasksRun">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TotalTasksRun { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TotalTasksRun" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.TotalTasksRun" />
      <MemberSignature Language="VB.NET" Value="Public Property TotalTasksRun As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TotalTasksRun : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.TotalTasksRun" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="totalTasksRun")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0091f-161">取得または計算ノードで完了したジョブ タスクの合計数を設定します。</span><span class="sxs-lookup"><span data-stu-id="0091f-161">Gets or sets the total number of job tasks completed on the compute node.</span></span> <span data-ttu-id="0091f-162">これには、ジョブ マネージャー タスクと通常のタスクがジョブの準備、ジョブのリリースまたは開始タスクではなくが含まれます。</span><span class="sxs-lookup"><span data-stu-id="0091f-162">This includes Job Manager tasks and normal tasks, but not Job Preparation, Job Release or Start tasks.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalTasksSucceeded">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TotalTasksSucceeded { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TotalTasksSucceeded" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.TotalTasksSucceeded" />
      <MemberSignature Language="VB.NET" Value="Public Property TotalTasksSucceeded As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TotalTasksSucceeded : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.TotalTasksSucceeded" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="totalTasksSucceeded")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0091f-163">取得または設定を正常に (exitCode 0) が完了したジョブのタスクの合計数、コンピューティング ノード上。</span><span class="sxs-lookup"><span data-stu-id="0091f-163">Gets or sets the total number of job tasks which completed successfully (with exitCode 0) on the compute node.</span></span> <span data-ttu-id="0091f-164">これには、ジョブ マネージャー タスクと通常のタスクがジョブの準備、ジョブのリリースまたは開始タスクではなくが含まれます。</span><span class="sxs-lookup"><span data-stu-id="0091f-164">This includes Job Manager tasks and normal tasks, but not Job Preparation, Job Release or Start tasks.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.Url" />
      <MemberSignature Language="VB.NET" Value="Public Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.Url" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="url")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0091f-165">取得または計算ノードの URL を設定します。</span><span class="sxs-lookup"><span data-stu-id="0091f-165">Gets or sets the URL of the compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="computeNode.Validate " />
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
            <span data-ttu-id="0091f-166">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="0091f-166">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="0091f-167">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0091f-167">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VmSize">
      <MemberSignature Language="C#" Value="public string VmSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VmSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.VmSize" />
      <MemberSignature Language="VB.NET" Value="Public Property VmSize As String" />
      <MemberSignature Language="F#" Value="member this.VmSize : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.VmSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="vmSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0091f-168">取得または計算ノードをホストする仮想マシンのサイズを設定します。</span><span class="sxs-lookup"><span data-stu-id="0091f-168">Gets or sets the size of the virtual machine hosting the compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="0091f-169">クラウド サービス プール (プール cloudServiceConfiguration で作成された) の仮想マシンの利用可能なサイズについては、クラウド サービス (http://azure.microsoft.com/documentation/articles/cloud-services-sizes-specs/) のサイズを参照してください。</span><span class="sxs-lookup"><span data-stu-id="0091f-169">For information about available sizes of virtual machines for Cloud Services pools (pools created with cloudServiceConfiguration), see Sizes for Cloud Services (http://azure.microsoft.com/documentation/articles/cloud-services-sizes-specs/).</span></span>
            <span data-ttu-id="0091f-170">バッチには、ExtraSmall、A1V2 A2V2 を除くすべてのクラウド サービス VM サイズがサポートしています。</span><span class="sxs-lookup"><span data-stu-id="0091f-170">Batch supports all Cloud Services VM sizes except ExtraSmall, A1V2 and A2V2.</span></span> <span data-ttu-id="0091f-171">(プール virtualMachineConfiguration で作成した) 仮想マシンのマーケットプ レースからイメージを使用するプールの利用可能な VM サイズについては (Linux) (https://azure.microsoft.com/documentation/articles/ の仮想マシンのサイズを参照してください。仮想マシンの linux-サイズ/) または仮想マシン (Windows) (https://azure.microsoft.com/documentation/articles/virtual-machines-windows-sizes/) のサイズ。</span><span class="sxs-lookup"><span data-stu-id="0091f-171">For information about available VM sizes for pools using images from the Virtual Machines Marketplace (pools created with virtualMachineConfiguration) see Sizes for Virtual Machines (Linux) (https://azure.microsoft.com/documentation/articles/virtual-machines-linux-sizes/) or Sizes for Virtual Machines (Windows) (https://azure.microsoft.com/documentation/articles/virtual-machines-windows-sizes/).</span></span>
            <span data-ttu-id="0091f-172">バッチには、STANDARD_A0 と premium storage (STANDARD_GS、STANDARD_DS、および STANDARD_DSV2 シリーズ) でそれらを除くすべての Azure VM サイズがサポートしています。</span><span class="sxs-lookup"><span data-stu-id="0091f-172">Batch supports all Azure VM sizes except STANDARD_A0 and those with premium storage (STANDARD_GS, STANDARD_DS, and STANDARD_DSV2 series).</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>