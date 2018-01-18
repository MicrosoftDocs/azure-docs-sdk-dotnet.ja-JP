<Type Name="IReliableCollection&lt;T&gt;" FullName="Microsoft.ServiceFabric.Data.Collections.IReliableCollection&lt;T&gt;">
  <TypeSignature Language="C#" Value="public interface IReliableCollection&lt;T&gt; : Microsoft.ServiceFabric.Data.IReliableState" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IReliableCollection`1&lt;T&gt; implements class Microsoft.ServiceFabric.Data.IReliableState" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.Collections.IReliableCollection`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IReliableCollection(Of T)&#xA;Implements IReliableState" />
  <TypeSignature Language="F#" Value="type IReliableCollection&lt;'T&gt; = interface&#xA;    interface IReliableState" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="T"><span data-ttu-id="f6121-101">コレクション内の要素の型。</span><span class="sxs-lookup"><span data-stu-id="f6121-101">The type of the elements in the collection.</span></span></typeparam>
    <summary>
      <para><span data-ttu-id="f6121-102">信頼性の高いコレクションを操作するメソッドを定義します。</span><span class="sxs-lookup"><span data-stu-id="f6121-102">Defines methods for manipulating Reliable Collections.</span></span></para>
    </summary>
    <remarks>
      <para><span data-ttu-id="f6121-103">詳細については、信頼性の高いコレクションがわかるように<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-reliable-collections">ここ</see>です。</span><span class="sxs-lookup"><span data-stu-id="f6121-103">More information on Reliable Collections can be seen <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-reliable-collections">here</see>.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="ClearAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ClearAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ClearAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableCollection`1.ClearAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function ClearAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member ClearAsync : unit -&gt; System.Threading.Tasks.Task" Usage="iReliableCollection.ClearAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="f6121-104">すべての状態を削除、 <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableCollection`1" />、レプリケートされ、保持された状態を含むです。</span><span class="sxs-lookup"><span data-stu-id="f6121-104">Removes all state from the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableCollection`1" />, including replicated and persisted state.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="f6121-105">非同期のクリア操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="f6121-105">A task that represents the asynchronous clear operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">
          <para><span data-ttu-id="f6121-106">この操作を実行しようとするときにスローされます、<cref name="IReliableCollection{T}" />に含まれていない、<see cref="F:System.Fabric.ReplicaRole.Primary" />ロール。</span><span class="sxs-lookup"><span data-stu-id="f6121-106">Thrown when attempting to perform this operation on a <cref name="IReliableCollection{T}" /> that is not in the <see cref="F:System.Fabric.ReplicaRole.Primary" /> role.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="f6121-107">この操作を指定したタイムアウト時間内に完了できなかったことを示します。</span><span class="sxs-lookup"><span data-stu-id="f6121-107">Indicates that this operation failed to complete within the given timeout.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetCountAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; GetCountAsync (Microsoft.ServiceFabric.Data.ITransaction tx);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;int64&gt; GetCountAsync(class Microsoft.ServiceFabric.Data.ITransaction tx) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableCollection`1.GetCountAsync(Microsoft.ServiceFabric.Data.ITransaction)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetCountAsync (tx As ITransaction) As Task(Of Long)" />
      <MemberSignature Language="F#" Value="abstract member GetCountAsync : Microsoft.ServiceFabric.Data.ITransaction -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="iReliableCollection.GetCountAsync tx" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
      </Parameters>
      <Docs>
        <param name="tx">
            <span data-ttu-id="f6121-108">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="f6121-108">The transaction to associate this operation with.</span></span> <span data-ttu-id="f6121-109">トランザクションの例を参照して<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-work-with-reliable-collections">ここ</see>です。</span><span class="sxs-lookup"><span data-stu-id="f6121-109">See examples of transactions <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-work-with-reliable-collections">here</see>.</span></span>
            </param>
        <summary>
          <para><span data-ttu-id="f6121-110"><see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableCollection`1" /> に格納されている要素の数を取得します。</span><span class="sxs-lookup"><span data-stu-id="f6121-110">Gets the number of elements contained in the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableCollection`1" />.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="f6121-111">要素の数を示す、非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="f6121-111">A task that represents the asynchronous operation, indicating the number of elements.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricNotReadableException">
          <para><span data-ttu-id="f6121-112">IReliableCollection が現時点での読み取りを使用できないことを示します。</span><span class="sxs-lookup"><span data-stu-id="f6121-112">Indicates that the IReliableCollection cannot serve reads at the moment.</span></span>
            <span data-ttu-id="f6121-113">すべてのページでこの例外はスローされる<see cref="T:System.Fabric.ReplicaRole" />s。</span><span class="sxs-lookup"><span data-stu-id="f6121-113">This exception can be thrown in all <see cref="T:System.Fabric.ReplicaRole" />s.</span></span>
            <span data-ttu-id="f6121-114">1 つの理由でスローされる可能性が、<see cref="F:System.Fabric.ReplicaRole.Primary" />ロールが失われる<see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />です。</span><span class="sxs-lookup"><span data-stu-id="f6121-114">One reason it may be thrown in the <see cref="F:System.Fabric.ReplicaRole.Primary" /> role is loss of <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span></span>
            <span data-ttu-id="f6121-115">1 つの理由でスローされる可能性が、<see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />ロールは、信頼性の高いコレクションの状態があるまだ一貫性のあります。</span><span class="sxs-lookup"><span data-stu-id="f6121-115">One reason it may be thrown in the <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> role is that Reliable Collection's state is not yet consistent.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="f6121-116">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="f6121-116">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="f6121-117">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="f6121-117">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="f6121-118">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f6121-118">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="f6121-119">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="f6121-119">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="f6121-120">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="f6121-120">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">
          <para><span data-ttu-id="f6121-121">この操作を実行しようとするときにスローされます、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableCollection`1" />に含まれていない、<see cref="F:System.Fabric.ReplicaRole.Primary" />ロール。</span><span class="sxs-lookup"><span data-stu-id="f6121-121">Thrown when attempting to perform this operation on a <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableCollection`1" /> that is not in the <see cref="F:System.Fabric.ReplicaRole.Primary" /> role.</span></span>
            <span data-ttu-id="f6121-122">使用 IReliableCollection の実装によってセカンダリ レプリカから、場合によっては、読み取りなどの操作を実行できます。</span><span class="sxs-lookup"><span data-stu-id="f6121-122">In some instances, read operations, such as this one, can be performed from secondary replicas depending on the implementation of the IReliableCollection used.</span></span></para>
        </exception>
      </Docs>
    </Member>
  </Members>
</Type>