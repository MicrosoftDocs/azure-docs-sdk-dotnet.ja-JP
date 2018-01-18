<Type Name="IStateProviderReplica" FullName="Microsoft.ServiceFabric.Data.IStateProviderReplica">
  <TypeSignature Language="C#" Value="public interface IStateProviderReplica" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStateProviderReplica" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.IStateProviderReplica" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStateProviderReplica" />
  <TypeSignature Language="F#" Value="type IStateProviderReplica = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e5288-101">Service Fabric サービスと対話するの信頼性の高い状態プロバイダーの複製を実装する必要がありますメソッドを定義します。</span><span class="sxs-lookup"><span data-stu-id="e5288-101">Defines methods a reliable state provider replica must implement for Service Fabric to interact with it.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Abort">
      <MemberSignature Language="C#" Value="public void Abort ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Abort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.Abort" />
      <MemberSignature Language="VB.NET" Value="Public Sub Abort ()" />
      <MemberSignature Language="F#" Value="abstract member Abort : unit -&gt; unit" Usage="iStateProviderReplica.Abort " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e5288-102">状態プロバイダーのレプリカを強制的に中止します。</span><span class="sxs-lookup"><span data-stu-id="e5288-102">Forcefully abort the state provider replica.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="e5288-103">これは一般に、ノードで、永続的な障害が検出されたときに、または Service Fabric は、内部エラーのため、レプリカのライフ サイクルを確実に管理できませんに発生します。</span><span class="sxs-lookup"><span data-stu-id="e5288-103">This generally occurs when a permanent fault is detected on the node, or when Service Fabric cannot reliably manage the replica's life-cycle due to internal failures.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task BackupAsync (Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;bool&gt;&gt; backupCallback);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task BackupAsync(class System.Func`3&lt;class Microsoft.ServiceFabric.Data.BackupInfo, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task`1&lt;bool&gt;&gt; backupCallback) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />
      <MemberSignature Language="VB.NET" Value="Public Function BackupAsync (backupCallback As Func(Of BackupInfo, CancellationToken, Task(Of Boolean))) As Task" />
      <MemberSignature Language="F#" Value="abstract member BackupAsync : Func&lt;Microsoft.ServiceFabric.Data.BackupInfo, System.Threading.CancellationToken, System.Threading.Tasks.Task&lt;bool&gt;&gt; -&gt; System.Threading.Tasks.Task" Usage="iStateProviderReplica.BackupAsync backupCallback" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupCallback" Type="System.Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;System.Boolean&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="backupCallback"><span data-ttu-id="e5288-104">バックアップ フォルダーがローカルで作成された、ノード外に移動する準備ができているときに呼び出されるコールバック。</span><span class="sxs-lookup"><span data-stu-id="e5288-104">Callback to be called when the backup folder has been created locally and is ready to be moved out of the node.</span></span></param>
        <summary>
            <span data-ttu-id="e5288-105">これによって管理されるすべての信頼性の高い状態の完全バックアップを実行<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />です。</span><span class="sxs-lookup"><span data-stu-id="e5288-105">Performs a full backup of all reliable state managed by this <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />.</span></span>
            </summary>
        <returns><span data-ttu-id="e5288-106">非同期のバックアップ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="e5288-106">Task that represents the asynchronous backup operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="e5288-107">完全バックアップは、1 時間のタイムアウトを設定して実行されます。</span><span class="sxs-lookup"><span data-stu-id="e5288-107">A FULL backup will be performed with a one-hour timeout.</span></span>
            <span data-ttu-id="e5288-108">BackupCallback によって返されるブール値では、サービスが正常に外部の場所に、バックアップ フォルダーを移動するかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="e5288-108">Boolean returned by the backupCallback indicate whether the service was able to successfully move the backup folder to an external location.</span></span>
            <span data-ttu-id="e5288-109">False が返される場合は BackupAsync backupCallback false が返されたことを示す関連するメッセージに InvalidOperationException がスローされます。</span><span class="sxs-lookup"><span data-stu-id="e5288-109">If false is returned, BackupAsync throws InvalidOperationException with the relevant message indicating backupCallback returned false.</span></span>
            <span data-ttu-id="e5288-110">また、バックアップはマークされます失敗とします。</span><span class="sxs-lookup"><span data-stu-id="e5288-110">Also, backup will be marked as unsuccessful.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task BackupAsync (Microsoft.ServiceFabric.Data.BackupOption option, TimeSpan timeout, System.Threading.CancellationToken cancellationToken, Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;bool&gt;&gt; backupCallback);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task BackupAsync(valuetype Microsoft.ServiceFabric.Data.BackupOption option, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken, class System.Func`3&lt;class Microsoft.ServiceFabric.Data.BackupInfo, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task`1&lt;bool&gt;&gt; backupCallback) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />
      <MemberSignature Language="F#" Value="abstract member BackupAsync : Microsoft.ServiceFabric.Data.BackupOption * TimeSpan * System.Threading.CancellationToken * Func&lt;Microsoft.ServiceFabric.Data.BackupInfo, System.Threading.CancellationToken, System.Threading.Tasks.Task&lt;bool&gt;&gt; -&gt; System.Threading.Tasks.Task" Usage="iStateProviderReplica.BackupAsync (option, timeout, cancellationToken, backupCallback)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="option" Type="Microsoft.ServiceFabric.Data.BackupOption" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
        <Parameter Name="backupCallback" Type="System.Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;System.Boolean&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="option"><span data-ttu-id="e5288-111">実行するバックアップの種類。</span><span class="sxs-lookup"><span data-stu-id="e5288-111">The type of backup to perform.</span></span></param>
        <param name="timeout"><span data-ttu-id="e5288-112">この操作のタイムアウト。</span><span class="sxs-lookup"><span data-stu-id="e5288-112">The timeout for this operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="e5288-113">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="e5288-113">The token to monitor for cancellation requests.</span></span></param>
        <param name="backupCallback"><span data-ttu-id="e5288-114">バックアップ フォルダーがローカルで作成された、ノード外に移動する準備ができているときに呼び出されるコールバック。</span><span class="sxs-lookup"><span data-stu-id="e5288-114">Callback to be called when the backup folder has been created locally and is ready to be moved out of the node.</span></span></param>
        <summary>
            <span data-ttu-id="e5288-115">これによって管理されるすべての信頼性の高い状態のバックアップを実行<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />です。</span><span class="sxs-lookup"><span data-stu-id="e5288-115">Performs a backup of all reliable state managed by this <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />.</span></span>
            </summary>
        <returns><span data-ttu-id="e5288-116">非同期のバックアップ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="e5288-116">Task that represents the asynchronous backup operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="e5288-117">BackupCallback によって返されるブール値では、サービスが正常に外部の場所に、バックアップ フォルダーを移動するかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="e5288-117">Boolean returned by the backupCallback indicate whether the service was able to successfully move the backup folder to an external location.</span></span>
            <span data-ttu-id="e5288-118">False が返される場合は BackupAsync backupCallback false が返されたことを示す関連するメッセージに InvalidOperationException がスローされます。</span><span class="sxs-lookup"><span data-stu-id="e5288-118">If false is returned, BackupAsync throws InvalidOperationException with the relevant message indicating backupCallback returned false.</span></span>
            <span data-ttu-id="e5288-119">また、バックアップはマークされます失敗とします。</span><span class="sxs-lookup"><span data-stu-id="e5288-119">Also, backup will be marked as unsuccessful.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ChangeRoleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ChangeRoleAsync (System.Fabric.ReplicaRole newRole, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ChangeRoleAsync(valuetype System.Fabric.ReplicaRole newRole, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.ChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ChangeRoleAsync : System.Fabric.ReplicaRole * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iStateProviderReplica.ChangeRoleAsync (newRole, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="newRole" Type="System.Fabric.ReplicaRole" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="newRole"><span data-ttu-id="e5288-120">プライマリまたはセカンダリなど、新しいレプリカ ロール。</span><span class="sxs-lookup"><span data-stu-id="e5288-120">The new replica role, such as primary or secondary.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="e5288-121">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="e5288-121">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="e5288-122">そのロールが変更される、たとえばプライマリまたはセカンダリに、状態プロバイダーのレプリカを通知します。</span><span class="sxs-lookup"><span data-stu-id="e5288-122">Notify the state provider replica that its role is changing, for example to Primary or Secondary.</span></span>
            </summary>
        <returns><span data-ttu-id="e5288-123">非同期の変更の役割の操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="e5288-123">Task that represents the asynchronous change role operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.CloseAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iStateProviderReplica.CloseAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="e5288-124">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="e5288-124">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="e5288-125">状態プロバイダーの複製が正常にクローズします。</span><span class="sxs-lookup"><span data-stu-id="e5288-125">Gracefully close the state provider replica.</span></span>
            </summary>
        <returns><span data-ttu-id="e5288-126">非同期の close 操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="e5288-126">Task that represents the asynchronous close operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="e5288-127">これは一般に、レプリカのコードにアップグレードされている、負荷分散のため、レプリカが移動されてまたは一時的なエラーが検出されたときに発生します。</span><span class="sxs-lookup"><span data-stu-id="e5288-127">This generally occurs when the replica's code is being upgrade, the replica is being moved due to load balancing, or a transient fault is detected.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Initialize">
      <MemberSignature Language="C#" Value="public void Initialize (System.Fabric.StatefulServiceInitializationParameters initializationParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Initialize(class System.Fabric.StatefulServiceInitializationParameters initializationParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.Initialize(System.Fabric.StatefulServiceInitializationParameters)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Initialize (initializationParameters As StatefulServiceInitializationParameters)" />
      <MemberSignature Language="F#" Value="abstract member Initialize : System.Fabric.StatefulServiceInitializationParameters -&gt; unit" Usage="iStateProviderReplica.Initialize initializationParameters" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="initializationParameters" Type="System.Fabric.StatefulServiceInitializationParameters" />
      </Parameters>
      <Docs>
        <param name="initializationParameters"><span data-ttu-id="e5288-128">サービス名、パーティション id、レプリカの id、およびコード パッケージ情報などのサービスの初期化情報。</span><span class="sxs-lookup"><span data-stu-id="e5288-128">Service initialization information such as service name, partition id, replica id, and code package information.</span></span></param>
        <summary>
            <span data-ttu-id="e5288-129">サービスの初期化情報を使用して、状態プロバイダーのレプリカを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e5288-129">Initialize the state provider replica using the service initialization information.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="e5288-130">複雑な処理を初期化中に行う必要はありません。</span><span class="sxs-lookup"><span data-stu-id="e5288-130">No complex processing should be done during Initialize.</span></span> <span data-ttu-id="e5288-131">OpenAsync では、高価なまたは実行時間の長いの初期化を行う必要があります。</span><span class="sxs-lookup"><span data-stu-id="e5288-131">Expensive or long-running initialization should be done in OpenAsync.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDataLossAsync">
      <MemberSignature Language="C#" Value="public Func&lt;System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;bool&gt;&gt; OnDataLossAsync { set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`2&lt;valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task`1&lt;bool&gt;&gt; OnDataLossAsync" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.IStateProviderReplica.OnDataLossAsync" />
      <MemberSignature Language="VB.NET" Value="Public Property OnDataLossAsync As Func(Of CancellationToken, Task(Of Boolean))" />
      <MemberSignature Language="F#" Value="member this.OnDataLossAsync : Func&lt;System.Threading.CancellationToken, System.Threading.Tasks.Task&lt;bool&gt;&gt;" Usage="Microsoft.ServiceFabric.Data.IStateProviderReplica.OnDataLossAsync" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;System.Boolean&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e5288-132">関数は、疑いのあるデータ損失の可能性の中に呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="e5288-132">Function called during suspected data-loss.</span></span>
            </summary>
        <value>
            <span data-ttu-id="e5288-133">疑いのあるデータ損失の処理の一部として呼び出される関数。</span><span class="sxs-lookup"><span data-stu-id="e5288-133">Function called as part of suspected data loss processing.</span></span>
            <span data-ttu-id="e5288-134">関数は、CancellationToken はし、イベントの非同期処理を表すタスクを返す必要があります。</span><span class="sxs-lookup"><span data-stu-id="e5288-134">Function takes in CancellationToken and need to return a Task that represents the asynchronous processing of the event.</span></span>
            <span data-ttu-id="e5288-135">True を返すには、レプリカの状態が復元されていることを示します。</span><span class="sxs-lookup"><span data-stu-id="e5288-135">Returning true, indicates that the replica's state has been restored.</span></span>
            <span data-ttu-id="e5288-136">False は、レプリカの状態が変更されていないことを示します。</span><span class="sxs-lookup"><span data-stu-id="e5288-136">False indicates that the replica's state has not been changed.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.IReplicator&gt; OpenAsync (System.Fabric.ReplicaOpenMode openMode, System.Fabric.IStatefulServicePartition partition, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.IReplicator&gt; OpenAsync(valuetype System.Fabric.ReplicaOpenMode openMode, class System.Fabric.IStatefulServicePartition partition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.OpenAsync(System.Fabric.ReplicaOpenMode,System.Fabric.IStatefulServicePartition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OpenAsync : System.Fabric.ReplicaOpenMode * System.Fabric.IStatefulServicePartition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.IReplicator&gt;" Usage="iStateProviderReplica.OpenAsync (openMode, partition, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.IReplicator&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="openMode" Type="System.Fabric.ReplicaOpenMode" />
        <Parameter Name="partition" Type="System.Fabric.IStatefulServicePartition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="openMode"><span data-ttu-id="e5288-137">これが新規または既存のレプリカであるかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="e5288-137">Indicates whether this is a new or existing replica.</span></span></param>
        <param name="partition"><span data-ttu-id="e5288-138">このレプリカが属しているパーティション。</span><span class="sxs-lookup"><span data-stu-id="e5288-138">The partition this replica belongs to.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="e5288-139">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="e5288-139">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="e5288-140">使用するため、状態プロバイダーのレプリカを開きます。</span><span class="sxs-lookup"><span data-stu-id="e5288-140">Open the state provider replica for use.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e5288-141">非同期の open 操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="e5288-141">Task that represents the asynchronous open operation.</span></span> <span data-ttu-id="e5288-142">結果には、パーティション内の他の状態プロバイダーのレプリカ間で状態のレプリケーションを担当するレプリケーターが含まれています。</span><span class="sxs-lookup"><span data-stu-id="e5288-142">The result contains the replicator responsible for replicating state between other state provider replicas in the partition.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="e5288-143">この時点でのタスクを開始状態プロバイダーの初期化を拡張します。</span><span class="sxs-lookup"><span data-stu-id="e5288-143">Extended state provider initialization tasks can be started at this time.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RestoreAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RestoreAsync (string backupFolderPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RestoreAsync(string backupFolderPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.RestoreAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RestoreAsync (backupFolderPath As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member RestoreAsync : string -&gt; System.Threading.Tasks.Task" Usage="iStateProviderReplica.RestoreAsync backupFolderPath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupFolderPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="backupFolderPath">
            <span data-ttu-id="e5288-144">レプリカがから復元するディレクトリ。</span><span class="sxs-lookup"><span data-stu-id="e5288-144">The directory where the replica is to be restored from.</span></span>
            <span data-ttu-id="e5288-145">このパラメーターを null にすることはできませんを空または空白のみが含まれています。</span><span class="sxs-lookup"><span data-stu-id="e5288-145">This parameter cannot be null, empty or contain just whitespace.</span></span> <span data-ttu-id="e5288-146">UNC パスも指定することがあります。</span><span class="sxs-lookup"><span data-stu-id="e5288-146">UNC paths may also be provided.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e5288-147">によって作成されたバックアップを復元<see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />または<see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />です。</span><span class="sxs-lookup"><span data-stu-id="e5288-147">Restore a backup taken by <see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" /> or <see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />.</span></span>
            </summary>
        <returns><span data-ttu-id="e5288-148">非同期の復元操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="e5288-148">Task that represents the asynchronous restore operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="e5288-149">つまり、復元するデータが、現在のレプリカの状態より進んでいる場合、復元は完了のみ、安全な復元が実行されます。</span><span class="sxs-lookup"><span data-stu-id="e5288-149">A safe restore will be performed, meaning the restore will only be completed if the data to restore is ahead of state of the current replica.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RestoreAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RestoreAsync (string backupFolderPath, Microsoft.ServiceFabric.Data.RestorePolicy restorePolicy, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RestoreAsync(string backupFolderPath, valuetype Microsoft.ServiceFabric.Data.RestorePolicy restorePolicy, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.RestoreAsync(System.String,Microsoft.ServiceFabric.Data.RestorePolicy,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RestoreAsync : string * Microsoft.ServiceFabric.Data.RestorePolicy * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iStateProviderReplica.RestoreAsync (backupFolderPath, restorePolicy, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupFolderPath" Type="System.String" />
        <Parameter Name="restorePolicy" Type="Microsoft.ServiceFabric.Data.RestorePolicy" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="backupFolderPath">
            <span data-ttu-id="e5288-150">レプリカがから復元するディレクトリ。</span><span class="sxs-lookup"><span data-stu-id="e5288-150">The directory where the replica is to be restored from.</span></span>
            <span data-ttu-id="e5288-151">このパラメーターを null にすることはできませんを空または空白のみが含まれています。</span><span class="sxs-lookup"><span data-stu-id="e5288-151">This parameter cannot be null, empty or contain just whitespace.</span></span> <span data-ttu-id="e5288-152">UNC パスも指定することがあります。</span><span class="sxs-lookup"><span data-stu-id="e5288-152">UNC paths may also be provided.</span></span>
            </param>
        <param name="restorePolicy"><span data-ttu-id="e5288-153">復元のポリシー。</span><span class="sxs-lookup"><span data-stu-id="e5288-153">The restore policy.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="e5288-154">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="e5288-154">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="e5288-155">によって作成されたバックアップを復元<see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />または<see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />です。</span><span class="sxs-lookup"><span data-stu-id="e5288-155">Restore a backup taken by <see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" /> or <see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />.</span></span>
            </summary>
        <returns><span data-ttu-id="e5288-156">非同期の復元操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="e5288-156">Task that represents the asynchronous restore operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>