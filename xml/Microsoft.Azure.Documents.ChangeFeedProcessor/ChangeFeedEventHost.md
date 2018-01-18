<Type Name="ChangeFeedEventHost" FullName="Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost">
  <TypeSignature Language="C#" Value="public class ChangeFeedEventHost" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ChangeFeedEventHost extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost" />
  <TypeSignature Language="VB.NET" Value="Public Class ChangeFeedEventHost" />
  <TypeSignature Language="F#" Value="type ChangeFeedEventHost = class&#xA;    interface IPartitionObserver&lt;DocumentServiceLease&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
    <AssemblyVersion>1.17.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7cb6d-101">変更を配布するための単純なホストは、オブザーバーとなり、これらのオブザーバー スケールの間でイベントをフィードです。</span><span class="sxs-lookup"><span data-stu-id="7cb6d-101">Simple host for distributing change feed events across observers and thus allowing these observers scale.</span></span>
            <span data-ttu-id="7cb6d-102">そのインスタンスは、負荷を分散し、により、動的スケーリングします。</span><span class="sxs-lookup"><span data-stu-id="7cb6d-102">It distributes the load across its instances and allows dynamic scaling:</span></span>
              - <span data-ttu-id="7cb6d-103">インスタンスまたはオブザーバー パーティション分割コレクション内のパーティションに分散されます。</span><span class="sxs-lookup"><span data-stu-id="7cb6d-103">Partitions in partitioned collections are distributed across instances/observers.</span></span>
              - <span data-ttu-id="7cb6d-104">新しいインスタンスは、配布を等しくする既存のインスタンスからのリースを受け取ります。</span><span class="sxs-lookup"><span data-stu-id="7cb6d-104">New instance takes leases from existing instances to make distribution equal.</span></span>
              - <span data-ttu-id="7cb6d-105">インスタンスが停止した場合、リースは残りのインスタンス間で分散されます。</span><span class="sxs-lookup"><span data-stu-id="7cb6d-105">If an instance dies, the leases are distributed across remaining instances.</span></span>
            <span data-ttu-id="7cb6d-106">1 つのホストと VM が多くの変更フィード イベントを処理できるようにするため、パーティション数が高いシナリオでは便利です。</span><span class="sxs-lookup"><span data-stu-id="7cb6d-106">It's useful for scenario when partition count is high so that one host/VM is not capable of processing that many change feed events.</span></span>
            <span data-ttu-id="7cb6d-107">クライアント アプリケーションを実装する必要がある<see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.IChangeFeedObserver" />ChangeFeedEventHost にプロセッサの実装を登録します。</span><span class="sxs-lookup"><span data-stu-id="7cb6d-107">Client application needs to implement <see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.IChangeFeedObserver" /> and register processor implementation with ChangeFeedEventHost.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="7cb6d-108">パーティションのリースを管理するための補助ドキュメント コレクションを使用します。</span><span class="sxs-lookup"><span data-stu-id="7cb6d-108">It uses auxiliary document collection for managing leases for a partition.</span></span>
            <span data-ttu-id="7cb6d-109">すべての EventProcessorHost インスタンスは、次の 2 つのタスクを実行します。</span><span class="sxs-lookup"><span data-stu-id="7cb6d-109">Every EventProcessorHost instance is performing the following two tasks:</span></span>
                1) <span data-ttu-id="7cb6d-110">リースを更新します。 ホストが所有する現在のリースの追跡し、継続的に、リースの更新では保持します。</span><span class="sxs-lookup"><span data-stu-id="7cb6d-110">Renew Leases: It keeps track of leases currently owned by the host and continuously keeps on renewing the leases.</span></span>
                2) <span data-ttu-id="7cb6d-111">リースを取得します。 各インスタンスは継続的に、すべてのリースをバランスの取れた状態にする、システムの取得する必要がありますが、リースがあるかどうかは確認をポーリングします。</span><span class="sxs-lookup"><span data-stu-id="7cb6d-111">Acquire Leases: Each instance continuously polls all leases to check if there are any leases it should acquire for the system to get into balanced state.</span></span>
                </remarks>
    <example>
      <code language="c#"><![CDATA[
            class DocumentFeedObserver : IChangeFeedObserver
            {
                private static int s_totalDocs = 0;
                public Task OpenAsync(ChangeFeedObserverContext context)
                {
                    Console.WriteLine("Worker opened, {0}", context.PartitionKeyRangeId);
                    return Task.CompletedTask;  // Requires targeting .NET 4.6+.
                }
                public Task CloseAsync(ChangeFeedObserverContext context, ChangeFeedObserverCloseReason reason)
                {
                    Console.WriteLine("Worker closed, {0}", context.PartitionKeyRangeId);
                    return Task.CompletedTask;
                }
                public Task ProcessChangesAsync(ChangeFeedObserverContext context, IReadOnlyList<Document> docs)
                {
                    Console.WriteLine("Change feed: total {0} doc(s)", Interlocked.Add(ref s_totalDocs, docs.Count));
                    return Task.CompletedTask;
                }
            }
            static async Task StartChangeFeedHost()
            {
                string hostName = Guid.NewGuid().ToString();
                DocumentCollectionInfo documentCollectionLocation = new DocumentCollectionInfo
                {
                    Uri = new Uri("https://YOUR_SERVICE.documents.azure.com:443/"),
                    MasterKey = "YOUR_SECRET_KEY==",
                    DatabaseName = "db1",
                    CollectionName = "documents"
                };
                DocumentCollectionInfo leaseCollectionLocation = new DocumentCollectionInfo
                {
                    Uri = new Uri("https://YOUR_SERVICE.documents.azure.com:443/"),
                    MasterKey = "YOUR_SECRET_KEY==",
                    DatabaseName = "db1",
                    CollectionName = "leases"
                };
                Console.WriteLine("Main program: Creating ChangeFeedEventHost...");
                ChangeFeedEventHost host = new ChangeFeedEventHost(hostName, documentCollectionLocation, leaseCollectionLocation);
                await host.RegisterObserverAsync<DocumentFeedObserver>();
                Console.WriteLine("Main program: press Enter to stop...");
                Console.ReadLine();
                await host.UnregisterObserversAsync();
            }
            ]]></code>
    </example>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ChangeFeedEventHost (string hostName, Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo documentCollectionLocation, Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo auxCollectionLocation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string hostName, class Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo documentCollectionLocation, class Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo auxCollectionLocation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost.#ctor(System.String,Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo,Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (hostName As String, documentCollectionLocation As DocumentCollectionInfo, auxCollectionLocation As DocumentCollectionInfo)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost : string * Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo * Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo -&gt; Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost" Usage="new Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost (hostName, documentCollectionLocation, auxCollectionLocation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="hostName" Type="System.String" />
        <Parameter Name="documentCollectionLocation" Type="Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo" />
        <Parameter Name="auxCollectionLocation" Type="Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo" />
      </Parameters>
      <Docs>
        <param name="hostName"><span data-ttu-id="7cb6d-112">このホストの一意の名前。</span><span class="sxs-lookup"><span data-stu-id="7cb6d-112">Unique name for this host.</span></span></param>
        <param name="documentCollectionLocation"><span data-ttu-id="7cb6d-113">変更を監視する DocumentDB コレクションの位置を指定します。</span><span class="sxs-lookup"><span data-stu-id="7cb6d-113">Specifies location of the DocumentDB collection to monitor changes for.</span></span></param>
        <param name="auxCollectionLocation"><span data-ttu-id="7cb6d-114">負荷分散の補助的なデータの場所を指定のインスタンス<see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost" />です。</span><span class="sxs-lookup"><span data-stu-id="7cb6d-114">Specifies location of auxiliary data for load-balancing instances of <see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost" />.</span></span></param>
        <summary>
            <span data-ttu-id="7cb6d-115"><see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7cb6d-115">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ChangeFeedEventHost (string hostName, Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo documentCollectionLocation, Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo auxCollectionLocation, Microsoft.Azure.Documents.Client.ChangeFeedOptions changeFeedOptions, Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions hostOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string hostName, class Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo documentCollectionLocation, class Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo auxCollectionLocation, class Microsoft.Azure.Documents.Client.ChangeFeedOptions changeFeedOptions, class Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions hostOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost.#ctor(System.String,Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo,Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo,Microsoft.Azure.Documents.Client.ChangeFeedOptions,Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost : string * Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo * Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo * Microsoft.Azure.Documents.Client.ChangeFeedOptions * Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions -&gt; Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost" Usage="new Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost (hostName, documentCollectionLocation, auxCollectionLocation, changeFeedOptions, hostOptions)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="hostName" Type="System.String" />
        <Parameter Name="documentCollectionLocation" Type="Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo" />
        <Parameter Name="auxCollectionLocation" Type="Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo" />
        <Parameter Name="changeFeedOptions" Type="Microsoft.Azure.Documents.Client.ChangeFeedOptions" />
        <Parameter Name="hostOptions" Type="Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions" />
      </Parameters>
      <Docs>
        <param name="hostName"><span data-ttu-id="7cb6d-116">このホストの一意の名前。</span><span class="sxs-lookup"><span data-stu-id="7cb6d-116">Unique name for this host.</span></span></param>
        <param name="documentCollectionLocation"><span data-ttu-id="7cb6d-117">変更を監視する DocumentDB コレクションの位置を指定します。</span><span class="sxs-lookup"><span data-stu-id="7cb6d-117">Specifies location of the DocumentDB collection to monitor changes for.</span></span></param>
        <param name="auxCollectionLocation"><span data-ttu-id="7cb6d-118">負荷分散の補助的なデータの場所を指定のインスタンス<see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost" />です。</span><span class="sxs-lookup"><span data-stu-id="7cb6d-118">Specifies location of auxiliary data for load-balancing instances of <see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost" />.</span></span></param>
        <param name="changeFeedOptions"><span data-ttu-id="7cb6d-119">Microsoft.AzureDocuments.DocumentClient.CreateChangeFeedQuery API に渡すオプションです。</span><span class="sxs-lookup"><span data-stu-id="7cb6d-119">Options to pass to the Microsoft.AzureDocuments.DocumentClient.CreateChangeFeedQuery API.</span></span></param>
        <param name="hostOptions"><span data-ttu-id="7cb6d-120">負荷分散を制御する追加のオプション<see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost" />インスタンス。</span><span class="sxs-lookup"><span data-stu-id="7cb6d-120">Additional options to control load-balancing of <see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost" /> instances.</span></span></param>
        <summary>
            <span data-ttu-id="7cb6d-121"><see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7cb6d-121">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEstimatedRemainingWork">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; GetEstimatedRemainingWork ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; GetEstimatedRemainingWork() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost.GetEstimatedRemainingWork" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEstimatedRemainingWork () As Task(Of Long)" />
      <MemberSignature Language="F#" Value="member this.GetEstimatedRemainingWork : unit -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="changeFeedEventHost.GetEstimatedRemainingWork " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost/&lt;GetEstimatedRemainingWork&gt;d__26))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7cb6d-122">非同期的に現在の既存リースを確認し、専用のパーティションごとの残存作業時間の概算を計算します。</span><span class="sxs-lookup"><span data-stu-id="7cb6d-122">Asynchronously checks the current existing leases and calculates an estimate of remaining work per leased partitions.</span></span>
            </summary>
        <returns><span data-ttu-id="7cb6d-123">処理するドキュメントの残りの量の見積もり</span><span class="sxs-lookup"><span data-stu-id="7cb6d-123">An estimate amount of remaining documents to be processed</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostName">
      <MemberSignature Language="C#" Value="public string HostName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost.HostName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HostName As String" />
      <MemberSignature Language="F#" Value="member this.HostName : string" Usage="Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost.HostName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="7cb6d-124">インスタンスの一意の名前をあるホスト名を取得します。</span><span class="sxs-lookup"><span data-stu-id="7cb6d-124">Gets the host name, which is a unique name for the instance.</span></span></summary>
        <value><span data-ttu-id="7cb6d-125">ホスト名です。</span><span class="sxs-lookup"><span data-stu-id="7cb6d-125">The host name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterObserverAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterObserverAsync&lt;T&gt; () where T : Microsoft.Azure.Documents.ChangeFeedProcessor.IChangeFeedObservernew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterObserverAsync&lt;.ctor (class Microsoft.Azure.Documents.ChangeFeedProcessor.IChangeFeedObserver) T&gt;() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost.RegisterObserverAsync``1" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterObserverAsync(Of T As {IChangeFeedObserverNew}) () As Task" />
      <MemberSignature Language="F#" Value="member this.RegisterObserverAsync : unit -&gt; System.Threading.Tasks.Task (requires 'T :&gt; Microsoft.Azure.Documents.ChangeFeedProcessor.IChangeFeedObserver and 'T : (new : unit -&gt; 'T))" Usage="changeFeedEventHost.RegisterObserverAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost/&lt;RegisterObserverAsync&gt;d__23`1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.Documents.ChangeFeedProcessor.IChangeFeedObserver</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters />
      <Docs>
        <typeparam name="T"><span data-ttu-id="7cb6d-126">特定のアプリケーション イベント オブザーバーの実装です。</span><span class="sxs-lookup"><span data-stu-id="7cb6d-126">Implementation of your application-specific event observer.</span></span></typeparam>
        <summary><span data-ttu-id="7cb6d-127">非同期的に、オブザーバー インターフェイスの実装をホストに登録します。</span><span class="sxs-lookup"><span data-stu-id="7cb6d-127">Asynchronously registers the observer interface implementation with the host.</span></span>
            <span data-ttu-id="7cb6d-128">また、このメソッドは、ホストを開始し、により、パーティションの配布プロセスへの参加を開始するようにします。</span><span class="sxs-lookup"><span data-stu-id="7cb6d-128">This method also starts the host and enables it to start participating in the partition distribution process.</span></span></summary>
        <returns><span data-ttu-id="7cb6d-129">タスクを示す、<see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost" />インスタンスが開始します。</span><span class="sxs-lookup"><span data-stu-id="7cb6d-129">A task indicating that the <see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost" /> instance has started.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterObserverFactoryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterObserverFactoryAsync (Microsoft.Azure.Documents.ChangeFeedProcessor.IChangeFeedObserverFactory factory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterObserverFactoryAsync(class Microsoft.Azure.Documents.ChangeFeedProcessor.IChangeFeedObserverFactory factory) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost.RegisterObserverFactoryAsync(Microsoft.Azure.Documents.ChangeFeedProcessor.IChangeFeedObserverFactory)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterObserverFactoryAsync (factory As IChangeFeedObserverFactory) As Task" />
      <MemberSignature Language="F#" Value="member this.RegisterObserverFactoryAsync : Microsoft.Azure.Documents.ChangeFeedProcessor.IChangeFeedObserverFactory -&gt; System.Threading.Tasks.Task" Usage="changeFeedEventHost.RegisterObserverFactoryAsync factory" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost/&lt;RegisterObserverFactoryAsync&gt;d__24))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="factory" Type="Microsoft.Azure.Documents.ChangeFeedProcessor.IChangeFeedObserverFactory" />
      </Parameters>
      <Docs>
        <param name="factory"><span data-ttu-id="7cb6d-130">特定のアプリケーション イベント オブザーバーの出荷時の実装です。</span><span class="sxs-lookup"><span data-stu-id="7cb6d-130">Implementation of your application-specific event observer factory.</span></span></param>
        <summary>
            <span data-ttu-id="7cb6d-131">非同期的にオブザーバー ファクトリの実装をホストに登録します。</span><span class="sxs-lookup"><span data-stu-id="7cb6d-131">Asynchronously registers the observer factory implementation with the host.</span></span>
            <span data-ttu-id="7cb6d-132">また、このメソッドは、ホストを開始し、により、パーティションの配布プロセスへの参加を開始するようにします。</span><span class="sxs-lookup"><span data-stu-id="7cb6d-132">This method also starts the host and enables it to start participating in the partition distribution process.</span></span>
            </summary>
        <returns><span data-ttu-id="7cb6d-133">タスクを示す、<see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost" />インスタンスが開始します。</span><span class="sxs-lookup"><span data-stu-id="7cb6d-133">A task indicating that the <see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost" /> instance has started.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnregisterObserversAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UnregisterObserversAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UnregisterObserversAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost.UnregisterObserversAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function UnregisterObserversAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.UnregisterObserversAsync : unit -&gt; System.Threading.Tasks.Task" Usage="changeFeedEventHost.UnregisterObserversAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost/&lt;UnregisterObserversAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="7cb6d-134">ホスト インスタンスを非同期的に終了します。</span><span class="sxs-lookup"><span data-stu-id="7cb6d-134">Asynchronously shuts down the host instance.</span></span> <span data-ttu-id="7cb6d-135">このメソッドは、現在保持されているすべてのパーティションでリースを維持し、正常にシャット ダウン オブジェクトでメソッドを呼び出すことによって各ホスト インスタンスを有効にします。</span><span class="sxs-lookup"><span data-stu-id="7cb6d-135">This method maintains the leases on all partitions currently held, and enables each host instance to shut down cleanly by invoking the method with object.</span></span></summary>
        <returns><span data-ttu-id="7cb6d-136">ホスト インスタンスを示すタスクが停止しました。</span><span class="sxs-lookup"><span data-stu-id="7cb6d-136">A task that indicates the host instance has stopped.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>