<Type Name="IComputeNodeOperations" FullName="Microsoft.Azure.Batch.Protocol.IComputeNodeOperations">
  <TypeSignature Language="C#" Value="public interface IComputeNodeOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IComputeNodeOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.IComputeNodeOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IComputeNodeOperations" />
  <TypeSignature Language="F#" Value="type IComputeNodeOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="35a8c-101">ComputeNodeOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="35a8c-101">ComputeNodeOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AddUserWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeAddUserHeaders&gt;&gt; AddUserWithHttpMessagesAsync (string poolId, string nodeId, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUser user, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeAddUserOptions computeNodeAddUserOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeAddUserHeaders&gt;&gt; AddUserWithHttpMessagesAsync(string poolId, string nodeId, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUser user, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeAddUserOptions computeNodeAddUserOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IComputeNodeOperations.AddUserWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUser,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeAddUserOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddUserWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUser * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeAddUserOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeAddUserHeaders&gt;&gt;" Usage="iComputeNodeOperations.AddUserWithHttpMessagesAsync (poolId, nodeId, user, computeNodeAddUserOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeAddUserHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="user" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUser" />
        <Parameter Name="computeNodeAddUserOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeAddUserOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            <span data-ttu-id="35a8c-102">コンピューティング ノードを含むプールの ID。</span><span class="sxs-lookup"><span data-stu-id="35a8c-102">The ID of the pool that contains the compute node.</span></span>
            </param>
        <param name="nodeId">
            <span data-ttu-id="35a8c-103">ユーザー アカウントを作成するコンピューターの ID。</span><span class="sxs-lookup"><span data-stu-id="35a8c-103">The ID of the machine on which you want to create a user account.</span></span>
            </param>
        <param name="user">
            <span data-ttu-id="35a8c-104">作成するユーザー アカウント。</span><span class="sxs-lookup"><span data-stu-id="35a8c-104">The user account to be created.</span></span>
            </param>
        <param name="computeNodeAddUserOptions">
            <span data-ttu-id="35a8c-105">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="35a8c-105">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="35a8c-106">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="35a8c-106">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="35a8c-107">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="35a8c-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="35a8c-108">指定された計算ノードには、ユーザー アカウントを追加します。</span><span class="sxs-lookup"><span data-stu-id="35a8c-108">Adds a user account to the specified compute node.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="35a8c-109">アイドル状態または実行中の状態にある場合にのみ、ノードに、ユーザー アカウントを追加できます。</span><span class="sxs-lookup"><span data-stu-id="35a8c-109">You can add a user account to a node only when it is in the idle or running state.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="35a8c-110">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="35a8c-110">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="35a8c-111">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="35a8c-111">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteUserWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeleteUserHeaders&gt;&gt; DeleteUserWithHttpMessagesAsync (string poolId, string nodeId, string userName, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeleteUserOptions computeNodeDeleteUserOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeleteUserHeaders&gt;&gt; DeleteUserWithHttpMessagesAsync(string poolId, string nodeId, string userName, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeleteUserOptions computeNodeDeleteUserOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IComputeNodeOperations.DeleteUserWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeleteUserOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteUserWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeleteUserOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeleteUserHeaders&gt;&gt;" Usage="iComputeNodeOperations.DeleteUserWithHttpMessagesAsync (poolId, nodeId, userName, computeNodeDeleteUserOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeleteUserHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="userName" Type="System.String" />
        <Parameter Name="computeNodeDeleteUserOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeleteUserOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            <span data-ttu-id="35a8c-112">コンピューティング ノードを含むプールの ID。</span><span class="sxs-lookup"><span data-stu-id="35a8c-112">The ID of the pool that contains the compute node.</span></span>
            </param>
        <param name="nodeId">
            <span data-ttu-id="35a8c-113">ユーザー アカウントを削除するコンピューターの ID。</span><span class="sxs-lookup"><span data-stu-id="35a8c-113">The ID of the machine on which you want to delete a user account.</span></span>
            </param>
        <param name="userName">
            <span data-ttu-id="35a8c-114">削除するユーザー アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="35a8c-114">The name of the user account to delete.</span></span>
            </param>
        <param name="computeNodeDeleteUserOptions">
            <span data-ttu-id="35a8c-115">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="35a8c-115">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="35a8c-116">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="35a8c-116">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="35a8c-117">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="35a8c-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="35a8c-118">指定された計算ノードから、ユーザー アカウントを削除します。</span><span class="sxs-lookup"><span data-stu-id="35a8c-118">Deletes a user account from the specified compute node.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="35a8c-119">アイドル状態または実行中の状態にある場合にのみ、ノードへのユーザー アカウントを削除できます。</span><span class="sxs-lookup"><span data-stu-id="35a8c-119">You can delete a user account to a node only when it is in the idle or running state.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="35a8c-120">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="35a8c-120">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="35a8c-121">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="35a8c-121">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DisableSchedulingWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDisableSchedulingHeaders&gt;&gt; DisableSchedulingWithHttpMessagesAsync (string poolId, string nodeId, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.DisableComputeNodeSchedulingOption&gt; nodeDisableSchedulingOption = null, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDisableSchedulingOptions computeNodeDisableSchedulingOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDisableSchedulingHeaders&gt;&gt; DisableSchedulingWithHttpMessagesAsync(string poolId, string nodeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.DisableComputeNodeSchedulingOption&gt; nodeDisableSchedulingOption, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDisableSchedulingOptions computeNodeDisableSchedulingOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IComputeNodeOperations.DisableSchedulingWithHttpMessagesAsync(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Protocol.Models.DisableComputeNodeSchedulingOption},Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDisableSchedulingOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DisableSchedulingWithHttpMessagesAsync : string * string * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.DisableComputeNodeSchedulingOption&gt; * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDisableSchedulingOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDisableSchedulingHeaders&gt;&gt;" Usage="iComputeNodeOperations.DisableSchedulingWithHttpMessagesAsync (poolId, nodeId, nodeDisableSchedulingOption, computeNodeDisableSchedulingOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDisableSchedulingHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="nodeDisableSchedulingOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.DisableComputeNodeSchedulingOption&gt;" />
        <Parameter Name="computeNodeDisableSchedulingOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDisableSchedulingOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            <span data-ttu-id="35a8c-122">コンピューティング ノードを含むプールの ID。</span><span class="sxs-lookup"><span data-stu-id="35a8c-122">The ID of the pool that contains the compute node.</span></span>
            </param>
        <param name="nodeId">
            <span data-ttu-id="35a8c-123">タスクのスケジュールを無効にするコンピューティング ノードの ID。</span><span class="sxs-lookup"><span data-stu-id="35a8c-123">The ID of the compute node on which you want to disable task scheduling.</span></span>
            </param>
        <param name="nodeDisableSchedulingOption">
            <span data-ttu-id="35a8c-124">コンピューティング ノードでタスクのスケジュール設定を無効にするときにタスクを実行中の対処方法。</span><span class="sxs-lookup"><span data-stu-id="35a8c-124">What to do with currently running tasks when disabling task scheduling on the compute node.</span></span> <span data-ttu-id="35a8c-125">既定値は requeue です。</span><span class="sxs-lookup"><span data-stu-id="35a8c-125">The default value is requeue.</span></span>
            <span data-ttu-id="35a8c-126">使用可能な値が含まれます: 'キューに再登録'、'終了'、'taskCompletion'</span><span class="sxs-lookup"><span data-stu-id="35a8c-126">Possible values include: 'requeue', 'terminate', 'taskCompletion'</span></span>
            </param>
        <param name="computeNodeDisableSchedulingOptions">
            <span data-ttu-id="35a8c-127">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="35a8c-127">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="35a8c-128">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="35a8c-128">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="35a8c-129">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="35a8c-129">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="35a8c-130">指定したコンピューティング ノードでタスクのスケジュール設定を無効にします。</span><span class="sxs-lookup"><span data-stu-id="35a8c-130">Disables task scheduling on the specified compute node.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="35a8c-131">現在のスケジュールの状態が有効になっている場合にのみ、ノード上のスケジュール タスクを無効にすることができます。</span><span class="sxs-lookup"><span data-stu-id="35a8c-131">You can disable task scheduling on a node only if its current scheduling state is enabled.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="35a8c-132">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="35a8c-132">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="35a8c-133">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="35a8c-133">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="EnableSchedulingWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEnableSchedulingHeaders&gt;&gt; EnableSchedulingWithHttpMessagesAsync (string poolId, string nodeId, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEnableSchedulingOptions computeNodeEnableSchedulingOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEnableSchedulingHeaders&gt;&gt; EnableSchedulingWithHttpMessagesAsync(string poolId, string nodeId, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEnableSchedulingOptions computeNodeEnableSchedulingOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IComputeNodeOperations.EnableSchedulingWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEnableSchedulingOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member EnableSchedulingWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEnableSchedulingOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEnableSchedulingHeaders&gt;&gt;" Usage="iComputeNodeOperations.EnableSchedulingWithHttpMessagesAsync (poolId, nodeId, computeNodeEnableSchedulingOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEnableSchedulingHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="computeNodeEnableSchedulingOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEnableSchedulingOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            <span data-ttu-id="35a8c-134">コンピューティング ノードを含むプールの ID。</span><span class="sxs-lookup"><span data-stu-id="35a8c-134">The ID of the pool that contains the compute node.</span></span>
            </param>
        <param name="nodeId">
            <span data-ttu-id="35a8c-135">タスクのスケジュール設定を有効にするコンピューティング ノードの ID。</span><span class="sxs-lookup"><span data-stu-id="35a8c-135">The ID of the compute node on which you want to enable task scheduling.</span></span>
            </param>
        <param name="computeNodeEnableSchedulingOptions">
            <span data-ttu-id="35a8c-136">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="35a8c-136">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="35a8c-137">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="35a8c-137">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="35a8c-138">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="35a8c-138">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="35a8c-139">指定したコンピューティング ノードでタスクのスケジュール設定を使用できます。</span><span class="sxs-lookup"><span data-stu-id="35a8c-139">Enables task scheduling on the specified compute node.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="35a8c-140">現在のスケジュールの状態が無効になっている場合にのみ、ノード上のスケジュール タスクを有効にすることができます。</span><span class="sxs-lookup"><span data-stu-id="35a8c-140">You can enable task scheduling on a node only if its current scheduling state is disabled</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="35a8c-141">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="35a8c-141">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="35a8c-142">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="35a8c-142">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetRemoteDesktopWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.IO.Stream,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteDesktopHeaders&gt;&gt; GetRemoteDesktopWithHttpMessagesAsync (string poolId, string nodeId, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteDesktopOptions computeNodeGetRemoteDesktopOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class System.IO.Stream, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteDesktopHeaders&gt;&gt; GetRemoteDesktopWithHttpMessagesAsync(string poolId, string nodeId, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteDesktopOptions computeNodeGetRemoteDesktopOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IComputeNodeOperations.GetRemoteDesktopWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteDesktopOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetRemoteDesktopWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteDesktopOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.IO.Stream, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteDesktopHeaders&gt;&gt;" Usage="iComputeNodeOperations.GetRemoteDesktopWithHttpMessagesAsync (poolId, nodeId, computeNodeGetRemoteDesktopOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.IO.Stream,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteDesktopHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="computeNodeGetRemoteDesktopOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteDesktopOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            <span data-ttu-id="35a8c-143">コンピューティング ノードを含むプールの ID。</span><span class="sxs-lookup"><span data-stu-id="35a8c-143">The ID of the pool that contains the compute node.</span></span>
            </param>
        <param name="nodeId">
            <span data-ttu-id="35a8c-144">リモート デスクトップ プロトコル ファイルを取得するコンピューティング ノードの ID。</span><span class="sxs-lookup"><span data-stu-id="35a8c-144">The ID of the compute node for which you want to get the Remote Desktop Protocol file.</span></span>
            </param>
        <param name="computeNodeGetRemoteDesktopOptions">
            <span data-ttu-id="35a8c-145">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="35a8c-145">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="35a8c-146">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="35a8c-146">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="35a8c-147">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="35a8c-147">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="35a8c-148">指定された計算ノードのリモート デスクトップ プロトコル ファイルを取得します。</span><span class="sxs-lookup"><span data-stu-id="35a8c-148">Gets the Remote Desktop Protocol file for the specified compute node.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="35a8c-149">ノードにアクセスするには、RDP ファイルを使用して、前に、ノードで、ユーザー アカウントを作成する必要があります。</span><span class="sxs-lookup"><span data-stu-id="35a8c-149">Before you can access a node by using the RDP file, you must create a user account on the node.</span></span> <span data-ttu-id="35a8c-150">この API は、クラウド サービスの構成で作成されたプールでのみ呼び出すことができます。</span><span class="sxs-lookup"><span data-stu-id="35a8c-150">This API can only be invoked on pools created with a cloud service configuration.</span></span> <span data-ttu-id="35a8c-151">プールの仮想マシンの構成で作成された場合は、GetRemoteLoginSettings API を参照してください。</span><span class="sxs-lookup"><span data-stu-id="35a8c-151">For pools created with a virtual machine configuration, see the GetRemoteLoginSettings API.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="35a8c-152">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="35a8c-152">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="35a8c-153">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="35a8c-153">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="35a8c-154">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="35a8c-154">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetRemoteLoginSettingsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsResult,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsHeaders&gt;&gt; GetRemoteLoginSettingsWithHttpMessagesAsync (string poolId, string nodeId, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsOptions computeNodeGetRemoteLoginSettingsOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsResult, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsHeaders&gt;&gt; GetRemoteLoginSettingsWithHttpMessagesAsync(string poolId, string nodeId, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsOptions computeNodeGetRemoteLoginSettingsOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IComputeNodeOperations.GetRemoteLoginSettingsWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetRemoteLoginSettingsWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsResult, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsHeaders&gt;&gt;" Usage="iComputeNodeOperations.GetRemoteLoginSettingsWithHttpMessagesAsync (poolId, nodeId, computeNodeGetRemoteLoginSettingsOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsResult,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="computeNodeGetRemoteLoginSettingsOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            <span data-ttu-id="35a8c-155">コンピューティング ノードを含むプールの ID。</span><span class="sxs-lookup"><span data-stu-id="35a8c-155">The ID of the pool that contains the compute node.</span></span>
            </param>
        <param name="nodeId">
            <span data-ttu-id="35a8c-156">リモート ログインの設定を取得する対象のコンピューティング ノードの ID。</span><span class="sxs-lookup"><span data-stu-id="35a8c-156">The ID of the compute node for which to obtain the remote login settings.</span></span>
            </param>
        <param name="computeNodeGetRemoteLoginSettingsOptions">
            <span data-ttu-id="35a8c-157">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="35a8c-157">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="35a8c-158">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="35a8c-158">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="35a8c-159">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="35a8c-159">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="35a8c-160">コンピューティング ノードへのリモート ログイン用に必要な設定を取得します。</span><span class="sxs-lookup"><span data-stu-id="35a8c-160">Gets the settings required for remote login to a compute node.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="35a8c-161">前にリモートでログインにリモート ログインの設定を使用してノード、ノードでユーザー アカウントを作成する必要があります。</span><span class="sxs-lookup"><span data-stu-id="35a8c-161">Before you can remotely login to a node using the remote login settings, you must create a user account on the node.</span></span> <span data-ttu-id="35a8c-162">この API は、仮想マシンの構成プロパティを使用して作成されたプールでのみ呼び出すことができます。</span><span class="sxs-lookup"><span data-stu-id="35a8c-162">This API can be invoked only on pools created with the virtual machine configuration property.</span></span> <span data-ttu-id="35a8c-163">クラウド サービスの構成で作成されたプール、GetRemoteDesktop API を参照してください。</span><span class="sxs-lookup"><span data-stu-id="35a8c-163">For pools created with a cloud service configuration, see the GetRemoteDesktop API.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="35a8c-164">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="35a8c-164">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="35a8c-165">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="35a8c-165">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="35a8c-166">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="35a8c-166">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNode,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetHeaders&gt;&gt; GetWithHttpMessagesAsync (string poolId, string nodeId, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetOptions computeNodeGetOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNode, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetHeaders&gt;&gt; GetWithHttpMessagesAsync(string poolId, string nodeId, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetOptions computeNodeGetOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IComputeNodeOperations.GetWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNode, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetHeaders&gt;&gt;" Usage="iComputeNodeOperations.GetWithHttpMessagesAsync (poolId, nodeId, computeNodeGetOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNode,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="computeNodeGetOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            <span data-ttu-id="35a8c-167">コンピューティング ノードを含むプールの ID。</span><span class="sxs-lookup"><span data-stu-id="35a8c-167">The ID of the pool that contains the compute node.</span></span>
            </param>
        <param name="nodeId">
            <span data-ttu-id="35a8c-168">に関する情報を取得するコンピューティング ノードの ID。</span><span class="sxs-lookup"><span data-stu-id="35a8c-168">The ID of the compute node that you want to get information about.</span></span>
            </param>
        <param name="computeNodeGetOptions">
            <span data-ttu-id="35a8c-169">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="35a8c-169">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="35a8c-170">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="35a8c-170">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="35a8c-171">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="35a8c-171">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="35a8c-172">指定された計算ノードに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="35a8c-172">Gets information about the specified compute node.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="35a8c-173">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="35a8c-173">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="35a8c-174">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="35a8c-174">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="35a8c-175">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="35a8c-175">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNode&gt;,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListHeaders&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListNextOptions computeNodeListNextOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNode&gt;, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListHeaders&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListNextOptions computeNodeListNextOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IComputeNodeOperations.ListNextWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListNextOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListNextOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNode&gt;, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListHeaders&gt;&gt;" Usage="iComputeNodeOperations.ListNextWithHttpMessagesAsync (nextPageLink, computeNodeListNextOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNode&gt;,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="computeNodeListNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListNextOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="35a8c-176">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="35a8c-176">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="computeNodeListNextOptions">
            <span data-ttu-id="35a8c-177">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="35a8c-177">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="35a8c-178">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="35a8c-178">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="35a8c-179">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="35a8c-179">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="35a8c-180">指定したプール内の計算ノードを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="35a8c-180">Lists the compute nodes in the specified pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="35a8c-181">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="35a8c-181">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="35a8c-182">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="35a8c-182">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="35a8c-183">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="35a8c-183">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNode&gt;,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListHeaders&gt;&gt; ListWithHttpMessagesAsync (string poolId, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListOptions computeNodeListOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNode&gt;, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListHeaders&gt;&gt; ListWithHttpMessagesAsync(string poolId, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListOptions computeNodeListOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IComputeNodeOperations.ListWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNode&gt;, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListHeaders&gt;&gt;" Usage="iComputeNodeOperations.ListWithHttpMessagesAsync (poolId, computeNodeListOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNode&gt;,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeListOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            <span data-ttu-id="35a8c-184">リストのノードにプールの ID。</span><span class="sxs-lookup"><span data-stu-id="35a8c-184">The ID of the pool from which you want to list nodes.</span></span>
            </param>
        <param name="computeNodeListOptions">
            <span data-ttu-id="35a8c-185">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="35a8c-185">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="35a8c-186">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="35a8c-186">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="35a8c-187">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="35a8c-187">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="35a8c-188">指定したプール内の計算ノードを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="35a8c-188">Lists the compute nodes in the specified pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="35a8c-189">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="35a8c-189">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="35a8c-190">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="35a8c-190">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="35a8c-191">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="35a8c-191">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RebootWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootHeaders&gt;&gt; RebootWithHttpMessagesAsync (string poolId, string nodeId, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOption&gt; nodeRebootOption = null, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOptions computeNodeRebootOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootHeaders&gt;&gt; RebootWithHttpMessagesAsync(string poolId, string nodeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOption&gt; nodeRebootOption, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOptions computeNodeRebootOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IComputeNodeOperations.RebootWithHttpMessagesAsync(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOption},Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RebootWithHttpMessagesAsync : string * string * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOption&gt; * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootHeaders&gt;&gt;" Usage="iComputeNodeOperations.RebootWithHttpMessagesAsync (poolId, nodeId, nodeRebootOption, computeNodeRebootOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="nodeRebootOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOption&gt;" />
        <Parameter Name="computeNodeRebootOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            <span data-ttu-id="35a8c-192">コンピューティング ノードを含むプールの ID。</span><span class="sxs-lookup"><span data-stu-id="35a8c-192">The ID of the pool that contains the compute node.</span></span>
            </param>
        <param name="nodeId">
            <span data-ttu-id="35a8c-193">再起動するコンピューティング ノードの ID。</span><span class="sxs-lookup"><span data-stu-id="35a8c-193">The ID of the compute node that you want to restart.</span></span>
            </param>
        <param name="nodeRebootOption">
            <span data-ttu-id="35a8c-194">コンピューティング ノードを再起動するタイミングと、実行中のタスクの処理方法します。</span><span class="sxs-lookup"><span data-stu-id="35a8c-194">When to reboot the compute node and what to do with currently running tasks.</span></span> <span data-ttu-id="35a8c-195">既定値は requeue です。</span><span class="sxs-lookup"><span data-stu-id="35a8c-195">The default value is requeue.</span></span> <span data-ttu-id="35a8c-196">使用可能な値が含まれます: 'requeue'、'終了'、'taskCompletion'、'retainedData'</span><span class="sxs-lookup"><span data-stu-id="35a8c-196">Possible values include: 'requeue', 'terminate', 'taskCompletion', 'retainedData'</span></span>
            </param>
        <param name="computeNodeRebootOptions">
            <span data-ttu-id="35a8c-197">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="35a8c-197">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="35a8c-198">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="35a8c-198">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="35a8c-199">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="35a8c-199">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="35a8c-200">指定された計算ノードを再起動します。</span><span class="sxs-lookup"><span data-stu-id="35a8c-200">Restarts the specified compute node.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="35a8c-201">アイドル状態または実行中の状態である場合にのみ、ノードを再起動したことができます。</span><span class="sxs-lookup"><span data-stu-id="35a8c-201">You can restart a node only if it is in an idle or running state.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="35a8c-202">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="35a8c-202">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="35a8c-203">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="35a8c-203">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ReimageWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageHeaders&gt;&gt; ReimageWithHttpMessagesAsync (string poolId, string nodeId, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption&gt; nodeReimageOption = null, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOptions computeNodeReimageOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageHeaders&gt;&gt; ReimageWithHttpMessagesAsync(string poolId, string nodeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption&gt; nodeReimageOption, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOptions computeNodeReimageOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IComputeNodeOperations.ReimageWithHttpMessagesAsync(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption},Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ReimageWithHttpMessagesAsync : string * string * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption&gt; * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageHeaders&gt;&gt;" Usage="iComputeNodeOperations.ReimageWithHttpMessagesAsync (poolId, nodeId, nodeReimageOption, computeNodeReimageOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="nodeReimageOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption&gt;" />
        <Parameter Name="computeNodeReimageOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            <span data-ttu-id="35a8c-204">コンピューティング ノードを含むプールの ID。</span><span class="sxs-lookup"><span data-stu-id="35a8c-204">The ID of the pool that contains the compute node.</span></span>
            </param>
        <param name="nodeId">
            <span data-ttu-id="35a8c-205">再起動するコンピューティング ノードの ID。</span><span class="sxs-lookup"><span data-stu-id="35a8c-205">The ID of the compute node that you want to restart.</span></span>
            </param>
        <param name="nodeReimageOption">
            <span data-ttu-id="35a8c-206">コンピューティング ノードを再イメージ化する場合と実行中のタスクを行うには新機能です。</span><span class="sxs-lookup"><span data-stu-id="35a8c-206">When to reimage the compute node and what to do with currently running tasks.</span></span> <span data-ttu-id="35a8c-207">既定値は requeue です。</span><span class="sxs-lookup"><span data-stu-id="35a8c-207">The default value is requeue.</span></span> <span data-ttu-id="35a8c-208">使用可能な値が含まれます: 'requeue'、'終了'、'taskCompletion'、'retainedData'</span><span class="sxs-lookup"><span data-stu-id="35a8c-208">Possible values include: 'requeue', 'terminate', 'taskCompletion', 'retainedData'</span></span>
            </param>
        <param name="computeNodeReimageOptions">
            <span data-ttu-id="35a8c-209">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="35a8c-209">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="35a8c-210">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="35a8c-210">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="35a8c-211">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="35a8c-211">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="35a8c-212">指定したコンピューティング ノードで、オペレーティング システムを再インストールします。</span><span class="sxs-lookup"><span data-stu-id="35a8c-212">Reinstalls the operating system on the specified compute node.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="35a8c-213">アイドル状態または実行中の状態である場合にのみ、ノードにオペレーティング システムを再インストールすることができます。</span><span class="sxs-lookup"><span data-stu-id="35a8c-213">You can reinstall the operating system on a node only if it is in an idle or running state.</span></span> <span data-ttu-id="35a8c-214">この API は、クラウド サービスの構成プロパティを使用して作成されたプールでのみ呼び出すことができます。</span><span class="sxs-lookup"><span data-stu-id="35a8c-214">This API can be invoked only on pools created with the cloud service configuration property.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="35a8c-215">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="35a8c-215">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="35a8c-216">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="35a8c-216">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateUserWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUpdateUserHeaders&gt;&gt; UpdateUserWithHttpMessagesAsync (string poolId, string nodeId, string userName, Microsoft.Azure.Batch.Protocol.Models.NodeUpdateUserParameter nodeUpdateUserParameter, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUpdateUserOptions computeNodeUpdateUserOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUpdateUserHeaders&gt;&gt; UpdateUserWithHttpMessagesAsync(string poolId, string nodeId, string userName, class Microsoft.Azure.Batch.Protocol.Models.NodeUpdateUserParameter nodeUpdateUserParameter, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUpdateUserOptions computeNodeUpdateUserOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IComputeNodeOperations.UpdateUserWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.NodeUpdateUserParameter,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUpdateUserOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateUserWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Batch.Protocol.Models.NodeUpdateUserParameter * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUpdateUserOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUpdateUserHeaders&gt;&gt;" Usage="iComputeNodeOperations.UpdateUserWithHttpMessagesAsync (poolId, nodeId, userName, nodeUpdateUserParameter, computeNodeUpdateUserOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUpdateUserHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="userName" Type="System.String" />
        <Parameter Name="nodeUpdateUserParameter" Type="Microsoft.Azure.Batch.Protocol.Models.NodeUpdateUserParameter" />
        <Parameter Name="computeNodeUpdateUserOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUpdateUserOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            <span data-ttu-id="35a8c-217">コンピューティング ノードを含むプールの ID。</span><span class="sxs-lookup"><span data-stu-id="35a8c-217">The ID of the pool that contains the compute node.</span></span>
            </param>
        <param name="nodeId">
            <span data-ttu-id="35a8c-218">ユーザー アカウントを更新するコンピューターの ID。</span><span class="sxs-lookup"><span data-stu-id="35a8c-218">The ID of the machine on which you want to update a user account.</span></span>
            </param>
        <param name="userName">
            <span data-ttu-id="35a8c-219">更新するユーザー アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="35a8c-219">The name of the user account to update.</span></span>
            </param>
        <param name="nodeUpdateUserParameter">
            <span data-ttu-id="35a8c-220">要求のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="35a8c-220">The parameters for the request.</span></span>
            </param>
        <param name="computeNodeUpdateUserOptions">
            <span data-ttu-id="35a8c-221">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="35a8c-221">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="35a8c-222">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="35a8c-222">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="35a8c-223">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="35a8c-223">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="35a8c-224">指定された計算ノード上のユーザー アカウントのパスワードと有効期限の時間を更新します。</span><span class="sxs-lookup"><span data-stu-id="35a8c-224">Updates the password and expiration time of a user account on the specified compute node.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="35a8c-225">この操作は、アカウントの更新可能なすべてのプロパティの置き換えられます。</span><span class="sxs-lookup"><span data-stu-id="35a8c-225">This operation replaces of all the updateable properties of the account.</span></span> <span data-ttu-id="35a8c-226">たとえば、expiryTime 要素が指定されていない場合は、現在の値がない左変更されていない、既定値に置き換えられます。</span><span class="sxs-lookup"><span data-stu-id="35a8c-226">For example, if the expiryTime element is not specified, the current value is replaced with the default value, not left unmodified.</span></span> <span data-ttu-id="35a8c-227">アイドル状態または実行中の状態にある場合にのみ、ノード上のユーザー アカウントを更新することができます。</span><span class="sxs-lookup"><span data-stu-id="35a8c-227">You can update a user account on a node only when it is in the idle or running state.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="35a8c-228">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="35a8c-228">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="35a8c-229">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="35a8c-229">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>