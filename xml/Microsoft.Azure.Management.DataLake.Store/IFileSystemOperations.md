<Type Name="IFileSystemOperations" FullName="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations">
  <TypeSignature Language="C#" Value="public interface IFileSystemOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IFileSystemOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IFileSystemOperations" />
  <TypeSignature Language="F#" Value="type IFileSystemOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b2b0d-101">FileSystemOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-101">FileSystemOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AppendWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; AppendWithHttpMessagesAsync (string accountName, string path, System.IO.Stream streamContents, Nullable&lt;long&gt; offset = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag = null, Nullable&lt;Guid&gt; leaseId = null, Nullable&lt;Guid&gt; fileSessionId = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; AppendWithHttpMessagesAsync(string accountName, string path, class System.IO.Stream streamContents, valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; leaseId, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; fileSessionId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.AppendWithHttpMessagesAsync(System.String,System.String,System.IO.Stream,System.Nullable{System.Int64},System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag},System.Nullable{System.Guid},System.Nullable{System.Guid},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AppendWithHttpMessagesAsync : string * string * System.IO.Stream * Nullable&lt;int64&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; * Nullable&lt;Guid&gt; * Nullable&lt;Guid&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iFileSystemOperations.AppendWithHttpMessagesAsync (accountName, path, streamContents, offset, syncFlag, leaseId, fileSessionId, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="streamContents" Type="System.IO.Stream" />
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="syncFlag" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt;" />
        <Parameter Name="leaseId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="fileSessionId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="b2b0d-102">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-102">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="b2b0d-103">Data Lake Store のパス (以降で '/') を追加するファイルのです。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-103">The Data Lake Store path (starting with '/') of the file to which to append.</span></span>
            </param>
        <param name="streamContents">
            <span data-ttu-id="b2b0d-104">ファイルに追加するときに含めるファイルの内容。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-104">The file contents to include when appending to the file.</span></span>
            </param>
        <param name="offset">
            <span data-ttu-id="b2b0d-105">追加操作を開始するためのストリームの省略可能なオフセット。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-105">The optional offset in the stream to begin the append operation.</span></span>
            <span data-ttu-id="b2b0d-106">既定では、ストリームの末尾に追加します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-106">Default is to append at the end of the stream.</span></span>
            </param>
        <param name="syncFlag">
            <span data-ttu-id="b2b0d-107">必要に応じて、同時実行の追加が完了した後の対処方法を示します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-107">Optionally indicates what to do after completion of the concurrent append.</span></span> <span data-ttu-id="b2b0d-108">データことを示しますより多くのデータは、クライアントですぐに送信される、ファイル ハンドルの開く/ロックされているままにする (を含むファイルの長さ、最終更新時刻) ファイルのメタデータは更新されません。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-108">DATA indicates that more data will be sent immediately by the client, the file handle should remain open/locked, and file metadata (including file length, last modified time) should NOT get updated.</span></span> <span data-ttu-id="b2b0d-109">メタデータことを示しますより多くのデータは、クライアントですぐに送信される、ファイル ハンドルのままにするオープン/ロックされているファイルのメタデータが更新を取得する必要があります。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-109">METADATA indicates that more data will be sent immediately by the client, the file handle should remain open/locked, and file metadata should get updated.</span></span> <span data-ttu-id="b2b0d-110">閉じることを示します、クライアントにデータの送信が行われますが、ファイル ハンドルが閉じられた/ロック解除、する必要がありますファイル メタデータが更新を取得する必要があります。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-110">CLOSE indicates that the client is done sending data, the file handle should be closed/unlocked, and file metadata should get updated.</span></span> <span data-ttu-id="b2b0d-111">使用可能な値が含まれます: 'データ'、'METADATA'、'終了'</span><span class="sxs-lookup"><span data-stu-id="b2b0d-111">Possible values include: 'DATA', 'METADATA', 'CLOSE'</span></span>
            </param>
        <param name="leaseId">
            <span data-ttu-id="b2b0d-112">省略可能な一意の GUID ファイルごとに単一ライター セマンティクスは、そのためには同じ leaseId でファイルを追加するクライアントだけが許可されることを意味することを確認します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-112">Optional unique GUID per file to ensure single writer semantics, meaning that only clients that append to the file with the same leaseId will be allowed to do so.</span></span>
            </param>
        <param name="fileSessionId">
            <span data-ttu-id="b2b0d-113">1 ファイルすべてを示す省略可能な一意の GUID、同じ追加 fileSessionId は、同じクライアントと同じセッションからです。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-113">Optional unique GUID per file indicating all the appends with the same fileSessionId are from the same client and same session.</span></span> <span data-ttu-id="b2b0d-114">SyncFlag がデータまたはメタデータの場合、パフォーマンスが向上が得られます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-114">This will give a performance benefit when syncFlag is DATA or METADATA.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b2b0d-115">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-115">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b2b0d-116">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-116">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2b0d-117">使用のシリアルを指定したファイルに追加します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-117">Used for serial appends to the specified file.</span></span> <span data-ttu-id="b2b0d-118">注: ターゲットは ConcurrentAppend によって追加されたデータを含めないでください。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-118">NOTE: The target must not contain data added by ConcurrentAppend.</span></span> <span data-ttu-id="b2b0d-119">ConcurrentAppend と追加を同義です。 使用することはできません。ターゲット ファイルが変更されたこれらのいずれかを使用して追加のオプションと、ターゲット ファイルで、その他の追加オプションは使用できません。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-119">ConcurrentAppend and Append cannot be used interchangeably; once a target file has been modified using either of these append options, the other append option cannot be used on the target file.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            <span data-ttu-id="b2b0d-120">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-120">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b2b0d-121">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-121">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CheckAccessWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; CheckAccessWithHttpMessagesAsync (string accountName, string path, string fsaction, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; CheckAccessWithHttpMessagesAsync(string accountName, string path, string fsaction, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.CheckAccessWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CheckAccessWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iFileSystemOperations.CheckAccessWithHttpMessagesAsync (accountName, path, fsaction, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="fsaction" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="b2b0d-122">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-122">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="b2b0d-123">Data Lake Store のパス (以降で '/') のファイルまたはディレクトリのアクセスをチェックします。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-123">The Data Lake Store path (starting with '/') of the file or directory for which to check access.</span></span>
            </param>
        <param name="fsaction">
            <span data-ttu-id="b2b0d-124">正規表現パターンに一致する文字列形式でのシステム操作読み取り/書き込み/実行のファイル ' [rwx-] \ {3\}'</span><span class="sxs-lookup"><span data-stu-id="b2b0d-124">File system operation read/write/execute in string form, matching regex pattern '[rwx-]{3}'</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b2b0d-125">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-125">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b2b0d-126">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2b0d-127">かどうか、指定のアクセスは、指定されたパスを確認します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-127">Checks if the specified access is available at the given path.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            <span data-ttu-id="b2b0d-128">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-128">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b2b0d-129">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-129">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ConcatWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; ConcatWithHttpMessagesAsync (string accountName, string path, System.Collections.Generic.IList&lt;string&gt; sources, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; ConcatWithHttpMessagesAsync(string accountName, string path, class System.Collections.Generic.IList`1&lt;string&gt; sources, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.ConcatWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ConcatWithHttpMessagesAsync : string * string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iFileSystemOperations.ConcatWithHttpMessagesAsync (accountName, path, sources, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="sources" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="b2b0d-130">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-130">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="b2b0d-131">Data Lake Store のパス (以降で '/') の連結の結果として得られる出力先ファイルです。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-131">The Data Lake Store path (starting with '/') of the destination file resulting from the concatenation.</span></span>
            </param>
        <param name="sources">
            <span data-ttu-id="b2b0d-132">一連のコンマ区切りの Data Lake Store パス (以降で '/') を連結する順序で連結するファイルのです。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-132">A list of comma separated Data Lake Store paths (starting with '/') of the files to concatenate, in the order in which they should be concatenated.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b2b0d-133">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-133">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b2b0d-134">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-134">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2b0d-135">出力先ファイル、成功時にすべてのソース ファイルを削除するのには、ソース ファイルのリストを連結します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-135">Concatenates the list of source files into the destination file, removing all source files upon success.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            <span data-ttu-id="b2b0d-136">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-136">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b2b0d-137">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-137">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ConcurrentAppendWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; ConcurrentAppendWithHttpMessagesAsync (string accountName, string path, System.IO.Stream streamContents, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.AppendModeType&gt; appendMode = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; ConcurrentAppendWithHttpMessagesAsync(string accountName, string path, class System.IO.Stream streamContents, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.AppendModeType&gt; appendMode, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.ConcurrentAppendWithHttpMessagesAsync(System.String,System.String,System.IO.Stream,System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.AppendModeType},System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ConcurrentAppendWithHttpMessagesAsync : string * string * System.IO.Stream * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.AppendModeType&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iFileSystemOperations.ConcurrentAppendWithHttpMessagesAsync (accountName, path, streamContents, appendMode, syncFlag, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="streamContents" Type="System.IO.Stream" />
        <Parameter Name="appendMode" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.AppendModeType&gt;" />
        <Parameter Name="syncFlag" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="b2b0d-138">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-138">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="b2b0d-139">Data Lake Store のパス (以降で '/') の同時実行を使用して、追加する追加ファイルです。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-139">The Data Lake Store path (starting with '/') of the file to which to append using concurrent append.</span></span>
            </param>
        <param name="streamContents">
            <span data-ttu-id="b2b0d-140">ファイルに追加するときに含めるファイルの内容。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-140">The file contents to include when appending to the file.</span></span>
            </param>
        <param name="appendMode">
            <span data-ttu-id="b2b0d-141">その存在または追加の既存のファイルを開くだけしていない場合、同時実行の追加の呼び出しはファイルを作成する必要がありますを示します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-141">Indicates the concurrent append call should create the file if it doesn't exist or just open the existing file for append.</span></span> <span data-ttu-id="b2b0d-142">使用可能な値が含まれます '自動 ' の作成。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-142">Possible values include: 'autocreate'</span></span>
            </param>
        <param name="syncFlag">
            <span data-ttu-id="b2b0d-143">必要に応じて、同時実行の追加が完了した後の対処方法を示します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-143">Optionally indicates what to do after completion of the concurrent append.</span></span> <span data-ttu-id="b2b0d-144">データことを示しますより多くのデータは、クライアントですぐに送信される、ファイル ハンドルの開く/ロックされているままにする (を含むファイルの長さ、最終更新時刻) ファイルのメタデータは更新されません。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-144">DATA indicates that more data will be sent immediately by the client, the file handle should remain open/locked, and file metadata (including file length, last modified time) should NOT get updated.</span></span> <span data-ttu-id="b2b0d-145">メタデータことを示しますより多くのデータは、クライアントですぐに送信される、ファイル ハンドルのままにするオープン/ロックされているファイルのメタデータが更新を取得する必要があります。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-145">METADATA indicates that more data will be sent immediately by the client, the file handle should remain open/locked, and file metadata should get updated.</span></span> <span data-ttu-id="b2b0d-146">閉じることを示します、クライアントにデータの送信が行われますが、ファイル ハンドルが閉じられた/ロック解除、する必要がありますファイル メタデータが更新を取得する必要があります。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-146">CLOSE indicates that the client is done sending data, the file handle should be closed/unlocked, and file metadata should get updated.</span></span> <span data-ttu-id="b2b0d-147">使用可能な値が含まれます: 'データ'、'METADATA'、'終了'</span><span class="sxs-lookup"><span data-stu-id="b2b0d-147">Possible values include: 'DATA', 'METADATA', 'CLOSE'</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b2b0d-148">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-148">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b2b0d-149">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-149">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2b0d-150">必要に応じて、指定されたファイルに追加されますがまだ存在しない場合、まずファイルを作成します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-150">Appends to the specified file, optionally first creating the file if it does not yet exist.</span></span> <span data-ttu-id="b2b0d-151">このメソッドは、ファイルに複数の同時追加をサポートします。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-151">This method supports multiple concurrent appends to the file.</span></span> <span data-ttu-id="b2b0d-152">注: ターゲットは作成または通常の (シリアル) Append によって追加されたデータを含めないでください。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-152">NOTE: The target must not contain data added by Create or normal (serial) Append.</span></span> <span data-ttu-id="b2b0d-153">ConcurrentAppend と追加を同義です。 使用することはできません。ターゲット ファイルが変更されたこれらのいずれかを使用して追加のオプションと、ターゲット ファイルで、その他の追加オプションは使用できません。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-153">ConcurrentAppend and Append cannot be used interchangeably; once a target file has been modified using either of these append options, the other append option cannot be used on the target file.</span></span> <span data-ttu-id="b2b0d-154">ConcurrentAppend 順序は保証されませんし、ランディング ターゲット ファイルのデータの重複が発生することができます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-154">ConcurrentAppend does not guarantee order and can result in duplicated data landing in the target file.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            <span data-ttu-id="b2b0d-155">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-155">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b2b0d-156">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-156">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; CreateWithHttpMessagesAsync (string accountName, string path, System.IO.Stream streamContents = null, Nullable&lt;bool&gt; overwrite = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag = null, Nullable&lt;Guid&gt; leaseId = null, Nullable&lt;int&gt; permission = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; CreateWithHttpMessagesAsync(string accountName, string path, class System.IO.Stream streamContents, valuetype System.Nullable`1&lt;bool&gt; overwrite, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; leaseId, valuetype System.Nullable`1&lt;int32&gt; permission, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.CreateWithHttpMessagesAsync(System.String,System.String,System.IO.Stream,System.Nullable{System.Boolean},System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag},System.Nullable{System.Guid},System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateWithHttpMessagesAsync : string * string * System.IO.Stream * Nullable&lt;bool&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; * Nullable&lt;Guid&gt; * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iFileSystemOperations.CreateWithHttpMessagesAsync (accountName, path, streamContents, overwrite, syncFlag, leaseId, permission, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="streamContents" Type="System.IO.Stream" />
        <Parameter Name="overwrite" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="syncFlag" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt;" />
        <Parameter Name="leaseId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="permission" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="b2b0d-157">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-157">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="b2b0d-158">Data Lake Store のパス (以降で '/') のファイルを作成します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-158">The Data Lake Store path (starting with '/') of the file to create.</span></span>
            </param>
        <param name="streamContents">
            <span data-ttu-id="b2b0d-159">ファイルを作成するときに含めるファイルの内容。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-159">The file contents to include when creating the file.</span></span> <span data-ttu-id="b2b0d-160">このパラメーターは省略可能な指定されていない場合、空のファイルに結果として得られます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-160">This parameter is optional, resulting in an empty file if not specified.</span></span>
            </param>
        <param name="overwrite">
            <span data-ttu-id="b2b0d-161">場合を示す値、ファイルは上書きする必要があります。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-161">The indication of if the file should be overwritten.</span></span>
            </param>
        <param name="syncFlag">
            <span data-ttu-id="b2b0d-162">必要に応じて作成の完了後に行う作業を示します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-162">Optionally indicates what to do after completion of the create.</span></span>
            <span data-ttu-id="b2b0d-163">データことを示しますより多くのデータは、クライアントですぐに送信される、ファイル ハンドルの開く/ロックされているままにする (を含むファイルの長さ、最終更新時刻) ファイルのメタデータは更新されません。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-163">DATA indicates that more data will be sent immediately by the client, the file handle should remain open/locked, and file metadata (including file length, last modified time) should NOT get updated.</span></span> <span data-ttu-id="b2b0d-164">メタデータことを示しますより多くのデータは、クライアントですぐに送信される、ファイル ハンドルのままにするオープン/ロックされているファイルのメタデータが更新を取得する必要があります。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-164">METADATA indicates that more data will be sent immediately by the client, the file handle should remain open/locked, and file metadata should get updated.</span></span> <span data-ttu-id="b2b0d-165">閉じることを示します、クライアントにデータの送信が行われますが、ファイル ハンドルが閉じられた/ロック解除、する必要がありますファイル メタデータが更新を取得する必要があります。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-165">CLOSE indicates that the client is done sending data, the file handle should be closed/unlocked, and file metadata should get updated.</span></span> <span data-ttu-id="b2b0d-166">使用可能な値が含まれます: 'データ'、'METADATA'、'終了'</span><span class="sxs-lookup"><span data-stu-id="b2b0d-166">Possible values include: 'DATA', 'METADATA', 'CLOSE'</span></span>
            </param>
        <param name="leaseId">
            <span data-ttu-id="b2b0d-167">省略可能な一意の GUID ファイルごとに単一ライター セマンティクスは、そのためには同じ leaseId でファイルを追加するクライアントだけが許可されることを意味することを確認します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-167">Optional unique GUID per file to ensure single writer semantics, meaning that only clients that append to the file with the same leaseId will be allowed to do so.</span></span>
            </param>
        <param name="permission">
            <span data-ttu-id="b2b0d-168">名前のないユーザー、マスクおよびファイルの作成時に設定される他のアクセス許可の 8 進数表現です。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-168">The octal representation of the unnamed user, mask and other permissions that should be set for the file when created.</span></span> <span data-ttu-id="b2b0d-169">指定しない場合、これらのコンテナーから継承します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-169">If not specified, it inherits these from the container.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b2b0d-170">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-170">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b2b0d-171">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-171">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2b0d-172">必要に応じて指定された内容でファイルを作成します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-172">Creates a file with optionally specified content.</span></span> <span data-ttu-id="b2b0d-173">注: コンテンツを指定する場合、結果として得られるファイルは変更できません ConcurrentAppend を使用します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-173">NOTE: If content is provided, the resulting file cannot be modified using ConcurrentAppend.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            <span data-ttu-id="b2b0d-174">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-174">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b2b0d-175">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-175">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;&gt; DeleteWithHttpMessagesAsync (string accountName, string path, Nullable&lt;bool&gt; recursive = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;&gt; DeleteWithHttpMessagesAsync(string accountName, string path, valuetype System.Nullable`1&lt;bool&gt; recursive, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;&gt;" Usage="iFileSystemOperations.DeleteWithHttpMessagesAsync (accountName, path, recursive, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="b2b0d-176">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-176">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="b2b0d-177">Data Lake Store のパス (以降で '/') のファイルまたはディレクトリを削除します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-177">The Data Lake Store path (starting with '/') of the file or directory to delete.</span></span>
            </param>
        <param name="recursive">
            <span data-ttu-id="b2b0d-178">削除が再帰的になるかどうかを示す、省略可能なスイッチ</span><span class="sxs-lookup"><span data-stu-id="b2b0d-178">The optional switch indicating if the delete should be recursive</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b2b0d-179">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-179">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b2b0d-180">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-180">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2b0d-181">要求されたファイルまたはディレクトリ、必要に応じて再帰的に削除します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-181">Deletes the requested file or directory, optionally recursively.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            <span data-ttu-id="b2b0d-182">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-182">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b2b0d-183">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-183">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b2b0d-184">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-184">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DownloadFile">
      <MemberSignature Language="C#" Value="public void DownloadFile (string accountName, string sourcePath, string destinationPath, int threadCount = -1, bool resume = false, bool overwrite = false, IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferProgress&gt; progressTracker = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DownloadFile(string accountName, string sourcePath, string destinationPath, int32 threadCount, bool resume, bool overwrite, class System.IProgress`1&lt;class Microsoft.Azure.Management.DataLake.Store.TransferProgress&gt; progressTracker, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.DownloadFile(System.String,System.String,System.String,System.Int32,System.Boolean,System.Boolean,System.IProgress{Microsoft.Azure.Management.DataLake.Store.TransferProgress},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DownloadFile : string * string * string * int * bool * bool * IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferProgress&gt; * System.Threading.CancellationToken -&gt; unit" Usage="iFileSystemOperations.DownloadFile (accountName, sourcePath, destinationPath, threadCount, resume, overwrite, progressTracker, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="sourcePath" Type="System.String" />
        <Parameter Name="destinationPath" Type="System.String" />
        <Parameter Name="threadCount" Type="System.Int32" />
        <Parameter Name="resume" Type="System.Boolean" />
        <Parameter Name="overwrite" Type="System.Boolean" />
        <Parameter Name="progressTracker" Type="System.IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferProgress&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="b2b0d-185">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-185">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="sourcePath">
            <span data-ttu-id="b2b0d-186">Data Lake Store のパス (以降で '/') のファイルをダウンロードします。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-186">The Data Lake Store path (starting with '/') of the file to download.</span></span>
            </param>
        <param name="destinationPath">
            <span data-ttu-id="b2b0d-187">ファイルをダウンロードするローカル パスです。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-187">The local path to download the file to.</span></span> <span data-ttu-id="b2b0d-188">ディレクトリが指定されている場合、ファイル名は、同じであるソース ファイル名として</span><span class="sxs-lookup"><span data-stu-id="b2b0d-188">If a directory is specified, the file name will be the same as the source file name</span></span>
            </param>
        <param name="threadCount">
            <span data-ttu-id="b2b0d-189">ダウンロード中に使用するスレッドの最大数。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-189">The maximum number of threads to use during the download.</span></span> <span data-ttu-id="b2b0d-190">既定では、この番号はに基づいて計算ファイルのサイズ。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-190">By default, this number will be computed based on file size.</span></span>
            </param>
        <param name="resume">
            <span data-ttu-id="b2b0d-191">このダウンロードは、障害が発生した以前のダウンロードの継続タスクを示すスイッチです。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-191">A switch indicating if this download is a continuation of a previous, failed download.</span></span> <span data-ttu-id="b2b0d-192">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-192">Default is false.</span></span>
            </param>
        <param name="overwrite">
            <span data-ttu-id="b2b0d-193">このダウンロードを示す、スイッチを上書きする、ターゲット ファイルが存在する場合。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-193">A switch indicating this download should overwrite the the target file if it exists.</span></span> <span data-ttu-id="b2b0d-194">既定値は false、およびターゲット ファイルが存在する場合は、ダウンロードに失敗するが高速されます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-194">Default is false, and the download will fast fail if the target file exists.</span></span>
            </param>
        <param name="progressTracker">
            <span data-ttu-id="b2b0d-195">非同期的にダウンロード操作の進行状況を追跡するために使用できる省略可能なデリゲート。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-195">An optional delegate that can be used to track the progress of the download operation asynchronously.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b2b0d-196">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-196">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2b0d-197">指定された Data Lake Store アカウントからファイルをダウンロードします。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-197">Downloads a file from the specified Data Lake Store account.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            <span data-ttu-id="b2b0d-198">操作に無効なステータス コードが返されるときにスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-198">Thrown when the operation returned an invalid status code.</span></span>
            </exception>
        <exception cref="T:System.Threading.Tasks.TaskCanceledException">
            <span data-ttu-id="b2b0d-199">操作の完了に時間がかかる場合、またはユーザーが明示的にキャンセルするとスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-199">Thrown when the operation takes too long to complete or if the user explicitly cancels it.</span></span>
            </exception>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.InvalidMetadataException">
            <span data-ttu-id="b2b0d-200">再開のメタデータが壊れているか、現在の操作に関連付けられていない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-200">Thrown when resume metadata is corrupt or not associated with the current operation.</span></span>
            </exception>
        <exception cref="T:System.IO.FileNotFoundException">
            <span data-ttu-id="b2b0d-201">ソース パスが見つからない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-201">Thrown when the source path cannot be found.</span></span>
            </exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="b2b0d-202">無効なダウンロードを試行または操作中にファイルが外部で変更された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-202">Thrown if an invalid download is attempted or a file is modified externally during the operation.</span></span>
            </exception>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.TransferFailedException">
            <span data-ttu-id="b2b0d-203">転送操作が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-203">Thrown if the transfer operation fails.</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b2b0d-204">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-204">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b2b0d-205">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-205">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DownloadFolder">
      <MemberSignature Language="C#" Value="public void DownloadFolder (string accountName, string sourcePath, string destinationPath, int perFileThreadCount = -1, int concurrentFileCount = -1, bool resume = false, bool overwrite = false, bool recurse = false, IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress&gt; progressTracker = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DownloadFolder(string accountName, string sourcePath, string destinationPath, int32 perFileThreadCount, int32 concurrentFileCount, bool resume, bool overwrite, bool recurse, class System.IProgress`1&lt;class Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress&gt; progressTracker, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.DownloadFolder(System.String,System.String,System.String,System.Int32,System.Int32,System.Boolean,System.Boolean,System.Boolean,System.IProgress{Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DownloadFolder : string * string * string * int * int * bool * bool * bool * IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress&gt; * System.Threading.CancellationToken -&gt; unit" Usage="iFileSystemOperations.DownloadFolder (accountName, sourcePath, destinationPath, perFileThreadCount, concurrentFileCount, resume, overwrite, recurse, progressTracker, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="sourcePath" Type="System.String" />
        <Parameter Name="destinationPath" Type="System.String" />
        <Parameter Name="perFileThreadCount" Type="System.Int32" />
        <Parameter Name="concurrentFileCount" Type="System.Int32" />
        <Parameter Name="resume" Type="System.Boolean" />
        <Parameter Name="overwrite" Type="System.Boolean" />
        <Parameter Name="recurse" Type="System.Boolean" />
        <Parameter Name="progressTracker" Type="System.IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="b2b0d-206">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-206">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="sourcePath">
            <span data-ttu-id="b2b0d-207">Data Lake Store のパス (以降で '/') をダウンロードするディレクトリ。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-207">The Data Lake Store path (starting with '/') of the directory to download.</span></span>
            </param>
        <param name="destinationPath">
            <span data-ttu-id="b2b0d-208">ダウンロードするフォルダーへのローカル パス。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-208">The local path to download the folder to.</span></span>
            </param>
        <param name="perFileThreadCount">
            <span data-ttu-id="b2b0d-209">ダウンロード中にファイルごとに使用するスレッドの最大数。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-209">The maximum number of threads to use per file during the download.</span></span> <span data-ttu-id="b2b0d-210">既定では、この番号はに基づいて計算フォルダー構造と平均ファイルのサイズ。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-210">By default, this number will be computed based on folder structure and average file size.</span></span>
            </param>
        <param name="concurrentFileCount">
            <span data-ttu-id="b2b0d-211">同時にダウンロードするファイルの最大数。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-211">The maximum number of files to download at once.</span></span> <span data-ttu-id="b2b0d-212">既定では、この番号はに基づいて計算のフォルダー構造およびファイルの数。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-212">By default, this number will be computed based on folder structure and number of files.</span></span>
            </param>
        <param name="resume">
            <span data-ttu-id="b2b0d-213">このダウンロードは、障害が発生した以前のダウンロードの継続タスクを示すスイッチです。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-213">A switch indicating if this download is a continuation of a previous, failed download.</span></span> <span data-ttu-id="b2b0d-214">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-214">Default is false.</span></span>
            </param>
        <param name="overwrite">
            <span data-ttu-id="b2b0d-215">このダウンロードを示すスイッチは、存在する場合、ターゲット ディレクトリの内容を上書きする必要があります。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-215">A switch indicating this download should overwrite the contents of the target directory if it exists.</span></span> <span data-ttu-id="b2b0d-216">既定値は false に設定し、ダウンロードは高速なフェールオーバー ターゲットの場所が存在する場合。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-216">Default is false, and the download will fast fail if the target location exists.</span></span>
            </param>
        <param name="recurse">
            <span data-ttu-id="b2b0d-217">このダウンロードを示すスイッチは、ソース ディレクトリを再帰的にまたは最上位レベルだけをダウンロードする必要があります。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-217">A switch indicating this download should download the source directory recursively or just the top level.</span></span> <span data-ttu-id="b2b0d-218">既定値は false の場合、最上位レベルだけがダウンロードされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-218">Default is false, only the top level will be downloaded.</span></span>
            </param>
        <param name="progressTracker">
            <span data-ttu-id="b2b0d-219">非同期的にダウンロード操作の進行状況を追跡するために使用できる省略可能なデリゲート。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-219">An optional delegate that can be used to track the progress of the download operation asynchronously.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b2b0d-220">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-220">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2b0d-221">指定された Data Lake Store アカウントからフォルダーをダウンロードします。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-221">Downloads a folder from the specified Data Lake Store account.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            <span data-ttu-id="b2b0d-222">操作に無効なステータス コードが返されるときにスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-222">Thrown when the operation returned an invalid status code.</span></span>
            </exception>
        <exception cref="T:System.Threading.Tasks.TaskCanceledException">
            <span data-ttu-id="b2b0d-223">操作の完了に時間がかかる場合、またはユーザーが明示的にキャンセルするとスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-223">Thrown when the operation takes too long to complete or if the user explicitly cancels it.</span></span>
            </exception>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.InvalidMetadataException">
            <span data-ttu-id="b2b0d-224">再開のメタデータが壊れているか、現在の操作に関連付けられていない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-224">Thrown when resume metadata is corrupt or not associated with the current operation.</span></span>
            </exception>
        <exception cref="T:System.IO.FileNotFoundException">
            <span data-ttu-id="b2b0d-225">ソース パスが見つからない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-225">Thrown when the source path cannot be found.</span></span>
            </exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="b2b0d-226">無効なダウンロードを試行またはファイル/フォルダーは、操作中に外部で変更する場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-226">Thrown if an invalid download is attempted or a file/folder is modified externally during the operation.</span></span>
            </exception>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.TransferFailedException">
            <span data-ttu-id="b2b0d-227">転送操作が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-227">Thrown if the transfer operation fails.</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b2b0d-228">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-228">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b2b0d-229">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-229">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetAclStatusWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.AclStatusResult&gt;&gt; GetAclStatusWithHttpMessagesAsync (string accountName, string path, Nullable&lt;bool&gt; tooId = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.AclStatusResult&gt;&gt; GetAclStatusWithHttpMessagesAsync(string accountName, string path, valuetype System.Nullable`1&lt;bool&gt; tooId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.GetAclStatusWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAclStatusWithHttpMessagesAsync : string * string * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.AclStatusResult&gt;&gt;" Usage="iFileSystemOperations.GetAclStatusWithHttpMessagesAsync (accountName, path, tooId, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.AclStatusResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="tooId" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="b2b0d-230">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-230">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="b2b0d-231">Data Lake Store のパス (以降で '/') のファイルまたはディレクトリの ACL を取得します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-231">The Data Lake Store path (starting with '/') of the file or directory for which to get the ACL.</span></span>
            </param>
        <param name="tooId">
            <span data-ttu-id="b2b0d-232">ACL エントリのオブジェクト ID の代わりにわかりやすい名前を返す省略可能なスイッチです。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-232">An optional switch to return friendly names in place of object ID for ACL entries.</span></span> <span data-ttu-id="b2b0d-233">tooid AAD のオブジェクト ID ではなく、false を返しますフレンドリ名を =。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-233">tooid=false returns friendly names instead of the AAD Object ID.</span></span> <span data-ttu-id="b2b0d-234">既定値は true の場合、AAD のオブジェクト Id を取得します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-234">Default value is true, returning AAD object IDs.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b2b0d-235">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-235">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b2b0d-236">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-236">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2b0d-237">指定したファイルまたはディレクトリのアクセス制御リスト (ACL) エントリを取得します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-237">Gets Access Control List (ACL) entries for the specified file or directory.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            <span data-ttu-id="b2b0d-238">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-238">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b2b0d-239">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-239">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b2b0d-240">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-240">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetContentSummaryWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.ContentSummaryResult&gt;&gt; GetContentSummaryWithHttpMessagesAsync (string accountName, string path, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.ContentSummaryResult&gt;&gt; GetContentSummaryWithHttpMessagesAsync(string accountName, string path, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.GetContentSummaryWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetContentSummaryWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.ContentSummaryResult&gt;&gt;" Usage="iFileSystemOperations.GetContentSummaryWithHttpMessagesAsync (accountName, path, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.ContentSummaryResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="b2b0d-241">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-241">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="b2b0d-242">Data Lake Store のパス (以降で '/') の概要を取得する対象のファイルです。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-242">The Data Lake Store path (starting with '/') of the file for which to retrieve the summary.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b2b0d-243">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-243">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b2b0d-244">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-244">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2b0d-245">ファイル パスで指定された、ファイルのコンテンツの集計オブジェクトを取得します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-245">Gets the file content summary object specified by the file path.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            <span data-ttu-id="b2b0d-246">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-246">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b2b0d-247">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-247">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b2b0d-248">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-248">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetFileStatusWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileStatusResult&gt;&gt; GetFileStatusWithHttpMessagesAsync (string accountName, string path, Nullable&lt;bool&gt; tooId = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.FileStatusResult&gt;&gt; GetFileStatusWithHttpMessagesAsync(string accountName, string path, valuetype System.Nullable`1&lt;bool&gt; tooId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.GetFileStatusWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetFileStatusWithHttpMessagesAsync : string * string * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileStatusResult&gt;&gt;" Usage="iFileSystemOperations.GetFileStatusWithHttpMessagesAsync (accountName, path, tooId, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileStatusResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="tooId" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="b2b0d-249">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-249">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="b2b0d-250">Data Lake Store のパス (以降で '/') のファイルまたは状態を取得する対象のディレクトリ。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-250">The Data Lake Store path (starting with '/') of the file or directory for which to retrieve the status.</span></span>
            </param>
        <param name="tooId">
            <span data-ttu-id="b2b0d-251">所有者とグループの代わりにわかりやすい名前を返す省略可能なスイッチです。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-251">An optional switch to return friendly names in place of owner and group.</span></span> <span data-ttu-id="b2b0d-252">tooid AAD のオブジェクト ID ではなく、false を返しますフレンドリ名を =。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-252">tooid=false returns friendly names instead of the AAD Object ID.</span></span> <span data-ttu-id="b2b0d-253">既定値は true の場合、AAD のオブジェクト Id を取得します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-253">Default value is true, returning AAD object IDs.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b2b0d-254">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-254">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b2b0d-255">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-255">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2b0d-256">ファイルのパスで指定されたファイルの状態オブジェクトを取得します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-256">Get the file status object specified by the file path.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            <span data-ttu-id="b2b0d-257">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-257">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b2b0d-258">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-258">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b2b0d-259">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-259">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListFileStatusWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileStatusesResult&gt;&gt; ListFileStatusWithHttpMessagesAsync (string accountName, string path, Nullable&lt;int&gt; listSize = null, string listAfter = null, string listBefore = null, Nullable&lt;bool&gt; tooId = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.FileStatusesResult&gt;&gt; ListFileStatusWithHttpMessagesAsync(string accountName, string path, valuetype System.Nullable`1&lt;int32&gt; listSize, string listAfter, string listBefore, valuetype System.Nullable`1&lt;bool&gt; tooId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.ListFileStatusWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int32},System.String,System.String,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListFileStatusWithHttpMessagesAsync : string * string * Nullable&lt;int&gt; * string * string * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileStatusesResult&gt;&gt;" Usage="iFileSystemOperations.ListFileStatusWithHttpMessagesAsync (accountName, path, listSize, listAfter, listBefore, tooId, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileStatusesResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="listSize" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="listAfter" Type="System.String" />
        <Parameter Name="listBefore" Type="System.String" />
        <Parameter Name="tooId" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="b2b0d-260">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-260">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="b2b0d-261">Data Lake Store のパス (以降で '/') のリストにディレクトリ。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-261">The Data Lake Store path (starting with '/') of the directory to list.</span></span>
            </param>
        <param name="listSize">
            <span data-ttu-id="b2b0d-262">取得または返されるアイテムの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-262">Gets or sets the number of items to return.</span></span> <span data-ttu-id="b2b0d-263">省略可能。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-263">Optional.</span></span>
            </param>
        <param name="listAfter">
            <span data-ttu-id="b2b0d-264">取得または結果を返すを開始位置となる項目または lexographical インデックスを設定します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-264">Gets or sets the item or lexographical index after which to begin returning results.</span></span> <span data-ttu-id="b2b0d-265">たとえば、'',' b' のファイル リストに指定された受信者 'と listAfter = 'b' は戻り値は '、および、listAfter = 'c' が戻り値と' です。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-265">For example, a file list of 'a','b','d' and listAfter='b' will return 'd', and a listAfter='c' will also return 'd'.</span></span> <span data-ttu-id="b2b0d-266">省略可能。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-266">Optional.</span></span>
            </param>
        <param name="listBefore">
            <span data-ttu-id="b2b0d-267">取得または結果を返すを開始する前に、項目または lexographical のインデックスを設定します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-267">Gets or sets the item or lexographical index before which to begin returning results.</span></span> <span data-ttu-id="b2b0d-268">たとえば、'',' b' のファイル リストに指定された受信者 'と listBefore = が' 'a'、'b'、および、listBefore に戻ります = 'c'、'a ',' b' を返すこともします。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-268">For example, a file list of 'a','b','d' and listBefore='d' will return 'a','b', and a listBefore='c' will also return 'a','b'.</span></span> <span data-ttu-id="b2b0d-269">省略可能。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-269">Optional.</span></span>
            </param>
        <param name="tooId">
            <span data-ttu-id="b2b0d-270">所有者とグループの代わりにわかりやすい名前を返す省略可能なスイッチです。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-270">An optional switch to return friendly names in place of owner and group.</span></span> <span data-ttu-id="b2b0d-271">tooid AAD のオブジェクト ID ではなく、false を返しますフレンドリ名を =。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-271">tooid=false returns friendly names instead of the AAD Object ID.</span></span> <span data-ttu-id="b2b0d-272">既定値は true の場合、AAD のオブジェクト Id を取得します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-272">Default value is true, returning AAD object IDs.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b2b0d-273">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-273">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b2b0d-274">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-274">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2b0d-275">省略可能な改ページ調整パラメーターを使用して、ファイルのパスで指定されたファイルの状態オブジェクトの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-275">Get the list of file status objects specified by the file path, with optional pagination parameters</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            <span data-ttu-id="b2b0d-276">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-276">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b2b0d-277">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-277">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b2b0d-278">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-278">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MkdirsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;&gt; MkdirsWithHttpMessagesAsync (string accountName, string path, Nullable&lt;int&gt; permission = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;&gt; MkdirsWithHttpMessagesAsync(string accountName, string path, valuetype System.Nullable`1&lt;int32&gt; permission, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.MkdirsWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member MkdirsWithHttpMessagesAsync : string * string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;&gt;" Usage="iFileSystemOperations.MkdirsWithHttpMessagesAsync (accountName, path, permission, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="permission" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="b2b0d-279">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-279">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="b2b0d-280">Data Lake Store のパス (以降で '/') を作成するディレクトリ。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-280">The Data Lake Store path (starting with '/') of the directory to create.</span></span>
            </param>
        <param name="permission">
            <span data-ttu-id="b2b0d-281">省略可能な 8 進数のアクセス許可のディレクトリの作成に使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-281">Optional octal permission with which the directory should be created.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b2b0d-282">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-282">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b2b0d-283">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-283">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2b0d-284">ディレクトリを作成します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-284">Creates a directory.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            <span data-ttu-id="b2b0d-285">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-285">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b2b0d-286">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-286">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b2b0d-287">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-287">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ModifyAclEntriesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; ModifyAclEntriesWithHttpMessagesAsync (string accountName, string path, string aclspec, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; ModifyAclEntriesWithHttpMessagesAsync(string accountName, string path, string aclspec, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.ModifyAclEntriesWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ModifyAclEntriesWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iFileSystemOperations.ModifyAclEntriesWithHttpMessagesAsync (accountName, path, aclspec, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclspec" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="b2b0d-288">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-288">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="b2b0d-289">Data Lake Store のパス (以降で '/') のファイルまたはディレクトリが変更されている ACL を使用します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-289">The Data Lake Store path (starting with '/') of the file or directory with the ACL being modified.</span></span>
            </param>
        <param name="aclspec">
            <span data-ttu-id="b2b0d-290">形式で、ACL の変更操作に含まれている ACL 仕様 ' [既定値:] ユーザー | グループ | その他の:: r |-w |-x |-'</span><span class="sxs-lookup"><span data-stu-id="b2b0d-290">The ACL specification included in ACL modification operations in the format '[default:]user|group|other::r|-w|-x|-'</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b2b0d-291">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-291">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b2b0d-292">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-292">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2b0d-293">ファイルまたはフォルダーの既存のアクセス制御リスト (ACL) エントリを変更します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-293">Modifies existing Access Control List (ACL) entries on a file or folder.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            <span data-ttu-id="b2b0d-294">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-294">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b2b0d-295">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-295">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MsConcatWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; MsConcatWithHttpMessagesAsync (string accountName, string path, System.IO.Stream streamContents, Nullable&lt;bool&gt; deleteSourceDirectory = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; MsConcatWithHttpMessagesAsync(string accountName, string path, class System.IO.Stream streamContents, valuetype System.Nullable`1&lt;bool&gt; deleteSourceDirectory, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.MsConcatWithHttpMessagesAsync(System.String,System.String,System.IO.Stream,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member MsConcatWithHttpMessagesAsync : string * string * System.IO.Stream * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iFileSystemOperations.MsConcatWithHttpMessagesAsync (accountName, path, streamContents, deleteSourceDirectory, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="streamContents" Type="System.IO.Stream" />
        <Parameter Name="deleteSourceDirectory" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="b2b0d-296">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-296">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="b2b0d-297">Data Lake Store のパス (以降で '/') の連結の結果として得られる出力先ファイルです。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-297">The Data Lake Store path (starting with '/') of the destination file resulting from the concatenation.</span></span>
            </param>
        <param name="streamContents">
            <span data-ttu-id="b2b0d-298">Data Lake Store パスの一覧 (以降で '/') のソース ファイルです。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-298">A list of Data Lake Store paths (starting with '/') of the source files.</span></span> <span data-ttu-id="b2b0d-299">形式でパスのコンマ区切りの一覧でなければなりません: sources=/file/path/1.txt,/file/path/2.txt,/file/path/lastfile.csv</span><span class="sxs-lookup"><span data-stu-id="b2b0d-299">Must be a comma-separated path list in the format: sources=/file/path/1.txt,/file/path/2.txt,/file/path/lastfile.csv</span></span>
            </param>
        <param name="deleteSourceDirectory">
            <span data-ttu-id="b2b0d-300">指定すると、最適化代わりに各個々 のソース ストリームを削除するには、フォルダーを削除、ソース ストリーム場合は代わりに、同じフォルダーにすべてのストリーム。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-300">Indicates that as an optimization instead of deleting each individual source stream, delete the source stream folder if all streams are in the same folder instead.</span></span> <span data-ttu-id="b2b0d-301">これは、結果、フォルダー内のみのストリームが連結操作の一部とパフォーマンスが大幅に改善します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-301">This results in a substantial performance improvement when the only streams in the folder are part of the concatenation operation.</span></span> <span data-ttu-id="b2b0d-302">警告: ソース ファイルではないその他のファイルの削除が含まれます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-302">WARNING: This includes the deletion of any other files that are not source files.</span></span>
            <span data-ttu-id="b2b0d-303">ソース ファイルがソース ディレクトリのファイルのみの場合は true にのみ設定します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-303">Only set this to true when source files are the only files in the source directory.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b2b0d-304">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-304">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b2b0d-305">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-305">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2b0d-306">出力先ファイル、成功時にすべてのソース ファイルを削除するのには、ソース ファイルのリストを連結します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-306">Concatenates the list of source files into the destination file, deleting all source files upon success.</span></span> <span data-ttu-id="b2b0d-307">このメソッドは、Concat メソッドよりも多くのソース ファイルのパスを受け取ります。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-307">This method accepts more source file paths than the Concat method.</span></span> <span data-ttu-id="b2b0d-308">このメソッドと、受け取るパラメーターは、使いやすさ、今後のバージョンでの変更の対象はします。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-308">This method and the parameters it accepts are subject to change for usability in an upcoming version.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            <span data-ttu-id="b2b0d-309">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-309">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b2b0d-310">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-310">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="OpenWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.IO.Stream&gt;&gt; OpenWithHttpMessagesAsync (string accountName, string path, Nullable&lt;long&gt; length = null, Nullable&lt;long&gt; offset = null, Nullable&lt;Guid&gt; fileSessionId = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.IO.Stream&gt;&gt; OpenWithHttpMessagesAsync(string accountName, string path, valuetype System.Nullable`1&lt;int64&gt; length, valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; fileSessionId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.OpenWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Guid},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OpenWithHttpMessagesAsync : string * string * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;Guid&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.IO.Stream&gt;&gt;" Usage="iFileSystemOperations.OpenWithHttpMessagesAsync (accountName, path, length, offset, fileSessionId, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.IO.Stream&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="length" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="fileSessionId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="b2b0d-311">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-311">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="b2b0d-312">Data Lake Store のパス (以降で '/') のファイルを開きます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-312">The Data Lake Store path (starting with '/') of the file to open.</span></span>
            </param>
        <param name="length">
            <span data-ttu-id="b2b0d-313">サーバーが取得しようとするバイト数。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-313">The number of bytes that the server will attempt to retrieve.</span></span> <span data-ttu-id="b2b0d-314">取得されます&lt;長さのバイト数を = です。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-314">It will retrieve &lt;= length bytes.</span></span>
            </param>
        <param name="offset">
            <span data-ttu-id="b2b0d-315">データの読み取りを開始するバイト オフセット。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-315">The byte offset to start reading data from.</span></span>
            </param>
        <param name="fileSessionId">
            <span data-ttu-id="b2b0d-316">1 ファイルが同じ fileSessionId ですべての読み取りを示す省略可能な一意の GUID は、同じクライアントと同じセッションです。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-316">Optional unique GUID per file indicating all the reads with the same fileSessionId are from the same client and same session.</span></span> <span data-ttu-id="b2b0d-317">パフォーマンス上の利点が得られます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-317">This will give a performance benefit.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b2b0d-318">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-318">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b2b0d-319">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-319">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2b0d-320">開き、指定したファイルから読み取ります。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-320">Opens and reads from the specified file.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b2b0d-321">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-321">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b2b0d-322">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-322">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b2b0d-323">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-323">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="PathExistsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;bool&gt;&gt; PathExistsWithHttpMessagesAsync (string accountName, string getFilePath, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;bool&gt;&gt; PathExistsWithHttpMessagesAsync(string accountName, string getFilePath, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.PathExistsWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PathExistsWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;bool&gt;&gt;" Usage="iFileSystemOperations.PathExistsWithHttpMessagesAsync (accountName, getFilePath, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Boolean&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="getFilePath" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="b2b0d-324">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-324">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="getFilePath">
            <span data-ttu-id="b2b0d-325">Data Lake Store のパス (以降で '/') のファイルまたはテスト対象のディレクトリ。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-325">The Data Lake Store path (starting with '/') of the file or directory for which to test.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b2b0d-326">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-326">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b2b0d-327">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-327">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2b0d-328">ファイル パスで指定されたファイルまたはディレクトリ オブジェクトの存在をテストします。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-328">Test the existence of a file or directory object specified by the file path.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            <span data-ttu-id="b2b0d-329">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-329">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b2b0d-330">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-330">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b2b0d-331">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-331">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="b2b0d-332">応答本文および応答ヘッダーを含む応答オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-332">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="RemoveAclEntriesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; RemoveAclEntriesWithHttpMessagesAsync (string accountName, string path, string aclspec, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; RemoveAclEntriesWithHttpMessagesAsync(string accountName, string path, string aclspec, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.RemoveAclEntriesWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RemoveAclEntriesWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iFileSystemOperations.RemoveAclEntriesWithHttpMessagesAsync (accountName, path, aclspec, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclspec" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="b2b0d-333">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-333">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="b2b0d-334">Data Lake Store のパス (以降で '/') のファイルまたはディレクトリ ACL を削除します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-334">The Data Lake Store path (starting with '/') of the file or directory with the ACL being removed.</span></span>
            </param>
        <param name="aclspec">
            <span data-ttu-id="b2b0d-335">形式で、ACL の削除操作に含まれている ACL spec ' [既定値:] ユーザー | グループ | その他の '</span><span class="sxs-lookup"><span data-stu-id="b2b0d-335">The ACL spec included in ACL removal operations in the format '[default:]user|group|other'</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b2b0d-336">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-336">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b2b0d-337">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-337">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2b0d-338">既存のファイルまたはフォルダーのアクセス制御リスト (ACL) エントリを削除します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-338">Removes existing Access Control List (ACL) entries for a file or folder.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            <span data-ttu-id="b2b0d-339">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-339">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b2b0d-340">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-340">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveAclWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; RemoveAclWithHttpMessagesAsync (string accountName, string path, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; RemoveAclWithHttpMessagesAsync(string accountName, string path, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.RemoveAclWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RemoveAclWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iFileSystemOperations.RemoveAclWithHttpMessagesAsync (accountName, path, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="b2b0d-341">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-341">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="b2b0d-342">Data Lake Store のパス (以降で '/') のファイルまたはディレクトリ ACL を削除します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-342">The Data Lake Store path (starting with '/') of the file or directory with the ACL being removed.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b2b0d-343">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-343">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b2b0d-344">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-344">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2b0d-345">指定したファイルまたはディレクトリの既存のアクセス制御リスト (ACL) を削除します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-345">Removes the existing Access Control List (ACL) of the specified file or directory.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            <span data-ttu-id="b2b0d-346">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-346">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b2b0d-347">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-347">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveDefaultAclWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; RemoveDefaultAclWithHttpMessagesAsync (string accountName, string path, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; RemoveDefaultAclWithHttpMessagesAsync(string accountName, string path, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.RemoveDefaultAclWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RemoveDefaultAclWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iFileSystemOperations.RemoveDefaultAclWithHttpMessagesAsync (accountName, path, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="b2b0d-348">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-348">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="b2b0d-349">Data Lake Store のパス (以降で '/') の既定の ACL が削除されると同じディレクトリにします。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-349">The Data Lake Store path (starting with '/') of the directory with the default ACL being removed.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b2b0d-350">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-350">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b2b0d-351">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-351">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2b0d-352">既存既定のアクセス制御リスト (ACL) の指定されたディレクトリを削除します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-352">Removes the existing Default Access Control List (ACL) of the specified directory.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            <span data-ttu-id="b2b0d-353">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-353">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b2b0d-354">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-354">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RenameWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;&gt; RenameWithHttpMessagesAsync (string accountName, string path, string destination, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;&gt; RenameWithHttpMessagesAsync(string accountName, string path, string destination, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.RenameWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RenameWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;&gt;" Usage="iFileSystemOperations.RenameWithHttpMessagesAsync (accountName, path, destination, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="destination" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="b2b0d-355">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-355">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="b2b0d-356">Data Lake Store のパス (以降で '/') のファイルまたはディレクトリに移動または名前変更します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-356">The Data Lake Store path (starting with '/') of the file or directory to move/rename.</span></span>
            </param>
        <param name="destination">
            <span data-ttu-id="b2b0d-357">移動または名前変更、ファイルまたはフォルダーへのパス</span><span class="sxs-lookup"><span data-stu-id="b2b0d-357">The path to move/rename the file or folder to</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b2b0d-358">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-358">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b2b0d-359">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-359">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2b0d-360">ファイルまたはディレクトリの名前を変更します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-360">Rename a file or directory.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            <span data-ttu-id="b2b0d-361">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-361">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b2b0d-362">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-362">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b2b0d-363">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-363">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="SetAclWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; SetAclWithHttpMessagesAsync (string accountName, string path, string aclspec, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; SetAclWithHttpMessagesAsync(string accountName, string path, string aclspec, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.SetAclWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetAclWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iFileSystemOperations.SetAclWithHttpMessagesAsync (accountName, path, aclspec, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclspec" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="b2b0d-364">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-364">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="b2b0d-365">Data Lake Store のパス (以降で '/') のファイルまたはディレクトリの ACL を設定します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-365">The Data Lake Store path (starting with '/') of the file or directory on which to set the ACL.</span></span>
            </param>
        <param name="aclspec">
            <span data-ttu-id="b2b0d-366">形式で ACL を作成する操作に含まれる ACL spec ' [既定値:] ユーザー | グループ | その他の:: r |-w |-x |-'</span><span class="sxs-lookup"><span data-stu-id="b2b0d-366">The ACL spec included in ACL creation operations in the format '[default:]user|group|other::r|-w|-x|-'</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b2b0d-367">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-367">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b2b0d-368">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-368">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2b0d-369">ファイルまたはフォルダーのアクセス制御リスト (ACL) を設定します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-369">Sets the Access Control List (ACL) for a file or folder.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            <span data-ttu-id="b2b0d-370">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-370">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b2b0d-371">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-371">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="SetFileExpiryWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; SetFileExpiryWithHttpMessagesAsync (string accountName, string path, Microsoft.Azure.Management.DataLake.Store.Models.ExpiryOptionType expiryOption, Nullable&lt;long&gt; expireTime = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; SetFileExpiryWithHttpMessagesAsync(string accountName, string path, valuetype Microsoft.Azure.Management.DataLake.Store.Models.ExpiryOptionType expiryOption, valuetype System.Nullable`1&lt;int64&gt; expireTime, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.SetFileExpiryWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.DataLake.Store.Models.ExpiryOptionType,System.Nullable{System.Int64},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetFileExpiryWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.DataLake.Store.Models.ExpiryOptionType * Nullable&lt;int64&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iFileSystemOperations.SetFileExpiryWithHttpMessagesAsync (accountName, path, expiryOption, expireTime, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="expiryOption" Type="Microsoft.Azure.Management.DataLake.Store.Models.ExpiryOptionType" />
        <Parameter Name="expireTime" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="b2b0d-372">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-372">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="b2b0d-373">Data Lake Store のパス (以降で '/') を設定するか、有効期限を削除するファイルのです。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-373">The Data Lake Store path (starting with '/') of the file on which to set or remove the expiration time.</span></span>
            </param>
        <param name="expiryOption">
            <span data-ttu-id="b2b0d-374">ファイルを使用する有効期限の種類を示します。 1。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-374">Indicates the type of expiration to use for the file: 1.</span></span>
            <span data-ttu-id="b2b0d-375">NeverExpire: ExpireTime は無視されます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-375">NeverExpire: ExpireTime is ignored.</span></span> <span data-ttu-id="b2b0d-376">2.</span><span class="sxs-lookup"><span data-stu-id="b2b0d-376">2.</span></span> <span data-ttu-id="b2b0d-377">RelativeToNow: ExpireTime は、ファイルの有効期限が更新されたときに、基準に有効期限の日付を表すミリ秒の整数です。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-377">RelativeToNow: ExpireTime is an integer in milliseconds representing the expiration date relative to when file expiration is updated.</span></span> <span data-ttu-id="b2b0d-378">手順 3.</span><span class="sxs-lookup"><span data-stu-id="b2b0d-378">3.</span></span>
            <span data-ttu-id="b2b0d-379">RelativeToCreationDate: ExpireTime は、ファイルの作成の基準とした有効期限の日付を表すミリ秒の整数です。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-379">RelativeToCreationDate: ExpireTime is an integer in milliseconds representing the expiration date relative to file creation.</span></span> <span data-ttu-id="b2b0d-380">4.</span><span class="sxs-lookup"><span data-stu-id="b2b0d-380">4.</span></span>
            <span data-ttu-id="b2b0d-381">絶対値: ExpireTime 整数です (ミリ秒単位) の 1970 年 1 月 1 基準とした Unix タイムスタンプとして 00時 00分: 00 です。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-381">Absolute: ExpireTime is an integer in milliseconds, as a Unix timestamp relative to 1/1/1970 00:00:00.</span></span> <span data-ttu-id="b2b0d-382">使用可能な値が含まれます: 'NeverExpire'、'RelativeToNow'、'RelativeToCreationDate'、'Absolute'</span><span class="sxs-lookup"><span data-stu-id="b2b0d-382">Possible values include: 'NeverExpire', 'RelativeToNow', 'RelativeToCreationDate', 'Absolute'</span></span>
            </param>
        <param name="expireTime">
            <span data-ttu-id="b2b0d-383">ファイルは、有効期限が設定された ExpiryOption に対応する時間。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-383">The time that the file will expire, corresponding to the ExpiryOption that was set.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b2b0d-384">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-384">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b2b0d-385">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-385">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2b0d-386">設定または指定したファイルに有効期限を削除します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-386">Sets or removes the expiration time on the specified file.</span></span> <span data-ttu-id="b2b0d-387">この操作は、ファイルに対してのみ実行できます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-387">This operation can only be executed against files.</span></span> <span data-ttu-id="b2b0d-388">フォルダーを指定することはできません。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-388">Folders are not supported.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            <span data-ttu-id="b2b0d-389">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-389">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b2b0d-390">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-390">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="SetOwnerWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; SetOwnerWithHttpMessagesAsync (string accountName, string path, string owner = null, string group = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; SetOwnerWithHttpMessagesAsync(string accountName, string path, string owner, string group, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.SetOwnerWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetOwnerWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iFileSystemOperations.SetOwnerWithHttpMessagesAsync (accountName, path, owner, group, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="owner" Type="System.String" />
        <Parameter Name="group" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="b2b0d-391">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-391">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="b2b0d-392">Data Lake Store のパス (以降で '/') のファイルまたは所有者を設定する対象のディレクトリ。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-392">The Data Lake Store path (starting with '/') of the file or directory for which to set the owner.</span></span>
            </param>
        <param name="owner">
            <span data-ttu-id="b2b0d-393">ファイルまたはディレクトリの所有者であるユーザーの AAD のオブジェクト ID。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-393">The AAD Object ID of the user owner of the file or directory.</span></span> <span data-ttu-id="b2b0d-394">空の場合は、プロパティは変更されません。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-394">If empty, the property will remain unchanged.</span></span>
            </param>
        <param name="group">
            <span data-ttu-id="b2b0d-395">ファイルまたはディレクトリのグループの所有者の AAD のオブジェクト ID。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-395">The AAD Object ID of the group owner of the file or directory.</span></span> <span data-ttu-id="b2b0d-396">空の場合は、プロパティは変更されません。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-396">If empty, the property will remain unchanged.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b2b0d-397">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-397">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b2b0d-398">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-398">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2b0d-399">ファイルまたはディレクトリの所有者を設定します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-399">Sets the owner of a file or directory.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            <span data-ttu-id="b2b0d-400">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-400">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b2b0d-401">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-401">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="SetPermissionWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; SetPermissionWithHttpMessagesAsync (string accountName, string path, string permission = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; SetPermissionWithHttpMessagesAsync(string accountName, string path, string permission, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.SetPermissionWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetPermissionWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iFileSystemOperations.SetPermissionWithHttpMessagesAsync (accountName, path, permission, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="permission" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="b2b0d-402">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-402">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="b2b0d-403">Data Lake Store のパス (以降で '/') のファイルまたはアクセス許可を設定する対象のディレクトリ。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-403">The Data Lake Store path (starting with '/') of the file or directory for which to set the permission.</span></span>
            </param>
        <param name="permission">
            <span data-ttu-id="b2b0d-404">(つまり、アクセス許可の文字列表現</span><span class="sxs-lookup"><span data-stu-id="b2b0d-404">A string representation of the permission (i.e</span></span> <span data-ttu-id="b2b0d-405">rwx')。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-405">'rwx').</span></span> <span data-ttu-id="b2b0d-406">空の場合、このプロパティは変更されません。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-406">If empty, this property remains unchanged.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b2b0d-407">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-407">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b2b0d-408">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-408">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2b0d-409">ファイルまたはフォルダーのアクセス許可を設定します。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-409">Sets the permission of the file or folder.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            <span data-ttu-id="b2b0d-410">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-410">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b2b0d-411">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-411">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UploadFile">
      <MemberSignature Language="C#" Value="public void UploadFile (string accountName, string sourcePath, string destinationPath, int threadCount = -1, bool resume = false, bool overwrite = false, bool uploadAsBinary = false, IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferProgress&gt; progressTracker = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void UploadFile(string accountName, string sourcePath, string destinationPath, int32 threadCount, bool resume, bool overwrite, bool uploadAsBinary, class System.IProgress`1&lt;class Microsoft.Azure.Management.DataLake.Store.TransferProgress&gt; progressTracker, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.UploadFile(System.String,System.String,System.String,System.Int32,System.Boolean,System.Boolean,System.Boolean,System.IProgress{Microsoft.Azure.Management.DataLake.Store.TransferProgress},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFile : string * string * string * int * bool * bool * bool * IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferProgress&gt; * System.Threading.CancellationToken -&gt; unit" Usage="iFileSystemOperations.UploadFile (accountName, sourcePath, destinationPath, threadCount, resume, overwrite, uploadAsBinary, progressTracker, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="sourcePath" Type="System.String" />
        <Parameter Name="destinationPath" Type="System.String" />
        <Parameter Name="threadCount" Type="System.Int32" />
        <Parameter Name="resume" Type="System.Boolean" />
        <Parameter Name="overwrite" Type="System.Boolean" />
        <Parameter Name="uploadAsBinary" Type="System.Boolean" />
        <Parameter Name="progressTracker" Type="System.IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferProgress&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="b2b0d-412">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-412">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="sourcePath">
            <span data-ttu-id="b2b0d-413">Data Lake Store アカウントにアップロードするローカル ソース ファイルです。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-413">The local source file to upload to the Data Lake Store account.</span></span>
            </param>
        <param name="destinationPath">
            <span data-ttu-id="b2b0d-414">Data Lake Store のパス (以降で '/')、ディレクトリまたはディレクトリとファイル名にアップロードするのです。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-414">The Data Lake Store path (starting with '/') of the directory or directory and filename to upload to.</span></span>
            </param>
        <param name="threadCount">
            <span data-ttu-id="b2b0d-415">アップロード中に使用するスレッドの最大数。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-415">The maximum number of threads to use during the upload.</span></span> <span data-ttu-id="b2b0d-416">既定では、この番号はに基づいて計算ファイルのサイズ。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-416">By default, this number will be computed based on file size.</span></span>
            </param>
        <param name="resume">
            <span data-ttu-id="b2b0d-417">このアップロードが、障害が発生した以前のアップロードの継続タスクであることを示すスイッチです。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-417">A switch indicating if this upload is a continuation of a previous, failed upload.</span></span> <span data-ttu-id="b2b0d-418">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-418">Default is false.</span></span>
            </param>
        <param name="overwrite">
            <span data-ttu-id="b2b0d-419">このアップロードを示すスイッチは、存在する場合、ターゲット ファイルを上書きします。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-419">A switch indicating this upload should overwrite the target file if it exists.</span></span> <span data-ttu-id="b2b0d-420">既定値は false に設定し、アップロードは高速なフェールオーバー ターゲット ファイルが存在する場合。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-420">Default is false, and the upload will fast fail if the target file exists.</span></span>
            </param>
        <param name="uploadAsBinary">
            <span data-ttu-id="b2b0d-421">このアップロードを示すスイッチは、パフォーマンスは多少向上レコード境界の整合性は保証されませんがバイナリとしてファイルを扱う必要があります。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-421">A switch indicating this upload should treat the file as binary, which is slightly more performant but does not ensure record boundary integrity.</span></span>
            </param>
        <param name="progressTracker">
            <span data-ttu-id="b2b0d-422">非同期的にアップロード操作の進行状況を追跡するために使用できる省略可能なデリゲート。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-422">An optional delegate that can be used to track the progress of the upload operation asynchronously.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b2b0d-423">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-423">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2b0d-424">指定された Data Lake Store アカウントにファイルをアップロードします。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-424">Uploads a file to the specified Data Lake Store account.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            <span data-ttu-id="b2b0d-425">操作に無効なステータス コードが返されるときにスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-425">Thrown when the operation returned an invalid status code.</span></span>
            </exception>
        <exception cref="T:System.Threading.Tasks.TaskCanceledException">
            <span data-ttu-id="b2b0d-426">操作の完了に時間がかかる場合、またはユーザーが明示的にキャンセルするとスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-426">Thrown when the operation takes too long to complete or if the user explicitly cancels it.</span></span>
            </exception>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.InvalidMetadataException">
            <span data-ttu-id="b2b0d-427">再開のメタデータが壊れているか、現在の操作に関連付けられていない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-427">Thrown when resume metadata is corrupt or not associated with the current operation.</span></span>
            </exception>
        <exception cref="T:System.IO.FileNotFoundException">
            <span data-ttu-id="b2b0d-428">ソース パスが見つからない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-428">Thrown when the source path cannot be found.</span></span>
            </exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="b2b0d-429">無効なアップロードの試行または操作中に、ファイルが外部で変更された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-429">Thrown if an invalid upload is attempted or the file is modified externally during the operation.</span></span>
            </exception>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.TransferFailedException">
            <span data-ttu-id="b2b0d-430">転送操作が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-430">Thrown if the transfer operation fails.</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b2b0d-431">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-431">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b2b0d-432">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-432">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UploadFolder">
      <MemberSignature Language="C#" Value="public void UploadFolder (string accountName, string sourcePath, string destinationPath, int perFileThreadCount = -1, int concurrentFileCount = -1, bool resume = false, bool overwrite = false, bool uploadAsBinary = false, bool recurse = false, IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress&gt; progressTracker = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void UploadFolder(string accountName, string sourcePath, string destinationPath, int32 perFileThreadCount, int32 concurrentFileCount, bool resume, bool overwrite, bool uploadAsBinary, bool recurse, class System.IProgress`1&lt;class Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress&gt; progressTracker, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.UploadFolder(System.String,System.String,System.String,System.Int32,System.Int32,System.Boolean,System.Boolean,System.Boolean,System.Boolean,System.IProgress{Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFolder : string * string * string * int * int * bool * bool * bool * bool * IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress&gt; * System.Threading.CancellationToken -&gt; unit" Usage="iFileSystemOperations.UploadFolder (accountName, sourcePath, destinationPath, perFileThreadCount, concurrentFileCount, resume, overwrite, uploadAsBinary, recurse, progressTracker, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="sourcePath" Type="System.String" />
        <Parameter Name="destinationPath" Type="System.String" />
        <Parameter Name="perFileThreadCount" Type="System.Int32" />
        <Parameter Name="concurrentFileCount" Type="System.Int32" />
        <Parameter Name="resume" Type="System.Boolean" />
        <Parameter Name="overwrite" Type="System.Boolean" />
        <Parameter Name="uploadAsBinary" Type="System.Boolean" />
        <Parameter Name="recurse" Type="System.Boolean" />
        <Parameter Name="progressTracker" Type="System.IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="b2b0d-433">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-433">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="sourcePath">
            <span data-ttu-id="b2b0d-434">Data Lake Store アカウントにアップロードするローカル ソース フォルダーです。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-434">The local source folder to upload to the Data Lake Store account.</span></span>
            </param>
        <param name="destinationPath">
            <span data-ttu-id="b2b0d-435">Data Lake Store のパス (以降で '/') にアップロードするディレクトリ。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-435">The Data Lake Store path (starting with '/') of the directory to upload to.</span></span>
            </param>
        <param name="perFileThreadCount">
            <span data-ttu-id="b2b0d-436">アップロード中にファイルごとに使用するスレッドの最大数。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-436">The maximum number of threads to use per file during the upload.</span></span> <span data-ttu-id="b2b0d-437">既定では、この番号はに基づいて計算フォルダー構造と平均ファイルのサイズ。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-437">By default, this number will be computed based on folder structure and average file size.</span></span>
            </param>
        <param name="concurrentFileCount">
            <span data-ttu-id="b2b0d-438">一度にアップロードするファイルの最大数。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-438">The maximum number of files to upload at once.</span></span> <span data-ttu-id="b2b0d-439">既定では、この番号はに基づいて計算のフォルダー構造およびファイルの数。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-439">By default, this number will be computed based on folder structure and number of files.</span></span>
            </param>
        <param name="resume">
            <span data-ttu-id="b2b0d-440">このアップロードが、障害が発生した以前のアップロードの継続タスクであることを示すスイッチです。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-440">A switch indicating if this upload is a continuation of a previous, failed upload.</span></span> <span data-ttu-id="b2b0d-441">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-441">Default is false.</span></span>
            </param>
        <param name="overwrite">
            <span data-ttu-id="b2b0d-442">存在する場合、このアップロードを示すスイッチはターゲット ディレクトリの内容を上書きする必要があります。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-442">A switch indicating this upload should overwrite the contents of the target directory if it exists.</span></span> <span data-ttu-id="b2b0d-443">既定値は false に設定し、アップロードは高速なフェールオーバー ターゲットの場所が存在する場合。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-443">Default is false, and the upload will fast fail if the target location exists.</span></span>
            </param>
        <param name="uploadAsBinary">
            <span data-ttu-id="b2b0d-444">このアップロードを示すスイッチは、パフォーマンスは多少向上レコード境界の整合性は保証されませんがバイナリとしてすべてのデータを扱う必要があります。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-444">A switch indicating this upload should treat all data as binary, which is slightly more performant but does not ensure record boundary integrity.</span></span> <span data-ttu-id="b2b0d-445">これは混合のバイナリとテキスト ファイルまたはバイナリのみのディレクトリのサイズの大きいフォルダーをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-445">This is recommended for large folders of mixed binary and text files or binary only directories.</span></span> <span data-ttu-id="b2b0d-446">既定値は false</span><span class="sxs-lookup"><span data-stu-id="b2b0d-446">Default is false</span></span>
            </param>
        <param name="recurse">
            <span data-ttu-id="b2b0d-447">このアップロードを示すスイッチには、ソース ディレクトリを再帰的にまたは最上位レベルだけをアップロードする必要があります。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-447">A switch indicating this upload should upload the source directory recursively or just the top level.</span></span> <span data-ttu-id="b2b0d-448">既定値は false の場合、最上位レベルだけがアップロードされるようにします。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-448">Default is false, only the top level will be uploaded.</span></span>
            </param>
        <param name="progressTracker">
            <span data-ttu-id="b2b0d-449">非同期的にアップロード操作の進行状況を追跡するために使用できる省略可能なデリゲート。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-449">An optional delegate that can be used to track the progress of the upload operation asynchronously.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b2b0d-450">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-450">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2b0d-451">指定された Data Lake Store アカウントにフォルダーをアップロードします。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-451">Uploads a folder to the specified Data Lake Store account.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            <span data-ttu-id="b2b0d-452">操作に無効なステータス コードが返されるときにスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-452">Thrown when the operation returned an invalid status code.</span></span>
            </exception>
        <exception cref="T:System.Threading.Tasks.TaskCanceledException">
            <span data-ttu-id="b2b0d-453">操作の完了に時間がかかる場合、またはユーザーが明示的にキャンセルするとスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-453">Thrown when the operation takes too long to complete or if the user explicitly cancels it.</span></span>
            </exception>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.InvalidMetadataException">
            <span data-ttu-id="b2b0d-454">再開のメタデータが壊れているか、現在の操作に関連付けられていない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-454">Thrown when resume metadata is corrupt or not associated with the current operation.</span></span>
            </exception>
        <exception cref="T:System.IO.FileNotFoundException">
            <span data-ttu-id="b2b0d-455">ソース パスが見つからない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-455">Thrown when the source path cannot be found.</span></span>
            </exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="b2b0d-456">無効なアップロードしようとすると、またはファイル/フォルダーが操作中に外部から変更されたがスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-456">Thrown if an invalid upload is attempted or a file/folder is modified externally during the operation.</span></span>
            </exception>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.TransferFailedException">
            <span data-ttu-id="b2b0d-457">転送操作が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-457">Thrown if the transfer operation fails.</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b2b0d-458">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-458">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b2b0d-459">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2b0d-459">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>