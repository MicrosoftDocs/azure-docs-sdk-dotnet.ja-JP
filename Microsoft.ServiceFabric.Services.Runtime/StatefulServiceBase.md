<Type Name="StatefulServiceBase" FullName="Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase">
  <TypeSignature Language="C#" Value="public abstract class StatefulServiceBase" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit StatefulServiceBase extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class StatefulServiceBase" />
  <TypeSignature Language="F#" Value="type StatefulServiceBase = class&#xA;    interface IStatefulUserServiceReplica" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="4033a-101">Microsoft Service Fabric が基づくステートフルな信頼性の高いサービスの基本クラスを表します。</span><span class="sxs-lookup"><span data-stu-id="4033a-101">Represents the base class for Microsoft Service Fabric based stateful reliable service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected StatefulServiceBase (System.Fabric.StatefulServiceContext serviceContext, Microsoft.ServiceFabric.Data.IStateProviderReplica2 stateProviderReplica);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Fabric.StatefulServiceContext serviceContext, class Microsoft.ServiceFabric.Data.IStateProviderReplica2 stateProviderReplica) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.#ctor(System.Fabric.StatefulServiceContext,Microsoft.ServiceFabric.Data.IStateProviderReplica2)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (serviceContext As StatefulServiceContext, stateProviderReplica As IStateProviderReplica2)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase : System.Fabric.StatefulServiceContext * Microsoft.ServiceFabric.Data.IStateProviderReplica2 -&gt; Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase" Usage="new Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase (serviceContext, stateProviderReplica)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.StatefulServiceContext" />
        <Parameter Name="stateProviderReplica" Type="Microsoft.ServiceFabric.Data.IStateProviderReplica2" />
      </Parameters>
      <Docs>
        <param name="serviceContext">
            <span data-ttu-id="4033a-102">A<see cref="T:System.Fabric.StatefulServiceContext" />レプリカ ID、パーティション ID、およびサービスの名前などの情報を提供するサービス コンテキストについて説明します。</span><span class="sxs-lookup"><span data-stu-id="4033a-102">A <see cref="T:System.Fabric.StatefulServiceContext" /> describes the service context, which it provides information like replica ID, partition ID, and service name.</span></span>
            </param>
        <param name="stateProviderReplica">
            <span data-ttu-id="4033a-103">A<see cref="T:Microsoft.ServiceFabric.Data.IStateProviderReplica2" />信頼性の高い状態プロバイダーの複製を表します。</span><span class="sxs-lookup"><span data-stu-id="4033a-103">A <see cref="T:Microsoft.ServiceFabric.Data.IStateProviderReplica2" /> represents a reliable state provider replica.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4033a-104">新しいステートフルなサービスを作成します。</span><span class="sxs-lookup"><span data-stu-id="4033a-104">Creates a new stateful service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException" />
      </Docs>
    </Member>
    <Member MemberName="BackupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task BackupAsync (Microsoft.ServiceFabric.Data.BackupDescription backupDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task BackupAsync(valuetype Microsoft.ServiceFabric.Data.BackupDescription backupDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.BackupAsync(Microsoft.ServiceFabric.Data.BackupDescription)" />
      <MemberSignature Language="F#" Value="member this.BackupAsync : Microsoft.ServiceFabric.Data.BackupDescription -&gt; System.Threading.Tasks.Task" Usage="statefulServiceBase.BackupAsync backupDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupDescription" Type="Microsoft.ServiceFabric.Data.BackupDescription" />
      </Parameters>
      <Docs>
        <param name="backupDescription">
            <span data-ttu-id="4033a-105">A<see cref="T:Microsoft.ServiceFabric.Data.BackupDescription" />バックアップ要求を記述します。</span><span class="sxs-lookup"><span data-stu-id="4033a-105">A <see cref="T:Microsoft.ServiceFabric.Data.BackupDescription" /> describing the backup request.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4033a-106">これによって管理されるすべての信頼性の高い状態のバックアップを実行<see cref="T:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase" />です。</span><span class="sxs-lookup"><span data-stu-id="4033a-106">Performs a backup of all reliable state managed by this <see cref="T:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase" />.</span></span>
            </summary>
        <returns><span data-ttu-id="4033a-107">非同期のバックアップ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="4033a-107">Task that represents the asynchronous backup operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task BackupAsync (Microsoft.ServiceFabric.Data.BackupDescription backupDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task BackupAsync(valuetype Microsoft.ServiceFabric.Data.BackupDescription backupDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.BackupAsync(Microsoft.ServiceFabric.Data.BackupDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.BackupAsync : Microsoft.ServiceFabric.Data.BackupDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="statefulServiceBase.BackupAsync (backupDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupDescription" Type="Microsoft.ServiceFabric.Data.BackupDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="backupDescription"><span data-ttu-id="4033a-108">A<see cref="T:Microsoft.ServiceFabric.Data.BackupDescription" />バックアップ要求を記述します。</span><span class="sxs-lookup"><span data-stu-id="4033a-108">A <see cref="T:Microsoft.ServiceFabric.Data.BackupDescription" /> describing the backup request.</span></span></param>
        <param name="timeout"><span data-ttu-id="4033a-109">この操作のタイムアウト。</span><span class="sxs-lookup"><span data-stu-id="4033a-109">The timeout for this operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="4033a-110">キャンセル トークンを使用して、キャンセル要求を監視します。</span><span class="sxs-lookup"><span data-stu-id="4033a-110">The cancellation token is used to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="4033a-111">これによって管理されるすべての信頼性の高い状態のバックアップを実行<see cref="T:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase" />です。</span><span class="sxs-lookup"><span data-stu-id="4033a-111">Performs a backup of all reliable state managed by this <see cref="T:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase" />.</span></span>
            </summary>
        <returns><span data-ttu-id="4033a-112">非同期のバックアップ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="4033a-112">Task that represents the asynchronous backup operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="4033a-113">BackupCallback によって返されるブール値では、サービスが正常に外部の場所に、バックアップ フォルダーを移動するかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="4033a-113">Boolean returned by the backupCallback indicate whether the service was able to successfully move the backup folder to an external location.</span></span>
            <span data-ttu-id="4033a-114">False が返される場合は BackupAsync backupCallback false が返されたことを示す関連するメッセージに InvalidOperationException がスローされます。</span><span class="sxs-lookup"><span data-stu-id="4033a-114">If false is returned, BackupAsync throws InvalidOperationException with the relevant message indicating backupCallback returned false.</span></span>
            <span data-ttu-id="4033a-115">また、バックアップはマークされます失敗とします。</span><span class="sxs-lookup"><span data-stu-id="4033a-115">Also, backup will be marked as unsuccessful.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Context">
      <MemberSignature Language="C#" Value="public System.Fabric.StatefulServiceContext Context { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.StatefulServiceContext Context" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.Context" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Context As StatefulServiceContext" />
      <MemberSignature Language="F#" Value="member this.Context : System.Fabric.StatefulServiceContext" Usage="Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.Context" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.StatefulServiceContext</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4033a-116">このステートフル サービスが動作しているサービス コンテキストを取得します。</span><span class="sxs-lookup"><span data-stu-id="4033a-116">Gets the service context that this stateful service is operating under.</span></span>
            <span data-ttu-id="4033a-117">レプリカ ID、パーティション ID、サービス名などのような情報を提供します。</span><span class="sxs-lookup"><span data-stu-id="4033a-117">It provides information like replica ID, partition ID, service name etc.</span></span>
            </summary>
        <value>
            <span data-ttu-id="4033a-118">A<see cref="T:System.Fabric.StatefulServiceContext" />レプリカ ID、パーティション ID、およびサービスの名前などの情報を提供するサービス コンテキストについて説明します。</span><span class="sxs-lookup"><span data-stu-id="4033a-118">A <see cref="T:System.Fabric.StatefulServiceContext" /> describes the service context, which it provides information like replica ID, partition ID, and service name.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceReplicaListeners">
      <MemberSignature Language="C#" Value="protected virtual System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener&gt; CreateServiceReplicaListeners ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener&gt; CreateServiceReplicaListeners() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.CreateServiceReplicaListeners" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function CreateServiceReplicaListeners () As IEnumerable(Of ServiceReplicaListener)" />
      <MemberSignature Language="F#" Value="abstract member CreateServiceReplicaListeners : unit -&gt; seq&lt;Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener&gt;&#xA;override this.CreateServiceReplicaListeners : unit -&gt; seq&lt;Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener&gt;" Usage="statefulServiceBase.CreateServiceReplicaListeners " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Runtime.IStatefulUserServiceReplica.CreateServiceReplicaListeners</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4033a-119">サービス レプリカの通信リスナーを指定するには、このメソッドをオーバーライドします。</span><span class="sxs-lookup"><span data-stu-id="4033a-119">Override this method to supply the communication listeners for the service replica.</span></span> <span data-ttu-id="4033a-120">通信リスナーによって返されるエンドポイントは、格納されている ListenerName の JSON 文字列としてのようなエンドポイントの文字列のペア</span><span class="sxs-lookup"><span data-stu-id="4033a-120">The endpoints returned by the communication listener are stored as a JSON string of ListenerName, Endpoint string pairs like</span></span> 
            <span data-ttu-id="4033a-121"><code>{"Endpoints":{"Listener1":"Endpoint1","Listener2":"Endpoint2" ...}}</code><para>信頼性の高いサービス ライフ サイクルに関する情報を参照してください https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle</para></span><span class="sxs-lookup"><span data-stu-id="4033a-121"><code>{"Endpoints":{"Listener1":"Endpoint1","Listener2":"Endpoint2" ...}}</code><para> For information about Reliable Services life cycle please see https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle </para></span></span></summary>
        <returns><span data-ttu-id="4033a-122">一覧<see cref="T:Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener" /></span><span class="sxs-lookup"><span data-stu-id="4033a-122">List of <see cref="T:Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener" /></span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAddresses">
      <MemberSignature Language="C#" Value="protected System.Collections.Generic.IReadOnlyDictionary&lt;string,string&gt; GetAddresses ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, string&gt; GetAddresses() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.GetAddresses" />
      <MemberSignature Language="VB.NET" Value="Protected Function GetAddresses () As IReadOnlyDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.GetAddresses : unit -&gt; System.Collections.Generic.IReadOnlyDictionary&lt;string, string&gt;" Usage="statefulServiceBase.GetAddresses " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4033a-123">すべてのアドレスの一覧のこのサービス レプリカとして取得 (ListenerName、エンドポイント) キーと値のペア。</span><span class="sxs-lookup"><span data-stu-id="4033a-123">Gets the list of all the addresses for this service replica as (ListenerName, Endpoint) key-value pair.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4033a-124"><see cref="T:System.Collections.Generic.IReadOnlyDictionary`2" /> (ListenerName、エンドポイント) とアドレスの一覧を含むキーと値のペア。</span><span class="sxs-lookup"><span data-stu-id="4033a-124">An <see cref="T:System.Collections.Generic.IReadOnlyDictionary`2" /> containing list of addresses as (ListenerName, Endpoint) key-value pair.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAbort">
      <MemberSignature Language="C#" Value="protected virtual void OnAbort ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnAbort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.OnAbort" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub OnAbort ()" />
      <MemberSignature Language="F#" Value="abstract member OnAbort : unit -&gt; unit&#xA;override this.OnAbort : unit -&gt; unit" Usage="statefulServiceBase.OnAbort " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Runtime.IStatefulUserServiceReplica.OnAbort</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4033a-125">サービスを中止中の通知です。</span><span class="sxs-lookup"><span data-stu-id="4033a-125">The notification that the service is being aborted.</span></span> <span data-ttu-id="4033a-126">RunAsync は、取り消し処理は中止パスには待機されなかったとして、このメソッドの実行と同時に実行可能性があります。</span><span class="sxs-lookup"><span data-stu-id="4033a-126">RunAsync MAY be running concurrently with the execution of this method, as cancellation is not awaited on the abort path.</span></span> 
            <span data-ttu-id="4033a-127"><para>信頼性の高いサービス ライフ サイクルに関する情報を参照してください https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle</para></span><span class="sxs-lookup"><span data-stu-id="4033a-127"><para> For information about Reliable Services life cycle please see https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle </para></span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnChangeRoleAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnChangeRoleAsync (System.Fabric.ReplicaRole newRole, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnChangeRoleAsync(valuetype System.Fabric.ReplicaRole newRole, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.OnChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnChangeRoleAsync : System.Fabric.ReplicaRole * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.OnChangeRoleAsync : System.Fabric.ReplicaRole * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="statefulServiceBase.OnChangeRoleAsync (newRole, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Runtime.IStatefulUserServiceReplica.OnChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="newRole" Type="System.Fabric.ReplicaRole" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="newRole"><span data-ttu-id="4033a-128">新しい<see cref="T:System.Fabric.ReplicaRole" />このサービス レプリカにします。</span><span class="sxs-lookup"><span data-stu-id="4033a-128">New <see cref="T:System.Fabric.ReplicaRole" /> for this service replica.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="4033a-129">キャンセル要求を監視するキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4033a-129">Cancellation token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="4033a-130">レプリカのロールを変更すると、最後の手順を完了する前に、このメソッドが呼び出されます<see cref="M:System.Fabric.IStatefulServiceReplica.ChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="4033a-130">This method is called when role of the replica is changing and it is the final step before completing <see cref="M:System.Fabric.IStatefulServiceReplica.ChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)" />.</span></span>
            <span data-ttu-id="4033a-131">このレプリカの内部コンポーネントの ChangeRole が完了したことを通知するには、このメソッドをオーバーライドします。</span><span class="sxs-lookup"><span data-stu-id="4033a-131">Override this method to be notified that ChangeRole has completed for this replica's internal components.</span></span>
            <span data-ttu-id="4033a-132"><para>信頼性の高いサービス ライフ サイクルに関する情報を参照してください https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle</para></span><span class="sxs-lookup"><span data-stu-id="4033a-132"><para> For information about Reliable Services life cycle please see https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle </para></span></span></summary>
        <returns>
            <span data-ttu-id="4033a-133">A<see cref="T:System.Threading.Tasks.Task" />未処理の操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="4033a-133">A <see cref="T:System.Threading.Tasks.Task" /> that represents outstanding operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCloseAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnCloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnCloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.OnCloseAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnCloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.OnCloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="statefulServiceBase.OnCloseAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Runtime.IStatefulUserServiceReplica.OnCloseAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="4033a-134">キャンセル要求を監視するキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4033a-134">Cancellation token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="4033a-135">サービスを正常に閉じるための最後の手順として、このメソッドが呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="4033a-135">This method is called as the final step of closing the service gracefully.</span></span>
            <span data-ttu-id="4033a-136">このレプリカの内部コンポーネントの終了が完了したことを通知するには、このメソッドをオーバーライドします。</span><span class="sxs-lookup"><span data-stu-id="4033a-136">Override this method to be notified that Close has completed for this replica's internal components.</span></span>
            <span data-ttu-id="4033a-137"><para>信頼性の高いサービス ライフ サイクルに関する情報を参照してください https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle</para></span><span class="sxs-lookup"><span data-stu-id="4033a-137"><para> For information about Reliable Services life cycle please see https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle </para></span></span></summary>
        <returns>
            <span data-ttu-id="4033a-138">A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理の操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="4033a-138">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDataLossAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task&lt;bool&gt; OnDataLossAsync (Microsoft.ServiceFabric.Data.RestoreContext restoreCtx, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; OnDataLossAsync(valuetype Microsoft.ServiceFabric.Data.RestoreContext restoreCtx, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.OnDataLossAsync(Microsoft.ServiceFabric.Data.RestoreContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnDataLossAsync : Microsoft.ServiceFabric.Data.RestoreContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.OnDataLossAsync : Microsoft.ServiceFabric.Data.RestoreContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="statefulServiceBase.OnDataLossAsync (restoreCtx, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="restoreCtx" Type="Microsoft.ServiceFabric.Data.RestoreContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="restoreCtx">
            <span data-ttu-id="4033a-139">A<see cref="T:Microsoft.ServiceFabric.Data.RestoreContext" />サービスを復元するために使用します。</span><span class="sxs-lookup"><span data-stu-id="4033a-139">A <see cref="T:Microsoft.ServiceFabric.Data.RestoreContext" /> to be used to restore the service.</span></span>
            </param>
        <param name="cancellationToken">
          <span data-ttu-id="4033a-140"><see cref="T:System.Threading.CancellationToken" />キャンセル要求を監視します。</span><span class="sxs-lookup"><span data-stu-id="4033a-140"><see cref="T:System.Threading.CancellationToken" /> to monitor for cancellation requests.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4033a-141">このメソッドは、疑いのあるデータの消失時に呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="4033a-141">This method is called during suspected data loss.</span></span> <span data-ttu-id="4033a-142">データの損失が発生した場合、サービスを復元するには、このメソッドをオーバーライドすることができます。</span><span class="sxs-lookup"><span data-stu-id="4033a-142">You can override this method to restore the service in case of data loss.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4033a-143">非同期の復元操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="4033a-143">A Task that represents the asynchronous restore operation.</span></span>
            <span data-ttu-id="4033a-144">True は、状態が復元されていることを示します。</span><span class="sxs-lookup"><span data-stu-id="4033a-144">True indicates that the state has been restored.</span></span>
            <span data-ttu-id="4033a-145">False は、レプリカの状態が変更されていないことを示します。</span><span class="sxs-lookup"><span data-stu-id="4033a-145">False indicates that the replica's state has not been modified.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnOpenAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnOpenAsync (System.Fabric.ReplicaOpenMode openMode, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnOpenAsync(valuetype System.Fabric.ReplicaOpenMode openMode, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.OnOpenAsync(System.Fabric.ReplicaOpenMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnOpenAsync : System.Fabric.ReplicaOpenMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.OnOpenAsync : System.Fabric.ReplicaOpenMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="statefulServiceBase.OnOpenAsync (openMode, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Runtime.IStatefulUserServiceReplica.OnOpenAsync(System.Fabric.ReplicaOpenMode,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="openMode" Type="System.Fabric.ReplicaOpenMode" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="openMode">
          <span data-ttu-id="4033a-146"><see cref="T:System.Fabric.ReplicaOpenMode" />このサービス レプリカです。</span><span class="sxs-lookup"><span data-stu-id="4033a-146"><see cref="T:System.Fabric.ReplicaOpenMode" /> for this service replica.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="4033a-147">キャンセル要求を監視するキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4033a-147">Cancellation token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="4033a-148">レプリカが開かれると、サービスを開くの最後の手順は、このメソッドが呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="4033a-148">This method is called when the replica is being opened and it is the final step of opening the service.</span></span>
            <span data-ttu-id="4033a-149">このレプリカの内部コンポーネントのオープンが完了したことを通知するには、このメソッドをオーバーライドします。</span><span class="sxs-lookup"><span data-stu-id="4033a-149">Override this method to be notified that Open has completed for this replica's internal components.</span></span>
            <span data-ttu-id="4033a-150"><para>信頼性の高いサービス ライフ サイクルに関する情報を参照してください https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle</para></span><span class="sxs-lookup"><span data-stu-id="4033a-150"><para> For information about Reliable Services life cycle please see https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle </para></span></span></summary>
        <returns>
            <span data-ttu-id="4033a-151">A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理の操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="4033a-151">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnRestoreCompletedAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnRestoreCompletedAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnRestoreCompletedAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.OnRestoreCompletedAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnRestoreCompletedAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.OnRestoreCompletedAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="statefulServiceBase.OnRestoreCompletedAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
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
          <span data-ttu-id="4033a-152"><see cref="T:System.Threading.CancellationToken" />キャンセル要求を監視します。</span><span class="sxs-lookup"><span data-stu-id="4033a-152"><see cref="T:System.Threading.CancellationToken" /> to monitor for cancellation requests.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4033a-153">バックアップの復元サービスを経由してレプリカの状態が正常に復元された場合、このメソッドが呼び出されます</span><span class="sxs-lookup"><span data-stu-id="4033a-153">This method is called when replica's state has been restored successfully via the Backup Restore service</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4033a-154">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="4033a-154">A Task that represents the asynchronous operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Partition">
      <MemberSignature Language="C#" Value="protected System.Fabric.IStatefulServicePartition Partition { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.IStatefulServicePartition Partition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.Partition" />
      <MemberSignature Language="VB.NET" Value="Protected ReadOnly Property Partition As IStatefulServicePartition" />
      <MemberSignature Language="F#" Value="member this.Partition : System.Fabric.IStatefulServicePartition" Usage="Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.Partition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.IStatefulServicePartition</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4033a-155">レプリカを現在のサービスが属するサービス パーティション。</span><span class="sxs-lookup"><span data-stu-id="4033a-155">The service partition to which current service replica belongs.</span></span> 
            </summary>
        <value>
            <span data-ttu-id="4033a-156"><see cref="T:System.Fabric.IStatefulServicePartition" />を表す、このサービス レプリカが属しているパーティション。</span><span class="sxs-lookup"><span data-stu-id="4033a-156">An <see cref="T:System.Fabric.IStatefulServicePartition" /> that represents the partition to which this service replica belongs.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task RunAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task RunAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RunAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.RunAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="statefulServiceBase.RunAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Runtime.IStatefulUserServiceReplica.RunAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="4033a-157">キャンセル要求を監視するキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4033a-157">Cancellation token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="4033a-158">このメソッドは、処理ループとして実装され、レプリカがプライマリの書き込みの状態の場合にのみ呼び出すことができます。</span><span class="sxs-lookup"><span data-stu-id="4033a-158">This method is implemented as a processing loop and will only be called when the replica is primary with write status.</span></span>
            <span data-ttu-id="4033a-159">アプリケーションのロジックでこのメソッドをオーバーライドします。</span><span class="sxs-lookup"><span data-stu-id="4033a-159">Override this method with the application logic.</span></span> 
            <span data-ttu-id="4033a-160"><para>信頼性の高いサービス ライフ サイクルに関する情報を参照してください https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle</para></span><span class="sxs-lookup"><span data-stu-id="4033a-160"><para> For information about Reliable Services life cycle please see https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle </para></span></span></summary>
        <returns>
            <span data-ttu-id="4033a-161">A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理の操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="4033a-161">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="4033a-162">オーバーライドする場合は、これらのガイドラインに従うようにしてください<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />: <list type="bullet"> <item> <description>確認<paramref name="cancellationToken" />に渡される<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />が実行と通知を受けた、1 回<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />として適切に終了します。できるだけ早くです。場合に注意してください<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />、目的の操作が完了を待つ必要はありません<paramref name="cancellationToken" />シグナル状態になる正常に返すことができます。</description></item><item><description>Service Fabric ランタイムがエスケープからすべての例外を処理しない<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />です。未処理の例外をからエスケープする場合<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />、Service Fabric ランタイムには、次のアクション、: <list type="bullet"> <item> <description>場合、 <see cref="T:System.Fabric.FabricException" /> (またはその派生例外のいずれか) からエスケープ<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />、Service Fabric実行時に、このサービス レプリカが再起動します。ヘルスの警告は、未処理の例外に関する詳細を含む Service Fabric Explorer に表示されます。</description></item><item><description>場合、<see cref="T:System.OperationCanceledException" />からエスケープ<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />Service Fabric ランタイムは、通知することによって取り消しを要求しましたが、<paramref name="cancellationToken" />に渡される<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />、Service Fabric ランタイムは、この例外を処理し、として正常に完了であると判断<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />.</description></item><item><description>場合、<see cref="T:System.OperationCanceledException" />からエスケープ<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />Service Fabric ランタイムに通知することによって取り消しを要求されません<paramref name="cancellationToken" />に渡される<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />、このサービスのレプリカをホストしているプロセスが終了します。これは、同じプロセスでホストされているその他のすべてのサービス レプリカに影響します。未処理の例外に関する詳細な情報は、Windows イベント ビューアーで表示できます。</description></item><item><description>その他の種類の例外をからエスケープする場合<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />このサービスのレプリカをホストしているプロセスが終了し、します。これは、同じプロセスでホストされているその他のすべてのサービス レプリカに影響します。未処理の例外に関する詳細な情報は、Windows イベント ビューアーで表示できます。</description></item></list></description></item></list><para>準拠するように失敗しているこれらのガイドラインにフェールオーバー、再構成またはスタックを取得するようにサービスのアップグレードが発生することができ、サービスの可用性に影響を与えることができます。</para></span><span class="sxs-lookup"><span data-stu-id="4033a-162">Please ensure you follow these guidelines when overriding <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />: <list type="bullet"><item><description> Make sure <paramref name="cancellationToken" /> passed to <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" /> is honored and once it has been signaled, <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" /> exits gracefully as soon as possible. Please note that if <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" /> has finished its intended work, it does not need to wait for <paramref name="cancellationToken" /> to be signaled and can return gracefully. </description></item><item><description> Service Fabric runtime does not handle all exception(s) escaping from <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />. If an unhandled exception escapes from <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />, then Service Fabric runtime takes following action(s): <list type="bullet"><item><description> If a <see cref="T:System.Fabric.FabricException" /> (or one of its derived exception) escapes from <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />, Service Fabric runtime will restart this service replica. A health warning will be appear in Service Fabric Explorer containing details about unhandled exception. </description></item><item><description> If an <see cref="T:System.OperationCanceledException" /> escapes from <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" /> and Service Fabric runtime has requested cancellation by signaling <paramref name="cancellationToken" /> passed to <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />, Service Fabric runtime handles this exception and considers it as graceful completion of <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />. </description></item><item><description> If an <see cref="T:System.OperationCanceledException" /> escapes from <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" /> and Service Fabric runtime has NOT requested cancellation by signaling <paramref name="cancellationToken" /> passed to <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />, the process that is hosting this service replica is brought down. This will impact all other service replicas that are hosted by the same process. The details about unhandled exceptions can be viewed in Windows Event Viewer. </description></item><item><description> If an exception of any other type escapes from <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" /> then the process that is hosting this service replica is brought down. This will impact all other service replicas that are hosted by the same process. The details about unhandled exceptions can be viewed in Windows Event Viewer. </description></item></list></description></item></list><para> Failing to conform to these guidelines can cause fail-over, reconfiguration or upgrade of your service to get stuck and can impact availability of your service. </para></span></span></remarks>
      </Docs>
    </Member>
  </Members>
</Type>