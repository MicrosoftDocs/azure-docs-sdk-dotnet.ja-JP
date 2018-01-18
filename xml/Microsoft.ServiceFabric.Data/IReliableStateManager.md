<Type Name="IReliableStateManager" FullName="Microsoft.ServiceFabric.Data.IReliableStateManager">
  <TypeSignature Language="C#" Value="public interface IReliableStateManager : Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;Microsoft.ServiceFabric.Data.IReliableState&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IReliableStateManager implements class Microsoft.ServiceFabric.Data.IAsyncEnumerable`1&lt;class Microsoft.ServiceFabric.Data.IReliableState&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />
  <TypeSignature Language="VB.NET" Value="Public Interface IReliableStateManager&#xA;Implements IAsyncEnumerable(Of IReliableState)" />
  <TypeSignature Language="F#" Value="type IReliableStateManager = interface&#xA;    interface IAsyncEnumerable&lt;IReliableState&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;Microsoft.ServiceFabric.Data.IReliableState&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="742c8-101">すべて管理<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />サービス レプリカにします。</span><span class="sxs-lookup"><span data-stu-id="742c8-101">Manages all <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> for a service replica.</span></span>
            <span data-ttu-id="742c8-102">サービス内の各レプリカは、独自の状態マネージャーであるため、独自のセット<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />です。</span><span class="sxs-lookup"><span data-stu-id="742c8-102">Each replica in a service has its own state manager and thus its own set of <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateTransaction">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Data.ITransaction CreateTransaction ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Data.ITransaction CreateTransaction() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.CreateTransaction" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateTransaction () As ITransaction" />
      <MemberSignature Language="F#" Value="abstract member CreateTransaction : unit -&gt; Microsoft.ServiceFabric.Data.ITransaction" Usage="iReliableStateManager.CreateTransaction " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Data.ITransaction</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="742c8-103">作成し、原子的に実行する操作をグループ化に使用できる新しいトランザクションを開始します。</span><span class="sxs-lookup"><span data-stu-id="742c8-103">Create and start a new transaction that can be used to group operations to be performed atomically.</span></span>
            </summary>
        <returns><span data-ttu-id="742c8-104">新しいトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="742c8-104">A new transaction.</span></span></returns>
        <remarks>
            <span data-ttu-id="742c8-105">操作は、トランザクションに渡すことによって追加されます、<see cref="T:Microsoft.ServiceFabric.Data.ITransaction" />信頼性の高い状態メソッド内のオブジェクトします。</span><span class="sxs-lookup"><span data-stu-id="742c8-105">Operations are added to the transaction by passing the <see cref="T:Microsoft.ServiceFabric.Data.ITransaction" /> object in to reliable state methods.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetOrAddAsync&lt;T&gt; (string name) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetOrAddAsync(Of T As IReliableState) (name As String) As Task(Of T)" />
      <MemberSignature Language="F#" Value="abstract member GetOrAddAsync : string -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)&gt; (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)" Usage="iReliableStateManager.GetOrAddAsync name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="742c8-106">指定する場合、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />型、クラス型またはインターフェイス型のいずれかを要求することがあります。</span><span class="sxs-lookup"><span data-stu-id="742c8-106">When specifying the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> type, you may ask for either a class type or an interface type.</span></span>
            <span data-ttu-id="742c8-107"><para>クラスの種類を指定する場合、システムはその型のインスタンスを返すしようとします。その型のインスタンスをインスタンス化できない場合 (抽象クラス、適切なコンス トラクターがないなど)、ArgumentException をスローします。</para><para>インターフェイス型を指定すると、マネージャーは具象型にインターフェイスを解決しようとします。型のマッピングが、ユーザーが指定されている場合、このメソッドは、(サポートされていない) 型を解決するのには、ユーザー指定のマッピングが使用されます。型のマッピングが、ユーザーが指定されていない場合、このメソッドは指定されたインターフェイスの既定の実装を選択します。指定されたインターフェイス型には、既定の実装はありません。 または型のユーザー指定のマッピングが指定されていない、種類が無効、このメソッドは ArgumentException をスローします。</para></span><span class="sxs-lookup"><span data-stu-id="742c8-107"><para> If specifying a class type, the system will attempt to return an instance of that type. If an instance of that type cannot be instantiated (e.g., abstract class, no suitable constructor), an ArgumentException is thrown. </para><para> If specifying an interface type, the manager will attempt to resolve the interface to a concrete type. If type mapping is specified by the user, this method will use the user-specified mapping to resolve the type (not yet supported). If type mapping is not specified by the user this method will select the default implementation for the interface given. If the given interface type does not have a default implementation, or a user-specified mapping for the type is not provided or the type is invalid, this method will throw ArgumentException. </para></span></span></typeparam>
        <param name="name">
            <span data-ttu-id="742c8-108"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。</span><span class="sxs-lookup"><span data-stu-id="742c8-108">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span></span> <span data-ttu-id="742c8-109">この名前は、この内で一意である必要があります<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />間<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />関係のない型を含む型。</span><span class="sxs-lookup"><span data-stu-id="742c8-109">This name must be unique in this <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> across <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> types, including unrelated types.</span></span>
            </param>
        <summary>
            <span data-ttu-id="742c8-110">取得、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定された型の<typeparamref name="T" />と、指定した名前が存在する場合、または 1 つ作成が既に存在しない場合は、それを取得します。</span><span class="sxs-lookup"><span data-stu-id="742c8-110">Gets an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> of the given type <typeparamref name="T" /> and with the given name if it exists, or creates one and returns it if it doesn't already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="742c8-111">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="742c8-111">Task that represents the asynchronous operation.</span></span> <span data-ttu-id="742c8-112">タスクの結果は、信頼性の高い状態のインスタンスです。</span><span class="sxs-lookup"><span data-stu-id="742c8-112">The task result is the reliable state instance.</span></span></returns>
        <remarks>
            <span data-ttu-id="742c8-113">これは、分割不可能な操作です。</span><span class="sxs-lookup"><span data-stu-id="742c8-113">This is an atomic operation.</span></span> <span data-ttu-id="742c8-114">ときに、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />を作成する必要がありますまたはいずれかを完了し、正常に戻り、作成できません。</span><span class="sxs-lookup"><span data-stu-id="742c8-114">When an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> needs to be created, it will either complete and return successfully or it will not be created.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="742c8-115"><paramref name="name" /> が null です。</span><span class="sxs-lookup"><span data-stu-id="742c8-115"><paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="742c8-116">型のインスタンス<typeparamref name="T" />を作成できないか、既存の<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />インスタンスの型ではありません<typeparamref name="T" />です。</span><span class="sxs-lookup"><span data-stu-id="742c8-116">An instance of the type <typeparamref name="T" /> cannot be created, or the existing <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> instance is not of type <typeparamref name="T" />.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="742c8-117">既定のタイムアウト以内に完了する操作が失敗しました。</span><span class="sxs-lookup"><span data-stu-id="742c8-117">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="742c8-118">場合にスローされる、<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="742c8-118">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in  <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="742c8-119">信頼性の高い状態マネージャーが閉じていることを示します。</span><span class="sxs-lookup"><span data-stu-id="742c8-119">Indicates that the Reliable State Manager is closed.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="742c8-120">操作は、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="742c8-120">The operation has been internally faulted by the system.</span></span> <span data-ttu-id="742c8-121">操作をやり直してください。</span><span class="sxs-lookup"><span data-stu-id="742c8-121">Retry the operation</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetOrAddAsync&lt;T&gt; (Uri name) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetOrAddAsync(Of T As IReliableState) (name As Uri) As Task(Of T)" />
      <MemberSignature Language="F#" Value="abstract member GetOrAddAsync : Uri -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)&gt; (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)" Usage="iReliableStateManager.GetOrAddAsync name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="742c8-122">指定する場合、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />型、クラス型またはインターフェイス型のいずれかを要求することがあります。</span><span class="sxs-lookup"><span data-stu-id="742c8-122">When specifying the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> type, you may ask for either a class type or an interface type.</span></span>
            <span data-ttu-id="742c8-123"><para>クラスの種類を指定する場合、システムはその型のインスタンスを返すしようとします。その型のインスタンスをインスタンス化できない場合 (抽象クラス、適切なコンス トラクターがないなど)、ArgumentException をスローします。</para><para>インターフェイス型を指定すると、マネージャーは具象型にインターフェイスを解決しようとします。型のマッピングが、ユーザーが指定されている場合、このメソッドは、(サポートされていない) 型を解決するのには、ユーザー指定のマッピングが使用されます。型のマッピングが、ユーザーが指定されていない場合、このメソッドは指定されたインターフェイスの既定の実装を選択します。指定されたインターフェイス型には、既定の実装はありません。 または型のユーザー指定のマッピングが指定されていない、種類が無効、このメソッドは ArgumentException をスローします。</para></span><span class="sxs-lookup"><span data-stu-id="742c8-123"><para> If specifying a class type, the system will attempt to return an instance of that type. If an instance of that type cannot be instantiated (e.g., abstract class, no suitable constructor), an ArgumentException is thrown. </para><para> If specifying an interface type, the manager will attempt to resolve the interface to a concrete type. If type mapping is specified by the user, this method will use the user-specified mapping to resolve the type (not yet supported). If type mapping is not specified by the user this method will select the default implementation for the interface given. If the given interface type does not have a default implementation, or a user-specified mapping for the type is not provided or the type is invalid, this method will throw ArgumentException. </para></span></span></typeparam>
        <param name="name">
            <span data-ttu-id="742c8-124"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。</span><span class="sxs-lookup"><span data-stu-id="742c8-124">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span></span> <span data-ttu-id="742c8-125">この名前は、この内で一意である必要があります<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />間<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />関係のない型を含む型。</span><span class="sxs-lookup"><span data-stu-id="742c8-125">This name must be unique in this <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> across <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> types, including unrelated types.</span></span>
            </param>
        <summary>
            <span data-ttu-id="742c8-126">取得、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定された型の<typeparamref name="T" />と、指定した名前が存在する場合、または 1 つ作成が既に存在しない場合は、それを取得します。</span><span class="sxs-lookup"><span data-stu-id="742c8-126">Gets an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> of the given type <typeparamref name="T" /> and with the given name if it exists, or creates one and returns it if it doesn't already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="742c8-127">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="742c8-127">Task that represents the asynchronous operation.</span></span> <span data-ttu-id="742c8-128">タスクの結果は、信頼性の高い状態のインスタンスです。</span><span class="sxs-lookup"><span data-stu-id="742c8-128">The task result is the reliable state instance.</span></span></returns>
        <remarks>
            <span data-ttu-id="742c8-129">これは、分割不可能な操作です。</span><span class="sxs-lookup"><span data-stu-id="742c8-129">This is an atomic operation.</span></span> <span data-ttu-id="742c8-130">ときに、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />を作成する必要がありますまたはいずれかを完了し、正常に戻り、作成できません。</span><span class="sxs-lookup"><span data-stu-id="742c8-130">When an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> needs to be created, it will either complete and return successfully or it will not be created.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="742c8-131"><paramref name="name" /> が null です。</span><span class="sxs-lookup"><span data-stu-id="742c8-131"><paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="742c8-132">型のインスタンス<typeparamref name="T" />を作成できないか、既存の<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />インスタンスの型ではありません<typeparamref name="T" />です。</span><span class="sxs-lookup"><span data-stu-id="742c8-132">An instance of the type <typeparamref name="T" /> cannot be created, or the existing <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> instance is not of type <typeparamref name="T" />.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="742c8-133">既定のタイムアウト以内に完了する操作が失敗しました。</span><span class="sxs-lookup"><span data-stu-id="742c8-133">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="742c8-134">場合にスローされる、<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="742c8-134">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in  <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="742c8-135">信頼性の高い状態マネージャーが閉じていることを示します。</span><span class="sxs-lookup"><span data-stu-id="742c8-135">Indicates that the Reliable State Manager is closed.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="742c8-136">操作は、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="742c8-136">The operation has been internally faulted by the system.</span></span> <span data-ttu-id="742c8-137">操作をやり直してください。</span><span class="sxs-lookup"><span data-stu-id="742c8-137">Retry the operation</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetOrAddAsync&lt;T&gt; (Microsoft.ServiceFabric.Data.ITransaction tx, string name) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class Microsoft.ServiceFabric.Data.ITransaction tx, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(Microsoft.ServiceFabric.Data.ITransaction,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetOrAddAsync(Of T As IReliableState) (tx As ITransaction, name As String) As Task(Of T)" />
      <MemberSignature Language="F#" Value="abstract member GetOrAddAsync : Microsoft.ServiceFabric.Data.ITransaction * string -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)&gt; (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)" Usage="iReliableStateManager.GetOrAddAsync (tx, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="742c8-138">指定する場合、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />型、クラス型またはインターフェイス型のいずれかを要求することがあります。</span><span class="sxs-lookup"><span data-stu-id="742c8-138">When specifying the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> type, you may ask for either a class type or an interface type.</span></span>
            <span data-ttu-id="742c8-139"><para>クラスの種類を指定する場合、システムはその型のインスタンスを返すしようとします。その型のインスタンスをインスタンス化できない場合 (抽象クラス、適切なコンス トラクターがないなど)、ArgumentException をスローします。</para><para>インターフェイス型を指定すると、マネージャーは具象型にインターフェイスを解決しようとします。型のマッピングが、ユーザーが指定されている場合、このメソッドは、(サポートされていない) 型を解決するのには、ユーザー指定のマッピングが使用されます。型のマッピングが、ユーザーが指定されていない場合、このメソッドは指定されたインターフェイスの既定の実装を選択します。指定されたインターフェイス型には、既定の実装はありません。 または型のユーザー指定のマッピングが指定されていない、種類が無効、このメソッドは ArgumentException をスローします。</para></span><span class="sxs-lookup"><span data-stu-id="742c8-139"><para> If specifying a class type, the system will attempt to return an instance of that type. If an instance of that type cannot be instantiated (e.g., abstract class, no suitable constructor), an ArgumentException is thrown. </para><para> If specifying an interface type, the manager will attempt to resolve the interface to a concrete type. If type mapping is specified by the user, this method will use the user-specified mapping to resolve the type (not yet supported). If type mapping is not specified by the user this method will select the default implementation for the interface given. If the given interface type does not have a default implementation, or a user-specified mapping for the type is not provided or the type is invalid, this method will throw ArgumentException. </para></span></span></typeparam>
        <param name="tx"><span data-ttu-id="742c8-140">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="742c8-140">Transaction to associate this operation with.</span></span></param>
        <param name="name">
            <span data-ttu-id="742c8-141"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。</span><span class="sxs-lookup"><span data-stu-id="742c8-141">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span></span> <span data-ttu-id="742c8-142">この名前は、この内で一意である必要があります<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />間<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />関係のない型を含む型。</span><span class="sxs-lookup"><span data-stu-id="742c8-142">This name must be unique in this <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> across <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> types, including unrelated types.</span></span>
            </param>
        <summary>
            <span data-ttu-id="742c8-143">取得、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定された型の<typeparamref name="T" />と、指定した名前が存在する場合、または 1 つ作成が既に存在しない場合は、それを取得します。</span><span class="sxs-lookup"><span data-stu-id="742c8-143">Gets an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> of the given type <typeparamref name="T" /> and with the given name if it exists, or creates one and returns it if it doesn't already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="742c8-144">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="742c8-144">Task that represents the asynchronous operation.</span></span> <span data-ttu-id="742c8-145">タスクの結果は、信頼性の高い状態のインスタンスです。</span><span class="sxs-lookup"><span data-stu-id="742c8-145">The task result is the reliable state instance.</span></span></returns>
        <remarks>
            <span data-ttu-id="742c8-146">これは、分割不可能な操作です。</span><span class="sxs-lookup"><span data-stu-id="742c8-146">This is an atomic operation.</span></span> <span data-ttu-id="742c8-147">ときに、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />を作成する必要がありますまたはいずれかを完了し、正常に戻り、作成できません。</span><span class="sxs-lookup"><span data-stu-id="742c8-147">When an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> needs to be created, it will either complete and return successfully or it will not be created.</span></span> <span data-ttu-id="742c8-148">このメソッドは、例外をスローする場合は、トランザクションが中止する必要があります。</span><span class="sxs-lookup"><span data-stu-id="742c8-148">If this method throws an exception, the transaction must be aborted.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="742c8-149"><paramref name="tx" />null、または<paramref name="name" />が null です。</span><span class="sxs-lookup"><span data-stu-id="742c8-149"><paramref name="tx" /> is null, or <paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="742c8-150">型のインスタンス<typeparamref name="T" />を作成できないか、既存の<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />インスタンスの型ではありません<typeparamref name="T" />です。</span><span class="sxs-lookup"><span data-stu-id="742c8-150">An instance of the type <typeparamref name="T" /> cannot be created, or the existing <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> instance is not of type <typeparamref name="T" />.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="742c8-151">既定のタイムアウト以内に完了する操作が失敗しました。</span><span class="sxs-lookup"><span data-stu-id="742c8-151">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="742c8-152">場合にスローされる、<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="742c8-152">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in  <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="742c8-153">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="742c8-153">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="742c8-154">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="742c8-154">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="742c8-155">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="742c8-155">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="742c8-156">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="742c8-156">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="742c8-157">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="742c8-157">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="742c8-158">信頼性の高い状態マネージャーが閉じていることを示します。</span><span class="sxs-lookup"><span data-stu-id="742c8-158">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetOrAddAsync&lt;T&gt; (Microsoft.ServiceFabric.Data.ITransaction tx, Uri name) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class Microsoft.ServiceFabric.Data.ITransaction tx, class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(Microsoft.ServiceFabric.Data.ITransaction,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetOrAddAsync(Of T As IReliableState) (tx As ITransaction, name As Uri) As Task(Of T)" />
      <MemberSignature Language="F#" Value="abstract member GetOrAddAsync : Microsoft.ServiceFabric.Data.ITransaction * Uri -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)&gt; (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)" Usage="iReliableStateManager.GetOrAddAsync (tx, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="name" Type="System.Uri" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="742c8-159">指定する場合、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />型、クラス型またはインターフェイス型のいずれかを要求することがあります。</span><span class="sxs-lookup"><span data-stu-id="742c8-159">When specifying the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> type, you may ask for either a class type or an interface type.</span></span>
            <span data-ttu-id="742c8-160"><para>クラスの種類を指定する場合、システムはその型のインスタンスを返すしようとします。その型のインスタンスをインスタンス化できない場合 (抽象クラス、適切なコンス トラクターがないなど)、ArgumentException をスローします。</para><para>インターフェイス型を指定すると、マネージャーは具象型にインターフェイスを解決しようとします。型のマッピングが、ユーザーが指定されている場合、このメソッドは、(サポートされていない) 型を解決するのには、ユーザー指定のマッピングが使用されます。型のマッピングが、ユーザーが指定されていない場合、このメソッドは指定されたインターフェイスの既定の実装を選択します。指定されたインターフェイス型には、既定の実装はありません。 または型のユーザー指定のマッピングが指定されていない、種類が無効、このメソッドは ArgumentException をスローします。</para></span><span class="sxs-lookup"><span data-stu-id="742c8-160"><para> If specifying a class type, the system will attempt to return an instance of that type. If an instance of that type cannot be instantiated (e.g., abstract class, no suitable constructor), an ArgumentException is thrown. </para><para> If specifying an interface type, the manager will attempt to resolve the interface to a concrete type. If type mapping is specified by the user, this method will use the user-specified mapping to resolve the type (not yet supported). If type mapping is not specified by the user this method will select the default implementation for the interface given. If the given interface type does not have a default implementation, or a user-specified mapping for the type is not provided or the type is invalid, this method will throw ArgumentException. </para></span></span></typeparam>
        <param name="tx"><span data-ttu-id="742c8-161">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="742c8-161">Transaction to associate this operation with.</span></span></param>
        <param name="name">
            <span data-ttu-id="742c8-162"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。</span><span class="sxs-lookup"><span data-stu-id="742c8-162">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span></span> <span data-ttu-id="742c8-163">この名前は、この内で一意である必要があります<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />間<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />関係のない型を含む型。</span><span class="sxs-lookup"><span data-stu-id="742c8-163">This name must be unique in this <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> across <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> types, including unrelated types.</span></span>
            </param>
        <summary>
            <span data-ttu-id="742c8-164">取得、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定された型の<typeparamref name="T" />と、指定した名前が存在する場合、または 1 つ作成が既に存在しない場合は、それを取得します。</span><span class="sxs-lookup"><span data-stu-id="742c8-164">Gets an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> of the given type <typeparamref name="T" /> and with the given name if it exists, or creates one and returns it if it doesn't already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="742c8-165">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="742c8-165">Task that represents the asynchronous operation.</span></span> <span data-ttu-id="742c8-166">タスクの結果は、信頼性の高い状態のインスタンスです。</span><span class="sxs-lookup"><span data-stu-id="742c8-166">The task result is the reliable state instance.</span></span></returns>
        <remarks>
            <span data-ttu-id="742c8-167">これは、分割不可能な操作です。</span><span class="sxs-lookup"><span data-stu-id="742c8-167">This is an atomic operation.</span></span> <span data-ttu-id="742c8-168">ときに、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />を作成する必要がありますまたはいずれかを完了し、正常に戻り、作成できません。</span><span class="sxs-lookup"><span data-stu-id="742c8-168">When an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> needs to be created, it will either complete and return successfully or it will not be created.</span></span> <span data-ttu-id="742c8-169">このメソッドは、例外をスローする場合は、トランザクションが中止する必要があります。</span><span class="sxs-lookup"><span data-stu-id="742c8-169">If this method throws an exception, the transaction must be aborted.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="742c8-170"><paramref name="tx" />null、または<paramref name="name" />が null です。</span><span class="sxs-lookup"><span data-stu-id="742c8-170"><paramref name="tx" /> is null, or <paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="742c8-171">型のインスタンス<typeparamref name="T" />を作成できないか、既存の<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />インスタンスの型ではありません<typeparamref name="T" />です。</span><span class="sxs-lookup"><span data-stu-id="742c8-171">An instance of the type <typeparamref name="T" /> cannot be created, or the existing <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> instance is not of type <typeparamref name="T" />.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="742c8-172">既定のタイムアウト以内に完了する操作が失敗しました。</span><span class="sxs-lookup"><span data-stu-id="742c8-172">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="742c8-173">場合にスローされる、<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="742c8-173">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in  <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="742c8-174">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="742c8-174">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="742c8-175">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="742c8-175">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="742c8-176">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="742c8-176">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="742c8-177">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="742c8-177">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="742c8-178">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="742c8-178">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="742c8-179">信頼性の高い状態マネージャーが閉じていることを示します。</span><span class="sxs-lookup"><span data-stu-id="742c8-179">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetOrAddAsync&lt;T&gt; (string name, TimeSpan timeout) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(string name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetOrAddAsync(Of T As IReliableState) (name As String, timeout As TimeSpan) As Task(Of T)" />
      <MemberSignature Language="F#" Value="abstract member GetOrAddAsync : string * TimeSpan -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)&gt; (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)" Usage="iReliableStateManager.GetOrAddAsync (name, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="742c8-180">指定する場合、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />型、クラス型またはインターフェイス型のいずれかを要求することがあります。</span><span class="sxs-lookup"><span data-stu-id="742c8-180">When specifying the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> type, you may ask for either a class type or an interface type.</span></span>
            <span data-ttu-id="742c8-181"><para>クラスの種類を指定する場合、システムはその型のインスタンスを返すしようとします。その型のインスタンスをインスタンス化できない場合 (抽象クラス、適切なコンス トラクターがないなど)、ArgumentException をスローします。</para><para>インターフェイス型を指定すると、マネージャーは具象型にインターフェイスを解決しようとします。型のマッピングが、ユーザーが指定されている場合、このメソッドは、(サポートされていない) 型を解決するのには、ユーザー指定のマッピングが使用されます。型のマッピングが、ユーザーが指定されていない場合、このメソッドは指定されたインターフェイスの既定の実装を選択します。指定されたインターフェイス型には、既定の実装はありません。 または型のユーザー指定のマッピングが指定されていない、種類が無効、このメソッドは ArgumentException をスローします。</para></span><span class="sxs-lookup"><span data-stu-id="742c8-181"><para> If specifying a class type, the system will attempt to return an instance of that type. If an instance of that type cannot be instantiated (e.g., abstract class, no suitable constructor), an ArgumentException is thrown. </para><para> If specifying an interface type, the manager will attempt to resolve the interface to a concrete type. If type mapping is specified by the user, this method will use the user-specified mapping to resolve the type (not yet supported). If type mapping is not specified by the user this method will select the default implementation for the interface given. If the given interface type does not have a default implementation, or a user-specified mapping for the type is not provided or the type is invalid, this method will throw ArgumentException. </para></span></span></typeparam>
        <param name="name">
            <span data-ttu-id="742c8-182"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。</span><span class="sxs-lookup"><span data-stu-id="742c8-182">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span></span> <span data-ttu-id="742c8-183">この名前は、この内で一意である必要があります<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />間<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />関係のない型を含む型。</span><span class="sxs-lookup"><span data-stu-id="742c8-183">This name must be unique in this <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> across <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> types, including unrelated types.</span></span>
            </param>
        <param name="timeout"><span data-ttu-id="742c8-184">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。</span><span class="sxs-lookup"><span data-stu-id="742c8-184">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="742c8-185">主にデッドロックを防ぐために使用します。</span><span class="sxs-lookup"><span data-stu-id="742c8-185">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="742c8-186">既定では 4 秒です。</span><span class="sxs-lookup"><span data-stu-id="742c8-186">The default is 4 seconds.</span></span></param>
        <summary>
            <span data-ttu-id="742c8-187">取得、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定された型の<typeparamref name="T" />と、指定した名前が存在する場合、または 1 つ作成が既に存在しない場合は、それを取得します。</span><span class="sxs-lookup"><span data-stu-id="742c8-187">Gets an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> of the given type <typeparamref name="T" /> and with the given name if it exists, or creates one and returns it if it doesn't already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="742c8-188">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="742c8-188">Task that represents the asynchronous operation.</span></span> <span data-ttu-id="742c8-189">タスクの結果は、信頼性の高い状態のインスタンスです。</span><span class="sxs-lookup"><span data-stu-id="742c8-189">The task result is the reliable state instance.</span></span></returns>
        <remarks>
            <span data-ttu-id="742c8-190">これは、分割不可能な操作です。</span><span class="sxs-lookup"><span data-stu-id="742c8-190">This is an atomic operation.</span></span> <span data-ttu-id="742c8-191">ときに、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />を作成する必要がありますまたはいずれかを完了し、正常に戻り、作成できません。</span><span class="sxs-lookup"><span data-stu-id="742c8-191">When an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> needs to be created, it will either complete and return successfully or it will not be created.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="742c8-192"><paramref name="name" /> が null です。</span><span class="sxs-lookup"><span data-stu-id="742c8-192"><paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="742c8-193">型のインスタンス<typeparamref name="T" />を作成できない既存または<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />インスタンスの型ではありません<typeparamref name="T" />、または<paramref name="timeout" />が負の値。</span><span class="sxs-lookup"><span data-stu-id="742c8-193">An instance of the type <typeparamref name="T" /> cannot be created, or the existing <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> instance is not of type <typeparamref name="T" />, or <paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="742c8-194">操作は、指定したタイムアウト時間内に完了できませんでした。</span><span class="sxs-lookup"><span data-stu-id="742c8-194">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="742c8-195">場合にスローされる、<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="742c8-195">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in  <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="742c8-196">信頼性の高い状態マネージャーが閉じていることを示します。</span><span class="sxs-lookup"><span data-stu-id="742c8-196">Indicates that the Reliable State Manager is closed.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="742c8-197">操作は、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="742c8-197">The operation has been internally faulted by the system.</span></span> <span data-ttu-id="742c8-198">操作をやり直してください。</span><span class="sxs-lookup"><span data-stu-id="742c8-198">Retry the operation</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetOrAddAsync&lt;T&gt; (Uri name, TimeSpan timeout) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class System.Uri name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(System.Uri,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetOrAddAsync(Of T As IReliableState) (name As Uri, timeout As TimeSpan) As Task(Of T)" />
      <MemberSignature Language="F#" Value="abstract member GetOrAddAsync : Uri * TimeSpan -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)&gt; (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)" Usage="iReliableStateManager.GetOrAddAsync (name, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="742c8-199">指定する場合、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />型、クラス型またはインターフェイス型のいずれかを要求することがあります。</span><span class="sxs-lookup"><span data-stu-id="742c8-199">When specifying the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> type, you may ask for either a class type or an interface type.</span></span>
            <span data-ttu-id="742c8-200"><para>クラスの種類を指定する場合、システムはその型のインスタンスを返すしようとします。その型のインスタンスをインスタンス化できない場合 (抽象クラス、適切なコンス トラクターがないなど)、ArgumentException をスローします。</para><para>インターフェイス型を指定すると、マネージャーは具象型にインターフェイスを解決しようとします。型のマッピングが、ユーザーが指定されている場合、このメソッドは、(サポートされていない) 型を解決するのには、ユーザー指定のマッピングが使用されます。型のマッピングが、ユーザーが指定されていない場合、このメソッドは指定されたインターフェイスの既定の実装を選択します。指定されたインターフェイス型には、既定の実装はありません。 または型のユーザー指定のマッピングが指定されていない、種類が無効、このメソッドは ArgumentException をスローします。</para></span><span class="sxs-lookup"><span data-stu-id="742c8-200"><para> If specifying a class type, the system will attempt to return an instance of that type. If an instance of that type cannot be instantiated (e.g., abstract class, no suitable constructor), an ArgumentException is thrown. </para><para> If specifying an interface type, the manager will attempt to resolve the interface to a concrete type. If type mapping is specified by the user, this method will use the user-specified mapping to resolve the type (not yet supported). If type mapping is not specified by the user this method will select the default implementation for the interface given. If the given interface type does not have a default implementation, or a user-specified mapping for the type is not provided or the type is invalid, this method will throw ArgumentException. </para></span></span></typeparam>
        <param name="name">
            <span data-ttu-id="742c8-201"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。</span><span class="sxs-lookup"><span data-stu-id="742c8-201">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span></span> <span data-ttu-id="742c8-202">この名前は、この内で一意である必要があります<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />間<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />関係のない型を含む型。</span><span class="sxs-lookup"><span data-stu-id="742c8-202">This name must be unique in this <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> across <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> types, including unrelated types.</span></span>
            </param>
        <param name="timeout"><span data-ttu-id="742c8-203">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。</span><span class="sxs-lookup"><span data-stu-id="742c8-203">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="742c8-204">主にデッドロックを防ぐために使用します。</span><span class="sxs-lookup"><span data-stu-id="742c8-204">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="742c8-205">既定では 4 秒です。</span><span class="sxs-lookup"><span data-stu-id="742c8-205">The default is 4 seconds.</span></span></param>
        <summary>
            <span data-ttu-id="742c8-206">取得、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定された型の<typeparamref name="T" />と、指定した名前が存在する場合、または 1 つ作成が既に存在しない場合は、それを取得します。</span><span class="sxs-lookup"><span data-stu-id="742c8-206">Gets an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> of the given type <typeparamref name="T" /> and with the given name if it exists, or creates one and returns it if it doesn't already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="742c8-207">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="742c8-207">Task that represents the asynchronous operation.</span></span> <span data-ttu-id="742c8-208">タスクの結果は、信頼性の高い状態のインスタンスです。</span><span class="sxs-lookup"><span data-stu-id="742c8-208">The task result is the reliable state instance.</span></span></returns>
        <remarks>
            <span data-ttu-id="742c8-209">これは、分割不可能な操作です。</span><span class="sxs-lookup"><span data-stu-id="742c8-209">This is an atomic operation.</span></span> <span data-ttu-id="742c8-210">ときに、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />を作成する必要がありますまたはいずれかを完了し、正常に戻り、作成できません。</span><span class="sxs-lookup"><span data-stu-id="742c8-210">When an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> needs to be created, it will either complete and return successfully or it will not be created.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="742c8-211"><paramref name="name" /> が null です。</span><span class="sxs-lookup"><span data-stu-id="742c8-211"><paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="742c8-212">型のインスタンス<typeparamref name="T" />を作成できない既存または<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />インスタンスの型ではありません<typeparamref name="T" />、または<paramref name="timeout" />が負の値。</span><span class="sxs-lookup"><span data-stu-id="742c8-212">An instance of the type <typeparamref name="T" /> cannot be created, or the existing <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> instance is not of type <typeparamref name="T" />, or <paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="742c8-213">操作は、指定したタイムアウト時間内に完了できませんでした。</span><span class="sxs-lookup"><span data-stu-id="742c8-213">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="742c8-214">場合にスローされる、<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="742c8-214">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in  <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="742c8-215">信頼性の高い状態マネージャーが閉じていることを示します。</span><span class="sxs-lookup"><span data-stu-id="742c8-215">Indicates that the Reliable State Manager is closed.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="742c8-216">操作は、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="742c8-216">The operation has been internally faulted by the system.</span></span> <span data-ttu-id="742c8-217">操作をやり直してください。</span><span class="sxs-lookup"><span data-stu-id="742c8-217">Retry the operation</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetOrAddAsync&lt;T&gt; (Microsoft.ServiceFabric.Data.ITransaction tx, string name, TimeSpan timeout) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class Microsoft.ServiceFabric.Data.ITransaction tx, string name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(Microsoft.ServiceFabric.Data.ITransaction,System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetOrAddAsync(Of T As IReliableState) (tx As ITransaction, name As String, timeout As TimeSpan) As Task(Of T)" />
      <MemberSignature Language="F#" Value="abstract member GetOrAddAsync : Microsoft.ServiceFabric.Data.ITransaction * string * TimeSpan -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)&gt; (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)" Usage="iReliableStateManager.GetOrAddAsync (tx, name, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="742c8-218">指定する場合、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />型、クラス型またはインターフェイス型のいずれかを要求することがあります。</span><span class="sxs-lookup"><span data-stu-id="742c8-218">When specifying the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> type, you may ask for either a class type or an interface type.</span></span>
            <span data-ttu-id="742c8-219"><para>クラスの種類を指定する場合、システムはその型のインスタンスを返すしようとします。その型のインスタンスをインスタンス化できない場合 (抽象クラス、適切なコンス トラクターがないなど)、ArgumentException をスローします。</para><para>インターフェイス型を指定すると、マネージャーは具象型にインターフェイスを解決しようとします。型のマッピングが、ユーザーが指定されている場合、このメソッドは、(サポートされていない) 型を解決するのには、ユーザー指定のマッピングが使用されます。型のマッピングが、ユーザーが指定されていない場合、このメソッドは指定されたインターフェイスの既定の実装を選択します。指定されたインターフェイス型には、既定の実装はありません。 または型のユーザー指定のマッピングが指定されていない、種類が無効、このメソッドは ArgumentException をスローします。</para></span><span class="sxs-lookup"><span data-stu-id="742c8-219"><para> If specifying a class type, the system will attempt to return an instance of that type. If an instance of that type cannot be instantiated (e.g., abstract class, no suitable constructor), an ArgumentException is thrown. </para><para> If specifying an interface type, the manager will attempt to resolve the interface to a concrete type. If type mapping is specified by the user, this method will use the user-specified mapping to resolve the type (not yet supported). If type mapping is not specified by the user this method will select the default implementation for the interface given. If the given interface type does not have a default implementation, or a user-specified mapping for the type is not provided or the type is invalid, this method will throw ArgumentException. </para></span></span></typeparam>
        <param name="tx"><span data-ttu-id="742c8-220">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="742c8-220">Transaction to associate this operation with.</span></span></param>
        <param name="name">
            <span data-ttu-id="742c8-221"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。</span><span class="sxs-lookup"><span data-stu-id="742c8-221">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span></span> <span data-ttu-id="742c8-222">この名前は、この内で一意である必要があります<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />間<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />関係のない型を含む型。</span><span class="sxs-lookup"><span data-stu-id="742c8-222">This name must be unique in this <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> across <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> types, including unrelated types.</span></span>
            </param>
        <param name="timeout"><span data-ttu-id="742c8-223">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。</span><span class="sxs-lookup"><span data-stu-id="742c8-223">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="742c8-224">主にデッドロックを防ぐために使用します。</span><span class="sxs-lookup"><span data-stu-id="742c8-224">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="742c8-225">既定では 4 秒です。</span><span class="sxs-lookup"><span data-stu-id="742c8-225">The default is 4 seconds.</span></span></param>
        <summary>
            <span data-ttu-id="742c8-226">取得、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定された型の<typeparamref name="T" />と、指定した名前が存在する場合、または 1 つ作成が既に存在しない場合は、それを取得します。</span><span class="sxs-lookup"><span data-stu-id="742c8-226">Gets an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> of the given type <typeparamref name="T" /> and with the given name if it exists, or creates one and returns it if it doesn't already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="742c8-227">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="742c8-227">Task that represents the asynchronous operation.</span></span> <span data-ttu-id="742c8-228">タスクの結果は、信頼性の高い状態のインスタンスです。</span><span class="sxs-lookup"><span data-stu-id="742c8-228">The task result is the reliable state instance.</span></span></returns>
        <remarks>
            <span data-ttu-id="742c8-229">これは、分割不可能な操作です。</span><span class="sxs-lookup"><span data-stu-id="742c8-229">This is an atomic operation.</span></span> <span data-ttu-id="742c8-230">ときに、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />を作成する必要がありますまたはいずれかを完了し、正常に戻り、作成できません。</span><span class="sxs-lookup"><span data-stu-id="742c8-230">When an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> needs to be created, it will either complete and return successfully or it will not be created.</span></span> <span data-ttu-id="742c8-231">このメソッドは、例外をスローする場合は、トランザクションが中止する必要があります。</span><span class="sxs-lookup"><span data-stu-id="742c8-231">If this method throws an exception, the transaction must be aborted.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="742c8-232"><paramref name="tx" />null、または<paramref name="name" />が null です。</span><span class="sxs-lookup"><span data-stu-id="742c8-232"><paramref name="tx" /> is null, or <paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="742c8-233">型のインスタンス<typeparamref name="T" />を作成できない既存または<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />インスタンスの型ではありません<typeparamref name="T" />、または<paramref name="timeout" />が負の値。</span><span class="sxs-lookup"><span data-stu-id="742c8-233">An instance of the type <typeparamref name="T" /> cannot be created, or the existing <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> instance is not of type <typeparamref name="T" />, or <paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="742c8-234">操作は、指定したタイムアウト時間内に完了できませんでした。</span><span class="sxs-lookup"><span data-stu-id="742c8-234">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="742c8-235">場合にスローされる、<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="742c8-235">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in  <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="742c8-236">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="742c8-236">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="742c8-237">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="742c8-237">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="742c8-238">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="742c8-238">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="742c8-239">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="742c8-239">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="742c8-240">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="742c8-240">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="742c8-241">信頼性の高い状態マネージャーが閉じていることを示します。</span><span class="sxs-lookup"><span data-stu-id="742c8-241">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetOrAddAsync&lt;T&gt; (Microsoft.ServiceFabric.Data.ITransaction tx, Uri name, TimeSpan timeout) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class Microsoft.ServiceFabric.Data.ITransaction tx, class System.Uri name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(Microsoft.ServiceFabric.Data.ITransaction,System.Uri,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetOrAddAsync(Of T As IReliableState) (tx As ITransaction, name As Uri, timeout As TimeSpan) As Task(Of T)" />
      <MemberSignature Language="F#" Value="abstract member GetOrAddAsync : Microsoft.ServiceFabric.Data.ITransaction * Uri * TimeSpan -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)&gt; (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)" Usage="iReliableStateManager.GetOrAddAsync (tx, name, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="742c8-242">指定する場合、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />型、クラス型またはインターフェイス型のいずれかを要求することがあります。</span><span class="sxs-lookup"><span data-stu-id="742c8-242">When specifying the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> type, you may ask for either a class type or an interface type.</span></span>
            <span data-ttu-id="742c8-243"><para>クラスの種類を指定する場合、システムはその型のインスタンスを返すしようとします。その型のインスタンスをインスタンス化できない場合 (抽象クラス、適切なコンス トラクターがないなど)、ArgumentException をスローします。</para><para>インターフェイス型を指定すると、マネージャーは具象型にインターフェイスを解決しようとします。型のマッピングが、ユーザーが指定されている場合、このメソッドは、(サポートされていない) 型を解決するのには、ユーザー指定のマッピングが使用されます。型のマッピングが、ユーザーが指定されていない場合、このメソッドは指定されたインターフェイスの既定の実装を選択します。指定されたインターフェイス型には、既定の実装はありません。 または型のユーザー指定のマッピングが指定されていない、種類が無効、このメソッドは ArgumentException をスローします。</para></span><span class="sxs-lookup"><span data-stu-id="742c8-243"><para> If specifying a class type, the system will attempt to return an instance of that type. If an instance of that type cannot be instantiated (e.g., abstract class, no suitable constructor), an ArgumentException is thrown. </para><para> If specifying an interface type, the manager will attempt to resolve the interface to a concrete type. If type mapping is specified by the user, this method will use the user-specified mapping to resolve the type (not yet supported). If type mapping is not specified by the user this method will select the default implementation for the interface given. If the given interface type does not have a default implementation, or a user-specified mapping for the type is not provided or the type is invalid, this method will throw ArgumentException. </para></span></span></typeparam>
        <param name="tx"><span data-ttu-id="742c8-244">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="742c8-244">Transaction to associate this operation with.</span></span></param>
        <param name="name">
            <span data-ttu-id="742c8-245"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。</span><span class="sxs-lookup"><span data-stu-id="742c8-245">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span></span> <span data-ttu-id="742c8-246">この名前は、この内で一意である必要があります<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />間<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />関係のない型を含む型。</span><span class="sxs-lookup"><span data-stu-id="742c8-246">This name must be unique in this <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> across <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> types, including unrelated types.</span></span>
            </param>
        <param name="timeout"><span data-ttu-id="742c8-247">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。</span><span class="sxs-lookup"><span data-stu-id="742c8-247">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="742c8-248">主にデッドロックを防ぐために使用します。</span><span class="sxs-lookup"><span data-stu-id="742c8-248">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="742c8-249">既定では 4 秒です。</span><span class="sxs-lookup"><span data-stu-id="742c8-249">The default is 4 seconds.</span></span></param>
        <summary>
            <span data-ttu-id="742c8-250">取得、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定された型の<typeparamref name="T" />と、指定した名前が存在する場合、または 1 つ作成が既に存在しない場合は、それを取得します。</span><span class="sxs-lookup"><span data-stu-id="742c8-250">Gets an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> of the given type <typeparamref name="T" /> and with the given name if it exists, or creates one and returns it if it doesn't already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="742c8-251">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="742c8-251">Task that represents the asynchronous operation.</span></span> <span data-ttu-id="742c8-252">タスクの結果は、信頼性の高い状態のインスタンスです。</span><span class="sxs-lookup"><span data-stu-id="742c8-252">The task result is the reliable state instance.</span></span></returns>
        <remarks>
            <span data-ttu-id="742c8-253">これは、分割不可能な操作です。</span><span class="sxs-lookup"><span data-stu-id="742c8-253">This is an atomic operation.</span></span> <span data-ttu-id="742c8-254">ときに、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />を作成する必要がありますまたはいずれかを完了し、正常に戻り、作成できません。</span><span class="sxs-lookup"><span data-stu-id="742c8-254">When an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> needs to be created, it will either complete and return successfully or it will not be created.</span></span> <span data-ttu-id="742c8-255">このメソッドは、例外をスローする場合は、トランザクションが中止する必要があります。</span><span class="sxs-lookup"><span data-stu-id="742c8-255">If this method throws an exception, the transaction must be aborted.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="742c8-256"><paramref name="tx" />null、または<paramref name="name" />が null です。</span><span class="sxs-lookup"><span data-stu-id="742c8-256"><paramref name="tx" /> is null, or <paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="742c8-257">型のインスタンス<typeparamref name="T" />を作成できない既存または<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />インスタンスの型ではありません<typeparamref name="T" />、または<paramref name="timeout" />が負の値。</span><span class="sxs-lookup"><span data-stu-id="742c8-257">An instance of the type <typeparamref name="T" /> cannot be created, or the existing <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> instance is not of type <typeparamref name="T" />, or <paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="742c8-258">操作は、指定したタイムアウト時間内に完了できませんでした。</span><span class="sxs-lookup"><span data-stu-id="742c8-258">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="742c8-259">場合にスローされる、<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="742c8-259">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in  <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="742c8-260">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="742c8-260">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="742c8-261">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="742c8-261">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="742c8-262">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="742c8-262">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="742c8-263">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="742c8-263">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="742c8-264">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="742c8-264">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="742c8-265">信頼性の高い状態マネージャーが閉じていることを示します。</span><span class="sxs-lookup"><span data-stu-id="742c8-265">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveAsync (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveAsync(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveAsync (name As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member RemoveAsync : string -&gt; System.Threading.Tasks.Task" Usage="iReliableStateManager.RemoveAsync name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="742c8-266">削除する <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。</span><span class="sxs-lookup"><span data-stu-id="742c8-266">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> to remove.</span></span></param>
        <summary>
            <span data-ttu-id="742c8-267">削除、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />この状態マネージャーから指定した名前です。</span><span class="sxs-lookup"><span data-stu-id="742c8-267">Removes the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name from this state manager.</span></span> <span data-ttu-id="742c8-268">状態が永続的な記憶域およびすべてのレプリカから削除されます。</span><span class="sxs-lookup"><span data-stu-id="742c8-268">The state is permanently removed from persistent storage and all replicas.</span></span>
            </summary>
        <returns><span data-ttu-id="742c8-269">非同期の削除操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="742c8-269">Task that represents the asynchronous remove operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="742c8-270">これは、分割不可能な操作です。</span><span class="sxs-lookup"><span data-stu-id="742c8-270">This is an atomic operation.</span></span> <span data-ttu-id="742c8-271"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />と共にすべての状態が正常に削除される予定または整合性のままにします。</span><span class="sxs-lookup"><span data-stu-id="742c8-271">The <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> will be successfully removed along with all state or be left in-tact.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="742c8-272"><paramref name="name" /> が null です。</span><span class="sxs-lookup"><span data-stu-id="742c8-272"><paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="742c8-273"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定した名前がありません。</span><span class="sxs-lookup"><span data-stu-id="742c8-273">An <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name does not exist.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="742c8-274">既定のタイムアウト以内に完了する操作が失敗しました。</span><span class="sxs-lookup"><span data-stu-id="742c8-274">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="742c8-275">場合にスローされる、<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="742c8-275">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in  <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="742c8-276">信頼性の高い状態マネージャーが閉じていることを示します。</span><span class="sxs-lookup"><span data-stu-id="742c8-276">Indicates that the Reliable State Manager is closed.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="742c8-277">操作は、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="742c8-277">The operation has been internally faulted by the system.</span></span> <span data-ttu-id="742c8-278">操作をやり直してください。</span><span class="sxs-lookup"><span data-stu-id="742c8-278">Retry the operation</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveAsync (Uri name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveAsync(class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveAsync (name As Uri) As Task" />
      <MemberSignature Language="F#" Value="abstract member RemoveAsync : Uri -&gt; System.Threading.Tasks.Task" Usage="iReliableStateManager.RemoveAsync name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="742c8-279">削除する <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。</span><span class="sxs-lookup"><span data-stu-id="742c8-279">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> to remove.</span></span></param>
        <summary>
            <span data-ttu-id="742c8-280">削除、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />この状態マネージャーから指定した名前です。</span><span class="sxs-lookup"><span data-stu-id="742c8-280">Removes the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name from this state manager.</span></span> <span data-ttu-id="742c8-281">状態が永続的な記憶域およびすべてのレプリカから削除されます。</span><span class="sxs-lookup"><span data-stu-id="742c8-281">The state is permanently removed from persistent storage and all replicas.</span></span>
            </summary>
        <returns><span data-ttu-id="742c8-282">非同期の削除操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="742c8-282">Task that represents the asynchronous remove operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="742c8-283">これは、分割不可能な操作です。</span><span class="sxs-lookup"><span data-stu-id="742c8-283">This is an atomic operation.</span></span> <span data-ttu-id="742c8-284"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />と共にすべての状態が正常に削除される予定または整合性のままにします。</span><span class="sxs-lookup"><span data-stu-id="742c8-284">The <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> will be successfully removed along with all state or be left in-tact.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="742c8-285"><paramref name="name" /> が null です。</span><span class="sxs-lookup"><span data-stu-id="742c8-285"><paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="742c8-286"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定した名前がありません。</span><span class="sxs-lookup"><span data-stu-id="742c8-286">An <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name does not exist.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="742c8-287">既定のタイムアウト以内に完了する操作が失敗しました。</span><span class="sxs-lookup"><span data-stu-id="742c8-287">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="742c8-288">場合にスローされる、<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="742c8-288">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in  <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="742c8-289">信頼性の高い状態マネージャーが閉じていることを示します。</span><span class="sxs-lookup"><span data-stu-id="742c8-289">Indicates that the Reliable State Manager is closed.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="742c8-290">操作は、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="742c8-290">The operation has been internally faulted by the system.</span></span> <span data-ttu-id="742c8-291">操作をやり直してください。</span><span class="sxs-lookup"><span data-stu-id="742c8-291">Retry the operation</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveAsync (Microsoft.ServiceFabric.Data.ITransaction tx, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveAsync (tx As ITransaction, name As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member RemoveAsync : Microsoft.ServiceFabric.Data.ITransaction * string -&gt; System.Threading.Tasks.Task" Usage="iReliableStateManager.RemoveAsync (tx, name)" />
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
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="tx"><span data-ttu-id="742c8-292">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="742c8-292">Transaction to associate this operation with.</span></span></param>
        <param name="name"><span data-ttu-id="742c8-293">削除する <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。</span><span class="sxs-lookup"><span data-stu-id="742c8-293">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> to remove.</span></span></param>
        <summary>
            <span data-ttu-id="742c8-294">削除、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />この状態マネージャーから指定した名前です。</span><span class="sxs-lookup"><span data-stu-id="742c8-294">Removes the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name from this state manager.</span></span> <span data-ttu-id="742c8-295">トランザクションがコミットされるとき、状態は永続的な記憶域およびすべてのレプリカから削除されます。</span><span class="sxs-lookup"><span data-stu-id="742c8-295">The state is permanently removed from persistent storage and all replicas when the transaction is committed.</span></span>
            </summary>
        <returns><span data-ttu-id="742c8-296">非同期の削除操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="742c8-296">Task that represents the asynchronous remove operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="742c8-297">これは、分割不可能な操作です。</span><span class="sxs-lookup"><span data-stu-id="742c8-297">This is an atomic operation.</span></span> <span data-ttu-id="742c8-298"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />と共にすべての状態が正常に削除される予定または整合性のままにします。</span><span class="sxs-lookup"><span data-stu-id="742c8-298">The <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> will be successfully removed along with all state or be left in-tact.</span></span> <span data-ttu-id="742c8-299">このメソッドは、例外をスローする場合は、トランザクションが中止する必要があります。</span><span class="sxs-lookup"><span data-stu-id="742c8-299">If this method throws an exception, the transaction must be aborted.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="742c8-300"><paramref name="tx" />null、または<paramref name="name" />が null です。</span><span class="sxs-lookup"><span data-stu-id="742c8-300"><paramref name="tx" /> is null, or <paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="742c8-301"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定した名前がありません。</span><span class="sxs-lookup"><span data-stu-id="742c8-301">An <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name does not exist.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="742c8-302">既定のタイムアウト以内に完了する操作が失敗しました。</span><span class="sxs-lookup"><span data-stu-id="742c8-302">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="742c8-303">場合にスローされる、<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="742c8-303">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in  <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="742c8-304">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="742c8-304">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="742c8-305">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="742c8-305">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="742c8-306">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="742c8-306">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="742c8-307">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="742c8-307">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="742c8-308">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="742c8-308">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="742c8-309">信頼性の高い状態マネージャーが閉じていることを示します。</span><span class="sxs-lookup"><span data-stu-id="742c8-309">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveAsync (Microsoft.ServiceFabric.Data.ITransaction tx, Uri name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveAsync (tx As ITransaction, name As Uri) As Task" />
      <MemberSignature Language="F#" Value="abstract member RemoveAsync : Microsoft.ServiceFabric.Data.ITransaction * Uri -&gt; System.Threading.Tasks.Task" Usage="iReliableStateManager.RemoveAsync (tx, name)" />
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
        <Parameter Name="name" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="tx"><span data-ttu-id="742c8-310">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="742c8-310">Transaction to associate this operation with.</span></span></param>
        <param name="name"><span data-ttu-id="742c8-311">削除する <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。</span><span class="sxs-lookup"><span data-stu-id="742c8-311">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> to remove.</span></span></param>
        <summary>
            <span data-ttu-id="742c8-312">削除、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />この状態マネージャーから指定した名前です。</span><span class="sxs-lookup"><span data-stu-id="742c8-312">Removes the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name from this state manager.</span></span> <span data-ttu-id="742c8-313">トランザクションがコミットされるとき、状態は永続的な記憶域およびすべてのレプリカから削除されます。</span><span class="sxs-lookup"><span data-stu-id="742c8-313">The state is permanently removed from persistent storage and all replicas when the transaction is committed.</span></span>
            </summary>
        <returns><span data-ttu-id="742c8-314">非同期の削除操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="742c8-314">Task that represents the asynchronous remove operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="742c8-315">これは、分割不可能な操作です。</span><span class="sxs-lookup"><span data-stu-id="742c8-315">This is an atomic operation.</span></span> <span data-ttu-id="742c8-316"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />と共にすべての状態が正常に削除される予定または整合性のままにします。</span><span class="sxs-lookup"><span data-stu-id="742c8-316">The <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> will be successfully removed along with all state or be left in-tact.</span></span> <span data-ttu-id="742c8-317">このメソッドは、例外をスローする場合は、トランザクションが中止する必要があります。</span><span class="sxs-lookup"><span data-stu-id="742c8-317">If this method throws an exception, the transaction must be aborted.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="742c8-318"><paramref name="tx" />null、または<paramref name="name" />が null です。</span><span class="sxs-lookup"><span data-stu-id="742c8-318"><paramref name="tx" /> is null, or <paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="742c8-319"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定した名前がありません。</span><span class="sxs-lookup"><span data-stu-id="742c8-319">An <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name does not exist.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="742c8-320">既定のタイムアウト以内に完了する操作が失敗しました。</span><span class="sxs-lookup"><span data-stu-id="742c8-320">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="742c8-321">場合にスローされる、<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="742c8-321">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in  <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="742c8-322">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="742c8-322">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="742c8-323">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="742c8-323">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="742c8-324">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="742c8-324">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="742c8-325">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="742c8-325">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="742c8-326">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="742c8-326">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="742c8-327">信頼性の高い状態マネージャーが閉じていることを示します。</span><span class="sxs-lookup"><span data-stu-id="742c8-327">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveAsync (string name, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveAsync(string name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveAsync (name As String, timeout As TimeSpan) As Task" />
      <MemberSignature Language="F#" Value="abstract member RemoveAsync : string * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="iReliableStateManager.RemoveAsync (name, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="742c8-328">削除する <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。</span><span class="sxs-lookup"><span data-stu-id="742c8-328">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> to remove.</span></span></param>
        <param name="timeout"><span data-ttu-id="742c8-329">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。</span><span class="sxs-lookup"><span data-stu-id="742c8-329">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="742c8-330">主にデッドロックを防ぐために使用します。</span><span class="sxs-lookup"><span data-stu-id="742c8-330">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="742c8-331">既定では 4 秒です。</span><span class="sxs-lookup"><span data-stu-id="742c8-331">The default is 4 seconds.</span></span></param>
        <summary>
            <span data-ttu-id="742c8-332">削除、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />この状態マネージャーから指定した名前です。</span><span class="sxs-lookup"><span data-stu-id="742c8-332">Removes the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name from this state manager.</span></span> <span data-ttu-id="742c8-333">状態が永続的な記憶域およびすべてのレプリカから削除されます。</span><span class="sxs-lookup"><span data-stu-id="742c8-333">The state is permanently removed from persistent storage and all replicas.</span></span>
            </summary>
        <returns><span data-ttu-id="742c8-334">非同期の削除操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="742c8-334">Task that represents the asynchronous remove operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="742c8-335">これは、分割不可能な操作です。</span><span class="sxs-lookup"><span data-stu-id="742c8-335">This is an atomic operation.</span></span> <span data-ttu-id="742c8-336"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />と共にすべての状態が正常に削除される予定または整合性のままにします。</span><span class="sxs-lookup"><span data-stu-id="742c8-336">The <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> will be successfully removed along with all state or be left in-tact.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="742c8-337"><paramref name="name" /> が null です。</span><span class="sxs-lookup"><span data-stu-id="742c8-337"><paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="742c8-338"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定した名前が存在しないか、<paramref name="timeout" />が負の値。</span><span class="sxs-lookup"><span data-stu-id="742c8-338">An <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name does not exist, or <paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="742c8-339">操作は、指定したタイムアウト時間内に完了できませんでした。</span><span class="sxs-lookup"><span data-stu-id="742c8-339">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="742c8-340">場合にスローされる、<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="742c8-340">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in  <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="742c8-341">信頼性の高い状態マネージャーが閉じていることを示します。</span><span class="sxs-lookup"><span data-stu-id="742c8-341">Indicates that the Reliable State Manager is closed.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="742c8-342">操作は、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="742c8-342">The operation has been internally faulted by the system.</span></span> <span data-ttu-id="742c8-343">操作をやり直してください。</span><span class="sxs-lookup"><span data-stu-id="742c8-343">Retry the operation</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveAsync (Uri name, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveAsync(class System.Uri name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(System.Uri,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveAsync (name As Uri, timeout As TimeSpan) As Task" />
      <MemberSignature Language="F#" Value="abstract member RemoveAsync : Uri * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="iReliableStateManager.RemoveAsync (name, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="742c8-344">削除する <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。</span><span class="sxs-lookup"><span data-stu-id="742c8-344">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> to remove.</span></span></param>
        <param name="timeout"><span data-ttu-id="742c8-345">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。</span><span class="sxs-lookup"><span data-stu-id="742c8-345">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="742c8-346">主にデッドロックを防ぐために使用します。</span><span class="sxs-lookup"><span data-stu-id="742c8-346">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="742c8-347">既定では 4 秒です。</span><span class="sxs-lookup"><span data-stu-id="742c8-347">The default is 4 seconds.</span></span></param>
        <summary>
            <span data-ttu-id="742c8-348">削除、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />この状態マネージャーから指定した名前です。</span><span class="sxs-lookup"><span data-stu-id="742c8-348">Removes the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name from this state manager.</span></span> <span data-ttu-id="742c8-349">状態が永続的な記憶域およびすべてのレプリカから削除されます。</span><span class="sxs-lookup"><span data-stu-id="742c8-349">The state is permanently removed from persistent storage and all replicas.</span></span>
            </summary>
        <returns><span data-ttu-id="742c8-350">非同期の削除操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="742c8-350">Task that represents the asynchronous remove operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="742c8-351">これは、分割不可能な操作です。</span><span class="sxs-lookup"><span data-stu-id="742c8-351">This is an atomic operation.</span></span> <span data-ttu-id="742c8-352"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />と共にすべての状態が正常に削除される予定または整合性のままにします。</span><span class="sxs-lookup"><span data-stu-id="742c8-352">The <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> will be successfully removed along with all state or be left in-tact.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="742c8-353"><paramref name="name" /> が null です。</span><span class="sxs-lookup"><span data-stu-id="742c8-353"><paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="742c8-354"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定した名前が存在しないか、<paramref name="timeout" />が負の値。</span><span class="sxs-lookup"><span data-stu-id="742c8-354">An <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name does not exist, or <paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="742c8-355">操作は、指定したタイムアウト時間内に完了できませんでした。</span><span class="sxs-lookup"><span data-stu-id="742c8-355">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="742c8-356">場合にスローされる、<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="742c8-356">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in  <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="742c8-357">信頼性の高い状態マネージャーが閉じていることを示します。</span><span class="sxs-lookup"><span data-stu-id="742c8-357">Indicates that the Reliable State Manager is closed.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="742c8-358">操作は、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="742c8-358">The operation has been internally faulted by the system.</span></span> <span data-ttu-id="742c8-359">操作をやり直してください。</span><span class="sxs-lookup"><span data-stu-id="742c8-359">Retry the operation</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveAsync (Microsoft.ServiceFabric.Data.ITransaction tx, string name, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, string name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveAsync (tx As ITransaction, name As String, timeout As TimeSpan) As Task" />
      <MemberSignature Language="F#" Value="abstract member RemoveAsync : Microsoft.ServiceFabric.Data.ITransaction * string * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="iReliableStateManager.RemoveAsync (tx, name, timeout)" />
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
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="tx"><span data-ttu-id="742c8-360">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="742c8-360">Transaction to associate this operation with.</span></span></param>
        <param name="name"><span data-ttu-id="742c8-361">削除する <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。</span><span class="sxs-lookup"><span data-stu-id="742c8-361">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> to remove.</span></span></param>
        <param name="timeout"><span data-ttu-id="742c8-362">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。</span><span class="sxs-lookup"><span data-stu-id="742c8-362">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="742c8-363">主にデッドロックを防ぐために使用します。</span><span class="sxs-lookup"><span data-stu-id="742c8-363">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="742c8-364">既定では 4 秒です。</span><span class="sxs-lookup"><span data-stu-id="742c8-364">The default is 4 seconds.</span></span></param>
        <summary>
            <span data-ttu-id="742c8-365">削除、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />この状態マネージャーから指定した名前です。</span><span class="sxs-lookup"><span data-stu-id="742c8-365">Removes the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name from this state manager.</span></span> <span data-ttu-id="742c8-366">トランザクションがコミットされるとき、状態は永続的な記憶域およびすべてのレプリカから削除されます。</span><span class="sxs-lookup"><span data-stu-id="742c8-366">The state is permanently removed from persistent storage and all replicas when the transaction is committed.</span></span>
            </summary>
        <returns><span data-ttu-id="742c8-367">非同期の削除操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="742c8-367">Task that represents the asynchronous remove operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="742c8-368">これは、分割不可能な操作です。</span><span class="sxs-lookup"><span data-stu-id="742c8-368">This is an atomic operation.</span></span> <span data-ttu-id="742c8-369"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />と共にすべての状態が正常に削除される予定または整合性のままにします。</span><span class="sxs-lookup"><span data-stu-id="742c8-369">The <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> will be successfully removed along with all state or be left in-tact.</span></span> <span data-ttu-id="742c8-370">このメソッドは、例外をスローする場合は、トランザクションが中止する必要があります。</span><span class="sxs-lookup"><span data-stu-id="742c8-370">If this method throws an exception, the transaction must be aborted.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="742c8-371"><paramref name="tx" />null、または<paramref name="name" />が null です。</span><span class="sxs-lookup"><span data-stu-id="742c8-371"><paramref name="tx" /> is null, or <paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="742c8-372"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定した名前が存在しないか、<paramref name="timeout" />が負の値。</span><span class="sxs-lookup"><span data-stu-id="742c8-372">An <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name does not exist, or <paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="742c8-373">操作は、指定したタイムアウト時間内に完了できませんでした。</span><span class="sxs-lookup"><span data-stu-id="742c8-373">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="742c8-374">場合にスローされる、<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="742c8-374">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in  <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="742c8-375">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="742c8-375">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="742c8-376">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="742c8-376">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="742c8-377">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="742c8-377">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="742c8-378">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="742c8-378">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="742c8-379">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="742c8-379">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="742c8-380">信頼性の高い状態マネージャーが閉じていることを示します。</span><span class="sxs-lookup"><span data-stu-id="742c8-380">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveAsync (Microsoft.ServiceFabric.Data.ITransaction tx, Uri name, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, class System.Uri name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Uri,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveAsync (tx As ITransaction, name As Uri, timeout As TimeSpan) As Task" />
      <MemberSignature Language="F#" Value="abstract member RemoveAsync : Microsoft.ServiceFabric.Data.ITransaction * Uri * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="iReliableStateManager.RemoveAsync (tx, name, timeout)" />
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
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="tx"><span data-ttu-id="742c8-381">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="742c8-381">Transaction to associate this operation with.</span></span></param>
        <param name="name"><span data-ttu-id="742c8-382">削除する <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。</span><span class="sxs-lookup"><span data-stu-id="742c8-382">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> to remove.</span></span></param>
        <param name="timeout"><span data-ttu-id="742c8-383">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。</span><span class="sxs-lookup"><span data-stu-id="742c8-383">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="742c8-384">主にデッドロックを防ぐために使用します。</span><span class="sxs-lookup"><span data-stu-id="742c8-384">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="742c8-385">既定では 4 秒です。</span><span class="sxs-lookup"><span data-stu-id="742c8-385">The default is 4 seconds.</span></span></param>
        <summary>
            <span data-ttu-id="742c8-386">削除、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />この状態マネージャーから指定した名前です。</span><span class="sxs-lookup"><span data-stu-id="742c8-386">Removes the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name from this state manager.</span></span> <span data-ttu-id="742c8-387">トランザクションがコミットされるとき、状態は永続的な記憶域およびすべてのレプリカから削除されます。</span><span class="sxs-lookup"><span data-stu-id="742c8-387">The state is permanently removed from persistent storage and all replicas when the transaction is committed.</span></span>
            </summary>
        <returns><span data-ttu-id="742c8-388">非同期の削除操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="742c8-388">Task that represents the asynchronous remove operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="742c8-389">これは、分割不可能な操作です。</span><span class="sxs-lookup"><span data-stu-id="742c8-389">This is an atomic operation.</span></span> <span data-ttu-id="742c8-390"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />と共にすべての状態が正常に削除される予定または整合性のままにします。</span><span class="sxs-lookup"><span data-stu-id="742c8-390">The <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> will be successfully removed along with all state or be left in-tact.</span></span> <span data-ttu-id="742c8-391">このメソッドは、例外をスローする場合は、トランザクションが中止する必要があります。</span><span class="sxs-lookup"><span data-stu-id="742c8-391">If this method throws an exception, the transaction must be aborted.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="742c8-392"><paramref name="tx" />null、または<paramref name="name" />が null です。</span><span class="sxs-lookup"><span data-stu-id="742c8-392"><paramref name="tx" /> is null, or <paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="742c8-393"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定した名前が存在しないか、<paramref name="timeout" />が負の値。</span><span class="sxs-lookup"><span data-stu-id="742c8-393">An <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name does not exist, or <paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="742c8-394">操作は、指定したタイムアウト時間内に完了できませんでした。</span><span class="sxs-lookup"><span data-stu-id="742c8-394">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="742c8-395">場合にスローされる、<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="742c8-395">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in  <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="742c8-396">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="742c8-396">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="742c8-397">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="742c8-397">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="742c8-398">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="742c8-398">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="742c8-399">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="742c8-399">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="742c8-400">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="742c8-400">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="742c8-401">信頼性の高い状態マネージャーが閉じていることを示します。</span><span class="sxs-lookup"><span data-stu-id="742c8-401">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="StateManagerChanged">
      <MemberSignature Language="C#" Value="event EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs&gt; StateManagerChanged;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs&gt; StateManagerChanged" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceFabric.Data.IReliableStateManager.StateManagerChanged" />
      <MemberSignature Language="VB.NET" Value="Event StateManagerChanged As EventHandler(Of NotifyStateManagerChangedEventArgs) " />
      <MemberSignature Language="F#" Value="member this.StateManagerChanged : EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs&gt; " Usage="member this.StateManagerChanged : System.EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="742c8-402">状態マネージャーの状態が変更されたときに発生します。</span><span class="sxs-lookup"><span data-stu-id="742c8-402">Occurs when State Manager's state changes.</span></span>
            <span data-ttu-id="742c8-403">たとえば、作成または信頼性の高い状態の削除または信頼性の高い状態マネージャーを再構築します。</span><span class="sxs-lookup"><span data-stu-id="742c8-403">For example, creation or delete of reliable state or rebuild of the reliable state manager.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransactionChanged">
      <MemberSignature Language="C#" Value="event EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs&gt; TransactionChanged;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs&gt; TransactionChanged" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceFabric.Data.IReliableStateManager.TransactionChanged" />
      <MemberSignature Language="VB.NET" Value="Event TransactionChanged As EventHandler(Of NotifyTransactionChangedEventArgs) " />
      <MemberSignature Language="F#" Value="member this.TransactionChanged : EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs&gt; " Usage="member this.TransactionChanged : System.EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="742c8-404">トランザクションの状態が変更されたときに発生します。</span><span class="sxs-lookup"><span data-stu-id="742c8-404">Occurs when a transaction's state changes.</span></span>
            <span data-ttu-id="742c8-405">たとえば、トランザクションのコミットされます。</span><span class="sxs-lookup"><span data-stu-id="742c8-405">For example, commit of a transaction.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryAddStateSerializer&lt;T&gt;">
      <MemberSignature Language="C#" Value="public bool TryAddStateSerializer&lt;T&gt; (Microsoft.ServiceFabric.Data.IStateSerializer&lt;T&gt; stateSerializer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool TryAddStateSerializer&lt;T&gt;(class Microsoft.ServiceFabric.Data.IStateSerializer`1&lt;!!T&gt; stateSerializer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.TryAddStateSerializer``1(Microsoft.ServiceFabric.Data.IStateSerializer{``0})" />
      <MemberSignature Language="VB.NET" Value="Public Function TryAddStateSerializer(Of T) (stateSerializer As IStateSerializer(Of T)) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member TryAddStateSerializer : Microsoft.ServiceFabric.Data.IStateSerializer&lt;'T&gt; -&gt; bool" Usage="iReliableStateManager.TryAddStateSerializer stateSerializer" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="stateSerializer" Type="Microsoft.ServiceFabric.Data.IStateSerializer&lt;T&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="742c8-406">シリアル化および逆シリアル化される型。</span><span class="sxs-lookup"><span data-stu-id="742c8-406">Type that will be serialized and deserialized.</span></span></typeparam>
        <param name="stateSerializer">
            <span data-ttu-id="742c8-407">追加する状態シリアライザー。</span><span class="sxs-lookup"><span data-stu-id="742c8-407">The state serializer to be added.</span></span>
            </param>
        <summary>
            <span data-ttu-id="742c8-408">すべての信頼性の高いコレクションのカスタム シリアライザーを登録します。</span><span class="sxs-lookup"><span data-stu-id="742c8-408">Registers a custom serializer for all reliable collections.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="742c8-409">カスタムのシリアライザーが追加された場合は true。</span><span class="sxs-lookup"><span data-stu-id="742c8-409">True if the custom serializer was added.</span></span>
            <span data-ttu-id="742c8-410">指定した型のカスタムのシリアライザーが既に存在する場合は false です。</span><span class="sxs-lookup"><span data-stu-id="742c8-410">False if a custom serializer for the given type already exists.</span></span>
            </returns>
        <remarks>
          <para>
            <span data-ttu-id="742c8-411">信頼性の高いコレクションは、オブジェクトをシリアル化する必要があるとき、に、指定した型のシリアライザーを状態マネージャーを要求します。</span><span class="sxs-lookup"><span data-stu-id="742c8-411">When a reliable collection needs to serialize an object, it asks the state manager for a serializer for the given type.</span></span>
            <span data-ttu-id="742c8-412">状態マネージャーは、入力の型に対して登録されているカスタムのシリアライザーが最初に確認します。</span><span class="sxs-lookup"><span data-stu-id="742c8-412">The state manager will first check if there is a custom serializer registered for the input type.</span></span> <span data-ttu-id="742c8-413">ない場合は、ある型をシリアル化できるかどうかは組み込みのシリアライザーのいずれかを確認します。</span><span class="sxs-lookup"><span data-stu-id="742c8-413">If not, it will check if one of the built-in serializers can serialize the type.</span></span> <span data-ttu-id="742c8-414">状態マネージャーは、次の種類の組み込みのシリアライザー: guid、bool、byte、sbyte、char、decimal、float、int、uint、double、long、ulong、short、ushort、文字列です。</span><span class="sxs-lookup"><span data-stu-id="742c8-414">The state manager has built-in serializers for the following types: guid, bool, byte, sbyte, char, decimal, double, float, int, uint, long, ulong, short, ushort and string.</span></span> <span data-ttu-id="742c8-415">使用していない場合、<see cref="T:System.Runtime.Serialization.DataContractSerializer" />です。</span><span class="sxs-lookup"><span data-stu-id="742c8-415">If not, it will use <see cref="T:System.Runtime.Serialization.DataContractSerializer" />.</span></span>
            </para>
          <para>
            <span data-ttu-id="742c8-416">シリアライザーの forwards と backwards の互換性が無限にあります。</span><span class="sxs-lookup"><span data-stu-id="742c8-416">Serializers must be infinitely forwards and backwards compatible.</span></span> <span data-ttu-id="742c8-417">組み込みのシリアライザーを使用しているタイプの場合、Service Fabric が上位互換性と下位互換性を保証します。</span><span class="sxs-lookup"><span data-stu-id="742c8-417">For the types that are using built-in serializers, Service Fabric ensures forwards and backwards compatibility.</span></span> <span data-ttu-id="742c8-418">ただし、組み込みのシリアライザーと型のカスタムのシリアライザーが追加されると、カスタムのシリアライザーは、そのタイプの組み込みのシリアル化形式と互換性のあるする必要があります。</span><span class="sxs-lookup"><span data-stu-id="742c8-418">However, if a custom serializer is added for a type with a built-in serializer, the custom serializer must be compatible with the built-in serialization format for that type.</span></span>
            </para>
          <para>
            <span data-ttu-id="742c8-419">このメソッドは、ステートフル サービスのコンス トラクターから呼び出す必要があります。</span><span class="sxs-lookup"><span data-stu-id="742c8-419">This method should be called from the constructor of the Stateful Service.</span></span> <span data-ttu-id="742c8-420">これにより、信頼性の高いコレクションいるために必要なシリアライザー、保存した状態の回復が開始される前にします。</span><span class="sxs-lookup"><span data-stu-id="742c8-420">This ensures that the Reliable Collections have the necessary serializers before recovery of the persisted state begins.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGetAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt; TryGetAsync&lt;T&gt; (string name) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!!T&gt;&gt; TryGetAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.TryGetAsync``1(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryGetAsync(Of T As IReliableState) (name As String) As Task(Of ConditionalValue(Of T))" />
      <MemberSignature Language="F#" Value="abstract member TryGetAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;'T&gt;&gt; (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)" Usage="iReliableStateManager.TryGetAsync name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="742c8-421">型を指定する場合は、具象型またはインターフェイス型のいずれかを要求することがあります。</span><span class="sxs-lookup"><span data-stu-id="742c8-421">When specifying the type, you may ask for either a concrete type or an interface type.</span></span> <span data-ttu-id="742c8-422">取得したオブジェクトは、指定された型にキャストされます。</span><span class="sxs-lookup"><span data-stu-id="742c8-422">The retrieved object will be cast to the given type.</span></span>
            </typeparam>
        <param name="name">
            <span data-ttu-id="742c8-423"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。</span><span class="sxs-lookup"><span data-stu-id="742c8-423">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span></span> <span data-ttu-id="742c8-424">この名前は、この内で一意である必要があります<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />間<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />関係のない型を含む型。</span><span class="sxs-lookup"><span data-stu-id="742c8-424">This name must be unique in this <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> across <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> types, including unrelated types.</span></span>
            </param>
        <summary>
            <span data-ttu-id="742c8-425">取得を試みます、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定された型の<typeparamref name="T" />と指定した名前です。</span><span class="sxs-lookup"><span data-stu-id="742c8-425">Attempts to get an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> of the given type <typeparamref name="T" /> and with the given name.</span></span>
            </summary>
        <returns><span data-ttu-id="742c8-426">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="742c8-426">Task that represents the asynchronous operation.</span></span> <span data-ttu-id="742c8-427">タスクの結果は、信頼性の高い状態が見つかったかどうかを示す組とそのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="742c8-427">The task result is a tuple indicating whether the reliable state was found, and if so the instance.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="742c8-428"><paramref name="name" /> が null です。</span><span class="sxs-lookup"><span data-stu-id="742c8-428"><paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="742c8-429"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />インスタンスは型に変換できません<typeparamref name="T" />です。</span><span class="sxs-lookup"><span data-stu-id="742c8-429">The <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> instance is not convertible to type <typeparamref name="T" />.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            <span data-ttu-id="742c8-430">例外は、状態マネージャーに信頼性の高いコレクションを取得できないことを示します。</span><span class="sxs-lookup"><span data-stu-id="742c8-430">Exception indicates that the State Manager cannot retrive a reliable collection.</span></span>
            <span data-ttu-id="742c8-431"><see cref="T:System.Fabric.FabricNotReadableException" />すべてのページでスローされる可能性<see cref="T:System.Fabric.ReplicaRole" />s。</span><span class="sxs-lookup"><span data-stu-id="742c8-431"><see cref="T:System.Fabric.FabricNotReadableException" /> can be thrown in all <see cref="T:System.Fabric.ReplicaRole" />s.</span></span>
            <span data-ttu-id="742c8-432">たとえば、ときに、<see cref="F:System.Fabric.ReplicaRole.Primary" />または<see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />を失った<see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />です。</span><span class="sxs-lookup"><span data-stu-id="742c8-432">For example, when a <see cref="F:System.Fabric.ReplicaRole.Primary" /> or <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> looses <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span></span></exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="742c8-433">信頼性の高い状態マネージャーが閉じていることを示します。</span><span class="sxs-lookup"><span data-stu-id="742c8-433">Indicates that the Reliable State Manager is closed.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="742c8-434">操作は、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="742c8-434">The operation has been internally faulted by the system.</span></span> <span data-ttu-id="742c8-435">操作をやり直してください。</span><span class="sxs-lookup"><span data-stu-id="742c8-435">Retry the operation</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="TryGetAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt; TryGetAsync&lt;T&gt; (Uri name) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!!T&gt;&gt; TryGetAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.TryGetAsync``1(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryGetAsync(Of T As IReliableState) (name As Uri) As Task(Of ConditionalValue(Of T))" />
      <MemberSignature Language="F#" Value="abstract member TryGetAsync : Uri -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;'T&gt;&gt; (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)" Usage="iReliableStateManager.TryGetAsync name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="742c8-436">型を指定する場合は、具象型またはインターフェイス型のいずれかを要求することがあります。</span><span class="sxs-lookup"><span data-stu-id="742c8-436">When specifying the type, you may ask for either a concrete type or an interface type.</span></span> <span data-ttu-id="742c8-437">取得したオブジェクトは、指定された型にキャストされます。</span><span class="sxs-lookup"><span data-stu-id="742c8-437">The retrieved object will be cast to the given type.</span></span>
            </typeparam>
        <param name="name">
            <span data-ttu-id="742c8-438"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。</span><span class="sxs-lookup"><span data-stu-id="742c8-438">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span></span> <span data-ttu-id="742c8-439">この名前は、この内で一意である必要があります<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />間<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />関係のない型を含む型。</span><span class="sxs-lookup"><span data-stu-id="742c8-439">This name must be unique in this <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> across <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> types, including unrelated types.</span></span>
            </param>
        <summary>
            <span data-ttu-id="742c8-440">取得を試みます、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定された型の<typeparamref name="T" />と指定した名前です。</span><span class="sxs-lookup"><span data-stu-id="742c8-440">Attempts to get an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> of the given type <typeparamref name="T" /> and with the given name.</span></span>
            </summary>
        <returns><span data-ttu-id="742c8-441">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="742c8-441">Task that represents the asynchronous operation.</span></span> <span data-ttu-id="742c8-442">タスクの結果は、信頼性の高い状態が見つかったかどうかを示す組とそのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="742c8-442">The task result is a tuple indicating whether the reliable state was found, and if so the instance.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="742c8-443"><paramref name="name" /> が null です。</span><span class="sxs-lookup"><span data-stu-id="742c8-443"><paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="742c8-444"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />インスタンスは型に変換できません<typeparamref name="T" />です。</span><span class="sxs-lookup"><span data-stu-id="742c8-444">The <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> instance is not convertible to type <typeparamref name="T" />.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            <span data-ttu-id="742c8-445">例外は、状態マネージャーに信頼性の高いコレクションを取得できないことを示します。</span><span class="sxs-lookup"><span data-stu-id="742c8-445">Exception indicates that the State Manager cannot retrive a reliable collection.</span></span>
            <span data-ttu-id="742c8-446"><see cref="T:System.Fabric.FabricNotReadableException" />すべてのページでスローされる可能性<see cref="T:System.Fabric.ReplicaRole" />s。</span><span class="sxs-lookup"><span data-stu-id="742c8-446"><see cref="T:System.Fabric.FabricNotReadableException" /> can be thrown in all <see cref="T:System.Fabric.ReplicaRole" />s.</span></span>
            <span data-ttu-id="742c8-447">たとえば、ときに、<see cref="F:System.Fabric.ReplicaRole.Primary" />または<see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />を失った<see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />です。</span><span class="sxs-lookup"><span data-stu-id="742c8-447">For example, when a <see cref="F:System.Fabric.ReplicaRole.Primary" /> or <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> looses <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span></span></exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="742c8-448">信頼性の高い状態マネージャーが閉じていることを示します。</span><span class="sxs-lookup"><span data-stu-id="742c8-448">Indicates that the Reliable State Manager is closed.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="742c8-449">操作は、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="742c8-449">The operation has been internally faulted by the system.</span></span> <span data-ttu-id="742c8-450">操作をやり直してください。</span><span class="sxs-lookup"><span data-stu-id="742c8-450">Retry the operation</span></span></exception>
      </Docs>
    </Member>
  </Members>
</Type>