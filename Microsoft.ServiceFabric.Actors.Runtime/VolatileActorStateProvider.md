<Type Name="VolatileActorStateProvider" FullName="Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider">
  <TypeSignature Language="C#" Value="public class VolatileActorStateProvider : Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider, Microsoft.ServiceFabric.Data.IStateProviderReplica2, System.Fabric.IStateProvider" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VolatileActorStateProvider extends System.Object implements class Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider, class Microsoft.ServiceFabric.Data.IStateProviderReplica, class Microsoft.ServiceFabric.Data.IStateProviderReplica2, class System.Fabric.IStateProvider" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider" />
  <TypeSignature Language="VB.NET" Value="Public Class VolatileActorStateProvider&#xA;Implements IActorStateProvider, IStateProvider, IStateProviderReplica2" />
  <TypeSignature Language="F#" Value="type VolatileActorStateProvider = class&#xA;    interface IActorStateProvider&#xA;    interface IStateProviderReplica2&#xA;    interface IStateProviderReplica&#xA;    interface IStateProvider&#xA;    interface VolatileLogicalTimeManager.ISnapshotHandler&#xA;    interface IActorStateProviderInternal" />
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
    <Interface>
      <InterfaceName>System.Fabric.IStateProvider</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="96167-101">実装を提供<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider" />アクター状態がメモリ内に保持し、揮発性です。</span><span class="sxs-lookup"><span data-stu-id="96167-101">Provides an implementation of <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider" /> where actor state is kept in-memory and is volatile.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VolatileActorStateProvider ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="96167-102"><see cref="T:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider" /> のインスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="96167-102">Creates an instance of <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VolatileActorStateProvider (System.Fabric.ReplicatorSettings replicatorSettings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ReplicatorSettings replicatorSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.#ctor(System.Fabric.ReplicatorSettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider : System.Fabric.ReplicatorSettings -&gt; Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider" Usage="new Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider replicatorSettings" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="replicatorSettings" Type="System.Fabric.ReplicatorSettings" />
      </Parameters>
      <Docs>
        <param name="replicatorSettings">
            <span data-ttu-id="96167-103">A<see cref="T:System.Fabric.ReplicatorSettings" />複製物作成会社の設定を説明します。</span><span class="sxs-lookup"><span data-stu-id="96167-103">A <see cref="T:System.Fabric.ReplicatorSettings" /> that describes replicator settings.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96167-104">インスタンスを作成<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider" />で複製物作成会社の設定を指定します。</span><span class="sxs-lookup"><span data-stu-id="96167-104">Creates an instance of <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider" /> with specified replicator settings.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.ActorActivatedAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IActorStateProvider.ActorActivatedAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.ActorActivatedAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#ActorActivatedAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.ActorActivatedAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider/&lt;Microsoft-ServiceFabric-Actors-Runtime-IActorStateProvider-ActorActivatedAsync&gt;d__24))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorId" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="actorId"><span data-ttu-id="96167-105">アクティブ化したアクターの ID です。</span><span class="sxs-lookup"><span data-stu-id="96167-105">ID of the actor that is activated.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="96167-106">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="96167-106">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="96167-107">指定した id に置き換えます。 アクターのライセンス認証プロセスの一部としてこのメソッドが呼び出されます</span><span class="sxs-lookup"><span data-stu-id="96167-107">This method is invoked as part of the activation process of the actor with the specified Id.</span></span> 
            </summary>
        <returns> <span data-ttu-id="96167-108">非同期のアクターのアクティブ化通知の処理を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="96167-108">A task that represents the asynchronous Actor activation notification processing.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="96167-109">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="96167-109">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.ContainsStateAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;bool&gt; IActorStateProvider.ContainsStateAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, string stateName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.ContainsStateAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, string stateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#ContainsStateAsync(Microsoft.ServiceFabric.Actors.ActorId,System.String,System.Threading.CancellationToken)" />
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
        <param name="actorId"><span data-ttu-id="96167-110">状態の有無を確認する対象のアクターの ID。</span><span class="sxs-lookup"><span data-stu-id="96167-110">The ID of the actor for which to check state existence.</span></span></param>
        <param name="stateName"><span data-ttu-id="96167-111">有無を確認するアクター状態の名前。</span><span class="sxs-lookup"><span data-stu-id="96167-111">The name of the actor state to check for existence.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="96167-112">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="96167-112">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="96167-113">アクター状態プロバイダーに指定した状態の名前を持つ、アクター状態が含まれているかどうかをチェックします。</span><span class="sxs-lookup"><span data-stu-id="96167-113">Checks whether actor state provider contains an actor state with specified state name.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="96167-114">非同期チェック操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="96167-114">A task that represents the asynchronous check operation.</span></span> <span data-ttu-id="96167-115">TResult パラメーターの値が<c>true</c>指定した名前と状態がそれ以外の場合に存在する場合は<c>false</c>です。</span><span class="sxs-lookup"><span data-stu-id="96167-115">The value of TResult parameter is <c>true</c> if state with specified name exists otherwise <c>false</c>.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="96167-116">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="96167-116">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.DeleteReminderAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IActorStateProvider.DeleteReminderAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, string reminderName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.DeleteReminderAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, string reminderName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#DeleteReminderAsync(Microsoft.ServiceFabric.Actors.ActorId,System.String,System.Threading.CancellationToken)" />
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
        <param name="actorId"><span data-ttu-id="96167-117">アラームを削除するアクターの ID。</span><span class="sxs-lookup"><span data-stu-id="96167-117">The ID of the actor for which to delete the reminder.</span></span></param>
        <param name="reminderName"><span data-ttu-id="96167-118">削除するアラームの名前。</span><span class="sxs-lookup"><span data-stu-id="96167-118">The name of the reminder to delete.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="96167-119">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="96167-119">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="96167-120">存在する場合は、指定されたアクター アラームを削除します。</span><span class="sxs-lookup"><span data-stu-id="96167-120">Deletes the specified actor reminder if it exists.</span></span>
            </summary>
        <returns><span data-ttu-id="96167-121">非同期の削除操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="96167-121">A task that represents the asynchronous delete operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="96167-122">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="96167-122">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.DeleteRemindersAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IActorStateProvider.DeleteRemindersAsync (System.Collections.Generic.IReadOnlyDictionary&lt;Microsoft.ServiceFabric.Actors.ActorId,System.Collections.Generic.IReadOnlyCollection&lt;string&gt;&gt; reminderNames, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.DeleteRemindersAsync(class System.Collections.Generic.IReadOnlyDictionary`2&lt;class Microsoft.ServiceFabric.Actors.ActorId, class System.Collections.Generic.IReadOnlyCollection`1&lt;string&gt;&gt; reminderNames, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#DeleteRemindersAsync(System.Collections.Generic.IReadOnlyDictionary{Microsoft.ServiceFabric.Actors.ActorId,System.Collections.Generic.IReadOnlyCollection{System.String}},System.Threading.CancellationToken)" />
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
        <param name="reminderNames"><span data-ttu-id="96167-123">削除するアラームのセット。</span><span class="sxs-lookup"><span data-stu-id="96167-123">The set of reminders to delete.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="96167-124">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="96167-124">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="96167-125">指定された通知のセットを削除します。</span><span class="sxs-lookup"><span data-stu-id="96167-125">Deletes the specified set of reminders.</span></span>
            </summary>
        <returns><span data-ttu-id="96167-126">非同期の削除操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="96167-126">A task that represents the asynchronous delete operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="96167-127">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="96167-127">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.EnumerateStateNamesAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;string&gt;&gt; IActorStateProvider.EnumerateStateNamesAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;string&gt;&gt; Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.EnumerateStateNamesAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#EnumerateStateNamesAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Threading.CancellationToken)" />
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
        <param name="actorId"><span data-ttu-id="96167-128">列挙可能なを作成する対象のアクターの ID。</span><span class="sxs-lookup"><span data-stu-id="96167-128">The ID of the actor for which to create enumerable.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="96167-129">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="96167-129">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="96167-130">指定されたアクターに関連付けられているすべての状態名の列挙可能なが作成されます。</span><span class="sxs-lookup"><span data-stu-id="96167-130">Creates an enumerable of all the state names associated with specified actor.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="96167-131">非同期の列挙操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="96167-131">A task that represents the asynchronous enumeration operation.</span></span> <span data-ttu-id="96167-132">TResult パラメーターの値は、指定されたアクターに関連付けられているすべての州名の列挙です。</span><span class="sxs-lookup"><span data-stu-id="96167-132">The value of TResult parameter is an enumerable of all state names associated with specified actor.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="96167-133">アクター状態プロバイダーから返された列挙子は、安全に読み取りと同時に使用し、状態プロバイダーに書き込みます。</span><span class="sxs-lookup"><span data-stu-id="96167-133">The enumerator returned from actor state provider is safe to use concurrently with reads and writes to the state provider.</span></span> <span data-ttu-id="96167-134">状態プロバイダーのスナップショットの一貫したビューを表します。</span><span class="sxs-lookup"><span data-stu-id="96167-134">It represents a snapshot consistent view of the state provider.</span></span>
            </remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="96167-135">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="96167-135">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.GetActorsAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Actors.Query.PagedResult&lt;Microsoft.ServiceFabric.Actors.ActorId&gt;&gt; IActorStateProvider.GetActorsAsync (int itemsCount, Microsoft.ServiceFabric.Actors.Query.ContinuationToken continuationToken, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Actors.Query.PagedResult`1&lt;class Microsoft.ServiceFabric.Actors.ActorId&gt;&gt; Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.GetActorsAsync(int32 itemsCount, class Microsoft.ServiceFabric.Actors.Query.ContinuationToken continuationToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#GetActorsAsync(System.Int32,Microsoft.ServiceFabric.Actors.Query.ContinuationToken,System.Threading.CancellationToken)" />
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
        <Parameter Name="itemsCount" Type="System.Int32" />
        <Parameter Name="continuationToken" Type="Microsoft.ServiceFabric.Actors.Query.ContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="itemsCount"><span data-ttu-id="96167-136">返される要求された項目の数。</span><span class="sxs-lookup"><span data-stu-id="96167-136">Number of items requested to be returned.</span></span></param>
        <param name="continuationToken">
            <span data-ttu-id="96167-137">クエリから結果を開始する継続トークンです。</span><span class="sxs-lookup"><span data-stu-id="96167-137">A continuation token to start querying the results from.</span></span>
            <span data-ttu-id="96167-138">継続トークンの null 値は、開始、先頭の値の形式を返すことを意味します。</span><span class="sxs-lookup"><span data-stu-id="96167-138">A null value of continuation token means start returning values form the beginning.</span></span>
            </param>
        <param name="cancellationToken"><span data-ttu-id="96167-139">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="96167-139">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="96167-140">状態プロバイダーから ActorIds を取得します。</span><span class="sxs-lookup"><span data-stu-id="96167-140">Gets ActorIds from the State Provider.</span></span>
            </summary>
        <returns><span data-ttu-id="96167-141">サーバーへの呼び出しの非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="96167-141">A task that represents the asynchronous operation of call to server.</span></span></returns>
        <remarks>
            <span data-ttu-id="96167-142"><paramref name="continuationToken" />この API の呼び出し時にアクター状態プロバイダーの状態に対する相対パスです。</span><span class="sxs-lookup"><span data-stu-id="96167-142">The <paramref name="continuationToken" /> is relative to the state of actor state provider at the time of invocation of this API.</span></span> <span data-ttu-id="96167-143">アクターの状態プロバイダーの変更を記述する場合 (つまり新しいアクターがアクティブ化または既存のアクターが削除されます) API と継続の間にこれを呼び出す前に、状態が変更された) の前の呼び出しからのトークンを指定して、結果はされたエントリを含めることがあります既に以前の呼び出しでフェッチします。</span><span class="sxs-lookup"><span data-stu-id="96167-143">If the state of actor state provider changes (i.e. new actors are activated or existing actors are deleted) in between calls to this API and the continuation token from previous call (before the state was modified) is supplied, the result may contain entries that were already fetched in previous calls.</span></span>
            </remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="96167-144">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="96167-144">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.Initialize">
      <MemberSignature Language="C#" Value="void IActorStateProvider.Initialize (Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation actorTypeInfo);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.Initialize(class Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation actorTypeInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#Initialize(Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation)" />
      <MemberSignature Language="VB.NET" Value="Sub Initialize (actorTypeInfo As ActorTypeInformation) Implements IActorStateProvider.Initialize" />
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
        <Parameter Name="actorTypeInfo" Type="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation" />
      </Parameters>
      <Docs>
        <param name="actorTypeInfo"><span data-ttu-id="96167-145">アクター クラスの型情報</span><span class="sxs-lookup"><span data-stu-id="96167-145">Type information of the actor class</span></span></param>
        <summary>
            <span data-ttu-id="96167-146">関連付けられているアクター型の型情報を使用してアクター状態プロバイダーを初期化します。</span><span class="sxs-lookup"><span data-stu-id="96167-146">Initializes the actor state provider with type information of the actor type associated with it.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.LoadRemindersAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Actors.Runtime.IActorReminderCollection&gt; IActorStateProvider.LoadRemindersAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Actors.Runtime.IActorReminderCollection&gt; Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.LoadRemindersAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#LoadRemindersAsync(System.Threading.CancellationToken)" />
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
        <param name="cancellationToken"><span data-ttu-id="96167-147">非同期の読み込み操作のキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="96167-147">The cancellation token for asynchronous load operation.</span></span></param>
        <summary>
            <span data-ttu-id="96167-148">アクター状態プロバイダーに含まれているすべてのアラームを読み込みます。</span><span class="sxs-lookup"><span data-stu-id="96167-148">Loads all the reminders contained in the actor state provider.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="96167-149">非同期ロード操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="96167-149">A task that represents the asynchronous load operation.</span></span> <span data-ttu-id="96167-150">TResult パラメーターの値は、アクター状態プロバイダーに含まれているすべてのアクター アラームのコレクションです。</span><span class="sxs-lookup"><span data-stu-id="96167-150">The value of TResult parameter is a collection of all actor reminders contained in the actor state provider.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="96167-151">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="96167-151">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.LoadStateAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;T&gt; IActorStateProvider.LoadStateAsync&lt;T&gt; (Microsoft.ServiceFabric.Actors.ActorId actorId, string stateName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.LoadStateAsync&lt;T&gt;(class Microsoft.ServiceFabric.Actors.ActorId actorId, string stateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#LoadStateAsync``1(Microsoft.ServiceFabric.Actors.ActorId,System.String,System.Threading.CancellationToken)" />
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
        <typeparam name="T"><span data-ttu-id="96167-152">アクターの状態の特定の状態名に関連付けられている値の型。</span><span class="sxs-lookup"><span data-stu-id="96167-152">Type of value of actor state associated with given state name.</span></span></typeparam>
        <param name="actorId"><span data-ttu-id="96167-153">状態の読み込み先のアクターの ID。</span><span class="sxs-lookup"><span data-stu-id="96167-153">The ID of the actor for which to load the state.</span></span></param>
        <param name="stateName"><span data-ttu-id="96167-154">読み込みにアクター状態の名前。</span><span class="sxs-lookup"><span data-stu-id="96167-154">The name of the actor state to load.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="96167-155">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="96167-155">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="96167-156">指定された状態の名前に関連付けられているアクターの状態を読み込みます。</span><span class="sxs-lookup"><span data-stu-id="96167-156">Loads the actor state associated with the specified state name.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="96167-157">非同期ロード操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="96167-157">A task that represents the asynchronous load operation.</span></span> <span data-ttu-id="96167-158">TResult のパラメーターの値には、特定の状態名に関連付けられているアクター状態の値が含まれています。</span><span class="sxs-lookup"><span data-stu-id="96167-158">The value of TResult parameter contains value of actor state associated with given state name.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Collections.Generic.KeyNotFoundException"><span data-ttu-id="96167-159">指定された状態の名前に関連付けられているアクターの状態は存在しません。</span><span class="sxs-lookup"><span data-stu-id="96167-159">The actor state associated with specified state name does not exist.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="96167-160">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="96167-160">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.ReminderCallbackCompletedAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IActorStateProvider.ReminderCallbackCompletedAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, Microsoft.ServiceFabric.Actors.Runtime.IActorReminder reminder, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.ReminderCallbackCompletedAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, class Microsoft.ServiceFabric.Actors.Runtime.IActorReminder reminder, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#ReminderCallbackCompletedAsync(Microsoft.ServiceFabric.Actors.ActorId,Microsoft.ServiceFabric.Actors.Runtime.IActorReminder,System.Threading.CancellationToken)" />
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
        <param name="actorId"><span data-ttu-id="96167-161">アラームを所有しているアクターの ID</span><span class="sxs-lookup"><span data-stu-id="96167-161">ID of the actor which own reminder</span></span></param>
        <param name="reminder"><span data-ttu-id="96167-162">正常に完了したアクターに送信します。</span><span class="sxs-lookup"><span data-stu-id="96167-162">Actor reminder that completed successfully.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="96167-163">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="96167-163">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="96167-164">アラームが起動し、そのコールバックの実行が終了したときに、このメソッドが呼び出される<see cref="M:Microsoft.ServiceFabric.Actors.Runtime.IRemindable.ReceiveReminderAsync(System.String,System.Byte[],System.TimeSpan,System.TimeSpan)" />が正常にします。</span><span class="sxs-lookup"><span data-stu-id="96167-164">This method is invoked when a reminder fires and finishes executing its callback <see cref="M:Microsoft.ServiceFabric.Actors.Runtime.IRemindable.ReceiveReminderAsync(System.String,System.Byte[],System.TimeSpan,System.TimeSpan)" /> successfully.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="96167-165">非同期の通知コールバックを表すタスクでは、通知の処理が完了しました。</span><span class="sxs-lookup"><span data-stu-id="96167-165">A task that represents the asynchronous reminder callback completed notification processing.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.RemoveActorAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IActorStateProvider.RemoveActorAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.RemoveActorAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#RemoveActorAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.RemoveActorAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider/&lt;Microsoft-ServiceFabric-Actors-Runtime-IActorStateProvider-RemoveActorAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorId" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="actorId"><span data-ttu-id="96167-166">状態を削除するアクターの ID です。</span><span class="sxs-lookup"><span data-stu-id="96167-166">ID of the actor for which to remove state.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="96167-167">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="96167-167">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="96167-168">すべての既存の状態と指定されたアクターにアトミックに関連付けられている通知を削除します。</span><span class="sxs-lookup"><span data-stu-id="96167-168">Removes all the existing states and reminders associated with specified actor atomically.</span></span>
            </summary>
        <returns><span data-ttu-id="96167-169">非同期の削除操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="96167-169">A task that represents the asynchronous remove operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="96167-170">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="96167-170">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.SaveReminderAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IActorStateProvider.SaveReminderAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, Microsoft.ServiceFabric.Actors.Runtime.IActorReminder reminder, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.SaveReminderAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, class Microsoft.ServiceFabric.Actors.Runtime.IActorReminder reminder, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#SaveReminderAsync(Microsoft.ServiceFabric.Actors.ActorId,Microsoft.ServiceFabric.Actors.Runtime.IActorReminder,System.Threading.CancellationToken)" />
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
        <param name="actorId"><span data-ttu-id="96167-171">アラームを保存する対象のアクターの ID。</span><span class="sxs-lookup"><span data-stu-id="96167-171">The ID of the actor for which to save the reminder.</span></span></param>
        <param name="reminder"><span data-ttu-id="96167-172">保存するアクターのお知らせします。</span><span class="sxs-lookup"><span data-stu-id="96167-172">The actor reminder to save.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="96167-173">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="96167-173">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="96167-174">指定されたアクター アラームを保存します。</span><span class="sxs-lookup"><span data-stu-id="96167-174">Saves the specified actor reminder.</span></span> <span data-ttu-id="96167-175">指定した名前のアクター アラームが存在しない場合は、それ以外の場合と同じ名前のアクター アラームを既存のアクター アラームが更新を追加します。</span><span class="sxs-lookup"><span data-stu-id="96167-175">If an actor reminder with given name does not exist, it adds the actor reminder otherwise existing actor reminder with same name is updated.</span></span> 
            </summary>
        <returns><span data-ttu-id="96167-176">非同期の保存操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="96167-176">A task that represents the asynchronous save operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="96167-177">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="96167-177">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.SaveStateAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IActorStateProvider.SaveStateAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, System.Collections.Generic.IReadOnlyCollection&lt;Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange&gt; stateChanges, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.SaveStateAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, class System.Collections.Generic.IReadOnlyCollection`1&lt;class Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange&gt; stateChanges, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#SaveStateAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Collections.Generic.IReadOnlyCollection{Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange},System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.SaveStateAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Collections.Generic.IReadOnlyCollection{Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider/&lt;Microsoft-ServiceFabric-Actors-Runtime-IActorStateProvider-SaveStateAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorId" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="stateChanges" Type="System.Collections.Generic.IReadOnlyCollection&lt;Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="actorId"><span data-ttu-id="96167-178">状態の変更を保存する対象のアクターの ID。</span><span class="sxs-lookup"><span data-stu-id="96167-178">The ID of the actor for which to save the state changes.</span></span></param>
        <param name="stateChanges"><span data-ttu-id="96167-179">状態の変更を保存するコレクション。</span><span class="sxs-lookup"><span data-stu-id="96167-179">The collection of state changes to save.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="96167-180">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="96167-180">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="96167-181">指定したアクター状態の変更のセットをアトミックに保存します。</span><span class="sxs-lookup"><span data-stu-id="96167-181">Saves the specified set of actor state changes atomically.</span></span>
            </summary>
        <returns><span data-ttu-id="96167-182">非同期の保存操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="96167-182">A task that represents the asynchronous save operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="96167-183">状態変更のコレクションには、指定された状態の名前の 1 つの項目を含める必要があります。</span><span class="sxs-lookup"><span data-stu-id="96167-183">The collection of state changes should contain only one item for a given state name.</span></span>
            <span data-ttu-id="96167-184">保存先に既に存在するか、存在しないアクター状態の更新/削除するアクターの状態を追加しようとしています。 操作は失敗します。</span><span class="sxs-lookup"><span data-stu-id="96167-184">The save operation will fail on trying to add an actor state which already exists or update/remove an actor state which does not exist.</span></span>
            </remarks>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="96167-185">ときに<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind" />は<see cref="F:Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind.None" /></span><span class="sxs-lookup"><span data-stu-id="96167-185">When <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind" /> is <see cref="F:Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind.None" /></span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="96167-186">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="96167-186">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.Abort">
      <MemberSignature Language="C#" Value="void IStateProviderReplica.Abort ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void Microsoft.ServiceFabric.Data.IStateProviderReplica.Abort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Data#IStateProviderReplica#Abort" />
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
            <span data-ttu-id="96167-187">状態プロバイダーのレプリカを強制的に中止します。</span><span class="sxs-lookup"><span data-stu-id="96167-187">Forcefully abort the state provider replica.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="96167-188">これは一般に、ノードで、永続的な障害が検出されたときに、または Service Fabric は、内部エラーのため、レプリカのライフ サイクルを確実に管理できませんに発生します。</span><span class="sxs-lookup"><span data-stu-id="96167-188">This generally occurs when a permanent fault is detected on the node, or when Service Fabric cannot reliably manage the replica's life-cycle due to internal failures.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IStateProviderReplica.BackupAsync (Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;bool&gt;&gt; backupCallback);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(class System.Func`3&lt;class Microsoft.ServiceFabric.Data.BackupInfo, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task`1&lt;bool&gt;&gt; backupCallback) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Data#IStateProviderReplica#BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />
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
        <param name="backupCallback"><span data-ttu-id="96167-189">バックアップ フォルダーがローカルで作成された、ノード外に移動する準備ができているときに呼び出されるコールバック。</span><span class="sxs-lookup"><span data-stu-id="96167-189">Callback to be called when the backup folder has been created locally and is ready to be moved out of the node.</span></span></param>
        <summary>
            <span data-ttu-id="96167-190">このアクター状態プロバイダーによって管理されている状態の完全バックアップを実行します</span><span class="sxs-lookup"><span data-stu-id="96167-190">Performs a full backup of state managed by this actor state provider</span></span>
            </summary>
        <returns><span data-ttu-id="96167-191">非同期のバックアップ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="96167-191">Task that represents the asynchronous backup operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="96167-192">バックアップ/復元がサポートされていない<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider" />です。</span><span class="sxs-lookup"><span data-stu-id="96167-192">Backup/restore is not supported by <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider" />.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IStateProviderReplica.BackupAsync (Microsoft.ServiceFabric.Data.BackupOption option, TimeSpan timeout, System.Threading.CancellationToken cancellationToken, Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;bool&gt;&gt; backupCallback);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(valuetype Microsoft.ServiceFabric.Data.BackupOption option, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken, class System.Func`3&lt;class Microsoft.ServiceFabric.Data.BackupInfo, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task`1&lt;bool&gt;&gt; backupCallback) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Data#IStateProviderReplica#BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
        <param name="option"><span data-ttu-id="96167-193">バックアップ用のオプションです。</span><span class="sxs-lookup"><span data-stu-id="96167-193">The option for the backup.</span></span></param>
        <param name="timeout"><span data-ttu-id="96167-194">バックアップのタイムアウト。</span><span class="sxs-lookup"><span data-stu-id="96167-194">The timeout for the backup.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="96167-195">バックアップのキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="96167-195">The cancellation token for the backup.</span></span></param>
        <param name="backupCallback"><span data-ttu-id="96167-196">バックアップ フォルダーの準備が呼び出されるコールバック。</span><span class="sxs-lookup"><span data-stu-id="96167-196">The callback to be called once the backup folder is ready.</span></span></param>
        <summary>
            <span data-ttu-id="96167-197">このアクター状態プロバイダーによって管理されている状態のバックアップを実行します。</span><span class="sxs-lookup"><span data-stu-id="96167-197">Performs backup of state managed by this actor sate provider.</span></span>
            </summary>
        <returns><span data-ttu-id="96167-198">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="96167-198">Task that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="96167-199">バックアップ/復元がサポートされていない<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider" />です。</span><span class="sxs-lookup"><span data-stu-id="96167-199">Backup/restore is not supported by <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider" />.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.ChangeRoleAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IStateProviderReplica.ChangeRoleAsync (System.Fabric.ReplicaRole newRole, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IStateProviderReplica.ChangeRoleAsync(valuetype System.Fabric.ReplicaRole newRole, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Data#IStateProviderReplica#ChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)" />
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
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider/&lt;Microsoft-ServiceFabric-Data-IStateProviderReplica-ChangeRoleAsync&gt;d__42))</AttributeName>
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
        <param name="newRole"><span data-ttu-id="96167-200">プライマリまたはセカンダリなど、新しいレプリカ ロール。</span><span class="sxs-lookup"><span data-stu-id="96167-200">The new replica role, such as primary or secondary.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="96167-201">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="96167-201">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="96167-202">そのロールが変更される、たとえばプライマリまたはセカンダリに、状態プロバイダーのレプリカを通知します。</span><span class="sxs-lookup"><span data-stu-id="96167-202">Notify the state provider replica that its role is changing, for example to Primary or Secondary.</span></span>
            </summary>
        <returns><span data-ttu-id="96167-203">非同期の変更の役割の操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="96167-203">Task that represents the asynchronous change role operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.CloseAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IStateProviderReplica.CloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IStateProviderReplica.CloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Data#IStateProviderReplica#CloseAsync(System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.CloseAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="96167-204">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="96167-204">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="96167-205">状態プロバイダーの複製が正常にクローズします。</span><span class="sxs-lookup"><span data-stu-id="96167-205">Gracefully close the state provider replica.</span></span>
            </summary>
        <returns><span data-ttu-id="96167-206">非同期の close 操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="96167-206">Task that represents the asynchronous close operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="96167-207">これは一般に、レプリカのコードにアップグレードされている、負荷分散のため、レプリカが移動されてまたは一時的なエラーが検出されたときに発生します。</span><span class="sxs-lookup"><span data-stu-id="96167-207">This generally occurs when the replica's code is being upgrade, the replica is being moved due to load balancing, or a transient fault is detected.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.Initialize">
      <MemberSignature Language="C#" Value="void IStateProviderReplica.Initialize (System.Fabric.StatefulServiceInitializationParameters initializationParameters);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void Microsoft.ServiceFabric.Data.IStateProviderReplica.Initialize(class System.Fabric.StatefulServiceInitializationParameters initializationParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Data#IStateProviderReplica#Initialize(System.Fabric.StatefulServiceInitializationParameters)" />
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
        <param name="initializationParameters"><span data-ttu-id="96167-208">サービス名、パーティション id、レプリカの id、およびコード パッケージ情報などのサービスの初期化情報。</span><span class="sxs-lookup"><span data-stu-id="96167-208">Service initialization information such as service name, partition id, replica id, and code package information.</span></span></param>
        <summary>
            <span data-ttu-id="96167-209">サービスの初期化情報を使用して、状態プロバイダーのレプリカを初期化します。</span><span class="sxs-lookup"><span data-stu-id="96167-209">Initialize the state provider replica using the service initialization information.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="96167-210">複雑な処理を初期化中に行う必要はありません。</span><span class="sxs-lookup"><span data-stu-id="96167-210">No complex processing should be done during Initialize.</span></span> <span data-ttu-id="96167-211">OpenAsync では、高価なまたは実行時間の長いの初期化を行う必要があります。</span><span class="sxs-lookup"><span data-stu-id="96167-211">Expensive or long-running initialization should be done in OpenAsync.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.OpenAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;System.Fabric.IReplicator&gt; IStateProviderReplica.OpenAsync (System.Fabric.ReplicaOpenMode openMode, System.Fabric.IStatefulServicePartition partition, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.IReplicator&gt; Microsoft.ServiceFabric.Data.IStateProviderReplica.OpenAsync(valuetype System.Fabric.ReplicaOpenMode openMode, class System.Fabric.IStatefulServicePartition partition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Data#IStateProviderReplica#OpenAsync(System.Fabric.ReplicaOpenMode,System.Fabric.IStatefulServicePartition,System.Threading.CancellationToken)" />
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
        <param name="openMode"><span data-ttu-id="96167-212">これが新規または既存のレプリカであるかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="96167-212">Indicates whether this is a new or existing replica.</span></span></param>
        <param name="partition"><span data-ttu-id="96167-213">このレプリカが属しているパーティション。</span><span class="sxs-lookup"><span data-stu-id="96167-213">The partition this replica belongs to.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="96167-214">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="96167-214">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="96167-215">使用するため、状態プロバイダーのレプリカを開きます。</span><span class="sxs-lookup"><span data-stu-id="96167-215">Open the state provider replica for use.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="96167-216">非同期の open 操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="96167-216">Task that represents the asynchronous open operation.</span></span> <span data-ttu-id="96167-217">結果には、パーティション内の他の状態プロバイダーのレプリカ間で状態のレプリケーションを担当するレプリケーターが含まれています。</span><span class="sxs-lookup"><span data-stu-id="96167-217">The result contains the replicator responsible for replicating state between other state provider replicas in the partition.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="96167-218">この時点でのタスクを開始状態プロバイダーの初期化を拡張します。</span><span class="sxs-lookup"><span data-stu-id="96167-218">Extended state provider initialization tasks can be started at this time.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.RestoreAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IStateProviderReplica.RestoreAsync (string backupFolderPath);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IStateProviderReplica.RestoreAsync(string backupFolderPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Data#IStateProviderReplica#RestoreAsync(System.String)" />
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
            <span data-ttu-id="96167-219">レプリカがから復元するディレクトリ。</span><span class="sxs-lookup"><span data-stu-id="96167-219">The directory where the replica is to be restored from.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96167-220">によって作成されたバックアップを復元<see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />または<see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />です。</span><span class="sxs-lookup"><span data-stu-id="96167-220">Restore a backup taken by <see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" /> or <see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />.</span></span>
            </summary>
        <returns><span data-ttu-id="96167-221">非同期の復元操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="96167-221">Task that represents the asynchronous restore operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="96167-222">バックアップ/復元がサポートされていない<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider" />です。</span><span class="sxs-lookup"><span data-stu-id="96167-222">Backup/restore is not supported by <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider" />.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.RestoreAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IStateProviderReplica.RestoreAsync (string backupFolderPath, Microsoft.ServiceFabric.Data.RestorePolicy restorePolicy, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IStateProviderReplica.RestoreAsync(string backupFolderPath, valuetype Microsoft.ServiceFabric.Data.RestorePolicy restorePolicy, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Data#IStateProviderReplica#RestoreAsync(System.String,Microsoft.ServiceFabric.Data.RestorePolicy,System.Threading.CancellationToken)" />
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
            <span data-ttu-id="96167-223">レプリカがから復元するディレクトリ。</span><span class="sxs-lookup"><span data-stu-id="96167-223">The directory where the replica is to be restored from.</span></span>
            </param>
        <param name="restorePolicy"><span data-ttu-id="96167-224">復元のポリシー。</span><span class="sxs-lookup"><span data-stu-id="96167-224">The restore policy.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="96167-225">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="96167-225">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="96167-226">によって作成されたバックアップを復元<see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />または<see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />です。</span><span class="sxs-lookup"><span data-stu-id="96167-226">Restore a backup taken by <see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" /> or <see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />.</span></span>
            </summary>
        <returns><span data-ttu-id="96167-227">非同期の復元操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="96167-227">Task that represents the asynchronous restore operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="96167-228">バックアップ/復元がサポートされていない<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider" />です。</span><span class="sxs-lookup"><span data-stu-id="96167-228">Backup/restore is not supported by <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider" />.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDataLossAsync">
      <MemberSignature Language="C#" Value="public Func&lt;System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;bool&gt;&gt; OnDataLossAsync { set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`2&lt;valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task`1&lt;bool&gt;&gt; OnDataLossAsync" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.OnDataLossAsync" />
      <MemberSignature Language="VB.NET" Value="Public Property OnDataLossAsync As Func(Of CancellationToken, Task(Of Boolean))" />
      <MemberSignature Language="F#" Value="member this.OnDataLossAsync : Func&lt;System.Threading.CancellationToken, System.Threading.Tasks.Task&lt;bool&gt;&gt;" Usage="Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.OnDataLossAsync" />
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
            <span data-ttu-id="96167-229">取得または疑いのあるデータ損失の可能性の中に呼び出される関数を設定します。</span><span class="sxs-lookup"><span data-stu-id="96167-229">Gets or sets the function called during suspected data-loss.</span></span>
            </summary>
        <value>
            <span data-ttu-id="96167-230">データ損失のコールバック関数を表す関数。</span><span class="sxs-lookup"><span data-stu-id="96167-230">A function representing data-loss callback function.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnRestoreCompletedAsync">
      <MemberSignature Language="C#" Value="public Func&lt;System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; OnRestoreCompletedAsync { set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`2&lt;valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; OnRestoreCompletedAsync" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.OnRestoreCompletedAsync" />
      <MemberSignature Language="VB.NET" Value="Public Property OnRestoreCompletedAsync As Func(Of CancellationToken, Task)" />
      <MemberSignature Language="F#" Value="member this.OnRestoreCompletedAsync : Func&lt;System.Threading.CancellationToken, System.Threading.Tasks.Task&gt;" Usage="Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.OnRestoreCompletedAsync" />
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
            <span data-ttu-id="96167-231">Post 復元が呼び出される関数はレプリカで実行されています。</span><span class="sxs-lookup"><span data-stu-id="96167-231">Function called post restore has been performed on the replica.</span></span>
            </summary>
        <value>
            <span data-ttu-id="96167-232">復元時に関数を表すには、コールバック関数が完了しました。</span><span class="sxs-lookup"><span data-stu-id="96167-232">A function representing on restore completed callback function.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Fabric.IStateProvider.GetCopyContext">
      <MemberSignature Language="C#" Value="System.Fabric.IOperationDataStream IStateProvider.GetCopyContext ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Fabric.IOperationDataStream System.Fabric.IStateProvider.GetCopyContext() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.System#Fabric#IStateProvider#GetCopyContext" />
      <MemberSignature Language="VB.NET" Value="Function GetCopyContext () As IOperationDataStream Implements IStateProvider.GetCopyContext" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IStateProvider.GetCopyContext</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.IOperationDataStream</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="96167-233">作成され、プライマリ レプリカにコンテキストを送信する開かれた後は、セカンダリ レプリカ上のコンテキストを取得します。</span><span class="sxs-lookup"><span data-stu-id="96167-233">Obtains context on a Secondary replica after it is created and opened to send context to the Primary replica.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="96167-234"><see cref="T:System.Fabric.IOperationDataStream" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="96167-234">Returns <see cref="T:System.Fabric.IOperationDataStream" />.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="96167-235">プライマリ レプリカがコンテキストを分析しを使用して状態を返送<see cref="M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" />です。</span><span class="sxs-lookup"><span data-stu-id="96167-235">The Primary replica analyzes the context and sends back state via <see cref="M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" />.</span></span></para>
          <para>
            <span data-ttu-id="96167-236"><see cref="M:System.Fabric.IStateProvider.GetCopyContext" />新しく作成された、アイドルなセカンダリ レプリカで呼び出され、非同期的に、プライマリ レプリカとの双方向メッセージ交換を確立するためのメカニズムを提供します。</span><span class="sxs-lookup"><span data-stu-id="96167-236"><see cref="M:System.Fabric.IStateProvider.GetCopyContext" /> is called on newly created, idle Secondary replicas and provides a mechanism to asynchronously establish a bidirectional conversation with the Primary replica.</span></span> <span data-ttu-id="96167-237">セカンダリ レプリカは、送信<see cref="T:System.Fabric.OperationData" />オブジェクトをプライマリ レプリカがセカンダリ レプリカでコンテキストを収集する場合の進行状況を判断できます。</span><span class="sxs-lookup"><span data-stu-id="96167-237">The Secondary replica sends <see cref="T:System.Fabric.OperationData" /> objects with which the Primary replica can determine the progress of collecting context on the Secondary replica.</span></span> <span data-ttu-id="96167-238">プライマリ レプリカは、必要な状態に戻すを送信して応答します。</span><span class="sxs-lookup"><span data-stu-id="96167-238">The Primary replica responds by sending the required state back.</span></span>
                <span data-ttu-id="96167-239">参照してください<see cref="M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" />交換の一方のプライマリ レプリカにします。</span><span class="sxs-lookup"><span data-stu-id="96167-239">See <see cref="M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" /> at the Primary replica for the other half of the exchange.</span></span> </para>
          <para><span data-ttu-id="96167-240">メモリ内のサービスでは、<see cref="M:System.Fabric.IStateProvider.GetCopyContext" />メソッドは呼び出されません、セカンダリ レプリカの状態は認識されている (空され、状態のすべてが必要)。</span><span class="sxs-lookup"><span data-stu-id="96167-240">For in-memory services, the <see cref="M:System.Fabric.IStateProvider.GetCopyContext" /> method is not called, as the state of the Secondary replicas is known (they are empty and will require all of the state).</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Fabric.IStateProvider.GetCopyState">
      <MemberSignature Language="C#" Value="System.Fabric.IOperationDataStream IStateProvider.GetCopyState (long upToSequenceNumber, System.Fabric.IOperationDataStream copyContext);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Fabric.IOperationDataStream System.Fabric.IStateProvider.GetCopyState(int64 upToSequenceNumber, class System.Fabric.IOperationDataStream copyContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.System#Fabric#IStateProvider#GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" />
      <MemberSignature Language="VB.NET" Value="Function GetCopyState (upToSequenceNumber As Long, copyContext As IOperationDataStream) As IOperationDataStream Implements IStateProvider.GetCopyState" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.IOperationDataStream</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="upToSequenceNumber" Type="System.Int64" />
        <Parameter Name="copyContext" Type="System.Fabric.IOperationDataStream" />
      </Parameters>
      <Docs>
        <param name="upToSequenceNumber">
          <para><span data-ttu-id="96167-241">最大最終シーケンス番号 (LSN) を使用してコピー ストリームに配置する必要があります、<see cref="M:System.Fabric.IStateReplicator.GetCopyStream" />メソッドです。</span><span class="sxs-lookup"><span data-stu-id="96167-241">The maximum last sequence number (LSN) that should be placed in the copy stream via the <see cref="M:System.Fabric.IStateReplicator.GetCopyStream" /> method.</span></span>
            <span data-ttu-id="96167-242">この数より大きい Lsn が経由でレプリケーション ストリームの一部として、セカンダリ レプリカに配信される、<see cref="M:System.Fabric.IStateReplicator.GetReplicationStream" />メソッドです。</span><span class="sxs-lookup"><span data-stu-id="96167-242">LSNs greater than this number are delivered to the Secondary replica as a part of the replication stream via the <see cref="M:System.Fabric.IStateReplicator.GetReplicationStream" /> method.</span></span></para>
        </param>
        <param name="copyContext">
          <para><span data-ttu-id="96167-243"><see cref="T:System.Fabric.IOperationDataStream" />を格納している、<see cref="T:System.Fabric.OperationData" />セカンダリ レプリカによって作成されるオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="96167-243">An <see cref="T:System.Fabric.IOperationDataStream" /> that contains the <see cref="T:System.Fabric.OperationData" /> objects that are created by the Secondary replica.</span></span> </para>
        </param>
        <summary>
          <para><span data-ttu-id="96167-244">プライマリ レプリカのセカンダリ レプリカを作成する必要がある状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="96167-244">Obtains the state on a Primary replica that is required to build a Secondary replica.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="96167-245"><see cref="T:System.Fabric.IOperationDataStream" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="96167-245">Returns <see cref="T:System.Fabric.IOperationDataStream" />.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="96167-246">同様に<see cref="M:System.Fabric.IStateProvider.GetCopyContext" />により、セカンダリ レプリカを使用して、プライマリ レプリカにコンテキストを送信する、 <see cref="T:System.Fabric.IOperationDataStream" />、<see cref="M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" />により、プライマリ レプリカで応答する、<see cref="T:System.Fabric.IOperationDataStream" />です。</span><span class="sxs-lookup"><span data-stu-id="96167-246">Just as <see cref="M:System.Fabric.IStateProvider.GetCopyContext" /> enables the Secondary replica to send context to the Primary replica via an <see cref="T:System.Fabric.IOperationDataStream" />, <see cref="M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" /> enables the Primary replica to respond with an <see cref="T:System.Fabric.IOperationDataStream" />.</span></span> <span data-ttu-id="96167-247">ストリームには使用して、セカンダリ レプリカに配信されるオブジェクトが含まれています、<see cref="M:System.Fabric.IStateReplicator.GetCopyStream" />のメソッド、<see cref="T:System.Fabric.FabricReplicator" />クラスです。</span><span class="sxs-lookup"><span data-stu-id="96167-247">The stream contains objects that are delivered to the Secondary replica via the <see cref="M:System.Fabric.IStateReplicator.GetCopyStream" /> method of the <see cref="T:System.Fabric.FabricReplicator" /> class.</span></span> <span data-ttu-id="96167-248">オブジェクトを実装<see cref="T:System.Fabric.IOperation" />し、指定されたデータが含まれています。</span><span class="sxs-lookup"><span data-stu-id="96167-248">The objects implement <see cref="T:System.Fabric.IOperation" /> and contain the specified data.</span></span> </para>
          <para> <span data-ttu-id="96167-249">プライマリ レプリカは、この呼び出しを受け取る、それを作成し、返す別<see cref="T:System.Fabric.IOperationDataStream" />を格納している<see cref="T:System.Fabric.OperationData" />です。</span><span class="sxs-lookup"><span data-stu-id="96167-249">When the Primary replica receives this call, it should create and return another <see cref="T:System.Fabric.IOperationDataStream" /> that contains <see cref="T:System.Fabric.OperationData" />.</span></span> <span data-ttu-id="96167-250"><see cref="T:System.Fabric.OperationData" />セカンダリ レプリカが次々 に提供されているために必要なデータ/状態を表す<paramref name="upToSequenceNumber" />最大 LSN。</span><span class="sxs-lookup"><span data-stu-id="96167-250"><see cref="T:System.Fabric.OperationData" /> represents the data/state that the Secondary replica requires to catch up to the provided <paramref name="upToSequenceNumber" /> maximum LSN.</span></span> <span data-ttu-id="96167-251">どの程度およびセカンダリ レプリカを経由で提供されるコンテキスト情報を使用して送信されるどの状態を持つを特定できる<see cref="M:System.Fabric.IStateProvider.GetCopyContext" />メソッドです。</span><span class="sxs-lookup"><span data-stu-id="96167-251">How much and which state has to be sent can be determined via the context information that the Secondary replica provides via <see cref="M:System.Fabric.IStateProvider.GetCopyContext" /> method.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Fabric.IStateProvider.GetLastCommittedSequenceNumber">
      <MemberSignature Language="C#" Value="long IStateProvider.GetLastCommittedSequenceNumber ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance int64 System.Fabric.IStateProvider.GetLastCommittedSequenceNumber() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.System#Fabric#IStateProvider#GetLastCommittedSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Function GetLastCommittedSequenceNumber () As Long Implements IStateProvider.GetLastCommittedSequenceNumber" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IStateProvider.GetLastCommittedSequenceNumber</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="96167-252">サービスがコミットされた最後のシーケンス番号を取得します。</span><span class="sxs-lookup"><span data-stu-id="96167-252">Obtains the last sequence number that the service has committed.</span></span> </para>
        </summary>
        <returns>
          <para><span data-ttu-id="96167-253"><see cref="T:System.Int64" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="96167-253">Returns <see cref="T:System.Int64" />.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="96167-254">データの損失が疑われると、最初の起動時に、永続的な状態がある場合に、サービスでこのメソッドが呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="96167-254">This method is called on a service when it first starts up, in case it has any persistent state, and when data loss is suspected.</span></span> <span data-ttu-id="96167-255">ステートフル サービス レプリカ起動すると、以前の更新から可能性がありますが保存されるデータを復元するオプションがあります。</span><span class="sxs-lookup"><span data-stu-id="96167-255">When a stateful service replica starts up, it has the option to restore any data that might have persisted from previous updates.</span></span>
            <span data-ttu-id="96167-256">このようないくつかの状態に復元するか、現在の進行状況がそのデータの最後に書き込まれたシーケンス番号です。</span><span class="sxs-lookup"><span data-stu-id="96167-256">If it restores some state in this manner, its current progress is the last written sequence number for that data.</span></span> <span data-ttu-id="96167-257">揮発性サービスは、単に 0 を返します。</span><span class="sxs-lookup"><span data-stu-id="96167-257">A volatile service can simply return 0.</span></span>
            <span data-ttu-id="96167-258">によって現在コミット進行状況がわかるため、フェールオーバー中に新しいプライマリ選択を判断するこのメソッドは、メモと呼ばれる、<see cref="T:System.Fabric.FabricReplicator" />その時点でクラスです。</span><span class="sxs-lookup"><span data-stu-id="96167-258">Note that this method is not called to determine a new primary election during fail-over, because the current committed progress is already known by the <see cref="T:System.Fabric.FabricReplicator" /> class at that time.</span></span> </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Fabric.IStateProvider.OnDataLossAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;bool&gt; IStateProvider.OnDataLossAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; System.Fabric.IStateProvider.OnDataLossAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.System#Fabric#IStateProvider#OnDataLossAsync(System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IStateProvider.OnDataLossAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">
          <para><span data-ttu-id="96167-259"><see cref="T:System.Threading.CancellationToken" />操作を確認するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="96167-259">The <see cref="T:System.Threading.CancellationToken" /> object that the operation is observing.</span></span> <span data-ttu-id="96167-260">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="96167-260">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="96167-261">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="96167-261">Note that cancellation is advisory and that the operation might still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="96167-262">このレプリカ セット内のレプリカのな書き込みクォーラムが失われていることと、そのためデータが失われる可能性がありますが発生したことを示します。</span><span class="sxs-lookup"><span data-stu-id="96167-262">Indicates that a write quorum of replicas in this replica set  has been lost, and that therefore data loss might have occurred.</span></span> <span data-ttu-id="96167-263">レプリカ セットは、プライマリ レプリカが含まれているレプリカの大部分で構成されます。</span><span class="sxs-lookup"><span data-stu-id="96167-263">The replica set consists of a majority of replicas, which includes the Primary replica.</span></span> </para>
        </summary>
        <returns>
          <para><span data-ttu-id="96167-264">返します<see cref="T:System.Threading.Tasks.Task`1" />型の<see cref="T:System.Boolean" />状態が変更されたかどうかを示すです。</span><span class="sxs-lookup"><span data-stu-id="96167-264">Returns <see cref="T:System.Threading.Tasks.Task`1" /> of type <see cref="T:System.Boolean" />, that indicates whether state changed.</span></span> <span data-ttu-id="96167-265">メソッドが true を返します、変更されたときまたは変更されていない場合、false が返されます。</span><span class="sxs-lookup"><span data-stu-id="96167-265">When it changed, the method returns true or when it did not change, the method returns false.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="96167-266">Service Fabric ランタイムが、プライマリ レプリカが含まれており、レプリカのクォーラムの障害発生時に新しいプライマリ レプリカと、すぐに、新しいプライマリ レプリカでこのメソッドを呼び出します。</span><span class="sxs-lookup"><span data-stu-id="96167-266">When the Service Fabric runtime observes the failure of a quorum of replicas, which includes the Primary replica, it elects a new Primary replica and immediately calls this method on the new Primary replica.</span></span> <span data-ttu-id="96167-267">データ損失の可能性が通知をプライマリ レプリカは、外部データ ソースからの状態を復元することもできます。 またはが現在の状態で実行を続行できます。</span><span class="sxs-lookup"><span data-stu-id="96167-267">A Primary replica that is informed of possible data loss can choose to restore its state from some external data source or can continue to run with the state that it currently has.</span></span> <span data-ttu-id="96167-268">サービスが、現在の状態で実行され続ける場合は、状態の変更が行われていないことを示す、このメソッドから false を返します。</span><span class="sxs-lookup"><span data-stu-id="96167-268">If the service continues to run with its current state, it should return false from this method, which indicates that no state change has been made.</span></span> <span data-ttu-id="96167-269">復元または不完全な作業は、ロールバックなどの状態を変更した場合は true を返します。</span><span class="sxs-lookup"><span data-stu-id="96167-269">If it has restored or altered its state, such as rolling back incomplete work, it should return true.</span></span> <span data-ttu-id="96167-270">True が返される場合はその他のレプリカの状態が不適切な想定されます。</span><span class="sxs-lookup"><span data-stu-id="96167-270">If true is returned, then the state in other replicas must be assumed to be incorrect.</span></span>
            <span data-ttu-id="96167-271">そのため、Service Fabric ランタイムでは、レプリカ セットから他のレプリカを削除し、それらを再作成します。</span><span class="sxs-lookup"><span data-stu-id="96167-271">Therefore, the Service Fabric runtime removes the other replicas from the replica set and recreates them.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Fabric.IStateProvider.UpdateEpochAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IStateProvider.UpdateEpochAsync (System.Fabric.Epoch epoch, long previousEpochLastSequenceNumber, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task System.Fabric.IStateProvider.UpdateEpochAsync(valuetype System.Fabric.Epoch epoch, int64 previousEpochLastSequenceNumber, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.System#Fabric#IStateProvider#UpdateEpochAsync(System.Fabric.Epoch,System.Int64,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IStateProvider.UpdateEpochAsync(System.Fabric.Epoch,System.Int64,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="epoch" Type="System.Fabric.Epoch" />
        <Parameter Name="previousEpochLastSequenceNumber" Type="System.Int64" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="epoch">
          <para><span data-ttu-id="96167-272">新しい <see cref="T:System.Fabric.Epoch" />。</span><span class="sxs-lookup"><span data-stu-id="96167-272">The new <see cref="T:System.Fabric.Epoch" />.</span></span></para>
        </param>
        <param name="previousEpochLastSequenceNumber">
          <para> <span data-ttu-id="96167-273">以前のエポックで発見された最大のシーケンス番号 (LSN)。</span><span class="sxs-lookup"><span data-stu-id="96167-273">The maximum sequence number (LSN) that should have been observed in the previous epoch.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="96167-274"><see cref="T:System.Threading.CancellationToken" />操作を確認するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="96167-274">The <see cref="T:System.Threading.CancellationToken" /> object that the operation is observing.</span></span> <span data-ttu-id="96167-275">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="96167-275">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="96167-276">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="96167-276">Note that cancellation is advisory and that the operation might still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="96167-277">レプリカ セットの構成が変更の理由で変更または、プライマリ レプリカへの変更をしようとしましたが、レプリカを示します。</span><span class="sxs-lookup"><span data-stu-id="96167-277">Indicates to a replica that the configuration of a replica set has changed due to a change or attempted change to the Primary replica.</span></span> <span data-ttu-id="96167-278">変更は、エラーまたは以前のプライマリ レプリカの負荷分散のために発生します。</span><span class="sxs-lookup"><span data-stu-id="96167-278">The change occurs due to failure or load balancing of the previous Primary replica.</span></span> <span data-ttu-id="96167-279">エポックの変更は、特定のプライマリ レプリカによって送信された実際の構成の期間に操作を分割することによって、バリアとして機能します。</span><span class="sxs-lookup"><span data-stu-id="96167-279">Epoch changes act as a barrier by segmenting operations into the exact configuration periods in which they were sent by a specific Primary replica.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="96167-280"><see cref="T:System.Threading.Tasks.Task" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="96167-280">Returns <see cref="T:System.Threading.Tasks.Task" />.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="96167-281">レプリカ セットのプライマリ レプリカが変更されているか、変更が試みられたために、このメソッドが呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="96167-281">This method is called because the Primary replica of the replica set has changed, or a change was attempted.</span></span> <span data-ttu-id="96167-282">セカンダリ レプリカは、新しいプライマリ レプリカになるとしているか、間違っている場合、新しいプライマリ レプリカにこのメソッドを受信、発生したレプリケーション ストリームから新しいプライマリ レプリカから最初の操作を取得しようとするときにします。</span><span class="sxs-lookup"><span data-stu-id="96167-282">Secondary replicas receive this method either when they are about to become the new Primary replica, or, if they are not the new Primary replica, they receive it when they attempt to get the first operation from the new Primary replica from the replication stream.</span></span> <span data-ttu-id="96167-283">プライマリ レプリカでは、試行が失敗した、プライマリ レプリカをスワップする場合は、このメソッドを受け取ることがあります。</span><span class="sxs-lookup"><span data-stu-id="96167-283">Primary replicas might occasionally receive this method if there is an attempt to swap the Primary replica, which fails.</span></span></para>
          <para><span data-ttu-id="96167-284">内の情報、<see cref="M:System.Fabric.IStateProvider.UpdateEpochAsync(System.Fabric.Epoch,System.Int64,System.Threading.CancellationToken)" />メソッドは、レプリカが受信した各エポックとそれらに含まれる最大の LSN の一覧、進行状況のベクトルを維持するためにサービスを有効にします。</span><span class="sxs-lookup"><span data-stu-id="96167-284">The information in the <see cref="M:System.Fabric.IStateProvider.UpdateEpochAsync(System.Fabric.Epoch,System.Int64,System.Threading.CancellationToken)" /> method enables the service to maintain a progress vector, which is a list of each epoch that the replica has received, and the maximum LSN that they contained.</span></span> <span data-ttu-id="96167-285">現在適用されている最大の LSN と進行状況のベクター データは、セカンダリ レプリカをどのように操作の進行を記述するコピー操作中に送信するのに便利です。</span><span class="sxs-lookup"><span data-stu-id="96167-285">The progress vector data along with the current applied maximum LSN is useful for a Secondary replica to send during the copy operation  to describe how far the operation has progressed.</span></span> <span data-ttu-id="96167-286">コピー操作中に、セカンダリ レプリカから受信した進行状況のベクトルを比較するには、セカンダリ レプリカが最新かどうか、どの状態は、セカンダリ レプリカに送信する必要があり、セカンダリ レプリカが false の進行状況を行われたかどうかを判断するプライマリ レプリカが有効にします。</span><span class="sxs-lookup"><span data-stu-id="96167-286">Comparing progress vectors that are received from Secondary replicas during the copy operation enables Primary replicas to determine whether the Secondary replica is up-to-date, what state must be sent to the Secondary replica, and whether the Secondary replica has made false progress.</span></span> <span data-ttu-id="96167-287">False の進行状況は、以前のエポックの LSN が、プライマリ レプリカを受信する LSN よりも大きいことを意味します。</span><span class="sxs-lookup"><span data-stu-id="96167-287">False progress means that an LSN in a previous epoch was greater than the LSN that the Primary replica receives.</span></span> </para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>