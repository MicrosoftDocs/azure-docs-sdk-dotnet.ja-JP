<Type Name="TransferParameters" FullName="Microsoft.Azure.Management.DataLake.Store.TransferParameters">
  <TypeSignature Language="C#" Value="public class TransferParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TransferParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.TransferParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class TransferParameters" />
  <TypeSignature Language="F#" Value="type TransferParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="6f046-101">DataLakeStoreTransferClient のパラメーターを表します。</span><span class="sxs-lookup"><span data-stu-id="6f046-101">Represents parameters for the DataLakeStoreTransferClient.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransferParameters (string inputFilePath, string targetStreamPath, string accountName, int perFileThreadCount = -1, int concurrentFileCount = -1, bool isOverwrite = false, bool isResume = false, bool isBinary = true, bool isRecursive = false, bool isDownload = false, long maxSegmentLength = 268435456, string localMetadataLocation = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string inputFilePath, string targetStreamPath, string accountName, int32 perFileThreadCount, int32 concurrentFileCount, bool isOverwrite, bool isResume, bool isBinary, bool isRecursive, bool isDownload, int64 maxSegmentLength, string localMetadataLocation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.TransferParameters.#ctor(System.String,System.String,System.String,System.Int32,System.Int32,System.Boolean,System.Boolean,System.Boolean,System.Boolean,System.Boolean,System.Int64,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (inputFilePath As String, targetStreamPath As String, accountName As String, Optional perFileThreadCount As Integer = -1, Optional concurrentFileCount As Integer = -1, Optional isOverwrite As Boolean = false, Optional isResume As Boolean = false, Optional isBinary As Boolean = true, Optional isRecursive As Boolean = false, Optional isDownload As Boolean = false, Optional maxSegmentLength As Long = 268435456, Optional localMetadataLocation As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Store.TransferParameters : string * string * string * int * int * bool * bool * bool * bool * bool * int64 * string -&gt; Microsoft.Azure.Management.DataLake.Store.TransferParameters" Usage="new Microsoft.Azure.Management.DataLake.Store.TransferParameters (inputFilePath, targetStreamPath, accountName, perFileThreadCount, concurrentFileCount, isOverwrite, isResume, isBinary, isRecursive, isDownload, maxSegmentLength, localMetadataLocation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="inputFilePath" Type="System.String" />
        <Parameter Name="targetStreamPath" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="perFileThreadCount" Type="System.Int32" />
        <Parameter Name="concurrentFileCount" Type="System.Int32" />
        <Parameter Name="isOverwrite" Type="System.Boolean" />
        <Parameter Name="isResume" Type="System.Boolean" />
        <Parameter Name="isBinary" Type="System.Boolean" />
        <Parameter Name="isRecursive" Type="System.Boolean" />
        <Parameter Name="isDownload" Type="System.Boolean" />
        <Parameter Name="maxSegmentLength" Type="System.Int64" />
        <Parameter Name="localMetadataLocation" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="inputFilePath"><span data-ttu-id="6f046-102">ファイルまたは転送されるフォルダーへの完全パス。</span><span class="sxs-lookup"><span data-stu-id="6f046-102">The full path to the file or folder to be transferred.</span></span></param>
        <param name="targetStreamPath"><span data-ttu-id="6f046-103">ここで、ファイルまたはフォルダーに転送されますストリームの完全パスです。</span><span class="sxs-lookup"><span data-stu-id="6f046-103">The full stream path where the file or folder will be transferred to.</span></span></param>
        <param name="accountName"><span data-ttu-id="6f046-104">転送するアカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="6f046-104">Name of the account to transfer to.</span></span></param>
        <param name="perFileThreadCount"><span data-ttu-id="6f046-105">あたりファイル スレッドの数、並列で転送するファイル セグメントの数を示すです。</span><span class="sxs-lookup"><span data-stu-id="6f046-105">The per file thread count, indicating the number of file segments to transfer in parallel.</span></span> <span data-ttu-id="6f046-106">この番号は、最適なパフォーマンスを FILE_SIZE/maxSegmentLength に制限されます。</span><span class="sxs-lookup"><span data-stu-id="6f046-106">This number is capped at FILE_SIZE/maxSegmentLength for optimal performance.</span></span></param>
        <param name="concurrentFileCount"><span data-ttu-id="6f046-107">並列ファイルの数、フォルダーの転送中に同時に転送するファイルの数を示すです。</span><span class="sxs-lookup"><span data-stu-id="6f046-107">The parallel file count, indicating the number of files to transfer in parallel during a folder transfer.</span></span> <span data-ttu-id="6f046-108">1 つのファイル転送では、このパラメーターは無視されます。</span><span class="sxs-lookup"><span data-stu-id="6f046-108">This parameter is ignored for single file transfers.</span></span> <span data-ttu-id="6f046-109">既定値はフォルダーを転送するための 5</span><span class="sxs-lookup"><span data-stu-id="6f046-109">Default is 5 for folder transfers</span></span></param>
        <param name="isOverwrite"><span data-ttu-id="6f046-110">(省略可能)ターゲット ストリームを上書きするかどうか。</span><span class="sxs-lookup"><span data-stu-id="6f046-110">(Optional) Whether to overwrite the target stream or not.</span></span></param>
        <param name="isResume"><span data-ttu-id="6f046-111">(省略可能)中断された転送を再開するかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="6f046-111">(Optional) Indicates whether to resume a previously interrupted transfer.</span></span></param>
        <param name="isBinary"><span data-ttu-id="6f046-112">(省略可能)入力ファイルをバイナリ ファイル (true) として扱うかどうか、またはレコード境界 (false) に転送のブロックを配置するかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="6f046-112">(Optional) Indicates whether to treat the input file as a binary file (true), or whether to align transfer blocks to record boundaries (false).</span></span></param>
        <param name="isRecursive"><span data-ttu-id="6f046-113">(省略可能)再帰的にソース フォルダーを転送するかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="6f046-113">(Optional) Indicates whether to transfer the source folder recursively or not.</span></span> <span data-ttu-id="6f046-114">True の場合、ソース ディレクトリを転送し、すべてのディレクトリの場合、ディレクトリ構造を保持します。</span><span class="sxs-lookup"><span data-stu-id="6f046-114">If true, will transfer the source directory and all sub directories, preserving directory structure.</span></span></param>
        <param name="isDownload"><span data-ttu-id="6f046-115">設定した場合 (省略可能) <c>true</c> [はダウンロード] 転送シナリオではなくです。</span><span class="sxs-lookup"><span data-stu-id="6f046-115">(Optional) if set to <c>true</c> [is download] instead of an transfer scenario.</span></span> <span data-ttu-id="6f046-116">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="6f046-116">Default is false.</span></span></param>
        <param name="maxSegmentLength"><span data-ttu-id="6f046-117">各セグメントの最大長。</span><span class="sxs-lookup"><span data-stu-id="6f046-117">Maximum length of each segment.</span></span> <span data-ttu-id="6f046-118">既定では 256 mb で、最適なパフォーマンスが得られます。</span><span class="sxs-lookup"><span data-stu-id="6f046-118">The default is 256mb, which gives optimal performance.</span></span> <span data-ttu-id="6f046-119">ご自身の責任に変更します。</span><span class="sxs-lookup"><span data-stu-id="6f046-119">Modify at your own risk.</span></span></param>
        <param name="localMetadataLocation"><span data-ttu-id="6f046-120">(省略可能)ディレクトリ パスを移行が進行中に、ローカルの転送のメタデータ ファイルを格納する場所を示します。</span><span class="sxs-lookup"><span data-stu-id="6f046-120">(Optional) Indicates the directory path where to store the local transfer metadata file while the transfer is in progress.</span></span> <span data-ttu-id="6f046-121">この場所は、このアプリケーションから書き込み可能である必要があります。</span><span class="sxs-lookup"><span data-stu-id="6f046-121">This location must be writeable from this application.</span></span> <span data-ttu-id="6f046-122">既定の場所: SpecialFolder.LocalApplicationData です。</span><span class="sxs-lookup"><span data-stu-id="6f046-122">Default location: SpecialFolder.LocalApplicationData.</span></span></param>
        <summary>
            <span data-ttu-id="6f046-123">DataLakeStoreTransferClient を一連のパラメーターを作成します。</span><span class="sxs-lookup"><span data-stu-id="6f046-123">Creates a new set of parameters for the DataLakeStoreTransferClient.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountName">
      <MemberSignature Language="C#" Value="public string AccountName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AccountName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.AccountName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccountName As String" />
      <MemberSignature Language="F#" Value="member this.AccountName : string" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.AccountName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6f046-124">転送、またはからダウンロードするアカウントの名前を示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="6f046-124">Gets a value indicating the name of the account to transfer to or download from.</span></span>
            </summary>
        <value>
            <span data-ttu-id="6f046-125">アカウントの名前です。</span><span class="sxs-lookup"><span data-stu-id="6f046-125">The name of the account.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConcurrentFileCount">
      <MemberSignature Language="C#" Value="public int ConcurrentFileCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ConcurrentFileCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.ConcurrentFileCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConcurrentFileCount As Integer" />
      <MemberSignature Language="F#" Value="member this.ConcurrentFileCount : int" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.ConcurrentFileCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6f046-126">フォルダーにファイルの数が転送されるか、並列でダウンロードを示している並列ファイルの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="6f046-126">Gets the parallel file count, which indicates how many files in a folder will be transferred or downloaded in parallel</span></span>
            </summary>
        <value>
            <span data-ttu-id="6f046-127">ファイルを転送または同時ダウンロード数。</span><span class="sxs-lookup"><span data-stu-id="6f046-127">The number of files to transfer or download at once.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delimiter">
      <MemberSignature Language="C#" Value="public string Delimiter { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Delimiter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.Delimiter" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Delimiter As String" />
      <MemberSignature Language="F#" Value="member this.Delimiter : string" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.Delimiter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6f046-128">存在する場合は、ファイルは、レコード境界区切りを示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="6f046-128">Gets a value indicating the record boundary delimiter for the file, if any.</span></span>
            </summary>
        <value>
            <span data-ttu-id="6f046-129">レコードの境界の区切り記号</span><span class="sxs-lookup"><span data-stu-id="6f046-129">The record boundary delimiter</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FileEncoding">
      <MemberSignature Language="C#" Value="public System.Text.Encoding FileEncoding { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Text.Encoding FileEncoding" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.FileEncoding" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FileEncoding As Encoding" />
      <MemberSignature Language="F#" Value="member this.FileEncoding : System.Text.Encoding" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.FileEncoding" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Text.Encoding</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6f046-130">転送中のファイルのエンコードを示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="6f046-130">Gets a value indicating the encoding of the file being transferred.</span></span>
            </summary>
        <value>
            <span data-ttu-id="6f046-131">ファイルのエンコーディング。</span><span class="sxs-lookup"><span data-stu-id="6f046-131">The file encoding.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InputFilePath">
      <MemberSignature Language="C#" Value="public string InputFilePath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InputFilePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.InputFilePath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InputFilePath As String" />
      <MemberSignature Language="F#" Value="member this.InputFilePath : string" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.InputFilePath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6f046-132">ファイルまたは転送されるフォルダーへの完全パスを示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="6f046-132">Gets a value indicating the full path to the file or folder to be transferred.</span></span>
            </summary>
        <value>
            <span data-ttu-id="6f046-133">入力ファイルのパス。</span><span class="sxs-lookup"><span data-stu-id="6f046-133">The input file path.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsBinary">
      <MemberSignature Language="C#" Value="public bool IsBinary { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsBinary" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.IsBinary" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsBinary As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsBinary : bool" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.IsBinary" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6f046-134">入力ファイルをバイナリ (true) または区切られた入力 (false) として扱うかどうかを示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="6f046-134">Gets a value indicating whether the input file should be treated as a binary (true) or a delimited input (false).</span></span>
            </summary>
        <value>
          <span data-ttu-id="6f046-135"><c>true</c>このインスタンスは、バイナリ、それ以外の場合<c>false</c>です。</span><span class="sxs-lookup"><span data-stu-id="6f046-135"><c>true</c> if this instance is binary; otherwise, <c>false</c>.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDownload">
      <MemberSignature Language="C#" Value="public bool IsDownload { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsDownload" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.IsDownload" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsDownload As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDownload : bool" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.IsDownload" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6f046-136">このインスタンスが転送ではなく、ローカル コンピューターにダウンロードするかどうかを示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="6f046-136">Gets a value indicating whether this instance is downloading to the local machine instead of transfering.</span></span>
            </summary>
        <value>
          <span data-ttu-id="6f046-137"><c>true</c>場合、このインスタンスがダウンロードされます。 それ以外の場合、 <c>false</c>です。</span><span class="sxs-lookup"><span data-stu-id="6f046-137"><c>true</c> if this instance is download; otherwise, <c>false</c>.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsOverwrite">
      <MemberSignature Language="C#" Value="public bool IsOverwrite { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsOverwrite" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.IsOverwrite" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsOverwrite As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsOverwrite : bool" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.IsOverwrite" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6f046-138">既に存在する場合は、対象のストリームを上書きするかどうかを示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="6f046-138">Gets a value indicating whether to overwrite the target stream if it already exists.</span></span>
            </summary>
        <value>
          <span data-ttu-id="6f046-139"><c>true</c>場合、このインスタンスが上書きされます。 それ以外の場合、 <c>false</c>です。</span><span class="sxs-lookup"><span data-stu-id="6f046-139"><c>true</c> if this instance is overwrite; otherwise, <c>false</c>.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsRecursive">
      <MemberSignature Language="C#" Value="public bool IsRecursive { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsRecursive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.IsRecursive" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsRecursive As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsRecursive : bool" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.IsRecursive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6f046-140">フォルダーの転送元フォルダーの再帰的に転送するかどうかを示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="6f046-140">Gets a value indicating whether the folder transfer should recursively transfer the source folder.</span></span> <span data-ttu-id="6f046-141">これはフォルダーを転送するために有効ではのみであり、ファイル転送は無視されます。</span><span class="sxs-lookup"><span data-stu-id="6f046-141">This is only valid for folder transfers and will be ignored for file transfers.</span></span>
            </summary>
        <value>
          <span data-ttu-id="6f046-142"><c>true</c>場合、このインスタンスが再帰的です。 それ以外の場合、 <c>false</c>です。</span><span class="sxs-lookup"><span data-stu-id="6f046-142"><c>true</c> if this instance is recursive; otherwise, <c>false</c>.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsResume">
      <MemberSignature Language="C#" Value="public bool IsResume { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsResume" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.IsResume" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsResume As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsResume : bool" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.IsResume" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6f046-143">中断された転送を再開するかどうかを示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="6f046-143">Gets a value indicating whether to resume a previously interrupted transfer.</span></span>
            </summary>
        <value>
          <span data-ttu-id="6f046-144"><c>true</c>場合、このインスタンスが再開されます。 それ以外の場合、 <c>false</c>です。</span><span class="sxs-lookup"><span data-stu-id="6f046-144"><c>true</c> if this instance is resume; otherwise, <c>false</c>.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalMetadataLocation">
      <MemberSignature Language="C#" Value="public string LocalMetadataLocation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LocalMetadataLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.LocalMetadataLocation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LocalMetadataLocation As String" />
      <MemberSignature Language="F#" Value="member this.LocalMetadataLocation : string" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.LocalMetadataLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6f046-145">ディレクトリ パスを転送用のメタデータを格納する場所を示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="6f046-145">Gets a value indicating the directory path where to store the metadata for the transfer.</span></span>
            </summary>
        <value>
            <span data-ttu-id="6f046-146">ローカルのメタデータの場所です。</span><span class="sxs-lookup"><span data-stu-id="6f046-146">The local metadata location.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxSegementLength">
      <MemberSignature Language="C#" Value="public long MaxSegementLength { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxSegementLength" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.MaxSegementLength" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxSegementLength As Long" />
      <MemberSignature Language="F#" Value="member this.MaxSegementLength : int64" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.MaxSegementLength" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6f046-147">各セグメントの最大長を取得します。</span><span class="sxs-lookup"><span data-stu-id="6f046-147">Gets the maximum length of each segement.</span></span>
            </summary>
        <value>
            <span data-ttu-id="6f046-148">各セグメントの最大長。</span><span class="sxs-lookup"><span data-stu-id="6f046-148">The maximum length of each segement.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PerFileThreadCount">
      <MemberSignature Language="C#" Value="public int PerFileThreadCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PerFileThreadCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.PerFileThreadCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PerFileThreadCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PerFileThreadCount : int" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.PerFileThreadCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6f046-149">1 つのファイル転送を使用してまたはダウンロードする並列スレッドの最大数を示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="6f046-149">Gets a value indicating the maximum number of parallel threads to use for a single file transfer or download.</span></span>
            </summary>
        <value>
            <span data-ttu-id="6f046-150">ファイルのスレッド数。</span><span class="sxs-lookup"><span data-stu-id="6f046-150">The file thread count.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetStreamPath">
      <MemberSignature Language="C#" Value="public string TargetStreamPath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetStreamPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.TargetStreamPath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TargetStreamPath As String" />
      <MemberSignature Language="F#" Value="member this.TargetStreamPath : string" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.TargetStreamPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6f046-151">ファイルに転送するストリームの完全パスを示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="6f046-151">Gets a value indicating the full stream path where the file will be transferred to.</span></span>
            </summary>
        <value>
            <span data-ttu-id="6f046-152">ターゲット ストリーム パス。</span><span class="sxs-lookup"><span data-stu-id="6f046-152">The target stream path.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>