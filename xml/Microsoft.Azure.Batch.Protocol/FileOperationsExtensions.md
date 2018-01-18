<Type Name="FileOperationsExtensions" FullName="Microsoft.Azure.Batch.Protocol.FileOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class FileOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit FileOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.FileOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module FileOperationsExtensions" />
  <TypeSignature Language="F#" Value="type FileOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="52743-101">FileOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="52743-101">Extension methods for FileOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DeleteFromComputeNode">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeHeaders DeleteFromComputeNode (this Microsoft.Azure.Batch.Protocol.IFileOperations operations, string poolId, string nodeId, string filePath, Nullable&lt;bool&gt; recursive = null, Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeOptions fileDeleteFromComputeNodeOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeHeaders DeleteFromComputeNode(class Microsoft.Azure.Batch.Protocol.IFileOperations operations, string poolId, string nodeId, string filePath, valuetype System.Nullable`1&lt;bool&gt; recursive, class Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeOptions fileDeleteFromComputeNodeOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.DeleteFromComputeNode(Microsoft.Azure.Batch.Protocol.IFileOperations,System.String,System.String,System.String,System.Nullable{System.Boolean},Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeOptions)" />
      <MemberSignature Language="F#" Value="static member DeleteFromComputeNode : Microsoft.Azure.Batch.Protocol.IFileOperations * string * string * string * Nullable&lt;bool&gt; * Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeHeaders" Usage="Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.DeleteFromComputeNode (operations, poolId, nodeId, filePath, recursive, fileDeleteFromComputeNodeOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IFileOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="fileDeleteFromComputeNodeOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="52743-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="52743-102">The operations group for this extension method.</span></span>
            </param>
        <param name="poolId">
            <span data-ttu-id="52743-103">コンピューティング ノードを含むプールの ID。</span><span class="sxs-lookup"><span data-stu-id="52743-103">The ID of the pool that contains the compute node.</span></span>
            </param>
        <param name="nodeId">
            <span data-ttu-id="52743-104">ファイルを削除するコンピューティング ノードの ID。</span><span class="sxs-lookup"><span data-stu-id="52743-104">The ID of the compute node from which you want to delete the file.</span></span>
            </param>
        <param name="filePath">
            <span data-ttu-id="52743-105">ファイルまたはディレクトリを削除するにへのパス。</span><span class="sxs-lookup"><span data-stu-id="52743-105">The path to the file or directory that you want to delete.</span></span>
            </param>
        <param name="recursive">
            <span data-ttu-id="52743-106">ディレクトリの子を削除するかどうか。</span><span class="sxs-lookup"><span data-stu-id="52743-106">Whether to delete children of a directory.</span></span> <span data-ttu-id="52743-107">FilePath パラメーターを表す場合、ディレクトリ、ファイルではなくが再帰的に、ディレクトリを削除するには、すべてのファイルとサブディレクトリを設定できます。</span><span class="sxs-lookup"><span data-stu-id="52743-107">If the filePath parameter represents a directory instead of a file, you can set recursive to true to delete the directory and all of the files and subdirectories in it.</span></span> <span data-ttu-id="52743-108">再帰が false の場合、ディレクトリを空にする必要がありますか、削除は失敗します。</span><span class="sxs-lookup"><span data-stu-id="52743-108">If recursive is false then the directory must be empty or deletion will fail.</span></span>
            </param>
        <param name="fileDeleteFromComputeNodeOptions">
            <span data-ttu-id="52743-109">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="52743-109">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="52743-110">コンピューティング ノードから、指定したファイルを削除します。</span><span class="sxs-lookup"><span data-stu-id="52743-110">Deletes the specified file from the compute node.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteFromComputeNodeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeHeaders&gt; DeleteFromComputeNodeAsync (this Microsoft.Azure.Batch.Protocol.IFileOperations operations, string poolId, string nodeId, string filePath, Nullable&lt;bool&gt; recursive = null, Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeOptions fileDeleteFromComputeNodeOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeHeaders&gt; DeleteFromComputeNodeAsync(class Microsoft.Azure.Batch.Protocol.IFileOperations operations, string poolId, string nodeId, string filePath, valuetype System.Nullable`1&lt;bool&gt; recursive, class Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeOptions fileDeleteFromComputeNodeOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.DeleteFromComputeNodeAsync(Microsoft.Azure.Batch.Protocol.IFileOperations,System.String,System.String,System.String,System.Nullable{System.Boolean},Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteFromComputeNodeAsync : Microsoft.Azure.Batch.Protocol.IFileOperations * string * string * string * Nullable&lt;bool&gt; * Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.DeleteFromComputeNodeAsync (operations, poolId, nodeId, filePath, recursive, fileDeleteFromComputeNodeOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.FileOperationsExtensions/&lt;DeleteFromComputeNodeAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IFileOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="fileDeleteFromComputeNodeOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="52743-111">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="52743-111">The operations group for this extension method.</span></span>
            </param>
        <param name="poolId">
            <span data-ttu-id="52743-112">コンピューティング ノードを含むプールの ID。</span><span class="sxs-lookup"><span data-stu-id="52743-112">The ID of the pool that contains the compute node.</span></span>
            </param>
        <param name="nodeId">
            <span data-ttu-id="52743-113">ファイルを削除するコンピューティング ノードの ID。</span><span class="sxs-lookup"><span data-stu-id="52743-113">The ID of the compute node from which you want to delete the file.</span></span>
            </param>
        <param name="filePath">
            <span data-ttu-id="52743-114">ファイルまたはディレクトリを削除するにへのパス。</span><span class="sxs-lookup"><span data-stu-id="52743-114">The path to the file or directory that you want to delete.</span></span>
            </param>
        <param name="recursive">
            <span data-ttu-id="52743-115">ディレクトリの子を削除するかどうか。</span><span class="sxs-lookup"><span data-stu-id="52743-115">Whether to delete children of a directory.</span></span> <span data-ttu-id="52743-116">FilePath パラメーターを表す場合、ディレクトリ、ファイルではなくが再帰的に、ディレクトリを削除するには、すべてのファイルとサブディレクトリを設定できます。</span><span class="sxs-lookup"><span data-stu-id="52743-116">If the filePath parameter represents a directory instead of a file, you can set recursive to true to delete the directory and all of the files and subdirectories in it.</span></span> <span data-ttu-id="52743-117">再帰が false の場合、ディレクトリを空にする必要がありますか、削除は失敗します。</span><span class="sxs-lookup"><span data-stu-id="52743-117">If recursive is false then the directory must be empty or deletion will fail.</span></span>
            </param>
        <param name="fileDeleteFromComputeNodeOptions">
            <span data-ttu-id="52743-118">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="52743-118">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="52743-119">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="52743-119">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="52743-120">コンピューティング ノードから、指定したファイルを削除します。</span><span class="sxs-lookup"><span data-stu-id="52743-120">Deletes the specified file from the compute node.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteFromTask">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskHeaders DeleteFromTask (this Microsoft.Azure.Batch.Protocol.IFileOperations operations, string jobId, string taskId, string filePath, Nullable&lt;bool&gt; recursive = null, Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskOptions fileDeleteFromTaskOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskHeaders DeleteFromTask(class Microsoft.Azure.Batch.Protocol.IFileOperations operations, string jobId, string taskId, string filePath, valuetype System.Nullable`1&lt;bool&gt; recursive, class Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskOptions fileDeleteFromTaskOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.DeleteFromTask(Microsoft.Azure.Batch.Protocol.IFileOperations,System.String,System.String,System.String,System.Nullable{System.Boolean},Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskOptions)" />
      <MemberSignature Language="F#" Value="static member DeleteFromTask : Microsoft.Azure.Batch.Protocol.IFileOperations * string * string * string * Nullable&lt;bool&gt; * Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskHeaders" Usage="Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.DeleteFromTask (operations, jobId, taskId, filePath, recursive, fileDeleteFromTaskOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IFileOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="fileDeleteFromTaskOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="52743-121">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="52743-121">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="52743-122">タスクが含まれているジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="52743-122">The ID of the job that contains the task.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="52743-123">タスクを削除するファイルの ID。</span><span class="sxs-lookup"><span data-stu-id="52743-123">The ID of the task whose file you want to delete.</span></span>
            </param>
        <param name="filePath">
            <span data-ttu-id="52743-124">タスク ファイルまたはディレクトリを削除するにへのパス。</span><span class="sxs-lookup"><span data-stu-id="52743-124">The path to the task file or directory that you want to delete.</span></span>
            </param>
        <param name="recursive">
            <span data-ttu-id="52743-125">ディレクトリの子を削除するかどうか。</span><span class="sxs-lookup"><span data-stu-id="52743-125">Whether to delete children of a directory.</span></span> <span data-ttu-id="52743-126">FilePath パラメーターを表す場合、ディレクトリ、ファイルではなくが再帰的に、ディレクトリを削除するには、すべてのファイルとサブディレクトリを設定できます。</span><span class="sxs-lookup"><span data-stu-id="52743-126">If the filePath parameter represents a directory instead of a file, you can set recursive to true to delete the directory and all of the files and subdirectories in it.</span></span> <span data-ttu-id="52743-127">再帰が false の場合、ディレクトリを空にする必要がありますか、削除は失敗します。</span><span class="sxs-lookup"><span data-stu-id="52743-127">If recursive is false then the directory must be empty or deletion will fail.</span></span>
            </param>
        <param name="fileDeleteFromTaskOptions">
            <span data-ttu-id="52743-128">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="52743-128">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="52743-129">タスクが実行したコンピューティング ノードから、指定したタスク ファイルを削除します。</span><span class="sxs-lookup"><span data-stu-id="52743-129">Deletes the specified task file from the compute node where the task ran.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteFromTaskAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskHeaders&gt; DeleteFromTaskAsync (this Microsoft.Azure.Batch.Protocol.IFileOperations operations, string jobId, string taskId, string filePath, Nullable&lt;bool&gt; recursive = null, Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskOptions fileDeleteFromTaskOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskHeaders&gt; DeleteFromTaskAsync(class Microsoft.Azure.Batch.Protocol.IFileOperations operations, string jobId, string taskId, string filePath, valuetype System.Nullable`1&lt;bool&gt; recursive, class Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskOptions fileDeleteFromTaskOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.DeleteFromTaskAsync(Microsoft.Azure.Batch.Protocol.IFileOperations,System.String,System.String,System.String,System.Nullable{System.Boolean},Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteFromTaskAsync : Microsoft.Azure.Batch.Protocol.IFileOperations * string * string * string * Nullable&lt;bool&gt; * Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.DeleteFromTaskAsync (operations, jobId, taskId, filePath, recursive, fileDeleteFromTaskOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.FileOperationsExtensions/&lt;DeleteFromTaskAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IFileOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="fileDeleteFromTaskOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="52743-130">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="52743-130">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="52743-131">タスクが含まれているジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="52743-131">The ID of the job that contains the task.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="52743-132">タスクを削除するファイルの ID。</span><span class="sxs-lookup"><span data-stu-id="52743-132">The ID of the task whose file you want to delete.</span></span>
            </param>
        <param name="filePath">
            <span data-ttu-id="52743-133">タスク ファイルまたはディレクトリを削除するにへのパス。</span><span class="sxs-lookup"><span data-stu-id="52743-133">The path to the task file or directory that you want to delete.</span></span>
            </param>
        <param name="recursive">
            <span data-ttu-id="52743-134">ディレクトリの子を削除するかどうか。</span><span class="sxs-lookup"><span data-stu-id="52743-134">Whether to delete children of a directory.</span></span> <span data-ttu-id="52743-135">FilePath パラメーターを表す場合、ディレクトリ、ファイルではなくが再帰的に、ディレクトリを削除するには、すべてのファイルとサブディレクトリを設定できます。</span><span class="sxs-lookup"><span data-stu-id="52743-135">If the filePath parameter represents a directory instead of a file, you can set recursive to true to delete the directory and all of the files and subdirectories in it.</span></span> <span data-ttu-id="52743-136">再帰が false の場合、ディレクトリを空にする必要がありますか、削除は失敗します。</span><span class="sxs-lookup"><span data-stu-id="52743-136">If recursive is false then the directory must be empty or deletion will fail.</span></span>
            </param>
        <param name="fileDeleteFromTaskOptions">
            <span data-ttu-id="52743-137">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="52743-137">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="52743-138">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="52743-138">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="52743-139">タスクが実行したコンピューティング ノードから、指定したタスク ファイルを削除します。</span><span class="sxs-lookup"><span data-stu-id="52743-139">Deletes the specified task file from the compute node where the task ran.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFromComputeNode">
      <MemberSignature Language="C#" Value="public static System.IO.Stream GetFromComputeNode (this Microsoft.Azure.Batch.Protocol.IFileOperations operations, string poolId, string nodeId, string filePath, Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions fileGetFromComputeNodeOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.IO.Stream GetFromComputeNode(class Microsoft.Azure.Batch.Protocol.IFileOperations operations, string poolId, string nodeId, string filePath, class Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions fileGetFromComputeNodeOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.GetFromComputeNode(Microsoft.Azure.Batch.Protocol.IFileOperations,System.String,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions)" />
      <MemberSignature Language="F#" Value="static member GetFromComputeNode : Microsoft.Azure.Batch.Protocol.IFileOperations * string * string * string * Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions -&gt; System.IO.Stream" Usage="Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.GetFromComputeNode (operations, poolId, nodeId, filePath, fileGetFromComputeNodeOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IO.Stream</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IFileOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="fileGetFromComputeNodeOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="52743-140">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="52743-140">The operations group for this extension method.</span></span>
            </param>
        <param name="poolId">
            <span data-ttu-id="52743-141">コンピューティング ノードを含むプールの ID。</span><span class="sxs-lookup"><span data-stu-id="52743-141">The ID of the pool that contains the compute node.</span></span>
            </param>
        <param name="nodeId">
            <span data-ttu-id="52743-142">ファイルが格納されているコンピューティング ノードの ID。</span><span class="sxs-lookup"><span data-stu-id="52743-142">The ID of the compute node that contains the file.</span></span>
            </param>
        <param name="filePath">
            <span data-ttu-id="52743-143">コンテンツを取得するコンピューティング ノードのファイルへのパス。</span><span class="sxs-lookup"><span data-stu-id="52743-143">The path to the compute node file that you want to get the content of.</span></span>
            </param>
        <param name="fileGetFromComputeNodeOptions">
            <span data-ttu-id="52743-144">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="52743-144">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="52743-145">指定された計算ノードのファイルの内容を返します。</span><span class="sxs-lookup"><span data-stu-id="52743-145">Returns the content of the specified compute node file.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFromComputeNodeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.IO.Stream&gt; GetFromComputeNodeAsync (this Microsoft.Azure.Batch.Protocol.IFileOperations operations, string poolId, string nodeId, string filePath, Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions fileGetFromComputeNodeOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.IO.Stream&gt; GetFromComputeNodeAsync(class Microsoft.Azure.Batch.Protocol.IFileOperations operations, string poolId, string nodeId, string filePath, class Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions fileGetFromComputeNodeOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.GetFromComputeNodeAsync(Microsoft.Azure.Batch.Protocol.IFileOperations,System.String,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetFromComputeNodeAsync : Microsoft.Azure.Batch.Protocol.IFileOperations * string * string * string * Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.IO.Stream&gt;" Usage="Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.GetFromComputeNodeAsync (operations, poolId, nodeId, filePath, fileGetFromComputeNodeOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.FileOperationsExtensions/&lt;GetFromComputeNodeAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.IO.Stream&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IFileOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="fileGetFromComputeNodeOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="52743-146">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="52743-146">The operations group for this extension method.</span></span>
            </param>
        <param name="poolId">
            <span data-ttu-id="52743-147">コンピューティング ノードを含むプールの ID。</span><span class="sxs-lookup"><span data-stu-id="52743-147">The ID of the pool that contains the compute node.</span></span>
            </param>
        <param name="nodeId">
            <span data-ttu-id="52743-148">ファイルが格納されているコンピューティング ノードの ID。</span><span class="sxs-lookup"><span data-stu-id="52743-148">The ID of the compute node that contains the file.</span></span>
            </param>
        <param name="filePath">
            <span data-ttu-id="52743-149">コンテンツを取得するコンピューティング ノードのファイルへのパス。</span><span class="sxs-lookup"><span data-stu-id="52743-149">The path to the compute node file that you want to get the content of.</span></span>
            </param>
        <param name="fileGetFromComputeNodeOptions">
            <span data-ttu-id="52743-150">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="52743-150">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="52743-151">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="52743-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="52743-152">指定された計算ノードのファイルの内容を返します。</span><span class="sxs-lookup"><span data-stu-id="52743-152">Returns the content of the specified compute node file.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFromTask">
      <MemberSignature Language="C#" Value="public static System.IO.Stream GetFromTask (this Microsoft.Azure.Batch.Protocol.IFileOperations operations, string jobId, string taskId, string filePath, Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskOptions fileGetFromTaskOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.IO.Stream GetFromTask(class Microsoft.Azure.Batch.Protocol.IFileOperations operations, string jobId, string taskId, string filePath, class Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskOptions fileGetFromTaskOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.GetFromTask(Microsoft.Azure.Batch.Protocol.IFileOperations,System.String,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskOptions)" />
      <MemberSignature Language="F#" Value="static member GetFromTask : Microsoft.Azure.Batch.Protocol.IFileOperations * string * string * string * Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskOptions -&gt; System.IO.Stream" Usage="Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.GetFromTask (operations, jobId, taskId, filePath, fileGetFromTaskOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IO.Stream</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IFileOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="fileGetFromTaskOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="52743-153">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="52743-153">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="52743-154">タスクが含まれているジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="52743-154">The ID of the job that contains the task.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="52743-155">タスクを取得するファイルの ID。</span><span class="sxs-lookup"><span data-stu-id="52743-155">The ID of the task whose file you want to retrieve.</span></span>
            </param>
        <param name="filePath">
            <span data-ttu-id="52743-156">コンテンツを取得するタスク ファイルへのパス。</span><span class="sxs-lookup"><span data-stu-id="52743-156">The path to the task file that you want to get the content of.</span></span>
            </param>
        <param name="fileGetFromTaskOptions">
            <span data-ttu-id="52743-157">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="52743-157">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="52743-158">指定したタスク ファイルの内容を返します。</span><span class="sxs-lookup"><span data-stu-id="52743-158">Returns the content of the specified task file.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFromTaskAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.IO.Stream&gt; GetFromTaskAsync (this Microsoft.Azure.Batch.Protocol.IFileOperations operations, string jobId, string taskId, string filePath, Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskOptions fileGetFromTaskOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.IO.Stream&gt; GetFromTaskAsync(class Microsoft.Azure.Batch.Protocol.IFileOperations operations, string jobId, string taskId, string filePath, class Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskOptions fileGetFromTaskOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.GetFromTaskAsync(Microsoft.Azure.Batch.Protocol.IFileOperations,System.String,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetFromTaskAsync : Microsoft.Azure.Batch.Protocol.IFileOperations * string * string * string * Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.IO.Stream&gt;" Usage="Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.GetFromTaskAsync (operations, jobId, taskId, filePath, fileGetFromTaskOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.FileOperationsExtensions/&lt;GetFromTaskAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.IO.Stream&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IFileOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="fileGetFromTaskOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="52743-159">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="52743-159">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="52743-160">タスクが含まれているジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="52743-160">The ID of the job that contains the task.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="52743-161">タスクを取得するファイルの ID。</span><span class="sxs-lookup"><span data-stu-id="52743-161">The ID of the task whose file you want to retrieve.</span></span>
            </param>
        <param name="filePath">
            <span data-ttu-id="52743-162">コンテンツを取得するタスク ファイルへのパス。</span><span class="sxs-lookup"><span data-stu-id="52743-162">The path to the task file that you want to get the content of.</span></span>
            </param>
        <param name="fileGetFromTaskOptions">
            <span data-ttu-id="52743-163">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="52743-163">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="52743-164">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="52743-164">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="52743-165">指定したタスク ファイルの内容を返します。</span><span class="sxs-lookup"><span data-stu-id="52743-165">Returns the content of the specified task file.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPropertiesFromComputeNode">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeHeaders GetPropertiesFromComputeNode (this Microsoft.Azure.Batch.Protocol.IFileOperations operations, string poolId, string nodeId, string filePath, Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions fileGetPropertiesFromComputeNodeOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeHeaders GetPropertiesFromComputeNode(class Microsoft.Azure.Batch.Protocol.IFileOperations operations, string poolId, string nodeId, string filePath, class Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions fileGetPropertiesFromComputeNodeOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.GetPropertiesFromComputeNode(Microsoft.Azure.Batch.Protocol.IFileOperations,System.String,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions)" />
      <MemberSignature Language="F#" Value="static member GetPropertiesFromComputeNode : Microsoft.Azure.Batch.Protocol.IFileOperations * string * string * string * Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeHeaders" Usage="Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.GetPropertiesFromComputeNode (operations, poolId, nodeId, filePath, fileGetPropertiesFromComputeNodeOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IFileOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="fileGetPropertiesFromComputeNodeOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="52743-166">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="52743-166">The operations group for this extension method.</span></span>
            </param>
        <param name="poolId">
            <span data-ttu-id="52743-167">コンピューティング ノードを含むプールの ID。</span><span class="sxs-lookup"><span data-stu-id="52743-167">The ID of the pool that contains the compute node.</span></span>
            </param>
        <param name="nodeId">
            <span data-ttu-id="52743-168">ファイルが格納されているコンピューティング ノードの ID。</span><span class="sxs-lookup"><span data-stu-id="52743-168">The ID of the compute node that contains the file.</span></span>
            </param>
        <param name="filePath">
            <span data-ttu-id="52743-169">プロパティを取得するコンピューティング ノードのファイルへのパス。</span><span class="sxs-lookup"><span data-stu-id="52743-169">The path to the compute node file that you want to get the properties of.</span></span>
            </param>
        <param name="fileGetPropertiesFromComputeNodeOptions">
            <span data-ttu-id="52743-170">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="52743-170">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="52743-171">指定された計算ノードのファイルのプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="52743-171">Gets the properties of the specified compute node file.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPropertiesFromComputeNodeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeHeaders&gt; GetPropertiesFromComputeNodeAsync (this Microsoft.Azure.Batch.Protocol.IFileOperations operations, string poolId, string nodeId, string filePath, Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions fileGetPropertiesFromComputeNodeOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeHeaders&gt; GetPropertiesFromComputeNodeAsync(class Microsoft.Azure.Batch.Protocol.IFileOperations operations, string poolId, string nodeId, string filePath, class Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions fileGetPropertiesFromComputeNodeOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.GetPropertiesFromComputeNodeAsync(Microsoft.Azure.Batch.Protocol.IFileOperations,System.String,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetPropertiesFromComputeNodeAsync : Microsoft.Azure.Batch.Protocol.IFileOperations * string * string * string * Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.GetPropertiesFromComputeNodeAsync (operations, poolId, nodeId, filePath, fileGetPropertiesFromComputeNodeOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.FileOperationsExtensions/&lt;GetPropertiesFromComputeNodeAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IFileOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="fileGetPropertiesFromComputeNodeOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="52743-172">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="52743-172">The operations group for this extension method.</span></span>
            </param>
        <param name="poolId">
            <span data-ttu-id="52743-173">コンピューティング ノードを含むプールの ID。</span><span class="sxs-lookup"><span data-stu-id="52743-173">The ID of the pool that contains the compute node.</span></span>
            </param>
        <param name="nodeId">
            <span data-ttu-id="52743-174">ファイルが格納されているコンピューティング ノードの ID。</span><span class="sxs-lookup"><span data-stu-id="52743-174">The ID of the compute node that contains the file.</span></span>
            </param>
        <param name="filePath">
            <span data-ttu-id="52743-175">プロパティを取得するコンピューティング ノードのファイルへのパス。</span><span class="sxs-lookup"><span data-stu-id="52743-175">The path to the compute node file that you want to get the properties of.</span></span>
            </param>
        <param name="fileGetPropertiesFromComputeNodeOptions">
            <span data-ttu-id="52743-176">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="52743-176">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="52743-177">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="52743-177">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="52743-178">指定された計算ノードのファイルのプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="52743-178">Gets the properties of the specified compute node file.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPropertiesFromTask">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders GetPropertiesFromTask (this Microsoft.Azure.Batch.Protocol.IFileOperations operations, string jobId, string taskId, string filePath, Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskOptions fileGetPropertiesFromTaskOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders GetPropertiesFromTask(class Microsoft.Azure.Batch.Protocol.IFileOperations operations, string jobId, string taskId, string filePath, class Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskOptions fileGetPropertiesFromTaskOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.GetPropertiesFromTask(Microsoft.Azure.Batch.Protocol.IFileOperations,System.String,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskOptions)" />
      <MemberSignature Language="F#" Value="static member GetPropertiesFromTask : Microsoft.Azure.Batch.Protocol.IFileOperations * string * string * string * Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders" Usage="Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.GetPropertiesFromTask (operations, jobId, taskId, filePath, fileGetPropertiesFromTaskOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IFileOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="fileGetPropertiesFromTaskOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="52743-179">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="52743-179">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="52743-180">タスクが含まれているジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="52743-180">The ID of the job that contains the task.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="52743-181">タスクのプロパティを取得するファイルの ID。</span><span class="sxs-lookup"><span data-stu-id="52743-181">The ID of the task whose file you want to get the properties of.</span></span>
            </param>
        <param name="filePath">
            <span data-ttu-id="52743-182">プロパティを取得するタスク ファイルへのパス。</span><span class="sxs-lookup"><span data-stu-id="52743-182">The path to the task file that you want to get the properties of.</span></span>
            </param>
        <param name="fileGetPropertiesFromTaskOptions">
            <span data-ttu-id="52743-183">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="52743-183">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="52743-184">指定したタスク ファイルのプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="52743-184">Gets the properties of the specified task file.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPropertiesFromTaskAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders&gt; GetPropertiesFromTaskAsync (this Microsoft.Azure.Batch.Protocol.IFileOperations operations, string jobId, string taskId, string filePath, Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskOptions fileGetPropertiesFromTaskOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders&gt; GetPropertiesFromTaskAsync(class Microsoft.Azure.Batch.Protocol.IFileOperations operations, string jobId, string taskId, string filePath, class Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskOptions fileGetPropertiesFromTaskOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.GetPropertiesFromTaskAsync(Microsoft.Azure.Batch.Protocol.IFileOperations,System.String,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetPropertiesFromTaskAsync : Microsoft.Azure.Batch.Protocol.IFileOperations * string * string * string * Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.GetPropertiesFromTaskAsync (operations, jobId, taskId, filePath, fileGetPropertiesFromTaskOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.FileOperationsExtensions/&lt;GetPropertiesFromTaskAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IFileOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="fileGetPropertiesFromTaskOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="52743-185">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="52743-185">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="52743-186">タスクが含まれているジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="52743-186">The ID of the job that contains the task.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="52743-187">タスクのプロパティを取得するファイルの ID。</span><span class="sxs-lookup"><span data-stu-id="52743-187">The ID of the task whose file you want to get the properties of.</span></span>
            </param>
        <param name="filePath">
            <span data-ttu-id="52743-188">プロパティを取得するタスク ファイルへのパス。</span><span class="sxs-lookup"><span data-stu-id="52743-188">The path to the task file that you want to get the properties of.</span></span>
            </param>
        <param name="fileGetPropertiesFromTaskOptions">
            <span data-ttu-id="52743-189">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="52743-189">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="52743-190">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="52743-190">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="52743-191">指定したタスク ファイルのプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="52743-191">Gets the properties of the specified task file.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFromComputeNode">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt; ListFromComputeNode (this Microsoft.Azure.Batch.Protocol.IFileOperations operations, string poolId, string nodeId, Nullable&lt;bool&gt; recursive = null, Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeOptions fileListFromComputeNodeOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt; ListFromComputeNode(class Microsoft.Azure.Batch.Protocol.IFileOperations operations, string poolId, string nodeId, valuetype System.Nullable`1&lt;bool&gt; recursive, class Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeOptions fileListFromComputeNodeOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.ListFromComputeNode(Microsoft.Azure.Batch.Protocol.IFileOperations,System.String,System.String,System.Nullable{System.Boolean},Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeOptions)" />
      <MemberSignature Language="F#" Value="static member ListFromComputeNode : Microsoft.Azure.Batch.Protocol.IFileOperations * string * string * Nullable&lt;bool&gt; * Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;" Usage="Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.ListFromComputeNode (operations, poolId, nodeId, recursive, fileListFromComputeNodeOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IFileOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="fileListFromComputeNodeOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="52743-192">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="52743-192">The operations group for this extension method.</span></span>
            </param>
        <param name="poolId">
            <span data-ttu-id="52743-193">コンピューティング ノードを含むプールの ID。</span><span class="sxs-lookup"><span data-stu-id="52743-193">The ID of the pool that contains the compute node.</span></span>
            </param>
        <param name="nodeId">
            <span data-ttu-id="52743-194">コンピューティング ノードの一覧を表示するファイルの ID。</span><span class="sxs-lookup"><span data-stu-id="52743-194">The ID of the compute node whose files you want to list.</span></span>
            </param>
        <param name="recursive">
            <span data-ttu-id="52743-195">ディレクトリの子の一覧を表示するかどうか。</span><span class="sxs-lookup"><span data-stu-id="52743-195">Whether to list children of a directory.</span></span>
            </param>
        <param name="fileListFromComputeNodeOptions">
            <span data-ttu-id="52743-196">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="52743-196">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="52743-197">すべての作業ディレクトリにファイルを指定された計算ノードに一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="52743-197">Lists all of the files in task directories on the specified compute node.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFromComputeNodeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;&gt; ListFromComputeNodeAsync (this Microsoft.Azure.Batch.Protocol.IFileOperations operations, string poolId, string nodeId, Nullable&lt;bool&gt; recursive = null, Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeOptions fileListFromComputeNodeOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;&gt; ListFromComputeNodeAsync(class Microsoft.Azure.Batch.Protocol.IFileOperations operations, string poolId, string nodeId, valuetype System.Nullable`1&lt;bool&gt; recursive, class Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeOptions fileListFromComputeNodeOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.ListFromComputeNodeAsync(Microsoft.Azure.Batch.Protocol.IFileOperations,System.String,System.String,System.Nullable{System.Boolean},Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListFromComputeNodeAsync : Microsoft.Azure.Batch.Protocol.IFileOperations * string * string * Nullable&lt;bool&gt; * Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.ListFromComputeNodeAsync (operations, poolId, nodeId, recursive, fileListFromComputeNodeOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.FileOperationsExtensions/&lt;ListFromComputeNodeAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IFileOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="fileListFromComputeNodeOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="52743-198">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="52743-198">The operations group for this extension method.</span></span>
            </param>
        <param name="poolId">
            <span data-ttu-id="52743-199">コンピューティング ノードを含むプールの ID。</span><span class="sxs-lookup"><span data-stu-id="52743-199">The ID of the pool that contains the compute node.</span></span>
            </param>
        <param name="nodeId">
            <span data-ttu-id="52743-200">コンピューティング ノードの一覧を表示するファイルの ID。</span><span class="sxs-lookup"><span data-stu-id="52743-200">The ID of the compute node whose files you want to list.</span></span>
            </param>
        <param name="recursive">
            <span data-ttu-id="52743-201">ディレクトリの子の一覧を表示するかどうか。</span><span class="sxs-lookup"><span data-stu-id="52743-201">Whether to list children of a directory.</span></span>
            </param>
        <param name="fileListFromComputeNodeOptions">
            <span data-ttu-id="52743-202">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="52743-202">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="52743-203">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="52743-203">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="52743-204">すべての作業ディレクトリにファイルを指定された計算ノードに一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="52743-204">Lists all of the files in task directories on the specified compute node.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFromComputeNodeNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt; ListFromComputeNodeNext (this Microsoft.Azure.Batch.Protocol.IFileOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeNextOptions fileListFromComputeNodeNextOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt; ListFromComputeNodeNext(class Microsoft.Azure.Batch.Protocol.IFileOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeNextOptions fileListFromComputeNodeNextOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.ListFromComputeNodeNext(Microsoft.Azure.Batch.Protocol.IFileOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeNextOptions)" />
      <MemberSignature Language="F#" Value="static member ListFromComputeNodeNext : Microsoft.Azure.Batch.Protocol.IFileOperations * string * Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeNextOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;" Usage="Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.ListFromComputeNodeNext (operations, nextPageLink, fileListFromComputeNodeNextOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IFileOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="fileListFromComputeNodeNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeNextOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="52743-205">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="52743-205">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="52743-206">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="52743-206">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="fileListFromComputeNodeNextOptions">
            <span data-ttu-id="52743-207">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="52743-207">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="52743-208">すべての作業ディレクトリにファイルを指定された計算ノードに一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="52743-208">Lists all of the files in task directories on the specified compute node.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFromComputeNodeNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;&gt; ListFromComputeNodeNextAsync (this Microsoft.Azure.Batch.Protocol.IFileOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeNextOptions fileListFromComputeNodeNextOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;&gt; ListFromComputeNodeNextAsync(class Microsoft.Azure.Batch.Protocol.IFileOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeNextOptions fileListFromComputeNodeNextOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.ListFromComputeNodeNextAsync(Microsoft.Azure.Batch.Protocol.IFileOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeNextOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListFromComputeNodeNextAsync : Microsoft.Azure.Batch.Protocol.IFileOperations * string * Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeNextOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.ListFromComputeNodeNextAsync (operations, nextPageLink, fileListFromComputeNodeNextOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.FileOperationsExtensions/&lt;ListFromComputeNodeNextAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IFileOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="fileListFromComputeNodeNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeNextOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="52743-209">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="52743-209">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="52743-210">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="52743-210">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="fileListFromComputeNodeNextOptions">
            <span data-ttu-id="52743-211">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="52743-211">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="52743-212">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="52743-212">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="52743-213">すべての作業ディレクトリにファイルを指定された計算ノードに一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="52743-213">Lists all of the files in task directories on the specified compute node.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFromTask">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt; ListFromTask (this Microsoft.Azure.Batch.Protocol.IFileOperations operations, string jobId, string taskId, Nullable&lt;bool&gt; recursive = null, Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskOptions fileListFromTaskOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt; ListFromTask(class Microsoft.Azure.Batch.Protocol.IFileOperations operations, string jobId, string taskId, valuetype System.Nullable`1&lt;bool&gt; recursive, class Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskOptions fileListFromTaskOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.ListFromTask(Microsoft.Azure.Batch.Protocol.IFileOperations,System.String,System.String,System.Nullable{System.Boolean},Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskOptions)" />
      <MemberSignature Language="F#" Value="static member ListFromTask : Microsoft.Azure.Batch.Protocol.IFileOperations * string * string * Nullable&lt;bool&gt; * Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;" Usage="Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.ListFromTask (operations, jobId, taskId, recursive, fileListFromTaskOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IFileOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="fileListFromTaskOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="52743-214">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="52743-214">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="52743-215">タスクが含まれているジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="52743-215">The ID of the job that contains the task.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="52743-216">タスク一覧を表示するファイルの ID。</span><span class="sxs-lookup"><span data-stu-id="52743-216">The ID of the task whose files you want to list.</span></span>
            </param>
        <param name="recursive">
            <span data-ttu-id="52743-217">作業ディレクトリの子の一覧を表示するかどうか。</span><span class="sxs-lookup"><span data-stu-id="52743-217">Whether to list children of the task directory.</span></span> <span data-ttu-id="52743-218">このパラメーターは、特定の種類のファイルの一覧にフィルター パラメーターと組み合わせて使用できます。</span><span class="sxs-lookup"><span data-stu-id="52743-218">This parameter can be used in combination with the filter parameter to list specific type of files.</span></span>
            </param>
        <param name="fileListFromTaskOptions">
            <span data-ttu-id="52743-219">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="52743-219">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="52743-220">コンピューティング ノードでは、タスクのディレクトリ内のファイルを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="52743-220">Lists the files in a task's directory on its compute node.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFromTaskAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;&gt; ListFromTaskAsync (this Microsoft.Azure.Batch.Protocol.IFileOperations operations, string jobId, string taskId, Nullable&lt;bool&gt; recursive = null, Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskOptions fileListFromTaskOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;&gt; ListFromTaskAsync(class Microsoft.Azure.Batch.Protocol.IFileOperations operations, string jobId, string taskId, valuetype System.Nullable`1&lt;bool&gt; recursive, class Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskOptions fileListFromTaskOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.ListFromTaskAsync(Microsoft.Azure.Batch.Protocol.IFileOperations,System.String,System.String,System.Nullable{System.Boolean},Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListFromTaskAsync : Microsoft.Azure.Batch.Protocol.IFileOperations * string * string * Nullable&lt;bool&gt; * Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.ListFromTaskAsync (operations, jobId, taskId, recursive, fileListFromTaskOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.FileOperationsExtensions/&lt;ListFromTaskAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IFileOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="fileListFromTaskOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="52743-221">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="52743-221">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="52743-222">タスクが含まれているジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="52743-222">The ID of the job that contains the task.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="52743-223">タスク一覧を表示するファイルの ID。</span><span class="sxs-lookup"><span data-stu-id="52743-223">The ID of the task whose files you want to list.</span></span>
            </param>
        <param name="recursive">
            <span data-ttu-id="52743-224">作業ディレクトリの子の一覧を表示するかどうか。</span><span class="sxs-lookup"><span data-stu-id="52743-224">Whether to list children of the task directory.</span></span> <span data-ttu-id="52743-225">このパラメーターは、特定の種類のファイルの一覧にフィルター パラメーターと組み合わせて使用できます。</span><span class="sxs-lookup"><span data-stu-id="52743-225">This parameter can be used in combination with the filter parameter to list specific type of files.</span></span>
            </param>
        <param name="fileListFromTaskOptions">
            <span data-ttu-id="52743-226">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="52743-226">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="52743-227">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="52743-227">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="52743-228">コンピューティング ノードでは、タスクのディレクトリ内のファイルを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="52743-228">Lists the files in a task's directory on its compute node.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFromTaskNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt; ListFromTaskNext (this Microsoft.Azure.Batch.Protocol.IFileOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskNextOptions fileListFromTaskNextOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt; ListFromTaskNext(class Microsoft.Azure.Batch.Protocol.IFileOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskNextOptions fileListFromTaskNextOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.ListFromTaskNext(Microsoft.Azure.Batch.Protocol.IFileOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskNextOptions)" />
      <MemberSignature Language="F#" Value="static member ListFromTaskNext : Microsoft.Azure.Batch.Protocol.IFileOperations * string * Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskNextOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;" Usage="Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.ListFromTaskNext (operations, nextPageLink, fileListFromTaskNextOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IFileOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="fileListFromTaskNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskNextOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="52743-229">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="52743-229">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="52743-230">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="52743-230">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="fileListFromTaskNextOptions">
            <span data-ttu-id="52743-231">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="52743-231">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="52743-232">コンピューティング ノードでは、タスクのディレクトリ内のファイルを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="52743-232">Lists the files in a task's directory on its compute node.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFromTaskNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;&gt; ListFromTaskNextAsync (this Microsoft.Azure.Batch.Protocol.IFileOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskNextOptions fileListFromTaskNextOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;&gt; ListFromTaskNextAsync(class Microsoft.Azure.Batch.Protocol.IFileOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskNextOptions fileListFromTaskNextOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.ListFromTaskNextAsync(Microsoft.Azure.Batch.Protocol.IFileOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskNextOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListFromTaskNextAsync : Microsoft.Azure.Batch.Protocol.IFileOperations * string * Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskNextOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.ListFromTaskNextAsync (operations, nextPageLink, fileListFromTaskNextOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.FileOperationsExtensions/&lt;ListFromTaskNextAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IFileOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="fileListFromTaskNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskNextOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="52743-233">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="52743-233">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="52743-234">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="52743-234">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="fileListFromTaskNextOptions">
            <span data-ttu-id="52743-235">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="52743-235">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="52743-236">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="52743-236">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="52743-237">コンピューティング ノードでは、タスクのディレクトリ内のファイルを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="52743-237">Lists the files in a task's directory on its compute node.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>