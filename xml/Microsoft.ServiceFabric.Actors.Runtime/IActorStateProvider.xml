<Type Name="IActorStateProvider" FullName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider">
  <TypeSignature Language="C#" Value="public interface IActorStateProvider : Microsoft.ServiceFabric.Data.IStateProviderReplica2" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IActorStateProvider implements class Microsoft.ServiceFabric.Data.IStateProviderReplica, class Microsoft.ServiceFabric.Data.IStateProviderReplica2" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider" />
  <TypeSignature Language="VB.NET" Value="Public Interface IActorStateProvider&#xA;Implements IStateProviderReplica2" />
  <TypeSignature Language="F#" Value="type IActorStateProvider = interface&#xA;    interface IStateProviderReplica2&#xA;    interface IStateProviderReplica" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Data.IStateProviderReplica2</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="8d336-101">アクター状態プロバイダーは、アクター ランタイムと通信するために実装する必要があるインターフェイスを表します。</span><span class="sxs-lookup"><span data-stu-id="8d336-101">Represents the interface that an actor state provider needs to implement for actor runtime to communicate with it.</span></span> 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ActorActivatedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ActorActivatedAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ActorActivatedAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.ActorActivatedAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ActorActivatedAsync : Microsoft.ServiceFabric.Actors.ActorId * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iActorStateProvider.ActorActivatedAsync (actorId, cancellationToken)" />
      <MemberType>Method</MemberType>
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
        <param name="actorId"><span data-ttu-id="8d336-102">アクティブ化したアクターの ID です。</span><span class="sxs-lookup"><span data-stu-id="8d336-102">ID of the actor that is activated.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8d336-103">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="8d336-103">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="8d336-104">指定したアクターの ID を持つアクターのアクティブ化プロセスの一部として呼び出され、</span><span class="sxs-lookup"><span data-stu-id="8d336-104">Invoked as part of the activation process of the actor with the specified actor ID.</span></span>
            </summary>
        <returns><span data-ttu-id="8d336-105">非同期のアクターのアクティブ化通知の処理を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="8d336-105">A task that represents the asynchronous actor activation notification processing.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="8d336-106">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="8d336-106">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ContainsStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; ContainsStateAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, string stateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ContainsStateAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, string stateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.ContainsStateAsync(Microsoft.ServiceFabric.Actors.ActorId,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ContainsStateAsync : Microsoft.ServiceFabric.Actors.ActorId * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iActorStateProvider.ContainsStateAsync (actorId, stateName, cancellationToken)" />
      <MemberType>Method</MemberType>
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
        <param name="actorId"><span data-ttu-id="8d336-107">状態の有無を確認する対象のアクターの ID です。</span><span class="sxs-lookup"><span data-stu-id="8d336-107">ID of the actor for which to check state existence.</span></span></param>
        <param name="stateName"><span data-ttu-id="8d336-108">有無を確認するアクター状態の名前です。</span><span class="sxs-lookup"><span data-stu-id="8d336-108">Name of the actor state to check for existence.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8d336-109">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="8d336-109">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="8d336-110">アクター状態プロバイダーに指定されたアクター ID の名前を指定した状態で、アクター状態が含まれるかどうか確認します</span><span class="sxs-lookup"><span data-stu-id="8d336-110">Checks whether actor state provider contains an actor state with specified state name for the specified actor ID.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="8d336-111">非同期チェック操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="8d336-111">A task that represents the asynchronous check operation.</span></span> <span data-ttu-id="8d336-112">TResult パラメーターの値が<c>true</c>指定した名前と状態がそれ以外の場合に存在する場合は<c>false</c>です。</span><span class="sxs-lookup"><span data-stu-id="8d336-112">The value of TResult parameter is <c>true</c> if state with specified name exists otherwise <c>false</c>.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="8d336-113">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="8d336-113">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteReminderAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteReminderAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, string reminderName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteReminderAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, string reminderName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.DeleteReminderAsync(Microsoft.ServiceFabric.Actors.ActorId,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteReminderAsync : Microsoft.ServiceFabric.Actors.ActorId * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iActorStateProvider.DeleteReminderAsync (actorId, reminderName, cancellationToken)" />
      <MemberType>Method</MemberType>
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
        <param name="actorId"><span data-ttu-id="8d336-114">アラームを削除するアクターの ID です。</span><span class="sxs-lookup"><span data-stu-id="8d336-114">ID of the actor for which to delete the reminder.</span></span></param>
        <param name="reminderName"><span data-ttu-id="8d336-115">削除するアラームの名前です。</span><span class="sxs-lookup"><span data-stu-id="8d336-115">Name of the reminder to delete.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8d336-116">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="8d336-116">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="8d336-117">存在する場合は、指定された通知の名前を持つアクター アラームを削除します。</span><span class="sxs-lookup"><span data-stu-id="8d336-117">Deletes the actor reminder with the given reminder name if it exists</span></span>
            </summary>
        <returns><span data-ttu-id="8d336-118">非同期の削除操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="8d336-118">A task that represents the asynchronous delete operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="8d336-119">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="8d336-119">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteRemindersAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteRemindersAsync (System.Collections.Generic.IReadOnlyDictionary&lt;Microsoft.ServiceFabric.Actors.ActorId,System.Collections.Generic.IReadOnlyCollection&lt;string&gt;&gt; reminderNames, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteRemindersAsync(class System.Collections.Generic.IReadOnlyDictionary`2&lt;class Microsoft.ServiceFabric.Actors.ActorId, class System.Collections.Generic.IReadOnlyCollection`1&lt;string&gt;&gt; reminderNames, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.DeleteRemindersAsync(System.Collections.Generic.IReadOnlyDictionary{Microsoft.ServiceFabric.Actors.ActorId,System.Collections.Generic.IReadOnlyCollection{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteRemindersAsync : System.Collections.Generic.IReadOnlyDictionary&lt;Microsoft.ServiceFabric.Actors.ActorId, System.Collections.Generic.IReadOnlyCollection&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iActorStateProvider.DeleteRemindersAsync (reminderNames, cancellationToken)" />
      <MemberType>Method</MemberType>
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
        <param name="reminderNames"><span data-ttu-id="8d336-120">削除するアラームのセット。</span><span class="sxs-lookup"><span data-stu-id="8d336-120">The set of reminders to delete.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8d336-121">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="8d336-121">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="8d336-122">指定された通知のセットを削除します。</span><span class="sxs-lookup"><span data-stu-id="8d336-122">Deletes the specified set of reminders.</span></span>
            </summary>
        <returns><span data-ttu-id="8d336-123">非同期の削除操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="8d336-123">A task that represents the asynchronous delete operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="8d336-124">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="8d336-124">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="EnumerateStateNamesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;string&gt;&gt; EnumerateStateNamesAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;string&gt;&gt; EnumerateStateNamesAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.EnumerateStateNamesAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member EnumerateStateNamesAsync : Microsoft.ServiceFabric.Actors.ActorId * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;string&gt;&gt;" Usage="iActorStateProvider.EnumerateStateNamesAsync (actorId, cancellationToken)" />
      <MemberType>Method</MemberType>
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
        <param name="actorId"><span data-ttu-id="8d336-125">列挙可能なを作成する対象のアクターの ID です。</span><span class="sxs-lookup"><span data-stu-id="8d336-125">ID of the actor for which to create enumerable.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8d336-126">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="8d336-126">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="8d336-127">指定したアクターの ID に関連付けられたすべての状態名の列挙可能な作成します。</span><span class="sxs-lookup"><span data-stu-id="8d336-127">Creates an enumerable of all the state names associated with specified actor ID.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="8d336-128">非同期の列挙操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="8d336-128">A task that represents the asynchronous enumeration operation.</span></span> <span data-ttu-id="8d336-129">TResult パラメーターの値は、指定されたアクターに関連付けられているすべての州名の列挙です。</span><span class="sxs-lookup"><span data-stu-id="8d336-129">The value of TResult parameter is an enumerable of all state names associated with specified actor.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="8d336-130">アクター状態プロバイダーから返された列挙子は、安全に読み取りと同時に使用し、状態プロバイダーに書き込みます。</span><span class="sxs-lookup"><span data-stu-id="8d336-130">The enumerator returned from actor state provider is safe to use concurrently with reads and writes to the state provider.</span></span> <span data-ttu-id="8d336-131">状態プロバイダーのスナップショットの一貫したビューを表します。</span><span class="sxs-lookup"><span data-stu-id="8d336-131">It represents a snapshot consistent view of the state provider.</span></span>
            </remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="8d336-132">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="8d336-132">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetActorsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Actors.Query.PagedResult&lt;Microsoft.ServiceFabric.Actors.ActorId&gt;&gt; GetActorsAsync (int numItemsToReturn, Microsoft.ServiceFabric.Actors.Query.ContinuationToken continuationToken, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Actors.Query.PagedResult`1&lt;class Microsoft.ServiceFabric.Actors.ActorId&gt;&gt; GetActorsAsync(int32 numItemsToReturn, class Microsoft.ServiceFabric.Actors.Query.ContinuationToken continuationToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.GetActorsAsync(System.Int32,Microsoft.ServiceFabric.Actors.Query.ContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetActorsAsync : int * Microsoft.ServiceFabric.Actors.Query.ContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Actors.Query.PagedResult&lt;Microsoft.ServiceFabric.Actors.ActorId&gt;&gt;" Usage="iActorStateProvider.GetActorsAsync (numItemsToReturn, continuationToken, cancellationToken)" />
      <MemberType>Method</MemberType>
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
        <param name="numItemsToReturn"><span data-ttu-id="8d336-133">返される要求された項目の数。</span><span class="sxs-lookup"><span data-stu-id="8d336-133">Number of items requested to be returned.</span></span></param>
        <param name="continuationToken">
            <span data-ttu-id="8d336-134">クエリから結果を開始する継続トークンです。</span><span class="sxs-lookup"><span data-stu-id="8d336-134">A continuation token to start querying the results from.</span></span>
            <span data-ttu-id="8d336-135">継続トークンの null 値は、開始、先頭の値の形式を返すことを意味します。</span><span class="sxs-lookup"><span data-stu-id="8d336-135">A null value of continuation token means start returning values form the beginning.</span></span>
            </param>
        <param name="cancellationToken"><span data-ttu-id="8d336-136">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="8d336-136">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="8d336-137">状態プロバイダーから要求された ActorID の数を取得します。</span><span class="sxs-lookup"><span data-stu-id="8d336-137">Gets the requested number of ActorID's from the state provider.</span></span>
            </summary>
        <returns><span data-ttu-id="8d336-138">サーバーへの呼び出しの非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="8d336-138">A task that represents the asynchronous operation of call to server.</span></span></returns>
        <remarks>
            <span data-ttu-id="8d336-139"><paramref name="continuationToken" />この API の呼び出し時にアクター状態プロバイダーの状態に対する相対パスです。</span><span class="sxs-lookup"><span data-stu-id="8d336-139">The <paramref name="continuationToken" /> is relative to the state of actor state provider at the time of invocation of this API.</span></span> <span data-ttu-id="8d336-140">アクターの状態プロバイダーの変更を記述する場合 (つまり新しいアクターがアクティブ化または既存のアクターが削除されます) API と継続の間にこれを呼び出す前に、状態が変更された) の前の呼び出しからのトークンを指定して、結果はされたエントリを含めることがあります既に以前の呼び出しでフェッチします。</span><span class="sxs-lookup"><span data-stu-id="8d336-140">If the state of actor state provider changes (i.e. new actors are activated or existing actors are deleted) in between calls to this API and the continuation token from previous call (before the state was modified) is supplied, the result may contain entries that were already fetched in previous calls.</span></span>
            </remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="8d336-141">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="8d336-141">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Initialize">
      <MemberSignature Language="C#" Value="public void Initialize (Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation actorTypeInformation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Initialize(class Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation actorTypeInformation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.Initialize(Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation)" />
      <MemberSignature Language="F#" Value="abstract member Initialize : Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation -&gt; unit" Usage="iActorStateProvider.Initialize actorTypeInformation" />
      <MemberType>Method</MemberType>
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
        <param name="actorTypeInformation"><span data-ttu-id="8d336-142">アクター クラスの型情報</span><span class="sxs-lookup"><span data-stu-id="8d336-142">Type information of the actor class</span></span></param>
        <summary>
            <span data-ttu-id="8d336-143">関連付けられているアクター型の型情報を使用してアクター状態プロバイダーを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8d336-143">Initializes the actor state provider with type information of the actor type associated with it.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadRemindersAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Actors.Runtime.IActorReminderCollection&gt; LoadRemindersAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Actors.Runtime.IActorReminderCollection&gt; LoadRemindersAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.LoadRemindersAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member LoadRemindersAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Actors.Runtime.IActorReminderCollection&gt;" Usage="iActorStateProvider.LoadRemindersAsync cancellationToken" />
      <MemberType>Method</MemberType>
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
        <param name="cancellationToken"><span data-ttu-id="8d336-144">非同期の読み込み操作のキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8d336-144">Cancellation token for asynchronous load operation.</span></span></param>
        <summary>
            <span data-ttu-id="8d336-145">アクター状態プロバイダーに含まれているすべてのアラームを読み込みます。</span><span class="sxs-lookup"><span data-stu-id="8d336-145">Loads all the reminders contained in the actor state provider.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="8d336-146">非同期ロード操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="8d336-146">A task that represents the asynchronous load operation.</span></span> <span data-ttu-id="8d336-147">TResult パラメーターの値は、アクター状態プロバイダーに含まれているすべてのアクター アラームのコレクションです。</span><span class="sxs-lookup"><span data-stu-id="8d336-147">The value of TResult parameter is a collection of all actor reminders contained in the actor state provider.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="8d336-148">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="8d336-148">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="LoadStateAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; LoadStateAsync&lt;T&gt; (Microsoft.ServiceFabric.Actors.ActorId actorId, string stateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; LoadStateAsync&lt;T&gt;(class Microsoft.ServiceFabric.Actors.ActorId actorId, string stateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.LoadStateAsync``1(Microsoft.ServiceFabric.Actors.ActorId,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member LoadStateAsync : Microsoft.ServiceFabric.Actors.ActorId * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'T&gt;" Usage="iActorStateProvider.LoadStateAsync (actorId, stateName, cancellationToken)" />
      <MemberType>Method</MemberType>
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
        <typeparam name="T"><span data-ttu-id="8d336-149">アクターの状態の特定の状態名に関連付けられている値の型。</span><span class="sxs-lookup"><span data-stu-id="8d336-149">Type of value of actor state associated with given state name.</span></span></typeparam>
        <param name="actorId"><span data-ttu-id="8d336-150">状態の読み込み先のアクターの ID です。</span><span class="sxs-lookup"><span data-stu-id="8d336-150">ID of the actor for which to load the state.</span></span></param>
        <param name="stateName"><span data-ttu-id="8d336-151">読み込みにアクター状態の名前です。</span><span class="sxs-lookup"><span data-stu-id="8d336-151">Name of the actor state to load.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8d336-152">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="8d336-152">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="8d336-153">指定されたアクター ID の指定した状態の名前に関連付けられているアクターの状態を読み込みます</span><span class="sxs-lookup"><span data-stu-id="8d336-153">Loads the actor state associated with the specified state name for the specified actor ID.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="8d336-154">非同期ロード操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="8d336-154">A task that represents the asynchronous load operation.</span></span> <span data-ttu-id="8d336-155">TResult のパラメーターの値には、特定の状態名に関連付けられているアクター状態の値が含まれています。</span><span class="sxs-lookup"><span data-stu-id="8d336-155">The value of TResult parameter contains value of actor state associated with given state name.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Collections.Generic.KeyNotFoundException"><span data-ttu-id="8d336-156">指定された状態の名前に関連付けられているアクターの状態は存在しません。</span><span class="sxs-lookup"><span data-stu-id="8d336-156">Actor state associated with specified state name does not exist.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="8d336-157">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="8d336-157">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ReminderCallbackCompletedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ReminderCallbackCompletedAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, Microsoft.ServiceFabric.Actors.Runtime.IActorReminder reminder, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ReminderCallbackCompletedAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, class Microsoft.ServiceFabric.Actors.Runtime.IActorReminder reminder, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.ReminderCallbackCompletedAsync(Microsoft.ServiceFabric.Actors.ActorId,Microsoft.ServiceFabric.Actors.Runtime.IActorReminder,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ReminderCallbackCompletedAsync : Microsoft.ServiceFabric.Actors.ActorId * Microsoft.ServiceFabric.Actors.Runtime.IActorReminder * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iActorStateProvider.ReminderCallbackCompletedAsync (actorId, reminder, cancellationToken)" />
      <MemberType>Method</MemberType>
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
        <param name="actorId"><span data-ttu-id="8d336-158">アラームを所有しているアクターの ID</span><span class="sxs-lookup"><span data-stu-id="8d336-158">ID of the actor which own reminder</span></span></param>
        <param name="reminder"><span data-ttu-id="8d336-159">正常に完了したアクターに送信します。</span><span class="sxs-lookup"><span data-stu-id="8d336-159">Actor reminder that completed successfully.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8d336-160">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="8d336-160">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="8d336-161">アラームが起動し、そのコールバックの実行が終了したときに呼び出される<see cref="M:Microsoft.ServiceFabric.Actors.Runtime.IRemindable.ReceiveReminderAsync(System.String,System.Byte[],System.TimeSpan,System.TimeSpan)" />が正常にします。</span><span class="sxs-lookup"><span data-stu-id="8d336-161">Invoked when a reminder fires and finishes executing its callback <see cref="M:Microsoft.ServiceFabric.Actors.Runtime.IRemindable.ReceiveReminderAsync(System.String,System.Byte[],System.TimeSpan,System.TimeSpan)" /> successfully.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="8d336-162">非同期の通知コールバックを表すタスクでは、通知の処理が完了しました。</span><span class="sxs-lookup"><span data-stu-id="8d336-162">A task that represents the asynchronous reminder callback completed notification processing.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveActorAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveActorAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveActorAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.RemoveActorAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RemoveActorAsync : Microsoft.ServiceFabric.Actors.ActorId * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iActorStateProvider.RemoveActorAsync (actorId, cancellationToken)" />
      <MemberType>Method</MemberType>
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
        <param name="actorId"><span data-ttu-id="8d336-163">状態を削除するアクターの ID です。</span><span class="sxs-lookup"><span data-stu-id="8d336-163">ID of the actor for which to remove state.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8d336-164">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="8d336-164">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="8d336-165">すべての既存の状態と原子的に指定されたアクターの ID に関連付けられた通知を削除します。</span><span class="sxs-lookup"><span data-stu-id="8d336-165">Removes all the existing states and reminders associated with specified actor ID atomically.</span></span>
            </summary>
        <returns><span data-ttu-id="8d336-166">非同期の削除操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="8d336-166">A task that represents the asynchronous remove operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="8d336-167">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="8d336-167">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="SaveReminderAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SaveReminderAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, Microsoft.ServiceFabric.Actors.Runtime.IActorReminder reminder, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SaveReminderAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, class Microsoft.ServiceFabric.Actors.Runtime.IActorReminder reminder, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.SaveReminderAsync(Microsoft.ServiceFabric.Actors.ActorId,Microsoft.ServiceFabric.Actors.Runtime.IActorReminder,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SaveReminderAsync : Microsoft.ServiceFabric.Actors.ActorId * Microsoft.ServiceFabric.Actors.Runtime.IActorReminder * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iActorStateProvider.SaveReminderAsync (actorId, reminder, cancellationToken)" />
      <MemberType>Method</MemberType>
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
        <param name="actorId"><span data-ttu-id="8d336-168">アラームを保存する対象のアクターの ID です。</span><span class="sxs-lookup"><span data-stu-id="8d336-168">ID of the actor for which to save the reminder.</span></span></param>
        <param name="reminder"><span data-ttu-id="8d336-169">アクター アラームを保存します。</span><span class="sxs-lookup"><span data-stu-id="8d336-169">Actor reminder to save.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8d336-170">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="8d336-170">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="8d336-171">指定したアクター ID アラームを保存します。</span><span class="sxs-lookup"><span data-stu-id="8d336-171">Saves the specified actor ID reminder.</span></span> <span data-ttu-id="8d336-172">指定した名前のアクター アラームが存在しない場合は、それ以外の場合と同じ名前のアクター アラームを既存のアクター アラームが更新を追加します。</span><span class="sxs-lookup"><span data-stu-id="8d336-172">If an actor reminder with given name does not exist, it adds the actor reminder otherwise existing actor reminder with same name is updated.</span></span> 
            </summary>
        <returns><span data-ttu-id="8d336-173">非同期の保存操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="8d336-173">A task that represents the asynchronous save operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="8d336-174">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="8d336-174">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="SaveStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SaveStateAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, System.Collections.Generic.IReadOnlyCollection&lt;Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange&gt; stateChanges, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SaveStateAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, class System.Collections.Generic.IReadOnlyCollection`1&lt;class Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange&gt; stateChanges, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.SaveStateAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Collections.Generic.IReadOnlyCollection{Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SaveStateAsync : Microsoft.ServiceFabric.Actors.ActorId * System.Collections.Generic.IReadOnlyCollection&lt;Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iActorStateProvider.SaveStateAsync (actorId, stateChanges, cancellationToken)" />
      <MemberType>Method</MemberType>
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
        <param name="actorId"><span data-ttu-id="8d336-175">状態の変更を保存する対象のアクターの ID です。</span><span class="sxs-lookup"><span data-stu-id="8d336-175">ID of the actor for which to save the state changes.</span></span></param>
        <param name="stateChanges"><span data-ttu-id="8d336-176">状態の変更を保存するコレクション。</span><span class="sxs-lookup"><span data-stu-id="8d336-176">Collection of state changes to save.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8d336-177">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="8d336-177">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="8d336-178">保存指定されたアクターのセット状態の変更、指定したアクターの ID をアトミックにします。</span><span class="sxs-lookup"><span data-stu-id="8d336-178">Saves the specified set of actor state changes for the specified actor ID atomically.</span></span>
            </summary>
        <returns><span data-ttu-id="8d336-179">非同期の保存操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="8d336-179">A task that represents the asynchronous save operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="8d336-180">状態変更のコレクションには、指定された状態の名前の 1 つの項目を含める必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d336-180">The collection of state changes should contain only one item for a given state name.</span></span>
            <span data-ttu-id="8d336-181">保存先に既に存在するか、存在しないアクター状態の更新/削除するアクターの状態を追加しようとしています。 操作は失敗します。</span><span class="sxs-lookup"><span data-stu-id="8d336-181">The save operation will fail on trying to add an actor state which already exists or update/remove an actor state which does not exist.</span></span>
            </remarks>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="8d336-182">ときに<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind" />は<see cref="F:Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind.None" /></span><span class="sxs-lookup"><span data-stu-id="8d336-182">When <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind" /> is <see cref="F:Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind.None" /></span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="8d336-183">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="8d336-183">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
  </Members>
</Type>