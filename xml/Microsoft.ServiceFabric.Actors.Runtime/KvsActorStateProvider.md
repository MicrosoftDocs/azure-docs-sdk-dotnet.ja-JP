<Type Name="KvsActorStateProvider" FullName="Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider">
  <TypeSignature Language="C#" Value="public sealed class KvsActorStateProvider : Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider, Microsoft.ServiceFabric.Data.IStateProviderReplica2" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit KvsActorStateProvider extends System.Object implements class Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider, class Microsoft.ServiceFabric.Data.IStateProviderReplica, class Microsoft.ServiceFabric.Data.IStateProviderReplica2" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class KvsActorStateProvider&#xA;Implements IActorStateProvider, IStateProviderReplica2" />
  <TypeSignature Language="F#" Value="type KvsActorStateProvider = class&#xA;    interface IActorStateProvider&#xA;    interface IStateProviderReplica2&#xA;    interface IStateProviderReplica&#xA;    interface VolatileLogicalTimeManager.ISnapshotHandler&#xA;    interface IActorStateProviderInternal" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Data.IStateProviderReplica2</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="b3a39-101">実装を提供<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider" />使用<see cref="T:System.Fabric.KeyValueStoreReplica" />を保存し、アクターの状態を維持します。</span><span class="sxs-lookup"><span data-stu-id="b3a39-101">Provides an implementation of <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider" /> which uses <see cref="T:System.Fabric.KeyValueStoreReplica" /> to store and persist the actor state.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KvsActorStateProvider ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b3a39-102">インスタンスを作成<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider" />既定の設定を使用します。</span><span class="sxs-lookup"><span data-stu-id="b3a39-102">Creates an instance of <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider" /> with default settings.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KvsActorStateProvider (bool enableIncrementalBackup);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(bool enableIncrementalBackup) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.#ctor(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (enableIncrementalBackup As Boolean)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider : bool -&gt; Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider" Usage="new Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider enableIncrementalBackup" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="enableIncrementalBackup" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="enableIncrementalBackup">
            <span data-ttu-id="b3a39-103">増分バックアップ機能を有効にするかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="b3a39-103">Indicates whether to enable incremental backup feature.</span></span>
            <span data-ttu-id="b3a39-104">これにより設定、<see cref="P:System.Fabric.LocalEseStoreSettings.EnableIncrementalBackup" />設定します。</span><span class="sxs-lookup"><span data-stu-id="b3a39-104">This sets the <see cref="P:System.Fabric.LocalEseStoreSettings.EnableIncrementalBackup" /> setting.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b3a39-105">インスタンスを作成<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider" />指定した設定を使用します。</span><span class="sxs-lookup"><span data-stu-id="b3a39-105">Creates an instance of <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider" /> with specified settings.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KvsActorStateProvider (bool enableIncrementalBackup, int logTruncationIntervalInMinutes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(bool enableIncrementalBackup, int32 logTruncationIntervalInMinutes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.#ctor(System.Boolean,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (enableIncrementalBackup As Boolean, logTruncationIntervalInMinutes As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider : bool * int -&gt; Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider" Usage="new Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider (enableIncrementalBackup, logTruncationIntervalInMinutes)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="enableIncrementalBackup" Type="System.Boolean" />
        <Parameter Name="logTruncationIntervalInMinutes" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="enableIncrementalBackup">
            <span data-ttu-id="b3a39-106">増分バックアップ機能を有効にするかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="b3a39-106">Indicates whether to enable incremental backup feature.</span></span>
            <span data-ttu-id="b3a39-107">これにより設定、<see cref="P:System.Fabric.LocalEseStoreSettings.EnableIncrementalBackup" />設定します。</span><span class="sxs-lookup"><span data-stu-id="b3a39-107">This sets the <see cref="P:System.Fabric.LocalEseStoreSettings.EnableIncrementalBackup" /> setting.</span></span>
            </param>
        <param name="logTruncationIntervalInMinutes">
            <span data-ttu-id="b3a39-108">その後、間隔を示す<see cref="T:System.Fabric.KeyValueStoreReplica" />ローカルの切り捨てを行うための試行がログを格納します。</span><span class="sxs-lookup"><span data-stu-id="b3a39-108">Indicates the interval after which <see cref="T:System.Fabric.KeyValueStoreReplica" /> tries to truncate local store logs.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b3a39-109">インスタンスを作成<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider" />指定した設定を使用します。</span><span class="sxs-lookup"><span data-stu-id="b3a39-109">Creates an instance of <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider" /> with specified settings.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="b3a39-110">増分バックアップが有効な場合<see cref="T:System.Fabric.KeyValueStoreReplica" />、そのトランザクション ログの管理に循環バッファーを使用しませんし、両方のログ プライマリおよびセカンダリ レプリカを定期的に切り捨てられます。</span><span class="sxs-lookup"><span data-stu-id="b3a39-110">When an incremental backup is enabled for <see cref="T:System.Fabric.KeyValueStoreReplica" />, it does not use circular buffer to manage its transaction logs and periodically truncates the logs both on primary and secondary replica(s).</span></span>
            <span data-ttu-id="b3a39-111">バックアップを自動的に移行する作業には、ログが切り捨てられます。</span><span class="sxs-lookup"><span data-stu-id="b3a39-111">The process of taking backup(s) automatically truncates logs.</span></span> <span data-ttu-id="b3a39-112">プライマリ レプリカでのユーザーのバックアップは開始されません<paramref name="logTruncationIntervalInMinutes" />、<see cref="T:System.Fabric.KeyValueStoreReplica" />自動的にログを切り捨てます。</span><span class="sxs-lookup"><span data-stu-id="b3a39-112">On the primary replica, if no user backup is initiated for <paramref name="logTruncationIntervalInMinutes" />, <see cref="T:System.Fabric.KeyValueStoreReplica" /> automatically truncates the logs.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KvsActorStateProvider (System.Fabric.ReplicatorSettings replicatorSettings = null, System.Fabric.LocalStoreSettings localStoreSettings = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ReplicatorSettings replicatorSettings, class System.Fabric.LocalStoreSettings localStoreSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.#ctor(System.Fabric.ReplicatorSettings,System.Fabric.LocalStoreSettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider : System.Fabric.ReplicatorSettings * System.Fabric.LocalStoreSettings -&gt; Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider" Usage="new Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider (replicatorSettings, localStoreSettings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="replicatorSettings" Type="System.Fabric.ReplicatorSettings" />
        <Parameter Name="localStoreSettings" Type="System.Fabric.LocalStoreSettings" />
      </Parameters>
      <Docs>
        <param name="replicatorSettings">
            <span data-ttu-id="b3a39-113">A<see cref="T:System.Fabric.ReplicatorSettings" />複製物作成会社の設定を説明します。</span><span class="sxs-lookup"><span data-stu-id="b3a39-113">A <see cref="T:System.Fabric.ReplicatorSettings" /> that describes replicator settings.</span></span>
            </param>
        <param name="localStoreSettings">
            <span data-ttu-id="b3a39-114">A<see cref="T:System.Fabric.LocalStoreSettings" />ローカル キー値ストアの設定を説明します。</span><span class="sxs-lookup"><span data-stu-id="b3a39-114">A <see cref="T:System.Fabric.LocalStoreSettings" /> that describes local key value store settings.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b3a39-115">インスタンスを作成<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider" />with 指定 replicator とローカル キーと値の設定を保存します。</span><span class="sxs-lookup"><span data-stu-id="b3a39-115">Creates an instance of <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider" /> with specified replicator and local key-value store settings.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.ActorActivatedAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IActorStateProvider.ActorActivatedAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.ActorActivatedAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#ActorActivatedAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.ActorActivatedAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorId" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="actorId"><span data-ttu-id="b3a39-116">アクティブ化したアクターの ID。</span><span class="sxs-lookup"><span data-stu-id="b3a39-116">The ID of the actor that is activated.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="b3a39-117">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="b3a39-117">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="b3a39-118">指定した id に置き換えます。 アクターのライセンス認証プロセスの一部としてこのメソッドが呼び出されます</span><span class="sxs-lookup"><span data-stu-id="b3a39-118">This method is invoked as part of the activation process of the actor with the specified Id.</span></span> 
            </summary>
        <returns> <span data-ttu-id="b3a39-119">非同期のアクターのアクティブ化通知の処理を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="b3a39-119">A task that represents the asynchronous Actor activation notification processing.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="b3a39-120">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="b3a39-120">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.ContainsStateAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;bool&gt; IActorStateProvider.ContainsStateAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, string stateName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.ContainsStateAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, string stateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#ContainsStateAsync(Microsoft.ServiceFabric.Actors.ActorId,System.String,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.ContainsStateAsync(Microsoft.ServiceFabric.Actors.ActorId,System.String,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorId" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="stateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="actorId"><span data-ttu-id="b3a39-121">状態の有無を確認する対象のアクターの ID です。</span><span class="sxs-lookup"><span data-stu-id="b3a39-121">ID of the actor for which to check state existence.</span></span></param>
        <param name="stateName"><span data-ttu-id="b3a39-122">有無を確認するアクター状態の名前です。</span><span class="sxs-lookup"><span data-stu-id="b3a39-122">Name of the actor state to check for existence.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="b3a39-123">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="b3a39-123">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="b3a39-124">アクター状態プロバイダーに指定した状態の名前を持つ、アクター状態が含まれているかどうかをチェックします。</span><span class="sxs-lookup"><span data-stu-id="b3a39-124">Checks whether the actor state provider contains an actor state with specified state name.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b3a39-125">非同期チェック操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="b3a39-125">A task that represents the asynchronous check operation.</span></span> <span data-ttu-id="b3a39-126">TResult パラメーターの値が<c>true</c>指定した名前と状態がそれ以外の場合に存在する場合は<c>false</c>です。</span><span class="sxs-lookup"><span data-stu-id="b3a39-126">The value of TResult parameter is <c>true</c> if state with specified name exists otherwise <c>false</c>.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="b3a39-127">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="b3a39-127">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.DeleteReminderAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IActorStateProvider.DeleteReminderAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, string reminderName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.DeleteReminderAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, string reminderName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#DeleteReminderAsync(Microsoft.ServiceFabric.Actors.ActorId,System.String,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.DeleteReminderAsync(Microsoft.ServiceFabric.Actors.ActorId,System.String,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorId" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="reminderName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="actorId"><span data-ttu-id="b3a39-128">アラームを削除するアクターの ID。</span><span class="sxs-lookup"><span data-stu-id="b3a39-128">The ID of the actor for which to delete the reminder.</span></span></param>
        <param name="reminderName"><span data-ttu-id="b3a39-129">削除するアラームの名前。</span><span class="sxs-lookup"><span data-stu-id="b3a39-129">The name of the reminder to delete.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="b3a39-130">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="b3a39-130">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="b3a39-131">存在する場合は、指定されたアクター アラームを削除します。</span><span class="sxs-lookup"><span data-stu-id="b3a39-131">Deletes the specified actor reminder if it exists.</span></span>
            </summary>
        <returns><span data-ttu-id="b3a39-132">非同期の削除操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="b3a39-132">A task that represents the asynchronous delete operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="b3a39-133">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="b3a39-133">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.DeleteRemindersAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IActorStateProvider.DeleteRemindersAsync (System.Collections.Generic.IReadOnlyDictionary&lt;Microsoft.ServiceFabric.Actors.ActorId,System.Collections.Generic.IReadOnlyCollection&lt;string&gt;&gt; reminderNames, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.DeleteRemindersAsync(class System.Collections.Generic.IReadOnlyDictionary`2&lt;class Microsoft.ServiceFabric.Actors.ActorId, class System.Collections.Generic.IReadOnlyCollection`1&lt;string&gt;&gt; reminderNames, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#DeleteRemindersAsync(System.Collections.Generic.IReadOnlyDictionary{Microsoft.ServiceFabric.Actors.ActorId,System.Collections.Generic.IReadOnlyCollection{System.String}},System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.DeleteRemindersAsync(System.Collections.Generic.IReadOnlyDictionary{Microsoft.ServiceFabric.Actors.ActorId,System.Collections.Generic.IReadOnlyCollection{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reminderNames" Type="System.Collections.Generic.IReadOnlyDictionary&lt;Microsoft.ServiceFabric.Actors.ActorId,System.Collections.Generic.IReadOnlyCollection&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="reminderNames"><span data-ttu-id="b3a39-134">削除するアラームのセット。</span><span class="sxs-lookup"><span data-stu-id="b3a39-134">The set of reminders to delete.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="b3a39-135">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="b3a39-135">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="b3a39-136">指定された通知のセットを削除します。</span><span class="sxs-lookup"><span data-stu-id="b3a39-136">Deletes the specified set of reminders.</span></span>
            </summary>
        <returns><span data-ttu-id="b3a39-137">非同期の削除操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="b3a39-137">A task that represents the asynchronous delete operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="b3a39-138">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="b3a39-138">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.EnumerateStateNamesAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;string&gt;&gt; IActorStateProvider.EnumerateStateNamesAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;string&gt;&gt; Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.EnumerateStateNamesAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#EnumerateStateNamesAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.EnumerateStateNamesAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorId" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="actorId"><span data-ttu-id="b3a39-139">列挙可能なを作成する対象のアクターの ID。</span><span class="sxs-lookup"><span data-stu-id="b3a39-139">The ID of the actor for which to create enumerable.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="b3a39-140">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="b3a39-140">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="b3a39-141">指定されたアクターに関連付けられているすべての状態名の列挙可能なが作成されます。</span><span class="sxs-lookup"><span data-stu-id="b3a39-141">Creates an enumerable of all the state names associated with specified actor.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b3a39-142">非同期の列挙操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="b3a39-142">A task that represents the asynchronous enumeration operation.</span></span> <span data-ttu-id="b3a39-143">TResult パラメーターの値は、指定されたアクターに関連付けられているすべての州名の列挙です。</span><span class="sxs-lookup"><span data-stu-id="b3a39-143">The value of TResult parameter is an enumerable of all state names associated with specified actor.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="b3a39-144">アクター状態プロバイダーから返された列挙子は、安全に読み取りと同時に使用し、状態プロバイダーに書き込みます。</span><span class="sxs-lookup"><span data-stu-id="b3a39-144">The enumerator returned from actor state provider is safe to use concurrently with reads and writes to the state provider.</span></span> <span data-ttu-id="b3a39-145">状態プロバイダーのスナップショットの一貫したビューを表します。</span><span class="sxs-lookup"><span data-stu-id="b3a39-145">It represents a snapshot consistent view of the state provider.</span></span>
            </remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="b3a39-146">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="b3a39-146">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.GetActorsAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Actors.Query.PagedResult&lt;Microsoft.ServiceFabric.Actors.ActorId&gt;&gt; IActorStateProvider.GetActorsAsync (int numItemsToReturn, Microsoft.ServiceFabric.Actors.Query.ContinuationToken continuationToken, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Actors.Query.PagedResult`1&lt;class Microsoft.ServiceFabric.Actors.ActorId&gt;&gt; Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.GetActorsAsync(int32 numItemsToReturn, class Microsoft.ServiceFabric.Actors.Query.ContinuationToken continuationToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#GetActorsAsync(System.Int32,Microsoft.ServiceFabric.Actors.Query.ContinuationToken,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.GetActorsAsync(System.Int32,Microsoft.ServiceFabric.Actors.Query.ContinuationToken,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Actors.Query.PagedResult&lt;Microsoft.ServiceFabric.Actors.ActorId&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="numItemsToReturn" Type="System.Int32" />
        <Parameter Name="continuationToken" Type="Microsoft.ServiceFabric.Actors.Query.ContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="numItemsToReturn"><span data-ttu-id="b3a39-147">返される要求された項目の数。</span><span class="sxs-lookup"><span data-stu-id="b3a39-147">The number of items requested to be returned.</span></span></param>
        <param name="continuationToken">
            <span data-ttu-id="b3a39-148">クエリから結果を開始する継続トークンです。</span><span class="sxs-lookup"><span data-stu-id="b3a39-148">A continuation token to start querying the results from.</span></span>
            <span data-ttu-id="b3a39-149">継続トークンの null 値は、開始、先頭の値の形式を返すことを意味します。</span><span class="sxs-lookup"><span data-stu-id="b3a39-149">A null value of continuation token means start returning values form the beginning.</span></span>
            </param>
        <param name="cancellationToken"><span data-ttu-id="b3a39-150">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="b3a39-150">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="b3a39-151">状態プロバイダーから、ActorIds を取得します。</span><span class="sxs-lookup"><span data-stu-id="b3a39-151">Gets the ActorIds from the State Provider.</span></span>
            </summary>
        <returns><span data-ttu-id="b3a39-152">サーバーへの呼び出しの非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="b3a39-152">A task that represents the asynchronous operation of call to server.</span></span></returns>
        <remarks>
            <span data-ttu-id="b3a39-153"><paramref name="continuationToken" />この API の呼び出し時にアクター状態プロバイダーの状態に対する相対パスです。</span><span class="sxs-lookup"><span data-stu-id="b3a39-153">The <paramref name="continuationToken" /> is relative to the state of actor state provider at the time of invocation of this API.</span></span> <span data-ttu-id="b3a39-154">アクターの状態プロバイダーの変更を記述する場合 (つまり新しいアクターがアクティブ化または既存のアクターが削除されます) API と継続の間にこれを呼び出す前に、状態が変更された) の前の呼び出しからのトークンを指定して、結果はされたエントリを含めることがあります既に以前の呼び出しでフェッチします。</span><span class="sxs-lookup"><span data-stu-id="b3a39-154">If the state of actor state provider changes (i.e. new actors are activated or existing actors are deleted) in between calls to this API and the continuation token from previous call (before the state was modified) is supplied, the result may contain entries that were already fetched in previous calls.</span></span>
            </remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="b3a39-155">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="b3a39-155">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.Initialize">
      <MemberSignature Language="C#" Value="void IActorStateProvider.Initialize (Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation actorTypeInformation);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.Initialize(class Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation actorTypeInformation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#Initialize(Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.Initialize(Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorTypeInformation" Type="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation" />
      </Parameters>
      <Docs>
        <param name="actorTypeInformation"><span data-ttu-id="b3a39-156">アクター クラスの型情報</span><span class="sxs-lookup"><span data-stu-id="b3a39-156">Type information of the actor class</span></span></param>
        <summary>
            <span data-ttu-id="b3a39-157">関連付けられているアクター型の型情報を使用してアクター状態プロバイダーを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b3a39-157">Initializes the actor state provider with type information of the actor type associated with it.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.LoadRemindersAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Actors.Runtime.IActorReminderCollection&gt; IActorStateProvider.LoadRemindersAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Actors.Runtime.IActorReminderCollection&gt; Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.LoadRemindersAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#LoadRemindersAsync(System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.LoadRemindersAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Actors.Runtime.IActorReminderCollection&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="b3a39-158">非同期の読み込み操作のキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b3a39-158">Cancellation token for asynchronous load operation.</span></span></param>
        <summary>
            <span data-ttu-id="b3a39-159">アクター状態プロバイダーに含まれているすべてのアラームを読み込みます。</span><span class="sxs-lookup"><span data-stu-id="b3a39-159">Loads all the reminders contained in the actor state provider.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b3a39-160">非同期ロード操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="b3a39-160">A task that represents the asynchronous load operation.</span></span> <span data-ttu-id="b3a39-161">TResult パラメーターの値は、アクター状態プロバイダーに含まれているすべてのアクター アラームのコレクションです。</span><span class="sxs-lookup"><span data-stu-id="b3a39-161">The value of TResult parameter is a collection of all actor reminders contained in the actor state provider.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="b3a39-162">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="b3a39-162">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.LoadStateAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;T&gt; IActorStateProvider.LoadStateAsync&lt;T&gt; (Microsoft.ServiceFabric.Actors.ActorId actorId, string stateName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.LoadStateAsync&lt;T&gt;(class Microsoft.ServiceFabric.Actors.ActorId actorId, string stateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#LoadStateAsync``1(Microsoft.ServiceFabric.Actors.ActorId,System.String,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.LoadStateAsync``1(Microsoft.ServiceFabric.Actors.ActorId,System.String,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="actorId" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="stateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="b3a39-163">特定の状態名に関連付けられているアクター状態の値の型。</span><span class="sxs-lookup"><span data-stu-id="b3a39-163">The type of value of actor state associated with given state name.</span></span></typeparam>
        <param name="actorId"><span data-ttu-id="b3a39-164">状態の読み込み先のアクターの ID。</span><span class="sxs-lookup"><span data-stu-id="b3a39-164">The ID of the actor for which to load the state.</span></span></param>
        <param name="stateName"><span data-ttu-id="b3a39-165">読み込みにアクター状態の名前。</span><span class="sxs-lookup"><span data-stu-id="b3a39-165">The name of the actor state to load.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="b3a39-166">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="b3a39-166">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="b3a39-167">指定された状態の名前に関連付けられているアクターの状態を読み込みます。</span><span class="sxs-lookup"><span data-stu-id="b3a39-167">Loads the actor state associated with the specified state name.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b3a39-168">非同期ロード操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="b3a39-168">A task that represents the asynchronous load operation.</span></span> <span data-ttu-id="b3a39-169">TResult のパラメーターの値には、特定の状態名に関連付けられているアクター状態の値が含まれています。</span><span class="sxs-lookup"><span data-stu-id="b3a39-169">The value of TResult parameter contains value of actor state associated with given state name.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Collections.Generic.KeyNotFoundException"><span data-ttu-id="b3a39-170">指定された状態の名前に関連付けられているアクターの状態は存在しません。</span><span class="sxs-lookup"><span data-stu-id="b3a39-170">The actor state associated with specified state name does not exist.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="b3a39-171">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="b3a39-171">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.ReminderCallbackCompletedAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IActorStateProvider.ReminderCallbackCompletedAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, Microsoft.ServiceFabric.Actors.Runtime.IActorReminder reminder, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.ReminderCallbackCompletedAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, class Microsoft.ServiceFabric.Actors.Runtime.IActorReminder reminder, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#ReminderCallbackCompletedAsync(Microsoft.ServiceFabric.Actors.ActorId,Microsoft.ServiceFabric.Actors.Runtime.IActorReminder,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.ReminderCallbackCompletedAsync(Microsoft.ServiceFabric.Actors.ActorId,Microsoft.ServiceFabric.Actors.Runtime.IActorReminder,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorId" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="reminder" Type="Microsoft.ServiceFabric.Actors.Runtime.IActorReminder" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="actorId"><span data-ttu-id="b3a39-172">アラームを所有しているアクターの ID</span><span class="sxs-lookup"><span data-stu-id="b3a39-172">The ID of the actor which own reminder</span></span></param>
        <param name="reminder"><span data-ttu-id="b3a39-173">アクター アラームが正常に完了しました。</span><span class="sxs-lookup"><span data-stu-id="b3a39-173">The actor reminder that completed successfully.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="b3a39-174">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="b3a39-174">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="b3a39-175">アラームが起動し、そのコールバックの実行が終了したときに、このメソッドが呼び出される<see cref="M:Microsoft.ServiceFabric.Actors.Runtime.IRemindable.ReceiveReminderAsync(System.String,System.Byte[],System.TimeSpan,System.TimeSpan)" />が正常にします。</span><span class="sxs-lookup"><span data-stu-id="b3a39-175">This method is invoked when a reminder fires and finishes executing its callback <see cref="M:Microsoft.ServiceFabric.Actors.Runtime.IRemindable.ReceiveReminderAsync(System.String,System.Byte[],System.TimeSpan,System.TimeSpan)" /> successfully.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b3a39-176">非同期の通知コールバックを表すタスクでは、通知の処理が完了しました。</span><span class="sxs-lookup"><span data-stu-id="b3a39-176">A task that represents the asynchronous reminder callback completed notification processing.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.RemoveActorAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IActorStateProvider.RemoveActorAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.RemoveActorAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#RemoveActorAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.RemoveActorAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorId" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="actorId"><span data-ttu-id="b3a39-177">状態を削除するアクターの ID です。</span><span class="sxs-lookup"><span data-stu-id="b3a39-177">ID of the actor for which to remove state.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="b3a39-178">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="b3a39-178">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="b3a39-179">すべての既存の状態と指定されたアクターにアトミックに関連付けられている通知を削除します。</span><span class="sxs-lookup"><span data-stu-id="b3a39-179">Removes all the existing states and reminders associated with specified actor atomically.</span></span>
            </summary>
        <returns><span data-ttu-id="b3a39-180">非同期の削除操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="b3a39-180">A task that represents the asynchronous remove operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="b3a39-181">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="b3a39-181">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.SaveReminderAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IActorStateProvider.SaveReminderAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, Microsoft.ServiceFabric.Actors.Runtime.IActorReminder reminder, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.SaveReminderAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, class Microsoft.ServiceFabric.Actors.Runtime.IActorReminder reminder, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#SaveReminderAsync(Microsoft.ServiceFabric.Actors.ActorId,Microsoft.ServiceFabric.Actors.Runtime.IActorReminder,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.SaveReminderAsync(Microsoft.ServiceFabric.Actors.ActorId,Microsoft.ServiceFabric.Actors.Runtime.IActorReminder,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorId" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="reminder" Type="Microsoft.ServiceFabric.Actors.Runtime.IActorReminder" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="actorId"><span data-ttu-id="b3a39-182">アラームを保存する対象のアクターの ID。</span><span class="sxs-lookup"><span data-stu-id="b3a39-182">The ID of the actor for which to save the reminder.</span></span></param>
        <param name="reminder"><span data-ttu-id="b3a39-183">保存するアクターのお知らせします。</span><span class="sxs-lookup"><span data-stu-id="b3a39-183">The actor reminder to save.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="b3a39-184">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="b3a39-184">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="b3a39-185">指定されたアクター アラームを保存します。</span><span class="sxs-lookup"><span data-stu-id="b3a39-185">Saves the specified actor reminder.</span></span> <span data-ttu-id="b3a39-186">指定した名前のアクター アラームが存在しない場合は、それ以外の場合と同じ名前のアクター アラームを既存のアクター アラームが更新を追加します。</span><span class="sxs-lookup"><span data-stu-id="b3a39-186">If an actor reminder with given name does not exist, it adds the actor reminder otherwise existing actor reminder with same name is updated.</span></span> 
            </summary>
        <returns><span data-ttu-id="b3a39-187">非同期の保存操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="b3a39-187">A task that represents the asynchronous save operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="b3a39-188">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="b3a39-188">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.SaveStateAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IActorStateProvider.SaveStateAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, System.Collections.Generic.IReadOnlyCollection&lt;Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange&gt; stateChanges, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.SaveStateAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, class System.Collections.Generic.IReadOnlyCollection`1&lt;class Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange&gt; stateChanges, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#SaveStateAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Collections.Generic.IReadOnlyCollection{Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange},System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.SaveStateAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Collections.Generic.IReadOnlyCollection{Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorId" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="stateChanges" Type="System.Collections.Generic.IReadOnlyCollection&lt;Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="actorId"><span data-ttu-id="b3a39-189">状態の変更を保存する対象のアクターの ID です。</span><span class="sxs-lookup"><span data-stu-id="b3a39-189">ID of the actor for which to save the state changes.</span></span></param>
        <param name="stateChanges"><span data-ttu-id="b3a39-190">状態の変更を保存するコレクション。</span><span class="sxs-lookup"><span data-stu-id="b3a39-190">Collection of state changes to save.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="b3a39-191">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="b3a39-191">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="b3a39-192">指定したアクター状態の変更のセットをアトミックに保存します。</span><span class="sxs-lookup"><span data-stu-id="b3a39-192">Saves the specified set of actor state changes atomically.</span></span>
            </summary>
        <returns><span data-ttu-id="b3a39-193">非同期の保存操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="b3a39-193">A task that represents the asynchronous save operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="b3a39-194">状態変更のコレクションには、指定された状態の名前の 1 つの項目を含める必要があります。</span><span class="sxs-lookup"><span data-stu-id="b3a39-194">The collection of state changes should contain only one item for a given state name.</span></span>
            <span data-ttu-id="b3a39-195">保存先に既に存在するか、存在しないアクター状態の更新/削除するアクターの状態を追加しようとしています。 操作は失敗します。</span><span class="sxs-lookup"><span data-stu-id="b3a39-195">The save operation will fail on trying to add an actor state which already exists or update/remove an actor state which does not exist.</span></span>
            </remarks>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="b3a39-196">ときに<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind" />は<see cref="F:Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind.None" /></span><span class="sxs-lookup"><span data-stu-id="b3a39-196">When <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind" /> is <see cref="F:Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind.None" /></span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="b3a39-197">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="b3a39-197">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.Abort">
      <MemberSignature Language="C#" Value="void IStateProviderReplica.Abort ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void Microsoft.ServiceFabric.Data.IStateProviderReplica.Abort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.Microsoft#ServiceFabric#Data#IStateProviderReplica#Abort" />
      <MemberSignature Language="VB.NET" Value="Sub Abort () Implements IStateProviderReplica.Abort" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.Abort</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b3a39-198">状態プロバイダーのレプリカを強制的に中止します。</span><span class="sxs-lookup"><span data-stu-id="b3a39-198">Forcefully abort the state provider replica.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="b3a39-199">これは一般に、ノードで、永続的な障害が検出されたときに、または Service Fabric は、内部エラーのため、レプリカのライフ サイクルを確実に管理できませんに発生します。</span><span class="sxs-lookup"><span data-stu-id="b3a39-199">This generally occurs when a permanent fault is detected on the node, or when Service Fabric cannot reliably manage the replica's life-cycle due to internal failures.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IStateProviderReplica.BackupAsync (Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;bool&gt;&gt; backupCallback);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(class System.Func`3&lt;class Microsoft.ServiceFabric.Data.BackupInfo, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task`1&lt;bool&gt;&gt; backupCallback) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.Microsoft#ServiceFabric#Data#IStateProviderReplica#BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />
      <MemberSignature Language="VB.NET" Value="Function BackupAsync (backupCallback As Func(Of BackupInfo, CancellationToken, Task(Of Boolean))) As Task Implements IStateProviderReplica.BackupAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupCallback" Type="System.Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;System.Boolean&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="backupCallback"><span data-ttu-id="b3a39-200">バックアップ フォルダーがローカルで作成された、ノード外に移動する準備ができているときに呼び出されるコールバック。</span><span class="sxs-lookup"><span data-stu-id="b3a39-200">Callback to be called when the backup folder has been created locally and is ready to be moved out of the node.</span></span></param>
        <summary>
            <span data-ttu-id="b3a39-201">このアクター状態プロバイダーによって管理されるすべての信頼性の高い状態の完全バックアップを実行します。</span><span class="sxs-lookup"><span data-stu-id="b3a39-201">Performs a full backup of all reliable state managed by this actor sate provider.</span></span>
            </summary>
        <returns><span data-ttu-id="b3a39-202">非同期のバックアップ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="b3a39-202">Task that represents the asynchronous backup operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="b3a39-203">完全バックアップは、1 時間のタイムアウトを設定して実行されます。</span><span class="sxs-lookup"><span data-stu-id="b3a39-203">A FULL backup will be performed with a one-hour timeout.</span></span>
            <span data-ttu-id="b3a39-204">BackupCallback によって返されるブール値では、サービスが正常に外部の場所に、バックアップ フォルダーを移動するかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="b3a39-204">Boolean returned by the backupCallback indicate whether the service was able to successfully move the backup folder to an external location.</span></span>
            <span data-ttu-id="b3a39-205">False が返される場合は BackupAsync backupCallback false が返されたことを示す関連するメッセージに InvalidOperationException がスローされます。</span><span class="sxs-lookup"><span data-stu-id="b3a39-205">If false is returned, BackupAsync throws InvalidOperationException with the relevant message indicating backupCallback returned false.</span></span>
            <span data-ttu-id="b3a39-206">また、バックアップはマークされます失敗とします。</span><span class="sxs-lookup"><span data-stu-id="b3a39-206">Also, backup will be marked as unsuccessful.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IStateProviderReplica.BackupAsync (Microsoft.ServiceFabric.Data.BackupOption option, TimeSpan timeout, System.Threading.CancellationToken cancellationToken, Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;bool&gt;&gt; backupCallback);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(valuetype Microsoft.ServiceFabric.Data.BackupOption option, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken, class System.Func`3&lt;class Microsoft.ServiceFabric.Data.BackupInfo, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task`1&lt;bool&gt;&gt; backupCallback) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.Microsoft#ServiceFabric#Data#IStateProviderReplica#BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider/&lt;Microsoft-ServiceFabric-Data-IStateProviderReplica-BackupAsync&gt;d__64))</AttributeName>
        </Attribute>
      </Attributes>
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
        <param name="option"><span data-ttu-id="b3a39-207">バックアップ用のオプションです。</span><span class="sxs-lookup"><span data-stu-id="b3a39-207">The option for the backup.</span></span></param>
        <param name="timeout"><span data-ttu-id="b3a39-208">バックアップのタイムアウト。</span><span class="sxs-lookup"><span data-stu-id="b3a39-208">The timeout for the backup.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="b3a39-209">バックアップのキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b3a39-209">The cancellation token for the backup.</span></span></param>
        <param name="backupCallback"><span data-ttu-id="b3a39-210">バックアップ フォルダーの準備が呼び出されるコールバック。</span><span class="sxs-lookup"><span data-stu-id="b3a39-210">The callback to be called once the backup folder is ready.</span></span></param>
        <summary>
            <span data-ttu-id="b3a39-211">このアクター状態プロバイダーによって管理される信頼性の高い状態のバックアップを実行します。</span><span class="sxs-lookup"><span data-stu-id="b3a39-211">Performs backup of reliable state managed by this actor sate provider.</span></span>
            </summary>
        <returns><span data-ttu-id="b3a39-212">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="b3a39-212">Task that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="b3a39-213">KVSActorStateProvider バックアップは、完全バックアップのみをサポートします。</span><span class="sxs-lookup"><span data-stu-id="b3a39-213">KVSActorStateProvider Backup only support Full backup.</span></span> <span data-ttu-id="b3a39-214">KVS BackupInfo にバックアップのバージョンが含まれていません。</span><span class="sxs-lookup"><span data-stu-id="b3a39-214">KVS BackupInfo does not contain backup version.</span></span>
            <span data-ttu-id="b3a39-215">バックアップのバージョンが設定されている無効にします。</span><span class="sxs-lookup"><span data-stu-id="b3a39-215">The Backup version is set to invalid.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.ChangeRoleAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IStateProviderReplica.ChangeRoleAsync (System.Fabric.ReplicaRole newRole, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IStateProviderReplica.ChangeRoleAsync(valuetype System.Fabric.ReplicaRole newRole, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.Microsoft#ServiceFabric#Data#IStateProviderReplica#ChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.ChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider/&lt;Microsoft-ServiceFabric-Data-IStateProviderReplica-ChangeRoleAsync&gt;d__60))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="newRole" Type="System.Fabric.ReplicaRole" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="newRole"><span data-ttu-id="b3a39-216">プライマリまたはセカンダリなど、新しいレプリカ ロール。</span><span class="sxs-lookup"><span data-stu-id="b3a39-216">The new replica role, such as primary or secondary.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="b3a39-217">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="b3a39-217">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="b3a39-218">そのロールが変更される、たとえばプライマリまたはセカンダリに、状態プロバイダーのレプリカを通知します。</span><span class="sxs-lookup"><span data-stu-id="b3a39-218">Notify the state provider replica that its role is changing, for example to Primary or Secondary.</span></span>
            </summary>
        <returns><span data-ttu-id="b3a39-219">非同期の変更の役割の操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="b3a39-219">Task that represents the asynchronous change role operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.CloseAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IStateProviderReplica.CloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IStateProviderReplica.CloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.Microsoft#ServiceFabric#Data#IStateProviderReplica#CloseAsync(System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.CloseAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider/&lt;Microsoft-ServiceFabric-Data-IStateProviderReplica-CloseAsync&gt;d__61))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="b3a39-220">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="b3a39-220">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="b3a39-221">状態プロバイダーの複製が正常にクローズします。</span><span class="sxs-lookup"><span data-stu-id="b3a39-221">Gracefully close the state provider replica.</span></span>
            </summary>
        <returns><span data-ttu-id="b3a39-222">非同期の close 操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="b3a39-222">Task that represents the asynchronous close operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="b3a39-223">これは一般に、レプリカのコードにアップグレードされている、負荷分散のため、レプリカが移動されてまたは一時的なエラーが検出されたときに発生します。</span><span class="sxs-lookup"><span data-stu-id="b3a39-223">This generally occurs when the replica's code is being upgrade, the replica is being moved due to load balancing, or a transient fault is detected.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.Initialize">
      <MemberSignature Language="C#" Value="void IStateProviderReplica.Initialize (System.Fabric.StatefulServiceInitializationParameters initializationParameters);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void Microsoft.ServiceFabric.Data.IStateProviderReplica.Initialize(class System.Fabric.StatefulServiceInitializationParameters initializationParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.Microsoft#ServiceFabric#Data#IStateProviderReplica#Initialize(System.Fabric.StatefulServiceInitializationParameters)" />
      <MemberSignature Language="VB.NET" Value="Sub Initialize (initializationParameters As StatefulServiceInitializationParameters) Implements IStateProviderReplica.Initialize" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.Initialize(System.Fabric.StatefulServiceInitializationParameters)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
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
            <span data-ttu-id="b3a39-224">サービス名、パーティション id、レプリカの id、およびコード パッケージ情報などのサービスの初期化情報。</span><span class="sxs-lookup"><span data-stu-id="b3a39-224">Service initialization information such as service name, partition id, replica id, and code package information.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b3a39-225">サービスの初期化情報を使用して、状態プロバイダーのレプリカを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b3a39-225">Initialize the state provider replica using the service initialization information.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="b3a39-226">複雑な処理を初期化中に行う必要はありません。</span><span class="sxs-lookup"><span data-stu-id="b3a39-226">No complex processing should be done during Initialize.</span></span> <span data-ttu-id="b3a39-227">OpenAsync では、高価なまたは実行時間の長いの初期化を行う必要があります。</span><span class="sxs-lookup"><span data-stu-id="b3a39-227">Expensive or long-running initialization should be done in OpenAsync.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.OpenAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;System.Fabric.IReplicator&gt; IStateProviderReplica.OpenAsync (System.Fabric.ReplicaOpenMode openMode, System.Fabric.IStatefulServicePartition partition, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.IReplicator&gt; Microsoft.ServiceFabric.Data.IStateProviderReplica.OpenAsync(valuetype System.Fabric.ReplicaOpenMode openMode, class System.Fabric.IStatefulServicePartition partition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.Microsoft#ServiceFabric#Data#IStateProviderReplica#OpenAsync(System.Fabric.ReplicaOpenMode,System.Fabric.IStatefulServicePartition,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.OpenAsync(System.Fabric.ReplicaOpenMode,System.Fabric.IStatefulServicePartition,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
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
        <param name="openMode"><span data-ttu-id="b3a39-228">これが新規または既存のレプリカであるかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="b3a39-228">Indicates whether this is a new or existing replica.</span></span></param>
        <param name="partition"><span data-ttu-id="b3a39-229">このレプリカが属しているパーティション。</span><span class="sxs-lookup"><span data-stu-id="b3a39-229">The partition this replica belongs to.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="b3a39-230">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="b3a39-230">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="b3a39-231">使用するため、状態プロバイダーのレプリカを開きます。</span><span class="sxs-lookup"><span data-stu-id="b3a39-231">Open the state provider replica for use.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b3a39-232">非同期の open 操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="b3a39-232">Task that represents the asynchronous open operation.</span></span> <span data-ttu-id="b3a39-233">結果には、パーティション内の他の状態プロバイダーのレプリカ間で状態のレプリケーションを担当するレプリケーターが含まれています。</span><span class="sxs-lookup"><span data-stu-id="b3a39-233">The result contains the replicator responsible for replicating state between other state provider replicas in the partition.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="b3a39-234">この時点でのタスクを開始状態プロバイダーの初期化を拡張します。</span><span class="sxs-lookup"><span data-stu-id="b3a39-234">Extended state provider initialization tasks can be started at this time.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.RestoreAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IStateProviderReplica.RestoreAsync (string backupFolderPath);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IStateProviderReplica.RestoreAsync(string backupFolderPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.Microsoft#ServiceFabric#Data#IStateProviderReplica#RestoreAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Function RestoreAsync (backupFolderPath As String) As Task Implements IStateProviderReplica.RestoreAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.RestoreAsync(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupFolderPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="backupFolderPath">
            <span data-ttu-id="b3a39-235">レプリカがから復元するディレクトリ。</span><span class="sxs-lookup"><span data-stu-id="b3a39-235">The directory where the replica is to be restored from.</span></span>
            <span data-ttu-id="b3a39-236">このパラメーターを null にすることはできませんを空または空白のみが含まれています。</span><span class="sxs-lookup"><span data-stu-id="b3a39-236">This parameter cannot be null, empty or contain just whitespace.</span></span> <span data-ttu-id="b3a39-237">UNC パスも指定することがあります。</span><span class="sxs-lookup"><span data-stu-id="b3a39-237">UNC paths may also be provided.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b3a39-238">によって作成されたバックアップを復元<see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />または<see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />です。</span><span class="sxs-lookup"><span data-stu-id="b3a39-238">Restore a backup taken by <see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" /> or <see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />.</span></span>
            </summary>
        <returns><span data-ttu-id="b3a39-239">非同期の復元操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="b3a39-239">Task that represents the asynchronous restore operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.RestoreAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IStateProviderReplica.RestoreAsync (string backupFolderPath, Microsoft.ServiceFabric.Data.RestorePolicy restorePolicy, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IStateProviderReplica.RestoreAsync(string backupFolderPath, valuetype Microsoft.ServiceFabric.Data.RestorePolicy restorePolicy, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.Microsoft#ServiceFabric#Data#IStateProviderReplica#RestoreAsync(System.String,Microsoft.ServiceFabric.Data.RestorePolicy,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.RestoreAsync(System.String,Microsoft.ServiceFabric.Data.RestorePolicy,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="b3a39-240">レプリカがから復元するディレクトリ。</span><span class="sxs-lookup"><span data-stu-id="b3a39-240">The directory where the replica is to be restored from.</span></span>
            <span data-ttu-id="b3a39-241">このパラメーターを null にすることはできませんを空または空白のみが含まれています。</span><span class="sxs-lookup"><span data-stu-id="b3a39-241">This parameter cannot be null, empty or contain just whitespace.</span></span> <span data-ttu-id="b3a39-242">UNC パスも指定することがあります。</span><span class="sxs-lookup"><span data-stu-id="b3a39-242">UNC paths may also be provided.</span></span>
            </param>
        <param name="restorePolicy"><span data-ttu-id="b3a39-243">復元のポリシー。</span><span class="sxs-lookup"><span data-stu-id="b3a39-243">The restore policy.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="b3a39-244">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="b3a39-244">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="b3a39-245">によって作成されたバックアップを復元<see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />または<see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />です。</span><span class="sxs-lookup"><span data-stu-id="b3a39-245">Restore a backup taken by <see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" /> or <see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />.</span></span>
            </summary>
        <returns><span data-ttu-id="b3a39-246">非同期の復元操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="b3a39-246">Task that represents the asynchronous restore operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDataLossAsync">
      <MemberSignature Language="C#" Value="public Func&lt;System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;bool&gt;&gt; OnDataLossAsync { set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`2&lt;valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task`1&lt;bool&gt;&gt; OnDataLossAsync" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.OnDataLossAsync" />
      <MemberSignature Language="VB.NET" Value="Public Property OnDataLossAsync As Func(Of CancellationToken, Task(Of Boolean))" />
      <MemberSignature Language="F#" Value="member this.OnDataLossAsync : Func&lt;System.Threading.CancellationToken, System.Threading.Tasks.Task&lt;bool&gt;&gt;" Usage="Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.OnDataLossAsync" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;System.Boolean&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b3a39-247">中に呼び出される関数には、データ損失が疑いがあります。</span><span class="sxs-lookup"><span data-stu-id="b3a39-247">The function called during suspected data-loss.</span></span>
            </summary>
        <value>
            <span data-ttu-id="b3a39-248">データ損失のコールバック関数を表す関数。</span><span class="sxs-lookup"><span data-stu-id="b3a39-248">A function representing data-loss callback function.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnRestoreCompletedAsync">
      <MemberSignature Language="C#" Value="public Func&lt;System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; OnRestoreCompletedAsync { set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`2&lt;valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; OnRestoreCompletedAsync" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.OnRestoreCompletedAsync" />
      <MemberSignature Language="VB.NET" Value="Public Property OnRestoreCompletedAsync As Func(Of CancellationToken, Task)" />
      <MemberSignature Language="F#" Value="member this.OnRestoreCompletedAsync : Func&lt;System.Threading.CancellationToken, System.Threading.Tasks.Task&gt;" Usage="Microsoft.ServiceFabric.Actors.Runtime.KvsActorStateProvider.OnRestoreCompletedAsync" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;System.Threading.CancellationToken,System.Threading.Tasks.Task&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b3a39-249">パーティションの状態をシステムによって自動的に復元した後に呼び出される関数</span><span class="sxs-lookup"><span data-stu-id="b3a39-249">Function called after the partition state has been restored automatically by the system</span></span>
            </summary>
        <value>
            <span data-ttu-id="b3a39-250">復元時に関数を表すには、コールバック関数が完了しました。</span><span class="sxs-lookup"><span data-stu-id="b3a39-250">A function representing on restore completed callback function.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>