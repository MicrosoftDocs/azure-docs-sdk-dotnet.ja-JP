<Type Name="IReliableDictionary2&lt;TKey,TValue&gt;" FullName="Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2&lt;TKey,TValue&gt;">
  <TypeSignature Language="C#" Value="public interface IReliableDictionary2&lt;TKey,TValue&gt; : Microsoft.ServiceFabric.Data.Collections.IReliableCollection&lt;System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;&gt;, Microsoft.ServiceFabric.Data.Collections.IReliableDictionary&lt;TKey,TValue&gt; where TKey : IComparable&lt;TKey&gt;, IEquatable&lt;TKey&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IReliableDictionary2`2&lt;(class System.IComparable`1&lt;!TKey&gt;, class System.IEquatable`1&lt;!TKey&gt;) TKey, TValue&gt; implements class Microsoft.ServiceFabric.Data.Collections.IReliableCollection`1&lt;valuetype System.Collections.Generic.KeyValuePair`2&lt;!TKey, !TValue&gt;&gt;, class Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2&lt;!TKey, !TValue&gt;, class Microsoft.ServiceFabric.Data.IReliableState" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2" />
  <TypeSignature Language="VB.NET" Value="Public Interface IReliableDictionary2(Of TKey, TValue)&#xA;Implements IReliableCollection(Of KeyValuePair(Of TKey, TValue)), IReliableDictionary(Of TKey, TValue)" />
  <TypeSignature Language="F#" Value="type IReliableDictionary2&lt;'Key, 'Value (requires 'Key :&gt; IComparable&lt;'Key&gt; and 'Key :&gt; IEquatable&lt;'Key&gt;)&gt; = interface&#xA;    interface IReliableDictionary&lt;'Key, 'Value (requires 'Key :&gt; IComparable&lt;'Key&gt; and 'Key :&gt; IEquatable&lt;'Key&gt;)&gt;&#xA;    interface IReliableCollection&lt;KeyValuePair&lt;'Key, 'Value&gt;&gt;&#xA;    interface IReliableState" />
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
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Data.Collections.IReliableDictionary&lt;TKey,TValue&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="TKey"><span data-ttu-id="12f41-101">信頼性の高いディクショナリ内のキーの型。</span><span class="sxs-lookup"><span data-stu-id="12f41-101">The type of the keys in the reliable dictionary.</span></span></typeparam>
    <typeparam name="TValue">
            <span data-ttu-id="12f41-102">信頼性の高いディクショナリ内の値の型。</span><span class="sxs-lookup"><span data-stu-id="12f41-102">The type of the values in the reliable dictionary.</span></span></typeparam>
    <summary>
            <span data-ttu-id="12f41-103">信頼性の高い永続化されレプリケートされているキー/値ペアのコレクションを表します。</span><span class="sxs-lookup"><span data-stu-id="12f41-103">Represents a reliable collection of key/value pairs that are persisted and replicated.</span></span>
            </summary>
    <remarks><span data-ttu-id="12f41-104">ディクショナリでの操作のコンテキストの外部キーまたは MUST NOT このディクショナリに格納されている値は変換。</span><span class="sxs-lookup"><span data-stu-id="12f41-104">Keys or values stored in this dictionary MUST NOT be mutated outside the context of an operation on the dictionary.</span></span>  <span data-ttu-id="12f41-105">両方をお勧め<typeparamref name="TKey" />と<typeparamref name="TValue" />偶発的なデータの破損を回避するために変更できません。</span><span class="sxs-lookup"><span data-stu-id="12f41-105">It is highly recommended to make both <typeparamref name="TKey" /> and <typeparamref name="TValue" /> immutable in order to avoid accidental data corruption.</span></span>
            
            <span data-ttu-id="12f41-106"><para>トランザクションは、同時実行の単位です。ユーザーが特定の時点の時間、インフライトの複数のトランザクションを持つことができますが、特定のトランザクションの各 API 呼び出す必要があります、一度に 1 つ。非同期信頼性の高いコレクション メソッドの呼び出しがいつ、 <see cref="T:Microsoft.ServiceFabric.Data.ITransaction" />、同じトランザクションを使用して別のメソッドを呼び出す前に、返されるタスクの完了を待つ必要があります。</para></span><span class="sxs-lookup"><span data-stu-id="12f41-106"><para> The transaction is the unit of concurrency. Users can have multiple transactions in-flight at any given point of time, but for a given transaction each API must be called one at a time. When calling any asynchronous Reliable Collection method that takes an <see cref="T:Microsoft.ServiceFabric.Data.ITransaction" />, you must wait for completion of the returned Task before calling another method using the same transaction. </para></span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public long Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Long" />
      <MemberSignature Language="F#" Value="member this.Count : int64" Usage="Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2&lt;'Key, 'Value (requires 'Key :&gt; System.IComparable&lt;'Key&gt; and 'Key :&gt; System.IEquatable&lt;'Key&gt;)&gt;.Count" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="12f41-107">含まれているキー/値ペアの数を取得、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2" />です。</span><span class="sxs-lookup"><span data-stu-id="12f41-107">Gets the number of key-value pairs contained in the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="12f41-108">このプロパティには、トランザクションのセマンティクスがありません。</span><span class="sxs-lookup"><span data-stu-id="12f41-108">This property does not have transactional semantics.</span></span> <span data-ttu-id="12f41-109">プロパティがアクセスした時点で最適な残存作業時間数、ディクショナリ内の項目を表します。</span><span class="sxs-lookup"><span data-stu-id="12f41-109">It represents the best effort number of items in the dictionary at the moment when the property was accessed.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateKeyEnumerableAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;TKey&gt;&gt; CreateKeyEnumerableAsync (Microsoft.ServiceFabric.Data.ITransaction txn);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Data.IAsyncEnumerable`1&lt;!TKey&gt;&gt; CreateKeyEnumerableAsync(class Microsoft.ServiceFabric.Data.ITransaction txn) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2.CreateKeyEnumerableAsync(Microsoft.ServiceFabric.Data.ITransaction)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateKeyEnumerableAsync (txn As ITransaction) As Task(Of IAsyncEnumerable(Of TKey))" />
      <MemberSignature Language="F#" Value="abstract member CreateKeyEnumerableAsync : Microsoft.ServiceFabric.Data.ITransaction -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;'Key&gt;&gt;" Usage="iReliableDictionary2.CreateKeyEnumerableAsync txn" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;TKey&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="txn" Type="Microsoft.ServiceFabric.Data.ITransaction" />
      </Parameters>
      <Docs>
        <param name="txn"><span data-ttu-id="12f41-110">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="12f41-110">Transaction to associate this operation with.</span></span></param>
        <summary>
            <span data-ttu-id="12f41-111">経由で非同期列挙子を作成、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2" />キーを列挙します。</span><span class="sxs-lookup"><span data-stu-id="12f41-111">Creates an async enumerator over the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2" /> to enumerate the keys.</span></span>
            </summary>
        <returns><span data-ttu-id="12f41-112">信頼性の高いディクショナリ キーの列挙可能です。</span><span class="sxs-lookup"><span data-stu-id="12f41-112">An enumerable for the reliable dictionary keys.</span></span></returns>
        <remarks>
            <span data-ttu-id="12f41-113">信頼性の高いディクショナリから返される enumerarable は安全に読み取りと同時に使用し、ディクショナリに書き込みます。</span><span class="sxs-lookup"><span data-stu-id="12f41-113">The enumerarable returned from the reliable dictionary is safe to use concurrently with reads and writes to the dictionary.</span></span> <span data-ttu-id="12f41-114">ディクショナリのスナップショットの一貫したビューを表します。</span><span class="sxs-lookup"><span data-stu-id="12f41-114">It represents a snapshot consistent view of the dictionary.</span></span>
            </remarks>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            <span data-ttu-id="12f41-115">例外は、信頼性の高いディクショナリが現時点での読み取りを使用できないことを示します。</span><span class="sxs-lookup"><span data-stu-id="12f41-115">Exception indicates that the Reliable Dictionary cannot serve reads at the moment.</span></span>
            <span data-ttu-id="12f41-116"><see cref="T:System.Fabric.FabricNotReadableException" />すべてのページでスローされる可能性<see cref="T:System.Fabric.ReplicaRole" />s。</span><span class="sxs-lookup"><span data-stu-id="12f41-116"><see cref="T:System.Fabric.FabricNotReadableException" /> can be thrown in all <see cref="T:System.Fabric.ReplicaRole" />s.</span></span>
            <span data-ttu-id="12f41-117">1 つの例でスローされたため、<see cref="F:System.Fabric.ReplicaRole.Primary" />が失われること<see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />です。</span><span class="sxs-lookup"><span data-stu-id="12f41-117">One example for it being thrown in the <see cref="F:System.Fabric.ReplicaRole.Primary" /> is loss of <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span></span>
            <span data-ttu-id="12f41-118">1 つの例でスローされたため、<see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />は、信頼性の高いコレクションの状態があるまだ一貫性のあります。</span><span class="sxs-lookup"><span data-stu-id="12f41-118">One example for it being thrown in the <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> is that Reliable Collection's state is not yet consistent.</span></span>
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="12f41-119">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="12f41-119">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="12f41-120">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="12f41-120">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="12f41-121">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="12f41-121">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="12f41-122">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="12f41-122">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="12f41-123">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="12f41-123">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="12f41-124">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</span><span class="sxs-lookup"><span data-stu-id="12f41-124">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CreateKeyEnumerableAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;TKey&gt;&gt; CreateKeyEnumerableAsync (Microsoft.ServiceFabric.Data.ITransaction txn, Microsoft.ServiceFabric.Data.Collections.EnumerationMode enumerationMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Data.IAsyncEnumerable`1&lt;!TKey&gt;&gt; CreateKeyEnumerableAsync(class Microsoft.ServiceFabric.Data.ITransaction txn, valuetype Microsoft.ServiceFabric.Data.Collections.EnumerationMode enumerationMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2.CreateKeyEnumerableAsync(Microsoft.ServiceFabric.Data.ITransaction,Microsoft.ServiceFabric.Data.Collections.EnumerationMode)" />
      <MemberSignature Language="F#" Value="abstract member CreateKeyEnumerableAsync : Microsoft.ServiceFabric.Data.ITransaction * Microsoft.ServiceFabric.Data.Collections.EnumerationMode -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;'Key&gt;&gt;" Usage="iReliableDictionary2.CreateKeyEnumerableAsync (txn, enumerationMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;TKey&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="txn" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="enumerationMode" Type="Microsoft.ServiceFabric.Data.Collections.EnumerationMode" />
      </Parameters>
      <Docs>
        <param name="txn"><span data-ttu-id="12f41-125">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="12f41-125">Transaction to associate this operation with.</span></span></param>
        <param name="enumerationMode"><span data-ttu-id="12f41-126">使用する列挙モード。</span><span class="sxs-lookup"><span data-stu-id="12f41-126">The enumeration mode to use.</span></span> <span data-ttu-id="12f41-127">既定値は順序なしです。</span><span class="sxs-lookup"><span data-stu-id="12f41-127">The default is Unordered.</span></span></param>
        <summary>
            <span data-ttu-id="12f41-128">経由で非同期列挙子を作成、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2" />キーを列挙します。</span><span class="sxs-lookup"><span data-stu-id="12f41-128">Creates an async enumerator over the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2" /> to enumerate the keys.</span></span>
            </summary>
        <returns><span data-ttu-id="12f41-129">列挙可能な<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2" />キー。</span><span class="sxs-lookup"><span data-stu-id="12f41-129">An enumerable for the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2" /> keys.</span></span></returns>
        <remarks>
            <span data-ttu-id="12f41-130">返された enumerarable、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2" />を安全に読み取りと同時に使用してディクショナリを書き込みます。</span><span class="sxs-lookup"><span data-stu-id="12f41-130">The enumerarable returned from the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2" /> is safe to use concurrently with reads and writes to the dictionary.</span></span> <span data-ttu-id="12f41-131">ディクショナリのスナップショットの一貫したビューを表します。</span><span class="sxs-lookup"><span data-stu-id="12f41-131">It represents a snapshot consistent view of the dictionary.</span></span>
            </remarks>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            <span data-ttu-id="12f41-132">例外は、信頼性の高いディクショナリが現時点での読み取りを使用できないことを示します。</span><span class="sxs-lookup"><span data-stu-id="12f41-132">Exception indicates that the Reliable Dictionary cannot serve reads at the moment.</span></span>
            <span data-ttu-id="12f41-133"><see cref="T:System.Fabric.FabricNotReadableException" />すべてのページでスローされる可能性<see cref="T:System.Fabric.ReplicaRole" />s。</span><span class="sxs-lookup"><span data-stu-id="12f41-133"><see cref="T:System.Fabric.FabricNotReadableException" /> can be thrown in all <see cref="T:System.Fabric.ReplicaRole" />s.</span></span>
            <span data-ttu-id="12f41-134">1 つの例でスローされたため、<see cref="F:System.Fabric.ReplicaRole.Primary" />が失われること<see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />です。</span><span class="sxs-lookup"><span data-stu-id="12f41-134">One example for it being thrown in the <see cref="F:System.Fabric.ReplicaRole.Primary" /> is loss of <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span></span>
            <span data-ttu-id="12f41-135">1 つの例でスローされたため、<see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />は、信頼性の高いコレクションの状態があるまだ一貫性のあります。</span><span class="sxs-lookup"><span data-stu-id="12f41-135">One example for it being thrown in the <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> is that Reliable Collection's state is not yet consistent.</span></span>
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="12f41-136">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="12f41-136">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="12f41-137">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="12f41-137">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="12f41-138">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="12f41-138">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="12f41-139">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="12f41-139">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="12f41-140">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="12f41-140">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="12f41-141">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</span><span class="sxs-lookup"><span data-stu-id="12f41-141">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CreateKeyEnumerableAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;TKey&gt;&gt; CreateKeyEnumerableAsync (Microsoft.ServiceFabric.Data.ITransaction txn, Microsoft.ServiceFabric.Data.Collections.EnumerationMode enumerationMode, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Data.IAsyncEnumerable`1&lt;!TKey&gt;&gt; CreateKeyEnumerableAsync(class Microsoft.ServiceFabric.Data.ITransaction txn, valuetype Microsoft.ServiceFabric.Data.Collections.EnumerationMode enumerationMode, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2.CreateKeyEnumerableAsync(Microsoft.ServiceFabric.Data.ITransaction,Microsoft.ServiceFabric.Data.Collections.EnumerationMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateKeyEnumerableAsync : Microsoft.ServiceFabric.Data.ITransaction * Microsoft.ServiceFabric.Data.Collections.EnumerationMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;'Key&gt;&gt;" Usage="iReliableDictionary2.CreateKeyEnumerableAsync (txn, enumerationMode, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;TKey&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="txn" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="enumerationMode" Type="Microsoft.ServiceFabric.Data.Collections.EnumerationMode" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="txn"><span data-ttu-id="12f41-142">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="12f41-142">Transaction to associate this operation with.</span></span></param>
        <param name="enumerationMode"><span data-ttu-id="12f41-143">使用する列挙モード。</span><span class="sxs-lookup"><span data-stu-id="12f41-143">The enumeration mode to use.</span></span> <span data-ttu-id="12f41-144">既定値は順序なしです。</span><span class="sxs-lookup"><span data-stu-id="12f41-144">The default is Unordered.</span></span></param>
        <param name="timeout">
            <span data-ttu-id="12f41-145">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。</span><span class="sxs-lookup"><span data-stu-id="12f41-145">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="12f41-146">主にデッドロックを防ぐために使用します。</span><span class="sxs-lookup"><span data-stu-id="12f41-146">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="12f41-147">既定では 4 秒です。</span><span class="sxs-lookup"><span data-stu-id="12f41-147">The default is 4 seconds.</span></span>
            </param>
        <param name="cancellationToken"><span data-ttu-id="12f41-148">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="12f41-148">The token to monitor for cancellation requests.</span></span> <span data-ttu-id="12f41-149">既定値は None です。</span><span class="sxs-lookup"><span data-stu-id="12f41-149">The default is None.</span></span></param>
        <summary>
            <span data-ttu-id="12f41-150">経由で非同期列挙子を作成、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2" />キーを列挙します。</span><span class="sxs-lookup"><span data-stu-id="12f41-150">Creates an async enumerator over the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2" /> to enumerate the keys.</span></span>
            </summary>
        <returns><span data-ttu-id="12f41-151">列挙可能な<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2" />キー。</span><span class="sxs-lookup"><span data-stu-id="12f41-151">An enumerable for the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2" /> keys.</span></span></returns>
        <remarks>
            <span data-ttu-id="12f41-152">返された enumerarable、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2" />を安全に読み取りと同時に使用してディクショナリを書き込みます。</span><span class="sxs-lookup"><span data-stu-id="12f41-152">The enumerarable returned from the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2" /> is safe to use concurrently with reads and writes to the dictionary.</span></span> <span data-ttu-id="12f41-153">ディクショナリのスナップショットの一貫したビューを表します。</span><span class="sxs-lookup"><span data-stu-id="12f41-153">It represents a snapshot consistent view of the dictionary.</span></span>
            </remarks>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            <span data-ttu-id="12f41-154">例外は、信頼性の高いディクショナリが現時点での読み取りを使用できないことを示します。</span><span class="sxs-lookup"><span data-stu-id="12f41-154">Exception indicates that the Reliable Dictionary cannot serve reads at the moment.</span></span>
            <span data-ttu-id="12f41-155"><see cref="T:System.Fabric.FabricNotReadableException" />すべてのページでスローされる可能性<see cref="T:System.Fabric.ReplicaRole" />s。</span><span class="sxs-lookup"><span data-stu-id="12f41-155"><see cref="T:System.Fabric.FabricNotReadableException" /> can be thrown in all <see cref="T:System.Fabric.ReplicaRole" />s.</span></span>
            <span data-ttu-id="12f41-156">1 つの例でスローされたため、<see cref="F:System.Fabric.ReplicaRole.Primary" />が失われること<see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />です。</span><span class="sxs-lookup"><span data-stu-id="12f41-156">One example for it being thrown in the <see cref="F:System.Fabric.ReplicaRole.Primary" /> is loss of <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span></span>
            <span data-ttu-id="12f41-157">1 つの例でスローされたため、<see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />は、信頼性の高いコレクションの状態があるまだ一貫性のあります。</span><span class="sxs-lookup"><span data-stu-id="12f41-157">One example for it being thrown in the <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> is that Reliable Collection's state is not yet consistent.</span></span>
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="12f41-158">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="12f41-158">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="12f41-159">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="12f41-159">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="12f41-160">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="12f41-160">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="12f41-161">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="12f41-161">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="12f41-162">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="12f41-162">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="12f41-163">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</span><span class="sxs-lookup"><span data-stu-id="12f41-163">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
      </Docs>
    </Member>
  </Members>
</Type>