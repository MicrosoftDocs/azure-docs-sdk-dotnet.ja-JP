<Type Name="IFileOperations" FullName="Microsoft.Azure.Batch.Protocol.IFileOperations">
  <TypeSignature Language="C#" Value="public interface IFileOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IFileOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.IFileOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IFileOperations" />
  <TypeSignature Language="F#" Value="type IFileOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="701d0-101">FileOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="701d0-101">FileOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DeleteFromComputeNodeWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeHeaders&gt;&gt; DeleteFromComputeNodeWithHttpMessagesAsync (string poolId, string nodeId, string filePath, Nullable&lt;bool&gt; recursive = null, Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeOptions fileDeleteFromComputeNodeOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeHeaders&gt;&gt; DeleteFromComputeNodeWithHttpMessagesAsync(string poolId, string nodeId, string filePath, valuetype System.Nullable`1&lt;bool&gt; recursive, class Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeOptions fileDeleteFromComputeNodeOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IFileOperations.DeleteFromComputeNodeWithHttpMessagesAsync(System.String,System.String,System.String,System.Nullable{System.Boolean},Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteFromComputeNodeWithHttpMessagesAsync : string * string * string * Nullable&lt;bool&gt; * Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeHeaders&gt;&gt;" Usage="iFileOperations.DeleteFromComputeNodeWithHttpMessagesAsync (poolId, nodeId, filePath, recursive, fileDeleteFromComputeNodeOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="fileDeleteFromComputeNodeOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            <span data-ttu-id="701d0-102">コンピューティング ノードを含むプールの ID。</span><span class="sxs-lookup"><span data-stu-id="701d0-102">The ID of the pool that contains the compute node.</span></span>
            </param>
        <param name="nodeId">
            <span data-ttu-id="701d0-103">ファイルを削除するコンピューティング ノードの ID。</span><span class="sxs-lookup"><span data-stu-id="701d0-103">The ID of the compute node from which you want to delete the file.</span></span>
            </param>
        <param name="filePath">
            <span data-ttu-id="701d0-104">ファイルまたはディレクトリを削除するにへのパス。</span><span class="sxs-lookup"><span data-stu-id="701d0-104">The path to the file or directory that you want to delete.</span></span>
            </param>
        <param name="recursive">
            <span data-ttu-id="701d0-105">ディレクトリの子を削除するかどうか。</span><span class="sxs-lookup"><span data-stu-id="701d0-105">Whether to delete children of a directory.</span></span> <span data-ttu-id="701d0-106">FilePath パラメーターを表す場合、ディレクトリ、ファイルではなくが再帰的に、ディレクトリを削除するには、すべてのファイルとサブディレクトリを設定できます。</span><span class="sxs-lookup"><span data-stu-id="701d0-106">If the filePath parameter represents a directory instead of a file, you can set recursive to true to delete the directory and all of the files and subdirectories in it.</span></span> <span data-ttu-id="701d0-107">再帰が false の場合、ディレクトリを空にする必要がありますか、削除は失敗します。</span><span class="sxs-lookup"><span data-stu-id="701d0-107">If recursive is false then the directory must be empty or deletion will fail.</span></span>
            </param>
        <param name="fileDeleteFromComputeNodeOptions">
            <span data-ttu-id="701d0-108">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="701d0-108">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="701d0-109">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="701d0-109">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="701d0-110">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="701d0-110">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="701d0-111">コンピューティング ノードから、指定したファイルを削除します。</span><span class="sxs-lookup"><span data-stu-id="701d0-111">Deletes the specified file from the compute node.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="701d0-112">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="701d0-112">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="701d0-113">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="701d0-113">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteFromTaskWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskHeaders&gt;&gt; DeleteFromTaskWithHttpMessagesAsync (string jobId, string taskId, string filePath, Nullable&lt;bool&gt; recursive = null, Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskOptions fileDeleteFromTaskOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskHeaders&gt;&gt; DeleteFromTaskWithHttpMessagesAsync(string jobId, string taskId, string filePath, valuetype System.Nullable`1&lt;bool&gt; recursive, class Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskOptions fileDeleteFromTaskOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IFileOperations.DeleteFromTaskWithHttpMessagesAsync(System.String,System.String,System.String,System.Nullable{System.Boolean},Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteFromTaskWithHttpMessagesAsync : string * string * string * Nullable&lt;bool&gt; * Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskHeaders&gt;&gt;" Usage="iFileOperations.DeleteFromTaskWithHttpMessagesAsync (jobId, taskId, filePath, recursive, fileDeleteFromTaskOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="fileDeleteFromTaskOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            <span data-ttu-id="701d0-114">タスクが含まれているジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="701d0-114">The ID of the job that contains the task.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="701d0-115">タスクを削除するファイルの ID。</span><span class="sxs-lookup"><span data-stu-id="701d0-115">The ID of the task whose file you want to delete.</span></span>
            </param>
        <param name="filePath">
            <span data-ttu-id="701d0-116">タスク ファイルまたはディレクトリを削除するにへのパス。</span><span class="sxs-lookup"><span data-stu-id="701d0-116">The path to the task file or directory that you want to delete.</span></span>
            </param>
        <param name="recursive">
            <span data-ttu-id="701d0-117">ディレクトリの子を削除するかどうか。</span><span class="sxs-lookup"><span data-stu-id="701d0-117">Whether to delete children of a directory.</span></span> <span data-ttu-id="701d0-118">FilePath パラメーターを表す場合、ディレクトリ、ファイルではなくが再帰的に、ディレクトリを削除するには、すべてのファイルとサブディレクトリを設定できます。</span><span class="sxs-lookup"><span data-stu-id="701d0-118">If the filePath parameter represents a directory instead of a file, you can set recursive to true to delete the directory and all of the files and subdirectories in it.</span></span> <span data-ttu-id="701d0-119">再帰が false の場合、ディレクトリを空にする必要がありますか、削除は失敗します。</span><span class="sxs-lookup"><span data-stu-id="701d0-119">If recursive is false then the directory must be empty or deletion will fail.</span></span>
            </param>
        <param name="fileDeleteFromTaskOptions">
            <span data-ttu-id="701d0-120">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="701d0-120">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="701d0-121">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="701d0-121">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="701d0-122">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="701d0-122">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="701d0-123">タスクが実行したコンピューティング ノードから、指定したタスク ファイルを削除します。</span><span class="sxs-lookup"><span data-stu-id="701d0-123">Deletes the specified task file from the compute node where the task ran.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="701d0-124">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="701d0-124">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="701d0-125">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="701d0-125">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetFromComputeNodeWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.IO.Stream,Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeHeaders&gt;&gt; GetFromComputeNodeWithHttpMessagesAsync (string poolId, string nodeId, string filePath, Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions fileGetFromComputeNodeOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class System.IO.Stream, class Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeHeaders&gt;&gt; GetFromComputeNodeWithHttpMessagesAsync(string poolId, string nodeId, string filePath, class Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions fileGetFromComputeNodeOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IFileOperations.GetFromComputeNodeWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetFromComputeNodeWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.IO.Stream, Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeHeaders&gt;&gt;" Usage="iFileOperations.GetFromComputeNodeWithHttpMessagesAsync (poolId, nodeId, filePath, fileGetFromComputeNodeOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.IO.Stream,Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="fileGetFromComputeNodeOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            <span data-ttu-id="701d0-126">コンピューティング ノードを含むプールの ID。</span><span class="sxs-lookup"><span data-stu-id="701d0-126">The ID of the pool that contains the compute node.</span></span>
            </param>
        <param name="nodeId">
            <span data-ttu-id="701d0-127">ファイルが格納されているコンピューティング ノードの ID。</span><span class="sxs-lookup"><span data-stu-id="701d0-127">The ID of the compute node that contains the file.</span></span>
            </param>
        <param name="filePath">
            <span data-ttu-id="701d0-128">コンテンツを取得するコンピューティング ノードのファイルへのパス。</span><span class="sxs-lookup"><span data-stu-id="701d0-128">The path to the compute node file that you want to get the content of.</span></span>
            </param>
        <param name="fileGetFromComputeNodeOptions">
            <span data-ttu-id="701d0-129">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="701d0-129">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="701d0-130">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="701d0-130">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="701d0-131">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="701d0-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="701d0-132">指定された計算ノードのファイルの内容を返します。</span><span class="sxs-lookup"><span data-stu-id="701d0-132">Returns the content of the specified compute node file.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="701d0-133">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="701d0-133">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="701d0-134">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="701d0-134">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="701d0-135">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="701d0-135">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetFromTaskWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.IO.Stream,Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders&gt;&gt; GetFromTaskWithHttpMessagesAsync (string jobId, string taskId, string filePath, Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskOptions fileGetFromTaskOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class System.IO.Stream, class Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders&gt;&gt; GetFromTaskWithHttpMessagesAsync(string jobId, string taskId, string filePath, class Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskOptions fileGetFromTaskOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IFileOperations.GetFromTaskWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetFromTaskWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.IO.Stream, Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders&gt;&gt;" Usage="iFileOperations.GetFromTaskWithHttpMessagesAsync (jobId, taskId, filePath, fileGetFromTaskOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.IO.Stream,Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="fileGetFromTaskOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            <span data-ttu-id="701d0-136">タスクが含まれているジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="701d0-136">The ID of the job that contains the task.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="701d0-137">タスクを取得するファイルの ID。</span><span class="sxs-lookup"><span data-stu-id="701d0-137">The ID of the task whose file you want to retrieve.</span></span>
            </param>
        <param name="filePath">
            <span data-ttu-id="701d0-138">コンテンツを取得するタスク ファイルへのパス。</span><span class="sxs-lookup"><span data-stu-id="701d0-138">The path to the task file that you want to get the content of.</span></span>
            </param>
        <param name="fileGetFromTaskOptions">
            <span data-ttu-id="701d0-139">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="701d0-139">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="701d0-140">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="701d0-140">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="701d0-141">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="701d0-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="701d0-142">指定したタスク ファイルの内容を返します。</span><span class="sxs-lookup"><span data-stu-id="701d0-142">Returns the content of the specified task file.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="701d0-143">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="701d0-143">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="701d0-144">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="701d0-144">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="701d0-145">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="701d0-145">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPropertiesFromComputeNodeWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeHeaders&gt;&gt; GetPropertiesFromComputeNodeWithHttpMessagesAsync (string poolId, string nodeId, string filePath, Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions fileGetPropertiesFromComputeNodeOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeHeaders&gt;&gt; GetPropertiesFromComputeNodeWithHttpMessagesAsync(string poolId, string nodeId, string filePath, class Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions fileGetPropertiesFromComputeNodeOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IFileOperations.GetPropertiesFromComputeNodeWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetPropertiesFromComputeNodeWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeHeaders&gt;&gt;" Usage="iFileOperations.GetPropertiesFromComputeNodeWithHttpMessagesAsync (poolId, nodeId, filePath, fileGetPropertiesFromComputeNodeOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="fileGetPropertiesFromComputeNodeOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            <span data-ttu-id="701d0-146">コンピューティング ノードを含むプールの ID。</span><span class="sxs-lookup"><span data-stu-id="701d0-146">The ID of the pool that contains the compute node.</span></span>
            </param>
        <param name="nodeId">
            <span data-ttu-id="701d0-147">ファイルが格納されているコンピューティング ノードの ID。</span><span class="sxs-lookup"><span data-stu-id="701d0-147">The ID of the compute node that contains the file.</span></span>
            </param>
        <param name="filePath">
            <span data-ttu-id="701d0-148">プロパティを取得するコンピューティング ノードのファイルへのパス。</span><span class="sxs-lookup"><span data-stu-id="701d0-148">The path to the compute node file that you want to get the properties of.</span></span>
            </param>
        <param name="fileGetPropertiesFromComputeNodeOptions">
            <span data-ttu-id="701d0-149">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="701d0-149">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="701d0-150">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="701d0-150">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="701d0-151">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="701d0-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="701d0-152">指定された計算ノードのファイルのプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="701d0-152">Gets the properties of the specified compute node file.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="701d0-153">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="701d0-153">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="701d0-154">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="701d0-154">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPropertiesFromTaskWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders&gt;&gt; GetPropertiesFromTaskWithHttpMessagesAsync (string jobId, string taskId, string filePath, Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskOptions fileGetPropertiesFromTaskOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders&gt;&gt; GetPropertiesFromTaskWithHttpMessagesAsync(string jobId, string taskId, string filePath, class Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskOptions fileGetPropertiesFromTaskOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IFileOperations.GetPropertiesFromTaskWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetPropertiesFromTaskWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders&gt;&gt;" Usage="iFileOperations.GetPropertiesFromTaskWithHttpMessagesAsync (jobId, taskId, filePath, fileGetPropertiesFromTaskOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="fileGetPropertiesFromTaskOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            <span data-ttu-id="701d0-155">タスクが含まれているジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="701d0-155">The ID of the job that contains the task.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="701d0-156">タスクのプロパティを取得するファイルの ID。</span><span class="sxs-lookup"><span data-stu-id="701d0-156">The ID of the task whose file you want to get the properties of.</span></span>
            </param>
        <param name="filePath">
            <span data-ttu-id="701d0-157">プロパティを取得するタスク ファイルへのパス。</span><span class="sxs-lookup"><span data-stu-id="701d0-157">The path to the task file that you want to get the properties of.</span></span>
            </param>
        <param name="fileGetPropertiesFromTaskOptions">
            <span data-ttu-id="701d0-158">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="701d0-158">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="701d0-159">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="701d0-159">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="701d0-160">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="701d0-160">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="701d0-161">指定したタスク ファイルのプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="701d0-161">Gets the properties of the specified task file.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="701d0-162">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="701d0-162">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="701d0-163">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="701d0-163">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListFromComputeNodeNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;,Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeHeaders&gt;&gt; ListFromComputeNodeNextWithHttpMessagesAsync (string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeNextOptions fileListFromComputeNodeNextOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;, class Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeHeaders&gt;&gt; ListFromComputeNodeNextWithHttpMessagesAsync(string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeNextOptions fileListFromComputeNodeNextOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IFileOperations.ListFromComputeNodeNextWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeNextOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListFromComputeNodeNextWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeNextOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;, Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeHeaders&gt;&gt;" Usage="iFileOperations.ListFromComputeNodeNextWithHttpMessagesAsync (nextPageLink, fileListFromComputeNodeNextOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;,Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="fileListFromComputeNodeNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeNextOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="701d0-164">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="701d0-164">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="fileListFromComputeNodeNextOptions">
            <span data-ttu-id="701d0-165">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="701d0-165">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="701d0-166">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="701d0-166">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="701d0-167">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="701d0-167">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="701d0-168">すべての作業ディレクトリにファイルを指定された計算ノードに一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="701d0-168">Lists all of the files in task directories on the specified compute node.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="701d0-169">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="701d0-169">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="701d0-170">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="701d0-170">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="701d0-171">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="701d0-171">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListFromComputeNodeWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;,Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeHeaders&gt;&gt; ListFromComputeNodeWithHttpMessagesAsync (string poolId, string nodeId, Nullable&lt;bool&gt; recursive = null, Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeOptions fileListFromComputeNodeOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;, class Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeHeaders&gt;&gt; ListFromComputeNodeWithHttpMessagesAsync(string poolId, string nodeId, valuetype System.Nullable`1&lt;bool&gt; recursive, class Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeOptions fileListFromComputeNodeOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IFileOperations.ListFromComputeNodeWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Boolean},Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListFromComputeNodeWithHttpMessagesAsync : string * string * Nullable&lt;bool&gt; * Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;, Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeHeaders&gt;&gt;" Usage="iFileOperations.ListFromComputeNodeWithHttpMessagesAsync (poolId, nodeId, recursive, fileListFromComputeNodeOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;,Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="fileListFromComputeNodeOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            <span data-ttu-id="701d0-172">コンピューティング ノードを含むプールの ID。</span><span class="sxs-lookup"><span data-stu-id="701d0-172">The ID of the pool that contains the compute node.</span></span>
            </param>
        <param name="nodeId">
            <span data-ttu-id="701d0-173">コンピューティング ノードの一覧を表示するファイルの ID。</span><span class="sxs-lookup"><span data-stu-id="701d0-173">The ID of the compute node whose files you want to list.</span></span>
            </param>
        <param name="recursive">
            <span data-ttu-id="701d0-174">ディレクトリの子の一覧を表示するかどうか。</span><span class="sxs-lookup"><span data-stu-id="701d0-174">Whether to list children of a directory.</span></span>
            </param>
        <param name="fileListFromComputeNodeOptions">
            <span data-ttu-id="701d0-175">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="701d0-175">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="701d0-176">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="701d0-176">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="701d0-177">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="701d0-177">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="701d0-178">すべての作業ディレクトリにファイルを指定された計算ノードに一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="701d0-178">Lists all of the files in task directories on the specified compute node.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="701d0-179">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="701d0-179">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="701d0-180">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="701d0-180">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="701d0-181">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="701d0-181">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListFromTaskNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;,Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskHeaders&gt;&gt; ListFromTaskNextWithHttpMessagesAsync (string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskNextOptions fileListFromTaskNextOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;, class Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskHeaders&gt;&gt; ListFromTaskNextWithHttpMessagesAsync(string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskNextOptions fileListFromTaskNextOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IFileOperations.ListFromTaskNextWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskNextOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListFromTaskNextWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskNextOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;, Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskHeaders&gt;&gt;" Usage="iFileOperations.ListFromTaskNextWithHttpMessagesAsync (nextPageLink, fileListFromTaskNextOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;,Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="fileListFromTaskNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskNextOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="701d0-182">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="701d0-182">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="fileListFromTaskNextOptions">
            <span data-ttu-id="701d0-183">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="701d0-183">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="701d0-184">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="701d0-184">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="701d0-185">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="701d0-185">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="701d0-186">コンピューティング ノードでは、タスクのディレクトリ内のファイルを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="701d0-186">Lists the files in a task's directory on its compute node.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="701d0-187">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="701d0-187">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="701d0-188">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="701d0-188">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="701d0-189">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="701d0-189">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListFromTaskWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;,Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskHeaders&gt;&gt; ListFromTaskWithHttpMessagesAsync (string jobId, string taskId, Nullable&lt;bool&gt; recursive = null, Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskOptions fileListFromTaskOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;, class Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskHeaders&gt;&gt; ListFromTaskWithHttpMessagesAsync(string jobId, string taskId, valuetype System.Nullable`1&lt;bool&gt; recursive, class Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskOptions fileListFromTaskOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IFileOperations.ListFromTaskWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Boolean},Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListFromTaskWithHttpMessagesAsync : string * string * Nullable&lt;bool&gt; * Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;, Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskHeaders&gt;&gt;" Usage="iFileOperations.ListFromTaskWithHttpMessagesAsync (jobId, taskId, recursive, fileListFromTaskOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;,Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="fileListFromTaskOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            <span data-ttu-id="701d0-190">タスクが含まれているジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="701d0-190">The ID of the job that contains the task.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="701d0-191">タスク一覧を表示するファイルの ID。</span><span class="sxs-lookup"><span data-stu-id="701d0-191">The ID of the task whose files you want to list.</span></span>
            </param>
        <param name="recursive">
            <span data-ttu-id="701d0-192">作業ディレクトリの子の一覧を表示するかどうか。</span><span class="sxs-lookup"><span data-stu-id="701d0-192">Whether to list children of the task directory.</span></span> <span data-ttu-id="701d0-193">このパラメーターは、特定の種類のファイルの一覧にフィルター パラメーターと組み合わせて使用できます。</span><span class="sxs-lookup"><span data-stu-id="701d0-193">This parameter can be used in combination with the filter parameter to list specific type of files.</span></span>
            </param>
        <param name="fileListFromTaskOptions">
            <span data-ttu-id="701d0-194">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="701d0-194">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="701d0-195">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="701d0-195">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="701d0-196">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="701d0-196">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="701d0-197">コンピューティング ノードでは、タスクのディレクトリ内のファイルを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="701d0-197">Lists the files in a task's directory on its compute node.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="701d0-198">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="701d0-198">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="701d0-199">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="701d0-199">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="701d0-200">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="701d0-200">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>