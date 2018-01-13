<Type Name="IStatefulServiceReplica" FullName="System.Fabric.IStatefulServiceReplica">
  <TypeSignature Language="C#" Value="public interface IStatefulServiceReplica" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStatefulServiceReplica" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IStatefulServiceReplica" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStatefulServiceReplica" />
  <TypeSignature Language="F#" Value="type IStatefulServiceReplica = interface" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="ee6b8-101">スタートアップ、初期化、ロールの変更、およびシャット ダウンなど、レプリカのライフ サイクルを制御する動作を定義します。</span><span class="sxs-lookup"><span data-stu-id="ee6b8-101">Defines behavior that governs the lifecycle of a replica, such as startup, initialization, role changes, and shutdown.</span></span> </para>
    </summary>
    <remarks>
      <para>
                <span data-ttu-id="ee6b8-102">ステートフルなサービスの種類は、このインターフェイスを実装する必要があります。</span><span class="sxs-lookup"><span data-stu-id="ee6b8-102">Stateful service types must implement this interface.</span></span> <span data-ttu-id="ee6b8-103"><see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.services.runtime.statefulservice">信頼性の高いステートフル サービス</see>このインターフェイスを実装し、レプリカのライフ サイクルを内部的に処理します。</span><span class="sxs-lookup"><span data-stu-id="ee6b8-103">The <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.services.runtime.statefulservice">Reliable Stateful service</see> implements this interface and handles replica lifecycle internally.</span></span> </para>
      <para>
                <span data-ttu-id="ee6b8-104">ステートフルなサービスの種類のロジックには、プライマリ レプリカ上で呼び出される動作とセカンダリ レプリカで呼び出される動作が含まれています。</span><span class="sxs-lookup"><span data-stu-id="ee6b8-104">The logic of a stateful service type includes behavior that is invoked on primary replicas and behavior that is invoked on secondary replicas.</span></span></para>
      <para>
                <span data-ttu-id="ee6b8-105">サービスの作成者が作成する場合は、指定された使用<see cref="T:System.Fabric.FabricReplicator" />、サービスを実装する必要がありますも、<see cref="T:System.Fabric.IStateProvider" />の実装を使用する<see cref="T:System.Fabric.IStateReplicator" />はによって提供される<see cref="T:System.Fabric.FabricReplicator" />です。</span><span class="sxs-lookup"><span data-stu-id="ee6b8-105">If the service author wants to make use of the provided <see cref="T:System.Fabric.FabricReplicator" />, then the service must also implement <see cref="T:System.Fabric.IStateProvider" /> to use the implementation of <see cref="T:System.Fabric.IStateReplicator" /> that is provided by <see cref="T:System.Fabric.FabricReplicator" />.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="Abort">
      <MemberSignature Language="C#" Value="public void Abort ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Abort() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatefulServiceReplica.Abort" />
      <MemberSignature Language="VB.NET" Value="Public Sub Abort ()" />
      <MemberSignature Language="F#" Value="abstract member Abort : unit -&gt; unit" Usage="iStatefulServiceReplica.Abort " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="ee6b8-106">サービスのレプリカが異常終了します。</span><span class="sxs-lookup"><span data-stu-id="ee6b8-106">Ungracefully terminates the service replica.</span></span></para>
        </summary>
        <remarks>
          <para><span data-ttu-id="ee6b8-107">Service Fabric プロセスのシャット ダウンとの使用によって生じる問題をネットワーク<see cref="M:System.Fabric.IServicePartition.ReportFault(System.Fabric.FaultType)" />レポートに、<see cref="F:System.Fabric.FaultType.Permanent" />フォールトが異常終了の例を示します。</span><span class="sxs-lookup"><span data-stu-id="ee6b8-107">Network issues resulting in Service Fabric process shutdown and the use of <see cref="M:System.Fabric.IServicePartition.ReportFault(System.Fabric.FaultType)" /> to report a <see cref="F:System.Fabric.FaultType.Permanent" /> fault are examples of ungraceful termination.</span></span> <span data-ttu-id="ee6b8-108">このメソッドが呼び出されると、サービス レプリカ必要がありますすぐにリリースしのすべての参照をクリーンアップし、返します。</span><span class="sxs-lookup"><span data-stu-id="ee6b8-108">When this method is invoked, the service replica should immediately release and clean up all references and return.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ChangeRoleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; ChangeRoleAsync (System.Fabric.ReplicaRole newRole, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; ChangeRoleAsync(valuetype System.Fabric.ReplicaRole newRole, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatefulServiceReplica.ChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ChangeRoleAsync : System.Fabric.ReplicaRole * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="iStatefulServiceReplica.ChangeRoleAsync (newRole, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1006:DoNotNestGenericTypesInMemberSignatures", Justification="Approved public API.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="newRole" Type="System.Fabric.ReplicaRole" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="newRole">
          <para><span data-ttu-id="ee6b8-109">更新された<see cref="T:System.Fabric.ReplicaRole" />このレプリカに遷移させなければならないことです。</span><span class="sxs-lookup"><span data-stu-id="ee6b8-109">The updated <see cref="T:System.Fabric.ReplicaRole" /> that this replica should transition to.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="ee6b8-110"><see cref="T:System.Threading.CancellationToken" />操作を確認するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="ee6b8-110">The <see cref="T:System.Threading.CancellationToken" /> object that the operation is observing.</span></span> <span data-ttu-id="ee6b8-111">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="ee6b8-111">It can be used to send a notification that the operation should be canceled.</span></span>
            <span data-ttu-id="ee6b8-112">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="ee6b8-112">Note that cancellation is advisory and that the operation might still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="ee6b8-113">サービス レプリカのロールを変更を 1 つの<see cref="T:System.Fabric.ReplicaRole" />です。</span><span class="sxs-lookup"><span data-stu-id="ee6b8-113">Changes the role of the service replica to one of the <see cref="T:System.Fabric.ReplicaRole" />.</span></span> </para>
        </summary>
        <returns>
          <para><span data-ttu-id="ee6b8-114">返します<see cref="T:System.Threading.Tasks.Task`1" />型の<see cref="T:System.String" />、サービス ファブリックの名前付けを使用して、レプリカに関連付けるには、サービスの新しい接続アドレス。</span><span class="sxs-lookup"><span data-stu-id="ee6b8-114">Returns <see cref="T:System.Threading.Tasks.Task`1" /> of type <see cref="T:System.String" />, the service’s new connection address that is to be associated with the replica via Service Fabric Naming.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="ee6b8-115">新しいロールは、パラメーターとして示されます。</span><span class="sxs-lookup"><span data-stu-id="ee6b8-115">The new role is indicated as a parameter.</span></span> <span data-ttu-id="ee6b8-116">ときに、サービス ロールに移行する、新しい、サービスが、現在リッスン アドレスを更新することです。</span><span class="sxs-lookup"><span data-stu-id="ee6b8-116">When the service transitions to the new role, the service has a chance to update its current listening address.</span></span>
            <span data-ttu-id="ee6b8-117">リッスン アドレスは、電子メール アドレス、クライアントが接続する経由で返されます 1、 <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.services.client.servicepartitionresolver#Microsoft_ServiceFabric_Services_Client_ServicePartitionResolver_ResolveAsync_System_Fabric_ResolvedServicePartition_System_Threading_CancellationToken_">ResolveAsync</see> API です。</span><span class="sxs-lookup"><span data-stu-id="ee6b8-117">The listening address is the address where clients connect to it and the one returned via the <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.services.client.servicepartitionresolver#Microsoft_ServiceFabric_Services_Client_ServicePartitionResolver_ResolveAsync_System_Fabric_ResolvedServicePartition_System_Threading_CancellationToken_">ResolveAsync</see> API.</span></span> <span data-ttu-id="ee6b8-118">クライアントからの通信が予想される場合、ポートなどの一部のリソースを要求のみにプライマリ レプリカであるときに、サービスが有効にします。</span><span class="sxs-lookup"><span data-stu-id="ee6b8-118">This enables the service when it is a primary replica to only claim some resources such as ports when communication from clients is expected.</span></span></para>
          <seealso href="https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-communication" />
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatefulServiceReplica.CloseAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iStatefulServiceReplica.CloseAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">
          <para><span data-ttu-id="ee6b8-119"><see cref="T:System.Threading.CancellationToken" />操作を確認するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="ee6b8-119">The <see cref="T:System.Threading.CancellationToken" /> object that the operation is observing.</span></span> <span data-ttu-id="ee6b8-120">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="ee6b8-120">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="ee6b8-121">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="ee6b8-121">Note that cancellation is advisory and that the operation might still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="ee6b8-122">シャット ダウンすると、サービスのレプリカを適切に閉じます。</span><span class="sxs-lookup"><span data-stu-id="ee6b8-122">Closes the service replica gracefully when it is being shut down.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="ee6b8-123"><see cref="T:System.Threading.Tasks.Task" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="ee6b8-123">Returns <see cref="T:System.Threading.Tasks.Task" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Initialize">
      <MemberSignature Language="C#" Value="public void Initialize (System.Fabric.StatefulServiceInitializationParameters initializationParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Initialize(class System.Fabric.StatefulServiceInitializationParameters initializationParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatefulServiceReplica.Initialize(System.Fabric.StatefulServiceInitializationParameters)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Initialize (initializationParameters As StatefulServiceInitializationParameters)" />
      <MemberSignature Language="F#" Value="abstract member Initialize : System.Fabric.StatefulServiceInitializationParameters -&gt; unit" Usage="iStatefulServiceReplica.Initialize initializationParameters" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="initializationParameters" Type="System.Fabric.StatefulServiceInitializationParameters" />
      </Parameters>
      <Docs>
        <param name="initializationParameters">
          <para><span data-ttu-id="ee6b8-124"><see cref="T:System.Fabric.StatefulServiceInitializationParameters" />このレプリカにします。</span><span class="sxs-lookup"><span data-stu-id="ee6b8-124">The <see cref="T:System.Fabric.StatefulServiceInitializationParameters" /> for this replica.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="ee6b8-125">新しく作成されたサービスのレプリカを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ee6b8-125">Initializes a newly created service replica.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.IReplicator&gt; OpenAsync (System.Fabric.ReplicaOpenMode openMode, System.Fabric.IStatefulServicePartition partition, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.IReplicator&gt; OpenAsync(valuetype System.Fabric.ReplicaOpenMode openMode, class System.Fabric.IStatefulServicePartition partition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatefulServiceReplica.OpenAsync(System.Fabric.ReplicaOpenMode,System.Fabric.IStatefulServicePartition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OpenAsync : System.Fabric.ReplicaOpenMode * System.Fabric.IStatefulServicePartition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.IReplicator&gt;" Usage="iStatefulServiceReplica.OpenAsync (openMode, partition, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
        <param name="openMode">
          <para><span data-ttu-id="ee6b8-126">これは、は、Service Fabric インフラストラクチャをサポートし、コードから直接使用するものではありません。</span><span class="sxs-lookup"><span data-stu-id="ee6b8-126">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></para>
        </param>
        <param name="partition">
          <para><span data-ttu-id="ee6b8-127"><see cref="T:System.Fabric.IStatefulServicePartition" />このレプリカの情報です。</span><span class="sxs-lookup"><span data-stu-id="ee6b8-127">The <see cref="T:System.Fabric.IStatefulServicePartition" /> information for this replica.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="ee6b8-128"><see cref="T:System.Threading.CancellationToken" />操作を確認するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="ee6b8-128">The <see cref="T:System.Threading.CancellationToken" /> object that the operation is observing.</span></span> <span data-ttu-id="ee6b8-129">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="ee6b8-129">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="ee6b8-130">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="ee6b8-130">Note that cancellation is advisory and that the operation might still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="ee6b8-131">その他の操作を実行できるように、初期化されたサービスのレプリカが開きます。</span><span class="sxs-lookup"><span data-stu-id="ee6b8-131">Opens an initialized service replica so that additional actions can be taken.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="ee6b8-132">返します<see cref="T:System.Threading.Tasks.Task`1" /> &lt; <see cref="T:System.Fabric.IReplicator" /> &gt;、<see cref="T:System.Fabric.IReplicator" />ステートフル サービスで使用されています。</span><span class="sxs-lookup"><span data-stu-id="ee6b8-132">Returns <see cref="T:System.Threading.Tasks.Task`1" />&lt;<see cref="T:System.Fabric.IReplicator" />&gt;, the <see cref="T:System.Fabric.IReplicator" /> that is used by the stateful service.</span></span> <span data-ttu-id="ee6b8-133">Service Fabric の実装を使用する<see cref="M:System.Fabric.IStatefulServiceReplica.OpenAsync(System.Fabric.ReplicaOpenMode,System.Fabric.IStatefulServicePartition,System.Threading.CancellationToken)" />、レプリカを返す必要があります、<see cref="T:System.Fabric.FabricReplicator" />から取得した<see cref="M:System.Fabric.IStatefulServicePartition.CreateReplicator(System.Fabric.IStateProvider,System.Fabric.ReplicatorSettings)" />です。</span><span class="sxs-lookup"><span data-stu-id="ee6b8-133">To use the Service Fabric implementation, in <see cref="M:System.Fabric.IStatefulServiceReplica.OpenAsync(System.Fabric.ReplicaOpenMode,System.Fabric.IStatefulServicePartition,System.Threading.CancellationToken)" />, the replica should return a <see cref="T:System.Fabric.FabricReplicator" /> that is obtained from  <see cref="M:System.Fabric.IStatefulServicePartition.CreateReplicator(System.Fabric.IStateProvider,System.Fabric.ReplicatorSettings)" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>