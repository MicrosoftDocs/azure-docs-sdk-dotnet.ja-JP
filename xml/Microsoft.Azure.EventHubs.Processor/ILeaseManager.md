<Type Name="ILeaseManager" FullName="Microsoft.Azure.EventHubs.Processor.ILeaseManager">
  <TypeSignature Language="C#" Value="public interface ILeaseManager" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ILeaseManager" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.Processor.ILeaseManager" />
  <TypeSignature Language="VB.NET" Value="Public Interface ILeaseManager" />
  <TypeSignature Language="F#" Value="type ILeaseManager = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
    <AssemblyVersion>1.0.1.0</AssemblyVersion>
    <AssemblyVersion>1.0.3.0</AssemblyVersion>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b6bef-101">EventProcessorHost リース Azure Storage 以外の場所を格納する場合は、このインターフェイスを使用して、独自のリース マネージャーを作成できます。</span><span class="sxs-lookup"><span data-stu-id="b6bef-101">If you wish to have EventProcessorHost store leases somewhere other than Azure Storage, you can write your own lease manager using this interface.</span></span>  
            
            <span data-ttu-id="b6bef-102"><para>Azure の記憶域マネージャーは、両方のインターフェイスは、同じクラスによって実装されて、リースと、チェックポイントの両方を同じ記憶域を使用します。自由に統一されたストアの両方の種類のデータがある場合は、同じ処理を行います。</para><para>お実装には、どのような情報を知ることがあるないために、このインターフェイスが初期化メソッドを指定できません。</para></span><span class="sxs-lookup"><span data-stu-id="b6bef-102"><para>The Azure Storage managers use the same storage for both lease and checkpoints, so both interfaces are implemented by the same class. You are free to do the same thing if you have a unified store for both types of data.</para><para>This interface does not specify initialization methods because we have no way of knowing what information your implementation will require.</para></span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AcquireLeaseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; AcquireLeaseAsync (Microsoft.Azure.EventHubs.Processor.Lease lease);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; AcquireLeaseAsync(class Microsoft.Azure.EventHubs.Processor.Lease lease) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ILeaseManager.AcquireLeaseAsync(Microsoft.Azure.EventHubs.Processor.Lease)" />
      <MemberSignature Language="F#" Value="abstract member AcquireLeaseAsync : Microsoft.Azure.EventHubs.Processor.Lease -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iLeaseManager.AcquireLeaseAsync lease" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lease" Type="Microsoft.Azure.EventHubs.Processor.Lease" />
      </Parameters>
      <Docs>
        <param name="lease"><span data-ttu-id="b6bef-103">既に GetLeaseAsync() から取得した適切なパーティションの情報をリース</span><span class="sxs-lookup"><span data-stu-id="b6bef-103">Lease info for the desired partition as previously obtained from GetLeaseAsync()</span></span></param>
        <summary>
            <span data-ttu-id="b6bef-104">この EventProcessorHost の適切なパーティションでリースを取得します。</span><span class="sxs-lookup"><span data-stu-id="b6bef-104">Acquire the lease on the desired partition for this EventProcessorHost.</span></span>
            
            <span data-ttu-id="b6bef-105"><para>別のホストによって既に所有されているリースを取得することに注意してください。リース スティー リングは、他のホストが開始されたときにパーティションが再配布方法です。</para></span><span class="sxs-lookup"><span data-stu-id="b6bef-105"><para>Note that it is legal to acquire a lease that is already owned by another host. Lease-stealing is how partitions are redistributed when additional hosts are started.</para></span></span></summary>
        <returns><span data-ttu-id="b6bef-106">リースは、その以外の場合は、正常に取得した場合は true。</span><span class="sxs-lookup"><span data-stu-id="b6bef-106">true if the lease was acquired successfully, false if not</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateLeaseIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Lease&gt; CreateLeaseIfNotExistsAsync (string partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.EventHubs.Processor.Lease&gt; CreateLeaseIfNotExistsAsync(string partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ILeaseManager.CreateLeaseIfNotExistsAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateLeaseIfNotExistsAsync (partitionId As String) As Task(Of Lease)" />
      <MemberSignature Language="F#" Value="abstract member CreateLeaseIfNotExistsAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Lease&gt;" Usage="iLeaseManager.CreateLeaseIfNotExistsAsync partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Lease&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partitionId"><span data-ttu-id="b6bef-107">リース情報を作成するパーティションの id</span><span class="sxs-lookup"><span data-stu-id="b6bef-107">id of partition to create lease info for</span></span></param>
        <summary>
            <span data-ttu-id="b6bef-108">ストアに、リースの情報を作成、特定のパーティションが存在しない場合。</span><span class="sxs-lookup"><span data-stu-id="b6bef-108">Create in the store the lease info for the given partition, if it does not exist.</span></span> <span data-ttu-id="b6bef-109">何も実行しない、ストアに既に存在しています。</span><span class="sxs-lookup"><span data-stu-id="b6bef-109">Do nothing if it does exist in the store already.</span></span> 
            </summary>
        <returns><span data-ttu-id="b6bef-110">パーティションの既存または新規に作成されたリース情報</span><span class="sxs-lookup"><span data-stu-id="b6bef-110">the existing or newly-created lease info for the partition</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateLeaseStoreIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; CreateLeaseStoreIfNotExistsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CreateLeaseStoreIfNotExistsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ILeaseManager.CreateLeaseStoreIfNotExistsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateLeaseStoreIfNotExistsAsync () As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member CreateLeaseStoreIfNotExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iLeaseManager.CreateLeaseStoreIfNotExistsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b6bef-111">リースのストアを作成することがない場合、何も存在する場合は。</span><span class="sxs-lookup"><span data-stu-id="b6bef-111">Create the lease store if it does not exist, do nothing if it does exist.</span></span>
            </summary>
        <returns><span data-ttu-id="b6bef-112">ストアが既にリース場合は true が存在するか、正常に作成されました、false 以外の場合</span><span class="sxs-lookup"><span data-stu-id="b6bef-112">true if the lease store already exists or was created successfully, false if not</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteLeaseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteLeaseAsync (Microsoft.Azure.EventHubs.Processor.Lease lease);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteLeaseAsync(class Microsoft.Azure.EventHubs.Processor.Lease lease) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ILeaseManager.DeleteLeaseAsync(Microsoft.Azure.EventHubs.Processor.Lease)" />
      <MemberSignature Language="F#" Value="abstract member DeleteLeaseAsync : Microsoft.Azure.EventHubs.Processor.Lease -&gt; System.Threading.Tasks.Task" Usage="iLeaseManager.DeleteLeaseAsync lease" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lease" Type="Microsoft.Azure.EventHubs.Processor.Lease" />
      </Parameters>
      <Docs>
        <param name="lease"><span data-ttu-id="b6bef-113">既に GetLeaseAsync() から取得した適切なパーティションの情報をリース</span><span class="sxs-lookup"><span data-stu-id="b6bef-113">Lease info for the desired partition as previously obtained from GetLeaseAsync()</span></span></param>
        <summary>
            <span data-ttu-id="b6bef-114">ストアから特定のパーティションのリース情報を削除します。</span><span class="sxs-lookup"><span data-stu-id="b6bef-114">Delete the lease info for the given partition from the store.</span></span> <span data-ttu-id="b6bef-115">成功として扱われる特定のパーティションに対するストアドのリースがない場合。</span><span class="sxs-lookup"><span data-stu-id="b6bef-115">If there is no stored lease for the given partition, that is treated as success.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteLeaseStoreAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; DeleteLeaseStoreAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteLeaseStoreAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ILeaseManager.DeleteLeaseStoreAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteLeaseStoreAsync () As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member DeleteLeaseStoreAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iLeaseManager.DeleteLeaseStoreAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b6bef-116">テストするために、EventProcessorHost は便利な関数では使用されません。</span><span class="sxs-lookup"><span data-stu-id="b6bef-116">Not used by EventProcessorHost, but a convenient function to have for testing.</span></span>
            </summary>
        <returns><span data-ttu-id="b6bef-117">リース ストアは、その以外の場合は、正常に削除された場合は true。</span><span class="sxs-lookup"><span data-stu-id="b6bef-117">true if the lease store was deleted successfully, false if not</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAllLeases">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Lease&gt;&gt; GetAllLeases ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.EventHubs.Processor.Lease&gt;&gt; GetAllLeases() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ILeaseManager.GetAllLeases" />
      <MemberSignature Language="VB.NET" Value="Public Function GetAllLeases () As IEnumerable(Of Task(Of Lease))" />
      <MemberSignature Language="F#" Value="abstract member GetAllLeases : unit -&gt; seq&lt;System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Lease&gt;&gt;" Usage="iLeaseManager.GetAllLeases " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Lease&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b6bef-118">すべてのパーティションのリース情報を返します。</span><span class="sxs-lookup"><span data-stu-id="b6bef-118">Return the lease info for all partitions.</span></span>
            <span data-ttu-id="b6bef-119">一般的な実装は、すべてのパーティションで GetLeaseAsync() を呼び出すだけでした。</span><span class="sxs-lookup"><span data-stu-id="b6bef-119">A typical implementation could just call GetLeaseAsync() on all partitions.</span></span>
            </summary>
        <returns><span data-ttu-id="b6bef-120">リース情報の一覧です。</span><span class="sxs-lookup"><span data-stu-id="b6bef-120">list of lease info.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLeaseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Lease&gt; GetLeaseAsync (string partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.EventHubs.Processor.Lease&gt; GetLeaseAsync(string partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ILeaseManager.GetLeaseAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetLeaseAsync (partitionId As String) As Task(Of Lease)" />
      <MemberSignature Language="F#" Value="abstract member GetLeaseAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Lease&gt;" Usage="iLeaseManager.GetLeaseAsync partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Lease&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partitionId"><span data-ttu-id="b6bef-121">リースを取得するパーティションの id</span><span class="sxs-lookup"><span data-stu-id="b6bef-121">id of partition to get lease for</span></span></param>
        <summary>
            <span data-ttu-id="b6bef-122">指定されたパーティションのリース情報を返します。</span><span class="sxs-lookup"><span data-stu-id="b6bef-122">Return the lease info for the specified partition.</span></span> <span data-ttu-id="b6bef-123">指定したパーティションのストアにリースが作成されていない場合は null を返すことができます。</span><span class="sxs-lookup"><span data-stu-id="b6bef-123">Can return null if no lease has been created in the store for the specified partition.</span></span>
            </summary>
        <returns><span data-ttu-id="b6bef-124">パーティション、または null の情報をリース</span><span class="sxs-lookup"><span data-stu-id="b6bef-124">lease info for the partition, or null</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LeaseDuration">
      <MemberSignature Language="C#" Value="public TimeSpan LeaseDuration { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan LeaseDuration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.ILeaseManager.LeaseDuration" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LeaseDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.LeaseDuration : TimeSpan" Usage="Microsoft.Azure.EventHubs.Processor.ILeaseManager.LeaseDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b6bef-125">テストのほとんどの場合に役立ちます。</span><span class="sxs-lookup"><span data-stu-id="b6bef-125">Mostly useful for testing.</span></span>
            </summary>
        <value><span data-ttu-id="b6bef-126">更新されないと、有効期限が切れる前に、リースの期間です。</span><span class="sxs-lookup"><span data-stu-id="b6bef-126">Duration of a lease before it expires unless renewed.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LeaseRenewInterval">
      <MemberSignature Language="C#" Value="public TimeSpan LeaseRenewInterval { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan LeaseRenewInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.ILeaseManager.LeaseRenewInterval" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LeaseRenewInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.LeaseRenewInterval : TimeSpan" Usage="Microsoft.Azure.EventHubs.Processor.ILeaseManager.LeaseRenewInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b6bef-127">リースをスキャンし、それらを更新か頻度 PartitionManager を指定するリース マネージャーの実装を使用できます。</span><span class="sxs-lookup"><span data-stu-id="b6bef-127">Allows a lease manager implementation to specify to PartitionManager how often it should scan leases and renew them.</span></span> <span data-ttu-id="b6bef-128">ホストが動作を中断した後に適切なタイミングでリースを再配布するためには、10 秒などの比較的短い間隔お勧めします。</span><span class="sxs-lookup"><span data-stu-id="b6bef-128">In order to redistribute leases in a timely fashion after a host ceases operating, we recommend a relatively short interval, such as ten seconds.</span></span> <span data-ttu-id="b6bef-129">言うまでもなく偶発的な有効期限を防ぐために、リース期間の半分未満でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="b6bef-129">Obviously it should be less than half of the lease length, to prevent accidental expiration.</span></span>
            </summary>
        <value><span data-ttu-id="b6bef-130">スリープ状態のスキャン間隔</span><span class="sxs-lookup"><span data-stu-id="b6bef-130">The sleep interval between scans</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LeaseStoreExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; LeaseStoreExistsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; LeaseStoreExistsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ILeaseManager.LeaseStoreExistsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function LeaseStoreExistsAsync () As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member LeaseStoreExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iLeaseManager.LeaseStoreExistsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b6bef-131">リース ストアが存在しますか。</span><span class="sxs-lookup"><span data-stu-id="b6bef-131">Does the lease store exist?</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReleaseLeaseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; ReleaseLeaseAsync (Microsoft.Azure.EventHubs.Processor.Lease lease);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ReleaseLeaseAsync(class Microsoft.Azure.EventHubs.Processor.Lease lease) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ILeaseManager.ReleaseLeaseAsync(Microsoft.Azure.EventHubs.Processor.Lease)" />
      <MemberSignature Language="F#" Value="abstract member ReleaseLeaseAsync : Microsoft.Azure.EventHubs.Processor.Lease -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iLeaseManager.ReleaseLeaseAsync lease" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lease" Type="Microsoft.Azure.EventHubs.Processor.Lease" />
      </Parameters>
      <Docs>
        <param name="lease"><span data-ttu-id="b6bef-132">リース付与するには</span><span class="sxs-lookup"><span data-stu-id="b6bef-132">Lease to be given up</span></span></param>
        <summary>
            <span data-ttu-id="b6bef-133">このホストで現在保持されている、リースを付けます。</span><span class="sxs-lookup"><span data-stu-id="b6bef-133">Give up a lease currently held by this host.</span></span>
            <span data-ttu-id="b6bef-134"><para>場合は、リースが盗難にあったされたり有効期限が切れて、解放が必要に応じてでありしようとした場合は失敗します。</para></span><span class="sxs-lookup"><span data-stu-id="b6bef-134"><para>If the lease has been stolen, or expired, releasing it is unnecessary, and will fail if attempted.</para></span></span></summary>
        <returns><span data-ttu-id="b6bef-135">リースは、その以外の場合は、正常にリリースされた場合は true。</span><span class="sxs-lookup"><span data-stu-id="b6bef-135">true if the lease was released successfully, false if not</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RenewLeaseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; RenewLeaseAsync (Microsoft.Azure.EventHubs.Processor.Lease lease);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; RenewLeaseAsync(class Microsoft.Azure.EventHubs.Processor.Lease lease) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ILeaseManager.RenewLeaseAsync(Microsoft.Azure.EventHubs.Processor.Lease)" />
      <MemberSignature Language="F#" Value="abstract member RenewLeaseAsync : Microsoft.Azure.EventHubs.Processor.Lease -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iLeaseManager.RenewLeaseAsync lease" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lease" Type="Microsoft.Azure.EventHubs.Processor.Lease" />
      </Parameters>
      <Docs>
        <param name="lease"><span data-ttu-id="b6bef-136">リースを更新します。</span><span class="sxs-lookup"><span data-stu-id="b6bef-136">Lease to be renewed</span></span></param>
        <summary>
            <span data-ttu-id="b6bef-137">このホストで現在保持されているリースを更新します。</span><span class="sxs-lookup"><span data-stu-id="b6bef-137">Renew a lease currently held by this host.</span></span>
            
            <span data-ttu-id="b6bef-138"><para>リースが盗難にあった場合または期限切れにした場合リリースされた、更新して更新することはできません。GetLease() し acquireLease() を再度呼び出す必要があります。</para></span><span class="sxs-lookup"><span data-stu-id="b6bef-138"><para>If the lease has been stolen, or expired, or released, it is not possible to renew it. You will have to call getLease() and then acquireLease() again.</para></span></span></summary>
        <returns><span data-ttu-id="b6bef-139">true の場合、リースは、その以外の場合は、正常に更新されました</span><span class="sxs-lookup"><span data-stu-id="b6bef-139">true if the lease was renewed successfully, false if not</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateLeaseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; UpdateLeaseAsync (Microsoft.Azure.EventHubs.Processor.Lease lease);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; UpdateLeaseAsync(class Microsoft.Azure.EventHubs.Processor.Lease lease) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ILeaseManager.UpdateLeaseAsync(Microsoft.Azure.EventHubs.Processor.Lease)" />
      <MemberSignature Language="F#" Value="abstract member UpdateLeaseAsync : Microsoft.Azure.EventHubs.Processor.Lease -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iLeaseManager.UpdateLeaseAsync lease" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lease" Type="Microsoft.Azure.EventHubs.Processor.Lease" />
      </Parameters>
      <Docs>
        <param name="lease"><span data-ttu-id="b6bef-140">新しいリース情報を格納します。</span><span class="sxs-lookup"><span data-stu-id="b6bef-140">New lease info to be stored</span></span></param>
        <summary>
            <span data-ttu-id="b6bef-141">指定されたリースの情報と、ストアを更新します。</span><span class="sxs-lookup"><span data-stu-id="b6bef-141">Update the store with the information in the provided lease.</span></span>
            
            <span data-ttu-id="b6bef-142"><para>更新するために現在のリースを保持する必要があります。リースが盗まれた、または有効期限が切れた、またはリリースを更新できません。更新プロセス中にリースの有効期限を避けるために、更新プログラムを実行する前にリースを更新する必要があります。</para></span><span class="sxs-lookup"><span data-stu-id="b6bef-142"><para>It is necessary to currently hold a lease in order to update it. If the lease has been stolen, or expired, or released, it cannot be updated. Updating should renew the lease before performing the update to avoid lease expiration during the process.</para></span></span></summary>
        <returns><span data-ttu-id="b6bef-143">更新後に実行された場合は、正常にされていない場合は true</span><span class="sxs-lookup"><span data-stu-id="b6bef-143">true if the updated was performed successfully, false if not</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>