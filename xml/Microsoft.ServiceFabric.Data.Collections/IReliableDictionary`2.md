<Type Name="IReliableDictionary&lt;TKey,TValue&gt;" FullName="Microsoft.ServiceFabric.Data.Collections.IReliableDictionary&lt;TKey,TValue&gt;">
  <TypeSignature Language="C#" Value="public interface IReliableDictionary&lt;TKey,TValue&gt; : Microsoft.ServiceFabric.Data.Collections.IReliableCollection&lt;System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;&gt; where TKey : IComparable&lt;TKey&gt;, IEquatable&lt;TKey&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IReliableDictionary`2&lt;(class System.IComparable`1&lt;!TKey&gt;, class System.IEquatable`1&lt;!TKey&gt;) TKey, TValue&gt; implements class Microsoft.ServiceFabric.Data.Collections.IReliableCollection`1&lt;valuetype System.Collections.Generic.KeyValuePair`2&lt;!TKey, !TValue&gt;&gt;, class Microsoft.ServiceFabric.Data.IReliableState" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />
  <TypeSignature Language="VB.NET" Value="Public Interface IReliableDictionary(Of TKey, TValue)&#xA;Implements IReliableCollection(Of KeyValuePair(Of TKey, TValue))" />
  <TypeSignature Language="F#" Value="type IReliableDictionary&lt;'Key, 'Value (requires 'Key :&gt; IComparable&lt;'Key&gt; and 'Key :&gt; IEquatable&lt;'Key&gt;)&gt; = interface&#xA;    interface IReliableCollection&lt;KeyValuePair&lt;'Key, 'Value&gt;&gt;&#xA;    interface IReliableState" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TKey">
      <Constraints>
        <InterfaceName>System.IComparable&lt;TKey&gt;</InterfaceName>
        <InterfaceName>System.IEquatable&lt;TKey&gt;</InterfaceName>
      </Constraints>
    </TypeParameter>
    <TypeParameter Name="TValue" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Data.Collections.IReliableCollection&lt;System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="TKey"><span data-ttu-id="6a08a-101">信頼性の高いディクショナリ内のキーの型。</span><span class="sxs-lookup"><span data-stu-id="6a08a-101">The type of the keys in the Reliable Dictionary.</span></span></typeparam>
    <typeparam name="TValue"><span data-ttu-id="6a08a-102">信頼性の高いディクショナリ内の値の型。</span><span class="sxs-lookup"><span data-stu-id="6a08a-102">The type of the values in the Reliable Dictionary.</span></span></typeparam>
    <summary>
      <para><span data-ttu-id="6a08a-103">信頼性の高い永続化されレプリケートされているキー/値ペアのコレクションを表します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-103">Represents a Reliable Collection of key/value pairs that are persisted and replicated.</span></span></para>
    </summary>
    <remarks>
      <para><span data-ttu-id="6a08a-104">ディクショナリでの操作のコンテキストの外部キーまたは MUST NOT このディクショナリに格納されている値は変換。</span><span class="sxs-lookup"><span data-stu-id="6a08a-104">Keys or values stored in this dictionary MUST NOT be mutated outside the context of an operation on the dictionary.</span></span> <span data-ttu-id="6a08a-105">両方をお勧め<typeparamref name="TKey" />と<typeparamref name="TValue" />偶発的なデータの破損を回避するために変更できません。</span><span class="sxs-lookup"><span data-stu-id="6a08a-105">It is highly recommended to make both <typeparamref name="TKey" /> and <typeparamref name="TValue" /> immutable in order to avoid accidental data corruption.</span></span>
            <span data-ttu-id="6a08a-106">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-work-with-reliable-collections">ここ</see>よくある落とし穴をします。</span><span class="sxs-lookup"><span data-stu-id="6a08a-106">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-work-with-reliable-collections">here</see> for common pitfalls.</span></span></para>
      <para><span data-ttu-id="6a08a-107">トランザクションは、同時実行の単位です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-107">The transaction is the unit of concurrency.</span></span> <span data-ttu-id="6a08a-108">ユーザーが特定の時点の時間、インフライトの複数のトランザクションを持つことができますが、特定のトランザクションの各 API 呼び出す必要があります、一度に 1 つ。</span><span class="sxs-lookup"><span data-stu-id="6a08a-108">Users can have multiple transactions in-flight at any given point of time, but for a given transaction each API must be called one at a time.</span></span>
            <span data-ttu-id="6a08a-109">非同期信頼性の高いコレクション メソッドの呼び出しがいつ、 <see cref="T:Microsoft.ServiceFabric.Data.ITransaction" />、同じトランザクションを使用して別のメソッドを呼び出す前に、返されるタスクの完了を待つ必要があります。</span><span class="sxs-lookup"><span data-stu-id="6a08a-109">When calling any asynchronous Reliable Collection method that takes an <see cref="T:Microsoft.ServiceFabric.Data.ITransaction" />, you must wait for completion of the returned Task before calling another method using the same transaction.</span></span> <span data-ttu-id="6a08a-110">トランザクションの例を参照して<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-work-with-reliable-collections">ここ</see>です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-110">See examples of transactions <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-work-with-reliable-collections">here</see>.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="AddAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AddAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, TValue value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AddAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, !TValue value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.AddAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,`1)" />
      <MemberSignature Language="VB.NET" Value="Public Function AddAsync (tx As ITransaction, key As TKey, value As TValue) As Task" />
      <MemberSignature Language="F#" Value="abstract member AddAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * 'Value -&gt; System.Threading.Tasks.Task" Usage="iReliableDictionary.AddAsync (tx, key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="value" Type="TValue" />
      </Parameters>
      <Docs>
        <param name="tx"><span data-ttu-id="6a08a-111">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="6a08a-111">Transaction to associate this operation with.</span></span></param>
        <param name="key"><span data-ttu-id="6a08a-112">追加されるキー。</span><span class="sxs-lookup"><span data-stu-id="6a08a-112">The key to be added.</span></span></param>
        <param name="value"><span data-ttu-id="6a08a-113">追加する値。</span><span class="sxs-lookup"><span data-stu-id="6a08a-113">The value to be added.</span></span> <span data-ttu-id="6a08a-114">参照型の場合は、値を null にできます。</span><span class="sxs-lookup"><span data-stu-id="6a08a-114">The value can be null for reference types.</span></span></param>
        <summary>
            <span data-ttu-id="6a08a-115">信頼性の高いディクショナリに、指定したキー/値ペアを追加します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-115">Adds the specified key/value pair to the Reliable Dictionary.</span></span>
            </summary>
        <returns><span data-ttu-id="6a08a-116">表す非同期のタスクは、操作を追加します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-116">A task that represents the asynchronous add operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="6a08a-117"><paramref name="tx" />null、または<paramref name="key" />が null またはシリアル化することはできません。</span><span class="sxs-lookup"><span data-stu-id="6a08a-117"><paramref name="tx" /> is null, or <paramref name="key" /> is null or cannot be serialized.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="6a08a-118">同じキーを持つ値は、信頼性の高いディクショナリに既に存在します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-118">A value with the same key already exists in the Reliable Dictionary.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="6a08a-119">既定のタイムアウト以内に完了する操作が失敗しました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-119">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="6a08a-120">ときにスローされる例外、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-120">The exception that is thrown when the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="6a08a-121">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-121">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="6a08a-122">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="6a08a-122">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="6a08a-123">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6a08a-123">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="6a08a-124">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-124">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="6a08a-125">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="6a08a-125">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="6a08a-126">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-126">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="AddAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AddAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, TValue value, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AddAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, !TValue value, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.AddAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,`1,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * 'Value * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iReliableDictionary.AddAsync (tx, key, value, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="value" Type="TValue" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="tx"><span data-ttu-id="6a08a-127">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="6a08a-127">Transaction to associate this operation with.</span></span></param>
        <param name="key"><span data-ttu-id="6a08a-128">追加されるキー。</span><span class="sxs-lookup"><span data-stu-id="6a08a-128">The key to be added.</span></span></param>
        <param name="value"><span data-ttu-id="6a08a-129">追加する値。</span><span class="sxs-lookup"><span data-stu-id="6a08a-129">The value to be added.</span></span> <span data-ttu-id="6a08a-130">参照型の場合は、値を null にできます。</span><span class="sxs-lookup"><span data-stu-id="6a08a-130">The value can be null for reference types.</span></span></param>
        <param name="timeout"><span data-ttu-id="6a08a-131">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。</span><span class="sxs-lookup"><span data-stu-id="6a08a-131">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="6a08a-132">主にデッドロックを防ぐために使用します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-132">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="6a08a-133">既定では 4 秒です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-133">The default is 4 seconds.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="6a08a-134">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="6a08a-134">The token to monitor for cancellation requests.</span></span> <span data-ttu-id="6a08a-135">既定値は None です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-135">The default is None.</span></span></param>
        <summary>
            <span data-ttu-id="6a08a-136">信頼性の高いディクショナリに、指定したキー/値ペアを追加します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-136">Adds the specified key/value pair to the Reliable Dictionary.</span></span>
            </summary>
        <returns><span data-ttu-id="6a08a-137">表す非同期のタスクは、操作を追加します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-137">A task that represents the asynchronous add operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="6a08a-138"><paramref name="tx" />null、または<paramref name="key" />が null またはシリアル化することはできません。</span><span class="sxs-lookup"><span data-stu-id="6a08a-138"><paramref name="tx" /> is null, or <paramref name="key" /> is null or cannot be serialized.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="6a08a-139">同じキーを持つ値は、信頼性の高いディクショナリに既に存在または<paramref name="timeout" />が負の値。</span><span class="sxs-lookup"><span data-stu-id="6a08a-139">A value with the same key already exists in the Reliable Dictionary, or <paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="6a08a-140">操作は、指定したタイムアウト時間内に完了できませんでした。</span><span class="sxs-lookup"><span data-stu-id="6a08a-140">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="6a08a-141">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-141">The operation was canceled.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="6a08a-142">ときにスローされる例外、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-142">The exception that is thrown when the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="6a08a-143">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-143">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="6a08a-144">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="6a08a-144">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="6a08a-145">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6a08a-145">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="6a08a-146">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-146">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="6a08a-147">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="6a08a-147">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="6a08a-148">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-148">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="AddOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;TValue&gt; AddOrUpdateAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, Func&lt;TKey,TValue&gt; addValueFactory, Func&lt;TKey,TValue,TValue&gt; updateValueFactory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TValue&gt; AddOrUpdateAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, class System.Func`2&lt;!TKey, !TValue&gt; addValueFactory, class System.Func`3&lt;!TKey, !TValue, !TValue&gt; updateValueFactory) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.AddOrUpdateAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.Func{`0,`1},System.Func{`0,`1,`1})" />
      <MemberSignature Language="VB.NET" Value="Public Function AddOrUpdateAsync (tx As ITransaction, key As TKey, addValueFactory As Func(Of TKey, TValue), updateValueFactory As Func(Of TKey, TValue, TValue)) As Task(Of TValue)" />
      <MemberSignature Language="F#" Value="abstract member AddOrUpdateAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * Func&lt;'Key, 'Value (requires 'Key :&gt; IComparable&lt;'Key&gt; and 'Key :&gt; IEquatable&lt;'Key&gt;)&gt; * Func&lt;'Key, 'Value, 'Value (requires 'Key :&gt; IComparable&lt;'Key&gt; and 'Key :&gt; IEquatable&lt;'Key&gt;)&gt; -&gt; System.Threading.Tasks.Task&lt;'Value&gt;" Usage="iReliableDictionary.AddOrUpdateAsync (tx, key, addValueFactory, updateValueFactory)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TValue&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="addValueFactory" Type="System.Func&lt;TKey,TValue&gt;" />
        <Parameter Name="updateValueFactory" Type="System.Func&lt;TKey,TValue,TValue&gt;" />
      </Parameters>
      <Docs>
        <param name="tx"><span data-ttu-id="6a08a-149">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="6a08a-149">Transaction to associate this operation with.</span></span></param>
        <param name="key"><span data-ttu-id="6a08a-150">追加するキーまたは値を更新するキー。</span><span class="sxs-lookup"><span data-stu-id="6a08a-150">The key to be added or whose value should be updated.</span></span></param>
        <param name="addValueFactory"><span data-ttu-id="6a08a-151">キーが存在しない場合に、値を生成するために使用される関数。</span><span class="sxs-lookup"><span data-stu-id="6a08a-151">The function used to generate a value for an absent key.</span></span></param>
        <param name="updateValueFactory"><span data-ttu-id="6a08a-152">キーの既存の値に基づいて、既存のキーの新しい値を生成するために使用される関数。</span><span class="sxs-lookup"><span data-stu-id="6a08a-152">The function used to generate a new value for an existing key based on the key's existing value.</span></span></param>
        <summary>
            <span data-ttu-id="6a08a-153">キーが既に存在しない場合に、信頼性の高い辞書にキー/値ペアを追加するか、キーが既に存在する場合は、信頼性の高いディクショナリのキー/値ペアを更新する、指定された関数を使用します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-153">Uses the specified functions to add a key/value pair to the Reliable Dictionary if the key does not already exist, or to update a key/value pair in the Reliable Dictionary if the key already exists.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="6a08a-154">非同期の追加または更新操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="6a08a-154">Task that represents the asynchronous add or update operation.</span></span> <span data-ttu-id="6a08a-155">タスクの結果は、キーの新しい値です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-155">The task result is the new value for the key.</span></span> <span data-ttu-id="6a08a-156">これは、なります、addValueFactory の結果 (キーが存在しない場合) か updateValueFactory の結果 (キーが存在) 場合。</span><span class="sxs-lookup"><span data-stu-id="6a08a-156">This will be either the result of addValueFactory (if the key was absent) or the result of updateValueFactory (if the key was present).</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="6a08a-157"><paramref name="tx" />null、または<paramref name="key" />が null またはシリアル化できませんまたは<paramref name="addValueFactory" />が null、または<paramref name="updateValueFactory" />が null です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-157"><paramref name="tx" /> is null, or <paramref name="key" /> is null or cannot be serialized, or <paramref name="addValueFactory" /> is null, or <paramref name="updateValueFactory" /> is null.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="6a08a-158">既定のタイムアウト以内に完了する操作が失敗しました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-158">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="6a08a-159">ときにスローされる例外、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-159">The exception that is thrown when the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="6a08a-160">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-160">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="6a08a-161">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="6a08a-161">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="6a08a-162">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6a08a-162">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="6a08a-163">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-163">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="6a08a-164">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="6a08a-164">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="6a08a-165">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-165">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="AddOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;TValue&gt; AddOrUpdateAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, TValue addValue, Func&lt;TKey,TValue,TValue&gt; updateValueFactory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TValue&gt; AddOrUpdateAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, !TValue addValue, class System.Func`3&lt;!TKey, !TValue, !TValue&gt; updateValueFactory) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.AddOrUpdateAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,`1,System.Func{`0,`1,`1})" />
      <MemberSignature Language="VB.NET" Value="Public Function AddOrUpdateAsync (tx As ITransaction, key As TKey, addValue As TValue, updateValueFactory As Func(Of TKey, TValue, TValue)) As Task(Of TValue)" />
      <MemberSignature Language="F#" Value="abstract member AddOrUpdateAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * 'Value * Func&lt;'Key, 'Value, 'Value (requires 'Key :&gt; IComparable&lt;'Key&gt; and 'Key :&gt; IEquatable&lt;'Key&gt;)&gt; -&gt; System.Threading.Tasks.Task&lt;'Value&gt;" Usage="iReliableDictionary.AddOrUpdateAsync (tx, key, addValue, updateValueFactory)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TValue&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="addValue" Type="TValue" />
        <Parameter Name="updateValueFactory" Type="System.Func&lt;TKey,TValue,TValue&gt;" />
      </Parameters>
      <Docs>
        <param name="tx"><span data-ttu-id="6a08a-166">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="6a08a-166">Transaction to associate this operation with.</span></span></param>
        <param name="key"><span data-ttu-id="6a08a-167">追加するキーまたは値を更新するキー。</span><span class="sxs-lookup"><span data-stu-id="6a08a-167">The key to be added or whose value should be updated.</span></span></param>
        <param name="addValue"><span data-ttu-id="6a08a-168">キーが存在しない場合に追加する値。</span><span class="sxs-lookup"><span data-stu-id="6a08a-168">The value to be added for an absent key.</span></span> <span data-ttu-id="6a08a-169">参照型の場合は、値を null にできます。</span><span class="sxs-lookup"><span data-stu-id="6a08a-169">The value can be null for reference types.</span></span></param>
        <param name="updateValueFactory"><span data-ttu-id="6a08a-170">キーの既存の値に基づいて、既存のキーの新しい値を生成するために使用される関数。</span><span class="sxs-lookup"><span data-stu-id="6a08a-170">The function used to generate a new value for an existing key based on the key's existing value.</span></span></param>
        <summary>
            <span data-ttu-id="6a08a-171">キーが既に存在しない場合、キーが既に存在する場合、指定された関数を使用して、信頼性の高いディクショナリのキー/値ペアを更新、信頼性の高い辞書にキー/値ペアを追加します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-171">Adds a key/value pair to the Reliable Dictionary if the key does not already exist, or updates a key/value pair in the Reliable Dictionary by using the specified function if the key already exists.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="6a08a-172">非同期の追加または更新操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="6a08a-172">Task that represents the asynchronous add or update operation.</span></span> <span data-ttu-id="6a08a-173">タスクの結果は、キーの新しい値です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-173">The task result is the new value for the key.</span></span> <span data-ttu-id="6a08a-174">これは、されますか、addValue (キーが存在しない場合) か updateValueFactory の結果 (キーが存在) 場合。</span><span class="sxs-lookup"><span data-stu-id="6a08a-174">This will be either addValue (if the key was absent) or the result of updateValueFactory (if the key was present).</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="6a08a-175"><paramref name="tx" />null、または<paramref name="key" />が null またはシリアル化できませんまたは<paramref name="updateValueFactory" />が null です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-175"><paramref name="tx" /> is null, or <paramref name="key" /> is null or cannot be serialized, or <paramref name="updateValueFactory" /> is null.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="6a08a-176">既定のタイムアウト以内に完了する操作が失敗しました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-176">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="6a08a-177">ときにスローされる例外、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-177">The exception that is thrown when the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="6a08a-178">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-178">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="6a08a-179">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="6a08a-179">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="6a08a-180">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6a08a-180">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="6a08a-181">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-181">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="6a08a-182">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="6a08a-182">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="6a08a-183">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-183">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="AddOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;TValue&gt; AddOrUpdateAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, Func&lt;TKey,TValue&gt; addValueFactory, Func&lt;TKey,TValue,TValue&gt; updateValueFactory, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TValue&gt; AddOrUpdateAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, class System.Func`2&lt;!TKey, !TValue&gt; addValueFactory, class System.Func`3&lt;!TKey, !TValue, !TValue&gt; updateValueFactory, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.AddOrUpdateAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.Func{`0,`1},System.Func{`0,`1,`1},System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddOrUpdateAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * Func&lt;'Key, 'Value (requires 'Key :&gt; IComparable&lt;'Key&gt; and 'Key :&gt; IEquatable&lt;'Key&gt;)&gt; * Func&lt;'Key, 'Value, 'Value (requires 'Key :&gt; IComparable&lt;'Key&gt; and 'Key :&gt; IEquatable&lt;'Key&gt;)&gt; * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'Value&gt;" Usage="iReliableDictionary.AddOrUpdateAsync (tx, key, addValueFactory, updateValueFactory, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TValue&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="addValueFactory" Type="System.Func&lt;TKey,TValue&gt;" />
        <Parameter Name="updateValueFactory" Type="System.Func&lt;TKey,TValue,TValue&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="tx"><span data-ttu-id="6a08a-184">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="6a08a-184">Transaction to associate this operation with.</span></span></param>
        <param name="key"><span data-ttu-id="6a08a-185">追加するキーまたは値を更新するキー。</span><span class="sxs-lookup"><span data-stu-id="6a08a-185">The key to be added or whose value should be updated.</span></span></param>
        <param name="addValueFactory"><span data-ttu-id="6a08a-186">キーが存在しない場合に、値を生成するために使用される関数。</span><span class="sxs-lookup"><span data-stu-id="6a08a-186">The function used to generate a value for an absent key.</span></span></param>
        <param name="updateValueFactory"><span data-ttu-id="6a08a-187">キーの既存の値に基づいて、既存のキーの新しい値を生成するために使用される関数。</span><span class="sxs-lookup"><span data-stu-id="6a08a-187">The function used to generate a new value for an existing key based on the key's existing value.</span></span></param>
        <param name="timeout"><span data-ttu-id="6a08a-188">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。</span><span class="sxs-lookup"><span data-stu-id="6a08a-188">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="6a08a-189">主にデッドロックを防ぐために使用します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-189">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="6a08a-190">既定では 4 秒です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-190">The default is 4 seconds.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="6a08a-191">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="6a08a-191">The token to monitor for cancellation requests.</span></span> <span data-ttu-id="6a08a-192">既定値は None です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-192">The default is None.</span></span></param>
        <summary>
            <span data-ttu-id="6a08a-193">キーが既に存在しない場合に、信頼性の高い辞書にキー/値ペアを追加するか、キーが既に存在する場合は、信頼性の高いディクショナリのキー/値ペアを更新する、指定された関数を使用します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-193">Uses the specified functions to add a key/value pair to the Reliable Dictionary if the key does not already exist, or to update a key/value pair in the Reliable Dictionary if the key already exists.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="6a08a-194">非同期の追加または更新操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="6a08a-194">Task that represents the asynchronous add or update operation.</span></span> <span data-ttu-id="6a08a-195">タスクの結果は、キーの新しい値です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-195">The task result is the new value for the key.</span></span> <span data-ttu-id="6a08a-196">これは、なります、addValueFactory の結果 (キーが存在しない場合) か updateValueFactory の結果 (キーが存在) 場合。</span><span class="sxs-lookup"><span data-stu-id="6a08a-196">This will be either the result of addValueFactory (if the key was absent) or the result of updateValueFactory (if the key was present).</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="6a08a-197"><paramref name="tx" />null、または<paramref name="key" />が null またはシリアル化できませんまたは<paramref name="addValueFactory" />が null、または<paramref name="updateValueFactory" />が null です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-197"><paramref name="tx" /> is null, or <paramref name="key" /> is null or cannot be serialized, or <paramref name="addValueFactory" /> is null, or <paramref name="updateValueFactory" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="6a08a-198"><paramref name="timeout" /> が負の値です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-198"><paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="6a08a-199">操作は、指定したタイムアウト時間内に完了できませんでした。</span><span class="sxs-lookup"><span data-stu-id="6a08a-199">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="6a08a-200">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-200">The operation was canceled.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="6a08a-201">ときにスローされる例外、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-201">The exception that is thrown when the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="6a08a-202">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-202">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="6a08a-203">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="6a08a-203">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="6a08a-204">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6a08a-204">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="6a08a-205">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-205">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="6a08a-206">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="6a08a-206">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="6a08a-207">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-207">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="AddOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;TValue&gt; AddOrUpdateAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, TValue addValue, Func&lt;TKey,TValue,TValue&gt; updateValueFactory, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TValue&gt; AddOrUpdateAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, !TValue addValue, class System.Func`3&lt;!TKey, !TValue, !TValue&gt; updateValueFactory, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.AddOrUpdateAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,`1,System.Func{`0,`1,`1},System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddOrUpdateAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * 'Value * Func&lt;'Key, 'Value, 'Value (requires 'Key :&gt; IComparable&lt;'Key&gt; and 'Key :&gt; IEquatable&lt;'Key&gt;)&gt; * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'Value&gt;" Usage="iReliableDictionary.AddOrUpdateAsync (tx, key, addValue, updateValueFactory, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TValue&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="addValue" Type="TValue" />
        <Parameter Name="updateValueFactory" Type="System.Func&lt;TKey,TValue,TValue&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="tx"><span data-ttu-id="6a08a-208">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="6a08a-208">Transaction to associate this operation with.</span></span></param>
        <param name="key"><span data-ttu-id="6a08a-209">追加するキーまたは値を更新するキー。</span><span class="sxs-lookup"><span data-stu-id="6a08a-209">The key to be added or whose value should be updated.</span></span></param>
        <param name="addValue"><span data-ttu-id="6a08a-210">キーが存在しない場合に追加する値。</span><span class="sxs-lookup"><span data-stu-id="6a08a-210">The value to be added for an absent key.</span></span> <span data-ttu-id="6a08a-211">参照型の場合は、値を null にできます。</span><span class="sxs-lookup"><span data-stu-id="6a08a-211">The value can be null for reference types.</span></span></param>
        <param name="updateValueFactory"><span data-ttu-id="6a08a-212">キーの既存の値に基づいて、既存のキーの新しい値を生成するために使用される関数。</span><span class="sxs-lookup"><span data-stu-id="6a08a-212">The function used to generate a new value for an existing key based on the key's existing value.</span></span></param>
        <param name="timeout"><span data-ttu-id="6a08a-213">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。</span><span class="sxs-lookup"><span data-stu-id="6a08a-213">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="6a08a-214">主にデッドロックを防ぐために使用します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-214">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="6a08a-215">既定では 4 秒です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-215">The default is 4 seconds.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="6a08a-216">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="6a08a-216">The token to monitor for cancellation requests.</span></span> <span data-ttu-id="6a08a-217">既定値は None です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-217">The default is None.</span></span></param>
        <summary>
            <span data-ttu-id="6a08a-218">キーが既に存在しない場合、キーが既に存在する場合、指定された関数を使用して、信頼性の高いディクショナリのキー/値ペアを更新、信頼性の高い辞書にキー/値ペアを追加します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-218">Adds a key/value pair to the Reliable Dictionary if the key does not already exist, or updates a key/value pair in the Reliable Dictionary by using the specified function if the key already exists.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="6a08a-219">非同期の追加または更新操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="6a08a-219">Task that represents the asynchronous add or update operation.</span></span> <span data-ttu-id="6a08a-220">タスクの結果は、キーの新しい値です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-220">The task result is the new value for the key.</span></span> <span data-ttu-id="6a08a-221">これは、されますか、addValue (キーが存在しない場合) か updateValueFactory の結果 (キーが存在) 場合。</span><span class="sxs-lookup"><span data-stu-id="6a08a-221">This will be either addValue (if the key was absent) or the result of updateValueFactory (if the key was present).</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="6a08a-222"><paramref name="tx" />null、または<paramref name="key" />が null またはシリアル化できませんまたは<paramref name="updateValueFactory" />が null です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-222"><paramref name="tx" /> is null, or <paramref name="key" /> is null or cannot be serialized, or <paramref name="updateValueFactory" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="6a08a-223"><paramref name="timeout" /> が負の値です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-223"><paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="6a08a-224">操作は、指定したタイムアウト時間内に完了できませんでした。</span><span class="sxs-lookup"><span data-stu-id="6a08a-224">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="6a08a-225">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-225">The operation was canceled.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="6a08a-226">ときにスローされる例外、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-226">The exception that is thrown when the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="6a08a-227">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-227">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="6a08a-228">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="6a08a-228">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="6a08a-229">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6a08a-229">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="6a08a-230">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-230">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="6a08a-231">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="6a08a-231">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="6a08a-232">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-232">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ClearAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ClearAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ClearAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.ClearAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ClearAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iReliableDictionary.ClearAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout"><span data-ttu-id="6a08a-233">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。</span><span class="sxs-lookup"><span data-stu-id="6a08a-233">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="6a08a-234">主にデッドロックを防ぐために使用します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-234">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="6a08a-235">既定では 4 秒です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-235">The default is 4 seconds.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="6a08a-236">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="6a08a-236">The token to monitor for cancellation requests.</span></span> <span data-ttu-id="6a08a-237">既定値は None です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-237">The default is None.</span></span></param>
        <summary>
            <span data-ttu-id="6a08a-238">信頼性の高いディクショナリからすべてのキーと値を削除します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-238">Removes all keys and values from the Reliable Dictionary.</span></span>
            </summary>
        <returns><span data-ttu-id="6a08a-239">非同期のクリア操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="6a08a-239">Task that represents the asynchronous clear operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="6a08a-240"><paramref name="timeout" /> が負の値です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-240"><paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="6a08a-241">操作は、指定したタイムアウト時間内に完了できませんでした。</span><span class="sxs-lookup"><span data-stu-id="6a08a-241">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="6a08a-242">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-242">The operation was canceled.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="6a08a-243">ときにスローされる例外、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-243">The exception that is thrown when the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ContainsKeyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; ContainsKeyAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ContainsKeyAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.ContainsKeyAsync(Microsoft.ServiceFabric.Data.ITransaction,`0)" />
      <MemberSignature Language="VB.NET" Value="Public Function ContainsKeyAsync (tx As ITransaction, key As TKey) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member ContainsKeyAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iReliableDictionary.ContainsKeyAsync (tx, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
      </Parameters>
      <Docs>
        <param name="tx"><span data-ttu-id="6a08a-244">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="6a08a-244">Transaction to associate this operation with.</span></span></param>
        <param name="key"><span data-ttu-id="6a08a-245">信頼性の高いディクショナリ内で検索するキー。</span><span class="sxs-lookup"><span data-stu-id="6a08a-245">The key to locate in the Reliable Dictionary.</span></span></param>
        <summary>
            <span data-ttu-id="6a08a-246">信頼性の高いディクショナリに指定したキーが含まれているかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-246">Determines whether the Reliable Dictionary contains the specified key.</span></span>
            </summary>
        <returns><span data-ttu-id="6a08a-247">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="6a08a-247">A task that represents the asynchronous operation.</span></span> <span data-ttu-id="6a08a-248">タスクの結果は、キーが存在するかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-248">The task result indicates whether the key exists.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="6a08a-249"><paramref name="tx" />null、または<paramref name="key" />が null またはシリアル化することはできません。</span><span class="sxs-lookup"><span data-stu-id="6a08a-249"><paramref name="tx" /> is null, or <paramref name="key" /> is null or cannot be serialized.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="6a08a-250">既定のタイムアウト以内に完了する操作が失敗しました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-250">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            <span data-ttu-id="6a08a-251">IReliableDictionary が現時点での読み取りを使用できないことを示します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-251">Indicates that the IReliableDictionary cannot serve reads at the moment.</span></span>
            <span data-ttu-id="6a08a-252">すべてのページでこの例外はスローされる<see cref="T:System.Fabric.ReplicaRole" />s。</span><span class="sxs-lookup"><span data-stu-id="6a08a-252">This exception can be thrown in all <see cref="T:System.Fabric.ReplicaRole" />s.</span></span>
            <span data-ttu-id="6a08a-253">1 つの理由でスローされる可能性が、<see cref="F:System.Fabric.ReplicaRole.Primary" />ロールが失われる<see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-253">One reason it may be thrown in the <see cref="F:System.Fabric.ReplicaRole.Primary" /> role is loss of <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span></span>
            <span data-ttu-id="6a08a-254">1 つの理由でスローされる可能性が、<see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />ロールは、信頼性の高いコレクションの状態があるまだ一貫性のあります。</span><span class="sxs-lookup"><span data-stu-id="6a08a-254">One reason it may be thrown in the <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> role is that Reliable Collection's state is not yet consistent.</span></span>
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="6a08a-255">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-255">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="6a08a-256">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="6a08a-256">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="6a08a-257">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6a08a-257">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="6a08a-258">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-258">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="6a08a-259">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="6a08a-259">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="6a08a-260">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-260">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ContainsKeyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; ContainsKeyAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, Microsoft.ServiceFabric.Data.Collections.LockMode lockMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ContainsKeyAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, valuetype Microsoft.ServiceFabric.Data.Collections.LockMode lockMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.ContainsKeyAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,Microsoft.ServiceFabric.Data.Collections.LockMode)" />
      <MemberSignature Language="F#" Value="abstract member ContainsKeyAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * Microsoft.ServiceFabric.Data.Collections.LockMode -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iReliableDictionary.ContainsKeyAsync (tx, key, lockMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="lockMode" Type="Microsoft.ServiceFabric.Data.Collections.LockMode" />
      </Parameters>
      <Docs>
        <param name="tx"><span data-ttu-id="6a08a-261">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="6a08a-261">Transaction to associate this operation with.</span></span></param>
        <param name="key"><span data-ttu-id="6a08a-262">信頼性の高いディクショナリ内で検索するキー。</span><span class="sxs-lookup"><span data-stu-id="6a08a-262">The key to locate in the Reliable Dictionary.</span></span></param>
        <param name="lockMode"><span data-ttu-id="6a08a-263">この読み取り操作に使用するロックの種類です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-263">Type of locking to use for this read operation.</span></span></param>
        <summary>
            <span data-ttu-id="6a08a-264">信頼性の高いディクショナリに指定したキーが含まれているかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-264">Determines whether the Reliable Dictionary contains the specified key.</span></span>
            </summary>
        <returns><span data-ttu-id="6a08a-265">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="6a08a-265">A task that represents the asynchronous operation.</span></span> <span data-ttu-id="6a08a-266">タスクの結果は、キーが存在するかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-266">The task result indicates whether the key exists.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="6a08a-267"><paramref name="tx" />null、または<paramref name="key" />が null またはシリアル化することはできません。</span><span class="sxs-lookup"><span data-stu-id="6a08a-267"><paramref name="tx" /> is null, or <paramref name="key" /> is null or cannot be serialized.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="6a08a-268">既定のタイムアウト以内に完了する操作が失敗しました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-268">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            <span data-ttu-id="6a08a-269">IReliableDictionary が現時点での読み取りを使用できないことを示します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-269">Indicates that the IReliableDictionary cannot serve reads at the moment.</span></span>
            <span data-ttu-id="6a08a-270">すべてのページでこの例外はスローされる<see cref="T:System.Fabric.ReplicaRole" />s。</span><span class="sxs-lookup"><span data-stu-id="6a08a-270">This exception can be thrown in all <see cref="T:System.Fabric.ReplicaRole" />s.</span></span>
            <span data-ttu-id="6a08a-271">1 つの理由でスローされる可能性が、<see cref="F:System.Fabric.ReplicaRole.Primary" />ロールが失われる<see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-271">One reason it may be thrown in the <see cref="F:System.Fabric.ReplicaRole.Primary" /> role is loss of <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span></span>
            <span data-ttu-id="6a08a-272">1 つの理由でスローされる可能性が、<see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />ロールは、信頼性の高いコレクションの状態があるまだ一貫性のあります。</span><span class="sxs-lookup"><span data-stu-id="6a08a-272">One reason it may be thrown in the <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> role is that Reliable Collection's state is not yet consistent.</span></span>
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="6a08a-273">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-273">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="6a08a-274">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="6a08a-274">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="6a08a-275">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6a08a-275">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="6a08a-276">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-276">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="6a08a-277">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="6a08a-277">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="6a08a-278">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-278">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ContainsKeyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; ContainsKeyAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ContainsKeyAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.ContainsKeyAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ContainsKeyAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iReliableDictionary.ContainsKeyAsync (tx, key, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="tx"><span data-ttu-id="6a08a-279">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="6a08a-279">Transaction to associate this operation with.</span></span></param>
        <param name="key"><span data-ttu-id="6a08a-280">信頼性の高いディクショナリ内で検索するキー。</span><span class="sxs-lookup"><span data-stu-id="6a08a-280">The key to locate in the Reliable Dictionary.</span></span></param>
        <param name="timeout"><span data-ttu-id="6a08a-281">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。</span><span class="sxs-lookup"><span data-stu-id="6a08a-281">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="6a08a-282">主にデッドロックを防ぐために使用します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-282">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="6a08a-283">既定では 4 秒です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-283">The default is 4 seconds.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="6a08a-284">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="6a08a-284">The token to monitor for cancellation requests.</span></span> <span data-ttu-id="6a08a-285">既定値は None です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-285">The default is None.</span></span></param>
        <summary>
            <span data-ttu-id="6a08a-286">信頼性の高いディクショナリに指定したキーが含まれているかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-286">Determines whether the Reliable Dictionary contains the specified key.</span></span>
            </summary>
        <returns><span data-ttu-id="6a08a-287">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="6a08a-287">A task that represents the asynchronous operation.</span></span> <span data-ttu-id="6a08a-288">タスクの結果は、キーが存在するかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-288">The task result indicates whether the key exists.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="6a08a-289"><paramref name="tx" />null、または<paramref name="key" />が null またはシリアル化することはできません。</span><span class="sxs-lookup"><span data-stu-id="6a08a-289"><paramref name="tx" /> is null, or <paramref name="key" /> is null or cannot be serialized.</span></span></exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="6a08a-290"><paramref name="timeout" /> が負の値です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-290"><paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="6a08a-291">操作は、指定したタイムアウト時間内に完了できませんでした。</span><span class="sxs-lookup"><span data-stu-id="6a08a-291">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="6a08a-292">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-292">The operation was canceled.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            <span data-ttu-id="6a08a-293">IReliableDictionary が現時点での読み取りを使用できないことを示します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-293">Indicates that the IReliableDictionary cannot serve reads at the moment.</span></span>
            <span data-ttu-id="6a08a-294">すべてのページでこの例外はスローされる<see cref="T:System.Fabric.ReplicaRole" />s。</span><span class="sxs-lookup"><span data-stu-id="6a08a-294">This exception can be thrown in all <see cref="T:System.Fabric.ReplicaRole" />s.</span></span>
            <span data-ttu-id="6a08a-295">1 つの理由でスローされる可能性が、<see cref="F:System.Fabric.ReplicaRole.Primary" />ロールが失われる<see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-295">One reason it may be thrown in the <see cref="F:System.Fabric.ReplicaRole.Primary" /> role is loss of <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span></span>
            <span data-ttu-id="6a08a-296">1 つの理由でスローされる可能性が、<see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />ロールは、信頼性の高いコレクションの状態があるまだ一貫性のあります。</span><span class="sxs-lookup"><span data-stu-id="6a08a-296">One reason it may be thrown in the <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> role is that Reliable Collection's state is not yet consistent.</span></span>
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="6a08a-297">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-297">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="6a08a-298">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="6a08a-298">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="6a08a-299">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6a08a-299">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="6a08a-300">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-300">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="6a08a-301">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="6a08a-301">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="6a08a-302">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-302">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ContainsKeyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; ContainsKeyAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, Microsoft.ServiceFabric.Data.Collections.LockMode lockMode, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ContainsKeyAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, valuetype Microsoft.ServiceFabric.Data.Collections.LockMode lockMode, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.ContainsKeyAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,Microsoft.ServiceFabric.Data.Collections.LockMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ContainsKeyAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * Microsoft.ServiceFabric.Data.Collections.LockMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iReliableDictionary.ContainsKeyAsync (tx, key, lockMode, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="lockMode" Type="Microsoft.ServiceFabric.Data.Collections.LockMode" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="tx"><span data-ttu-id="6a08a-303">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="6a08a-303">Transaction to associate this operation with.</span></span></param>
        <param name="key"><span data-ttu-id="6a08a-304">信頼性の高いディクショナリ内で検索するキー。</span><span class="sxs-lookup"><span data-stu-id="6a08a-304">The key to locate in the Reliable Dictionary.</span></span></param>
        <param name="lockMode"><span data-ttu-id="6a08a-305">この読み取り操作に使用するロックの種類です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-305">Type of locking to use for this read operation.</span></span></param>
        <param name="timeout"><span data-ttu-id="6a08a-306">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。</span><span class="sxs-lookup"><span data-stu-id="6a08a-306">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="6a08a-307">主にデッドロックを防ぐために使用します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-307">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="6a08a-308">既定では 4 秒です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-308">The default is 4 seconds.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="6a08a-309">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="6a08a-309">The token to monitor for cancellation requests.</span></span> <span data-ttu-id="6a08a-310">既定値は None です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-310">The default is None.</span></span></param>
        <summary>
            <span data-ttu-id="6a08a-311">信頼性の高いディクショナリに指定したキーが含まれているかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-311">Determines whether the Reliable Dictionary contains the specified key.</span></span>
            </summary>
        <returns><span data-ttu-id="6a08a-312">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="6a08a-312">A task that represents the asynchronous operation.</span></span> <span data-ttu-id="6a08a-313">タスクの結果は、キーが存在するかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-313">The task result indicates whether the key exists.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="6a08a-314"><paramref name="tx" />null、または<paramref name="key" />が null またはシリアル化することはできません。</span><span class="sxs-lookup"><span data-stu-id="6a08a-314"><paramref name="tx" /> is null, or <paramref name="key" /> is null or cannot be serialized.</span></span></exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="6a08a-315"><paramref name="timeout" /> が負の値です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-315"><paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="6a08a-316">操作は、指定したタイムアウト時間内に完了できませんでした。</span><span class="sxs-lookup"><span data-stu-id="6a08a-316">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="6a08a-317">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-317">The operation was canceled.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            <span data-ttu-id="6a08a-318">IReliableDictionary が現時点での読み取りを使用できないことを示します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-318">Indicates that the IReliableDictionary cannot serve reads at the moment.</span></span>
            <span data-ttu-id="6a08a-319">すべてのページでこの例外はスローされる<see cref="T:System.Fabric.ReplicaRole" />s。</span><span class="sxs-lookup"><span data-stu-id="6a08a-319">This exception can be thrown in all <see cref="T:System.Fabric.ReplicaRole" />s.</span></span>
            <span data-ttu-id="6a08a-320">1 つの理由でスローされる可能性が、<see cref="F:System.Fabric.ReplicaRole.Primary" />ロールが失われる<see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-320">One reason it may be thrown in the <see cref="F:System.Fabric.ReplicaRole.Primary" /> role is loss of <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span></span>
            <span data-ttu-id="6a08a-321">1 つの理由でスローされる可能性が、<see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />ロールは、信頼性の高いコレクションの状態があるまだ一貫性のあります。</span><span class="sxs-lookup"><span data-stu-id="6a08a-321">One reason it may be thrown in the <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> role is that Reliable Collection's state is not yet consistent.</span></span>
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="6a08a-322">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-322">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="6a08a-323">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="6a08a-323">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="6a08a-324">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6a08a-324">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="6a08a-325">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-325">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="6a08a-326">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="6a08a-326">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="6a08a-327">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-327">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CreateEnumerableAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;&gt;&gt; CreateEnumerableAsync (Microsoft.ServiceFabric.Data.ITransaction txn);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Data.IAsyncEnumerable`1&lt;valuetype System.Collections.Generic.KeyValuePair`2&lt;!TKey, !TValue&gt;&gt;&gt; CreateEnumerableAsync(class Microsoft.ServiceFabric.Data.ITransaction txn) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.CreateEnumerableAsync(Microsoft.ServiceFabric.Data.ITransaction)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateEnumerableAsync (txn As ITransaction) As Task(Of IAsyncEnumerable(Of KeyValuePair(Of TKey, TValue)))" />
      <MemberSignature Language="F#" Value="abstract member CreateEnumerableAsync : Microsoft.ServiceFabric.Data.ITransaction -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;System.Collections.Generic.KeyValuePair&lt;'Key, 'Value&gt;&gt;&gt;" Usage="iReliableDictionary.CreateEnumerableAsync txn" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="txn" Type="Microsoft.ServiceFabric.Data.ITransaction" />
      </Parameters>
      <Docs>
        <param name="txn"><span data-ttu-id="6a08a-328">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="6a08a-328">The transaction to associate this operation with.</span></span></param>
        <summary>
            <span data-ttu-id="6a08a-329">非同期の列挙子を作成、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-329">Creates an asynchronous enumerator over the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />.</span></span>
            </summary>
        <returns>
          <para><span data-ttu-id="6a08a-330">表す非同期のタスクは、列挙可能な操作を作成します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-330">A task that represents the asynchronous create enumerable operation.</span></span> <span data-ttu-id="6a08a-331">タスクの結果は、信頼性の高い辞書の列挙子です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-331">The task result is an enumerator for the Reliable Dictionary.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="6a08a-332">返された列挙子は、安全に読み取りと同時に使用し、信頼性の高いディクショナリに書き込みます。</span><span class="sxs-lookup"><span data-stu-id="6a08a-332">The returned enumerator is safe to use concurrently with reads and writes to the Reliable Dictionary.</span></span>
            <span data-ttu-id="6a08a-333">スナップショットの一貫したビューを表します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-333">It represents a snapshot consistent view.</span></span> <span data-ttu-id="6a08a-334">なお、<see cref="M:Microsoft.ServiceFabric.Data.IAsyncEnumerable`1.GetAsyncEnumerator" />を列挙するために、返された IAsyncEnumerable に呼び出される必要があります。</span><span class="sxs-lookup"><span data-stu-id="6a08a-334">Please note that <see cref="M:Microsoft.ServiceFabric.Data.IAsyncEnumerable`1.GetAsyncEnumerator" /> needs to be called on the returned IAsyncEnumerable in order to enumerate.</span></span> <span data-ttu-id="6a08a-335">使用例がわかるように<see href="https://github.com/Azure-Samples/service-fabric-dotnet-web-reference-app/blob/master/ReferenceApp/Inventory.Service/InventoryService.cs">ここ</see>です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-335">Example usage can be seen <see href="https://github.com/Azure-Samples/service-fabric-dotnet-web-reference-app/blob/master/ReferenceApp/Inventory.Service/InventoryService.cs">here</see>.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            <span data-ttu-id="6a08a-336">IReliableDictionary が現時点での読み取りを使用できないことを示します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-336">Indicates that the IReliableDictionary cannot serve reads at the moment.</span></span>
            <span data-ttu-id="6a08a-337">すべてのページでこの例外はスローされる<see cref="T:System.Fabric.ReplicaRole" />s。</span><span class="sxs-lookup"><span data-stu-id="6a08a-337">This exception can be thrown in all <see cref="T:System.Fabric.ReplicaRole" />s.</span></span>
            <span data-ttu-id="6a08a-338">1 つの理由でスローされる可能性が、<see cref="F:System.Fabric.ReplicaRole.Primary" />ロールが失われる<see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-338">One reason it may be thrown in the <see cref="F:System.Fabric.ReplicaRole.Primary" /> role is loss of <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span></span>
            <span data-ttu-id="6a08a-339">1 つの理由でスローされる可能性が、<see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />ロールは、信頼性の高いコレクションの状態があるまだ一貫性のあります。</span><span class="sxs-lookup"><span data-stu-id="6a08a-339">One reason it may be thrown in the <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> role is that Reliable Collection's state is not yet consistent.</span></span>
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="6a08a-340">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-340">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="6a08a-341">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="6a08a-341">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="6a08a-342">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6a08a-342">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="6a08a-343">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-343">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="6a08a-344">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="6a08a-344">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="6a08a-345">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-345">Indicates that the Reliable Dictionary is closed or deleted.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateEnumerableAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;&gt;&gt; CreateEnumerableAsync (Microsoft.ServiceFabric.Data.ITransaction txn, Microsoft.ServiceFabric.Data.Collections.EnumerationMode enumerationMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Data.IAsyncEnumerable`1&lt;valuetype System.Collections.Generic.KeyValuePair`2&lt;!TKey, !TValue&gt;&gt;&gt; CreateEnumerableAsync(class Microsoft.ServiceFabric.Data.ITransaction txn, valuetype Microsoft.ServiceFabric.Data.Collections.EnumerationMode enumerationMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.CreateEnumerableAsync(Microsoft.ServiceFabric.Data.ITransaction,Microsoft.ServiceFabric.Data.Collections.EnumerationMode)" />
      <MemberSignature Language="F#" Value="abstract member CreateEnumerableAsync : Microsoft.ServiceFabric.Data.ITransaction * Microsoft.ServiceFabric.Data.Collections.EnumerationMode -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;System.Collections.Generic.KeyValuePair&lt;'Key, 'Value&gt;&gt;&gt;" Usage="iReliableDictionary.CreateEnumerableAsync (txn, enumerationMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="txn" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="enumerationMode" Type="Microsoft.ServiceFabric.Data.Collections.EnumerationMode" />
      </Parameters>
      <Docs>
        <param name="txn"><span data-ttu-id="6a08a-346">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="6a08a-346">The transaction to associate this operation with.</span></span></param>
        <param name="enumerationMode"><span data-ttu-id="6a08a-347">使用する列挙モード。</span><span class="sxs-lookup"><span data-stu-id="6a08a-347">The enumeration mode to use.</span></span> <span data-ttu-id="6a08a-348">既定値は順序なしです。</span><span class="sxs-lookup"><span data-stu-id="6a08a-348">The default is Unordered.</span></span> <span data-ttu-id="6a08a-349">列挙体の順序付けは昇順のみです。</span><span class="sxs-lookup"><span data-stu-id="6a08a-349">Ordered enumeration is ascending only.</span></span> </param>
        <summary>
            <span data-ttu-id="6a08a-350">非同期の列挙子を作成、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-350">Creates an asynchronous enumerator over the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />.</span></span>
            </summary>
        <returns>
          <para><span data-ttu-id="6a08a-351">表す非同期のタスクは、列挙可能な操作を作成します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-351">A task that represents the asynchronous create enumerable operation.</span></span> <span data-ttu-id="6a08a-352">タスクの結果は、信頼性の高い辞書の列挙子です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-352">The task result is an enumerator for the Reliable Dictionary.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="6a08a-353">返された列挙子は、安全に読み取りと同時に使用し、信頼性の高いディクショナリに書き込みます。</span><span class="sxs-lookup"><span data-stu-id="6a08a-353">The returned enumerator is safe to use concurrently with reads and writes to the Reliable Dictionary.</span></span>
            <span data-ttu-id="6a08a-354">スナップショットの一貫したビューを表します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-354">It represents a snapshot consistent view.</span></span> <span data-ttu-id="6a08a-355">なお、<see cref="M:Microsoft.ServiceFabric.Data.IAsyncEnumerable`1.GetAsyncEnumerator" />を列挙するために、返された IAsyncEnumerable に呼び出される必要があります。</span><span class="sxs-lookup"><span data-stu-id="6a08a-355">Please note that <see cref="M:Microsoft.ServiceFabric.Data.IAsyncEnumerable`1.GetAsyncEnumerator" /> needs to be called on the returned IAsyncEnumerable in order to enumerate.</span></span> <span data-ttu-id="6a08a-356">使用例がわかるように<see href="https://github.com/Azure-Samples/service-fabric-dotnet-web-reference-app/blob/master/ReferenceApp/Inventory.Service/InventoryService.cs">ここ</see>です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-356">Example usage can be seen <see href="https://github.com/Azure-Samples/service-fabric-dotnet-web-reference-app/blob/master/ReferenceApp/Inventory.Service/InventoryService.cs">here</see>.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            <span data-ttu-id="6a08a-357">IReliableDictionary が現時点での読み取りを使用できないことを示します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-357">Indicates that the IReliableDictionary cannot serve reads at the moment.</span></span>
            <span data-ttu-id="6a08a-358">すべてのページでこの例外はスローされる<see cref="T:System.Fabric.ReplicaRole" />s。</span><span class="sxs-lookup"><span data-stu-id="6a08a-358">This exception can be thrown in all <see cref="T:System.Fabric.ReplicaRole" />s.</span></span>
            <span data-ttu-id="6a08a-359">1 つの理由でスローされる可能性が、<see cref="F:System.Fabric.ReplicaRole.Primary" />ロールが失われる<see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-359">One reason it may be thrown in the <see cref="F:System.Fabric.ReplicaRole.Primary" /> role is loss of <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span></span>
            <span data-ttu-id="6a08a-360">1 つの理由でスローされる可能性が、<see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />ロールは、信頼性の高いコレクションの状態があるまだ一貫性のあります。</span><span class="sxs-lookup"><span data-stu-id="6a08a-360">One reason it may be thrown in the <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> role is that Reliable Collection's state is not yet consistent.</span></span>
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="6a08a-361">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-361">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="6a08a-362">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="6a08a-362">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="6a08a-363">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6a08a-363">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="6a08a-364">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-364">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="6a08a-365">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="6a08a-365">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="6a08a-366">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-366">Indicates that the Reliable Dictionary is closed or deleted.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateEnumerableAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;&gt;&gt; CreateEnumerableAsync (Microsoft.ServiceFabric.Data.ITransaction txn, Func&lt;TKey,bool&gt; filter, Microsoft.ServiceFabric.Data.Collections.EnumerationMode enumerationMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Data.IAsyncEnumerable`1&lt;valuetype System.Collections.Generic.KeyValuePair`2&lt;!TKey, !TValue&gt;&gt;&gt; CreateEnumerableAsync(class Microsoft.ServiceFabric.Data.ITransaction txn, class System.Func`2&lt;!TKey, bool&gt; filter, valuetype Microsoft.ServiceFabric.Data.Collections.EnumerationMode enumerationMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.CreateEnumerableAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Func{`0,System.Boolean},Microsoft.ServiceFabric.Data.Collections.EnumerationMode)" />
      <MemberSignature Language="F#" Value="abstract member CreateEnumerableAsync : Microsoft.ServiceFabric.Data.ITransaction * Func&lt;'Key, bool (requires 'Key :&gt; IComparable&lt;'Key&gt; and 'Key :&gt; IEquatable&lt;'Key&gt;)&gt; * Microsoft.ServiceFabric.Data.Collections.EnumerationMode -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;System.Collections.Generic.KeyValuePair&lt;'Key, 'Value&gt;&gt;&gt;" Usage="iReliableDictionary.CreateEnumerableAsync (txn, filter, enumerationMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="txn" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="filter" Type="System.Func&lt;TKey,System.Boolean&gt;" />
        <Parameter Name="enumerationMode" Type="Microsoft.ServiceFabric.Data.Collections.EnumerationMode" />
      </Parameters>
      <Docs>
        <param name="txn"><span data-ttu-id="6a08a-367">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="6a08a-367">The transaction to associate this operation with.</span></span></param>
        <param name="filter"><span data-ttu-id="6a08a-368">キーに基づく列挙型に含めるキーと値のペアをフィルター処理する述語。</span><span class="sxs-lookup"><span data-stu-id="6a08a-368">Predicate that filters the key-value pairs to include in the enumeration based on the key.</span></span></param>
        <param name="enumerationMode"><span data-ttu-id="6a08a-369">使用する列挙モード。</span><span class="sxs-lookup"><span data-stu-id="6a08a-369">The enumeration mode to use.</span></span> <span data-ttu-id="6a08a-370">既定値は順序なしです。</span><span class="sxs-lookup"><span data-stu-id="6a08a-370">The default is Unordered.</span></span> <span data-ttu-id="6a08a-371">列挙体の順序付けは昇順のみです。</span><span class="sxs-lookup"><span data-stu-id="6a08a-371">Ordered enumeration is ascending only.</span></span></param>
        <summary>
            <span data-ttu-id="6a08a-372">非同期の列挙子を作成、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-372">Creates an asynchronous enumerator over the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />.</span></span>
            </summary>
        <returns>
          <para><span data-ttu-id="6a08a-373">表す非同期のタスクは、列挙可能な操作を作成します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-373">A task that represents the asynchronous create enumerable operation.</span></span> <span data-ttu-id="6a08a-374">タスクの結果は、信頼性の高い辞書の列挙子です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-374">The task result is an enumerator for the Reliable Dictionary.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="6a08a-375">返された列挙子は、安全に読み取りと同時に使用し、信頼性の高いディクショナリに書き込みます。</span><span class="sxs-lookup"><span data-stu-id="6a08a-375">The returned enumerator is safe to use concurrently with reads and writes to the Reliable Dictionary.</span></span>
            <span data-ttu-id="6a08a-376">スナップショットの一貫したビューを表します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-376">It represents a snapshot consistent view.</span></span> <span data-ttu-id="6a08a-377">なお、<see cref="M:Microsoft.ServiceFabric.Data.IAsyncEnumerable`1.GetAsyncEnumerator" />を列挙するために、返された IAsyncEnumerable に呼び出される必要があります。</span><span class="sxs-lookup"><span data-stu-id="6a08a-377">Please note that <see cref="M:Microsoft.ServiceFabric.Data.IAsyncEnumerable`1.GetAsyncEnumerator" /> needs to be called on the returned IAsyncEnumerable in order to enumerate.</span></span> <span data-ttu-id="6a08a-378">使用例がわかるように<see href="https://github.com/Azure-Samples/service-fabric-dotnet-web-reference-app/blob/master/ReferenceApp/Inventory.Service/InventoryService.cs">ここ</see>です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-378">Example usage can be seen <see href="https://github.com/Azure-Samples/service-fabric-dotnet-web-reference-app/blob/master/ReferenceApp/Inventory.Service/InventoryService.cs">here</see>.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            <span data-ttu-id="6a08a-379">IReliableDictionary が現時点での読み取りを使用できないことを示します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-379">Indicates that the IReliableDictionary cannot serve reads at the moment.</span></span>
            <span data-ttu-id="6a08a-380">すべてのページでこの例外はスローされる<see cref="T:System.Fabric.ReplicaRole" />s。</span><span class="sxs-lookup"><span data-stu-id="6a08a-380">This exception can be thrown in all <see cref="T:System.Fabric.ReplicaRole" />s.</span></span>
            <span data-ttu-id="6a08a-381">1 つの理由でスローされる可能性が、<see cref="F:System.Fabric.ReplicaRole.Primary" />ロールが失われる<see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-381">One reason it may be thrown in the <see cref="F:System.Fabric.ReplicaRole.Primary" /> role is loss of <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span></span>
            <span data-ttu-id="6a08a-382">1 つの理由でスローされる可能性が、<see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />ロールは、信頼性の高いコレクションの状態があるまだ一貫性のあります。</span><span class="sxs-lookup"><span data-stu-id="6a08a-382">One reason it may be thrown in the <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> role is that Reliable Collection's state is not yet consistent.</span></span>
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="6a08a-383">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-383">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="6a08a-384">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="6a08a-384">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="6a08a-385">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6a08a-385">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="6a08a-386">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-386">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="6a08a-387">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="6a08a-387">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="6a08a-388">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-388">Indicates that the Reliable Dictionary is closed or deleted.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="DictionaryChanged">
      <MemberSignature Language="C#" Value="event EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs&lt;TKey,TValue&gt;&gt; DictionaryChanged;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs`2&lt;!TKey, !TValue&gt;&gt; DictionaryChanged" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.DictionaryChanged" />
      <MemberSignature Language="VB.NET" Value="Event DictionaryChanged As EventHandler(Of NotifyDictionaryChangedEventArgs(Of TKey, TValue)) " />
      <MemberSignature Language="F#" Value="member this.DictionaryChanged : EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs&lt;'Key, 'Value&gt;&gt; " Usage="member this.DictionaryChanged : System.EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs&lt;'Key, 'Value&gt;&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs&lt;TKey,TValue&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6a08a-389">信頼性の高いディクショナリが変更されたときに発生します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-389">Occurs when the Reliable Dictionary changes.</span></span>
            <span data-ttu-id="6a08a-390">たとえば、更新プログラムの追加または削除の項目。</span><span class="sxs-lookup"><span data-stu-id="6a08a-390">For example, addition, update or removal of an item.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOrAddAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;TValue&gt; GetOrAddAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, Func&lt;TKey,TValue&gt; valueFactory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TValue&gt; GetOrAddAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, class System.Func`2&lt;!TKey, !TValue&gt; valueFactory) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.GetOrAddAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.Func{`0,`1})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetOrAddAsync (tx As ITransaction, key As TKey, valueFactory As Func(Of TKey, TValue)) As Task(Of TValue)" />
      <MemberSignature Language="F#" Value="abstract member GetOrAddAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * Func&lt;'Key, 'Value (requires 'Key :&gt; IComparable&lt;'Key&gt; and 'Key :&gt; IEquatable&lt;'Key&gt;)&gt; -&gt; System.Threading.Tasks.Task&lt;'Value&gt;" Usage="iReliableDictionary.GetOrAddAsync (tx, key, valueFactory)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TValue&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="valueFactory" Type="System.Func&lt;TKey,TValue&gt;" />
      </Parameters>
      <Docs>
        <param name="tx"><span data-ttu-id="6a08a-391">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="6a08a-391">Transaction to associate this operation with.</span></span></param>
        <param name="key"><span data-ttu-id="6a08a-392">追加する要素のキー。</span><span class="sxs-lookup"><span data-stu-id="6a08a-392">The key of the element to add.</span></span></param>
        <param name="valueFactory"><span data-ttu-id="6a08a-393">キーの値を生成するために使用される関数。</span><span class="sxs-lookup"><span data-stu-id="6a08a-393">The function used to generate a value for the key.</span></span></param>
        <summary>
            <span data-ttu-id="6a08a-394">キーが既に存在しない場合に指定された関数を使用して、信頼性の高い辞書にキー/値ペアを追加します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-394">Adds a key/value pair to the Reliable Dictionary by using the specified function, if the key does not already exist.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="6a08a-395">表す非同期のタスクは、操作を追加します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-395">A task that represents the asynchronous add operation.</span></span> <span data-ttu-id="6a08a-396">タスクの結果は、キーの値です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-396">The task result is the value for the key.</span></span> <span data-ttu-id="6a08a-397">これは、キーが、信頼性の高いディクショナリに既に場合は、キーの既存の値またはキーが信頼性の高いディクショナリ内でない場合は valueFactory から返されたキーの新しい値のいずれかになります。</span><span class="sxs-lookup"><span data-stu-id="6a08a-397">This will be either the existing value for the key if the key is already in the Reliable Dictionary, or the new value for the key as returned by valueFactory if the key was not in the Reliable Dictionary.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="6a08a-398"><paramref name="tx" />null、または<paramref name="key" />が null またはシリアル化できませんまたは<paramref name="valueFactory" />が null です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-398"><paramref name="tx" /> is null, or <paramref name="key" /> is null or cannot be serialized, or <paramref name="valueFactory" /> is null.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="6a08a-399">既定のタイムアウト以内に完了する操作が失敗しました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-399">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="6a08a-400">ときにスローされる例外、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-400">The exception that is thrown when the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="6a08a-401">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-401">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="6a08a-402">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="6a08a-402">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="6a08a-403">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6a08a-403">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="6a08a-404">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-404">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="6a08a-405">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="6a08a-405">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="6a08a-406">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-406">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetOrAddAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;TValue&gt; GetOrAddAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, TValue value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TValue&gt; GetOrAddAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, !TValue value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.GetOrAddAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,`1)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetOrAddAsync (tx As ITransaction, key As TKey, value As TValue) As Task(Of TValue)" />
      <MemberSignature Language="F#" Value="abstract member GetOrAddAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * 'Value -&gt; System.Threading.Tasks.Task&lt;'Value&gt;" Usage="iReliableDictionary.GetOrAddAsync (tx, key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TValue&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="value" Type="TValue" />
      </Parameters>
      <Docs>
        <param name="tx"><span data-ttu-id="6a08a-407">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="6a08a-407">Transaction to associate this operation with.</span></span></param>
        <param name="key"><span data-ttu-id="6a08a-408">追加する要素のキー。</span><span class="sxs-lookup"><span data-stu-id="6a08a-408">The key of the element to add.</span></span></param>
        <param name="value"><span data-ttu-id="6a08a-409">キーがまだ存在しない場合に追加する値。</span><span class="sxs-lookup"><span data-stu-id="6a08a-409">The value to be added, if the key does not already exist.</span></span></param>
        <summary>
            <span data-ttu-id="6a08a-410">キーが既に存在しない場合は、信頼性の高い辞書にキー/値ペアを追加します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-410">Adds a key/value pair to the Reliable Dictionary if the key does not already exist.</span></span>
            <span data-ttu-id="6a08a-411">キーが存在する場合は、値に更新プログラムは作成されません。</span><span class="sxs-lookup"><span data-stu-id="6a08a-411">If the key exists no updates will be made to the value.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="6a08a-412">表す非同期のタスクは、操作を追加します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-412">A task that represents the asynchronous add operation.</span></span> <span data-ttu-id="6a08a-413">タスクの結果は、キーの値です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-413">The task result is the value for the key.</span></span> <span data-ttu-id="6a08a-414">これは、場合は、キーが、信頼性の高いディクショナリに既にキーの既存の値または新しい値のいずれか場合なりますキーは、信頼性の高いディクショナリではありませんでした。</span><span class="sxs-lookup"><span data-stu-id="6a08a-414">This will be either the existing value for the key if the key is already in the Reliable Dictionary, or the new value if the key was not in the Reliable Dictionary.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="6a08a-415"><paramref name="tx" />null、または<paramref name="key" />が null またはシリアル化することはできません。</span><span class="sxs-lookup"><span data-stu-id="6a08a-415"><paramref name="tx" /> is null, or <paramref name="key" /> is null or cannot be serialized.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="6a08a-416">既定のタイムアウト以内に完了する操作が失敗しました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-416">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="6a08a-417">ときにスローされる例外、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-417">The exception that is thrown when the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="6a08a-418">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-418">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="6a08a-419">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="6a08a-419">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="6a08a-420">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6a08a-420">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="6a08a-421">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-421">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="6a08a-422">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="6a08a-422">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="6a08a-423">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-423">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetOrAddAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;TValue&gt; GetOrAddAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, Func&lt;TKey,TValue&gt; valueFactory, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TValue&gt; GetOrAddAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, class System.Func`2&lt;!TKey, !TValue&gt; valueFactory, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.GetOrAddAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.Func{`0,`1},System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetOrAddAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * Func&lt;'Key, 'Value (requires 'Key :&gt; IComparable&lt;'Key&gt; and 'Key :&gt; IEquatable&lt;'Key&gt;)&gt; * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'Value&gt;" Usage="iReliableDictionary.GetOrAddAsync (tx, key, valueFactory, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TValue&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="valueFactory" Type="System.Func&lt;TKey,TValue&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="tx"><span data-ttu-id="6a08a-424">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="6a08a-424">Transaction to associate this operation with.</span></span></param>
        <param name="key"><span data-ttu-id="6a08a-425">追加する要素のキー。</span><span class="sxs-lookup"><span data-stu-id="6a08a-425">The key of the element to add.</span></span></param>
        <param name="valueFactory"><span data-ttu-id="6a08a-426">キーの値を生成するために使用される関数。</span><span class="sxs-lookup"><span data-stu-id="6a08a-426">The function used to generate a value for the key.</span></span></param>
        <param name="timeout"><span data-ttu-id="6a08a-427">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。</span><span class="sxs-lookup"><span data-stu-id="6a08a-427">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="6a08a-428">主にデッドロックを防ぐために使用します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-428">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="6a08a-429">既定では 4 秒です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-429">The default is 4 seconds.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="6a08a-430">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="6a08a-430">The token to monitor for cancellation requests.</span></span> <span data-ttu-id="6a08a-431">既定値は None です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-431">The default is None.</span></span></param>
        <summary>
            <span data-ttu-id="6a08a-432">キーが既に存在しない場合に指定された関数を使用して、信頼性の高い辞書にキー/値ペアを追加します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-432">Adds a key/value pair to the Reliable Dictionary by using the specified function, if the key does not already exist.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="6a08a-433">表す非同期のタスクは、操作を追加します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-433">A task that represents the asynchronous add operation.</span></span> <span data-ttu-id="6a08a-434">タスクの結果は、キーの値です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-434">The task result is the value for the key.</span></span> <span data-ttu-id="6a08a-435">これは、キーが、信頼性の高いディクショナリに既に場合は、キーの既存の値またはキーが信頼性の高いディクショナリ内でない場合は valueFactory から返されたキーの新しい値のいずれかになります。</span><span class="sxs-lookup"><span data-stu-id="6a08a-435">This will be either the existing value for the key if the key is already in the Reliable Dictionary, or the new value for the key as returned by valueFactory if the key was not in the Reliable Dictionary.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="6a08a-436"><paramref name="tx" />null、または<paramref name="key" />が null またはシリアル化できませんまたは<paramref name="valueFactory" />が null です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-436"><paramref name="tx" /> is null, or <paramref name="key" /> is null or cannot be serialized, or <paramref name="valueFactory" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="6a08a-437"><paramref name="timeout" /> が負の値です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-437"><paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="6a08a-438">操作は、指定したタイムアウト時間内に完了できませんでした。</span><span class="sxs-lookup"><span data-stu-id="6a08a-438">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="6a08a-439">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-439">The operation was canceled.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="6a08a-440">ときにスローされる例外、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-440">The exception that is thrown when the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="6a08a-441">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-441">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="6a08a-442">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="6a08a-442">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="6a08a-443">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6a08a-443">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="6a08a-444">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-444">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="6a08a-445">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="6a08a-445">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="6a08a-446">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-446">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetOrAddAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;TValue&gt; GetOrAddAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, TValue value, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TValue&gt; GetOrAddAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, !TValue value, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.GetOrAddAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,`1,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetOrAddAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * 'Value * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'Value&gt;" Usage="iReliableDictionary.GetOrAddAsync (tx, key, value, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TValue&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="value" Type="TValue" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="tx"><span data-ttu-id="6a08a-447">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="6a08a-447">Transaction to associate this operation with.</span></span></param>
        <param name="key"><span data-ttu-id="6a08a-448">追加する要素のキー。</span><span class="sxs-lookup"><span data-stu-id="6a08a-448">The key of the element to add.</span></span></param>
        <param name="value"><span data-ttu-id="6a08a-449">キーがまだ存在しない場合に追加する値。</span><span class="sxs-lookup"><span data-stu-id="6a08a-449">The value to be added, if the key does not already exist.</span></span></param>
        <param name="timeout"><span data-ttu-id="6a08a-450">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。</span><span class="sxs-lookup"><span data-stu-id="6a08a-450">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="6a08a-451">主にデッドロックを防ぐために使用します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-451">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="6a08a-452">既定では 4 秒です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-452">The default is 4 seconds.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="6a08a-453">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="6a08a-453">The token to monitor for cancellation requests.</span></span> <span data-ttu-id="6a08a-454">既定値は None です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-454">The default is None.</span></span></param>
        <summary>
            <span data-ttu-id="6a08a-455">キーが既に存在しない場合は、信頼性の高い辞書にキー/値ペアを追加します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-455">Adds a key/value pair to the Reliable Dictionary if the key does not already exist.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="6a08a-456">表す非同期のタスクは、操作を追加します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-456">A task that represents the asynchronous add operation.</span></span> <span data-ttu-id="6a08a-457">タスクの結果は、キーの値です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-457">The task result is the value for the key.</span></span> <span data-ttu-id="6a08a-458">これは、場合は、キーが、信頼性の高いディクショナリに既にキーの既存の値または新しい値のいずれか場合なりますキーは、信頼性の高いディクショナリではありませんでした。</span><span class="sxs-lookup"><span data-stu-id="6a08a-458">This will be either the existing value for the key if the key is already in the Reliable Dictionary, or the new value if the key was not in the Reliable Dictionary.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="6a08a-459"><paramref name="tx" />null、または<paramref name="key" />が null またはシリアル化することはできません。</span><span class="sxs-lookup"><span data-stu-id="6a08a-459"><paramref name="tx" /> is null, or <paramref name="key" /> is null or cannot be serialized.</span></span></exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="6a08a-460"><paramref name="timeout" /> が負の値です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-460"><paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="6a08a-461">操作は、指定したタイムアウト時間内に完了できませんでした。</span><span class="sxs-lookup"><span data-stu-id="6a08a-461">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="6a08a-462">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-462">The operation was canceled.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="6a08a-463">ときにスローされる例外、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-463">The exception that is thrown when the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="6a08a-464">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-464">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="6a08a-465">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="6a08a-465">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="6a08a-466">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6a08a-466">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="6a08a-467">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-467">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="6a08a-468">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="6a08a-468">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="6a08a-469">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-469">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RebuildNotificationAsyncCallback">
      <MemberSignature Language="C#" Value="public Func&lt;Microsoft.ServiceFabric.Data.Collections.IReliableDictionary&lt;TKey,TValue&gt;,Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryRebuildEventArgs&lt;TKey,TValue&gt;,System.Threading.Tasks.Task&gt; RebuildNotificationAsyncCallback { set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`3&lt;class Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2&lt;!TKey, !TValue&gt;, class Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryRebuildEventArgs`2&lt;!TKey, !TValue&gt;, class System.Threading.Tasks.Task&gt; RebuildNotificationAsyncCallback" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.RebuildNotificationAsyncCallback" />
      <MemberSignature Language="VB.NET" Value="Public Property RebuildNotificationAsyncCallback As Func(Of IReliableDictionary(Of TKey, TValue), NotifyDictionaryRebuildEventArgs(Of TKey, TValue), Task)" />
      <MemberSignature Language="F#" Value="member this.RebuildNotificationAsyncCallback : Func&lt;Microsoft.ServiceFabric.Data.Collections.IReliableDictionary&lt;'Key, 'Value&gt;, Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryRebuildEventArgs&lt;'Key, 'Value&gt;, System.Threading.Tasks.Task&gt;" Usage="Microsoft.ServiceFabric.Data.Collections.IReliableDictionary&lt;'Key, 'Value (requires 'Key :&gt; System.IComparable&lt;'Key&gt; and 'Key :&gt; System.IEquatable&lt;'Key&gt;)&gt;.RebuildNotificationAsyncCallback" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;Microsoft.ServiceFabric.Data.Collections.IReliableDictionary&lt;TKey,TValue&gt;,Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryRebuildEventArgs&lt;TKey,TValue&gt;,System.Threading.Tasks.Task&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6a08a-470">信頼性の高いディクショナリがコピー、復元または復旧中に再構築されるときに呼び出される関数。</span><span class="sxs-lookup"><span data-stu-id="6a08a-470">A function that is called when the Reliable Dictionary is being rebuilt during copy, restore or recovery.</span></span>
            </summary>
        <value>
            <span data-ttu-id="6a08a-471">非同期の再構築の通知関数。</span><span class="sxs-lookup"><span data-stu-id="6a08a-471">The asynchronous rebuild notification function.</span></span> <span data-ttu-id="6a08a-472">関数は、IReliableDictionary and NotifyDictionaryRebuildEventArgs トークン内の取得しを再構築の通知の非同期処理を表すタスクを返します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-472">Function takes in IReliableDictionary and NotifyDictionaryRebuildEventArgs token and returns a Task that represents the asynchronous processing of the rebuild notification.</span></span>
            </value>
        <remarks>
          <span data-ttu-id="6a08a-473"><see cref="T:Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs`2" />このコールバック内でのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="6a08a-473"><see cref="T:Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs`2" /> can only be used within this callback.</span></span>
            <span data-ttu-id="6a08a-474">非同期のコールバックが完了すると、<see cref="T:Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryRebuildEventArgs`2" />は無効になります。</span><span class="sxs-lookup"><span data-stu-id="6a08a-474">Once the asynchronous callback completes, the <see cref="T:Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryRebuildEventArgs`2" /> becomes invalid.</span></span> <span data-ttu-id="6a08a-475">詳細については、<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-notifications">ここを</see>を参照してください。</span><span class="sxs-lookup"><span data-stu-id="6a08a-475">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-notifications">here</see> for more information.</span></span> 
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SetAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, TValue value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, !TValue value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.SetAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,`1)" />
      <MemberSignature Language="VB.NET" Value="Public Function SetAsync (tx As ITransaction, key As TKey, value As TValue) As Task" />
      <MemberSignature Language="F#" Value="abstract member SetAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * 'Value -&gt; System.Threading.Tasks.Task" Usage="iReliableDictionary.SetAsync (tx, key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="value" Type="TValue" />
      </Parameters>
      <Docs>
        <param name="tx"><span data-ttu-id="6a08a-476">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="6a08a-476">Transaction to associate this operation with.</span></span></param>
        <param name="key"><span data-ttu-id="6a08a-477">キー値を更新する必要があります。</span><span class="sxs-lookup"><span data-stu-id="6a08a-477">The key whose value should be updated.</span></span></param>
        <param name="value"><span data-ttu-id="6a08a-478">指定した要素の値を置き換える値<paramref name="key" />です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-478">The value that replaces the value of the element that has the specified <paramref name="key" />.</span></span></param>
        <summary>
            <span data-ttu-id="6a08a-479">キーが既に存在しない場合、キーが既に存在する場合は、信頼性の高いディクショナリのキー/値ペアを更新、信頼性の高い辞書にキー/値ペアを追加します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-479">Adds a key/value pair to the Reliable Dictionary if the key does not already exist, or updates a key/value pair in the Reliable Dictionary if the key already exists.</span></span>
            </summary>
        <returns><span data-ttu-id="6a08a-480">非同期更新操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="6a08a-480">A task that represents the asynchronous update operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="6a08a-481"><paramref name="tx" />null、または<paramref name="key" />が null またはシリアル化することはできません。</span><span class="sxs-lookup"><span data-stu-id="6a08a-481"><paramref name="tx" /> is null, or <paramref name="key" /> is null or cannot be serialized.</span></span></exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="6a08a-482"><paramref name="key" />信頼性の高いディクショナリではありません。</span><span class="sxs-lookup"><span data-stu-id="6a08a-482"><paramref name="key" /> does not exist in the Reliable Dictionary.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="6a08a-483">既定のタイムアウト以内に完了する操作が失敗しました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-483">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="6a08a-484">ときにスローされる例外、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-484">The exception that is thrown when the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="6a08a-485">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-485">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="6a08a-486">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="6a08a-486">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="6a08a-487">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6a08a-487">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="6a08a-488">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-488">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="6a08a-489">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="6a08a-489">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="6a08a-490">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-490">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="SetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SetAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, TValue value, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, !TValue value, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.SetAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,`1,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * 'Value * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iReliableDictionary.SetAsync (tx, key, value, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="value" Type="TValue" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="tx"><span data-ttu-id="6a08a-491">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="6a08a-491">Transaction to associate this operation with.</span></span></param>
        <param name="key"><span data-ttu-id="6a08a-492">キー値を更新する必要があります。</span><span class="sxs-lookup"><span data-stu-id="6a08a-492">The key whose value should be updated.</span></span></param>
        <param name="value"><span data-ttu-id="6a08a-493">指定した要素の値を置き換える値<paramref name="key" />です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-493">The value that replaces the value of the element that has the specified <paramref name="key" />.</span></span></param>
        <param name="timeout"><span data-ttu-id="6a08a-494">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。</span><span class="sxs-lookup"><span data-stu-id="6a08a-494">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="6a08a-495">主にデッドロックを防ぐために使用します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-495">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="6a08a-496">既定では 4 秒です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-496">The default is 4 seconds.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="6a08a-497">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="6a08a-497">The token to monitor for cancellation requests.</span></span> <span data-ttu-id="6a08a-498">既定値は None です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-498">The default is None.</span></span></param>
        <summary>
            <span data-ttu-id="6a08a-499">キーが既に存在しない場合、キーが既に存在する場合は、信頼性の高いディクショナリのキー/値ペアを更新、信頼性の高い辞書にキー/値ペアを追加します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-499">Adds a key/value pair to the Reliable Dictionary if the key does not already exist, or updates a key/value pair in the Reliable Dictionary if the key already exists.</span></span>
            </summary>
        <returns><span data-ttu-id="6a08a-500">非同期更新操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="6a08a-500">A task that represents the asynchronous update operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="6a08a-501"><paramref name="tx" />null、または<paramref name="key" />が null またはシリアル化することはできません。</span><span class="sxs-lookup"><span data-stu-id="6a08a-501"><paramref name="tx" /> is null, or <paramref name="key" /> is null or cannot be serialized.</span></span></exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="6a08a-502"><paramref name="key" />ディクショナリに存在しない、信頼性の高い、または<paramref name="timeout" />が負の値。</span><span class="sxs-lookup"><span data-stu-id="6a08a-502"><paramref name="key" /> does not exist in the Reliable Dictionary, or <paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="6a08a-503">操作は、指定したタイムアウト時間内に完了できませんでした。</span><span class="sxs-lookup"><span data-stu-id="6a08a-503">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="6a08a-504">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-504">The operation was canceled.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="6a08a-505">ときにスローされる例外、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-505">The exception that is thrown when the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="6a08a-506">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-506">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="6a08a-507">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="6a08a-507">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="6a08a-508">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6a08a-508">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="6a08a-509">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-509">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="6a08a-510">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="6a08a-510">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="6a08a-511">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-511">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="TryAddAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; TryAddAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, TValue value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; TryAddAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, !TValue value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.TryAddAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,`1)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryAddAsync (tx As ITransaction, key As TKey, value As TValue) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member TryAddAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * 'Value -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iReliableDictionary.TryAddAsync (tx, key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="value" Type="TValue" />
      </Parameters>
      <Docs>
        <param name="tx"><span data-ttu-id="6a08a-512">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="6a08a-512">Transaction to associate this operation with.</span></span></param>
        <param name="key"><span data-ttu-id="6a08a-513">追加する要素のキー。</span><span class="sxs-lookup"><span data-stu-id="6a08a-513">The key of the element to add.</span></span></param>
        <param name="value"><span data-ttu-id="6a08a-514">追加する要素の値。</span><span class="sxs-lookup"><span data-stu-id="6a08a-514">The value of the element to add.</span></span> <span data-ttu-id="6a08a-515">参照型の場合は、値を null にできます。</span><span class="sxs-lookup"><span data-stu-id="6a08a-515">The value can be null for reference types.</span></span></param>
        <summary>
            <span data-ttu-id="6a08a-516">信頼性の高いディクショナリに、指定したキーと値を追加しようとしています。</span><span class="sxs-lookup"><span data-stu-id="6a08a-516">Attempts to add the specified key and value to the Reliable Dictionary.</span></span>
            </summary>
        <returns><span data-ttu-id="6a08a-517">表す非同期のタスクは、操作を追加します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-517">A task that represents the asynchronous add operation.</span></span> <span data-ttu-id="6a08a-518">タスクの結果は、キー/値ペアが追加されたかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-518">The task result indicates whether the key/value pair was added.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="6a08a-519"><paramref name="tx" />null、または<paramref name="key" />が null またはシリアル化することはできません。</span><span class="sxs-lookup"><span data-stu-id="6a08a-519"><paramref name="tx" /> is null, or <paramref name="key" /> is null or cannot be serialized.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="6a08a-520">既定のタイムアウト以内に完了する操作が失敗しました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-520">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="6a08a-521">ときにスローされる例外、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-521">The exception that is thrown when the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="6a08a-522">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-522">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="6a08a-523">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="6a08a-523">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="6a08a-524">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6a08a-524">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="6a08a-525">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-525">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="6a08a-526">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="6a08a-526">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="6a08a-527">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-527">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="TryAddAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; TryAddAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, TValue value, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; TryAddAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, !TValue value, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.TryAddAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,`1,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TryAddAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * 'Value * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iReliableDictionary.TryAddAsync (tx, key, value, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="value" Type="TValue" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="tx"><span data-ttu-id="6a08a-528">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="6a08a-528">Transaction to associate this operation with.</span></span></param>
        <param name="key"><span data-ttu-id="6a08a-529">追加する要素のキー。</span><span class="sxs-lookup"><span data-stu-id="6a08a-529">The key of the element to add.</span></span></param>
        <param name="value"><span data-ttu-id="6a08a-530">追加する要素の値。</span><span class="sxs-lookup"><span data-stu-id="6a08a-530">The value of the element to add.</span></span> <span data-ttu-id="6a08a-531">参照型の場合は、値を null にできます。</span><span class="sxs-lookup"><span data-stu-id="6a08a-531">The value can be null for reference types.</span></span></param>
        <param name="timeout"><span data-ttu-id="6a08a-532">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。</span><span class="sxs-lookup"><span data-stu-id="6a08a-532">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="6a08a-533">主にデッドロックを防ぐために使用します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-533">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="6a08a-534">既定では 4 秒です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-534">The default is 4 seconds.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="6a08a-535">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="6a08a-535">The token to monitor for cancellation requests.</span></span> <span data-ttu-id="6a08a-536">既定値は None です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-536">The default is None.</span></span></param>
        <summary>
            <span data-ttu-id="6a08a-537">信頼性の高いディクショナリに、指定したキーと値を追加しようとしています。</span><span class="sxs-lookup"><span data-stu-id="6a08a-537">Attempts to add the specified key and value to the Reliable Dictionary.</span></span>
            </summary>
        <returns><span data-ttu-id="6a08a-538">表す非同期のタスクは、操作を追加します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-538">A task that represents the asynchronous add operation.</span></span> <span data-ttu-id="6a08a-539">タスクの結果は、キー/値ペアが追加されたかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-539">The task result indicates whether the key/value pair was added.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="6a08a-540"><paramref name="tx" />null、または<paramref name="key" />が null またはシリアル化することはできません。</span><span class="sxs-lookup"><span data-stu-id="6a08a-540"><paramref name="tx" /> is null, or <paramref name="key" /> is null or cannot be serialized.</span></span></exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="6a08a-541"><paramref name="timeout" /> が負の値です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-541"><paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="6a08a-542">操作は、指定したタイムアウト時間内に完了できませんでした。</span><span class="sxs-lookup"><span data-stu-id="6a08a-542">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="6a08a-543">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-543">The operation was canceled.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="6a08a-544">ときにスローされる例外、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-544">The exception that is thrown when the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="6a08a-545">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-545">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="6a08a-546">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="6a08a-546">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="6a08a-547">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6a08a-547">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="6a08a-548">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-548">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="6a08a-549">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="6a08a-549">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="6a08a-550">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-550">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="TryGetValueAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;TValue&gt;&gt; TryGetValueAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!TValue&gt;&gt; TryGetValueAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.TryGetValueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryGetValueAsync (tx As ITransaction, key As TKey) As Task(Of ConditionalValue(Of TValue))" />
      <MemberSignature Language="F#" Value="abstract member TryGetValueAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;'Value&gt;&gt;" Usage="iReliableDictionary.TryGetValueAsync (tx, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;TValue&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
      </Parameters>
      <Docs>
        <param name="tx"><span data-ttu-id="6a08a-551">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="6a08a-551">Transaction to associate this operation with.</span></span></param>
        <param name="key"><span data-ttu-id="6a08a-552">取得する値のキー。</span><span class="sxs-lookup"><span data-stu-id="6a08a-552">The key of the value to get.</span></span></param>
        <summary>
            <span data-ttu-id="6a08a-553">信頼性の高いディクショナリから指定されたキーに関連付けられている値を取得しようとしています。</span><span class="sxs-lookup"><span data-stu-id="6a08a-553">Attempts to get the value associated with the specified key from the Reliable Dictionary.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="6a08a-554">非同期の読み取り操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="6a08a-554">A task that represents the asynchronous read operation.</span></span> <span data-ttu-id="6a08a-555">タスクの結果の組は、その場合は、信頼性の高いディクショナリのキーが見つかったかどうかを示す、値。</span><span class="sxs-lookup"><span data-stu-id="6a08a-555">The task result is a tuple indicating whether the key was found in the Reliable Dictionary and if so, the value.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="6a08a-556"><paramref name="tx" />null、または<paramref name="key" />が null またはシリアル化することはできません。</span><span class="sxs-lookup"><span data-stu-id="6a08a-556"><paramref name="tx" /> is null, or <paramref name="key" /> is null or cannot be serialized.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="6a08a-557">既定のタイムアウト以内に完了する操作が失敗しました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-557">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            <span data-ttu-id="6a08a-558">IReliableDictionary が現時点での読み取りを使用できないことを示します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-558">Indicates that the IReliableDictionary cannot serve reads at the moment.</span></span>
            <span data-ttu-id="6a08a-559">すべてのページでこの例外はスローされる<see cref="T:System.Fabric.ReplicaRole" />s。</span><span class="sxs-lookup"><span data-stu-id="6a08a-559">This exception can be thrown in all <see cref="T:System.Fabric.ReplicaRole" />s.</span></span>
            <span data-ttu-id="6a08a-560">1 つの理由でスローされる可能性が、<see cref="F:System.Fabric.ReplicaRole.Primary" />ロールが失われる<see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-560">One reason it may be thrown in the <see cref="F:System.Fabric.ReplicaRole.Primary" /> role is loss of <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span></span>
            <span data-ttu-id="6a08a-561">1 つの理由でスローされる可能性が、<see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />ロールは、信頼性の高いコレクションの状態があるまだ一貫性のあります。</span><span class="sxs-lookup"><span data-stu-id="6a08a-561">One reason it may be thrown in the <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> role is that Reliable Collection's state is not yet consistent.</span></span>
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="6a08a-562">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-562">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="6a08a-563">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="6a08a-563">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="6a08a-564">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6a08a-564">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="6a08a-565">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-565">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="6a08a-566">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="6a08a-566">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="6a08a-567">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-567">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="TryGetValueAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;TValue&gt;&gt; TryGetValueAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, Microsoft.ServiceFabric.Data.Collections.LockMode lockMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!TValue&gt;&gt; TryGetValueAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, valuetype Microsoft.ServiceFabric.Data.Collections.LockMode lockMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.TryGetValueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,Microsoft.ServiceFabric.Data.Collections.LockMode)" />
      <MemberSignature Language="F#" Value="abstract member TryGetValueAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * Microsoft.ServiceFabric.Data.Collections.LockMode -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;'Value&gt;&gt;" Usage="iReliableDictionary.TryGetValueAsync (tx, key, lockMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;TValue&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="lockMode" Type="Microsoft.ServiceFabric.Data.Collections.LockMode" />
      </Parameters>
      <Docs>
        <param name="tx"><span data-ttu-id="6a08a-568">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="6a08a-568">Transaction to associate this operation with.</span></span></param>
        <param name="key"><span data-ttu-id="6a08a-569">取得する値のキー。</span><span class="sxs-lookup"><span data-stu-id="6a08a-569">The key of the value to get.</span></span></param>
        <param name="lockMode"><span data-ttu-id="6a08a-570">この読み取り操作に使用するロックの種類です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-570">Type of locking to use for this read operation.</span></span></param>
        <summary>
            <span data-ttu-id="6a08a-571">信頼性の高いディクショナリから指定されたキーに関連付けられている値を取得しようとしています。</span><span class="sxs-lookup"><span data-stu-id="6a08a-571">Attempts to get the value associated with the specified key from the Reliable Dictionary.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="6a08a-572">非同期の読み取り操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="6a08a-572">A task that represents the asynchronous read operation.</span></span> <span data-ttu-id="6a08a-573">タスクの結果の組は、その場合は、信頼性の高いディクショナリのキーが見つかったかどうかを示す、値。</span><span class="sxs-lookup"><span data-stu-id="6a08a-573">The task result is a tuple indicating whether the key was found in the Reliable Dictionary and if so, the value.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="6a08a-574"><paramref name="tx" />null、または<paramref name="key" />が null またはシリアル化することはできません。</span><span class="sxs-lookup"><span data-stu-id="6a08a-574"><paramref name="tx" /> is null, or <paramref name="key" /> is null or cannot be serialized.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="6a08a-575">既定のタイムアウト以内に完了する操作が失敗しました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-575">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            <span data-ttu-id="6a08a-576">IReliableDictionary が現時点での読み取りを使用できないことを示します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-576">Indicates that the IReliableDictionary cannot serve reads at the moment.</span></span>
            <span data-ttu-id="6a08a-577">すべてのページでこの例外はスローされる<see cref="T:System.Fabric.ReplicaRole" />s。</span><span class="sxs-lookup"><span data-stu-id="6a08a-577">This exception can be thrown in all <see cref="T:System.Fabric.ReplicaRole" />s.</span></span>
            <span data-ttu-id="6a08a-578">1 つの理由でスローされる可能性が、<see cref="F:System.Fabric.ReplicaRole.Primary" />ロールが失われる<see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-578">One reason it may be thrown in the <see cref="F:System.Fabric.ReplicaRole.Primary" /> role is loss of <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span></span>
            <span data-ttu-id="6a08a-579">1 つの理由でスローされる可能性が、<see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />ロールは、信頼性の高いコレクションの状態があるまだ一貫性のあります。</span><span class="sxs-lookup"><span data-stu-id="6a08a-579">One reason it may be thrown in the <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> role is that Reliable Collection's state is not yet consistent.</span></span>
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="6a08a-580">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-580">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="6a08a-581">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="6a08a-581">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="6a08a-582">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6a08a-582">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="6a08a-583">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-583">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="6a08a-584">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="6a08a-584">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="6a08a-585">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-585">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="TryGetValueAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;TValue&gt;&gt; TryGetValueAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!TValue&gt;&gt; TryGetValueAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.TryGetValueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TryGetValueAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;'Value&gt;&gt;" Usage="iReliableDictionary.TryGetValueAsync (tx, key, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;TValue&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="tx"><span data-ttu-id="6a08a-586">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="6a08a-586">Transaction to associate this operation with.</span></span></param>
        <param name="key"><span data-ttu-id="6a08a-587">取得する値のキー。</span><span class="sxs-lookup"><span data-stu-id="6a08a-587">The key of the value to get.</span></span></param>
        <param name="timeout"><span data-ttu-id="6a08a-588">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。</span><span class="sxs-lookup"><span data-stu-id="6a08a-588">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="6a08a-589">主にデッドロックを防ぐために使用します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-589">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="6a08a-590">既定では 4 秒です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-590">The default is 4 seconds.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="6a08a-591">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="6a08a-591">The token to monitor for cancellation requests.</span></span> <span data-ttu-id="6a08a-592">既定値は None です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-592">The default is None.</span></span></param>
        <summary>
            <span data-ttu-id="6a08a-593">信頼性の高いディクショナリから指定されたキーに関連付けられている値を取得しようとしています。</span><span class="sxs-lookup"><span data-stu-id="6a08a-593">Attempts to get the value associated with the specified key from the Reliable Dictionary.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="6a08a-594">非同期の読み取り操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="6a08a-594">A task that represents the asynchronous read operation.</span></span> <span data-ttu-id="6a08a-595">タスクの結果の組は、その場合は、信頼性の高いディクショナリのキーが見つかったかどうかを示す、値。</span><span class="sxs-lookup"><span data-stu-id="6a08a-595">The task result is a tuple indicating whether the key was found in the Reliable Dictionary and if so, the value.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="6a08a-596"><paramref name="tx" />null、または<paramref name="key" />が null またはシリアル化することはできません。</span><span class="sxs-lookup"><span data-stu-id="6a08a-596"><paramref name="tx" /> is null, or <paramref name="key" /> is null or cannot be serialized.</span></span></exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="6a08a-597"><paramref name="timeout" /> が負の値です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-597"><paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="6a08a-598">操作は、指定したタイムアウト時間内に完了できませんでした。</span><span class="sxs-lookup"><span data-stu-id="6a08a-598">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="6a08a-599">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-599">The operation was canceled.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            <span data-ttu-id="6a08a-600">IReliableDictionary が現時点での読み取りを使用できないことを示します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-600">Indicates that the IReliableDictionary cannot serve reads at the moment.</span></span>
            <span data-ttu-id="6a08a-601">すべてのページでこの例外はスローされる<see cref="T:System.Fabric.ReplicaRole" />s。</span><span class="sxs-lookup"><span data-stu-id="6a08a-601">This exception can be thrown in all <see cref="T:System.Fabric.ReplicaRole" />s.</span></span>
            <span data-ttu-id="6a08a-602">1 つの理由でスローされる可能性が、<see cref="F:System.Fabric.ReplicaRole.Primary" />ロールが失われる<see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-602">One reason it may be thrown in the <see cref="F:System.Fabric.ReplicaRole.Primary" /> role is loss of <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span></span>
            <span data-ttu-id="6a08a-603">1 つの理由でスローされる可能性が、<see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />ロールは、信頼性の高いコレクションの状態があるまだ一貫性のあります。</span><span class="sxs-lookup"><span data-stu-id="6a08a-603">One reason it may be thrown in the <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> role is that Reliable Collection's state is not yet consistent.</span></span>
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="6a08a-604">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-604">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="6a08a-605">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="6a08a-605">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="6a08a-606">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6a08a-606">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="6a08a-607">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-607">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="6a08a-608">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="6a08a-608">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="6a08a-609">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-609">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="TryGetValueAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;TValue&gt;&gt; TryGetValueAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, Microsoft.ServiceFabric.Data.Collections.LockMode lockMode, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!TValue&gt;&gt; TryGetValueAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, valuetype Microsoft.ServiceFabric.Data.Collections.LockMode lockMode, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.TryGetValueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,Microsoft.ServiceFabric.Data.Collections.LockMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TryGetValueAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * Microsoft.ServiceFabric.Data.Collections.LockMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;'Value&gt;&gt;" Usage="iReliableDictionary.TryGetValueAsync (tx, key, lockMode, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;TValue&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="lockMode" Type="Microsoft.ServiceFabric.Data.Collections.LockMode" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="tx"><span data-ttu-id="6a08a-610">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="6a08a-610">Transaction to associate this operation with.</span></span></param>
        <param name="key"><span data-ttu-id="6a08a-611">取得する値のキー。</span><span class="sxs-lookup"><span data-stu-id="6a08a-611">The key of the value to get.</span></span></param>
        <param name="lockMode"><span data-ttu-id="6a08a-612">この読み取り操作に使用するロックの種類です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-612">Type of locking to use for this read operation.</span></span></param>
        <param name="timeout"><span data-ttu-id="6a08a-613">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。</span><span class="sxs-lookup"><span data-stu-id="6a08a-613">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="6a08a-614">主にデッドロックを防ぐために使用します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-614">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="6a08a-615">既定では 4 秒です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-615">The default is 4 seconds.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="6a08a-616">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="6a08a-616">The token to monitor for cancellation requests.</span></span> <span data-ttu-id="6a08a-617">既定値は None です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-617">The default is None.</span></span></param>
        <summary>
            <span data-ttu-id="6a08a-618">信頼性の高いディクショナリから指定されたキーに関連付けられている値を取得しようとしています。</span><span class="sxs-lookup"><span data-stu-id="6a08a-618">Attempts to get the value associated with the specified key from the Reliable Dictionary.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="6a08a-619">非同期の読み取り操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="6a08a-619">A task that represents the asynchronous read operation.</span></span> <span data-ttu-id="6a08a-620">タスクの結果の組は、その場合は、信頼性の高いディクショナリのキーが見つかったかどうかを示す、値。</span><span class="sxs-lookup"><span data-stu-id="6a08a-620">The task result is a tuple indicating whether the key was found in the Reliable Dictionary and if so, the value.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="6a08a-621"><paramref name="tx" />null、または<paramref name="key" />が null またはシリアル化することはできません。</span><span class="sxs-lookup"><span data-stu-id="6a08a-621"><paramref name="tx" /> is null, or <paramref name="key" /> is null or cannot be serialized.</span></span></exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="6a08a-622"><paramref name="timeout" /> が負の値です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-622"><paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="6a08a-623">操作は、指定したタイムアウト時間内に完了できませんでした。</span><span class="sxs-lookup"><span data-stu-id="6a08a-623">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="6a08a-624">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-624">The operation was canceled.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            <span data-ttu-id="6a08a-625">IReliableDictionary が現時点での読み取りを使用できないことを示します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-625">Indicates that the IReliableDictionary cannot serve reads at the moment.</span></span>
            <span data-ttu-id="6a08a-626">すべてのページでこの例外はスローされる<see cref="T:System.Fabric.ReplicaRole" />s。</span><span class="sxs-lookup"><span data-stu-id="6a08a-626">This exception can be thrown in all <see cref="T:System.Fabric.ReplicaRole" />s.</span></span>
            <span data-ttu-id="6a08a-627">1 つの理由でスローされる可能性が、<see cref="F:System.Fabric.ReplicaRole.Primary" />ロールが失われる<see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-627">One reason it may be thrown in the <see cref="F:System.Fabric.ReplicaRole.Primary" /> role is loss of <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span></span>
            <span data-ttu-id="6a08a-628">1 つの理由でスローされる可能性が、<see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />ロールは、信頼性の高いコレクションの状態があるまだ一貫性のあります。</span><span class="sxs-lookup"><span data-stu-id="6a08a-628">One reason it may be thrown in the <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> role is that Reliable Collection's state is not yet consistent.</span></span>
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="6a08a-629">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-629">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="6a08a-630">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="6a08a-630">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="6a08a-631">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6a08a-631">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="6a08a-632">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-632">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="6a08a-633">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="6a08a-633">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="6a08a-634">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-634">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="TryRemoveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;TValue&gt;&gt; TryRemoveAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!TValue&gt;&gt; TryRemoveAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.TryRemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,`0)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryRemoveAsync (tx As ITransaction, key As TKey) As Task(Of ConditionalValue(Of TValue))" />
      <MemberSignature Language="F#" Value="abstract member TryRemoveAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;'Value&gt;&gt;" Usage="iReliableDictionary.TryRemoveAsync (tx, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;TValue&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
      </Parameters>
      <Docs>
        <param name="tx"><span data-ttu-id="6a08a-635">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="6a08a-635">Transaction to associate this operation with.</span></span></param>
        <param name="key"><span data-ttu-id="6a08a-636">削除する要素のキー。</span><span class="sxs-lookup"><span data-stu-id="6a08a-636">The key of the element to remove.</span></span></param>
        <summary>
            <span data-ttu-id="6a08a-637">信頼性の高いディクショナリから指定されたキーに値を削除しようとしています。</span><span class="sxs-lookup"><span data-stu-id="6a08a-637">Attempts to remove the value with the specified key from the Reliable Dictionary.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="6a08a-638">非同期の削除操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="6a08a-638">Task that represents the asynchronous remove operation.</span></span> <span data-ttu-id="6a08a-639">タスクの結果の組は、その場合、信頼性の高いディクショナリからキーが削除されたかどうかを示す、値。</span><span class="sxs-lookup"><span data-stu-id="6a08a-639">The task result is a tuple indicating whether the key was removed from the Reliable Dictionary and if so, the value.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="6a08a-640"><paramref name="tx" />null、または<paramref name="key" />が null またはシリアル化することはできません。</span><span class="sxs-lookup"><span data-stu-id="6a08a-640"><paramref name="tx" /> is null, or <paramref name="key" /> is null or cannot be serialized.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="6a08a-641">既定のタイムアウト以内に完了する操作が失敗しました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-641">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="6a08a-642">ときにスローされる例外、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-642">The exception that is thrown when the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="6a08a-643">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-643">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="6a08a-644">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="6a08a-644">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="6a08a-645">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6a08a-645">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="6a08a-646">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-646">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="6a08a-647">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="6a08a-647">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="6a08a-648">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-648">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="TryRemoveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;TValue&gt;&gt; TryRemoveAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!TValue&gt;&gt; TryRemoveAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.TryRemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TryRemoveAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;'Value&gt;&gt;" Usage="iReliableDictionary.TryRemoveAsync (tx, key, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;TValue&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="tx"><span data-ttu-id="6a08a-649">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="6a08a-649">Transaction to associate this operation with.</span></span></param>
        <param name="key"><span data-ttu-id="6a08a-650">削除する要素のキー。</span><span class="sxs-lookup"><span data-stu-id="6a08a-650">The key of the element to remove.</span></span></param>
        <param name="timeout"><span data-ttu-id="6a08a-651">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。</span><span class="sxs-lookup"><span data-stu-id="6a08a-651">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="6a08a-652">主にデッドロックを防ぐために使用します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-652">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="6a08a-653">既定では 4 秒です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-653">The default is 4 seconds.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="6a08a-654">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="6a08a-654">The token to monitor for cancellation requests.</span></span> <span data-ttu-id="6a08a-655">既定値は None です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-655">The default is None.</span></span></param>
        <summary>
            <span data-ttu-id="6a08a-656">信頼性の高いディクショナリから指定されたキーに値を削除しようとしています。</span><span class="sxs-lookup"><span data-stu-id="6a08a-656">Attempts to remove the value with the specified key from the Reliable Dictionary.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="6a08a-657">非同期の削除操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="6a08a-657">Task that represents the asynchronous remove operation.</span></span> <span data-ttu-id="6a08a-658">タスクの結果の組は、その場合、信頼性の高いディクショナリからキーが削除されたかどうかを示す、値。</span><span class="sxs-lookup"><span data-stu-id="6a08a-658">The task result is a tuple indicating whether the key was removed from the Reliable Dictionary and if so, the value.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="6a08a-659"><paramref name="tx" />null、または<paramref name="key" />が null またはシリアル化することはできません。</span><span class="sxs-lookup"><span data-stu-id="6a08a-659"><paramref name="tx" /> is null, or <paramref name="key" /> is null or cannot be serialized.</span></span></exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="6a08a-660"><paramref name="timeout" /> が負の値です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-660"><paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="6a08a-661">操作は、指定したタイムアウト時間内に完了できませんでした。</span><span class="sxs-lookup"><span data-stu-id="6a08a-661">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="6a08a-662">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-662">The operation was canceled.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="6a08a-663">ときにスローされる例外、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-663">The exception that is thrown when the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="6a08a-664">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-664">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="6a08a-665">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="6a08a-665">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="6a08a-666">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6a08a-666">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="6a08a-667">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-667">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="6a08a-668">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="6a08a-668">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="6a08a-669">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-669">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="TryUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; TryUpdateAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, TValue newValue, TValue comparisonValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; TryUpdateAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, !TValue newValue, !TValue comparisonValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.TryUpdateAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,`1,`1)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryUpdateAsync (tx As ITransaction, key As TKey, newValue As TValue, comparisonValue As TValue) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member TryUpdateAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * 'Value * 'Value -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iReliableDictionary.TryUpdateAsync (tx, key, newValue, comparisonValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="newValue" Type="TValue" />
        <Parameter Name="comparisonValue" Type="TValue" />
      </Parameters>
      <Docs>
        <param name="tx"><span data-ttu-id="6a08a-670">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="6a08a-670">Transaction to associate this operation with.</span></span></param>
        <param name="key"><span data-ttu-id="6a08a-671">値を <paramref name="comparisonValue" /> と比較し、場合によっては置き換えるキー。</span><span class="sxs-lookup"><span data-stu-id="6a08a-671">The key whose value is compared with <paramref name="comparisonValue" /> and possibly replaced.</span></span></param>
        <param name="newValue"><span data-ttu-id="6a08a-672">比較した結果が等しい場合に、指定した <paramref name="key" /> を持つ要素の値を置き換える値。</span><span class="sxs-lookup"><span data-stu-id="6a08a-672">The value that replaces the value of the element that has the specified <paramref name="key" /> if the comparison results in equality.</span></span></param>
        <param name="comparisonValue"><span data-ttu-id="6a08a-673">指定した <paramref name="key" /> を持つ要素の値と比較する値。</span><span class="sxs-lookup"><span data-stu-id="6a08a-673">The value that is compared to the value of the element that has the specified <paramref name="key" />.</span></span></param>
        <summary>
            <span data-ttu-id="6a08a-674">指定したキーの既存の値と指定した値を比較し、等しい場合は別の値でキーを更新します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-674">Compares the existing value for the specified key with a specified value, and if they are equal, updates the key with a third value.</span></span>
            </summary>
        <returns><span data-ttu-id="6a08a-675">非同期更新操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="6a08a-675">A task that represents the asynchronous update operation.</span></span> <span data-ttu-id="6a08a-676">タスクの結果は、オブジェクトが更新されたかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-676">The task result indicates whether the object was updated.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="6a08a-677"><paramref name="tx" />null、または<paramref name="key" />が null またはシリアル化することはできません。</span><span class="sxs-lookup"><span data-stu-id="6a08a-677"><paramref name="tx" /> is null, or <paramref name="key" /> is null or cannot be serialized.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="6a08a-678">既定のタイムアウト以内に完了する操作が失敗しました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-678">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="6a08a-679">ときにスローされる例外、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-679">The exception that is thrown when the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="6a08a-680">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-680">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="6a08a-681">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="6a08a-681">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="6a08a-682">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6a08a-682">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="6a08a-683">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-683">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="6a08a-684">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="6a08a-684">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="6a08a-685">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-685">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="TryUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; TryUpdateAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, TValue newValue, TValue comparisonValue, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; TryUpdateAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, !TValue newValue, !TValue comparisonValue, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.TryUpdateAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,`1,`1,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TryUpdateAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * 'Value * 'Value * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iReliableDictionary.TryUpdateAsync (tx, key, newValue, comparisonValue, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="newValue" Type="TValue" />
        <Parameter Name="comparisonValue" Type="TValue" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="tx"><span data-ttu-id="6a08a-686">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="6a08a-686">Transaction to associate this operation with.</span></span></param>
        <param name="key"><span data-ttu-id="6a08a-687">値を <paramref name="comparisonValue" /> と比較し、場合によっては置き換えるキー。</span><span class="sxs-lookup"><span data-stu-id="6a08a-687">The key whose value is compared with <paramref name="comparisonValue" /> and possibly replaced.</span></span></param>
        <param name="newValue"><span data-ttu-id="6a08a-688">比較した結果が等しい場合に、指定した <paramref name="key" /> を持つ要素の値を置き換える値。</span><span class="sxs-lookup"><span data-stu-id="6a08a-688">The value that replaces the value of the element that has the specified <paramref name="key" /> if the comparison results in equality.</span></span></param>
        <param name="comparisonValue"><span data-ttu-id="6a08a-689">指定した <paramref name="key" /> を持つ要素の値と比較する値。</span><span class="sxs-lookup"><span data-stu-id="6a08a-689">The value that is compared to the value of the element that has the specified <paramref name="key" />.</span></span></param>
        <param name="timeout"><span data-ttu-id="6a08a-690">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。</span><span class="sxs-lookup"><span data-stu-id="6a08a-690">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="6a08a-691">主にデッドロックを防ぐために使用します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-691">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="6a08a-692">既定では 4 秒です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-692">The default is 4 seconds.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="6a08a-693">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="6a08a-693">The token to monitor for cancellation requests.</span></span> <span data-ttu-id="6a08a-694">既定値は None です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-694">The default is None.</span></span></param>
        <summary>
            <span data-ttu-id="6a08a-695">指定したキーの既存の値と指定した値を比較し、等しい場合は別の値でキーを更新します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-695">Compares the existing value for the specified key with a specified value, and if they are equal, updates the key with a third value.</span></span>
            </summary>
        <returns><span data-ttu-id="6a08a-696">非同期更新操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="6a08a-696">A task that represents the asynchronous update operation.</span></span> <span data-ttu-id="6a08a-697">タスクの結果は、オブジェクトが更新されたかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-697">The task result indicates whether the object was updated.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="6a08a-698"><paramref name="tx" />null、または<paramref name="key" />が null またはシリアル化することはできません。</span><span class="sxs-lookup"><span data-stu-id="6a08a-698"><paramref name="tx" /> is null, or <paramref name="key" /> is null or cannot be serialized.</span></span></exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="6a08a-699"><paramref name="timeout" /> が負の値です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-699"><paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="6a08a-700">操作は、指定したタイムアウト時間内に完了できませんでした。</span><span class="sxs-lookup"><span data-stu-id="6a08a-700">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="6a08a-701">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-701">The operation was canceled.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="6a08a-702">ときにスローされる例外、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="6a08a-702">The exception that is thrown when the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="6a08a-703">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-703">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="6a08a-704">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="6a08a-704">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="6a08a-705">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6a08a-705">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="6a08a-706">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="6a08a-706">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="6a08a-707">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="6a08a-707">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="6a08a-708">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</span><span class="sxs-lookup"><span data-stu-id="6a08a-708">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
      </Docs>
    </Member>
  </Members>
</Type>