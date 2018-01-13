<Type Name="MockAdlsClient" FullName="Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient">
  <TypeSignature Language="C#" Value="public sealed class MockAdlsClient : Microsoft.Azure.DataLake.Store.AdlsClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit MockAdlsClient extends Microsoft.Azure.DataLake.Store.AdlsClient" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class MockAdlsClient&#xA;Inherits AdlsClient" />
  <TypeSignature Language="F#" Value="type MockAdlsClient = class&#xA;    inherit AdlsClient" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.DataLake.Store.AdlsClient</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d4c2d-101">モック Adls クライアント。</span><span class="sxs-lookup"><span data-stu-id="d4c2d-101">Mock Adls Client.</span></span> <span data-ttu-id="d4c2d-102">すべての操作は、メモリ内で実行されます。</span><span class="sxs-lookup"><span data-stu-id="d4c2d-102">All the operations are done in memory.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BulkDownload">
      <MemberSignature Language="C#" Value="public override Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus BulkDownload (string srcPath, string destPath, int numThreads = -1, Microsoft.Azure.DataLake.Store.IfExists shouldOverwrite = Microsoft.Azure.DataLake.Store.IfExists.Overwrite, IProgress&lt;Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus&gt; progressTracker = null, bool notRecurse = false, bool resume = false, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus BulkDownload(string srcPath, string destPath, int32 numThreads, valuetype Microsoft.Azure.DataLake.Store.IfExists shouldOverwrite, class System.IProgress`1&lt;class Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus&gt; progressTracker, bool notRecurse, bool resume, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient.BulkDownload(System.String,System.String,System.Int32,Microsoft.Azure.DataLake.Store.IfExists,System.IProgress{Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus},System.Boolean,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function BulkDownload (srcPath As String, destPath As String, Optional numThreads As Integer = -1, Optional shouldOverwrite As IfExists = Microsoft.Azure.DataLake.Store.IfExists.Overwrite, Optional progressTracker As IProgress(Of TransferStatus) = null, Optional notRecurse As Boolean = false, Optional resume As Boolean = false, Optional cancelToken As CancellationToken = null) As TransferStatus" />
      <MemberSignature Language="F#" Value="override this.BulkDownload : string * string * int * Microsoft.Azure.DataLake.Store.IfExists * IProgress&lt;Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus&gt; * bool * bool * System.Threading.CancellationToken -&gt; Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus" Usage="mockAdlsClient.BulkDownload (srcPath, destPath, numThreads, shouldOverwrite, progressTracker, notRecurse, resume, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="srcPath" Type="System.String" />
        <Parameter Name="destPath" Type="System.String" />
        <Parameter Name="numThreads" Type="System.Int32" />
        <Parameter Name="shouldOverwrite" Type="Microsoft.Azure.DataLake.Store.IfExists" />
        <Parameter Name="progressTracker" Type="System.IProgress&lt;Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus&gt;" />
        <Parameter Name="notRecurse" Type="System.Boolean" />
        <Parameter Name="resume" Type="System.Boolean" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="srcPath"><span data-ttu-id="d4c2d-103">リモート ソース パス</span><span class="sxs-lookup"><span data-stu-id="d4c2d-103">Remote source path</span></span></param>
        <param name="destPath"><span data-ttu-id="d4c2d-104">ローカルのコピー先のパス。</span><span class="sxs-lookup"><span data-stu-id="d4c2d-104">Local destination path.</span></span> <span data-ttu-id="d4c2d-105">ディレクトリに常になります。</span><span class="sxs-lookup"><span data-stu-id="d4c2d-105">It should always be a directory.</span></span></param>
        <param name="numThreads"><span data-ttu-id="d4c2d-106">未使用</span><span class="sxs-lookup"><span data-stu-id="d4c2d-106">Not used</span></span></param>
        <param name="shouldOverwrite"><span data-ttu-id="d4c2d-107">上書きするか、変換先が存在する場合は、省略するかどうか</span><span class="sxs-lookup"><span data-stu-id="d4c2d-107">Whether to overwrite or skip if the destination exists</span></span></param>
        <param name="progressTracker"><span data-ttu-id="d4c2d-108">未使用</span><span class="sxs-lookup"><span data-stu-id="d4c2d-108">Not used</span></span></param>
        <param name="notRecurse"><span data-ttu-id="d4c2d-109">未使用</span><span class="sxs-lookup"><span data-stu-id="d4c2d-109">Not used</span></span></param>
        <param name="resume"><span data-ttu-id="d4c2d-110">未使用</span><span class="sxs-lookup"><span data-stu-id="d4c2d-110">Not used</span></span></param>
        <param name="cancelToken">To be added.</param>
        <summary>
            <span data-ttu-id="d4c2d-111">ローカル ファイルに保存およびメモリ ストリームからデータを読み取ります</span><span class="sxs-lookup"><span data-stu-id="d4c2d-111">Reads data from memory stream and save it to local file</span></span>
            </summary>
        <returns><span data-ttu-id="d4c2d-112">ダウンロードの詳細をカプセル化する転送状態</span><span class="sxs-lookup"><span data-stu-id="d4c2d-112">Transfer status encapsulating the details of download</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BulkUpload">
      <MemberSignature Language="C#" Value="public override Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus BulkUpload (string srcPath, string destPath, int numThreads = -1, Microsoft.Azure.DataLake.Store.IfExists shouldOverwrite = Microsoft.Azure.DataLake.Store.IfExists.Overwrite, IProgress&lt;Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus&gt; progressTracker = null, bool notRecurse = false, bool resume = false, bool isBinary = false, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus BulkUpload(string srcPath, string destPath, int32 numThreads, valuetype Microsoft.Azure.DataLake.Store.IfExists shouldOverwrite, class System.IProgress`1&lt;class Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus&gt; progressTracker, bool notRecurse, bool resume, bool isBinary, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient.BulkUpload(System.String,System.String,System.Int32,Microsoft.Azure.DataLake.Store.IfExists,System.IProgress{Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus},System.Boolean,System.Boolean,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function BulkUpload (srcPath As String, destPath As String, Optional numThreads As Integer = -1, Optional shouldOverwrite As IfExists = Microsoft.Azure.DataLake.Store.IfExists.Overwrite, Optional progressTracker As IProgress(Of TransferStatus) = null, Optional notRecurse As Boolean = false, Optional resume As Boolean = false, Optional isBinary As Boolean = false, Optional cancelToken As CancellationToken = null) As TransferStatus" />
      <MemberSignature Language="F#" Value="override this.BulkUpload : string * string * int * Microsoft.Azure.DataLake.Store.IfExists * IProgress&lt;Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus&gt; * bool * bool * bool * System.Threading.CancellationToken -&gt; Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus" Usage="mockAdlsClient.BulkUpload (srcPath, destPath, numThreads, shouldOverwrite, progressTracker, notRecurse, resume, isBinary, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="srcPath" Type="System.String" />
        <Parameter Name="destPath" Type="System.String" />
        <Parameter Name="numThreads" Type="System.Int32" />
        <Parameter Name="shouldOverwrite" Type="Microsoft.Azure.DataLake.Store.IfExists" />
        <Parameter Name="progressTracker" Type="System.IProgress&lt;Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus&gt;" />
        <Parameter Name="notRecurse" Type="System.Boolean" />
        <Parameter Name="resume" Type="System.Boolean" />
        <Parameter Name="isBinary" Type="System.Boolean" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="srcPath"><span data-ttu-id="d4c2d-113">ローカルのソース パス</span><span class="sxs-lookup"><span data-stu-id="d4c2d-113">Local source path</span></span></param>
        <param name="destPath"><span data-ttu-id="d4c2d-114">リモート宛先パス - ディレクトリ必要があります。</span><span class="sxs-lookup"><span data-stu-id="d4c2d-114">Remote destination path - It should always be a directory.</span></span></param>
        <param name="numThreads"><span data-ttu-id="d4c2d-115">未使用</span><span class="sxs-lookup"><span data-stu-id="d4c2d-115">Not used</span></span></param>
        <param name="shouldOverwrite"><span data-ttu-id="d4c2d-116">上書きするか、変換先が存在する場合は、省略するかどうか</span><span class="sxs-lookup"><span data-stu-id="d4c2d-116">Whether to overwrite or skip if the destination exists</span></span></param>
        <param name="progressTracker"><span data-ttu-id="d4c2d-117">未使用</span><span class="sxs-lookup"><span data-stu-id="d4c2d-117">Not used</span></span></param>
        <param name="notRecurse"><span data-ttu-id="d4c2d-118">未使用</span><span class="sxs-lookup"><span data-stu-id="d4c2d-118">Not used</span></span></param>
        <param name="resume"><span data-ttu-id="d4c2d-119">未使用</span><span class="sxs-lookup"><span data-stu-id="d4c2d-119">Not used</span></span></param>
        <param name="isBinary"><span data-ttu-id="d4c2d-120">未使用</span><span class="sxs-lookup"><span data-stu-id="d4c2d-120">Not used</span></span></param>
        <param name="cancelToken">To be added.</param>
        <summary>
            <span data-ttu-id="d4c2d-121">ファイルのみが一括アップロードされます。</span><span class="sxs-lookup"><span data-stu-id="d4c2d-121">Bulk uploads file only.</span></span> <span data-ttu-id="d4c2d-122">ローカル ファイルを読み取り、エントリのメモリ ストリームを保持</span><span class="sxs-lookup"><span data-stu-id="d4c2d-122">Reads a local file and maintains the memory stream for the entry</span></span>
            </summary>
        <returns><span data-ttu-id="d4c2d-123">アップロードの詳細をカプセル化する転送状態</span><span class="sxs-lookup"><span data-stu-id="d4c2d-123">Transfer Status encapsulating the details of upload</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConcatenateFiles">
      <MemberSignature Language="C#" Value="public override void ConcatenateFiles (string destination, System.Collections.Generic.List&lt;string&gt; concatFiles, bool deleteSource = false, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void ConcatenateFiles(string destination, class System.Collections.Generic.List`1&lt;string&gt; concatFiles, bool deleteSource, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient.ConcatenateFiles(System.String,System.Collections.Generic.List{System.String},System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub ConcatenateFiles (destination As String, concatFiles As List(Of String), Optional deleteSource As Boolean = false, Optional cancelToken As CancellationToken = null)" />
      <MemberSignature Language="F#" Value="override this.ConcatenateFiles : string * System.Collections.Generic.List&lt;string&gt; * bool * System.Threading.CancellationToken -&gt; unit" Usage="mockAdlsClient.ConcatenateFiles (destination, concatFiles, deleteSource, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="destination" Type="System.String" />
        <Parameter Name="concatFiles" Type="System.Collections.Generic.List&lt;System.String&gt;" />
        <Parameter Name="deleteSource" Type="System.Boolean" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="destination"><span data-ttu-id="d4c2d-124">宛先エントリ</span><span class="sxs-lookup"><span data-stu-id="d4c2d-124">Destination entry</span></span></param>
        <param name="concatFiles"><span data-ttu-id="d4c2d-125">Concat ファイル</span><span class="sxs-lookup"><span data-stu-id="d4c2d-125">Concat files</span></span></param>
        <param name="deleteSource"><span data-ttu-id="d4c2d-126">ソースを削除する場合は true。</span><span class="sxs-lookup"><span data-stu-id="d4c2d-126">True if we want to delete source</span></span></param>
        <param name="cancelToken"><span data-ttu-id="d4c2d-127">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="d4c2d-127">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="d4c2d-128">Concats メモリ ストリーム ソースのエントリの新しいメモリ ストリームにマージし</span><span class="sxs-lookup"><span data-stu-id="d4c2d-128">Concats the memory stream of source entries and merges them into a new memory stream</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDirectory">
      <MemberSignature Language="C#" Value="public override bool CreateDirectory (string dirName, string octalPermission = null, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool CreateDirectory(string dirName, string octalPermission, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient.CreateDirectory(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CreateDirectory (dirName As String, Optional octalPermission As String = null, Optional cancelToken As CancellationToken = null) As Boolean" />
      <MemberSignature Language="F#" Value="override this.CreateDirectory : string * string * System.Threading.CancellationToken -&gt; bool" Usage="mockAdlsClient.CreateDirectory (dirName, octalPermission, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="dirName" Type="System.String" />
        <Parameter Name="octalPermission" Type="System.String" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="dirName"><span data-ttu-id="d4c2d-129">ディレクトリ名</span><span class="sxs-lookup"><span data-stu-id="d4c2d-129">Directory name</span></span></param>
        <param name="octalPermission"><span data-ttu-id="d4c2d-130">8 進数のアクセス許可</span><span class="sxs-lookup"><span data-stu-id="d4c2d-130">Octal permission</span></span></param>
        <param name="cancelToken"><span data-ttu-id="d4c2d-131">Cacnellation トークン</span><span class="sxs-lookup"><span data-stu-id="d4c2d-131">Cacnellation token</span></span></param>
        <summary>
            <span data-ttu-id="d4c2d-132">作成、内部辞書内にあるディレクトリのエントリをディレクトリ-を作成します。</span><span class="sxs-lookup"><span data-stu-id="d4c2d-132">Creates a directory- Creates an entry for the directory in the internal dictionary</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFile">
      <MemberSignature Language="C#" Value="public override Microsoft.Azure.DataLake.Store.AdlsOutputStream CreateFile (string filename, Microsoft.Azure.DataLake.Store.IfExists mode, string octalPermission = null, bool createParent = true);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.Azure.DataLake.Store.AdlsOutputStream CreateFile(string filename, valuetype Microsoft.Azure.DataLake.Store.IfExists mode, string octalPermission, bool createParent) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient.CreateFile(System.String,Microsoft.Azure.DataLake.Store.IfExists,System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CreateFile (filename As String, mode As IfExists, Optional octalPermission As String = null, Optional createParent As Boolean = true) As AdlsOutputStream" />
      <MemberSignature Language="F#" Value="override this.CreateFile : string * Microsoft.Azure.DataLake.Store.IfExists * string * bool -&gt; Microsoft.Azure.DataLake.Store.AdlsOutputStream" Usage="mockAdlsClient.CreateFile (filename, mode, octalPermission, createParent)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.DataLake.Store.AdlsOutputStream</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filename" Type="System.String" />
        <Parameter Name="mode" Type="Microsoft.Azure.DataLake.Store.IfExists" />
        <Parameter Name="octalPermission" Type="System.String" />
        <Parameter Name="createParent" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="filename"><span data-ttu-id="d4c2d-133">ファイル名</span><span class="sxs-lookup"><span data-stu-id="d4c2d-133">File name</span></span></param>
        <param name="mode"><span data-ttu-id="d4c2d-134">場合に失敗したりする上書き仕掛けてが存在します。</span><span class="sxs-lookup"><span data-stu-id="d4c2d-134">If exists hether to overwrite or fail</span></span></param>
        <param name="octalPermission"><span data-ttu-id="d4c2d-135">アクセス許可文字列</span><span class="sxs-lookup"><span data-stu-id="d4c2d-135">Permission string</span></span></param>
        <param name="createParent"><span data-ttu-id="d4c2d-136">親を作成する場合は true。 ディレクトリ - 現在影響を与えません</span><span class="sxs-lookup"><span data-stu-id="d4c2d-136">True if we create parent directories- currently has no effect</span></span></param>
        <summary>
            <span data-ttu-id="d4c2d-137">新しいファイルの内部ディクショナリへのエントリを作成します。</span><span class="sxs-lookup"><span data-stu-id="d4c2d-137">Creates an entry to the internal dictionary for the new file.</span></span> <span data-ttu-id="d4c2d-138">AclStatus、DirectoryEntry およびメモリ ストリーム エントリをカプセル化します。</span><span class="sxs-lookup"><span data-stu-id="d4c2d-138">The entry encapsulates AclStatus, DirectoryEntry and a memory stream</span></span>
            </summary>
        <returns><span data-ttu-id="d4c2d-139">モック ADls 出力ストリーム</span><span class="sxs-lookup"><span data-stu-id="d4c2d-139">Mock ADls output stream</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public override bool Delete (string path, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Delete(string path, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient.Delete(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Delete (path As String, Optional cancelToken As CancellationToken = null) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Delete : string * System.Threading.CancellationToken -&gt; bool" Usage="mockAdlsClient.Delete (path, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="d4c2d-140">ファイルまたはディレクトリのパス</span><span class="sxs-lookup"><span data-stu-id="d4c2d-140">Path of the file or directory</span></span></param>
        <param name="cancelToken"><span data-ttu-id="d4c2d-141">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="d4c2d-141">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="d4c2d-142">内部辞書からエントリを削除します。</span><span class="sxs-lookup"><span data-stu-id="d4c2d-142">Delete an entry from the internal dictionary</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteRecursive">
      <MemberSignature Language="C#" Value="public override bool DeleteRecursive (string path, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool DeleteRecursive(string path, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient.DeleteRecursive(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function DeleteRecursive (path As String, Optional cancelToken As CancellationToken = null) As Boolean" />
      <MemberSignature Language="F#" Value="override this.DeleteRecursive : string * System.Threading.CancellationToken -&gt; bool" Usage="mockAdlsClient.DeleteRecursive (path, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="d4c2d-143">ディレクトリまたはファイルのパス</span><span class="sxs-lookup"><span data-stu-id="d4c2d-143">Path of directory or file</span></span></param>
        <param name="cancelToken"><span data-ttu-id="d4c2d-144">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="d4c2d-144">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="d4c2d-145">ディレクトリまたは削除ファイル内のすべてのエントリを削除します。</span><span class="sxs-lookup"><span data-stu-id="d4c2d-145">Deletes all entries within a directory or delete a file</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnumerateDirectory">
      <MemberSignature Language="C#" Value="public override System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.DataLake.Store.DirectoryEntry&gt; EnumerateDirectory (string path, Microsoft.Azure.DataLake.Store.UserGroupRepresentation userIdFormat = Microsoft.Azure.DataLake.Store.UserGroupRepresentation.ObjectID, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.DataLake.Store.DirectoryEntry&gt; EnumerateDirectory(string path, valuetype Microsoft.Azure.DataLake.Store.UserGroupRepresentation userIdFormat, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient.EnumerateDirectory(System.String,Microsoft.Azure.DataLake.Store.UserGroupRepresentation,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function EnumerateDirectory (path As String, Optional userIdFormat As UserGroupRepresentation = Microsoft.Azure.DataLake.Store.UserGroupRepresentation.ObjectID, Optional cancelToken As CancellationToken = null) As IEnumerable(Of DirectoryEntry)" />
      <MemberSignature Language="F#" Value="override this.EnumerateDirectory : string * Microsoft.Azure.DataLake.Store.UserGroupRepresentation * System.Threading.CancellationToken -&gt; seq&lt;Microsoft.Azure.DataLake.Store.DirectoryEntry&gt;" Usage="mockAdlsClient.EnumerateDirectory (path, userIdFormat, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.DataLake.Store.DirectoryEntry&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="userIdFormat" Type="Microsoft.Azure.DataLake.Store.UserGroupRepresentation" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="d4c2d-146">ディレクトリまたはファイルのパス</span><span class="sxs-lookup"><span data-stu-id="d4c2d-146">Path of directory or file</span></span></param>
        <param name="userIdFormat"><span data-ttu-id="d4c2d-147">ユーザーまたはグループの Id の形式</span><span class="sxs-lookup"><span data-stu-id="d4c2d-147">User or group Id format</span></span></param>
        <param name="cancelToken"><span data-ttu-id="d4c2d-148">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="d4c2d-148">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="d4c2d-149">指定したディレクトリの下に含まれるエントリの一覧を返します</span><span class="sxs-lookup"><span data-stu-id="d4c2d-149">Returns a list of entries contained under the given directory</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAclStatus">
      <MemberSignature Language="C#" Value="public override Microsoft.Azure.DataLake.Store.Acl.AclStatus GetAclStatus (string path, Microsoft.Azure.DataLake.Store.UserGroupRepresentation userIdFormat = Microsoft.Azure.DataLake.Store.UserGroupRepresentation.ObjectID, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.Azure.DataLake.Store.Acl.AclStatus GetAclStatus(string path, valuetype Microsoft.Azure.DataLake.Store.UserGroupRepresentation userIdFormat, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient.GetAclStatus(System.String,Microsoft.Azure.DataLake.Store.UserGroupRepresentation,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetAclStatus (path As String, Optional userIdFormat As UserGroupRepresentation = Microsoft.Azure.DataLake.Store.UserGroupRepresentation.ObjectID, Optional cancelToken As CancellationToken = null) As AclStatus" />
      <MemberSignature Language="F#" Value="override this.GetAclStatus : string * Microsoft.Azure.DataLake.Store.UserGroupRepresentation * System.Threading.CancellationToken -&gt; Microsoft.Azure.DataLake.Store.Acl.AclStatus" Usage="mockAdlsClient.GetAclStatus (path, userIdFormat, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.DataLake.Store.Acl.AclStatus</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="userIdFormat" Type="Microsoft.Azure.DataLake.Store.UserGroupRepresentation" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="d4c2d-150">ファイルまたはディレクトリのパス</span><span class="sxs-lookup"><span data-stu-id="d4c2d-150">Path of the file or directory</span></span></param>
        <param name="userIdFormat"><span data-ttu-id="d4c2d-151">ユーザー/グループ オブジェクトを表現する方法</span><span class="sxs-lookup"><span data-stu-id="d4c2d-151">way to represent the user/group object</span></span></param>
        <param name="cancelToken"><span data-ttu-id="d4c2d-152">CancellationToken 要求を取り消します</span><span class="sxs-lookup"><span data-stu-id="d4c2d-152">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="d4c2d-153">ACL エントリの一覧、所有者 ID、グループ ID、8 進数のアクセス許可およびファイルまたはディレクトリの (ディレクトリ) の場合のみ sticky ビットを取得します。</span><span class="sxs-lookup"><span data-stu-id="d4c2d-153">Gets the ACL entry list, owner ID, group ID, octal permission and sticky bit (only for a directory) of the file/directory</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAppendStream">
      <MemberSignature Language="C#" Value="public override Microsoft.Azure.DataLake.Store.AdlsOutputStream GetAppendStream (string filename, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.Azure.DataLake.Store.AdlsOutputStream GetAppendStream(string filename, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient.GetAppendStream(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetAppendStream (filename As String, Optional cancelToken As CancellationToken = null) As AdlsOutputStream" />
      <MemberSignature Language="F#" Value="override this.GetAppendStream : string * System.Threading.CancellationToken -&gt; Microsoft.Azure.DataLake.Store.AdlsOutputStream" Usage="mockAdlsClient.GetAppendStream (filename, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.DataLake.Store.AdlsOutputStream</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filename" Type="System.String" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="filename"><span data-ttu-id="d4c2d-154">ファイル名</span><span class="sxs-lookup"><span data-stu-id="d4c2d-154">File name</span></span></param>
        <param name="cancelToken"><span data-ttu-id="d4c2d-155">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="d4c2d-155">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="d4c2d-156">モック adls 出力ストリーム内のカプセル化されたファイルに追加メモリ ストリームを返します。</span><span class="sxs-lookup"><span data-stu-id="d4c2d-156">Returns the memory stream for appending to the file encapsulated in mock adls output stream.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDirectoryEntry">
      <MemberSignature Language="C#" Value="public override Microsoft.Azure.DataLake.Store.DirectoryEntry GetDirectoryEntry (string path, Microsoft.Azure.DataLake.Store.UserGroupRepresentation userIdFormat = Microsoft.Azure.DataLake.Store.UserGroupRepresentation.ObjectID, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.Azure.DataLake.Store.DirectoryEntry GetDirectoryEntry(string path, valuetype Microsoft.Azure.DataLake.Store.UserGroupRepresentation userIdFormat, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient.GetDirectoryEntry(System.String,Microsoft.Azure.DataLake.Store.UserGroupRepresentation,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetDirectoryEntry (path As String, Optional userIdFormat As UserGroupRepresentation = Microsoft.Azure.DataLake.Store.UserGroupRepresentation.ObjectID, Optional cancelToken As CancellationToken = null) As DirectoryEntry" />
      <MemberSignature Language="F#" Value="override this.GetDirectoryEntry : string * Microsoft.Azure.DataLake.Store.UserGroupRepresentation * System.Threading.CancellationToken -&gt; Microsoft.Azure.DataLake.Store.DirectoryEntry" Usage="mockAdlsClient.GetDirectoryEntry (path, userIdFormat, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.DataLake.Store.DirectoryEntry</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="userIdFormat" Type="Microsoft.Azure.DataLake.Store.UserGroupRepresentation" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="d4c2d-157">ファイルまたはディレクトリのパス</span><span class="sxs-lookup"><span data-stu-id="d4c2d-157">Path of file or directory</span></span></param>
        <param name="userIdFormat"><span data-ttu-id="d4c2d-158">ユーザーまたはグループの Id の形式</span><span class="sxs-lookup"><span data-stu-id="d4c2d-158">User or group Id format</span></span></param>
        <param name="cancelToken"><span data-ttu-id="d4c2d-159">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="d4c2d-159">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="d4c2d-160">ディレクトリまたはファイルの情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="d4c2d-160">Get Directory or file info</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMockClient">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient GetMockClient ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient GetMockClient() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient.GetMockClient" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetMockClient () As MockAdlsClient" />
      <MemberSignature Language="F#" Value="static member GetMockClient : unit -&gt; Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient" Usage="Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient.GetMockClient " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d4c2d-161">モック adls クライアントのインスタンスを返すファクトリ メソッド</span><span class="sxs-lookup"><span data-stu-id="d4c2d-161">Factory method that returns an instance of Mock adls client</span></span>
            </summary>
        <returns><span data-ttu-id="d4c2d-162">モック ADls クライアント</span><span class="sxs-lookup"><span data-stu-id="d4c2d-162">Mock ADls Client</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetReadStream">
      <MemberSignature Language="C#" Value="public override Microsoft.Azure.DataLake.Store.AdlsInputStream GetReadStream (string filename, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.Azure.DataLake.Store.AdlsInputStream GetReadStream(string filename, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient.GetReadStream(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetReadStream (filename As String, Optional cancelToken As CancellationToken = null) As AdlsInputStream" />
      <MemberSignature Language="F#" Value="override this.GetReadStream : string * System.Threading.CancellationToken -&gt; Microsoft.Azure.DataLake.Store.AdlsInputStream" Usage="mockAdlsClient.GetReadStream (filename, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.DataLake.Store.AdlsInputStream</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filename" Type="System.String" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="filename"><span data-ttu-id="d4c2d-163">ファイル名</span><span class="sxs-lookup"><span data-stu-id="d4c2d-163">File name</span></span></param>
        <param name="cancelToken"><span data-ttu-id="d4c2d-164">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="d4c2d-164">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="d4c2d-165">ファイルのデータを読み取るためのメモリ ストリームを返します</span><span class="sxs-lookup"><span data-stu-id="d4c2d-165">Returns a memory stream for reading data of the file</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ModifyAclEntries">
      <MemberSignature Language="C#" Value="public override void ModifyAclEntries (string path, System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; aclSpec, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void ModifyAclEntries(string path, class System.Collections.Generic.List`1&lt;class Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; aclSpec, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient.ModifyAclEntries(System.String,System.Collections.Generic.List{Microsoft.Azure.DataLake.Store.Acl.AclEntry},System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub ModifyAclEntries (path As String, aclSpec As List(Of AclEntry), Optional cancelToken As CancellationToken = null)" />
      <MemberSignature Language="F#" Value="override this.ModifyAclEntries : string * System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; * System.Threading.CancellationToken -&gt; unit" Usage="mockAdlsClient.ModifyAclEntries (path, aclSpec, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclSpec" Type="System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt;" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="d4c2d-166">ファイルまたはディレクトリのパス</span><span class="sxs-lookup"><span data-stu-id="d4c2d-166">Path of file or directory</span></span></param>
        <param name="aclSpec"><span data-ttu-id="d4c2d-167">Acl リストを追加するには</span><span class="sxs-lookup"><span data-stu-id="d4c2d-167">Acl list to append</span></span></param>
        <param name="cancelToken"><span data-ttu-id="d4c2d-168">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="d4c2d-168">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="d4c2d-169">指定したパスの acl エントリを追加します。</span><span class="sxs-lookup"><span data-stu-id="d4c2d-169">Adds acl entries for a given path</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAclEntries">
      <MemberSignature Language="C#" Value="public override void RemoveAclEntries (string path, System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; aclSpec, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void RemoveAclEntries(string path, class System.Collections.Generic.List`1&lt;class Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; aclSpec, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient.RemoveAclEntries(System.String,System.Collections.Generic.List{Microsoft.Azure.DataLake.Store.Acl.AclEntry},System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub RemoveAclEntries (path As String, aclSpec As List(Of AclEntry), Optional cancelToken As CancellationToken = null)" />
      <MemberSignature Language="F#" Value="override this.RemoveAclEntries : string * System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; * System.Threading.CancellationToken -&gt; unit" Usage="mockAdlsClient.RemoveAclEntries (path, aclSpec, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclSpec" Type="System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt;" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="d4c2d-170">ファイルまたはディレクトリのパス</span><span class="sxs-lookup"><span data-stu-id="d4c2d-170">Path of the file or directory</span></span></param>
        <param name="aclSpec"><span data-ttu-id="d4c2d-171">削除する Acl エントリの一覧</span><span class="sxs-lookup"><span data-stu-id="d4c2d-171">List of Acl Entries to remove</span></span></param>
        <param name="cancelToken"><span data-ttu-id="d4c2d-172">CancellationToken 要求を取り消します</span><span class="sxs-lookup"><span data-stu-id="d4c2d-172">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="d4c2d-173">削除は、ファイルまたはメモリに保持する内部 AclStatus からディレクトリの Acl エントリを指定します。</span><span class="sxs-lookup"><span data-stu-id="d4c2d-173">Removes specified Acl Entries for a file or directory from the internal AclStatus maintained in memory.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAllAcls">
      <MemberSignature Language="C#" Value="public override void RemoveAllAcls (string path, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void RemoveAllAcls(string path, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient.RemoveAllAcls(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub RemoveAllAcls (path As String, Optional cancelToken As CancellationToken = null)" />
      <MemberSignature Language="F#" Value="override this.RemoveAllAcls : string * System.Threading.CancellationToken -&gt; unit" Usage="mockAdlsClient.RemoveAllAcls (path, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="d4c2d-174">ファイルまたはディレクトリのパス</span><span class="sxs-lookup"><span data-stu-id="d4c2d-174">Path of the file or directory</span></span></param>
        <param name="cancelToken"><span data-ttu-id="d4c2d-175">CancellationToken 要求を取り消します</span><span class="sxs-lookup"><span data-stu-id="d4c2d-175">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="d4c2d-176">メモリに保持する内部 AclStatus からファイルまたはディレクトリのすべての Acl エントリを削除します。</span><span class="sxs-lookup"><span data-stu-id="d4c2d-176">Removes all Acl Entries for a file or directory from the internal AclStatus maintained in memory.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveDefaultAcls">
      <MemberSignature Language="C#" Value="public override void RemoveDefaultAcls (string path, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void RemoveDefaultAcls(string path, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient.RemoveDefaultAcls(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub RemoveDefaultAcls (path As String, Optional cancelToken As CancellationToken = null)" />
      <MemberSignature Language="F#" Value="override this.RemoveDefaultAcls : string * System.Threading.CancellationToken -&gt; unit" Usage="mockAdlsClient.RemoveDefaultAcls (path, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="d4c2d-177">ファイルまたはディレクトリのパス</span><span class="sxs-lookup"><span data-stu-id="d4c2d-177">Path of the file or directory</span></span></param>
        <param name="cancelToken"><span data-ttu-id="d4c2d-178">CancellationToken 要求を取り消します</span><span class="sxs-lookup"><span data-stu-id="d4c2d-178">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="d4c2d-179">メモリに保持する内部 AclStatus からファイルまたはディレクトリのすべての Acl エントリの AclScope デフォルトを削除します。</span><span class="sxs-lookup"><span data-stu-id="d4c2d-179">Removes all Acl Entries of AclScope default for a file or directory from the internal AclStatus maintained in memory.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Rename">
      <MemberSignature Language="C#" Value="public override bool Rename (string path, string destination, bool overwrite = false, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Rename(string path, string destination, bool overwrite, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient.Rename(System.String,System.String,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Rename (path As String, destination As String, Optional overwrite As Boolean = false, Optional cancelToken As CancellationToken = null) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Rename : string * string * bool * System.Threading.CancellationToken -&gt; bool" Usage="mockAdlsClient.Rename (path, destination, overwrite, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="destination" Type="System.String" />
        <Parameter Name="overwrite" Type="System.Boolean" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="d4c2d-180">ソースのパス名</span><span class="sxs-lookup"><span data-stu-id="d4c2d-180">Source path name</span></span></param>
        <param name="destination"><span data-ttu-id="d4c2d-181">移行先パス</span><span class="sxs-lookup"><span data-stu-id="d4c2d-181">Destination path</span></span></param>
        <param name="overwrite"><span data-ttu-id="d4c2d-182">ターゲット ファイルを上書きする場合は true。</span><span class="sxs-lookup"><span data-stu-id="d4c2d-182">True if we want to overwrite the destination file</span></span></param>
        <param name="cancelToken"><span data-ttu-id="d4c2d-183">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="d4c2d-183">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="d4c2d-184">ソースのエントリを削除し、ソースのエントリの同じメタデータを持つ内部ディクショナリ内に新しいエントリを追加</span><span class="sxs-lookup"><span data-stu-id="d4c2d-184">Removes the source entry and add a new entry in the internal dictionary with the same metadata of the source entry</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetAcl">
      <MemberSignature Language="C#" Value="public override void SetAcl (string path, System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; aclSpec, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void SetAcl(string path, class System.Collections.Generic.List`1&lt;class Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; aclSpec, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient.SetAcl(System.String,System.Collections.Generic.List{Microsoft.Azure.DataLake.Store.Acl.AclEntry},System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub SetAcl (path As String, aclSpec As List(Of AclEntry), Optional cancelToken As CancellationToken = null)" />
      <MemberSignature Language="F#" Value="override this.SetAcl : string * System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; * System.Threading.CancellationToken -&gt; unit" Usage="mockAdlsClient.SetAcl (path, aclSpec, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclSpec" Type="System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt;" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="d4c2d-185">ファイルまたはディレクトリのパス</span><span class="sxs-lookup"><span data-stu-id="d4c2d-185">Path of file or directory</span></span></param>
        <param name="aclSpec"><span data-ttu-id="d4c2d-186">Acl リストを設定するには</span><span class="sxs-lookup"><span data-stu-id="d4c2d-186">Acl list to set</span></span></param>
        <param name="cancelToken"><span data-ttu-id="d4c2d-187">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="d4c2d-187">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="d4c2d-188">指定されたパスに新しい acl エントリを設定します。</span><span class="sxs-lookup"><span data-stu-id="d4c2d-188">Sets new acl entries for the given path.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetExpiryTime">
      <MemberSignature Language="C#" Value="public override void SetExpiryTime (string path, Microsoft.Azure.DataLake.Store.ExpiryOption eopt, long expiryTime, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void SetExpiryTime(string path, valuetype Microsoft.Azure.DataLake.Store.ExpiryOption eopt, int64 expiryTime, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient.SetExpiryTime(System.String,Microsoft.Azure.DataLake.Store.ExpiryOption,System.Int64,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub SetExpiryTime (path As String, eopt As ExpiryOption, expiryTime As Long, Optional cancelToken As CancellationToken = null)" />
      <MemberSignature Language="F#" Value="override this.SetExpiryTime : string * Microsoft.Azure.DataLake.Store.ExpiryOption * int64 * System.Threading.CancellationToken -&gt; unit" Usage="mockAdlsClient.SetExpiryTime (path, eopt, expiryTime, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="eopt" Type="Microsoft.Azure.DataLake.Store.ExpiryOption" />
        <Parameter Name="expiryTime" Type="System.Int64" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="d4c2d-189">ファイルまたはディレクトリのパス</span><span class="sxs-lookup"><span data-stu-id="d4c2d-189">Path of file or directory</span></span></param>
        <param name="eopt"><span data-ttu-id="d4c2d-190">有効期限オプション</span><span class="sxs-lookup"><span data-stu-id="d4c2d-190">Expiry option</span></span></param>
        <param name="expiryTime"><span data-ttu-id="d4c2d-191">有効期限</span><span class="sxs-lookup"><span data-stu-id="d4c2d-191">Expiry time</span></span></param>
        <param name="cancelToken"><span data-ttu-id="d4c2d-192">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="d4c2d-192">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="d4c2d-193">ファイルの有効期限を設定します。</span><span class="sxs-lookup"><span data-stu-id="d4c2d-193">Sets the expiry time for the file.</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetOwner">
      <MemberSignature Language="C#" Value="public override void SetOwner (string path, string owner, string group, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void SetOwner(string path, string owner, string group, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient.SetOwner(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub SetOwner (path As String, owner As String, group As String, Optional cancelToken As CancellationToken = null)" />
      <MemberSignature Language="F#" Value="override this.SetOwner : string * string * string * System.Threading.CancellationToken -&gt; unit" Usage="mockAdlsClient.SetOwner (path, owner, group, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="owner" Type="System.String" />
        <Parameter Name="group" Type="System.String" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="d4c2d-194">ファイルまたはディレクトリのパス</span><span class="sxs-lookup"><span data-stu-id="d4c2d-194">Path of file or directory</span></span></param>
        <param name="owner"><span data-ttu-id="d4c2d-195">所有者の guid</span><span class="sxs-lookup"><span data-stu-id="d4c2d-195">Owner guid</span></span></param>
        <param name="group"><span data-ttu-id="d4c2d-196">グループの guid</span><span class="sxs-lookup"><span data-stu-id="d4c2d-196">Group guid</span></span></param>
        <param name="cancelToken"><span data-ttu-id="d4c2d-197">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="d4c2d-197">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="d4c2d-198">所有者とパスのグループを設定します。</span><span class="sxs-lookup"><span data-stu-id="d4c2d-198">Sets the owner and group of the path</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPermission">
      <MemberSignature Language="C#" Value="public override void SetPermission (string path, string permission, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void SetPermission(string path, string permission, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient.SetPermission(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub SetPermission (path As String, permission As String, Optional cancelToken As CancellationToken = null)" />
      <MemberSignature Language="F#" Value="override this.SetPermission : string * string * System.Threading.CancellationToken -&gt; unit" Usage="mockAdlsClient.SetPermission (path, permission, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="permission" Type="System.String" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="d4c2d-199">ファイルまたはディレクトリのパス</span><span class="sxs-lookup"><span data-stu-id="d4c2d-199">Path of file or directory</span></span></param>
        <param name="permission"><span data-ttu-id="d4c2d-200">アクセス許可文字列</span><span class="sxs-lookup"><span data-stu-id="d4c2d-200">Permission string</span></span></param>
        <param name="cancelToken"><span data-ttu-id="d4c2d-201">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="d4c2d-201">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="d4c2d-202">指定されたパスのアクセス許可文字列を設定します。</span><span class="sxs-lookup"><span data-stu-id="d4c2d-202">Sets the permission string for the given path</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>