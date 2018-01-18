<Type Name="Pool" FullName="Microsoft.Azure.Management.Batch.Models.Pool">
  <TypeSignature Language="C#" Value="public class Pool : Microsoft.Azure.Management.Batch.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Pool extends Microsoft.Azure.Management.Batch.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.Pool" />
  <TypeSignature Language="VB.NET" Value="Public Class Pool&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type Pool = class&#xA;    inherit ProxyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Batch.Models.ProxyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="a117b-101">プールに関する情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="a117b-101">Contains information about a pool.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Pool ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.Pool.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a117b-102">プール クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a117b-102">Initializes a new instance of the Pool class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Pool (string id = null, string name = null, string type = null, string etag = null, string displayName = null, Nullable&lt;DateTime&gt; lastModified = null, Nullable&lt;DateTime&gt; creationTime = null, Nullable&lt;Microsoft.Azure.Management.Batch.Models.PoolProvisioningState&gt; provisioningState = null, Nullable&lt;DateTime&gt; provisioningStateTransitionTime = null, Nullable&lt;Microsoft.Azure.Management.Batch.Models.AllocationState&gt; allocationState = null, Nullable&lt;DateTime&gt; allocationStateTransitionTime = null, string vmSize = null, Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration deploymentConfiguration = null, Nullable&lt;int&gt; currentDedicatedNodes = null, Nullable&lt;int&gt; currentLowPriorityNodes = null, Microsoft.Azure.Management.Batch.Models.ScaleSettings scaleSettings = null, Microsoft.Azure.Management.Batch.Models.AutoScaleRun autoScaleRun = null, Nullable&lt;Microsoft.Azure.Management.Batch.Models.InterNodeCommunicationState&gt; interNodeCommunication = null, Microsoft.Azure.Management.Batch.Models.NetworkConfiguration networkConfiguration = null, Nullable&lt;int&gt; maxTasksPerNode = null, Microsoft.Azure.Management.Batch.Models.TaskSchedulingPolicy taskSchedulingPolicy = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.UserAccount&gt; userAccounts = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.MetadataItem&gt; metadata = null, Microsoft.Azure.Management.Batch.Models.StartTask startTask = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.CertificateReference&gt; certificates = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference&gt; applicationPackages = null, System.Collections.Generic.IList&lt;string&gt; applicationLicenses = null, Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus resizeOperationStatus = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string etag, string displayName, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastModified, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; creationTime, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.PoolProvisioningState&gt; provisioningState, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; provisioningStateTransitionTime, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.AllocationState&gt; allocationState, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; allocationStateTransitionTime, string vmSize, class Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration deploymentConfiguration, valuetype System.Nullable`1&lt;int32&gt; currentDedicatedNodes, valuetype System.Nullable`1&lt;int32&gt; currentLowPriorityNodes, class Microsoft.Azure.Management.Batch.Models.ScaleSettings scaleSettings, class Microsoft.Azure.Management.Batch.Models.AutoScaleRun autoScaleRun, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.InterNodeCommunicationState&gt; interNodeCommunication, class Microsoft.Azure.Management.Batch.Models.NetworkConfiguration networkConfiguration, valuetype System.Nullable`1&lt;int32&gt; maxTasksPerNode, class Microsoft.Azure.Management.Batch.Models.TaskSchedulingPolicy taskSchedulingPolicy, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.UserAccount&gt; userAccounts, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.MetadataItem&gt; metadata, class Microsoft.Azure.Management.Batch.Models.StartTask startTask, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.CertificateReference&gt; certificates, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference&gt; applicationPackages, class System.Collections.Generic.IList`1&lt;string&gt; applicationLicenses, class Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus resizeOperationStatus) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.Pool.#ctor(System.String,System.String,System.String,System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{Microsoft.Azure.Management.Batch.Models.PoolProvisioningState},System.Nullable{System.DateTime},System.Nullable{Microsoft.Azure.Management.Batch.Models.AllocationState},System.Nullable{System.DateTime},System.String,Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration,System.Nullable{System.Int32},System.Nullable{System.Int32},Microsoft.Azure.Management.Batch.Models.ScaleSettings,Microsoft.Azure.Management.Batch.Models.AutoScaleRun,System.Nullable{Microsoft.Azure.Management.Batch.Models.InterNodeCommunicationState},Microsoft.Azure.Management.Batch.Models.NetworkConfiguration,System.Nullable{System.Int32},Microsoft.Azure.Management.Batch.Models.TaskSchedulingPolicy,System.Collections.Generic.IList{Microsoft.Azure.Management.Batch.Models.UserAccount},System.Collections.Generic.IList{Microsoft.Azure.Management.Batch.Models.MetadataItem},Microsoft.Azure.Management.Batch.Models.StartTask,System.Collections.Generic.IList{Microsoft.Azure.Management.Batch.Models.CertificateReference},System.Collections.Generic.IList{Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference},System.Collections.Generic.IList{System.String},Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.Pool : string * string * string * string * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;Microsoft.Azure.Management.Batch.Models.PoolProvisioningState&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;Microsoft.Azure.Management.Batch.Models.AllocationState&gt; * Nullable&lt;DateTime&gt; * string * Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Microsoft.Azure.Management.Batch.Models.ScaleSettings * Microsoft.Azure.Management.Batch.Models.AutoScaleRun * Nullable&lt;Microsoft.Azure.Management.Batch.Models.InterNodeCommunicationState&gt; * Microsoft.Azure.Management.Batch.Models.NetworkConfiguration * Nullable&lt;int&gt; * Microsoft.Azure.Management.Batch.Models.TaskSchedulingPolicy * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.UserAccount&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.MetadataItem&gt; * Microsoft.Azure.Management.Batch.Models.StartTask * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.CertificateReference&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference&gt; * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus -&gt; Microsoft.Azure.Management.Batch.Models.Pool" Usage="new Microsoft.Azure.Management.Batch.Models.Pool (id, name, type, etag, displayName, lastModified, creationTime, provisioningState, provisioningStateTransitionTime, allocationState, allocationStateTransitionTime, vmSize, deploymentConfiguration, currentDedicatedNodes, currentLowPriorityNodes, scaleSettings, autoScaleRun, interNodeCommunication, networkConfiguration, maxTasksPerNode, taskSchedulingPolicy, userAccounts, metadata, startTask, certificates, applicationPackages, applicationLicenses, resizeOperationStatus)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="lastModified" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="creationTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="provisioningState" Type="System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.PoolProvisioningState&gt;" />
        <Parameter Name="provisioningStateTransitionTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="allocationState" Type="System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.AllocationState&gt;" />
        <Parameter Name="allocationStateTransitionTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="vmSize" Type="System.String" />
        <Parameter Name="deploymentConfiguration" Type="Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration" />
        <Parameter Name="currentDedicatedNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentLowPriorityNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="scaleSettings" Type="Microsoft.Azure.Management.Batch.Models.ScaleSettings" />
        <Parameter Name="autoScaleRun" Type="Microsoft.Azure.Management.Batch.Models.AutoScaleRun" />
        <Parameter Name="interNodeCommunication" Type="System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.InterNodeCommunicationState&gt;" />
        <Parameter Name="networkConfiguration" Type="Microsoft.Azure.Management.Batch.Models.NetworkConfiguration" />
        <Parameter Name="maxTasksPerNode" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="taskSchedulingPolicy" Type="Microsoft.Azure.Management.Batch.Models.TaskSchedulingPolicy" />
        <Parameter Name="userAccounts" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.UserAccount&gt;" />
        <Parameter Name="metadata" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.MetadataItem&gt;" />
        <Parameter Name="startTask" Type="Microsoft.Azure.Management.Batch.Models.StartTask" />
        <Parameter Name="certificates" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.CertificateReference&gt;" />
        <Parameter Name="applicationPackages" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference&gt;" />
        <Parameter Name="applicationLicenses" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="resizeOperationStatus" Type="Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="a117b-103">リソースの ID。</span><span class="sxs-lookup"><span data-stu-id="a117b-103">The ID of the resource.</span></span></param>
        <param name="name"><span data-ttu-id="a117b-104">リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="a117b-104">The name of the resource.</span></span></param>
        <param name="type"><span data-ttu-id="a117b-105">リソースの型。</span><span class="sxs-lookup"><span data-stu-id="a117b-105">The type of the resource.</span></span></param>
        <param name="etag"><span data-ttu-id="a117b-106">同時実行ステートメントの使用、リソースの ETag。</span><span class="sxs-lookup"><span data-stu-id="a117b-106">The ETag of the resource, used for concurrency statements.</span></span></param>
        <param name="displayName"><span data-ttu-id="a117b-107">プールの表示名。</span><span class="sxs-lookup"><span data-stu-id="a117b-107">The display name for the pool.</span></span></param>
        <param name="lastModified"><span data-ttu-id="a117b-108">最終更新時刻プールをします。</span><span class="sxs-lookup"><span data-stu-id="a117b-108">The last modified time of the pool.</span></span></param>
        <param name="creationTime"><span data-ttu-id="a117b-109">プールの作成時間。</span><span class="sxs-lookup"><span data-stu-id="a117b-109">The creation time of the pool.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="a117b-110">プールの現在の状態。</span><span class="sxs-lookup"><span data-stu-id="a117b-110">The current state of the pool.</span></span></param>
        <param name="provisioningStateTransitionTime"><span data-ttu-id="a117b-111">現在の状態、プールになった時刻。</span><span class="sxs-lookup"><span data-stu-id="a117b-111">The time at which the pool entered its current state.</span></span></param>
        <param name="allocationState"><span data-ttu-id="a117b-112">プールのサイズを変更するかどうか。</span><span class="sxs-lookup"><span data-stu-id="a117b-112">Whether the pool is resizing.</span></span></param>
        <param name="allocationStateTransitionTime"><span data-ttu-id="a117b-113">現在の割り当て状態、プールになった時刻。</span><span class="sxs-lookup"><span data-stu-id="a117b-113">The time at which the pool entered its current allocation state.</span></span></param>
        <param name="vmSize"><span data-ttu-id="a117b-114">プール内の仮想マシンのサイズ。</span><span class="sxs-lookup"><span data-stu-id="a117b-114">The size of virtual machines in the pool.</span></span> <span data-ttu-id="a117b-115">プール内のすべての Vm は、同じサイズです。</span><span class="sxs-lookup"><span data-stu-id="a117b-115">All VMs in a pool are the same size.</span></span></param>
        <param name="deploymentConfiguration"><span data-ttu-id="a117b-116">このプロパティは、プールのノードがある方法について説明します - クラウド サービスまたは仮想マシンを使用して展開します。</span><span class="sxs-lookup"><span data-stu-id="a117b-116">This property describes how the pool nodes will be deployed - using Cloud Services or Virtual Machines.</span></span></param>
        <param name="currentDedicatedNodes"><span data-ttu-id="a117b-117">現在、プール内の計算ノードの数。</span><span class="sxs-lookup"><span data-stu-id="a117b-117">The number of compute nodes currently in the pool.</span></span></param>
        <param name="currentLowPriorityNodes"><span data-ttu-id="a117b-118">低優先度の数は、現在、プール内のノードを計算します。</span><span class="sxs-lookup"><span data-stu-id="a117b-118">The number of low priority compute nodes currently in the pool.</span></span></param>
        <param name="scaleSettings"><span data-ttu-id="a117b-119">プール内のノードの数を構成する設定です。</span><span class="sxs-lookup"><span data-stu-id="a117b-119">Settings which configure the number of nodes in the pool.</span></span></param>
        <param name="autoScaleRun"><span data-ttu-id="a117b-120">結果と自動スケール式の前回の実行からのエラーです。</span><span class="sxs-lookup"><span data-stu-id="a117b-120">The results and errors from the last execution of the autoscale formula.</span></span></param>
        <param name="interNodeCommunication"><span data-ttu-id="a117b-121">かどうか、プールは、ノード間の直接通信を許可します。</span><span class="sxs-lookup"><span data-stu-id="a117b-121">Whether the pool permits direct communication between nodes.</span></span></param>
        <param name="networkConfiguration"><span data-ttu-id="a117b-122">プールのネットワーク構成。</span><span class="sxs-lookup"><span data-stu-id="a117b-122">The network configuration for the pool.</span></span></param>
        <param name="maxTasksPerNode"><span data-ttu-id="a117b-123">プール内の単一コンピューティング ノードで同時に実行できるタスクの最大数。</span><span class="sxs-lookup"><span data-stu-id="a117b-123">The maximum number of tasks that can run concurrently on a single compute node in the pool.</span></span></param>
        <param name="taskSchedulingPolicy"><span data-ttu-id="a117b-124">どのタスクはプール内のコンピューティング ノード間で分散されます。</span><span class="sxs-lookup"><span data-stu-id="a117b-124">How tasks are distributed across compute nodes in a pool.</span></span></param>
        <param name="userAccounts"><span data-ttu-id="a117b-125">プール内の各ノード上に作成されるユーザー アカウントの一覧です。</span><span class="sxs-lookup"><span data-stu-id="a117b-125">The list of user accounts to be created on each node in the pool.</span></span></param>
        <param name="metadata"><span data-ttu-id="a117b-126">メタデータとしてプールに関連付けられている名前と値のペアの一覧。</span><span class="sxs-lookup"><span data-stu-id="a117b-126">A list of name-value pairs associated with the pool as metadata.</span></span></param>
        <param name="startTask"><span data-ttu-id="a117b-127">各コンピューティング ノードで、プールに参加を実行する指定されたタスク。</span><span class="sxs-lookup"><span data-stu-id="a117b-127">A task specified to run on each compute node as it joins the pool.</span></span></param>
        <param name="certificates"><span data-ttu-id="a117b-128">プール内の各コンピューティング ノードにインストールされている証明書の一覧です。</span><span class="sxs-lookup"><span data-stu-id="a117b-128">The list of certificates to be installed on each compute node in the pool.</span></span></param>
        <param name="applicationPackages"><span data-ttu-id="a117b-129">プール内の各コンピューティング ノードにインストールされているアプリケーション パッケージの一覧。</span><span class="sxs-lookup"><span data-stu-id="a117b-129">The list of application packages to be installed on each compute node in the pool.</span></span></param>
        <param name="applicationLicenses"><span data-ttu-id="a117b-130">アプリケーションの一覧のライセンスは、バッチ サービスは、プール内の各コンピューティング ノードで使用できるようにします。</span><span class="sxs-lookup"><span data-stu-id="a117b-130">The list of application licenses the Batch service will make available on each compute node in the pool.</span></span></param>
        <param name="resizeOperationStatus"><span data-ttu-id="a117b-131">現在または最近完了したサイズ変更操作に関する詳細情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="a117b-131">Contains details about the current or last completed resize operation.</span></span></param>
        <summary>
            <span data-ttu-id="a117b-132">プール クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a117b-132">Initializes a new instance of the Pool class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllocationState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Batch.Models.AllocationState&gt; AllocationState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.AllocationState&gt; AllocationState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.AllocationState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AllocationState As Nullable(Of AllocationState)" />
      <MemberSignature Language="F#" Value="member this.AllocationState : Nullable&lt;Microsoft.Azure.Management.Batch.Models.AllocationState&gt;" Usage="Microsoft.Azure.Management.Batch.Models.Pool.AllocationState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.allocationState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.AllocationState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
             <span data-ttu-id="a117b-133">プールのサイズを変更するかどうかを取得します。</span><span class="sxs-lookup"><span data-stu-id="a117b-133">Gets whether the pool is resizing.</span></span>
             </summary>
        <value>To be added.</value>
        <remarks>
             <span data-ttu-id="a117b-134">値は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="a117b-134">Values are:</span></span>
            
             <span data-ttu-id="a117b-135">steady - プールがないをサイズ変更します。</span><span class="sxs-lookup"><span data-stu-id="a117b-135">Steady - The pool is not resizing.</span></span> <span data-ttu-id="a117b-136">進行中のプール内のノードの数を変更することはありません。</span><span class="sxs-lookup"><span data-stu-id="a117b-136">There are no changes to the number of nodes in the pool in progress.</span></span> <span data-ttu-id="a117b-137">プールは、専用のノードの数を変更するプールの操作が実行されているされないときとが作成されるときに、この状態を入力します。</span><span class="sxs-lookup"><span data-stu-id="a117b-137">A pool enters this state when it is created and when no operations are being performed on the pool to change the number of dedicated nodes.</span></span>
             <span data-ttu-id="a117b-138">このサイズを変更するには、プールのサイズを変更します。つまり、コンピューティング ノードの中に追加またはプールから削除します。</span><span class="sxs-lookup"><span data-stu-id="a117b-138">Resizing - The pool is resizing; that is, compute nodes are being added to or removed from the pool.</span></span>
             <span data-ttu-id="a117b-139">停止中 - プールのサイズ変更が、ユーザーは、サイズ変更を停止することを要求したが停止要求がまだ完了していません。</span><span class="sxs-lookup"><span data-stu-id="a117b-139">Stopping - The pool was resizing, but the user has requested that the resize be stopped, but the stop request has not yet been completed.</span></span> <span data-ttu-id="a117b-140">使用可能な値が含まれます: '点灯'、'サイズを変更する'、'停止'</span><span class="sxs-lookup"><span data-stu-id="a117b-140">Possible values include: 'Steady', 'Resizing', 'Stopping'</span></span>
             </remarks>
      </Docs>
    </Member>
    <Member MemberName="AllocationStateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; AllocationStateTransitionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; AllocationStateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.AllocationStateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AllocationStateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.AllocationStateTransitionTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Batch.Models.Pool.AllocationStateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.allocationStateTransitionTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a117b-141">プールが現在の割り当て状態を入力するされた時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="a117b-141">Gets the time at which the pool entered its current allocation state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationLicenses">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ApplicationLicenses { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ApplicationLicenses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.ApplicationLicenses" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationLicenses As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ApplicationLicenses : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.ApplicationLicenses" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.applicationLicenses")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a117b-142">取得またはアプリケーションのライセンスの一覧をバッチ サービスは、プール内の各コンピューティング ノードで使用できるように設定します。</span><span class="sxs-lookup"><span data-stu-id="a117b-142">Gets or sets the list of application licenses the Batch service will make available on each compute node in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="a117b-143">アプリケーションのライセンスの一覧は、使用できる Batch サービス アプリケーションのライセンスのサブセットである必要があります。</span><span class="sxs-lookup"><span data-stu-id="a117b-143">The list of application licenses must be a subset of available Batch service application licenses.</span></span> <span data-ttu-id="a117b-144">これはサポートされていない要求されるライセンスと、プールの作成は失敗します。</span><span class="sxs-lookup"><span data-stu-id="a117b-144">If a license is requested which is not supported, pool creation will fail.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationPackages">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference&gt; ApplicationPackages { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference&gt; ApplicationPackages" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.ApplicationPackages" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationPackages As IList(Of ApplicationPackageReference)" />
      <MemberSignature Language="F#" Value="member this.ApplicationPackages : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.ApplicationPackages" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.applicationPackages")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a117b-145">取得またはプール内の各コンピューティング ノードにインストールされているアプリケーション パッケージの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="a117b-145">Gets or sets the list of application packages to be installed on each compute node in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="a117b-146">アプリケーション パッケージへの変更は、プールに参加するすべての新しいコンピューティング ノードに影響するが、コンピューティング ノードを再起動または再イメージ化されるまで、プールに既に存在するには影響しません。</span><span class="sxs-lookup"><span data-stu-id="a117b-146">Changes to application packages affect all new compute nodes joining the pool, but do not affect compute nodes that are already in the pool until they are rebooted or reimaged.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoScaleRun">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.AutoScaleRun AutoScaleRun { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.AutoScaleRun AutoScaleRun" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.AutoScaleRun" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AutoScaleRun As AutoScaleRun" />
      <MemberSignature Language="F#" Value="member this.AutoScaleRun : Microsoft.Azure.Management.Batch.Models.AutoScaleRun" Usage="Microsoft.Azure.Management.Batch.Models.Pool.AutoScaleRun" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.autoScaleRun")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.AutoScaleRun</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a117b-147">自動スケール式の前回の実行からの結果とエラーを取得します。</span><span class="sxs-lookup"><span data-stu-id="a117b-147">Gets the results and errors from the last execution of the autoscale formula.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="a117b-148">このプロパティが専用場合、プールは自動的にスケーリング、つまり autoScaleSettings が使用されます。</span><span class="sxs-lookup"><span data-stu-id="a117b-148">This property is set only if the pool automatically scales, i.e. autoScaleSettings are used.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Certificates">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.CertificateReference&gt; Certificates { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.CertificateReference&gt; Certificates" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.Certificates" />
      <MemberSignature Language="VB.NET" Value="Public Property Certificates As IList(Of CertificateReference)" />
      <MemberSignature Language="F#" Value="member this.Certificates : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.CertificateReference&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.Certificates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.certificates")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.CertificateReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a117b-149">取得またはプール内の各コンピューティング ノードにインストールされている証明書の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="a117b-149">Gets or sets the list of certificates to be installed on each compute node in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="a117b-150">Windows では、ノードを計算するため、バッチ サービスは、場所と指定された証明書ストアに証明書をインストールします。</span><span class="sxs-lookup"><span data-stu-id="a117b-150">For Windows compute nodes, the Batch service installs the certificates to the specified certificate store and location.</span></span> <span data-ttu-id="a117b-151">Linux 計算ノードでは、証明書は、タスクの作業ディレクトリと変数 AZ_BATCH_CERTIFICATES_DIR がこの場所にクエリするタスクに指定された環境の内部ディレクトリに保存されます。</span><span class="sxs-lookup"><span data-stu-id="a117b-151">For Linux compute nodes, the certificates are stored in a directory inside the task working directory and an environment variable AZ_BATCH_CERTIFICATES_DIR is supplied to the task to query for this location.</span></span> <span data-ttu-id="a117b-152">'RemoteUser' の可視性を持つ証明書は、'certs' ディレクトリは、ユーザーのホーム ディレクトリに作成 (など/home/{ユーザー名}/certs) および証明書はそのディレクトリに配置します。</span><span class="sxs-lookup"><span data-stu-id="a117b-152">For certificates with visibility of 'remoteUser', a 'certs' directory is created in the user's home directory (e.g., /home/{user-name}/certs) and certificates are placed in that directory.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.CreationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreationTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Batch.Models.Pool.CreationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.creationTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a117b-153">プールの作成時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="a117b-153">Gets the creation time of the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentDedicatedNodes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; CurrentDedicatedNodes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; CurrentDedicatedNodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.CurrentDedicatedNodes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentDedicatedNodes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.CurrentDedicatedNodes : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Batch.Models.Pool.CurrentDedicatedNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.currentDedicatedNodes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a117b-154">現在、プール内のコンピューティング ノードの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="a117b-154">Gets the number of compute nodes currently in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentLowPriorityNodes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; CurrentLowPriorityNodes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; CurrentLowPriorityNodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.CurrentLowPriorityNodes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentLowPriorityNodes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.CurrentLowPriorityNodes : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Batch.Models.Pool.CurrentLowPriorityNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.currentLowPriorityNodes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a117b-155">数を取得します低優先度の計算ノード現在プールします。</span><span class="sxs-lookup"><span data-stu-id="a117b-155">Gets the number of low priority compute nodes currently in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeploymentConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration DeploymentConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration DeploymentConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.DeploymentConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property DeploymentConfiguration As DeploymentConfiguration" />
      <MemberSignature Language="F#" Value="member this.DeploymentConfiguration : Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.DeploymentConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.deploymentConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a117b-156">このプロパティは、プールのノードを展開する方法 - について説明を取得または設定のクラウド サービスまたは仮想マシンを使用します。</span><span class="sxs-lookup"><span data-stu-id="a117b-156">Gets or sets this property describes how the pool nodes will be deployed - using Cloud Services or Virtual Machines.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="a117b-157">CloudServiceConfiguration を使用するには、VirtualMachineConfiguration で Azure Virtual Machines (IaaS) を使用して、Azure クラウド サービス (PaaS) を使用して、ノードを作成することを指定します。</span><span class="sxs-lookup"><span data-stu-id="a117b-157">Using CloudServiceConfiguration specifies that the nodes should be creating using Azure Cloud Services (PaaS), while VirtualMachineConfiguration uses Azure Virtual Machines (IaaS).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.displayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a117b-158">取得またはプールの表示名を設定します。</span><span class="sxs-lookup"><span data-stu-id="a117b-158">Gets or sets the display name for the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="a117b-159">表示名は一意でない必要があり、最大で 1,024 の最大長の Unicode 文字を含めることができます。</span><span class="sxs-lookup"><span data-stu-id="a117b-159">The display name need not be unique and can contain any Unicode characters up to a maximum length of 1024.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="InterNodeCommunication">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Batch.Models.InterNodeCommunicationState&gt; InterNodeCommunication { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.InterNodeCommunicationState&gt; InterNodeCommunication" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.InterNodeCommunication" />
      <MemberSignature Language="VB.NET" Value="Public Property InterNodeCommunication As Nullable(Of InterNodeCommunicationState)" />
      <MemberSignature Language="F#" Value="member this.InterNodeCommunication : Nullable&lt;Microsoft.Azure.Management.Batch.Models.InterNodeCommunicationState&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.InterNodeCommunication" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.interNodeCommunication")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.InterNodeCommunicationState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a117b-160">取得またはプールがノード間で直接通信を許可するかどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="a117b-160">Gets or sets whether the pool permits direct communication between nodes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="a117b-161">これは、制限にノードをプールに割り当てることができます。</span><span class="sxs-lookup"><span data-stu-id="a117b-161">This imposes restrictions on which nodes can be assigned to the pool.</span></span> <span data-ttu-id="a117b-162">この値を有効にすると、プールに割り当てられるノードの要求された数の可能性を低減できます。</span><span class="sxs-lookup"><span data-stu-id="a117b-162">Enabling this value can reduce the chance of the requested number of nodes to be allocated in the pool.</span></span> <span data-ttu-id="a117b-163">指定しない場合、この値が '無効' に既定値です。</span><span class="sxs-lookup"><span data-stu-id="a117b-163">If not specified, this value defaults to 'Disabled'.</span></span> <span data-ttu-id="a117b-164">使用可能な値が含まれます: 'Enabled'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="a117b-164">Possible values include: 'Enabled', 'Disabled'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModified">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastModified { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastModified" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.LastModified" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastModified As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastModified : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Batch.Models.Pool.LastModified" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lastModified")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a117b-165">プールの最終更新時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="a117b-165">Gets the last modified time of the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="a117b-166">これは、前回 targetDedicatedNodes や autoScaleSettings などのプール レベル データが変更されました。</span><span class="sxs-lookup"><span data-stu-id="a117b-166">This is the last time at which the pool level data, such as the targetDedicatedNodes or autoScaleSettings, changed.</span></span> <span data-ttu-id="a117b-167">コンピューティング ノードの状態を変更するなど、ノード レベルの変更には考慮されません。</span><span class="sxs-lookup"><span data-stu-id="a117b-167">It does not factor in node-level changes such as a compute node changing state.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxTasksPerNode">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxTasksPerNode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxTasksPerNode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.MaxTasksPerNode" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxTasksPerNode As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxTasksPerNode : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.MaxTasksPerNode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maxTasksPerNode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a117b-168">取得またはプール内の 1 つのコンピューティング ノードで同時に実行できるタスクの最大数を設定します。</span><span class="sxs-lookup"><span data-stu-id="a117b-168">Gets or sets the maximum number of tasks that can run concurrently on a single compute node in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.MetadataItem&gt; Metadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.MetadataItem&gt; Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public Property Metadata As IList(Of MetadataItem)" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.MetadataItem&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.Metadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.metadata")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.MetadataItem&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a117b-169">取得またはメタデータとしてプールに関連付けられている名前と値のペアの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="a117b-169">Gets or sets a list of name-value pairs associated with the pool as metadata.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="a117b-170">バッチ サービスがメタデータに意味を割り当てませんこれは、ユーザー コードを使用するためだけです。</span><span class="sxs-lookup"><span data-stu-id="a117b-170">The Batch service does not assign any meaning to metadata; it is solely for the use of user code.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.NetworkConfiguration NetworkConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.NetworkConfiguration NetworkConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.NetworkConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkConfiguration As NetworkConfiguration" />
      <MemberSignature Language="F#" Value="member this.NetworkConfiguration : Microsoft.Azure.Management.Batch.Models.NetworkConfiguration with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.NetworkConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.networkConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.NetworkConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a117b-171">取得またはプールのネットワーク構成を設定します。</span><span class="sxs-lookup"><span data-stu-id="a117b-171">Gets or sets the network configuration for the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Batch.Models.PoolProvisioningState&gt; ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.PoolProvisioningState&gt; ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As Nullable(Of PoolProvisioningState)" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Nullable&lt;Microsoft.Azure.Management.Batch.Models.PoolProvisioningState&gt;" Usage="Microsoft.Azure.Management.Batch.Models.Pool.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.PoolProvisioningState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
             <span data-ttu-id="a117b-172">プールの現在の状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="a117b-172">Gets the current state of the pool.</span></span>
             </summary>
        <value>To be added.</value>
        <remarks>
             <span data-ttu-id="a117b-173">値は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="a117b-173">Values are:</span></span>
            
             <span data-ttu-id="a117b-174">成功 - プールは、コンピューティング ノードの可用性の対象のタスクを実行できるようにします。</span><span class="sxs-lookup"><span data-stu-id="a117b-174">Succeeded - The pool is available to run tasks subject to the availability of compute nodes.</span></span>
             <span data-ttu-id="a117b-175">削除すると、ユーザーが、プールが削除されることを要求しましたが、削除操作がまだ完了していません。</span><span class="sxs-lookup"><span data-stu-id="a117b-175">Deleting - The user has requested that the pool be deleted, but the delete operation has not yet completed.</span></span> <span data-ttu-id="a117b-176">使用可能な値が含まれます: は ' Succeeded'、'削除'</span><span class="sxs-lookup"><span data-stu-id="a117b-176">Possible values include: 'Succeeded', 'Deleting'</span></span>
             </remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningStateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ProvisioningStateTransitionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ProvisioningStateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.ProvisioningStateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningStateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ProvisioningStateTransitionTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Batch.Models.Pool.ProvisioningStateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningStateTransitionTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a117b-177">プールが、現在の状態を入力する時間を取得します。</span><span class="sxs-lookup"><span data-stu-id="a117b-177">Gets the time at which the pool entered its current state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResizeOperationStatus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus ResizeOperationStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus ResizeOperationStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.ResizeOperationStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResizeOperationStatus As ResizeOperationStatus" />
      <MemberSignature Language="F#" Value="member this.ResizeOperationStatus : Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus" Usage="Microsoft.Azure.Management.Batch.Models.Pool.ResizeOperationStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.resizeOperationStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a117b-178">取得には、現在または最近完了したサイズ変更操作に関する詳細情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="a117b-178">Gets contains details about the current or last completed resize operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScaleSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.ScaleSettings ScaleSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.ScaleSettings ScaleSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.ScaleSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property ScaleSettings As ScaleSettings" />
      <MemberSignature Language="F#" Value="member this.ScaleSettings : Microsoft.Azure.Management.Batch.Models.ScaleSettings with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.ScaleSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.scaleSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.ScaleSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a117b-179">取得または設定には、プール内のノードの数の構成を設定します。</span><span class="sxs-lookup"><span data-stu-id="a117b-179">Gets or sets settings which configure the number of nodes in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.StartTask StartTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.StartTask StartTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.StartTask" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTask As StartTask" />
      <MemberSignature Language="F#" Value="member this.StartTask : Microsoft.Azure.Management.Batch.Models.StartTask with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.StartTask" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.startTask")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.StartTask</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a117b-180">取得または各コンピューティング ノードで、プールに参加を実行する指定されたタスクを設定します。</span><span class="sxs-lookup"><span data-stu-id="a117b-180">Gets or sets a task specified to run on each compute node as it joins the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="a117b-181">修正プログラム (更新) 操作では、このプロパティは、プールから、開始タスクを削除する空のオブジェクトに設定できます。</span><span class="sxs-lookup"><span data-stu-id="a117b-181">In an PATCH (update) operation, this property can be set to an empty object to remove the start task from the pool.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskSchedulingPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.TaskSchedulingPolicy TaskSchedulingPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.TaskSchedulingPolicy TaskSchedulingPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.TaskSchedulingPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property TaskSchedulingPolicy As TaskSchedulingPolicy" />
      <MemberSignature Language="F#" Value="member this.TaskSchedulingPolicy : Microsoft.Azure.Management.Batch.Models.TaskSchedulingPolicy with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.TaskSchedulingPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.taskSchedulingPolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.TaskSchedulingPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a117b-182">取得またはタスクのプール内のコンピューティング ノード間で配分する方法を設定します。</span><span class="sxs-lookup"><span data-stu-id="a117b-182">Gets or sets how tasks are distributed across compute nodes in a pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserAccounts">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.UserAccount&gt; UserAccounts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.UserAccount&gt; UserAccounts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.UserAccounts" />
      <MemberSignature Language="VB.NET" Value="Public Property UserAccounts As IList(Of UserAccount)" />
      <MemberSignature Language="F#" Value="member this.UserAccounts : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.UserAccount&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.UserAccounts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.userAccounts")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.UserAccount&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a117b-183">取得またはプール内の各ノード上に作成されるユーザー アカウントの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="a117b-183">Gets or sets the list of user accounts to be created on each node in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.Pool.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="pool.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a117b-184">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="a117b-184">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a117b-185">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a117b-185">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VmSize">
      <MemberSignature Language="C#" Value="public string VmSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VmSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.VmSize" />
      <MemberSignature Language="VB.NET" Value="Public Property VmSize As String" />
      <MemberSignature Language="F#" Value="member this.VmSize : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.VmSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.vmSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a117b-186">取得またはプール内の仮想マシンのサイズを設定します。</span><span class="sxs-lookup"><span data-stu-id="a117b-186">Gets or sets the size of virtual machines in the pool.</span></span> <span data-ttu-id="a117b-187">プール内のすべての Vm は、同じサイズです。</span><span class="sxs-lookup"><span data-stu-id="a117b-187">All VMs in a pool are the same size.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="a117b-188">クラウド サービス プール (プール cloudServiceConfiguration で作成された) の仮想マシンの利用可能なサイズについては、クラウド サービス (http://azure.microsoft.com/documentation/articles/cloud-services-sizes-specs/) のサイズを参照してください。</span><span class="sxs-lookup"><span data-stu-id="a117b-188">For information about available sizes of virtual machines for Cloud Services pools (pools created with cloudServiceConfiguration), see Sizes for Cloud Services (http://azure.microsoft.com/documentation/articles/cloud-services-sizes-specs/).</span></span>
            <span data-ttu-id="a117b-189">バッチには、ExtraSmall を除くすべてのクラウド サービス VM サイズがサポートしています。</span><span class="sxs-lookup"><span data-stu-id="a117b-189">Batch supports all Cloud Services VM sizes except ExtraSmall.</span></span> <span data-ttu-id="a117b-190">(プール virtualMachineConfiguration で作成した) 仮想マシンのマーケットプ レースからイメージを使用するプールの利用可能な VM サイズについては (Linux) (https://azure.microsoft.com/documentation/articles/ の仮想マシンのサイズを参照してください。仮想マシンの linux-サイズ/) または仮想マシン (Windows) (https://azure.microsoft.com/documentation/articles/virtual-machines-windows-sizes/) のサイズ。</span><span class="sxs-lookup"><span data-stu-id="a117b-190">For information about available VM sizes for pools using images from the Virtual Machines Marketplace (pools created with virtualMachineConfiguration) see Sizes for Virtual Machines (Linux) (https://azure.microsoft.com/documentation/articles/virtual-machines-linux-sizes/) or Sizes for Virtual Machines (Windows) (https://azure.microsoft.com/documentation/articles/virtual-machines-windows-sizes/).</span></span>
            <span data-ttu-id="a117b-191">バッチには、STANDARD_A0 と premium storage (STANDARD_GS、STANDARD_DS、および STANDARD_DSV2 シリーズ) でそれらを除くすべての Azure VM サイズがサポートしています。</span><span class="sxs-lookup"><span data-stu-id="a117b-191">Batch supports all Azure VM sizes except STANDARD_A0 and those with premium storage (STANDARD_GS, STANDARD_DS, and STANDARD_DSV2 series).</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>