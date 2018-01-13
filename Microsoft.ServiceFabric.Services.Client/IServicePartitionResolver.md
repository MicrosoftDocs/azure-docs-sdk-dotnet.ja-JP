<Type Name="IServicePartitionResolver" FullName="Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver">
  <TypeSignature Language="C#" Value="public interface IServicePartitionResolver" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IServicePartitionResolver" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver" />
  <TypeSignature Language="VB.NET" Value="Public Interface IServicePartitionResolver" />
  <TypeSignature Language="F#" Value="type IServicePartitionResolver = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
      <para>
            <span data-ttu-id="6235b-101">サービス パーティション競合回避モジュールのインターフェイスを定義します。</span><span class="sxs-lookup"><span data-stu-id="6235b-101">Defines the interface for the Service partition resolver.</span></span>
            <span data-ttu-id="6235b-102">サービスの解決は、一連のパーティション内のレプリカのエンドポイントを検索するプロセスです。</span><span class="sxs-lookup"><span data-stu-id="6235b-102">Service resolution is the process of looking up the set of endpoints for the replicas in a partition.</span></span> <span data-ttu-id="6235b-103">サービス パーティションの競合回避モジュールでは、サービスの解決のロジックを実装します。</span><span class="sxs-lookup"><span data-stu-id="6235b-103">A service partition resolver implements the logic for service resolution.</span></span>
            </para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ResolveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveAsync (System.Fabric.ResolvedServicePartition previousRsp, TimeSpan resolveTimeoutPerTry, TimeSpan maxRetryBackoffInterval, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveAsync(class System.Fabric.ResolvedServicePartition previousRsp, valuetype System.TimeSpan resolveTimeoutPerTry, valuetype System.TimeSpan maxRetryBackoffInterval, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver.ResolveAsync(System.Fabric.ResolvedServicePartition,System.TimeSpan,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ResolveAsync : System.Fabric.ResolvedServicePartition * TimeSpan * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="iServicePartitionResolver.ResolveAsync (previousRsp, resolveTimeoutPerTry, maxRetryBackoffInterval, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="previousRsp" Type="System.Fabric.ResolvedServicePartition" />
        <Parameter Name="resolveTimeoutPerTry" Type="System.TimeSpan" />
        <Parameter Name="maxRetryBackoffInterval" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="previousRsp"><span data-ttu-id="6235b-104">クライアントが ResolveAsync() メソッドの以前の呼び出しから取得した解決済みのサービス パーティション。</span><span class="sxs-lookup"><span data-stu-id="6235b-104">The resolved service partition that the client got from the earlier invocation of the ResolveAsync() method.</span></span></param>
        <param name="resolveTimeoutPerTry"><span data-ttu-id="6235b-105">解決ごとのタイムアウトを再試行してください。</span><span class="sxs-lookup"><span data-stu-id="6235b-105">The timeout per resolve try.</span></span></param>
        <param name="maxRetryBackoffInterval">
            <span data-ttu-id="6235b-106">再試行できない例外により、障害発生後、解像度を再試行する前にバックオフする間隔。</span><span class="sxs-lookup"><span data-stu-id="6235b-106">The interval to back-off before retrying the resolution after a failure due to retry-able exception.</span></span>
            </param>
        <param name="cancellationToken">
          <para>
            <span data-ttu-id="6235b-107">この CancellationToken は、この操作を確認します。</span><span class="sxs-lookup"><span data-stu-id="6235b-107">The CancellationToken that this operation is observing.</span></span> <span data-ttu-id="6235b-108">取り消す必要がある操作の通知に使用されます。</span><span class="sxs-lookup"><span data-stu-id="6235b-108">It is used to notify the operation that it should be canceled.</span></span>
            </para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="6235b-109">再試行可能エラー時に指定したバックアップ/再試行設定で指定されたサービスの既に解決されたパーティションが再解決します。</span><span class="sxs-lookup"><span data-stu-id="6235b-109">Re-resolves a previously resolved partition of the specified service with specified back-off/retry settings on retry-able errors.</span></span> <span data-ttu-id="6235b-110">このメソッドのオーバー ロードは、クライアントが、解決済みのサービス パーティションを持つことが有効ではなくなったことを確認する場合に使用されます。</span><span class="sxs-lookup"><span data-stu-id="6235b-110">This method overload is used in cases where the client knows that the resolved service partition that it has is no longer valid.</span></span>
            </para>
        </summary>
        <returns>
            <span data-ttu-id="6235b-111">A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理のサービスの解決操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="6235b-111">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding service resolution operation.</span></span> <span data-ttu-id="6235b-112">タスクから結果が、<see cref="T:System.Fabric.ResolvedServicePartition" />サービス エンドポイントを含む、解決済みのサービス パーティションに関する情報を含むオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="6235b-112">The result from the Task is the <see cref="T:System.Fabric.ResolvedServicePartition" /> object, that contains the information about the resolved service partition including the service endpoints.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResolveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveAsync (Uri serviceUri, Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey, TimeSpan resolveTimeoutPerTry, TimeSpan maxRetryBackoffInterval, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveAsync(class System.Uri serviceUri, class Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey, valuetype System.TimeSpan resolveTimeoutPerTry, valuetype System.TimeSpan maxRetryBackoffInterval, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver.ResolveAsync(System.Uri,Microsoft.ServiceFabric.Services.Client.ServicePartitionKey,System.TimeSpan,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ResolveAsync : Uri * Microsoft.ServiceFabric.Services.Client.ServicePartitionKey * TimeSpan * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="iServicePartitionResolver.ResolveAsync (serviceUri, partitionKey, resolveTimeoutPerTry, maxRetryBackoffInterval, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceUri" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="Microsoft.ServiceFabric.Services.Client.ServicePartitionKey" />
        <Parameter Name="resolveTimeoutPerTry" Type="System.TimeSpan" />
        <Parameter Name="maxRetryBackoffInterval" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceUri"><span data-ttu-id="6235b-113">解決するのには、サービス インスタンスの名前です。</span><span class="sxs-lookup"><span data-stu-id="6235b-113">Name of the service instance to resolve.</span></span></param>
        <param name="partitionKey">
          <para>
            <span data-ttu-id="6235b-114"><see cref="T:Microsoft.ServiceFabric.Services.Client.ServicePartitionKey">キー</see>サービス インスタンスの対象のパーティションを指定します。</span><span class="sxs-lookup"><span data-stu-id="6235b-114"><see cref="T:Microsoft.ServiceFabric.Services.Client.ServicePartitionKey">Key</see> that determines the target partition of the service instance.</span></span> <span data-ttu-id="6235b-115"><see cref="T:System.Fabric.ServicePartitionKind">パーティション</see>で指定されてキーは、パーティション スキームの一致使用サービス インスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="6235b-115">The <see cref="T:System.Fabric.ServicePartitionKind">partitioning scheme</see> specified in the key should match the partitioning scheme used to create the service instance.</span></span>
            </para>
        </param>
        <param name="resolveTimeoutPerTry"><span data-ttu-id="6235b-116">解決ごとのタイムアウトを再試行してください。</span><span class="sxs-lookup"><span data-stu-id="6235b-116">The timeout per resolve try.</span></span></param>
        <param name="maxRetryBackoffInterval">
            <span data-ttu-id="6235b-117">再試行できない例外により、障害発生後、解像度を再試行する前にバックオフする間隔。</span><span class="sxs-lookup"><span data-stu-id="6235b-117">The interval to back-off before retrying the resolution after a failure due to retry-able exception.</span></span>
            </param>
        <param name="cancellationToken">
          <para>
            <span data-ttu-id="6235b-118">この CancellationToken は、この操作を確認します。</span><span class="sxs-lookup"><span data-stu-id="6235b-118">The CancellationToken that this operation is observing.</span></span> <span data-ttu-id="6235b-119">取り消す必要がある操作の通知に使用されます。</span><span class="sxs-lookup"><span data-stu-id="6235b-119">It is used to notify the operation that it should be canceled.</span></span>
            </para>
        </param>
        <summary>
            <span data-ttu-id="6235b-120">再試行可能エラー時に指定したバックアップ/再試行設定で指定されたサービスのパーティションを解決します。</span><span class="sxs-lookup"><span data-stu-id="6235b-120">Resolves a partition of the specified service with specified back-off/retry settings on retry-able errors.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="6235b-121">A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理のサービスの解決操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="6235b-121">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents the outstanding service resolution operation.</span></span> <span data-ttu-id="6235b-122">タスクから結果が、<see cref="T:System.Fabric.ResolvedServicePartition" />サービス エンドポイントを含む、解決済みのサービス パーティションに関する情報を含むオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="6235b-122">The result from the Task is the <see cref="T:System.Fabric.ResolvedServicePartition" /> object, that contains the information about the resolved service partition including the service endpoints.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>