<Type Name="CloudPool" FullName="Microsoft.Azure.Batch.Protocol.Models.CloudPool">
  <TypeSignature Language="C#" Value="public class CloudPool" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CloudPool extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.CloudPool" />
  <TypeSignature Language="VB.NET" Value="Public Class CloudPool" />
  <TypeSignature Language="F#" Value="type CloudPool = class" />
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
            <span data-ttu-id="34683-101">Azure Batch のサービスにプールします。</span><span class="sxs-lookup"><span data-stu-id="34683-101">A pool in the Azure Batch service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudPool ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.CloudPool.#ctor" />
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
            <span data-ttu-id="34683-102">CloudPool クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="34683-102">Initializes a new instance of the CloudPool class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudPool (string id = null, string displayName = null, string url = null, string eTag = null, Nullable&lt;DateTime&gt; lastModified = null, Nullable&lt;DateTime&gt; creationTime = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.PoolState&gt; state = null, Nullable&lt;DateTime&gt; stateTransitionTime = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.AllocationState&gt; allocationState = null, Nullable&lt;DateTime&gt; allocationStateTransitionTime = null, string vmSize = null, Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration cloudServiceConfiguration = null, Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration virtualMachineConfiguration = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResizeError&gt; resizeErrors = null, Nullable&lt;int&gt; currentDedicatedNodes = null, Nullable&lt;int&gt; currentLowPriorityNodes = null, Nullable&lt;int&gt; targetDedicatedNodes = null, Nullable&lt;int&gt; targetLowPriorityNodes = null, Nullable&lt;bool&gt; enableAutoScale = null, string autoScaleFormula = null, Nullable&lt;TimeSpan&gt; autoScaleEvaluationInterval = null, Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun autoScaleRun = null, Nullable&lt;bool&gt; enableInterNodeCommunication = null, Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration networkConfiguration = null, Microsoft.Azure.Batch.Protocol.Models.StartTask startTask = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; certificateReferences = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; applicationPackageReferences = null, System.Collections.Generic.IList&lt;string&gt; applicationLicenses = null, Nullable&lt;int&gt; maxTasksPerNode = null, Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy taskSchedulingPolicy = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.UserAccount&gt; userAccounts = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; metadata = null, Microsoft.Azure.Batch.Protocol.Models.PoolStatistics stats = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string displayName, string url, string eTag, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastModified, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; creationTime, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.PoolState&gt; state, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; stateTransitionTime, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.AllocationState&gt; allocationState, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; allocationStateTransitionTime, string vmSize, class Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration cloudServiceConfiguration, class Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration virtualMachineConfiguration, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ResizeError&gt; resizeErrors, valuetype System.Nullable`1&lt;int32&gt; currentDedicatedNodes, valuetype System.Nullable`1&lt;int32&gt; currentLowPriorityNodes, valuetype System.Nullable`1&lt;int32&gt; targetDedicatedNodes, valuetype System.Nullable`1&lt;int32&gt; targetLowPriorityNodes, valuetype System.Nullable`1&lt;bool&gt; enableAutoScale, string autoScaleFormula, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; autoScaleEvaluationInterval, class Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun autoScaleRun, valuetype System.Nullable`1&lt;bool&gt; enableInterNodeCommunication, class Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration networkConfiguration, class Microsoft.Azure.Batch.Protocol.Models.StartTask startTask, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; certificateReferences, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; applicationPackageReferences, class System.Collections.Generic.IList`1&lt;string&gt; applicationLicenses, valuetype System.Nullable`1&lt;int32&gt; maxTasksPerNode, class Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy taskSchedulingPolicy, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.UserAccount&gt; userAccounts, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; metadata, class Microsoft.Azure.Batch.Protocol.Models.PoolStatistics stats) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.CloudPool.#ctor(System.String,System.String,System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{Microsoft.Azure.Batch.Protocol.Models.PoolState},System.Nullable{System.DateTime},System.Nullable{Microsoft.Azure.Batch.Protocol.Models.AllocationState},System.Nullable{System.DateTime},System.String,Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration,Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration,System.Nullable{System.TimeSpan},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.ResizeError},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Boolean},System.String,System.Nullable{System.TimeSpan},Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun,System.Nullable{System.Boolean},Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration,Microsoft.Azure.Batch.Protocol.Models.StartTask,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.CertificateReference},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference},System.Collections.Generic.IList{System.String},System.Nullable{System.Int32},Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.UserAccount},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.MetadataItem},Microsoft.Azure.Batch.Protocol.Models.PoolStatistics)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.CloudPool : string * string * string * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.PoolState&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.AllocationState&gt; * Nullable&lt;DateTime&gt; * string * Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration * Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration * Nullable&lt;TimeSpan&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResizeError&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;bool&gt; * string * Nullable&lt;TimeSpan&gt; * Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun * Nullable&lt;bool&gt; * Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration * Microsoft.Azure.Batch.Protocol.Models.StartTask * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;int&gt; * Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.UserAccount&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; * Microsoft.Azure.Batch.Protocol.Models.PoolStatistics -&gt; Microsoft.Azure.Batch.Protocol.Models.CloudPool" Usage="new Microsoft.Azure.Batch.Protocol.Models.CloudPool (id, displayName, url, eTag, lastModified, creationTime, state, stateTransitionTime, allocationState, allocationStateTransitionTime, vmSize, cloudServiceConfiguration, virtualMachineConfiguration, resizeTimeout, resizeErrors, currentDedicatedNodes, currentLowPriorityNodes, targetDedicatedNodes, targetLowPriorityNodes, enableAutoScale, autoScaleFormula, autoScaleEvaluationInterval, autoScaleRun, enableInterNodeCommunication, networkConfiguration, startTask, certificateReferences, applicationPackageReferences, applicationLicenses, maxTasksPerNode, taskSchedulingPolicy, userAccounts, metadata, stats)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="url" Type="System.String" />
        <Parameter Name="eTag" Type="System.String" />
        <Parameter Name="lastModified" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="creationTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="state" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.PoolState&gt;" />
        <Parameter Name="stateTransitionTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="allocationState" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.AllocationState&gt;" />
        <Parameter Name="allocationStateTransitionTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="vmSize" Type="System.String" />
        <Parameter Name="cloudServiceConfiguration" Type="Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration" />
        <Parameter Name="virtualMachineConfiguration" Type="Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="resizeErrors" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResizeError&gt;" />
        <Parameter Name="currentDedicatedNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentLowPriorityNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="targetDedicatedNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="targetLowPriorityNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="enableAutoScale" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="autoScaleFormula" Type="System.String" />
        <Parameter Name="autoScaleEvaluationInterval" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="autoScaleRun" Type="Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun" />
        <Parameter Name="enableInterNodeCommunication" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="networkConfiguration" Type="Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration" />
        <Parameter Name="startTask" Type="Microsoft.Azure.Batch.Protocol.Models.StartTask" />
        <Parameter Name="certificateReferences" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt;" />
        <Parameter Name="applicationPackageReferences" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt;" />
        <Parameter Name="applicationLicenses" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="maxTasksPerNode" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="taskSchedulingPolicy" Type="Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy" />
        <Parameter Name="userAccounts" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.UserAccount&gt;" />
        <Parameter Name="metadata" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt;" />
        <Parameter Name="stats" Type="Microsoft.Azure.Batch.Protocol.Models.PoolStatistics" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="34683-103">アカウント内のプールを一意に識別する文字列。</span><span class="sxs-lookup"><span data-stu-id="34683-103">A string that uniquely identifies the pool within the account.</span></span></param>
        <param name="displayName"><span data-ttu-id="34683-104">プールの表示名。</span><span class="sxs-lookup"><span data-stu-id="34683-104">The display name for the pool.</span></span></param>
        <param name="url"><span data-ttu-id="34683-105">プールの URL です。</span><span class="sxs-lookup"><span data-stu-id="34683-105">The URL of the pool.</span></span></param>
        <param name="eTag"><span data-ttu-id="34683-106">プールの ETag です。</span><span class="sxs-lookup"><span data-stu-id="34683-106">The ETag of the pool.</span></span></param>
        <param name="lastModified"><span data-ttu-id="34683-107">最終更新時刻プールをします。</span><span class="sxs-lookup"><span data-stu-id="34683-107">The last modified time of the pool.</span></span></param>
        <param name="creationTime"><span data-ttu-id="34683-108">プールの作成時間。</span><span class="sxs-lookup"><span data-stu-id="34683-108">The creation time of the pool.</span></span></param>
        <param name="state"><span data-ttu-id="34683-109">プールの現在の状態。</span><span class="sxs-lookup"><span data-stu-id="34683-109">The current state of the pool.</span></span></param>
        <param name="stateTransitionTime"><span data-ttu-id="34683-110">現在の状態、プールになった時刻。</span><span class="sxs-lookup"><span data-stu-id="34683-110">The time at which the pool entered its current state.</span></span></param>
        <param name="allocationState"><span data-ttu-id="34683-111">プールのサイズを変更するかどうか。</span><span class="sxs-lookup"><span data-stu-id="34683-111">Whether the pool is resizing.</span></span></param>
        <param name="allocationStateTransitionTime"><span data-ttu-id="34683-112">現在の割り当て状態、プールになった時刻。</span><span class="sxs-lookup"><span data-stu-id="34683-112">The time at which the pool entered its current allocation state.</span></span></param>
        <param name="vmSize"><span data-ttu-id="34683-113">プール内の仮想マシンのサイズ。</span><span class="sxs-lookup"><span data-stu-id="34683-113">The size of virtual machines in the pool.</span></span> <span data-ttu-id="34683-114">プール内の仮想マシンのサイズはすべて同じです。</span><span class="sxs-lookup"><span data-stu-id="34683-114">All virtual machines in a pool are the same size.</span></span></param>
        <param name="cloudServiceConfiguration"><span data-ttu-id="34683-115">プールのクラウドサービス構成。</span><span class="sxs-lookup"><span data-stu-id="34683-115">The cloud service configuration for the pool.</span></span></param>
        <param name="virtualMachineConfiguration"><span data-ttu-id="34683-116">プールの仮想マシン構成。</span><span class="sxs-lookup"><span data-stu-id="34683-116">The virtual machine configuration for the pool.</span></span></param>
        <param name="resizeTimeout"><span data-ttu-id="34683-117">プールにコンピューティング ノードの割り当てのタイムアウト。</span><span class="sxs-lookup"><span data-stu-id="34683-117">The timeout for allocation of compute nodes to the pool.</span></span></param>
        <param name="resizeErrors"><span data-ttu-id="34683-118">プールで最後のサイズ変更を実行中に発生したエラーの一覧。</span><span class="sxs-lookup"><span data-stu-id="34683-118">A list of errors encountered while performing the last resize on the pool.</span></span></param>
        <param name="currentDedicatedNodes"><span data-ttu-id="34683-119">専用の数は、現在、プール内のノードを計算します。</span><span class="sxs-lookup"><span data-stu-id="34683-119">The number of dedicated compute nodes currently in the pool.</span></span></param>
        <param name="currentLowPriorityNodes"><span data-ttu-id="34683-120">優先度の低いの数は、現在、プール内のノードを計算します。</span><span class="sxs-lookup"><span data-stu-id="34683-120">The number of low-priority compute nodes currently in the pool.</span></span></param>
        <param name="targetDedicatedNodes"><span data-ttu-id="34683-121">専用の目的の数は、プール内のノードを計算します。</span><span class="sxs-lookup"><span data-stu-id="34683-121">The desired number of dedicated compute nodes in the pool.</span></span></param>
        <param name="targetLowPriorityNodes"><span data-ttu-id="34683-122">目的の優先度の低い数は、プール内のノードを計算します。</span><span class="sxs-lookup"><span data-stu-id="34683-122">The desired number of low-priority compute nodes in the pool.</span></span></param>
        <param name="enableAutoScale"><span data-ttu-id="34683-123">かどうか、プールのサイズは、時間の経過と共に自動的に調整する必要があります。</span><span class="sxs-lookup"><span data-stu-id="34683-123">Whether the pool size should automatically adjust over time.</span></span></param>
        <param name="autoScaleFormula"><span data-ttu-id="34683-124">プール内の計算ノードの必要な数の式。</span><span class="sxs-lookup"><span data-stu-id="34683-124">A formula for the desired number of compute nodes in the pool.</span></span></param>
        <param name="autoScaleEvaluationInterval"><span data-ttu-id="34683-125">自動スケールの数式に従ってプールのサイズを自動的に調整する時間間隔。</span><span class="sxs-lookup"><span data-stu-id="34683-125">The time interval at which to automatically adjust the pool size according to the autoscale formula.</span></span></param>
        <param name="autoScaleRun"><span data-ttu-id="34683-126">結果と自動スケール式の前回の実行からのエラーです。</span><span class="sxs-lookup"><span data-stu-id="34683-126">The results and errors from the last execution of the autoscale formula.</span></span></param>
        <param name="enableInterNodeCommunication"><span data-ttu-id="34683-127">かどうか、プールは、ノード間の直接通信を許可します。</span><span class="sxs-lookup"><span data-stu-id="34683-127">Whether the pool permits direct communication between nodes.</span></span></param>
        <param name="networkConfiguration"><span data-ttu-id="34683-128">プールのネットワーク構成。</span><span class="sxs-lookup"><span data-stu-id="34683-128">The network configuration for the pool.</span></span></param>
        <param name="startTask"><span data-ttu-id="34683-129">各コンピューティング ノードで、プールに参加を実行する指定されたタスク。</span><span class="sxs-lookup"><span data-stu-id="34683-129">A task specified to run on each compute node as it joins the pool.</span></span></param>
        <param name="certificateReferences"><span data-ttu-id="34683-130">プール内の各コンピューティング ノードにインストールされている証明書の一覧です。</span><span class="sxs-lookup"><span data-stu-id="34683-130">The list of certificates to be installed on each compute node in the pool.</span></span></param>
        <param name="applicationPackageReferences"><span data-ttu-id="34683-131">プール内の各コンピューティング ノードにインストールされているアプリケーション パッケージの一覧。</span><span class="sxs-lookup"><span data-stu-id="34683-131">The list of application packages to be installed on each compute node in the pool.</span></span></param>
        <param name="applicationLicenses"><span data-ttu-id="34683-132">アプリケーションの一覧のライセンスは、バッチ サービスは、プール内の各コンピューティング ノードで使用できるようにします。</span><span class="sxs-lookup"><span data-stu-id="34683-132">The list of application licenses the Batch service will make available on each compute node in the pool.</span></span></param>
        <param name="maxTasksPerNode"><span data-ttu-id="34683-133">プール内の単一コンピューティング ノードで同時に実行できるタスクの最大数。</span><span class="sxs-lookup"><span data-stu-id="34683-133">The maximum number of tasks that can run concurrently on a single compute node in the pool.</span></span></param>
        <param name="taskSchedulingPolicy"><span data-ttu-id="34683-134">どのタスクはプール内のコンピューティング ノード間で分散されます。</span><span class="sxs-lookup"><span data-stu-id="34683-134">How tasks are distributed across compute nodes in a pool.</span></span></param>
        <param name="userAccounts"><span data-ttu-id="34683-135">プール内の各ノード上に作成されるユーザー アカウントの一覧です。</span><span class="sxs-lookup"><span data-stu-id="34683-135">The list of user accounts to be created on each node in the pool.</span></span></param>
        <param name="metadata"><span data-ttu-id="34683-136">メタデータとしてプールに関連付けられている名前と値のペアの一覧。</span><span class="sxs-lookup"><span data-stu-id="34683-136">A list of name-value pairs associated with the pool as metadata.</span></span></param>
        <param name="stats"><span data-ttu-id="34683-137">プール全体の有効期間にわたって使用状況の統計の使用効率とリソース</span><span class="sxs-lookup"><span data-stu-id="34683-137">Utilization and resource usage statistics for the entire lifetime of the pool.</span></span></param>
        <summary>
            <span data-ttu-id="34683-138">CloudPool クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="34683-138">Initializes a new instance of the CloudPool class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllocationState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.AllocationState&gt; AllocationState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.AllocationState&gt; AllocationState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudPool.AllocationState" />
      <MemberSignature Language="VB.NET" Value="Public Property AllocationState As Nullable(Of AllocationState)" />
      <MemberSignature Language="F#" Value="member this.AllocationState : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.AllocationState&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudPool.AllocationState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="allocationState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.AllocationState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="34683-139">取得またはプールのサイズを変更するかどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="34683-139">Gets or sets whether the pool is resizing.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="34683-140">使用可能な値が含まれます: '点灯'、'サイズを変更する'、'停止'</span><span class="sxs-lookup"><span data-stu-id="34683-140">Possible values include: 'steady', 'resizing', 'stopping'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AllocationStateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; AllocationStateTransitionTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; AllocationStateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudPool.AllocationStateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public Property AllocationStateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.AllocationStateTransitionTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudPool.AllocationStateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="allocationStateTransitionTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="34683-141">取得またはプールが現在の割り当て状態を入力するされた時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="34683-141">Gets or sets the time at which the pool entered its current allocation state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationLicenses">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ApplicationLicenses { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ApplicationLicenses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudPool.ApplicationLicenses" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationLicenses As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ApplicationLicenses : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudPool.ApplicationLicenses" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="applicationLicenses")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="34683-142">取得またはアプリケーションのライセンスの一覧をバッチ サービスは、プール内の各コンピューティング ノードで使用できるように設定します。</span><span class="sxs-lookup"><span data-stu-id="34683-142">Gets or sets the list of application licenses the Batch service will make available on each compute node in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="34683-143">アプリケーションのライセンスの一覧は、使用できる Batch サービス アプリケーションのライセンスのサブセットである必要があります。</span><span class="sxs-lookup"><span data-stu-id="34683-143">The list of application licenses must be a subset of available Batch service application licenses.</span></span> <span data-ttu-id="34683-144">これはサポートされていない要求されるライセンスと、プールの作成は失敗します。</span><span class="sxs-lookup"><span data-stu-id="34683-144">If a license is requested which is not supported, pool creation will fail.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationPackageReferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; ApplicationPackageReferences { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; ApplicationPackageReferences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudPool.ApplicationPackageReferences" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationPackageReferences As IList(Of ApplicationPackageReference)" />
      <MemberSignature Language="F#" Value="member this.ApplicationPackageReferences : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudPool.ApplicationPackageReferences" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="applicationPackageReferences")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="34683-145">取得またはプール内の各コンピューティング ノードにインストールされているアプリケーション パッケージの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="34683-145">Gets or sets the list of application packages to be installed on each compute node in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoScaleEvaluationInterval">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; AutoScaleEvaluationInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; AutoScaleEvaluationInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudPool.AutoScaleEvaluationInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoScaleEvaluationInterval As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.AutoScaleEvaluationInterval : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudPool.AutoScaleEvaluationInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="autoScaleEvaluationInterval")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="34683-146">取得または自動スケールの数式に従ってプールのサイズを自動的に調整するための時間間隔を設定します。</span><span class="sxs-lookup"><span data-stu-id="34683-146">Gets or sets the time interval at which to automatically adjust the pool size according to the autoscale formula.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="34683-147">プールは自動的にスケーリング、つまり enableAutoScale が true の場合のみ、このプロパティが設定されます。</span><span class="sxs-lookup"><span data-stu-id="34683-147">This property is set only if the pool automatically scales, i.e. enableAutoScale is true.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoScaleFormula">
      <MemberSignature Language="C#" Value="public string AutoScaleFormula { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AutoScaleFormula" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudPool.AutoScaleFormula" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoScaleFormula As String" />
      <MemberSignature Language="F#" Value="member this.AutoScaleFormula : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudPool.AutoScaleFormula" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="autoScaleFormula")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="34683-148">取得またはプール内の式の目的のコンピューティング ノードの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="34683-148">Gets or sets a formula for the desired number of compute nodes in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="34683-149">プールは自動的にスケーリング、つまり enableAutoScale が true の場合のみ、このプロパティが設定されます。</span><span class="sxs-lookup"><span data-stu-id="34683-149">This property is set only if the pool automatically scales, i.e. enableAutoScale is true.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoScaleRun">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun AutoScaleRun { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun AutoScaleRun" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudPool.AutoScaleRun" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoScaleRun As AutoScaleRun" />
      <MemberSignature Language="F#" Value="member this.AutoScaleRun : Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudPool.AutoScaleRun" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="autoScaleRun")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="34683-150">取得または自動スケール式の前回の実行からの結果とエラーに設定します。</span><span class="sxs-lookup"><span data-stu-id="34683-150">Gets or sets the results and errors from the last execution of the autoscale formula.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="34683-151">プールは自動的にスケーリング、つまり enableAutoScale が true の場合のみ、このプロパティが設定されます。</span><span class="sxs-lookup"><span data-stu-id="34683-151">This property is set only if the pool automatically scales, i.e. enableAutoScale is true.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateReferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; CertificateReferences { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; CertificateReferences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudPool.CertificateReferences" />
      <MemberSignature Language="VB.NET" Value="Public Property CertificateReferences As IList(Of CertificateReference)" />
      <MemberSignature Language="F#" Value="member this.CertificateReferences : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudPool.CertificateReferences" />
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
            <span data-ttu-id="34683-152">取得またはプール内の各コンピューティング ノードにインストールされている証明書の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="34683-152">Gets or sets the list of certificates to be installed on each compute node in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="34683-153">Windows では、ノードを計算するため、バッチ サービスは、場所と指定された証明書ストアに証明書をインストールします。</span><span class="sxs-lookup"><span data-stu-id="34683-153">For Windows compute nodes, the Batch service installs the certificates to the specified certificate store and location.</span></span> <span data-ttu-id="34683-154">Linux 計算ノードでは、証明書は、タスクの作業ディレクトリと変数 AZ_BATCH_CERTIFICATES_DIR がこの場所にクエリするタスクに指定された環境の内部ディレクトリに保存されます。</span><span class="sxs-lookup"><span data-stu-id="34683-154">For Linux compute nodes, the certificates are stored in a directory inside the task working directory and an environment variable AZ_BATCH_CERTIFICATES_DIR is supplied to the task to query for this location.</span></span> <span data-ttu-id="34683-155">'RemoteUser' の可視性を持つ証明書は、'certs' ディレクトリは、ユーザーのホーム ディレクトリに作成 (など/home/{ユーザー名}/certs) および証明書はそのディレクトリに配置します。</span><span class="sxs-lookup"><span data-stu-id="34683-155">For certificates with visibility of 'remoteUser', a 'certs' directory is created in the user's home directory (e.g., /home/{user-name}/certs) and certificates are placed in that directory.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CloudServiceConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration CloudServiceConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration CloudServiceConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudPool.CloudServiceConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property CloudServiceConfiguration As CloudServiceConfiguration" />
      <MemberSignature Language="F#" Value="member this.CloudServiceConfiguration : Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudPool.CloudServiceConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="cloudServiceConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="34683-156">取得またはプールをクラウド サービスの構成を設定します。</span><span class="sxs-lookup"><span data-stu-id="34683-156">Gets or sets the cloud service configuration for the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="34683-157">このプロパティと virtualMachineConfiguration は相互に排他的とプロパティのいずれかを指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="34683-157">This property and virtualMachineConfiguration are mutually exclusive and one of the properties must be specified.</span></span> <span data-ttu-id="34683-158">このプロパティは、Batch アカウントが、poolAllocationMode プロパティ 'UserSubscription' に設定して作成されたかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="34683-158">This property cannot be specified if the Batch account was created with its poolAllocationMode property set to 'UserSubscription'.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreationTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudPool.CreationTime" />
      <MemberSignature Language="VB.NET" Value="Public Property CreationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreationTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudPool.CreationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="creationTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="34683-159">取得またはプールの作成時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="34683-159">Gets or sets the creation time of the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentDedicatedNodes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; CurrentDedicatedNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; CurrentDedicatedNodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudPool.CurrentDedicatedNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property CurrentDedicatedNodes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.CurrentDedicatedNodes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudPool.CurrentDedicatedNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="currentDedicatedNodes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="34683-160">取得またはプールに現在専用のコンピューティング ノードの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="34683-160">Gets or sets the number of dedicated compute nodes currently in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentLowPriorityNodes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; CurrentLowPriorityNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; CurrentLowPriorityNodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudPool.CurrentLowPriorityNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property CurrentLowPriorityNodes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.CurrentLowPriorityNodes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudPool.CurrentLowPriorityNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="currentLowPriorityNodes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="34683-161">取得またはプールに現在の優先度の低いコンピューティング ノードの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="34683-161">Gets or sets the number of low-priority compute nodes currently in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="34683-162">この数には、占有されている優先度の低いコンピューティング ノードが含まれています。</span><span class="sxs-lookup"><span data-stu-id="34683-162">Low-priority compute nodes which have been preempted are included in this count.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudPool.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudPool.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="displayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="34683-163">取得またはプールの表示名を設定します。</span><span class="sxs-lookup"><span data-stu-id="34683-163">Gets or sets the display name for the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="34683-164">表示名は一意でない必要があり、最大で 1,024 の最大長の Unicode 文字を含めることができます。</span><span class="sxs-lookup"><span data-stu-id="34683-164">The display name need not be unique and can contain any Unicode characters up to a maximum length of 1024.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableAutoScale">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableAutoScale { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableAutoScale" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudPool.EnableAutoScale" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableAutoScale As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableAutoScale : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudPool.EnableAutoScale" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="enableAutoScale")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="34683-165">取得または時間の経過と共に、プールのサイズを自動的に調整するかどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="34683-165">Gets or sets whether the pool size should automatically adjust over time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="34683-166">False の場合、targetDedicateNodes と targetLowPriorityNodes の少なくとも 1 つ指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="34683-166">If false, at least one of targetDedicateNodes and targetLowPriorityNodes must be specified.</span></span> <span data-ttu-id="34683-167">True の場合は、autoScaleFormula プロパティは必須と数式に従ってプールが自動的にサイズ変更します。</span><span class="sxs-lookup"><span data-stu-id="34683-167">If true, the autoScaleFormula property is required and the pool automatically resizes according to the formula.</span></span> <span data-ttu-id="34683-168">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="34683-168">The default value is false.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableInterNodeCommunication">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableInterNodeCommunication { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableInterNodeCommunication" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudPool.EnableInterNodeCommunication" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableInterNodeCommunication As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableInterNodeCommunication : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudPool.EnableInterNodeCommunication" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="enableInterNodeCommunication")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="34683-169">取得またはプールがノード間で直接通信を許可するかどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="34683-169">Gets or sets whether the pool permits direct communication between nodes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="34683-170">これは、制限にノードをプールに割り当てることができます。</span><span class="sxs-lookup"><span data-stu-id="34683-170">This imposes restrictions on which nodes can be assigned to the pool.</span></span> <span data-ttu-id="34683-171">この値を指定すると、プールに割り当てられるノードの要求された数の可能性を低減できます。</span><span class="sxs-lookup"><span data-stu-id="34683-171">Specifying this value can reduce the chance of the requested number of nodes to be allocated in the pool.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudPool.ETag" />
      <MemberSignature Language="VB.NET" Value="Public Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudPool.ETag" />
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
            <span data-ttu-id="34683-172">取得またはプールの ETag を設定します。</span><span class="sxs-lookup"><span data-stu-id="34683-172">Gets or sets the ETag of the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="34683-173">これは、不透明な文字列です。</span><span class="sxs-lookup"><span data-stu-id="34683-173">This is an opaque string.</span></span> <span data-ttu-id="34683-174">要求間でプールが変更されたかどうかを検出するために使用できます。</span><span class="sxs-lookup"><span data-stu-id="34683-174">You can use it to detect whether the pool has changed between requests.</span></span> <span data-ttu-id="34683-175">特にには、変更が反映されるその他のユーザーが変更プール間場合にのみを指定するプールを更新する場合に ETag を渡すことができます。</span><span class="sxs-lookup"><span data-stu-id="34683-175">In particular, you can be pass the ETag when updating a pool to specify that your changes should take effect only if nobody else has modified the pool in the meantime.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudPool.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudPool.Id" />
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
            <span data-ttu-id="34683-176">取得またはアカウント内のプールを一意に識別する文字列を設定します。</span><span class="sxs-lookup"><span data-stu-id="34683-176">Gets or sets a string that uniquely identifies the pool within the account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="34683-177">ID は、ハイフン、アンダー スコアを含む、英数字の任意の組み合わせを含めることができ、64 を超える文字を含めることはできません。</span><span class="sxs-lookup"><span data-stu-id="34683-177">The ID can contain any combination of alphanumeric characters including hyphens and underscores, and cannot contain more than 64 characters.</span></span> <span data-ttu-id="34683-178">ID は大文字と小文字を区別 (つまり、大文字と小文字が異なるだけ、アカウント内の 2 つの Id はない必要があります)。</span><span class="sxs-lookup"><span data-stu-id="34683-178">The ID is case-preserving and case-insensitive (that is, you may not have two IDs within an account that differ only by case).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModified">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastModified { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastModified" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudPool.LastModified" />
      <MemberSignature Language="VB.NET" Value="Public Property LastModified As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastModified : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudPool.LastModified" />
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
            <span data-ttu-id="34683-179">取得またはプールの最終更新時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="34683-179">Gets or sets the last modified time of the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="34683-180">これは、前回のプール レベルなど、データ、targetDedicatedNodes または enableAutoscale の設定が変更されました。</span><span class="sxs-lookup"><span data-stu-id="34683-180">This is the last time at which the pool level data, such as the targetDedicatedNodes or enableAutoscale settings, changed.</span></span> <span data-ttu-id="34683-181">コンピューティング ノードの状態を変更するなど、ノード レベルの変更には考慮されません。</span><span class="sxs-lookup"><span data-stu-id="34683-181">It does not factor in node-level changes such as a compute node changing state.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxTasksPerNode">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxTasksPerNode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxTasksPerNode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudPool.MaxTasksPerNode" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxTasksPerNode As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxTasksPerNode : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudPool.MaxTasksPerNode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxTasksPerNode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="34683-182">取得またはプール内の 1 つのコンピューティング ノードで同時に実行できるタスクの最大数を設定します。</span><span class="sxs-lookup"><span data-stu-id="34683-182">Gets or sets the maximum number of tasks that can run concurrently on a single compute node in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; Metadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudPool.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public Property Metadata As IList(Of MetadataItem)" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudPool.Metadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="metadata")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="34683-183">取得またはメタデータとしてプールに関連付けられている名前と値のペアの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="34683-183">Gets or sets a list of name-value pairs associated with the pool as metadata.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration NetworkConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration NetworkConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudPool.NetworkConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkConfiguration As NetworkConfiguration" />
      <MemberSignature Language="F#" Value="member this.NetworkConfiguration : Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudPool.NetworkConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="networkConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="34683-184">取得またはプールのネットワーク構成を設定します。</span><span class="sxs-lookup"><span data-stu-id="34683-184">Gets or sets the network configuration for the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResizeErrors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResizeError&gt; ResizeErrors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ResizeError&gt; ResizeErrors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudPool.ResizeErrors" />
      <MemberSignature Language="VB.NET" Value="Public Property ResizeErrors As IList(Of ResizeError)" />
      <MemberSignature Language="F#" Value="member this.ResizeErrors : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResizeError&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudPool.ResizeErrors" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resizeErrors")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResizeError&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="34683-185">取得またはプールで最後のサイズ変更を実行中に発生したエラーの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="34683-185">Gets or sets a list of errors encountered while performing the last resize on the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="34683-186">最後のプール サイズ変更中に 1 つまたは複数のエラーが発生した場合にのみ、およびプールの allocationState が安定した場合にのみ、このプロパティが設定されます。</span><span class="sxs-lookup"><span data-stu-id="34683-186">This property is set only if one or more errors occurred during the last pool resize, and only when the pool allocationState is Steady.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResizeTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; ResizeTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; ResizeTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudPool.ResizeTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property ResizeTimeout As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.ResizeTimeout : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudPool.ResizeTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resizeTimeout")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="34683-187">取得またはプールに割り当てるコンピューティング ノードの場合のタイムアウトを設定します。</span><span class="sxs-lookup"><span data-stu-id="34683-187">Gets or sets the timeout for allocation of compute nodes to the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="34683-188">これは、最新のサイズ変更操作のタイムアウトです。</span><span class="sxs-lookup"><span data-stu-id="34683-188">This is the timeout for the most recent resize operation.</span></span> <span data-ttu-id="34683-189">(プール作成時の初回サイズ設定もサイズ変更とカウントされます。)既定値は、15 分です。</span><span class="sxs-lookup"><span data-stu-id="34683-189">(The initial sizing when the pool is created counts as a resize.) The default value is 15 minutes.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.StartTask StartTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.StartTask StartTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudPool.StartTask" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTask As StartTask" />
      <MemberSignature Language="F#" Value="member this.StartTask : Microsoft.Azure.Batch.Protocol.Models.StartTask with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudPool.StartTask" />
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
            <span data-ttu-id="34683-190">取得または各コンピューティング ノードで、プールに参加を実行する指定されたタスクを設定します。</span><span class="sxs-lookup"><span data-stu-id="34683-190">Gets or sets a task specified to run on each compute node as it joins the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.PoolState&gt; State { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.PoolState&gt; State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudPool.State" />
      <MemberSignature Language="VB.NET" Value="Public Property State As Nullable(Of PoolState)" />
      <MemberSignature Language="F#" Value="member this.State : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.PoolState&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudPool.State" />
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
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.PoolState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="34683-191">取得またはプールの現在の状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="34683-191">Gets or sets the current state of the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="34683-192">使用可能な値が含まれます: 'active'、'削除'、'アップグレード'</span><span class="sxs-lookup"><span data-stu-id="34683-192">Possible values include: 'active', 'deleting', 'upgrading'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StateTransitionTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudPool.StateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StateTransitionTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudPool.StateTransitionTime" />
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
            <span data-ttu-id="34683-193">取得またはプールが、現在の状態を入力する時間を設定します。</span><span class="sxs-lookup"><span data-stu-id="34683-193">Gets or sets the time at which the pool entered its current state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Stats">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.PoolStatistics Stats { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.PoolStatistics Stats" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudPool.Stats" />
      <MemberSignature Language="VB.NET" Value="Public Property Stats As PoolStatistics" />
      <MemberSignature Language="F#" Value="member this.Stats : Microsoft.Azure.Batch.Protocol.Models.PoolStatistics with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudPool.Stats" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="stats")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.PoolStatistics</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="34683-194">取得またはプール全体の有効期間にわたって使用率とリソース使用状況の統計情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="34683-194">Gets or sets utilization and resource usage statistics for the entire lifetime of the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetDedicatedNodes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TargetDedicatedNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TargetDedicatedNodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudPool.TargetDedicatedNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetDedicatedNodes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TargetDedicatedNodes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudPool.TargetDedicatedNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetDedicatedNodes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="34683-195">取得またはプールの目的専用のコンピューティング ノードの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="34683-195">Gets or sets the desired number of dedicated compute nodes in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetLowPriorityNodes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TargetLowPriorityNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TargetLowPriorityNodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudPool.TargetLowPriorityNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetLowPriorityNodes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TargetLowPriorityNodes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudPool.TargetLowPriorityNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetLowPriorityNodes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="34683-196">取得またはプールに目的の優先度の低いコンピューティング ノードの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="34683-196">Gets or sets the desired number of low-priority compute nodes in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskSchedulingPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy TaskSchedulingPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy TaskSchedulingPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudPool.TaskSchedulingPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property TaskSchedulingPolicy As TaskSchedulingPolicy" />
      <MemberSignature Language="F#" Value="member this.TaskSchedulingPolicy : Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudPool.TaskSchedulingPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="taskSchedulingPolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="34683-197">取得またはタスクのプール内のコンピューティング ノード間で配分する方法を設定します。</span><span class="sxs-lookup"><span data-stu-id="34683-197">Gets or sets how tasks are distributed across compute nodes in a pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudPool.Url" />
      <MemberSignature Language="VB.NET" Value="Public Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudPool.Url" />
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
            <span data-ttu-id="34683-198">取得またはプールの URL を設定します。</span><span class="sxs-lookup"><span data-stu-id="34683-198">Gets or sets the URL of the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserAccounts">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.UserAccount&gt; UserAccounts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.UserAccount&gt; UserAccounts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudPool.UserAccounts" />
      <MemberSignature Language="VB.NET" Value="Public Property UserAccounts As IList(Of UserAccount)" />
      <MemberSignature Language="F#" Value="member this.UserAccounts : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.UserAccount&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudPool.UserAccounts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="userAccounts")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.UserAccount&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="34683-199">取得またはプール内の各ノード上に作成されるユーザー アカウントの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="34683-199">Gets or sets the list of user accounts to be created on each node in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.CloudPool.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="cloudPool.Validate " />
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
            <span data-ttu-id="34683-200">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="34683-200">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="34683-201">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="34683-201">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration VirtualMachineConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration VirtualMachineConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudPool.VirtualMachineConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualMachineConfiguration As VirtualMachineConfiguration" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineConfiguration : Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudPool.VirtualMachineConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="virtualMachineConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="34683-202">取得またはプールの仮想マシンの構成を設定します。</span><span class="sxs-lookup"><span data-stu-id="34683-202">Gets or sets the virtual machine configuration for the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="34683-203">このプロパティと cloudServiceConfiguration は相互に排他的とプロパティのいずれかを指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="34683-203">This property and cloudServiceConfiguration are mutually exclusive and one of the properties must be specified.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="VmSize">
      <MemberSignature Language="C#" Value="public string VmSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VmSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudPool.VmSize" />
      <MemberSignature Language="VB.NET" Value="Public Property VmSize As String" />
      <MemberSignature Language="F#" Value="member this.VmSize : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudPool.VmSize" />
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
            <span data-ttu-id="34683-204">取得またはプール内の仮想マシンのサイズを設定します。</span><span class="sxs-lookup"><span data-stu-id="34683-204">Gets or sets the size of virtual machines in the pool.</span></span> <span data-ttu-id="34683-205">プール内の仮想マシンのサイズはすべて同じです。</span><span class="sxs-lookup"><span data-stu-id="34683-205">All virtual machines in a pool are the same size.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="34683-206">クラウド サービス プール (プール cloudServiceConfiguration で作成された) の仮想マシンの利用可能なサイズについては、クラウド サービス (http://azure.microsoft.com/documentation/articles/cloud-services-sizes-specs/) のサイズを参照してください。</span><span class="sxs-lookup"><span data-stu-id="34683-206">For information about available sizes of virtual machines for Cloud Services pools (pools created with cloudServiceConfiguration), see Sizes for Cloud Services (http://azure.microsoft.com/documentation/articles/cloud-services-sizes-specs/).</span></span>
            <span data-ttu-id="34683-207">バッチには、ExtraSmall、A1V2 A2V2 を除くすべてのクラウド サービス VM サイズがサポートしています。</span><span class="sxs-lookup"><span data-stu-id="34683-207">Batch supports all Cloud Services VM sizes except ExtraSmall, A1V2 and A2V2.</span></span> <span data-ttu-id="34683-208">(プール virtualMachineConfiguration で作成した) 仮想マシンのマーケットプ レースからイメージを使用するプールの利用可能な VM サイズについては (Linux) (https://azure.microsoft.com/documentation/articles/ の仮想マシンのサイズを参照してください。仮想マシンの linux-サイズ/) または仮想マシン (Windows) (https://azure.microsoft.com/documentation/articles/virtual-machines-windows-sizes/) のサイズ。</span><span class="sxs-lookup"><span data-stu-id="34683-208">For information about available VM sizes for pools using images from the Virtual Machines Marketplace (pools created with virtualMachineConfiguration) see Sizes for Virtual Machines (Linux) (https://azure.microsoft.com/documentation/articles/virtual-machines-linux-sizes/) or Sizes for Virtual Machines (Windows) (https://azure.microsoft.com/documentation/articles/virtual-machines-windows-sizes/).</span></span>
            <span data-ttu-id="34683-209">バッチには、STANDARD_A0 と premium storage (STANDARD_GS、STANDARD_DS、および STANDARD_DSV2 シリーズ) でそれらを除くすべての Azure VM サイズがサポートしています。</span><span class="sxs-lookup"><span data-stu-id="34683-209">Batch supports all Azure VM sizes except STANDARD_A0 and those with premium storage (STANDARD_GS, STANDARD_DS, and STANDARD_DSV2 series).</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>