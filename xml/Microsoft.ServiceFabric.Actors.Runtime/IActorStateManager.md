<Type Name="IActorStateManager" FullName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager">
  <TypeSignature Language="C#" Value="public interface IActorStateManager" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IActorStateManager" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager" />
  <TypeSignature Language="VB.NET" Value="Public Interface IActorStateManager" />
  <TypeSignature Language="F#" Value="type IActorStateManager = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="41e34-101">状態を管理するメソッドを公開するインターフェイスを表す、<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.Actor" />です。</span><span class="sxs-lookup"><span data-stu-id="41e34-101">Represents an interface that exposes methods to manage state of an <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.Actor" />.</span></span>
            <span data-ttu-id="41e34-102">このインターフェイスはによって実装<see cref="P:Microsoft.ServiceFabric.Actors.Runtime.Actor.StateManager" />です。</span><span class="sxs-lookup"><span data-stu-id="41e34-102">This interface is implemented by <see cref="P:Microsoft.ServiceFabric.Actors.Runtime.Actor.StateManager" />.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AddOrUpdateStateAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; AddOrUpdateStateAsync&lt;T&gt; (string stateName, T addValue, Func&lt;string,T,T&gt; updateValueFactory, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; AddOrUpdateStateAsync&lt;T&gt;(string stateName, !!T addValue, class System.Func`3&lt;string, !!T, !!T&gt; updateValueFactory, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.AddOrUpdateStateAsync``1(System.String,``0,System.Func{System.String,``0,``0},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddOrUpdateStateAsync : string * 'T * Func&lt;string, 'T, 'T&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'T&gt;" Usage="iActorStateManager.AddOrUpdateStateAsync (stateName, addValue, updateValueFactory, cancellationToken)" />
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
        <Parameter Name="stateName" Type="System.String" />
        <Parameter Name="addValue" Type="T" />
        <Parameter Name="updateValueFactory" Type="System.Func&lt;System.String,T,T&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="41e34-103">特定の状態名に関連付けられている値の型。</span><span class="sxs-lookup"><span data-stu-id="41e34-103">Type of value associated with given state name.</span></span></typeparam>
        <param name="stateName"><span data-ttu-id="41e34-104">追加または更新するアクター状態の名前です。</span><span class="sxs-lookup"><span data-stu-id="41e34-104">Name of the actor state to add or update.</span></span></param>
        <param name="addValue"><span data-ttu-id="41e34-105">存在しないかどうかに追加するアクター状態の値です。</span><span class="sxs-lookup"><span data-stu-id="41e34-105">Value of the actor state to add if it does not exist.</span></span></param>
        <param name="updateValueFactory"><span data-ttu-id="41e34-106">存在する場合に更新するアクター状態の値を生成するファクトリ関数。</span><span class="sxs-lookup"><span data-stu-id="41e34-106">Factory function to generate value of actor state to update if it exists.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="41e34-107">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="41e34-107">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="41e34-108">アクターを追加します。 特定の状態名、または存在する場合、指定した状態の名前で状態を更新が存在しない場合の状態。</span><span class="sxs-lookup"><span data-stu-id="41e34-108">Adds an actor state with given state name, if it does not already exist or updates the state with specified state name, if it exists.</span></span> 
            </summary>
        <returns>
            <span data-ttu-id="41e34-109">非同期の追加または更新操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="41e34-109">A task that represents the asynchronous add/update operation.</span></span> <span data-ttu-id="41e34-110">TResult のパラメーターの値には、追加/更新がアクター状態の値が含まれています。</span><span class="sxs-lookup"><span data-stu-id="41e34-110">The value of TResult parameter contains value of actor state that was added/updated.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="41e34-111">状態値の型<typeparamref name="T" />する必要があります<see href="https://msdn.microsoft.com/library/ms731923.aspx">データ コントラクト</see>シリアル化可能です。</span><span class="sxs-lookup"><span data-stu-id="41e34-111">The type of state value <typeparamref name="T" /> must be <see href="https://msdn.microsoft.com/library/ms731923.aspx">Data Contract</see> serializable.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException"> <span data-ttu-id="41e34-112">指定された状態の名前が null です。</span><span class="sxs-lookup"><span data-stu-id="41e34-112">The specified state name is null.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="41e34-113">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="41e34-113">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="AddStateAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AddStateAsync&lt;T&gt; (string stateName, T value, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AddStateAsync&lt;T&gt;(string stateName, !!T value, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.AddStateAsync``1(System.String,``0,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddStateAsync : string * 'T * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iActorStateManager.AddStateAsync (stateName, value, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="stateName" Type="System.String" />
        <Parameter Name="value" Type="T" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="41e34-114">特定の状態名に関連付けられている値の型。</span><span class="sxs-lookup"><span data-stu-id="41e34-114">Type of value associated with given state name.</span></span></typeparam>
        <param name="stateName"><span data-ttu-id="41e34-115">追加するアクター状態の名前です。</span><span class="sxs-lookup"><span data-stu-id="41e34-115">Name of the actor state to add.</span></span></param>
        <param name="value"><span data-ttu-id="41e34-116">追加するアクター状態の値です。</span><span class="sxs-lookup"><span data-stu-id="41e34-116">Value of the actor state to add.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="41e34-117">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="41e34-117">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="41e34-118">アクターを追加します。 特定の状態の名前と状態。</span><span class="sxs-lookup"><span data-stu-id="41e34-118">Adds an actor state with given state name.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="41e34-119">表す非同期のタスクは、操作を追加します。</span><span class="sxs-lookup"><span data-stu-id="41e34-119">A task that represents the asynchronous add operation.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="41e34-120">状態値の型<typeparamref name="T" />する必要があります<see href="https://msdn.microsoft.com/library/ms731923.aspx">データ コントラクト</see>シリアル化可能です。</span><span class="sxs-lookup"><span data-stu-id="41e34-120">The type of state value <typeparamref name="T" /> must be <see href="https://msdn.microsoft.com/library/ms731923.aspx">Data Contract</see> serializable.</span></span>
            </remarks>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="41e34-121">アクター状態の特定の状態名既に存在します。</span><span class="sxs-lookup"><span data-stu-id="41e34-121">An actor state with given state name already exists.</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="41e34-122">指定された状態の名前が null です。</span><span class="sxs-lookup"><span data-stu-id="41e34-122">The specified state name is null.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="41e34-123">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="41e34-123">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ClearCacheAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ClearCacheAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ClearCacheAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.ClearCacheAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ClearCacheAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iActorStateManager.ClearCacheAsync cancellationToken" />
      <MemberType>Method</MemberType>
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
        <param name="cancellationToken"><span data-ttu-id="41e34-124">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="41e34-124">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="41e34-125">すべてのキャッシュされたアクター状態とで実行される任意のサービス操作をクリア<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager" />の最新の状態の保存操作以降。</span><span class="sxs-lookup"><span data-stu-id="41e34-125">Clears all the cached actor states and any operation(s) performed on <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager" /> since last state save operation.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="41e34-126">非同期キャッシュのクリア操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="41e34-126">A task that represents the asynchronous clear cache operation.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="41e34-127">実行されるすべての操作<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager" />最後に保存操作が、キャッシュをクリアするクリアされ、次の保存操作には含まれません。</span><span class="sxs-lookup"><span data-stu-id="41e34-127">All the operation(s) performed on <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager" />  since last save operation are cleared on clearing the cache and will not be included in next save operation.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainsStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; ContainsStateAsync (string stateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ContainsStateAsync(string stateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.ContainsStateAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ContainsStateAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iActorStateManager.ContainsStateAsync (stateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="stateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="stateName"><span data-ttu-id="41e34-128">アクター状態の名前。</span><span class="sxs-lookup"><span data-stu-id="41e34-128">Name of the actor state.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="41e34-129">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="41e34-129">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="41e34-130">指定した名前のアクター状態が存在するかを確認します。</span><span class="sxs-lookup"><span data-stu-id="41e34-130">Checks if an actor state with specified name exists.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="41e34-131">非同期チェック操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="41e34-131">A task that represents the asynchronous check operation.</span></span> <span data-ttu-id="41e34-132">TResult パラメーターの値が<c>true</c>指定した名前と状態がそれ以外の場合に存在する場合は<c>false</c>です。</span><span class="sxs-lookup"><span data-stu-id="41e34-132">The value of TResult parameter is <c>true</c> if state with specified name exists otherwise <c>false</c>.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"> <span data-ttu-id="41e34-133">指定された状態の名前が null です。</span><span class="sxs-lookup"><span data-stu-id="41e34-133">The specified state name is null.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="41e34-134">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="41e34-134">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetOrAddStateAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetOrAddStateAsync&lt;T&gt; (string stateName, T value, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; GetOrAddStateAsync&lt;T&gt;(string stateName, !!T value, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.GetOrAddStateAsync``1(System.String,``0,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetOrAddStateAsync : string * 'T * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'T&gt;" Usage="iActorStateManager.GetOrAddStateAsync (stateName, value, cancellationToken)" />
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
        <Parameter Name="stateName" Type="System.String" />
        <Parameter Name="value" Type="T" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="41e34-135">特定の状態名に関連付けられている値の型。</span><span class="sxs-lookup"><span data-stu-id="41e34-135">Type of value associated with given state name.</span></span></typeparam>
        <param name="stateName"><span data-ttu-id="41e34-136">アクター状態を取得または追加の名前です。</span><span class="sxs-lookup"><span data-stu-id="41e34-136">Name of the actor state to get or add.</span></span></param>
        <param name="value"><span data-ttu-id="41e34-137">存在しないかどうかに追加するアクター状態の値です。</span><span class="sxs-lookup"><span data-stu-id="41e34-137">Value of the actor state to add if it does not exist.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="41e34-138">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="41e34-138">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="41e34-139">存在する場合は、指定された状態の名前を持つ、アクターの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="41e34-139">Gets an actor state with the given state name if it exists.</span></span> <span data-ttu-id="41e34-140">存在しない場合は、作成し、指定した名前と値を持つ新しい状態。</span><span class="sxs-lookup"><span data-stu-id="41e34-140">If it does not exist, creates and new state with the specified name and value.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="41e34-141">表す非同期のタスクは、取得か、操作を追加します。</span><span class="sxs-lookup"><span data-stu-id="41e34-141">A task that represents the asynchronous get or add operation.</span></span> <span data-ttu-id="41e34-142">パラメーターには、アクター状態の値が含まれています。 TResult の値は、状態の名前を指定します。</span><span class="sxs-lookup"><span data-stu-id="41e34-142">The value of TResult parameter contains value of actor state with given state name.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="41e34-143">状態値の型<typeparamref name="T" />する必要があります<see href="https://msdn.microsoft.com/library/ms731923.aspx">データ コントラクト</see>シリアル化可能です。</span><span class="sxs-lookup"><span data-stu-id="41e34-143">The type of state value <typeparamref name="T" /> must be <see href="https://msdn.microsoft.com/library/ms731923.aspx">Data Contract</see> serializable.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException"> <span data-ttu-id="41e34-144">指定された状態の名前が null です。</span><span class="sxs-lookup"><span data-stu-id="41e34-144">The specified state name is null.</span></span>
            <span data-ttu-id="41e34-145">有効な状態名の文字列を提供します。</span><span class="sxs-lookup"><span data-stu-id="41e34-145">Provide a valid state name string.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="41e34-146">指定されたを使用して、要求が取り消されました<paramref name="cancellationToken" />です。</span><span class="sxs-lookup"><span data-stu-id="41e34-146">The request was canceled using the specified <paramref name="cancellationToken" />.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetStateAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetStateAsync&lt;T&gt; (string stateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; GetStateAsync&lt;T&gt;(string stateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.GetStateAsync``1(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetStateAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'T&gt;" Usage="iActorStateManager.GetStateAsync (stateName, cancellationToken)" />
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
        <Parameter Name="stateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="41e34-147">特定の状態名に関連付けられている値の型。</span><span class="sxs-lookup"><span data-stu-id="41e34-147">Type of value associated with given state name.</span></span></typeparam>
        <param name="stateName"><span data-ttu-id="41e34-148">取得するアクター状態の名前です。</span><span class="sxs-lookup"><span data-stu-id="41e34-148">Name of the actor state to get.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="41e34-149">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="41e34-149">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="41e34-150">指定した状態の名前を持つ、アクターの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="41e34-150">Gets an actor state with specified state name.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="41e34-151">非同期の get 操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="41e34-151">A task that represents the asynchronous get operation.</span></span> <span data-ttu-id="41e34-152">パラメーターには、アクター状態の値が含まれています。 TResult の値は、状態の名前を指定します。</span><span class="sxs-lookup"><span data-stu-id="41e34-152">The value of TResult parameter contains value of actor state with given state name.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="41e34-153">状態値の型<typeparamref name="T" />する必要があります<see href="https://msdn.microsoft.com/library/ms731923.aspx">データ コントラクト</see>シリアル化可能です。</span><span class="sxs-lookup"><span data-stu-id="41e34-153">The type of state value <typeparamref name="T" /> must be <see href="https://msdn.microsoft.com/library/ms731923.aspx">Data Contract</see> serializable.</span></span>
            </remarks>
        <exception cref="T:System.Collections.Generic.KeyNotFoundException">
            <span data-ttu-id="41e34-154">アクター状態の特定の状態名がありません。</span><span class="sxs-lookup"><span data-stu-id="41e34-154">An actor state with given state name does not exist.</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="41e34-155">指定された状態の名前が null です。</span><span class="sxs-lookup"><span data-stu-id="41e34-155">The specified state name is null.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="41e34-156">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="41e34-156">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetStateNamesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;string&gt;&gt; GetStateNamesAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;string&gt;&gt; GetStateNamesAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.GetStateNamesAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetStateNamesAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;string&gt;&gt;" Usage="iActorStateManager.GetStateNamesAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="41e34-157">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="41e34-157">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="41e34-158">現在のアクターのすべてのアクターの状態名の列挙可能なが作成されます。</span><span class="sxs-lookup"><span data-stu-id="41e34-158">Creates an enumerable of all actor state names for current actor.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="41e34-159">非同期の列挙操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="41e34-159">A task that represents the asynchronous enumeration operation.</span></span> <span data-ttu-id="41e34-160">TResult パラメーターの値は、すべてのアクターの状態名の列挙です。</span><span class="sxs-lookup"><span data-stu-id="41e34-160">The value of TResult parameter is an enumerable of all actor state names.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="41e34-161">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="41e34-161">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveStateAsync (string stateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveStateAsync(string stateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.RemoveStateAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RemoveStateAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iActorStateManager.RemoveStateAsync (stateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="stateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="stateName"><span data-ttu-id="41e34-162">削除するアクター状態の名前です。</span><span class="sxs-lookup"><span data-stu-id="41e34-162">Name of the actor state to remove.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="41e34-163">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="41e34-163">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="41e34-164">指定した状態の名前を持つ、アクターの状態を削除します。</span><span class="sxs-lookup"><span data-stu-id="41e34-164">Removes an actor state with specified state name.</span></span>
            </summary>
        <returns><span data-ttu-id="41e34-165">非同期の削除操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="41e34-165">A task that represents the asynchronous remove operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Collections.Generic.KeyNotFoundException">
            <span data-ttu-id="41e34-166">アクター状態の特定の状態名がありません。</span><span class="sxs-lookup"><span data-stu-id="41e34-166">An actor state with given state name does not exist.</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException"> <span data-ttu-id="41e34-167">指定された状態の名前が null です。</span><span class="sxs-lookup"><span data-stu-id="41e34-167">The specified state name is null.</span></span> </exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="41e34-168">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="41e34-168">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="SaveStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SaveStateAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SaveStateAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.SaveStateAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SaveStateAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iActorStateManager.SaveStateAsync cancellationToken" />
      <MemberType>Method</MemberType>
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
        <param name="cancellationToken"><span data-ttu-id="41e34-169">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="41e34-169">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="41e34-170">キャッシュされた状態の変更を保存 (追加/更新/削除) 最後の呼び出し以降に行われた<see cref="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.SaveStateAsync(System.Threading.CancellationToken)" />アクター ランタイムによって、またはユーザーによって明示的にします。</span><span class="sxs-lookup"><span data-stu-id="41e34-170">Saves all the cached state changes (add/update/remove) that were made since last call to <see cref="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.SaveStateAsync(System.Threading.CancellationToken)" /> by actor runtime or by user explicitly.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="41e34-171">非同期の保存操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="41e34-171">A task that represents the asynchronous save operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetStateAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SetStateAsync&lt;T&gt; (string stateName, T value, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetStateAsync&lt;T&gt;(string stateName, !!T value, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.SetStateAsync``1(System.String,``0,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetStateAsync : string * 'T * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iActorStateManager.SetStateAsync (stateName, value, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="stateName" Type="System.String" />
        <Parameter Name="value" Type="T" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="41e34-172">特定の状態名に関連付けられている値の型。</span><span class="sxs-lookup"><span data-stu-id="41e34-172">Type of value associated with given state name.</span></span></typeparam>
        <param name="stateName"><span data-ttu-id="41e34-173">設定するアクター状態の名前です。</span><span class="sxs-lookup"><span data-stu-id="41e34-173">Name of the actor state to set.</span></span></param>
        <param name="value"><span data-ttu-id="41e34-174">アクター状態の値です。</span><span class="sxs-lookup"><span data-stu-id="41e34-174">Value of the actor state.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="41e34-175">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="41e34-175">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="41e34-176">アクターを持つ状態特定の状態名を指定した値を設定します。</span><span class="sxs-lookup"><span data-stu-id="41e34-176">Sets an actor state with given state name to specified value.</span></span>
            <span data-ttu-id="41e34-177">指定した名前のアクター状態が存在しない場合が追加されます。</span><span class="sxs-lookup"><span data-stu-id="41e34-177">If an actor state with specified name does not exist, it is added.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="41e34-178">一連の非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="41e34-178">A task that represents the asynchronous set operation.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="41e34-179">状態値の型<typeparamref name="T" />する必要があります<see href="https://msdn.microsoft.com/library/ms731923.aspx">データ コントラクト</see>シリアル化可能です。</span><span class="sxs-lookup"><span data-stu-id="41e34-179">The type of state value <typeparamref name="T" /> must be <see href="https://msdn.microsoft.com/library/ms731923.aspx">Data Contract</see> serializable.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="41e34-180">指定された状態の名前が null です。</span><span class="sxs-lookup"><span data-stu-id="41e34-180">The specified state name is null.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="41e34-181">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="41e34-181">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="TryAddStateAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; TryAddStateAsync&lt;T&gt; (string stateName, T value, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; TryAddStateAsync&lt;T&gt;(string stateName, !!T value, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.TryAddStateAsync``1(System.String,``0,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TryAddStateAsync : string * 'T * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iActorStateManager.TryAddStateAsync (stateName, value, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="stateName" Type="System.String" />
        <Parameter Name="value" Type="T" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="41e34-182">特定の状態名に関連付けられている値の型。</span><span class="sxs-lookup"><span data-stu-id="41e34-182">Type of value associated with given state name.</span></span></typeparam>
        <param name="stateName"><span data-ttu-id="41e34-183">追加するアクター状態の名前です。</span><span class="sxs-lookup"><span data-stu-id="41e34-183">Name of the actor state to add.</span></span></param>
        <param name="value"><span data-ttu-id="41e34-184">追加するアクター状態の値です。</span><span class="sxs-lookup"><span data-stu-id="41e34-184">Value of the actor state to add.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="41e34-185">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="41e34-185">The token to monitor for cancellation requests.</span></span>
            <span data-ttu-id="41e34-186">これは省略可能な既定値<see cref="P:System.Threading.CancellationToken.None" /></span><span class="sxs-lookup"><span data-stu-id="41e34-186">This is optional and defaults to <see cref="P:System.Threading.CancellationToken.None" /></span></span></param>
        <summary>
            <span data-ttu-id="41e34-187">アクターを追加する操作は、指定された状態の名前と値を持つ状態します。</span><span class="sxs-lookup"><span data-stu-id="41e34-187">Attempts to add an actor state with given state name and value.</span></span> <span data-ttu-id="41e34-188">同じ名前を持つ、アクター状態は既に存在する場合は false を返します。</span><span class="sxs-lookup"><span data-stu-id="41e34-188">Returns false if an actor state with the same name already exists.</span></span> 
            </summary>
        <returns>
            <span data-ttu-id="41e34-189">操作をブール値を表すタスクを非同期に追加します。</span><span class="sxs-lookup"><span data-stu-id="41e34-189">A boolean task that represents the asynchronous add operation.</span></span> <span data-ttu-id="41e34-190">True を返しますの場合、値が正常に追加し、false の場合と同じ名前のアクター状態既に存在します。</span><span class="sxs-lookup"><span data-stu-id="41e34-190">Returns true if the value was successfully added and false if an actor state with the same name already exists.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="41e34-191">状態値の型<typeparamref name="T" />する必要があります<see href="https://msdn.microsoft.com/library/ms731923.aspx">データ コントラクト</see>シリアル化可能です。</span><span class="sxs-lookup"><span data-stu-id="41e34-191">The type of state value <typeparamref name="T" /> must be <see href="https://msdn.microsoft.com/library/ms731923.aspx">Data Contract</see> serializable.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="41e34-192">指定された状態の名前が null です。</span><span class="sxs-lookup"><span data-stu-id="41e34-192">The specified state name is null.</span></span>
            <span data-ttu-id="41e34-193">有効な状態名の文字列を提供します。</span><span class="sxs-lookup"><span data-stu-id="41e34-193">Provide a valid state name string.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="41e34-194">指定されたを使用して、要求が取り消されました<paramref name="cancellationToken" />です。</span><span class="sxs-lookup"><span data-stu-id="41e34-194">The request was canceled using the specified <paramref name="cancellationToken" />.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="TryGetStateAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt; TryGetStateAsync&lt;T&gt; (string stateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!!T&gt;&gt; TryGetStateAsync&lt;T&gt;(string stateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.TryGetStateAsync``1(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TryGetStateAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;'T&gt;&gt;" Usage="iActorStateManager.TryGetStateAsync (stateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="stateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="41e34-195">特定の状態名に関連付けられている値の型。</span><span class="sxs-lookup"><span data-stu-id="41e34-195">Type of value associated with given state name.</span></span></typeparam>
        <param name="stateName"><span data-ttu-id="41e34-196">取得するアクター状態の名前です。</span><span class="sxs-lookup"><span data-stu-id="41e34-196">Name of the actor state to get.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="41e34-197">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="41e34-197">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="41e34-198">指定した状態の名前を持つ、アクター状態の取得を試みます。</span><span class="sxs-lookup"><span data-stu-id="41e34-198">Attempts to get an actor state with specified state name.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="41e34-199">非同期の get 操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="41e34-199">A task that represents the asynchronous get operation.</span></span> <span data-ttu-id="41e34-200">TResult パラメーターの値が含まれる<see cref="T:Microsoft.ServiceFabric.Data.ConditionalValue`1" />存在する場合は、アクターの状態が存在するかどうかとアクター状態の値を示すです。</span><span class="sxs-lookup"><span data-stu-id="41e34-200">The value of TResult parameter contains <see cref="T:Microsoft.ServiceFabric.Data.ConditionalValue`1" /> indicating whether the actor state is present and the value of actor state if it is present.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="41e34-201">状態値の型<typeparamref name="T" />する必要があります<see href="https://msdn.microsoft.com/library/ms731923.aspx">データ コントラクト</see>シリアル化可能です。</span><span class="sxs-lookup"><span data-stu-id="41e34-201">The type of state value <typeparamref name="T" /> must be <see href="https://msdn.microsoft.com/library/ms731923.aspx">Data Contract</see> serializable.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="41e34-202">指定された状態の名前が null です。</span><span class="sxs-lookup"><span data-stu-id="41e34-202">The specified state name is null.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="41e34-203">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="41e34-203">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="TryRemoveStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; TryRemoveStateAsync (string stateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; TryRemoveStateAsync(string stateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.TryRemoveStateAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TryRemoveStateAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iActorStateManager.TryRemoveStateAsync (stateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="stateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="stateName"><span data-ttu-id="41e34-204">削除するアクター状態の名前です。</span><span class="sxs-lookup"><span data-stu-id="41e34-204">Name of the actor state to remove.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="41e34-205">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="41e34-205">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="41e34-206">指定した状態の名前を持つ、アクター状態の削除を試みます。</span><span class="sxs-lookup"><span data-stu-id="41e34-206">Attempts to remove an actor state with specified state name.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="41e34-207">非同期の削除操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="41e34-207">A task that represents the asynchronous remove operation.</span></span> <span data-ttu-id="41e34-208">TResult のパラメーターの値は、状態が正常に削除されたかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="41e34-208">The value of TResult parameter indicates if the state was successfully removed.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"> <span data-ttu-id="41e34-209">指定された状態の名前が null です。</span><span class="sxs-lookup"><span data-stu-id="41e34-209">The specified state name is null.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="41e34-210">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="41e34-210">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
  </Members>
</Type>