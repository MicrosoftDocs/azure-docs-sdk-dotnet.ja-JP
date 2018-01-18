<Type Name="IPoolOperations" FullName="Microsoft.Azure.Batch.Protocol.IPoolOperations">
  <TypeSignature Language="C#" Value="public interface IPoolOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IPoolOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.IPoolOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IPoolOperations" />
  <TypeSignature Language="F#" Value="type IPoolOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d778e-101">PoolOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="d778e-101">PoolOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AddWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolAddHeaders&gt;&gt; AddWithHttpMessagesAsync (Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter pool, Microsoft.Azure.Batch.Protocol.Models.PoolAddOptions poolAddOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolAddHeaders&gt;&gt; AddWithHttpMessagesAsync(class Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter pool, class Microsoft.Azure.Batch.Protocol.Models.PoolAddOptions poolAddOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.AddWithHttpMessagesAsync(Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter,Microsoft.Azure.Batch.Protocol.Models.PoolAddOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddWithHttpMessagesAsync : Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter * Microsoft.Azure.Batch.Protocol.Models.PoolAddOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolAddHeaders&gt;&gt;" Usage="iPoolOperations.AddWithHttpMessagesAsync (pool, poolAddOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolAddHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="pool" Type="Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter" />
        <Parameter Name="poolAddOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolAddOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="pool">
            <span data-ttu-id="d778e-102">追加するプールです。</span><span class="sxs-lookup"><span data-stu-id="d778e-102">The pool to be added.</span></span>
            </param>
        <param name="poolAddOptions">
            <span data-ttu-id="d778e-103">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="d778e-103">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d778e-104">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d778e-104">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d778e-105">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d778e-105">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d778e-106">指定されたアカウントにプールを追加します。</span><span class="sxs-lookup"><span data-stu-id="d778e-106">Adds a pool to the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="d778e-107">プールの名前を付けるときは、ユーザー名またはシークレット プロジェクト名などの機密情報が含まれないようにします。</span><span class="sxs-lookup"><span data-stu-id="d778e-107">When naming pools, avoid including sensitive information such as user names or secret project names.</span></span> <span data-ttu-id="d778e-108">この情報は、Microsoft サポート エンジニアにアクセスできる製品利用統計情報ログに表示可能性があります。</span><span class="sxs-lookup"><span data-stu-id="d778e-108">This information may appear in telemetry logs accessible to Microsoft Support engineers.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="d778e-109">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d778e-109">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d778e-110">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d778e-110">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolDeleteHeaders&gt;&gt; DeleteWithHttpMessagesAsync (string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolDeleteOptions poolDeleteOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolDeleteHeaders&gt;&gt; DeleteWithHttpMessagesAsync(string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolDeleteOptions poolDeleteOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.DeleteWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.PoolDeleteOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.PoolDeleteOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolDeleteHeaders&gt;&gt;" Usage="iPoolOperations.DeleteWithHttpMessagesAsync (poolId, poolDeleteOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolDeleteHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolDeleteOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolDeleteOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            <span data-ttu-id="d778e-111">削除するプールの ID。</span><span class="sxs-lookup"><span data-stu-id="d778e-111">The ID of the pool to delete.</span></span>
            </param>
        <param name="poolDeleteOptions">
            <span data-ttu-id="d778e-112">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="d778e-112">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d778e-113">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d778e-113">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d778e-114">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d778e-114">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d778e-115">指定されたアカウントからプールを削除します。</span><span class="sxs-lookup"><span data-stu-id="d778e-115">Deletes a pool from the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="d778e-116">プールが削除されることを要求すると、次の操作が行われますプールの状態が削除; に設定されている。プールで進行中のサイズ変更操作が停止しました。バッチ サービスの開始ノードをゼロにプールのサイズ変更既存のノードで実行されているすべてのタスクが終了し、(既定 requeue オプションを使用して要求された resize pool 操作) 場合、キューに再登録します。最後に、プールは、システムから削除されます。</span><span class="sxs-lookup"><span data-stu-id="d778e-116">When you request that a pool be deleted, the following actions occur: the pool state is set to deleting; any ongoing resize operation on the pool are stopped; the Batch service starts resizing the pool to zero nodes; any tasks running on existing nodes are terminated and requeued (as if a resize pool operation had been requested with the default requeue option); finally, the pool is removed from the system.</span></span> <span data-ttu-id="d778e-117">実行中のタスクが再配置、ため、ユーザーは、別のプールを対象に、ジョブを更新することで、これらのタスクを再実行できます。</span><span class="sxs-lookup"><span data-stu-id="d778e-117">Because running tasks are requeued, the user can rerun these tasks by updating their job to target a different pool.</span></span> <span data-ttu-id="d778e-118">タスクは、新しいプールで実行できます。</span><span class="sxs-lookup"><span data-stu-id="d778e-118">The tasks can then run on the new pool.</span></span> <span data-ttu-id="d778e-119">キューの動作をオーバーライドする場合は、サイズがゼロにプールを削除する前に、プールを圧縮するには、明示的にサイズ変更のプールを呼び出す必要があります。</span><span class="sxs-lookup"><span data-stu-id="d778e-119">If you want to override the requeue behavior, then you should call resize pool explicitly to shrink the pool to zero size before deleting the pool.</span></span> <span data-ttu-id="d778e-120">削除状態のプールの更新プログラム、修正または削除の API を呼び出す場合は、エラー コード PoolBeingDeleted HTTP ステータス コード 409 で失敗します。</span><span class="sxs-lookup"><span data-stu-id="d778e-120">If you call an Update, Patch or Delete API on a pool in the deleting state, it will fail with HTTP status code 409 with error code PoolBeingDeleted.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="d778e-121">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d778e-121">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d778e-122">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d778e-122">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DisableAutoScaleWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleHeaders&gt;&gt; DisableAutoScaleWithHttpMessagesAsync (string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleOptions poolDisableAutoScaleOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleHeaders&gt;&gt; DisableAutoScaleWithHttpMessagesAsync(string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleOptions poolDisableAutoScaleOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.DisableAutoScaleWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DisableAutoScaleWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleHeaders&gt;&gt;" Usage="iPoolOperations.DisableAutoScaleWithHttpMessagesAsync (poolId, poolDisableAutoScaleOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolDisableAutoScaleOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            <span data-ttu-id="d778e-123">自動スケーリングを無効にするプールの ID。</span><span class="sxs-lookup"><span data-stu-id="d778e-123">The ID of the pool on which to disable automatic scaling.</span></span>
            </param>
        <param name="poolDisableAutoScaleOptions">
            <span data-ttu-id="d778e-124">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="d778e-124">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d778e-125">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d778e-125">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d778e-126">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d778e-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d778e-127">プールの自動スケーリングを無効にします。</span><span class="sxs-lookup"><span data-stu-id="d778e-127">Disables automatic scaling for a pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="d778e-128">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d778e-128">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d778e-129">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d778e-129">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="EnableAutoScaleWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleHeaders&gt;&gt; EnableAutoScaleWithHttpMessagesAsync (string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter poolEnableAutoScaleParameter, Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleOptions poolEnableAutoScaleOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleHeaders&gt;&gt; EnableAutoScaleWithHttpMessagesAsync(string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter poolEnableAutoScaleParameter, class Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleOptions poolEnableAutoScaleOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.EnableAutoScaleWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter,Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member EnableAutoScaleWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter * Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleHeaders&gt;&gt;" Usage="iPoolOperations.EnableAutoScaleWithHttpMessagesAsync (poolId, poolEnableAutoScaleParameter, poolEnableAutoScaleOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolEnableAutoScaleParameter" Type="Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter" />
        <Parameter Name="poolEnableAutoScaleOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            <span data-ttu-id="d778e-130">自動スケーリングを有効にするプールの ID。</span><span class="sxs-lookup"><span data-stu-id="d778e-130">The ID of the pool on which to enable automatic scaling.</span></span>
            </param>
        <param name="poolEnableAutoScaleParameter">
            <span data-ttu-id="d778e-131">要求のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="d778e-131">The parameters for the request.</span></span>
            </param>
        <param name="poolEnableAutoScaleOptions">
            <span data-ttu-id="d778e-132">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="d778e-132">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d778e-133">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d778e-133">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d778e-134">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d778e-134">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d778e-135">プールの自動スケーリングを有効にします。</span><span class="sxs-lookup"><span data-stu-id="d778e-135">Enables automatic scaling for a pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="d778e-136">サイズ変更操作が、プールで進行中の場合は、プールで自動スケーリングを有効にすることはできません。</span><span class="sxs-lookup"><span data-stu-id="d778e-136">You cannot enable automatic scaling on a pool if a resize operation is in progress on the pool.</span></span> <span data-ttu-id="d778e-137">プールの自動スケーリングが現在無効にした場合は、要求の一部として、有効な自動スケール式を指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="d778e-137">If automatic scaling of the pool is currently disabled, you must specify a valid autoscale formula as part of the request.</span></span> <span data-ttu-id="d778e-138">プールの自動スケーリングが既に有効になっている場合、新しい自動スケール式や新しい評価の間隔を指定する可能性があります。</span><span class="sxs-lookup"><span data-stu-id="d778e-138">If automatic scaling of the pool is already enabled, you may specify a new autoscale formula and/or a new evaluation interval.</span></span> <span data-ttu-id="d778e-139">30 秒ごとに 2 回以上で、同じプールのこの API を呼び出すことはできません。</span><span class="sxs-lookup"><span data-stu-id="d778e-139">You cannot call this API for the same pool more than once every 30 seconds.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="d778e-140">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d778e-140">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d778e-141">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d778e-141">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="EvaluateAutoScaleWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun,Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleHeaders&gt;&gt; EvaluateAutoScaleWithHttpMessagesAsync (string poolId, string autoScaleFormula, Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleOptions poolEvaluateAutoScaleOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun, class Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleHeaders&gt;&gt; EvaluateAutoScaleWithHttpMessagesAsync(string poolId, string autoScaleFormula, class Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleOptions poolEvaluateAutoScaleOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.EvaluateAutoScaleWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member EvaluateAutoScaleWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun, Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleHeaders&gt;&gt;" Usage="iPoolOperations.EvaluateAutoScaleWithHttpMessagesAsync (poolId, autoScaleFormula, poolEvaluateAutoScaleOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun,Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="autoScaleFormula" Type="System.String" />
        <Parameter Name="poolEvaluateAutoScaleOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            <span data-ttu-id="d778e-142">自動スケーリング式を評価するプールの ID。</span><span class="sxs-lookup"><span data-stu-id="d778e-142">The ID of the pool on which to evaluate the automatic scaling formula.</span></span>
            </param>
        <param name="autoScaleFormula">
            <span data-ttu-id="d778e-143">プール内の計算ノードの必要な数の式。</span><span class="sxs-lookup"><span data-stu-id="d778e-143">The formula for the desired number of compute nodes in the pool.</span></span>
            <span data-ttu-id="d778e-144">数式が検証されると、結果が計算されがプールには適用されません。</span><span class="sxs-lookup"><span data-stu-id="d778e-144">The formula is validated and its results calculated, but it is not applied to the pool.</span></span> <span data-ttu-id="d778e-145">適用するには、数式をプールに 'を有効にするプールの自動スケーリングを' です。</span><span class="sxs-lookup"><span data-stu-id="d778e-145">To apply the formula to the pool, 'Enable automatic scaling on a pool'.</span></span> <span data-ttu-id="d778e-146">この式の指定に関する詳細についてを参照して自動的に Azure Batch プール (https://azure.microsoft.com/en-us/documentation/articles/batch-automatic-scaling) 内のノードをコンピューティング スケール。</span><span class="sxs-lookup"><span data-stu-id="d778e-146">For more information about specifying this formula, see Automatically scale compute nodes in an Azure Batch pool (https://azure.microsoft.com/en-us/documentation/articles/batch-automatic-scaling).</span></span>
            </param>
        <param name="poolEvaluateAutoScaleOptions">
            <span data-ttu-id="d778e-147">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="d778e-147">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d778e-148">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d778e-148">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d778e-149">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d778e-149">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d778e-150">自動の評価結果は、プール内の数式をスケーリングを取得します。</span><span class="sxs-lookup"><span data-stu-id="d778e-150">Gets the result of evaluating an automatic scaling formula on the pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="d778e-151">この API は、自動スケール式を検証するため、主には、プールに、式を適用せず、結果が単純に返されるです。</span><span class="sxs-lookup"><span data-stu-id="d778e-151">This API is primarily for validating an autoscale formula, as it simply returns the result without applying the formula to the pool.</span></span>
            <span data-ttu-id="d778e-152">自動スケーリング式を評価するために有効になっている、プールが必要です。</span><span class="sxs-lookup"><span data-stu-id="d778e-152">The pool must have auto scaling enabled in order to evaluate a formula.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="d778e-153">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d778e-153">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="d778e-154">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d778e-154">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d778e-155">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d778e-155">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ExistsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;bool,Microsoft.Azure.Batch.Protocol.Models.PoolExistsHeaders&gt;&gt; ExistsWithHttpMessagesAsync (string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolExistsOptions poolExistsOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;bool, class Microsoft.Azure.Batch.Protocol.Models.PoolExistsHeaders&gt;&gt; ExistsWithHttpMessagesAsync(string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolExistsOptions poolExistsOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.ExistsWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.PoolExistsOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExistsWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.PoolExistsOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;bool, Microsoft.Azure.Batch.Protocol.Models.PoolExistsHeaders&gt;&gt;" Usage="iPoolOperations.ExistsWithHttpMessagesAsync (poolId, poolExistsOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Boolean,Microsoft.Azure.Batch.Protocol.Models.PoolExistsHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolExistsOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolExistsOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            <span data-ttu-id="d778e-156">取得するプールの ID。</span><span class="sxs-lookup"><span data-stu-id="d778e-156">The ID of the pool to get.</span></span>
            </param>
        <param name="poolExistsOptions">
            <span data-ttu-id="d778e-157">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="d778e-157">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d778e-158">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d778e-158">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d778e-159">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d778e-159">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d778e-160">プールの基本プロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="d778e-160">Gets basic properties of a pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="d778e-161">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d778e-161">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d778e-162">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d778e-162">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetAllLifetimeStatisticsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolStatistics,Microsoft.Azure.Batch.Protocol.Models.PoolGetAllLifetimeStatisticsHeaders&gt;&gt; GetAllLifetimeStatisticsWithHttpMessagesAsync (Microsoft.Azure.Batch.Protocol.Models.PoolGetAllLifetimeStatisticsOptions poolGetAllLifetimeStatisticsOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolStatistics, class Microsoft.Azure.Batch.Protocol.Models.PoolGetAllLifetimeStatisticsHeaders&gt;&gt; GetAllLifetimeStatisticsWithHttpMessagesAsync(class Microsoft.Azure.Batch.Protocol.Models.PoolGetAllLifetimeStatisticsOptions poolGetAllLifetimeStatisticsOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.GetAllLifetimeStatisticsWithHttpMessagesAsync(Microsoft.Azure.Batch.Protocol.Models.PoolGetAllLifetimeStatisticsOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAllLifetimeStatisticsWithHttpMessagesAsync : Microsoft.Azure.Batch.Protocol.Models.PoolGetAllLifetimeStatisticsOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolStatistics, Microsoft.Azure.Batch.Protocol.Models.PoolGetAllLifetimeStatisticsHeaders&gt;&gt;" Usage="iPoolOperations.GetAllLifetimeStatisticsWithHttpMessagesAsync (poolGetAllLifetimeStatisticsOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolStatistics,Microsoft.Azure.Batch.Protocol.Models.PoolGetAllLifetimeStatisticsHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolGetAllLifetimeStatisticsOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolGetAllLifetimeStatisticsOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolGetAllLifetimeStatisticsOptions">
            <span data-ttu-id="d778e-163">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="d778e-163">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d778e-164">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d778e-164">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d778e-165">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d778e-165">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d778e-166">指定されたアカウント内のプールのすべての有効期間の概要統計情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="d778e-166">Gets lifetime summary statistics for all of the pools in the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="d778e-167">統計情報は、存在していたアカウントを作成してから、アカウントの最後の更新時刻、統計のすべてのプール間で集計されます。</span><span class="sxs-lookup"><span data-stu-id="d778e-167">Statistics are aggregated across all pools that have ever existed in the account, from account creation to the last update time of the statistics.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="d778e-168">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d778e-168">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="d778e-169">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d778e-169">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d778e-170">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d778e-170">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool,Microsoft.Azure.Batch.Protocol.Models.PoolGetHeaders&gt;&gt; GetWithHttpMessagesAsync (string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolGetOptions poolGetOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudPool, class Microsoft.Azure.Batch.Protocol.Models.PoolGetHeaders&gt;&gt; GetWithHttpMessagesAsync(string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolGetOptions poolGetOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.GetWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.PoolGetOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.PoolGetOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool, Microsoft.Azure.Batch.Protocol.Models.PoolGetHeaders&gt;&gt;" Usage="iPoolOperations.GetWithHttpMessagesAsync (poolId, poolGetOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool,Microsoft.Azure.Batch.Protocol.Models.PoolGetHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolGetOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolGetOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            <span data-ttu-id="d778e-171">取得するプールの ID。</span><span class="sxs-lookup"><span data-stu-id="d778e-171">The ID of the pool to get.</span></span>
            </param>
        <param name="poolGetOptions">
            <span data-ttu-id="d778e-172">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="d778e-172">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d778e-173">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d778e-173">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d778e-174">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d778e-174">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d778e-175">指定したプールに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="d778e-175">Gets information about the specified pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="d778e-176">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d778e-176">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="d778e-177">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d778e-177">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d778e-178">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d778e-178">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt;,Microsoft.Azure.Batch.Protocol.Models.PoolListHeaders&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.PoolListNextOptions poolListNextOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt;, class Microsoft.Azure.Batch.Protocol.Models.PoolListHeaders&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.PoolListNextOptions poolListNextOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.ListNextWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.PoolListNextOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.PoolListNextOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt;, Microsoft.Azure.Batch.Protocol.Models.PoolListHeaders&gt;&gt;" Usage="iPoolOperations.ListNextWithHttpMessagesAsync (nextPageLink, poolListNextOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt;,Microsoft.Azure.Batch.Protocol.Models.PoolListHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="poolListNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolListNextOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="d778e-179">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="d778e-179">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="poolListNextOptions">
            <span data-ttu-id="d778e-180">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="d778e-180">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d778e-181">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d778e-181">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d778e-182">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d778e-182">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d778e-183">指定されたアカウント内のプールのすべての一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="d778e-183">Lists all of the pools in the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="d778e-184">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d778e-184">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="d778e-185">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d778e-185">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d778e-186">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d778e-186">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListUsageMetricsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt;,Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsHeaders&gt;&gt; ListUsageMetricsNextWithHttpMessagesAsync (string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsNextOptions poolListUsageMetricsNextOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt;, class Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsHeaders&gt;&gt; ListUsageMetricsNextWithHttpMessagesAsync(string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsNextOptions poolListUsageMetricsNextOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.ListUsageMetricsNextWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsNextOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListUsageMetricsNextWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsNextOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt;, Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsHeaders&gt;&gt;" Usage="iPoolOperations.ListUsageMetricsNextWithHttpMessagesAsync (nextPageLink, poolListUsageMetricsNextOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt;,Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="poolListUsageMetricsNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsNextOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="d778e-187">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="d778e-187">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="poolListUsageMetricsNextOptions">
            <span data-ttu-id="d778e-188">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="d778e-188">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d778e-189">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d778e-189">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d778e-190">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d778e-190">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d778e-191">指定されたアカウント用の個別の時間間隔の間でプールを使用して集計の使用状況メトリックを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="d778e-191">Lists the usage metrics, aggregated by pool across individual time intervals, for the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="d778e-192">など、poolId $filter 句を指定しない場合、応答には、返される集計間隔の時間の範囲内のアカウント内に存在していたすべてのプールが含まれます。</span><span class="sxs-lookup"><span data-stu-id="d778e-192">If you do not specify a $filter clause including a poolId, the response includes all pools that existed in the account in the time range of the returned aggregation intervals.</span></span> <span data-ttu-id="d778e-193">指定しない場合、startTime、endTime など $filter 句を現在使用できません。 最後の集計間隔の開始と終了時刻に、これらの既定のフィルターつまり、最後の集計間隔のみが返されます。</span><span class="sxs-lookup"><span data-stu-id="d778e-193">If you do not specify a $filter clause including a startTime or endTime these filters default to the start and end times of the last aggregation interval currently available; that is, only the last aggregation interval is returned.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="d778e-194">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d778e-194">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="d778e-195">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d778e-195">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d778e-196">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d778e-196">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListUsageMetricsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt;,Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsHeaders&gt;&gt; ListUsageMetricsWithHttpMessagesAsync (Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions poolListUsageMetricsOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt;, class Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsHeaders&gt;&gt; ListUsageMetricsWithHttpMessagesAsync(class Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions poolListUsageMetricsOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.ListUsageMetricsWithHttpMessagesAsync(Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListUsageMetricsWithHttpMessagesAsync : Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt;, Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsHeaders&gt;&gt;" Usage="iPoolOperations.ListUsageMetricsWithHttpMessagesAsync (poolListUsageMetricsOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt;,Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolListUsageMetricsOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolListUsageMetricsOptions">
            <span data-ttu-id="d778e-197">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="d778e-197">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d778e-198">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d778e-198">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d778e-199">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d778e-199">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d778e-200">指定されたアカウント用の個別の時間間隔の間でプールを使用して集計の使用状況メトリックを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="d778e-200">Lists the usage metrics, aggregated by pool across individual time intervals, for the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="d778e-201">など、poolId $filter 句を指定しない場合、応答には、返される集計間隔の時間の範囲内のアカウント内に存在していたすべてのプールが含まれます。</span><span class="sxs-lookup"><span data-stu-id="d778e-201">If you do not specify a $filter clause including a poolId, the response includes all pools that existed in the account in the time range of the returned aggregation intervals.</span></span> <span data-ttu-id="d778e-202">指定しない場合、startTime、endTime など $filter 句を現在使用できません。 最後の集計間隔の開始と終了時刻に、これらの既定のフィルターつまり、最後の集計間隔のみが返されます。</span><span class="sxs-lookup"><span data-stu-id="d778e-202">If you do not specify a $filter clause including a startTime or endTime these filters default to the start and end times of the last aggregation interval currently available; that is, only the last aggregation interval is returned.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="d778e-203">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d778e-203">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="d778e-204">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d778e-204">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d778e-205">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d778e-205">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt;,Microsoft.Azure.Batch.Protocol.Models.PoolListHeaders&gt;&gt; ListWithHttpMessagesAsync (Microsoft.Azure.Batch.Protocol.Models.PoolListOptions poolListOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt;, class Microsoft.Azure.Batch.Protocol.Models.PoolListHeaders&gt;&gt; ListWithHttpMessagesAsync(class Microsoft.Azure.Batch.Protocol.Models.PoolListOptions poolListOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.ListWithHttpMessagesAsync(Microsoft.Azure.Batch.Protocol.Models.PoolListOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : Microsoft.Azure.Batch.Protocol.Models.PoolListOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt;, Microsoft.Azure.Batch.Protocol.Models.PoolListHeaders&gt;&gt;" Usage="iPoolOperations.ListWithHttpMessagesAsync (poolListOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt;,Microsoft.Azure.Batch.Protocol.Models.PoolListHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolListOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolListOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolListOptions">
            <span data-ttu-id="d778e-206">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="d778e-206">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d778e-207">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d778e-207">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d778e-208">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d778e-208">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d778e-209">指定されたアカウント内のプールのすべての一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="d778e-209">Lists all of the pools in the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="d778e-210">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d778e-210">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="d778e-211">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d778e-211">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d778e-212">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d778e-212">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="PatchWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolPatchHeaders&gt;&gt; PatchWithHttpMessagesAsync (string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter poolPatchParameter, Microsoft.Azure.Batch.Protocol.Models.PoolPatchOptions poolPatchOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolPatchHeaders&gt;&gt; PatchWithHttpMessagesAsync(string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter poolPatchParameter, class Microsoft.Azure.Batch.Protocol.Models.PoolPatchOptions poolPatchOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.PatchWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter,Microsoft.Azure.Batch.Protocol.Models.PoolPatchOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PatchWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter * Microsoft.Azure.Batch.Protocol.Models.PoolPatchOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolPatchHeaders&gt;&gt;" Usage="iPoolOperations.PatchWithHttpMessagesAsync (poolId, poolPatchParameter, poolPatchOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolPatchHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolPatchParameter" Type="Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter" />
        <Parameter Name="poolPatchOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolPatchOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            <span data-ttu-id="d778e-213">更新するプールの ID。</span><span class="sxs-lookup"><span data-stu-id="d778e-213">The ID of the pool to update.</span></span>
            </param>
        <param name="poolPatchParameter">
            <span data-ttu-id="d778e-214">要求のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="d778e-214">The parameters for the request.</span></span>
            </param>
        <param name="poolPatchOptions">
            <span data-ttu-id="d778e-215">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="d778e-215">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d778e-216">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d778e-216">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d778e-217">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d778e-217">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d778e-218">指定したプールのプロパティを更新します。</span><span class="sxs-lookup"><span data-stu-id="d778e-218">Updates the properties of the specified pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="d778e-219">これには、要求で指定されたプールのプロパティのみ置き換えられます。</span><span class="sxs-lookup"><span data-stu-id="d778e-219">This only replaces the pool properties specified in the request.</span></span>
            <span data-ttu-id="d778e-220">たとえば、プールに関連付けられている開始タスク、要求が開始タスク要素を指定しない場合は、既存の開始タスク保持プールにします。</span><span class="sxs-lookup"><span data-stu-id="d778e-220">For example, if the pool has a start task associated with it, and a request does not specify a start task element, then the pool keeps the existing start task.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="d778e-221">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d778e-221">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d778e-222">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d778e-222">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveNodesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesHeaders&gt;&gt; RemoveNodesWithHttpMessagesAsync (string poolId, Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter nodeRemoveParameter, Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesOptions poolRemoveNodesOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesHeaders&gt;&gt; RemoveNodesWithHttpMessagesAsync(string poolId, class Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter nodeRemoveParameter, class Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesOptions poolRemoveNodesOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.RemoveNodesWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter,Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RemoveNodesWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter * Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesHeaders&gt;&gt;" Usage="iPoolOperations.RemoveNodesWithHttpMessagesAsync (poolId, nodeRemoveParameter, poolRemoveNodesOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeRemoveParameter" Type="Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter" />
        <Parameter Name="poolRemoveNodesOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            <span data-ttu-id="d778e-223">ノードを削除するプールの ID。</span><span class="sxs-lookup"><span data-stu-id="d778e-223">The ID of the pool from which you want to remove nodes.</span></span>
            </param>
        <param name="nodeRemoveParameter">
            <span data-ttu-id="d778e-224">要求のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="d778e-224">The parameters for the request.</span></span>
            </param>
        <param name="poolRemoveNodesOptions">
            <span data-ttu-id="d778e-225">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="d778e-225">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d778e-226">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d778e-226">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d778e-227">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d778e-227">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d778e-228">削除は、指定したプールからノードを計算します。</span><span class="sxs-lookup"><span data-stu-id="d778e-228">Removes compute nodes from the specified pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="d778e-229">この操作は、プールの割り当ての状態が点灯している場合にのみ実行できます。</span><span class="sxs-lookup"><span data-stu-id="d778e-229">This operation can only run when the allocation state of the pool is steady.</span></span> <span data-ttu-id="d778e-230">この操作を実行すると、割り当て状態の変更定常からサイズを変更します。</span><span class="sxs-lookup"><span data-stu-id="d778e-230">When this operation runs, the allocation state changes from steady to resizing.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="d778e-231">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d778e-231">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d778e-232">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d778e-232">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ResizeWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolResizeHeaders&gt;&gt; ResizeWithHttpMessagesAsync (string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter poolResizeParameter, Microsoft.Azure.Batch.Protocol.Models.PoolResizeOptions poolResizeOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolResizeHeaders&gt;&gt; ResizeWithHttpMessagesAsync(string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter poolResizeParameter, class Microsoft.Azure.Batch.Protocol.Models.PoolResizeOptions poolResizeOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.ResizeWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter,Microsoft.Azure.Batch.Protocol.Models.PoolResizeOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ResizeWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter * Microsoft.Azure.Batch.Protocol.Models.PoolResizeOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolResizeHeaders&gt;&gt;" Usage="iPoolOperations.ResizeWithHttpMessagesAsync (poolId, poolResizeParameter, poolResizeOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolResizeHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolResizeParameter" Type="Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter" />
        <Parameter Name="poolResizeOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolResizeOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            <span data-ttu-id="d778e-233">サイズを変更するプールの ID です。</span><span class="sxs-lookup"><span data-stu-id="d778e-233">The ID of the pool to resize.</span></span>
            </param>
        <param name="poolResizeParameter">
            <span data-ttu-id="d778e-234">要求のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="d778e-234">The parameters for the request.</span></span>
            </param>
        <param name="poolResizeOptions">
            <span data-ttu-id="d778e-235">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="d778e-235">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d778e-236">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d778e-236">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d778e-237">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d778e-237">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d778e-238">プールに割り当てられているコンピューティング ノードの数を変更します。</span><span class="sxs-lookup"><span data-stu-id="d778e-238">Changes the number of compute nodes that are assigned to a pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="d778e-239">割り当て状態が点灯しているときに、プールのサイズのみできます。</span><span class="sxs-lookup"><span data-stu-id="d778e-239">You can only resize a pool when its allocation state is steady.</span></span> <span data-ttu-id="d778e-240">プールは既にサイズ変更、要求はステータス コードで失敗します。</span><span class="sxs-lookup"><span data-stu-id="d778e-240">If the pool is already resizing, the request fails with status code</span></span>
            409. <span data-ttu-id="d778e-241">ときに、プールにある場合、プールの割り当ての状態の変更定常からサイズを変更するのには、サイズを変更します。</span><span class="sxs-lookup"><span data-stu-id="d778e-241">When you resize a pool, the pool's allocation state changes from steady to resizing.</span></span> <span data-ttu-id="d778e-242">自動スケーリング用に構成されているプールのサイズを変更することはできません。</span><span class="sxs-lookup"><span data-stu-id="d778e-242">You cannot resize pools which are configured for automatic scaling.</span></span> <span data-ttu-id="d778e-243">これを行うしようとすると、バッチ サービスはエラー 409 を返します。</span><span class="sxs-lookup"><span data-stu-id="d778e-243">If you try to do this, the Batch service returns an error 409.</span></span> <span data-ttu-id="d778e-244">起点、プールのサイズを変更する場合、バッチ サービスは削除するノードを選択します。</span><span class="sxs-lookup"><span data-stu-id="d778e-244">If you resize a pool downwards, the Batch service chooses which nodes to remove.</span></span> <span data-ttu-id="d778e-245">特定のノードを削除するには、代わりにプール削除ノード API を使用します。</span><span class="sxs-lookup"><span data-stu-id="d778e-245">To remove specific nodes, use the pool remove nodes API instead.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="d778e-246">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d778e-246">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d778e-247">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d778e-247">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="StopResizeWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeHeaders&gt;&gt; StopResizeWithHttpMessagesAsync (string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeOptions poolStopResizeOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeHeaders&gt;&gt; StopResizeWithHttpMessagesAsync(string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeOptions poolStopResizeOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.StopResizeWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member StopResizeWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeHeaders&gt;&gt;" Usage="iPoolOperations.StopResizeWithHttpMessagesAsync (poolId, poolStopResizeOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolStopResizeOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            <span data-ttu-id="d778e-248">サイズを停止するプールの ID。</span><span class="sxs-lookup"><span data-stu-id="d778e-248">The ID of the pool whose resizing you want to stop.</span></span>
            </param>
        <param name="poolStopResizeOptions">
            <span data-ttu-id="d778e-249">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="d778e-249">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d778e-250">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d778e-250">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d778e-251">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d778e-251">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d778e-252">継続的な停止のサイズ変更、プールに操作します。</span><span class="sxs-lookup"><span data-stu-id="d778e-252">Stops an ongoing resize operation on the pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="d778e-253">プール サイズ変更操作の前に以前の状態は元に戻りません。 行われるさらなる変更だけが停止され、プールが、現在の状態を維持します。</span><span class="sxs-lookup"><span data-stu-id="d778e-253">This does not restore the pool to its previous state before the resize operation: it only stops any further changes being made, and the pool maintains its current state.</span></span> <span data-ttu-id="d778e-254">停止後、プールが停止操作が完了するとではノードの数に安定します。</span><span class="sxs-lookup"><span data-stu-id="d778e-254">After stopping, the pool stabilizes at the number of nodes it was at when the stop operation was done.</span></span> <span data-ttu-id="d778e-255">プール割り当て状態は、停止操作中は停止してから、安定したに最初に変更します。</span><span class="sxs-lookup"><span data-stu-id="d778e-255">During the stop operation, the pool allocation state changes first to stopping and then to steady.</span></span> <span data-ttu-id="d778e-256">サイズ変更操作で、明示的なサイズ変更プール要求である必要はありません。この API は、作成時に、プールの初期サイズ設定を停止するようにも使用できます。</span><span class="sxs-lookup"><span data-stu-id="d778e-256">A resize operation need not be an explicit resize pool request; this API can also be used to halt the initial sizing of the pool when it is created.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="d778e-257">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d778e-257">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d778e-258">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d778e-258">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdatePropertiesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesHeaders&gt;&gt; UpdatePropertiesWithHttpMessagesAsync (string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesParameter poolUpdatePropertiesParameter, Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesOptions poolUpdatePropertiesOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesHeaders&gt;&gt; UpdatePropertiesWithHttpMessagesAsync(string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesParameter poolUpdatePropertiesParameter, class Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesOptions poolUpdatePropertiesOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.UpdatePropertiesWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesParameter,Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdatePropertiesWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesParameter * Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesHeaders&gt;&gt;" Usage="iPoolOperations.UpdatePropertiesWithHttpMessagesAsync (poolId, poolUpdatePropertiesParameter, poolUpdatePropertiesOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolUpdatePropertiesParameter" Type="Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesParameter" />
        <Parameter Name="poolUpdatePropertiesOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            <span data-ttu-id="d778e-259">更新するプールの ID。</span><span class="sxs-lookup"><span data-stu-id="d778e-259">The ID of the pool to update.</span></span>
            </param>
        <param name="poolUpdatePropertiesParameter">
            <span data-ttu-id="d778e-260">要求のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="d778e-260">The parameters for the request.</span></span>
            </param>
        <param name="poolUpdatePropertiesOptions">
            <span data-ttu-id="d778e-261">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="d778e-261">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d778e-262">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d778e-262">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d778e-263">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d778e-263">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d778e-264">指定したプールのプロパティを更新します。</span><span class="sxs-lookup"><span data-stu-id="d778e-264">Updates the properties of the specified pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="d778e-265">これにより、プールのすべての更新可能なプロパティが完全に置き換えられます。</span><span class="sxs-lookup"><span data-stu-id="d778e-265">This fully replaces all the updateable properties of the pool.</span></span> <span data-ttu-id="d778e-266">たとえば、開始タスクがこの要求に指定されていない場合、Batch service が解除され、プールに関連付けられている開始タスク、既存の開始タスク。</span><span class="sxs-lookup"><span data-stu-id="d778e-266">For example, if the pool has a start task associated with it and if start task is not specified with this request, then the Batch service will remove the existing start task.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="d778e-267">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d778e-267">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d778e-268">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d778e-268">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpgradeOSWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSHeaders&gt;&gt; UpgradeOSWithHttpMessagesAsync (string poolId, string targetOSVersion, Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSOptions poolUpgradeOSOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSHeaders&gt;&gt; UpgradeOSWithHttpMessagesAsync(string poolId, string targetOSVersion, class Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSOptions poolUpgradeOSOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.UpgradeOSWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpgradeOSWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSHeaders&gt;&gt;" Usage="iPoolOperations.UpgradeOSWithHttpMessagesAsync (poolId, targetOSVersion, poolUpgradeOSOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="targetOSVersion" Type="System.String" />
        <Parameter Name="poolUpgradeOSOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            <span data-ttu-id="d778e-269">アップグレードするプールの ID。</span><span class="sxs-lookup"><span data-stu-id="d778e-269">The ID of the pool to upgrade.</span></span>
            </param>
        <param name="targetOSVersion">
            <span data-ttu-id="d778e-270">プール内の仮想マシンにインストールされる Azure ゲスト OS バージョン。</span><span class="sxs-lookup"><span data-stu-id="d778e-270">The Azure Guest OS version to be installed on the virtual machines in the pool.</span></span>
            </param>
        <param name="poolUpgradeOSOptions">
            <span data-ttu-id="d778e-271">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="d778e-271">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d778e-272">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d778e-272">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d778e-273">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d778e-273">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d778e-274">指定したプールのオペレーティング システムをアップグレードします。</span><span class="sxs-lookup"><span data-stu-id="d778e-274">Upgrades the operating system of the specified pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="d778e-275">アップグレード中は、バッチ サービス アップグレードは、プール内のノードを計算します。</span><span class="sxs-lookup"><span data-stu-id="d778e-275">During an upgrade, the Batch service upgrades each compute node in the pool.</span></span> <span data-ttu-id="d778e-276">アップグレードのコンピューティング ノードを選択すると、そのノードで実行されているすべてのタスクがノードから削除され、後で (または、別の計算ノード) を再実行キューに返されます。</span><span class="sxs-lookup"><span data-stu-id="d778e-276">When a compute node is chosen for upgrade, any tasks running on that node are removed from the node and returned to the queue to be rerun later (or on a different compute node).</span></span> <span data-ttu-id="d778e-277">アップグレードが完了するまで、ノードは使用できません。</span><span class="sxs-lookup"><span data-stu-id="d778e-277">The node will be unavailable until the upgrade is complete.</span></span> <span data-ttu-id="d778e-278">ノードは、サービスのアップグレード対象として外すと、この演算の結果は一時的に削減プールの容量。</span><span class="sxs-lookup"><span data-stu-id="d778e-278">This operation results in temporarily reduced pool capacity as nodes are taken out of service to be upgraded.</span></span> <span data-ttu-id="d778e-279">サービスが、すべてのアップグレードを回避しようとしています。 バッチはコンピューティング ノードを同時とは限りません (特にでサイズの小さいプール); の実行したがって、プールは一時的に実行できるようにタスクでない可能性があります。</span><span class="sxs-lookup"><span data-stu-id="d778e-279">Although the Batch service tries to avoid upgrading all compute nodes at the same time, it does not guarantee to do this (particularly on small pools); therefore, the pool may be temporarily unavailable to run tasks.</span></span> <span data-ttu-id="d778e-280">この操作を実行するときにアップグレードする場合に、プールの状態を変更します。</span><span class="sxs-lookup"><span data-stu-id="d778e-280">When this operation runs, the pool state changes to upgrading.</span></span> <span data-ttu-id="d778e-281">すべてのコンピューティング ノードでは、アップグレードが完了したら、ときに、プールの状態をアクティブに返します。</span><span class="sxs-lookup"><span data-stu-id="d778e-281">When all compute nodes have finished upgrading, the pool state returns to active.</span></span> <span data-ttu-id="d778e-282">アップグレードの進行状況では、プールの currentOSVersion は OS のバージョンから、ノードをアップグレードして、targetOSVersion ノードへのアップグレードは、OS のバージョンを反映することを反映します。</span><span class="sxs-lookup"><span data-stu-id="d778e-282">While the upgrade is in progress, the pool's currentOSVersion reflects the OS version that nodes are upgrading from, and targetOSVersion reflects the OS version that nodes are upgrading to.</span></span> <span data-ttu-id="d778e-283">アップグレードが完了したら、currentOSVersion はすべてのノードで実行されている OS バージョンを反映するように更新されます。</span><span class="sxs-lookup"><span data-stu-id="d778e-283">Once the upgrade is complete, currentOSVersion is updated to reflect the OS version now running on all nodes.</span></span> <span data-ttu-id="d778e-284">この操作は、cloudServiceConfiguration プロパティを使用して作成されたプールでのみ呼び出すことができます。</span><span class="sxs-lookup"><span data-stu-id="d778e-284">This operation can only be invoked on pools created with the cloudServiceConfiguration property.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="d778e-285">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d778e-285">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d778e-286">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d778e-286">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>