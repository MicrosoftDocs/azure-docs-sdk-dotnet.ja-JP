<Type Name="TaskOutputStorage" FullName="Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage">
  <TypeSignature Language="C#" Value="public class TaskOutputStorage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskOutputStorage extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskOutputStorage" />
  <TypeSignature Language="F#" Value="type TaskOutputStorage = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5cae2-101">Azure Batch のタスクの出力の永続的な記憶域を表します。</span><span class="sxs-lookup"><span data-stu-id="5cae2-101">Represents persistent storage for the outputs of an Azure Batch task.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="5cae2-102">タスクの出力は、ジョブ全体ではなく、特定のタスクに論理的に関連付けられている出力データを参照してください。</span><span class="sxs-lookup"><span data-stu-id="5cae2-102">Task outputs refer to output data logically associated with a specific task, rather than the job as a whole.</span></span> <span data-ttu-id="5cae2-103">たとえば、ムービー レンダリング ジョブ、タスクが 1 つのフレームをレンダリングする場合そのフレームなりますタスクの出力。</span><span class="sxs-lookup"><span data-stu-id="5cae2-103">For example, in a movie rendering job, if a task rendered a single frame, that frame would be a task output.</span></span>  <span data-ttu-id="5cae2-104">ログと中間ファイルなどの他の診断情報も永続化タスクの出力として (を参照してください<see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />クライアントは、メイン出力の補助的なデータと識別できるように、これらを分類する方法について)。</span><span class="sxs-lookup"><span data-stu-id="5cae2-104">Logs and other diagnostic information such as intermediate files may also be persisted as task outputs (see <see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" /> for a way to categorise these so that clients can distinguish between the main output and auxiliary data).</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskOutputStorage (Uri jobOutputContainerUri, string taskId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri jobOutputContainerUri, string taskId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.#ctor(System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (jobOutputContainerUri As Uri, taskId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage : Uri * string -&gt; Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage" Usage="new Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage (jobOutputContainerUri, taskId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="jobOutputContainerUri" Type="System.Uri" />
        <Parameter Name="taskId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="jobOutputContainerUri"><span data-ttu-id="5cae2-105">このジョブに関連付けられている出力に使用する Azure storage blob コンテナーの URL です。</span><span class="sxs-lookup"><span data-stu-id="5cae2-105">The URL in Azure storage of the blob container to use for outputs associated with this job.</span></span> <span data-ttu-id="5cae2-106">この URL は、コンテナーへのアクセスを付与する SAS (Shared Access Signature) を含める必要があります。 またはコンテナーをパブリックにする必要があります。</span><span class="sxs-lookup"><span data-stu-id="5cae2-106">This URL must contain a SAS (Shared Access Signature) granting access to the container, or the container must be public.</span></span></param>
        <param name="taskId"><span data-ttu-id="5cae2-107">Azure Batch のタスクの id。</span><span class="sxs-lookup"><span data-stu-id="5cae2-107">The id of the Azure Batch task.</span></span></param>
        <summary>
            <span data-ttu-id="5cae2-108">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" />タスク id と、ジョブ出力のコンテナーを表す URL からのクラスです。</span><span class="sxs-lookup"><span data-stu-id="5cae2-108">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" /> class from a task id and a URL representing the job output container.</span></span>
            </summary>
        <remarks><span data-ttu-id="5cae2-109">コンテナーは既に存在する必要があります。TaskOutputStorage クラスが作成していないのです。</span><span class="sxs-lookup"><span data-stu-id="5cae2-109">The container must already exist; the TaskOutputStorage class does not create it for you.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskOutputStorage (Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount, string jobId, string taskId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount, string jobId, string taskId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.#ctor(Microsoft.WindowsAzure.Storage.CloudStorageAccount,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (storageAccount As CloudStorageAccount, jobId As String, taskId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage : Microsoft.WindowsAzure.Storage.CloudStorageAccount * string * string -&gt; Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage" Usage="new Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage (storageAccount, jobId, taskId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storageAccount" Type="Microsoft.WindowsAzure.Storage.CloudStorageAccount" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="storageAccount"><span data-ttu-id="5cae2-110">ストレージ アカウントは、Azure Batch アカウントにリンクします。</span><span class="sxs-lookup"><span data-stu-id="5cae2-110">The storage account linked to the Azure Batch account.</span></span></param>
        <param name="jobId"><span data-ttu-id="5cae2-111">タスクを含む Azure Batch のジョブの id。</span><span class="sxs-lookup"><span data-stu-id="5cae2-111">The id of the Azure Batch job containing the task.</span></span></param>
        <param name="taskId"><span data-ttu-id="5cae2-112">Azure Batch のタスクの id。</span><span class="sxs-lookup"><span data-stu-id="5cae2-112">The id of the Azure Batch task.</span></span></param>
        <summary>
            <span data-ttu-id="5cae2-113">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" />クラスからストレージ アカウント、ジョブの id、およびタスクの id。</span><span class="sxs-lookup"><span data-stu-id="5cae2-113">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" /> class from a storage account, job id, and task id.</span></span>
            </summary>
        <remarks><span data-ttu-id="5cae2-114">ジョブ出力コンテナーが存在する必要があります。TaskOutputStorage クラスが作成していないのです。</span><span class="sxs-lookup"><span data-stu-id="5cae2-114">The job output container must already exist; the TaskOutputStorage class does not create it for you.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskOutputStorage (Uri jobOutputContainerUri, string taskId, Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy storageRetryPolicy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri jobOutputContainerUri, string taskId, class Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy storageRetryPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.#ctor(System.Uri,System.String,Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (jobOutputContainerUri As Uri, taskId As String, storageRetryPolicy As IRetryPolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage : Uri * string * Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy -&gt; Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage" Usage="new Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage (jobOutputContainerUri, taskId, storageRetryPolicy)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="jobOutputContainerUri" Type="System.Uri" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="storageRetryPolicy" Type="Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" />
      </Parameters>
      <Docs>
        <param name="jobOutputContainerUri"><span data-ttu-id="5cae2-115">このジョブに関連付けられている出力に使用する Azure storage blob コンテナーの URL です。</span><span class="sxs-lookup"><span data-stu-id="5cae2-115">The URL in Azure storage of the blob container to use for outputs associated with this job.</span></span> <span data-ttu-id="5cae2-116">この URL は、コンテナーへのアクセスを付与する SAS (Shared Access Signature) を含める必要があります。 またはコンテナーをパブリックにする必要があります。</span><span class="sxs-lookup"><span data-stu-id="5cae2-116">This URL must contain a SAS (Shared Access Signature) granting access to the container, or the container must be public.</span></span></param>
        <param name="taskId"><span data-ttu-id="5cae2-117">Azure Batch のタスクの id。</span><span class="sxs-lookup"><span data-stu-id="5cae2-117">The id of the Azure Batch task.</span></span></param>
        <param name="storageRetryPolicy"><span data-ttu-id="5cae2-118">記憶域の要求の再試行ポリシーです。</span><span class="sxs-lookup"><span data-stu-id="5cae2-118">The retry policy for storage requests.</span></span></param>
        <summary>
            <span data-ttu-id="5cae2-119">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" />タスク id と、ジョブ出力のコンテナーを表す URL からのクラスです。</span><span class="sxs-lookup"><span data-stu-id="5cae2-119">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" /> class from a task id and a URL representing the job output container.</span></span>
            </summary>
        <remarks><span data-ttu-id="5cae2-120">コンテナーは既に存在する必要があります。TaskOutputStorage クラスが作成していないのです。</span><span class="sxs-lookup"><span data-stu-id="5cae2-120">The container must already exist; the TaskOutputStorage class does not create it for you.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskOutputStorage (Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount, string jobId, string taskId, Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy storageRetryPolicy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount, string jobId, string taskId, class Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy storageRetryPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.#ctor(Microsoft.WindowsAzure.Storage.CloudStorageAccount,System.String,System.String,Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (storageAccount As CloudStorageAccount, jobId As String, taskId As String, storageRetryPolicy As IRetryPolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage : Microsoft.WindowsAzure.Storage.CloudStorageAccount * string * string * Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy -&gt; Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage" Usage="new Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage (storageAccount, jobId, taskId, storageRetryPolicy)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storageAccount" Type="Microsoft.WindowsAzure.Storage.CloudStorageAccount" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="storageRetryPolicy" Type="Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" />
      </Parameters>
      <Docs>
        <param name="storageAccount"><span data-ttu-id="5cae2-121">ストレージ アカウントは、Azure Batch アカウントにリンクします。</span><span class="sxs-lookup"><span data-stu-id="5cae2-121">The storage account linked to the Azure Batch account.</span></span></param>
        <param name="jobId"><span data-ttu-id="5cae2-122">タスクを含む Azure Batch のジョブの id。</span><span class="sxs-lookup"><span data-stu-id="5cae2-122">The id of the Azure Batch job containing the task.</span></span></param>
        <param name="taskId"><span data-ttu-id="5cae2-123">Azure Batch のタスクの id。</span><span class="sxs-lookup"><span data-stu-id="5cae2-123">The id of the Azure Batch task.</span></span></param>
        <param name="storageRetryPolicy"><span data-ttu-id="5cae2-124">記憶域の要求の再試行ポリシーです。</span><span class="sxs-lookup"><span data-stu-id="5cae2-124">The retry policy for storage requests.</span></span></param>
        <summary>
            <span data-ttu-id="5cae2-125">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" />クラスからストレージ アカウント、ジョブの id、およびタスクの id。</span><span class="sxs-lookup"><span data-stu-id="5cae2-125">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" /> class from a storage account, job id, and task id.</span></span>
            </summary>
        <remarks><span data-ttu-id="5cae2-126">ジョブ出力コンテナーが存在する必要があります。TaskOutputStorage クラスが作成していないのです。</span><span class="sxs-lookup"><span data-stu-id="5cae2-126">The job output container must already exist; the TaskOutputStorage class does not create it for you.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOutputAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt; GetOutputAsync (Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind kind, string filePath, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt; GetOutputAsync(class Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind kind, string filePath, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.GetOutputAsync(Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetOutputAsync : Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt;" Usage="taskOutputStorage.GetOutputAsync (kind, filePath, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage/&lt;GetOutputAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="kind" Type="Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="kind"><span data-ttu-id="5cae2-127">A<see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />を取得する出力のカテゴリを表す<see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskOutput" />または<see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskLog" />です。</span><span class="sxs-lookup"><span data-stu-id="5cae2-127">A <see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" /> representing the category of the output to retrieve, for example <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskOutput" /> or <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskLog" />.</span></span></param>
        <param name="filePath"><span data-ttu-id="5cae2-128">Blob ストレージに永続化が出力されるパスです。</span><span class="sxs-lookup"><span data-stu-id="5cae2-128">The path under which the output was persisted in blob storage.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5cae2-129">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="5cae2-129">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="5cae2-130">種類とパスによって Azure blob ストレージからのタスクの出力を取得します。</span><span class="sxs-lookup"><span data-stu-id="5cae2-130">Retrieves a task output from Azure blob storage by kind and path.</span></span>
            </summary>
        <returns><span data-ttu-id="5cae2-131">Azure blob ストレージに要求されたファイルへの参照。</span><span class="sxs-lookup"><span data-stu-id="5cae2-131">A reference to the requested file in Azure blob storage.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListOutputs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt; ListOutputs (Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind kind);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt; ListOutputs(class Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind kind) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.ListOutputs(Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind)" />
      <MemberSignature Language="VB.NET" Value="Public Function ListOutputs (kind As TaskOutputKind) As IEnumerable(Of OutputFileReference)" />
      <MemberSignature Language="F#" Value="member this.ListOutputs : Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind -&gt; seq&lt;Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt;" Usage="taskOutputStorage.ListOutputs kind" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="kind" Type="Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />
      </Parameters>
      <Docs>
        <param name="kind"><span data-ttu-id="5cae2-132">A<see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />出力を一覧表示などのカテゴリを表す<see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskOutput" />または<see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskLog" />です。</span><span class="sxs-lookup"><span data-stu-id="5cae2-132">A <see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" /> representing the category of outputs to list, for example <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskOutput" /> or <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskLog" />.</span></span></param>
        <summary>
            <span data-ttu-id="5cae2-133">指定した種類のタスクの出力を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="5cae2-133">Lists the task outputs of the specified kind.</span></span>
            </summary>
        <returns><span data-ttu-id="5cae2-134">指定した種類の永続化されたタスク出力の一覧です。</span><span class="sxs-lookup"><span data-stu-id="5cae2-134">A list of persisted task outputs of the specified kind.</span></span></returns>
        <remarks><span data-ttu-id="5cae2-135">列挙される場合に遅延の一覧を取得し、Azure blob ストレージからされます。</span><span class="sxs-lookup"><span data-stu-id="5cae2-135">The list is retrieved lazily from Azure blob storage when it is enumerated.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="SaveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SaveAsync (Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind kind, string relativePath, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SaveAsync(class Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind kind, string relativePath, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.SaveAsync(Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.SaveAsync : Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="taskOutputStorage.SaveAsync (kind, relativePath, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage/&lt;SaveAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="kind" Type="Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />
        <Parameter Name="relativePath" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="kind"><span data-ttu-id="5cae2-136">A<see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />など、このファイルの格納に使用するカテゴリを表す<see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskOutput" />または<see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskLog" />です。</span><span class="sxs-lookup"><span data-stu-id="5cae2-136">A <see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" /> representing the category under which to store this file, for example <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskOutput" /> or <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskLog" />.</span></span></param>
        <param name="relativePath"><span data-ttu-id="5cae2-137">現在のディレクトリに対して相対的に、保存するファイルのパス。</span><span class="sxs-lookup"><span data-stu-id="5cae2-137">The path of the file to save, relative to the current directory.</span></span>
            <span data-ttu-id="5cae2-138">ファイルが現在のディレクトリのサブディレクトリ内にある場合は、相対パスは blob ストレージに保持されます。</span><span class="sxs-lookup"><span data-stu-id="5cae2-138">If the file is in a subdirectory of the current directory, the relative path will be preserved in blob storage.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5cae2-139">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="5cae2-139">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="5cae2-140">指定したファイルを永続的ストレージに保存します。</span><span class="sxs-lookup"><span data-stu-id="5cae2-140">Saves the specified file to persistent storage.</span></span>
            </summary>
        <returns><span data-ttu-id="5cae2-141">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="5cae2-141">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="5cae2-142">ファイルが現在のディレクトリの外部にある場合は、ディレクトリ ツリーを走査は削除されます。</span><span class="sxs-lookup"><span data-stu-id="5cae2-142">If the file is outside the current directory, traversals up the directory tree are removed.</span></span>
            <span data-ttu-id="5cae2-143">たとえば、<paramref name="relativePath" />の"..\ProcessEnv.cmd"の blob 名を作成する目的で"ProcessEnv.cmd"として取り扱われます。</span><span class="sxs-lookup"><span data-stu-id="5cae2-143">For example, a <paramref name="relativePath" /> of "..\ProcessEnv.cmd" would be treated as "ProcessEnv.cmd" for the purposes of creating a blob name.</span></span></remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="5cae2-144"><paramref name="kind" />または<paramref name="relativePath" />引数が null です。</span><span class="sxs-lookup"><span data-stu-id="5cae2-144">The <paramref name="kind" /> or <paramref name="relativePath" /> argument is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="5cae2-145"><paramref name="relativePath" />引数が絶対パス、または空です。</span><span class="sxs-lookup"><span data-stu-id="5cae2-145">The <paramref name="relativePath" /> argument is an absolute path, or is empty.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="SaveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SaveAsync (Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind kind, string sourcePath, string destinationRelativePath, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SaveAsync(class Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind kind, string sourcePath, string destinationRelativePath, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.SaveAsync(Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.SaveAsync : Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="taskOutputStorage.SaveAsync (kind, sourcePath, destinationRelativePath, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage/&lt;SaveAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="kind" Type="Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />
        <Parameter Name="sourcePath" Type="System.String" />
        <Parameter Name="destinationRelativePath" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="kind"><span data-ttu-id="5cae2-146">A<see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />など、このファイルの格納に使用するカテゴリを表す<see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskOutput" />または<see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskLog" />です。</span><span class="sxs-lookup"><span data-stu-id="5cae2-146">A <see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" /> representing the category under which to store this file, for example <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskOutput" /> or <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskLog" />.</span></span></param>
        <param name="sourcePath"><span data-ttu-id="5cae2-147">保存するファイルのパス。</span><span class="sxs-lookup"><span data-stu-id="5cae2-147">The path of the file to save.</span></span></param>
        <param name="destinationRelativePath"><span data-ttu-id="5cae2-148">ファイルの保存先となる blob の名前です。</span><span class="sxs-lookup"><span data-stu-id="5cae2-148">The blob name under which to save the file.</span></span> <span data-ttu-id="5cae2-149">これには、"pointclouds/pointcloud_0001.txt"などの相対的なコンポーネントが含まれます。</span><span class="sxs-lookup"><span data-stu-id="5cae2-149">This may include a relative component, such as "pointclouds/pointcloud_0001.txt".</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5cae2-150">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="5cae2-150">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="5cae2-151">指定したファイルを永続的ストレージに保存します。</span><span class="sxs-lookup"><span data-stu-id="5cae2-151">Saves the specified file to persistent storage.</span></span>
            </summary>
        <returns><span data-ttu-id="5cae2-152">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="5cae2-152">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="5cae2-153"><paramref name="kind" />、 <paramref name="sourcePath" />、または<paramref name="destinationRelativePath" />引数が null です。</span><span class="sxs-lookup"><span data-stu-id="5cae2-153">The <paramref name="kind" />, <paramref name="sourcePath" />, or <paramref name="destinationRelativePath" /> argument is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="5cae2-154"><paramref name="sourcePath" />または<paramref name="destinationRelativePath" />引数が空です。</span><span class="sxs-lookup"><span data-stu-id="5cae2-154">The <paramref name="sourcePath" /> or <paramref name="destinationRelativePath" /> argument is empty.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="SaveTextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SaveTextAsync (Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind kind, string text, string destinationRelativePath, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SaveTextAsync(class Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind kind, string text, string destinationRelativePath, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.SaveTextAsync(Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.SaveTextAsync : Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="taskOutputStorage.SaveTextAsync (kind, text, destinationRelativePath, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage/&lt;SaveTextAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="kind" Type="Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />
        <Parameter Name="text" Type="System.String" />
        <Parameter Name="destinationRelativePath" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="kind"><span data-ttu-id="5cae2-155">A<see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />など、このデータの格納に使用するカテゴリを表す<see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskOutput" />または<see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskLog" />です。</span><span class="sxs-lookup"><span data-stu-id="5cae2-155">A <see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" /> representing the category under which to store this data, for example <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskOutput" /> or <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskLog" />.</span></span></param>
        <param name="text"><span data-ttu-id="5cae2-156">保存するテキスト。</span><span class="sxs-lookup"><span data-stu-id="5cae2-156">The text to save.</span></span></param>
        <param name="destinationRelativePath"><span data-ttu-id="5cae2-157">テキストの保存に使用する blob の名前です。</span><span class="sxs-lookup"><span data-stu-id="5cae2-157">The blob name under which to save the text.</span></span> <span data-ttu-id="5cae2-158">これには、"records/widget42.json"などの相対的なコンポーネントが含まれます。</span><span class="sxs-lookup"><span data-stu-id="5cae2-158">This may include a relative component, such as "records/widget42.json".</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5cae2-159">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="5cae2-159">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="5cae2-160">ローカル ファイルを作成することがなく、指定したテキストを永続的な記憶域に保存します。</span><span class="sxs-lookup"><span data-stu-id="5cae2-160">Saves the specified text to persistent storage, without requiring you to create a local file.</span></span>
            </summary>
        <returns><span data-ttu-id="5cae2-161">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="5cae2-161">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="5cae2-162"><paramref name="kind" />、 <paramref name="text" />、または<paramref name="destinationRelativePath" />引数が null です。</span><span class="sxs-lookup"><span data-stu-id="5cae2-162">The <paramref name="kind" />, <paramref name="text" />, or <paramref name="destinationRelativePath" /> argument is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="5cae2-163"><paramref name="destinationRelativePath" />引数が空です。</span><span class="sxs-lookup"><span data-stu-id="5cae2-163">The <paramref name="destinationRelativePath" /> argument is empty.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="SaveTrackedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Conventions.Files.ITrackedSaveOperation&gt; SaveTrackedAsync (string relativePath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Conventions.Files.ITrackedSaveOperation&gt; SaveTrackedAsync(string relativePath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.SaveTrackedAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SaveTrackedAsync (relativePath As String) As Task(Of ITrackedSaveOperation)" />
      <MemberSignature Language="F#" Value="member this.SaveTrackedAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Conventions.Files.ITrackedSaveOperation&gt;" Usage="taskOutputStorage.SaveTrackedAsync relativePath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage/&lt;SaveTrackedAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Conventions.Files.ITrackedSaveOperation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="relativePath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="relativePath"><span data-ttu-id="5cae2-164">現在のディレクトリに対して相対的に、保存するファイルのパス。</span><span class="sxs-lookup"><span data-stu-id="5cae2-164">The path of the file to save, relative to the current directory.</span></span>
            <span data-ttu-id="5cae2-165">ファイルが現在のディレクトリのサブディレクトリ内にある場合は、相対パスは blob ストレージに保持されます。</span><span class="sxs-lookup"><span data-stu-id="5cae2-165">If the file is in a subdirectory of the current directory, the relative path will be preserved in blob storage.</span></span></param>
        <summary>
            <span data-ttu-id="5cae2-166">永続的な記憶域に指定されたファイルを保存、 <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskLog" />、および後続のトラックがファイルに追加しても永続的なコピーに追加します。</span><span class="sxs-lookup"><span data-stu-id="5cae2-166">Saves the specified file to persistent storage as a <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskLog" />, and tracks subsequent appends to the file and appends them to the persistent copy too.</span></span>
            </summary>
        <returns><span data-ttu-id="5cae2-167"><see cref="T:Microsoft.Azure.Batch.Conventions.Files.ITrackedSaveOperation" />ファイルを blob ストレージに保存され、ファイルを定期的にフラッシュが破棄されるまで、blob に追加します。</span><span class="sxs-lookup"><span data-stu-id="5cae2-167">An <see cref="T:Microsoft.Azure.Batch.Conventions.Files.ITrackedSaveOperation" /> which will save a file to blob storage and will periodically flush file appends to the blob until disposed.</span></span>  <span data-ttu-id="5cae2-168">破棄されると、残りのすべて追加が blob ストレージ、さらにフラッシュされたファイルの追跡の追加が停止します。</span><span class="sxs-lookup"><span data-stu-id="5cae2-168">When disposed, all remaining appends are flushed to blob storage, and further tracking of file appends is stopped.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="5cae2-169">追跡のサポートのみ追加します。</span><span class="sxs-lookup"><span data-stu-id="5cae2-169">Tracking supports only appends.</span></span> <span data-ttu-id="5cae2-170">つまり、ファイルが追跡されているときに最後に追加されたデータすべてが永続的ストレージに追加されます。</span><span class="sxs-lookup"><span data-stu-id="5cae2-170">That is, while a file is being tracked, any data added at the end is appended to the persistent storage.</span></span> <span data-ttu-id="5cae2-171">永続的なストアに既にアップロードされているデータへの変更は反映されません。</span><span class="sxs-lookup"><span data-stu-id="5cae2-171">Changes to data that has already been uploaded will not be reflected to the persistent store.</span></span> <span data-ttu-id="5cae2-172">したがって、このメソッドはデータがファイルの末尾に追加のみ (非回転) ログ ファイルなどのファイルでのみ使用するためものです。</span><span class="sxs-lookup"><span data-stu-id="5cae2-172">This method is therefore intended for use only with files such as (non-rotating) log files where data is only added at the end of the file.</span></span>
            <span data-ttu-id="5cae2-173">ファイルの内容全体が変更できる場合を使用して<see cref="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.SaveAsync(Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind,System.String,System.Threading.CancellationToken)" />および定期的にまたはそれぞれの変更後の呼び出しです。</span><span class="sxs-lookup"><span data-stu-id="5cae2-173">If the entire contents of a file can change, use <see cref="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.SaveAsync(Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind,System.String,System.Threading.CancellationToken)" /> and call it periodically or after each change.</span></span></para>
          <para><span data-ttu-id="5cae2-174">ファイルが現在のディレクトリの外部にある場合は、ディレクトリ ツリーを走査は削除されます。</span><span class="sxs-lookup"><span data-stu-id="5cae2-174">If the file is outside the current directory, traversals up the directory tree are removed.</span></span>
            <span data-ttu-id="5cae2-175">たとえば、<paramref name="relativePath" />の"..\ProcessEnv.cmd"の blob 名を作成する目的で"ProcessEnv.cmd"として取り扱われます。</span><span class="sxs-lookup"><span data-stu-id="5cae2-175">For example, a <paramref name="relativePath" /> of "..\ProcessEnv.cmd" would be treated as "ProcessEnv.cmd" for the purposes of creating a blob name.</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="5cae2-176"><paramref name="relativePath" /> 引数が null です。</span><span class="sxs-lookup"><span data-stu-id="5cae2-176">The <paramref name="relativePath" /> argument is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="5cae2-177"><paramref name="relativePath" />引数が絶対パス、または空です。</span><span class="sxs-lookup"><span data-stu-id="5cae2-177">The <paramref name="relativePath" /> argument is an absolute path, or is empty.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="SaveTrackedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Conventions.Files.ITrackedSaveOperation&gt; SaveTrackedAsync (Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind kind, string sourcePath, string destinationRelativePath, TimeSpan flushInterval);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Conventions.Files.ITrackedSaveOperation&gt; SaveTrackedAsync(class Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind kind, string sourcePath, string destinationRelativePath, valuetype System.TimeSpan flushInterval) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.SaveTrackedAsync(Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind,System.String,System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function SaveTrackedAsync (kind As TaskOutputKind, sourcePath As String, destinationRelativePath As String, flushInterval As TimeSpan) As Task(Of ITrackedSaveOperation)" />
      <MemberSignature Language="F#" Value="member this.SaveTrackedAsync : Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind * string * string * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Conventions.Files.ITrackedSaveOperation&gt;" Usage="taskOutputStorage.SaveTrackedAsync (kind, sourcePath, destinationRelativePath, flushInterval)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage/&lt;SaveTrackedAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Conventions.Files.ITrackedSaveOperation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="kind" Type="Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />
        <Parameter Name="sourcePath" Type="System.String" />
        <Parameter Name="destinationRelativePath" Type="System.String" />
        <Parameter Name="flushInterval" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="kind"><span data-ttu-id="5cae2-178">A<see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />など、このファイルの格納に使用するカテゴリを表す<see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskOutput" />または<see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskLog" />です。</span><span class="sxs-lookup"><span data-stu-id="5cae2-178">A <see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" /> representing the category under which to store this file, for example <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskOutput" /> or <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskLog" />.</span></span></param>
        <param name="sourcePath"><span data-ttu-id="5cae2-179">保存するファイルのパス。</span><span class="sxs-lookup"><span data-stu-id="5cae2-179">The path of the file to save.</span></span></param>
        <param name="destinationRelativePath"><span data-ttu-id="5cae2-180">ファイルの保存先となる blob の名前です。</span><span class="sxs-lookup"><span data-stu-id="5cae2-180">The blob name under which to save the file.</span></span> <span data-ttu-id="5cae2-181">これには、"pointclouds/pointcloud_0001.txt"などの相対的なコンポーネントが含まれます。</span><span class="sxs-lookup"><span data-stu-id="5cae2-181">This may include a relative component, such as "pointclouds/pointcloud_0001.txt".</span></span></param>
        <param name="flushInterval"><span data-ttu-id="5cae2-182">フラッシュ間隔は、永続的な記憶域を追加します。</span><span class="sxs-lookup"><span data-stu-id="5cae2-182">The interval at which to flush appends to persistent storage.</span></span></param>
        <summary>
            <span data-ttu-id="5cae2-183">保存永続的な記憶域、および後続のトラックを指定したファイルはファイルに追加しても永続的なコピーに追加します。</span><span class="sxs-lookup"><span data-stu-id="5cae2-183">Saves the specified file to persistent storage, and tracks subsequent appends to the file and appends them to the persistent copy too.</span></span>
            </summary>
        <returns><span data-ttu-id="5cae2-184"><see cref="T:Microsoft.Azure.Batch.Conventions.Files.ITrackedSaveOperation" />ファイルを blob ストレージに保存され、ファイルを定期的にフラッシュが破棄されるまで、blob に追加します。</span><span class="sxs-lookup"><span data-stu-id="5cae2-184">An <see cref="T:Microsoft.Azure.Batch.Conventions.Files.ITrackedSaveOperation" /> which will save a file to blob storage and will periodically flush file appends to the blob until disposed.</span></span>  <span data-ttu-id="5cae2-185">破棄されると、残りのすべて追加が blob ストレージ、さらにフラッシュされたファイルの追跡の追加が停止します。</span><span class="sxs-lookup"><span data-stu-id="5cae2-185">When disposed, all remaining appends are flushed to blob storage, and further tracking of file appends is stopped.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="5cae2-186">追跡のサポートのみ追加します。</span><span class="sxs-lookup"><span data-stu-id="5cae2-186">Tracking supports only appends.</span></span> <span data-ttu-id="5cae2-187">つまり、ファイルが追跡されているときに最後に追加されたデータすべてが永続的ストレージに追加されます。</span><span class="sxs-lookup"><span data-stu-id="5cae2-187">That is, while a file is being tracked, any data added at the end is appended to the persistent storage.</span></span> <span data-ttu-id="5cae2-188">永続的なストアに既にアップロードされているデータへの変更は反映されません。</span><span class="sxs-lookup"><span data-stu-id="5cae2-188">Changes to data that has already been uploaded will not be reflected to the persistent store.</span></span> <span data-ttu-id="5cae2-189">したがって、このメソッドはデータがファイルの末尾に追加のみ (非回転) ログ ファイルなどのファイルでのみ使用するためものです。</span><span class="sxs-lookup"><span data-stu-id="5cae2-189">This method is therefore intended for use only with files such as (non-rotating) log files where data is only added at the end of the file.</span></span>
            <span data-ttu-id="5cae2-190">ファイルの内容全体が変更できる場合を使用して<see cref="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.SaveAsync(Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind,System.String,System.String,System.Threading.CancellationToken)" />および定期的にまたはそれぞれの変更後の呼び出しです。</span><span class="sxs-lookup"><span data-stu-id="5cae2-190">If the entire contents of a file can change, use <see cref="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.SaveAsync(Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind,System.String,System.String,System.Threading.CancellationToken)" /> and call it periodically or after each change.</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="5cae2-191"><paramref name="kind" />、 <paramref name="sourcePath" />、または<paramref name="destinationRelativePath" />引数が null です。</span><span class="sxs-lookup"><span data-stu-id="5cae2-191">The <paramref name="kind" />, <paramref name="sourcePath" />, or <paramref name="destinationRelativePath" /> argument is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="5cae2-192"><paramref name="sourcePath" />または<paramref name="destinationRelativePath" />引数が空です。</span><span class="sxs-lookup"><span data-stu-id="5cae2-192">The <paramref name="sourcePath" /> or <paramref name="destinationRelativePath" /> argument is empty.</span></span></exception>
      </Docs>
    </Member>
  </Members>
</Type>