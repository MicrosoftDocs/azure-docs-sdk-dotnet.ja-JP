<Type Name="JobOutputStorage" FullName="Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage">
  <TypeSignature Language="C#" Value="public class JobOutputStorage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobOutputStorage extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" />
  <TypeSignature Language="VB.NET" Value="Public Class JobOutputStorage" />
  <TypeSignature Language="F#" Value="type JobOutputStorage = class" />
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
            <span data-ttu-id="02205-101">Azure Batch のジョブの出力の永続的な記憶域を表します。</span><span class="sxs-lookup"><span data-stu-id="02205-101">Represents persistent storage for the outputs of an Azure Batch job.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="02205-102">ジョブの出力は、特定のタスクではなく、ジョブ全体に論理的に関連付けられている出力データを参照してください。</span><span class="sxs-lookup"><span data-stu-id="02205-102">Job outputs refer to output data logically associated with the entire job, rather than a particular task.</span></span> <span data-ttu-id="02205-103">たとえば、ムービー レンダリング ジョブ、タスク、ムービーにすべてのフレームを結合する場合論理的がジョブの出力。</span><span class="sxs-lookup"><span data-stu-id="02205-103">For example, in a movie rendering job, if a task combined all the frames into a movie, that would logically be a job output.</span></span> <span data-ttu-id="02205-104">'ジョブ' の出力は、どのタスクを認識してから、クライアントを保存するように出力をこれによりの目的は、これを生成します。</span><span class="sxs-lookup"><span data-stu-id="02205-104">The purpose of categorising an output as a 'job' output is to save the client from having to know which task produced it.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobOutputStorage (Uri jobOutputContainerUri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri jobOutputContainerUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage.#ctor(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (jobOutputContainerUri As Uri)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage : Uri -&gt; Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" Usage="new Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage jobOutputContainerUri" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="jobOutputContainerUri" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="jobOutputContainerUri"><span data-ttu-id="02205-105">ジョブに使用する blob コンテナーの Azure ストレージ内の URL を出力します。</span><span class="sxs-lookup"><span data-stu-id="02205-105">The URL in Azure storage of the blob container to use for job outputs.</span></span> <span data-ttu-id="02205-106">この URL は、コンテナーへのアクセスを付与する SAS (Shared Access Signature) を含める必要があります。 またはコンテナーをパブリックにする必要があります。</span><span class="sxs-lookup"><span data-stu-id="02205-106">This URL must contain a SAS (Shared Access Signature) granting access to the container, or the container must be public.</span></span></param>
        <summary>
            <span data-ttu-id="02205-107">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" />ジョブ出力のコンテナーを表す URL からのクラスです。</span><span class="sxs-lookup"><span data-stu-id="02205-107">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" /> class from a URL representing the job output container.</span></span>
            </summary>
        <remarks><span data-ttu-id="02205-108">コンテナーは既に存在する必要があります。JobOutputStorage クラスが作成していないのです。</span><span class="sxs-lookup"><span data-stu-id="02205-108">The container must already exist; the JobOutputStorage class does not create it for you.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobOutputStorage (Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount, string jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount, string jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage.#ctor(Microsoft.WindowsAzure.Storage.CloudStorageAccount,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (storageAccount As CloudStorageAccount, jobId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage : Microsoft.WindowsAzure.Storage.CloudStorageAccount * string -&gt; Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" Usage="new Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage (storageAccount, jobId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storageAccount" Type="Microsoft.WindowsAzure.Storage.CloudStorageAccount" />
        <Parameter Name="jobId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="storageAccount"><span data-ttu-id="02205-109">ストレージ アカウントは、Azure Batch アカウントにリンクします。</span><span class="sxs-lookup"><span data-stu-id="02205-109">The storage account linked to the Azure Batch account.</span></span></param>
        <param name="jobId"><span data-ttu-id="02205-110">Azure Batch のジョブの id。</span><span class="sxs-lookup"><span data-stu-id="02205-110">The id of the Azure Batch job.</span></span></param>
        <summary>
            <span data-ttu-id="02205-111">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" />ストレージ アカウントとジョブの id からのクラスです。</span><span class="sxs-lookup"><span data-stu-id="02205-111">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" /> class from a storage account and job id.</span></span>
            </summary>
        <remarks><span data-ttu-id="02205-112">ジョブ出力コンテナーが存在する必要があります。JobOutputStorage クラスが作成していないのです。</span><span class="sxs-lookup"><span data-stu-id="02205-112">The job output container must already exist; the JobOutputStorage class does not create it for you.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobOutputStorage (Uri jobOutputContainerUri, Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy storageRetryPolicy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri jobOutputContainerUri, class Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy storageRetryPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage.#ctor(System.Uri,Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (jobOutputContainerUri As Uri, storageRetryPolicy As IRetryPolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage : Uri * Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy -&gt; Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" Usage="new Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage (jobOutputContainerUri, storageRetryPolicy)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="jobOutputContainerUri" Type="System.Uri" />
        <Parameter Name="storageRetryPolicy" Type="Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" />
      </Parameters>
      <Docs>
        <param name="jobOutputContainerUri"><span data-ttu-id="02205-113">ジョブに使用する blob コンテナーの Azure ストレージ内の URL を出力します。</span><span class="sxs-lookup"><span data-stu-id="02205-113">The URL in Azure storage of the blob container to use for job outputs.</span></span> <span data-ttu-id="02205-114">この URL は、コンテナーへのアクセスを付与する SAS (Shared Access Signature) を含める必要があります。 またはコンテナーをパブリックにする必要があります。</span><span class="sxs-lookup"><span data-stu-id="02205-114">This URL must contain a SAS (Shared Access Signature) granting access to the container, or the container must be public.</span></span></param>
        <param name="storageRetryPolicy"><span data-ttu-id="02205-115">記憶域の要求の再試行ポリシーです。</span><span class="sxs-lookup"><span data-stu-id="02205-115">The retry policy for storage requests.</span></span></param>
        <summary>
            <span data-ttu-id="02205-116">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" />ジョブ出力のコンテナーを表す URL からのクラスです。</span><span class="sxs-lookup"><span data-stu-id="02205-116">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" /> class from a URL representing the job output container.</span></span>
            </summary>
        <remarks><span data-ttu-id="02205-117">コンテナーは既に存在する必要があります。JobOutputStorage クラスが作成していないのです。</span><span class="sxs-lookup"><span data-stu-id="02205-117">The container must already exist; the JobOutputStorage class does not create it for you.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobOutputStorage (Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount, string jobId, Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy storageRetryPolicy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount, string jobId, class Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy storageRetryPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage.#ctor(Microsoft.WindowsAzure.Storage.CloudStorageAccount,System.String,Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (storageAccount As CloudStorageAccount, jobId As String, storageRetryPolicy As IRetryPolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage : Microsoft.WindowsAzure.Storage.CloudStorageAccount * string * Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy -&gt; Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" Usage="new Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage (storageAccount, jobId, storageRetryPolicy)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storageAccount" Type="Microsoft.WindowsAzure.Storage.CloudStorageAccount" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="storageRetryPolicy" Type="Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" />
      </Parameters>
      <Docs>
        <param name="storageAccount"><span data-ttu-id="02205-118">ストレージ アカウントは、Azure Batch アカウントにリンクします。</span><span class="sxs-lookup"><span data-stu-id="02205-118">The storage account linked to the Azure Batch account.</span></span></param>
        <param name="jobId"><span data-ttu-id="02205-119">Azure Batch のジョブの id。</span><span class="sxs-lookup"><span data-stu-id="02205-119">The id of the Azure Batch job.</span></span></param>
        <param name="storageRetryPolicy"><span data-ttu-id="02205-120">記憶域の要求の再試行ポリシーです。</span><span class="sxs-lookup"><span data-stu-id="02205-120">The retry policy for storage requests.</span></span></param>
        <summary>
            <span data-ttu-id="02205-121">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" />ストレージ アカウントとジョブの id からのクラスです。</span><span class="sxs-lookup"><span data-stu-id="02205-121">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" /> class from a storage account and job id.</span></span>
            </summary>
        <remarks><span data-ttu-id="02205-122">ジョブ出力コンテナーが存在する必要があります。JobOutputStorage クラスが作成していないのです。</span><span class="sxs-lookup"><span data-stu-id="02205-122">The job output container must already exist; the JobOutputStorage class does not create it for you.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOutputAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt; GetOutputAsync (Microsoft.Azure.Batch.Conventions.Files.JobOutputKind kind, string filePath, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt; GetOutputAsync(class Microsoft.Azure.Batch.Conventions.Files.JobOutputKind kind, string filePath, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage.GetOutputAsync(Microsoft.Azure.Batch.Conventions.Files.JobOutputKind,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetOutputAsync : Microsoft.Azure.Batch.Conventions.Files.JobOutputKind * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt;" Usage="jobOutputStorage.GetOutputAsync (kind, filePath, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage/&lt;GetOutputAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="kind" Type="Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="kind"><span data-ttu-id="02205-123">A<see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" />を取得する出力のカテゴリを表す<see cref="F:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.JobOutput" />または<see cref="F:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.JobPreview" />です。</span><span class="sxs-lookup"><span data-stu-id="02205-123">A <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" /> representing the category of the output to retrieve, for example <see cref="F:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.JobOutput" /> or <see cref="F:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.JobPreview" />.</span></span></param>
        <param name="filePath"><span data-ttu-id="02205-124">Blob ストレージに永続化が出力されるパスです。</span><span class="sxs-lookup"><span data-stu-id="02205-124">The path under which the output was persisted in blob storage.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="02205-125">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="02205-125">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="02205-126">種類とパスによって Azure blob ストレージからジョブの出力を取得します。</span><span class="sxs-lookup"><span data-stu-id="02205-126">Retrieves a job output from Azure blob storage by kind and path.</span></span>
            </summary>
        <returns><span data-ttu-id="02205-127">Azure blob ストレージに要求されたファイルへの参照。</span><span class="sxs-lookup"><span data-stu-id="02205-127">A reference to the requested file in Azure blob storage.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListOutputs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt; ListOutputs (Microsoft.Azure.Batch.Conventions.Files.JobOutputKind kind);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt; ListOutputs(class Microsoft.Azure.Batch.Conventions.Files.JobOutputKind kind) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage.ListOutputs(Microsoft.Azure.Batch.Conventions.Files.JobOutputKind)" />
      <MemberSignature Language="VB.NET" Value="Public Function ListOutputs (kind As JobOutputKind) As IEnumerable(Of OutputFileReference)" />
      <MemberSignature Language="F#" Value="member this.ListOutputs : Microsoft.Azure.Batch.Conventions.Files.JobOutputKind -&gt; seq&lt;Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt;" Usage="jobOutputStorage.ListOutputs kind" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="kind" Type="Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" />
      </Parameters>
      <Docs>
        <param name="kind"><span data-ttu-id="02205-128">A<see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" />出力を一覧表示などのカテゴリを表す<see cref="F:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.JobOutput" />または<see cref="F:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.JobPreview" />です。</span><span class="sxs-lookup"><span data-stu-id="02205-128">A <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" /> representing the category of outputs to list, for example <see cref="F:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.JobOutput" /> or <see cref="F:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.JobPreview" />.</span></span></param>
        <summary>
            <span data-ttu-id="02205-129">指定した種類のジョブの出力を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="02205-129">Lists the job outputs of the specified kind.</span></span>
            </summary>
        <returns><span data-ttu-id="02205-130">指定した種類の永続化されたジョブ出力の一覧です。</span><span class="sxs-lookup"><span data-stu-id="02205-130">A list of persisted job outputs of the specified kind.</span></span></returns>
        <remarks><span data-ttu-id="02205-131">列挙される場合に遅延の一覧を取得し、Azure blob ストレージからされます。</span><span class="sxs-lookup"><span data-stu-id="02205-131">The list is retrieved lazily from Azure blob storage when it is enumerated.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="SaveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SaveAsync (Microsoft.Azure.Batch.Conventions.Files.JobOutputKind kind, string relativePath, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SaveAsync(class Microsoft.Azure.Batch.Conventions.Files.JobOutputKind kind, string relativePath, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage.SaveAsync(Microsoft.Azure.Batch.Conventions.Files.JobOutputKind,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.SaveAsync : Microsoft.Azure.Batch.Conventions.Files.JobOutputKind * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="jobOutputStorage.SaveAsync (kind, relativePath, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage/&lt;SaveAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="kind" Type="Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" />
        <Parameter Name="relativePath" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="kind"><span data-ttu-id="02205-132">A<see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" />など、このファイルの格納に使用するカテゴリを表す<see cref="F:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.JobOutput" />または<see cref="F:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.JobPreview" />です。</span><span class="sxs-lookup"><span data-stu-id="02205-132">A <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" /> representing the category under which to store this file, for example <see cref="F:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.JobOutput" /> or <see cref="F:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.JobPreview" />.</span></span></param>
        <param name="relativePath"><span data-ttu-id="02205-133">現在のディレクトリに対して相対的に、保存するファイルのパス。</span><span class="sxs-lookup"><span data-stu-id="02205-133">The path of the file to save, relative to the current directory.</span></span>
            <span data-ttu-id="02205-134">ファイルが現在のディレクトリのサブディレクトリ内にある場合は、相対パスは blob ストレージに保持されます。</span><span class="sxs-lookup"><span data-stu-id="02205-134">If the file is in a subdirectory of the current directory, the relative path will be preserved in blob storage.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="02205-135">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="02205-135">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="02205-136">指定したファイルを永続的ストレージに保存します。</span><span class="sxs-lookup"><span data-stu-id="02205-136">Saves the specified file to persistent storage.</span></span>
            </summary>
        <returns><span data-ttu-id="02205-137">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="02205-137">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="02205-138">ファイルが現在のディレクトリの外部にある場合は、ディレクトリ ツリーを走査は削除されます。</span><span class="sxs-lookup"><span data-stu-id="02205-138">If the file is outside the current directory, traversals up the directory tree are removed.</span></span>
            <span data-ttu-id="02205-139">たとえば、<paramref name="relativePath" />の"..\ProcessEnv.cmd"の blob 名を作成する目的で"ProcessEnv.cmd"として取り扱われます。</span><span class="sxs-lookup"><span data-stu-id="02205-139">For example, a <paramref name="relativePath" /> of "..\ProcessEnv.cmd" would be treated as "ProcessEnv.cmd" for the purposes of creating a blob name.</span></span></remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="02205-140"><paramref name="kind" />または<paramref name="relativePath" />引数が null です。</span><span class="sxs-lookup"><span data-stu-id="02205-140">The <paramref name="kind" /> or <paramref name="relativePath" /> argument is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="02205-141"><paramref name="relativePath" />引数が絶対パス、または空です。</span><span class="sxs-lookup"><span data-stu-id="02205-141">The <paramref name="relativePath" /> argument is an absolute path, or is empty.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="SaveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SaveAsync (Microsoft.Azure.Batch.Conventions.Files.JobOutputKind kind, string sourcePath, string destinationRelativePath, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SaveAsync(class Microsoft.Azure.Batch.Conventions.Files.JobOutputKind kind, string sourcePath, string destinationRelativePath, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage.SaveAsync(Microsoft.Azure.Batch.Conventions.Files.JobOutputKind,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.SaveAsync : Microsoft.Azure.Batch.Conventions.Files.JobOutputKind * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="jobOutputStorage.SaveAsync (kind, sourcePath, destinationRelativePath, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage/&lt;SaveAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="kind" Type="Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" />
        <Parameter Name="sourcePath" Type="System.String" />
        <Parameter Name="destinationRelativePath" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="kind"><span data-ttu-id="02205-142">A<see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" />など、このファイルの格納に使用するカテゴリを表す<see cref="F:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.JobOutput" />または<see cref="F:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.JobPreview" />です。</span><span class="sxs-lookup"><span data-stu-id="02205-142">A <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" /> representing the category under which to store this file, for example <see cref="F:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.JobOutput" /> or <see cref="F:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.JobPreview" />.</span></span></param>
        <param name="sourcePath"><span data-ttu-id="02205-143">保存するファイルのパス。</span><span class="sxs-lookup"><span data-stu-id="02205-143">The path of the file to save.</span></span></param>
        <param name="destinationRelativePath"><span data-ttu-id="02205-144">ファイルの保存先となる blob の名前です。</span><span class="sxs-lookup"><span data-stu-id="02205-144">The blob name under which to save the file.</span></span> <span data-ttu-id="02205-145">これには、"pointclouds/pointcloud_0001.txt"などの相対的なコンポーネントが含まれます。</span><span class="sxs-lookup"><span data-stu-id="02205-145">This may include a relative component, such as "pointclouds/pointcloud_0001.txt".</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="02205-146">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="02205-146">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="02205-147">指定したファイルを永続的ストレージに保存します。</span><span class="sxs-lookup"><span data-stu-id="02205-147">Saves the specified file to persistent storage.</span></span>
            </summary>
        <returns><span data-ttu-id="02205-148">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="02205-148">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="02205-149"><paramref name="kind" />、 <paramref name="sourcePath" />、または<paramref name="destinationRelativePath" />引数が null です。</span><span class="sxs-lookup"><span data-stu-id="02205-149">The <paramref name="kind" />, <paramref name="sourcePath" />, or <paramref name="destinationRelativePath" /> argument is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="02205-150"><paramref name="sourcePath" />または<paramref name="destinationRelativePath" />引数が空です。</span><span class="sxs-lookup"><span data-stu-id="02205-150">The <paramref name="sourcePath" /> or <paramref name="destinationRelativePath" /> argument is empty.</span></span></exception>
      </Docs>
    </Member>
  </Members>
</Type>