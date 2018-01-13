<Type Name="FileSystemOperationsExtensions" FullName="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class FileSystemOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit FileSystemOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module FileSystemOperationsExtensions" />
  <TypeSignature Language="F#" Value="type FileSystemOperationsExtensions = class" />
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
            <span data-ttu-id="50109-101">FileSystemOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="50109-101">Extension methods for FileSystemOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Append">
      <MemberSignature Language="C#" Value="public static void Append (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, System.IO.Stream streamContents, Nullable&lt;long&gt; offset = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag = null, Nullable&lt;Guid&gt; leaseId = null, Nullable&lt;Guid&gt; fileSessionId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Append(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, class System.IO.Stream streamContents, valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; leaseId, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; fileSessionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.Append(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.IO.Stream,System.Nullable{System.Int64},System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag},System.Nullable{System.Guid},System.Nullable{System.Guid})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Append (operations As IFileSystemOperations, accountName As String, path As String, streamContents As Stream, Optional offset As Nullable(Of Long) = null, Optional syncFlag As Nullable(Of SyncFlag) = null, Optional leaseId As Nullable(Of Guid) = null, Optional fileSessionId As Nullable(Of Guid) = null)" />
      <MemberSignature Language="F#" Value="static member Append : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * System.IO.Stream * Nullable&lt;int64&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; * Nullable&lt;Guid&gt; * Nullable&lt;Guid&gt; -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.Append (operations, accountName, path, streamContents, offset, syncFlag, leaseId, fileSessionId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="streamContents" Type="System.IO.Stream" />
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="syncFlag" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt;" />
        <Parameter Name="leaseId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="fileSessionId" Type="System.Nullable&lt;System.Guid&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="50109-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="50109-102">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="50109-103">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="50109-103">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="50109-104">Data Lake Store のパス (以降で '/') を追加するファイルのです。</span><span class="sxs-lookup"><span data-stu-id="50109-104">The Data Lake Store path (starting with '/') of the file to which to append.</span></span>
            </param>
        <param name="streamContents">
            <span data-ttu-id="50109-105">ファイルに追加するときに含めるファイルの内容。</span><span class="sxs-lookup"><span data-stu-id="50109-105">The file contents to include when appending to the file.</span></span>
            </param>
        <param name="offset">
            <span data-ttu-id="50109-106">追加操作を開始するためのストリームの省略可能なオフセット。</span><span class="sxs-lookup"><span data-stu-id="50109-106">The optional offset in the stream to begin the append operation.</span></span> <span data-ttu-id="50109-107">既定では、ストリームの末尾に追加します。</span><span class="sxs-lookup"><span data-stu-id="50109-107">Default is to append at the end of the stream.</span></span>
            </param>
        <param name="syncFlag">
            <span data-ttu-id="50109-108">必要に応じて、同時実行の追加が完了した後の対処方法を示します。</span><span class="sxs-lookup"><span data-stu-id="50109-108">Optionally indicates what to do after completion of the concurrent append.</span></span>
            <span data-ttu-id="50109-109">データことを示しますより多くのデータは、クライアントですぐに送信される、ファイル ハンドルの開く/ロックされているままにする (を含むファイルの長さ、最終更新時刻) ファイルのメタデータは更新されません。</span><span class="sxs-lookup"><span data-stu-id="50109-109">DATA indicates that more data will be sent immediately by the client, the file handle should remain open/locked, and file metadata (including file length, last modified time) should NOT get updated.</span></span> <span data-ttu-id="50109-110">メタデータことを示しますより多くのデータは、クライアントですぐに送信される、ファイル ハンドルのままにするオープン/ロックされているファイルのメタデータが更新を取得する必要があります。</span><span class="sxs-lookup"><span data-stu-id="50109-110">METADATA indicates that more data will be sent immediately by the client, the file handle should remain open/locked, and file metadata should get updated.</span></span> <span data-ttu-id="50109-111">閉じることを示します、クライアントにデータの送信が行われますが、ファイル ハンドルが閉じられた/ロック解除、する必要がありますファイル メタデータが更新を取得する必要があります。</span><span class="sxs-lookup"><span data-stu-id="50109-111">CLOSE indicates that the client is done sending data, the file handle should be closed/unlocked, and file metadata should get updated.</span></span> <span data-ttu-id="50109-112">使用可能な値が含まれます: 'データ'、'METADATA'、'終了'</span><span class="sxs-lookup"><span data-stu-id="50109-112">Possible values include: 'DATA', 'METADATA', 'CLOSE'</span></span>
            </param>
        <param name="leaseId">
            <span data-ttu-id="50109-113">省略可能な一意の GUID ファイルごとに単一ライター セマンティクスは、そのためには同じ leaseId でファイルを追加するクライアントだけが許可されることを意味することを確認します。</span><span class="sxs-lookup"><span data-stu-id="50109-113">Optional unique GUID per file to ensure single writer semantics, meaning that only clients that append to the file with the same leaseId will be allowed to do so.</span></span>
            </param>
        <param name="fileSessionId">
            <span data-ttu-id="50109-114">1 ファイルすべてを示す省略可能な一意の GUID、同じ追加 fileSessionId は、同じクライアントと同じセッションからです。</span><span class="sxs-lookup"><span data-stu-id="50109-114">Optional unique GUID per file indicating all the appends with the same fileSessionId are from the same client and same session.</span></span> <span data-ttu-id="50109-115">SyncFlag がデータまたはメタデータの場合、パフォーマンスが向上が得られます。</span><span class="sxs-lookup"><span data-stu-id="50109-115">This will give a performance benefit when syncFlag is DATA or METADATA.</span></span>
            </param>
        <summary>
            <span data-ttu-id="50109-116">使用のシリアルを指定したファイルに追加します。</span><span class="sxs-lookup"><span data-stu-id="50109-116">Used for serial appends to the specified file.</span></span> <span data-ttu-id="50109-117">注: ターゲットは ConcurrentAppend によって追加されたデータを含めないでください。</span><span class="sxs-lookup"><span data-stu-id="50109-117">NOTE: The target must not contain data added by ConcurrentAppend.</span></span> <span data-ttu-id="50109-118">ConcurrentAppend と追加を同義です。 使用することはできません。ターゲット ファイルが変更されたこれらのいずれかを使用して追加のオプションと、ターゲット ファイルで、その他の追加オプションは使用できません。</span><span class="sxs-lookup"><span data-stu-id="50109-118">ConcurrentAppend and Append cannot be used interchangeably; once a target file has been modified using either of these append options, the other append option cannot be used on the target file.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppendAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task AppendAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, System.IO.Stream streamContents, Nullable&lt;long&gt; offset = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag = null, Nullable&lt;Guid&gt; leaseId = null, Nullable&lt;Guid&gt; fileSessionId = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task AppendAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, class System.IO.Stream streamContents, valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; leaseId, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; fileSessionId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.AppendAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.IO.Stream,System.Nullable{System.Int64},System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag},System.Nullable{System.Guid},System.Nullable{System.Guid},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member AppendAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * System.IO.Stream * Nullable&lt;int64&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; * Nullable&lt;Guid&gt; * Nullable&lt;Guid&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.AppendAsync (operations, accountName, path, streamContents, offset, syncFlag, leaseId, fileSessionId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;AppendAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="streamContents" Type="System.IO.Stream" />
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="syncFlag" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt;" />
        <Parameter Name="leaseId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="fileSessionId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="50109-119">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="50109-119">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="50109-120">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="50109-120">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="50109-121">Data Lake Store のパス (以降で '/') を追加するファイルのです。</span><span class="sxs-lookup"><span data-stu-id="50109-121">The Data Lake Store path (starting with '/') of the file to which to append.</span></span>
            </param>
        <param name="streamContents">
            <span data-ttu-id="50109-122">ファイルに追加するときに含めるファイルの内容。</span><span class="sxs-lookup"><span data-stu-id="50109-122">The file contents to include when appending to the file.</span></span>
            </param>
        <param name="offset">
            <span data-ttu-id="50109-123">追加操作を開始するためのストリームの省略可能なオフセット。</span><span class="sxs-lookup"><span data-stu-id="50109-123">The optional offset in the stream to begin the append operation.</span></span> <span data-ttu-id="50109-124">既定では、ストリームの末尾に追加します。</span><span class="sxs-lookup"><span data-stu-id="50109-124">Default is to append at the end of the stream.</span></span>
            </param>
        <param name="syncFlag">
            <span data-ttu-id="50109-125">必要に応じて、同時実行の追加が完了した後の対処方法を示します。</span><span class="sxs-lookup"><span data-stu-id="50109-125">Optionally indicates what to do after completion of the concurrent append.</span></span>
            <span data-ttu-id="50109-126">データことを示しますより多くのデータは、クライアントですぐに送信される、ファイル ハンドルの開く/ロックされているままにする (を含むファイルの長さ、最終更新時刻) ファイルのメタデータは更新されません。</span><span class="sxs-lookup"><span data-stu-id="50109-126">DATA indicates that more data will be sent immediately by the client, the file handle should remain open/locked, and file metadata (including file length, last modified time) should NOT get updated.</span></span> <span data-ttu-id="50109-127">メタデータことを示しますより多くのデータは、クライアントですぐに送信される、ファイル ハンドルのままにするオープン/ロックされているファイルのメタデータが更新を取得する必要があります。</span><span class="sxs-lookup"><span data-stu-id="50109-127">METADATA indicates that more data will be sent immediately by the client, the file handle should remain open/locked, and file metadata should get updated.</span></span> <span data-ttu-id="50109-128">閉じることを示します、クライアントにデータの送信が行われますが、ファイル ハンドルが閉じられた/ロック解除、する必要がありますファイル メタデータが更新を取得する必要があります。</span><span class="sxs-lookup"><span data-stu-id="50109-128">CLOSE indicates that the client is done sending data, the file handle should be closed/unlocked, and file metadata should get updated.</span></span> <span data-ttu-id="50109-129">使用可能な値が含まれます: 'データ'、'METADATA'、'終了'</span><span class="sxs-lookup"><span data-stu-id="50109-129">Possible values include: 'DATA', 'METADATA', 'CLOSE'</span></span>
            </param>
        <param name="leaseId">
            <span data-ttu-id="50109-130">省略可能な一意の GUID ファイルごとに単一ライター セマンティクスは、そのためには同じ leaseId でファイルを追加するクライアントだけが許可されることを意味することを確認します。</span><span class="sxs-lookup"><span data-stu-id="50109-130">Optional unique GUID per file to ensure single writer semantics, meaning that only clients that append to the file with the same leaseId will be allowed to do so.</span></span>
            </param>
        <param name="fileSessionId">
            <span data-ttu-id="50109-131">1 ファイルすべてを示す省略可能な一意の GUID、同じ追加 fileSessionId は、同じクライアントと同じセッションからです。</span><span class="sxs-lookup"><span data-stu-id="50109-131">Optional unique GUID per file indicating all the appends with the same fileSessionId are from the same client and same session.</span></span> <span data-ttu-id="50109-132">SyncFlag がデータまたはメタデータの場合、パフォーマンスが向上が得られます。</span><span class="sxs-lookup"><span data-stu-id="50109-132">This will give a performance benefit when syncFlag is DATA or METADATA.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="50109-133">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="50109-133">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="50109-134">使用のシリアルを指定したファイルに追加します。</span><span class="sxs-lookup"><span data-stu-id="50109-134">Used for serial appends to the specified file.</span></span> <span data-ttu-id="50109-135">注: ターゲットは ConcurrentAppend によって追加されたデータを含めないでください。</span><span class="sxs-lookup"><span data-stu-id="50109-135">NOTE: The target must not contain data added by ConcurrentAppend.</span></span> <span data-ttu-id="50109-136">ConcurrentAppend と追加を同義です。 使用することはできません。ターゲット ファイルが変更されたこれらのいずれかを使用して追加のオプションと、ターゲット ファイルで、その他の追加オプションは使用できません。</span><span class="sxs-lookup"><span data-stu-id="50109-136">ConcurrentAppend and Append cannot be used interchangeably; once a target file has been modified using either of these append options, the other append option cannot be used on the target file.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckAccess">
      <MemberSignature Language="C#" Value="public static void CheckAccess (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string fsaction);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void CheckAccess(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string fsaction) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.CheckAccess(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub CheckAccess (operations As IFileSystemOperations, accountName As String, path As String, fsaction As String)" />
      <MemberSignature Language="F#" Value="static member CheckAccess : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.CheckAccess (operations, accountName, path, fsaction)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="fsaction" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="50109-137">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="50109-137">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="50109-138">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="50109-138">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="50109-139">Data Lake Store のパス (以降で '/') のファイルまたはディレクトリのアクセスをチェックします。</span><span class="sxs-lookup"><span data-stu-id="50109-139">The Data Lake Store path (starting with '/') of the file or directory for which to check access.</span></span>
            </param>
        <param name="fsaction">
            <span data-ttu-id="50109-140">正規表現パターンに一致する文字列形式でのシステム操作読み取り/書き込み/実行のファイル ' [rwx-] \ {3\}'</span><span class="sxs-lookup"><span data-stu-id="50109-140">File system operation read/write/execute in string form, matching regex pattern '[rwx-]{3}'</span></span>
            </param>
        <summary>
            <span data-ttu-id="50109-141">かどうか、指定のアクセスは、指定されたパスを確認します。</span><span class="sxs-lookup"><span data-stu-id="50109-141">Checks if the specified access is available at the given path.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckAccessAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CheckAccessAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string fsaction, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CheckAccessAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string fsaction, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.CheckAccessAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckAccessAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.CheckAccessAsync (operations, accountName, path, fsaction, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;CheckAccessAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="fsaction" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="50109-142">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="50109-142">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="50109-143">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="50109-143">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="50109-144">Data Lake Store のパス (以降で '/') のファイルまたはディレクトリのアクセスをチェックします。</span><span class="sxs-lookup"><span data-stu-id="50109-144">The Data Lake Store path (starting with '/') of the file or directory for which to check access.</span></span>
            </param>
        <param name="fsaction">
            <span data-ttu-id="50109-145">正規表現パターンに一致する文字列形式でのシステム操作読み取り/書き込み/実行のファイル ' [rwx-] \ {3\}'</span><span class="sxs-lookup"><span data-stu-id="50109-145">File system operation read/write/execute in string form, matching regex pattern '[rwx-]{3}'</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="50109-146">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="50109-146">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="50109-147">かどうか、指定のアクセスは、指定されたパスを確認します。</span><span class="sxs-lookup"><span data-stu-id="50109-147">Checks if the specified access is available at the given path.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Concat">
      <MemberSignature Language="C#" Value="public static void Concat (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, System.Collections.Generic.IList&lt;string&gt; sources);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Concat(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, class System.Collections.Generic.IList`1&lt;string&gt; sources) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.Concat(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Concat (operations As IFileSystemOperations, accountName As String, path As String, sources As IList(Of String))" />
      <MemberSignature Language="F#" Value="static member Concat : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * System.Collections.Generic.IList&lt;string&gt; -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.Concat (operations, accountName, path, sources)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="sources" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="50109-148">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="50109-148">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="50109-149">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="50109-149">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="50109-150">Data Lake Store のパス (以降で '/') の連結の結果として得られる出力先ファイルです。</span><span class="sxs-lookup"><span data-stu-id="50109-150">The Data Lake Store path (starting with '/') of the destination file resulting from the concatenation.</span></span>
            </param>
        <param name="sources">
            <span data-ttu-id="50109-151">一連のコンマ区切りの Data Lake Store パス (以降で '/') を連結する順序で連結するファイルのです。</span><span class="sxs-lookup"><span data-stu-id="50109-151">A list of comma separated Data Lake Store paths (starting with '/') of the files to concatenate, in the order in which they should be concatenated.</span></span>
            </param>
        <summary>
            <span data-ttu-id="50109-152">出力先ファイル、成功時にすべてのソース ファイルを削除するのには、ソース ファイルのリストを連結します。</span><span class="sxs-lookup"><span data-stu-id="50109-152">Concatenates the list of source files into the destination file, removing all source files upon success.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConcatAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ConcatAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, System.Collections.Generic.IList&lt;string&gt; sources, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ConcatAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, class System.Collections.Generic.IList`1&lt;string&gt; sources, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.ConcatAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Collections.Generic.IList{System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ConcatAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * System.Collections.Generic.IList&lt;string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.ConcatAsync (operations, accountName, path, sources, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;ConcatAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="sources" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="50109-153">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="50109-153">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="50109-154">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="50109-154">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="50109-155">Data Lake Store のパス (以降で '/') の連結の結果として得られる出力先ファイルです。</span><span class="sxs-lookup"><span data-stu-id="50109-155">The Data Lake Store path (starting with '/') of the destination file resulting from the concatenation.</span></span>
            </param>
        <param name="sources">
            <span data-ttu-id="50109-156">一連のコンマ区切りの Data Lake Store パス (以降で '/') を連結する順序で連結するファイルのです。</span><span class="sxs-lookup"><span data-stu-id="50109-156">A list of comma separated Data Lake Store paths (starting with '/') of the files to concatenate, in the order in which they should be concatenated.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="50109-157">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="50109-157">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="50109-158">出力先ファイル、成功時にすべてのソース ファイルを削除するのには、ソース ファイルのリストを連結します。</span><span class="sxs-lookup"><span data-stu-id="50109-158">Concatenates the list of source files into the destination file, removing all source files upon success.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConcurrentAppend">
      <MemberSignature Language="C#" Value="public static void ConcurrentAppend (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, System.IO.Stream streamContents, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.AppendModeType&gt; appendMode = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ConcurrentAppend(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, class System.IO.Stream streamContents, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.AppendModeType&gt; appendMode, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.ConcurrentAppend(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.IO.Stream,System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.AppendModeType},System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub ConcurrentAppend (operations As IFileSystemOperations, accountName As String, path As String, streamContents As Stream, Optional appendMode As Nullable(Of AppendModeType) = null, Optional syncFlag As Nullable(Of SyncFlag) = null)" />
      <MemberSignature Language="F#" Value="static member ConcurrentAppend : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * System.IO.Stream * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.AppendModeType&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.ConcurrentAppend (operations, accountName, path, streamContents, appendMode, syncFlag)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="streamContents" Type="System.IO.Stream" />
        <Parameter Name="appendMode" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.AppendModeType&gt;" />
        <Parameter Name="syncFlag" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="50109-159">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="50109-159">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="50109-160">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="50109-160">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="50109-161">Data Lake Store のパス (以降で '/') の同時実行を使用して、追加する追加ファイルです。</span><span class="sxs-lookup"><span data-stu-id="50109-161">The Data Lake Store path (starting with '/') of the file to which to append using concurrent append.</span></span>
            </param>
        <param name="streamContents">
            <span data-ttu-id="50109-162">ファイルに追加するときに含めるファイルの内容。</span><span class="sxs-lookup"><span data-stu-id="50109-162">The file contents to include when appending to the file.</span></span>
            </param>
        <param name="appendMode">
            <span data-ttu-id="50109-163">その存在または追加の既存のファイルを開くだけしていない場合、同時実行の追加の呼び出しはファイルを作成する必要がありますを示します。</span><span class="sxs-lookup"><span data-stu-id="50109-163">Indicates the concurrent append call should create the file if it doesn't exist or just open the existing file for append.</span></span> <span data-ttu-id="50109-164">使用可能な値が含まれます '自動 ' の作成。</span><span class="sxs-lookup"><span data-stu-id="50109-164">Possible values include: 'autocreate'</span></span>
            </param>
        <param name="syncFlag">
            <span data-ttu-id="50109-165">必要に応じて、同時実行の追加が完了した後の対処方法を示します。</span><span class="sxs-lookup"><span data-stu-id="50109-165">Optionally indicates what to do after completion of the concurrent append.</span></span>
            <span data-ttu-id="50109-166">データことを示しますより多くのデータは、クライアントですぐに送信される、ファイル ハンドルの開く/ロックされているままにする (を含むファイルの長さ、最終更新時刻) ファイルのメタデータは更新されません。</span><span class="sxs-lookup"><span data-stu-id="50109-166">DATA indicates that more data will be sent immediately by the client, the file handle should remain open/locked, and file metadata (including file length, last modified time) should NOT get updated.</span></span> <span data-ttu-id="50109-167">メタデータことを示しますより多くのデータは、クライアントですぐに送信される、ファイル ハンドルのままにするオープン/ロックされているファイルのメタデータが更新を取得する必要があります。</span><span class="sxs-lookup"><span data-stu-id="50109-167">METADATA indicates that more data will be sent immediately by the client, the file handle should remain open/locked, and file metadata should get updated.</span></span> <span data-ttu-id="50109-168">閉じることを示します、クライアントにデータの送信が行われますが、ファイル ハンドルが閉じられた/ロック解除、する必要がありますファイル メタデータが更新を取得する必要があります。</span><span class="sxs-lookup"><span data-stu-id="50109-168">CLOSE indicates that the client is done sending data, the file handle should be closed/unlocked, and file metadata should get updated.</span></span> <span data-ttu-id="50109-169">使用可能な値が含まれます: 'データ'、'METADATA'、'終了'</span><span class="sxs-lookup"><span data-stu-id="50109-169">Possible values include: 'DATA', 'METADATA', 'CLOSE'</span></span>
            </param>
        <summary>
            <span data-ttu-id="50109-170">必要に応じて、指定されたファイルに追加されますがまだ存在しない場合、まずファイルを作成します。</span><span class="sxs-lookup"><span data-stu-id="50109-170">Appends to the specified file, optionally first creating the file if it does not yet exist.</span></span> <span data-ttu-id="50109-171">このメソッドは、ファイルに複数の同時追加をサポートします。</span><span class="sxs-lookup"><span data-stu-id="50109-171">This method supports multiple concurrent appends to the file.</span></span> <span data-ttu-id="50109-172">注: ターゲットは作成または通常の (シリアル) Append によって追加されたデータを含めないでください。</span><span class="sxs-lookup"><span data-stu-id="50109-172">NOTE: The target must not contain data added by Create or normal (serial) Append.</span></span> <span data-ttu-id="50109-173">ConcurrentAppend と追加を同義です。 使用することはできません。ターゲット ファイルが変更されたこれらのいずれかを使用して追加のオプションと、ターゲット ファイルで、その他の追加オプションは使用できません。</span><span class="sxs-lookup"><span data-stu-id="50109-173">ConcurrentAppend and Append cannot be used interchangeably; once a target file has been modified using either of these append options, the other append option cannot be used on the target file.</span></span>
            <span data-ttu-id="50109-174">ConcurrentAppend 順序は保証されませんし、ランディング ターゲット ファイルのデータの重複が発生することができます。</span><span class="sxs-lookup"><span data-stu-id="50109-174">ConcurrentAppend does not guarantee order and can result in duplicated data landing in the target file.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConcurrentAppendAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ConcurrentAppendAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, System.IO.Stream streamContents, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.AppendModeType&gt; appendMode = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ConcurrentAppendAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, class System.IO.Stream streamContents, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.AppendModeType&gt; appendMode, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.ConcurrentAppendAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.IO.Stream,System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.AppendModeType},System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ConcurrentAppendAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * System.IO.Stream * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.AppendModeType&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.ConcurrentAppendAsync (operations, accountName, path, streamContents, appendMode, syncFlag, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;ConcurrentAppendAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="streamContents" Type="System.IO.Stream" />
        <Parameter Name="appendMode" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.AppendModeType&gt;" />
        <Parameter Name="syncFlag" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="50109-175">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="50109-175">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="50109-176">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="50109-176">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="50109-177">Data Lake Store のパス (以降で '/') の同時実行を使用して、追加する追加ファイルです。</span><span class="sxs-lookup"><span data-stu-id="50109-177">The Data Lake Store path (starting with '/') of the file to which to append using concurrent append.</span></span>
            </param>
        <param name="streamContents">
            <span data-ttu-id="50109-178">ファイルに追加するときに含めるファイルの内容。</span><span class="sxs-lookup"><span data-stu-id="50109-178">The file contents to include when appending to the file.</span></span>
            </param>
        <param name="appendMode">
            <span data-ttu-id="50109-179">その存在または追加の既存のファイルを開くだけしていない場合、同時実行の追加の呼び出しはファイルを作成する必要がありますを示します。</span><span class="sxs-lookup"><span data-stu-id="50109-179">Indicates the concurrent append call should create the file if it doesn't exist or just open the existing file for append.</span></span> <span data-ttu-id="50109-180">使用可能な値が含まれます '自動 ' の作成。</span><span class="sxs-lookup"><span data-stu-id="50109-180">Possible values include: 'autocreate'</span></span>
            </param>
        <param name="syncFlag">
            <span data-ttu-id="50109-181">必要に応じて、同時実行の追加が完了した後の対処方法を示します。</span><span class="sxs-lookup"><span data-stu-id="50109-181">Optionally indicates what to do after completion of the concurrent append.</span></span>
            <span data-ttu-id="50109-182">データことを示しますより多くのデータは、クライアントですぐに送信される、ファイル ハンドルの開く/ロックされているままにする (を含むファイルの長さ、最終更新時刻) ファイルのメタデータは更新されません。</span><span class="sxs-lookup"><span data-stu-id="50109-182">DATA indicates that more data will be sent immediately by the client, the file handle should remain open/locked, and file metadata (including file length, last modified time) should NOT get updated.</span></span> <span data-ttu-id="50109-183">メタデータことを示しますより多くのデータは、クライアントですぐに送信される、ファイル ハンドルのままにするオープン/ロックされているファイルのメタデータが更新を取得する必要があります。</span><span class="sxs-lookup"><span data-stu-id="50109-183">METADATA indicates that more data will be sent immediately by the client, the file handle should remain open/locked, and file metadata should get updated.</span></span> <span data-ttu-id="50109-184">閉じることを示します、クライアントにデータの送信が行われますが、ファイル ハンドルが閉じられた/ロック解除、する必要がありますファイル メタデータが更新を取得する必要があります。</span><span class="sxs-lookup"><span data-stu-id="50109-184">CLOSE indicates that the client is done sending data, the file handle should be closed/unlocked, and file metadata should get updated.</span></span> <span data-ttu-id="50109-185">使用可能な値が含まれます: 'データ'、'METADATA'、'終了'</span><span class="sxs-lookup"><span data-stu-id="50109-185">Possible values include: 'DATA', 'METADATA', 'CLOSE'</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="50109-186">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="50109-186">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="50109-187">必要に応じて、指定されたファイルに追加されますがまだ存在しない場合、まずファイルを作成します。</span><span class="sxs-lookup"><span data-stu-id="50109-187">Appends to the specified file, optionally first creating the file if it does not yet exist.</span></span> <span data-ttu-id="50109-188">このメソッドは、ファイルに複数の同時追加をサポートします。</span><span class="sxs-lookup"><span data-stu-id="50109-188">This method supports multiple concurrent appends to the file.</span></span> <span data-ttu-id="50109-189">注: ターゲットは作成または通常の (シリアル) Append によって追加されたデータを含めないでください。</span><span class="sxs-lookup"><span data-stu-id="50109-189">NOTE: The target must not contain data added by Create or normal (serial) Append.</span></span> <span data-ttu-id="50109-190">ConcurrentAppend と追加を同義です。 使用することはできません。ターゲット ファイルが変更されたこれらのいずれかを使用して追加のオプションと、ターゲット ファイルで、その他の追加オプションは使用できません。</span><span class="sxs-lookup"><span data-stu-id="50109-190">ConcurrentAppend and Append cannot be used interchangeably; once a target file has been modified using either of these append options, the other append option cannot be used on the target file.</span></span>
            <span data-ttu-id="50109-191">ConcurrentAppend 順序は保証されませんし、ランディング ターゲット ファイルのデータの重複が発生することができます。</span><span class="sxs-lookup"><span data-stu-id="50109-191">ConcurrentAppend does not guarantee order and can result in duplicated data landing in the target file.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static void Create (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, System.IO.Stream streamContents = null, Nullable&lt;bool&gt; overwrite = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag = null, Nullable&lt;Guid&gt; leaseId = null, Nullable&lt;int&gt; permission = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Create(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, class System.IO.Stream streamContents, valuetype System.Nullable`1&lt;bool&gt; overwrite, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; leaseId, valuetype System.Nullable`1&lt;int32&gt; permission) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.Create(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.IO.Stream,System.Nullable{System.Boolean},System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag},System.Nullable{System.Guid},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Create (operations As IFileSystemOperations, accountName As String, path As String, Optional streamContents As Stream = null, Optional overwrite As Nullable(Of Boolean) = null, Optional syncFlag As Nullable(Of SyncFlag) = null, Optional leaseId As Nullable(Of Guid) = null, Optional permission As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * System.IO.Stream * Nullable&lt;bool&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; * Nullable&lt;Guid&gt; * Nullable&lt;int&gt; -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.Create (operations, accountName, path, streamContents, overwrite, syncFlag, leaseId, permission)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="streamContents" Type="System.IO.Stream" />
        <Parameter Name="overwrite" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="syncFlag" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt;" />
        <Parameter Name="leaseId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="permission" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="50109-192">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="50109-192">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="50109-193">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="50109-193">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="50109-194">Data Lake Store のパス (以降で '/') のファイルを作成します。</span><span class="sxs-lookup"><span data-stu-id="50109-194">The Data Lake Store path (starting with '/') of the file to create.</span></span>
            </param>
        <param name="streamContents">
            <span data-ttu-id="50109-195">ファイルを作成するときに含めるファイルの内容。</span><span class="sxs-lookup"><span data-stu-id="50109-195">The file contents to include when creating the file.</span></span> <span data-ttu-id="50109-196">このパラメーターは省略可能な指定されていない場合、空のファイルに結果として得られます。</span><span class="sxs-lookup"><span data-stu-id="50109-196">This parameter is optional, resulting in an empty file if not specified.</span></span>
            </param>
        <param name="overwrite">
            <span data-ttu-id="50109-197">場合を示す値、ファイルは上書きする必要があります。</span><span class="sxs-lookup"><span data-stu-id="50109-197">The indication of if the file should be overwritten.</span></span>
            </param>
        <param name="syncFlag">
            <span data-ttu-id="50109-198">必要に応じて作成の完了後に行う作業を示します。</span><span class="sxs-lookup"><span data-stu-id="50109-198">Optionally indicates what to do after completion of the create.</span></span> <span data-ttu-id="50109-199">データことを示しますより多くのデータは、クライアントですぐに送信される、ファイル ハンドルの開く/ロックされているままにする (を含むファイルの長さ、最終更新時刻) ファイルのメタデータは更新されません。</span><span class="sxs-lookup"><span data-stu-id="50109-199">DATA indicates that more data will be sent immediately by the client, the file handle should remain open/locked, and file metadata (including file length, last modified time) should NOT get updated.</span></span> <span data-ttu-id="50109-200">メタデータことを示しますより多くのデータは、クライアントですぐに送信される、ファイル ハンドルのままにするオープン/ロックされているファイルのメタデータが更新を取得する必要があります。</span><span class="sxs-lookup"><span data-stu-id="50109-200">METADATA indicates that more data will be sent immediately by the client, the file handle should remain open/locked, and file metadata should get updated.</span></span> <span data-ttu-id="50109-201">閉じることを示します、クライアントにデータの送信が行われますが、ファイル ハンドルが閉じられた/ロック解除、する必要がありますファイル メタデータが更新を取得する必要があります。</span><span class="sxs-lookup"><span data-stu-id="50109-201">CLOSE indicates that the client is done sending data, the file handle should be closed/unlocked, and file metadata should get updated.</span></span> <span data-ttu-id="50109-202">使用可能な値が含まれます: 'データ'、'METADATA'、'終了'</span><span class="sxs-lookup"><span data-stu-id="50109-202">Possible values include: 'DATA', 'METADATA', 'CLOSE'</span></span>
            </param>
        <param name="leaseId">
            <span data-ttu-id="50109-203">省略可能な一意の GUID ファイルごとに単一ライター セマンティクスは、そのためには同じ leaseId でファイルを追加するクライアントだけが許可されることを意味することを確認します。</span><span class="sxs-lookup"><span data-stu-id="50109-203">Optional unique GUID per file to ensure single writer semantics, meaning that only clients that append to the file with the same leaseId will be allowed to do so.</span></span>
            </param>
        <param name="permission">
            <span data-ttu-id="50109-204">名前のないユーザー、マスクおよびファイルの作成時に設定される他のアクセス許可の 8 進数表現です。</span><span class="sxs-lookup"><span data-stu-id="50109-204">The octal representation of the unnamed user, mask and other permissions that should be set for the file when created.</span></span> <span data-ttu-id="50109-205">指定しない場合、これらのコンテナーから継承します。</span><span class="sxs-lookup"><span data-stu-id="50109-205">If not specified, it inherits these from the container.</span></span>
            </param>
        <summary>
            <span data-ttu-id="50109-206">必要に応じて指定された内容でファイルを作成します。</span><span class="sxs-lookup"><span data-stu-id="50109-206">Creates a file with optionally specified content.</span></span> <span data-ttu-id="50109-207">注: コンテンツを指定する場合、結果として得られるファイルは変更できません ConcurrentAppend を使用します。</span><span class="sxs-lookup"><span data-stu-id="50109-207">NOTE: If content is provided, the resulting file cannot be modified using ConcurrentAppend.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CreateAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, System.IO.Stream streamContents = null, Nullable&lt;bool&gt; overwrite = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag = null, Nullable&lt;Guid&gt; leaseId = null, Nullable&lt;int&gt; permission = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CreateAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, class System.IO.Stream streamContents, valuetype System.Nullable`1&lt;bool&gt; overwrite, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; leaseId, valuetype System.Nullable`1&lt;int32&gt; permission, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.CreateAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.IO.Stream,System.Nullable{System.Boolean},System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag},System.Nullable{System.Guid},System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * System.IO.Stream * Nullable&lt;bool&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; * Nullable&lt;Guid&gt; * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.CreateAsync (operations, accountName, path, streamContents, overwrite, syncFlag, leaseId, permission, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;CreateAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="streamContents" Type="System.IO.Stream" />
        <Parameter Name="overwrite" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="syncFlag" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt;" />
        <Parameter Name="leaseId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="permission" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="50109-208">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="50109-208">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="50109-209">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="50109-209">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="50109-210">Data Lake Store のパス (以降で '/') のファイルを作成します。</span><span class="sxs-lookup"><span data-stu-id="50109-210">The Data Lake Store path (starting with '/') of the file to create.</span></span>
            </param>
        <param name="streamContents">
            <span data-ttu-id="50109-211">ファイルを作成するときに含めるファイルの内容。</span><span class="sxs-lookup"><span data-stu-id="50109-211">The file contents to include when creating the file.</span></span> <span data-ttu-id="50109-212">このパラメーターは省略可能な指定されていない場合、空のファイルに結果として得られます。</span><span class="sxs-lookup"><span data-stu-id="50109-212">This parameter is optional, resulting in an empty file if not specified.</span></span>
            </param>
        <param name="overwrite">
            <span data-ttu-id="50109-213">場合を示す値、ファイルは上書きする必要があります。</span><span class="sxs-lookup"><span data-stu-id="50109-213">The indication of if the file should be overwritten.</span></span>
            </param>
        <param name="syncFlag">
            <span data-ttu-id="50109-214">必要に応じて作成の完了後に行う作業を示します。</span><span class="sxs-lookup"><span data-stu-id="50109-214">Optionally indicates what to do after completion of the create.</span></span> <span data-ttu-id="50109-215">データことを示しますより多くのデータは、クライアントですぐに送信される、ファイル ハンドルの開く/ロックされているままにする (を含むファイルの長さ、最終更新時刻) ファイルのメタデータは更新されません。</span><span class="sxs-lookup"><span data-stu-id="50109-215">DATA indicates that more data will be sent immediately by the client, the file handle should remain open/locked, and file metadata (including file length, last modified time) should NOT get updated.</span></span> <span data-ttu-id="50109-216">メタデータことを示しますより多くのデータは、クライアントですぐに送信される、ファイル ハンドルのままにするオープン/ロックされているファイルのメタデータが更新を取得する必要があります。</span><span class="sxs-lookup"><span data-stu-id="50109-216">METADATA indicates that more data will be sent immediately by the client, the file handle should remain open/locked, and file metadata should get updated.</span></span> <span data-ttu-id="50109-217">閉じることを示します、クライアントにデータの送信が行われますが、ファイル ハンドルが閉じられた/ロック解除、する必要がありますファイル メタデータが更新を取得する必要があります。</span><span class="sxs-lookup"><span data-stu-id="50109-217">CLOSE indicates that the client is done sending data, the file handle should be closed/unlocked, and file metadata should get updated.</span></span> <span data-ttu-id="50109-218">使用可能な値が含まれます: 'データ'、'METADATA'、'終了'</span><span class="sxs-lookup"><span data-stu-id="50109-218">Possible values include: 'DATA', 'METADATA', 'CLOSE'</span></span>
            </param>
        <param name="leaseId">
            <span data-ttu-id="50109-219">省略可能な一意の GUID ファイルごとに単一ライター セマンティクスは、そのためには同じ leaseId でファイルを追加するクライアントだけが許可されることを意味することを確認します。</span><span class="sxs-lookup"><span data-stu-id="50109-219">Optional unique GUID per file to ensure single writer semantics, meaning that only clients that append to the file with the same leaseId will be allowed to do so.</span></span>
            </param>
        <param name="permission">
            <span data-ttu-id="50109-220">名前のないユーザー、マスクおよびファイルの作成時に設定される他のアクセス許可の 8 進数表現です。</span><span class="sxs-lookup"><span data-stu-id="50109-220">The octal representation of the unnamed user, mask and other permissions that should be set for the file when created.</span></span> <span data-ttu-id="50109-221">指定しない場合、これらのコンテナーから継承します。</span><span class="sxs-lookup"><span data-stu-id="50109-221">If not specified, it inherits these from the container.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="50109-222">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="50109-222">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="50109-223">必要に応じて指定された内容でファイルを作成します。</span><span class="sxs-lookup"><span data-stu-id="50109-223">Creates a file with optionally specified content.</span></span> <span data-ttu-id="50109-224">注: コンテンツを指定する場合、結果として得られるファイルは変更できません ConcurrentAppend を使用します。</span><span class="sxs-lookup"><span data-stu-id="50109-224">NOTE: If content is provided, the resulting file cannot be modified using ConcurrentAppend.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult Delete (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, Nullable&lt;bool&gt; recursive = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult Delete(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, valuetype System.Nullable`1&lt;bool&gt; recursive) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.Delete(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IFileSystemOperations, accountName As String, path As String, Optional recursive As Nullable(Of Boolean) = null) As FileOperationResult" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.Delete (operations, accountName, path, recursive)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="50109-225">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="50109-225">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="50109-226">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="50109-226">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="50109-227">Data Lake Store のパス (以降で '/') のファイルまたはディレクトリを削除します。</span><span class="sxs-lookup"><span data-stu-id="50109-227">The Data Lake Store path (starting with '/') of the file or directory to delete.</span></span>
            </param>
        <param name="recursive">
            <span data-ttu-id="50109-228">削除が再帰的になるかどうかを示す、省略可能なスイッチ</span><span class="sxs-lookup"><span data-stu-id="50109-228">The optional switch indicating if the delete should be recursive</span></span>
            </param>
        <summary>
            <span data-ttu-id="50109-229">要求されたファイルまたはディレクトリ、必要に応じて再帰的に削除します。</span><span class="sxs-lookup"><span data-stu-id="50109-229">Deletes the requested file or directory, optionally recursively.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt; DeleteAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, Nullable&lt;bool&gt; recursive = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt; DeleteAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, valuetype System.Nullable`1&lt;bool&gt; recursive, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.DeleteAsync (operations, accountName, path, recursive, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;DeleteAsync&gt;d__39))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="50109-230">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="50109-230">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="50109-231">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="50109-231">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="50109-232">Data Lake Store のパス (以降で '/') のファイルまたはディレクトリを削除します。</span><span class="sxs-lookup"><span data-stu-id="50109-232">The Data Lake Store path (starting with '/') of the file or directory to delete.</span></span>
            </param>
        <param name="recursive">
            <span data-ttu-id="50109-233">削除が再帰的になるかどうかを示す、省略可能なスイッチ</span><span class="sxs-lookup"><span data-stu-id="50109-233">The optional switch indicating if the delete should be recursive</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="50109-234">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="50109-234">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="50109-235">要求されたファイルまたはディレクトリ、必要に応じて再帰的に削除します。</span><span class="sxs-lookup"><span data-stu-id="50109-235">Deletes the requested file or directory, optionally recursively.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAclStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Store.Models.AclStatusResult GetAclStatus (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, Nullable&lt;bool&gt; tooId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Store.Models.AclStatusResult GetAclStatus(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, valuetype System.Nullable`1&lt;bool&gt; tooId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.GetAclStatus(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAclStatus (operations As IFileSystemOperations, accountName As String, path As String, Optional tooId As Nullable(Of Boolean) = null) As AclStatusResult" />
      <MemberSignature Language="F#" Value="static member GetAclStatus : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.DataLake.Store.Models.AclStatusResult" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.GetAclStatus (operations, accountName, path, tooId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.AclStatusResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="tooId" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="50109-236">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="50109-236">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="50109-237">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="50109-237">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="50109-238">Data Lake Store のパス (以降で '/') のファイルまたはディレクトリの ACL を取得します。</span><span class="sxs-lookup"><span data-stu-id="50109-238">The Data Lake Store path (starting with '/') of the file or directory for which to get the ACL.</span></span>
            </param>
        <param name="tooId">
            <span data-ttu-id="50109-239">ACL エントリのオブジェクト ID の代わりにわかりやすい名前を返す省略可能なスイッチです。</span><span class="sxs-lookup"><span data-stu-id="50109-239">An optional switch to return friendly names in place of object ID for ACL entries.</span></span> <span data-ttu-id="50109-240">tooid AAD のオブジェクト ID ではなく、false を返しますフレンドリ名を =。</span><span class="sxs-lookup"><span data-stu-id="50109-240">tooid=false returns friendly names instead of the AAD Object ID.</span></span>
            <span data-ttu-id="50109-241">既定値は true の場合、AAD のオブジェクト Id を取得します。</span><span class="sxs-lookup"><span data-stu-id="50109-241">Default value is true, returning AAD object IDs.</span></span>
            </param>
        <summary>
            <span data-ttu-id="50109-242">指定したファイルまたはディレクトリのアクセス制御リスト (ACL) エントリを取得します。</span><span class="sxs-lookup"><span data-stu-id="50109-242">Gets Access Control List (ACL) entries for the specified file or directory.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAclStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.AclStatusResult&gt; GetAclStatusAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, Nullable&lt;bool&gt; tooId = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.AclStatusResult&gt; GetAclStatusAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, valuetype System.Nullable`1&lt;bool&gt; tooId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.GetAclStatusAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAclStatusAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.AclStatusResult&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.GetAclStatusAsync (operations, accountName, path, tooId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;GetAclStatusAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.AclStatusResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="tooId" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="50109-243">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="50109-243">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="50109-244">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="50109-244">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="50109-245">Data Lake Store のパス (以降で '/') のファイルまたはディレクトリの ACL を取得します。</span><span class="sxs-lookup"><span data-stu-id="50109-245">The Data Lake Store path (starting with '/') of the file or directory for which to get the ACL.</span></span>
            </param>
        <param name="tooId">
            <span data-ttu-id="50109-246">ACL エントリのオブジェクト ID の代わりにわかりやすい名前を返す省略可能なスイッチです。</span><span class="sxs-lookup"><span data-stu-id="50109-246">An optional switch to return friendly names in place of object ID for ACL entries.</span></span> <span data-ttu-id="50109-247">tooid AAD のオブジェクト ID ではなく、false を返しますフレンドリ名を =。</span><span class="sxs-lookup"><span data-stu-id="50109-247">tooid=false returns friendly names instead of the AAD Object ID.</span></span>
            <span data-ttu-id="50109-248">既定値は true の場合、AAD のオブジェクト Id を取得します。</span><span class="sxs-lookup"><span data-stu-id="50109-248">Default value is true, returning AAD object IDs.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="50109-249">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="50109-249">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="50109-250">指定したファイルまたはディレクトリのアクセス制御リスト (ACL) エントリを取得します。</span><span class="sxs-lookup"><span data-stu-id="50109-250">Gets Access Control List (ACL) entries for the specified file or directory.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetContentSummary">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Store.Models.ContentSummaryResult GetContentSummary (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Store.Models.ContentSummaryResult GetContentSummary(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.GetContentSummary(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetContentSummary (operations As IFileSystemOperations, accountName As String, path As String) As ContentSummaryResult" />
      <MemberSignature Language="F#" Value="static member GetContentSummary : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string -&gt; Microsoft.Azure.Management.DataLake.Store.Models.ContentSummaryResult" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.GetContentSummary (operations, accountName, path)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.ContentSummaryResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="50109-251">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="50109-251">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="50109-252">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="50109-252">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="50109-253">Data Lake Store のパス (以降で '/') の概要を取得する対象のファイルです。</span><span class="sxs-lookup"><span data-stu-id="50109-253">The Data Lake Store path (starting with '/') of the file for which to retrieve the summary.</span></span>
            </param>
        <summary>
            <span data-ttu-id="50109-254">ファイル パスで指定された、ファイルのコンテンツの集計オブジェクトを取得します。</span><span class="sxs-lookup"><span data-stu-id="50109-254">Gets the file content summary object specified by the file path.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetContentSummaryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.ContentSummaryResult&gt; GetContentSummaryAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.ContentSummaryResult&gt; GetContentSummaryAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.GetContentSummaryAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetContentSummaryAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.ContentSummaryResult&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.GetContentSummaryAsync (operations, accountName, path, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;GetContentSummaryAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.ContentSummaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="50109-255">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="50109-255">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="50109-256">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="50109-256">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="50109-257">Data Lake Store のパス (以降で '/') の概要を取得する対象のファイルです。</span><span class="sxs-lookup"><span data-stu-id="50109-257">The Data Lake Store path (starting with '/') of the file for which to retrieve the summary.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="50109-258">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="50109-258">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="50109-259">ファイル パスで指定された、ファイルのコンテンツの集計オブジェクトを取得します。</span><span class="sxs-lookup"><span data-stu-id="50109-259">Gets the file content summary object specified by the file path.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFileStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Store.Models.FileStatusResult GetFileStatus (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, Nullable&lt;bool&gt; tooId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Store.Models.FileStatusResult GetFileStatus(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, valuetype System.Nullable`1&lt;bool&gt; tooId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.GetFileStatus(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetFileStatus (operations As IFileSystemOperations, accountName As String, path As String, Optional tooId As Nullable(Of Boolean) = null) As FileStatusResult" />
      <MemberSignature Language="F#" Value="static member GetFileStatus : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.DataLake.Store.Models.FileStatusResult" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.GetFileStatus (operations, accountName, path, tooId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.FileStatusResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="tooId" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="50109-260">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="50109-260">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="50109-261">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="50109-261">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="50109-262">Data Lake Store のパス (以降で '/') のファイルまたは状態を取得する対象のディレクトリ。</span><span class="sxs-lookup"><span data-stu-id="50109-262">The Data Lake Store path (starting with '/') of the file or directory for which to retrieve the status.</span></span>
            </param>
        <param name="tooId">
            <span data-ttu-id="50109-263">所有者とグループの代わりにわかりやすい名前を返す省略可能なスイッチです。</span><span class="sxs-lookup"><span data-stu-id="50109-263">An optional switch to return friendly names in place of owner and group.</span></span>
            <span data-ttu-id="50109-264">tooid AAD のオブジェクト ID ではなく、false を返しますフレンドリ名を =。</span><span class="sxs-lookup"><span data-stu-id="50109-264">tooid=false returns friendly names instead of the AAD Object ID.</span></span> <span data-ttu-id="50109-265">既定値は true の場合、AAD のオブジェクト Id を取得します。</span><span class="sxs-lookup"><span data-stu-id="50109-265">Default value is true, returning AAD object IDs.</span></span>
            </param>
        <summary>
            <span data-ttu-id="50109-266">ファイルのパスで指定されたファイルの状態オブジェクトを取得します。</span><span class="sxs-lookup"><span data-stu-id="50109-266">Get the file status object specified by the file path.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFileStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileStatusResult&gt; GetFileStatusAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, Nullable&lt;bool&gt; tooId = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.FileStatusResult&gt; GetFileStatusAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, valuetype System.Nullable`1&lt;bool&gt; tooId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.GetFileStatusAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetFileStatusAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileStatusResult&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.GetFileStatusAsync (operations, accountName, path, tooId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;GetFileStatusAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileStatusResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="tooId" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="50109-267">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="50109-267">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="50109-268">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="50109-268">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="50109-269">Data Lake Store のパス (以降で '/') のファイルまたは状態を取得する対象のディレクトリ。</span><span class="sxs-lookup"><span data-stu-id="50109-269">The Data Lake Store path (starting with '/') of the file or directory for which to retrieve the status.</span></span>
            </param>
        <param name="tooId">
            <span data-ttu-id="50109-270">所有者とグループの代わりにわかりやすい名前を返す省略可能なスイッチです。</span><span class="sxs-lookup"><span data-stu-id="50109-270">An optional switch to return friendly names in place of owner and group.</span></span>
            <span data-ttu-id="50109-271">tooid AAD のオブジェクト ID ではなく、false を返しますフレンドリ名を =。</span><span class="sxs-lookup"><span data-stu-id="50109-271">tooid=false returns friendly names instead of the AAD Object ID.</span></span> <span data-ttu-id="50109-272">既定値は true の場合、AAD のオブジェクト Id を取得します。</span><span class="sxs-lookup"><span data-stu-id="50109-272">Default value is true, returning AAD object IDs.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="50109-273">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="50109-273">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="50109-274">ファイルのパスで指定されたファイルの状態オブジェクトを取得します。</span><span class="sxs-lookup"><span data-stu-id="50109-274">Get the file status object specified by the file path.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFileStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Store.Models.FileStatusesResult ListFileStatus (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, Nullable&lt;int&gt; listSize = null, string listAfter = null, string listBefore = null, Nullable&lt;bool&gt; tooId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Store.Models.FileStatusesResult ListFileStatus(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, valuetype System.Nullable`1&lt;int32&gt; listSize, string listAfter, string listBefore, valuetype System.Nullable`1&lt;bool&gt; tooId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.ListFileStatus(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Nullable{System.Int32},System.String,System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListFileStatus (operations As IFileSystemOperations, accountName As String, path As String, Optional listSize As Nullable(Of Integer) = null, Optional listAfter As String = null, Optional listBefore As String = null, Optional tooId As Nullable(Of Boolean) = null) As FileStatusesResult" />
      <MemberSignature Language="F#" Value="static member ListFileStatus : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * Nullable&lt;int&gt; * string * string * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.DataLake.Store.Models.FileStatusesResult" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.ListFileStatus (operations, accountName, path, listSize, listAfter, listBefore, tooId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.FileStatusesResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="listSize" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="listAfter" Type="System.String" />
        <Parameter Name="listBefore" Type="System.String" />
        <Parameter Name="tooId" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="50109-275">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="50109-275">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="50109-276">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="50109-276">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="50109-277">Data Lake Store のパス (以降で '/') のリストにディレクトリ。</span><span class="sxs-lookup"><span data-stu-id="50109-277">The Data Lake Store path (starting with '/') of the directory to list.</span></span>
            </param>
        <param name="listSize">
            <span data-ttu-id="50109-278">取得または返されるアイテムの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="50109-278">Gets or sets the number of items to return.</span></span> <span data-ttu-id="50109-279">省略可能。</span><span class="sxs-lookup"><span data-stu-id="50109-279">Optional.</span></span>
            </param>
        <param name="listAfter">
            <span data-ttu-id="50109-280">取得または結果を返すを開始位置となる項目または lexographical インデックスを設定します。</span><span class="sxs-lookup"><span data-stu-id="50109-280">Gets or sets the item or lexographical index after which to begin returning results.</span></span> <span data-ttu-id="50109-281">たとえば、'',' b' のファイル リストに指定された受信者 'と listAfter = 'b' は戻り値は '、および、listAfter = 'c' が戻り値と' です。</span><span class="sxs-lookup"><span data-stu-id="50109-281">For example, a file list of 'a','b','d' and listAfter='b' will return 'd', and a listAfter='c' will also return 'd'.</span></span> <span data-ttu-id="50109-282">省略可能。</span><span class="sxs-lookup"><span data-stu-id="50109-282">Optional.</span></span>
            </param>
        <param name="listBefore">
            <span data-ttu-id="50109-283">取得または結果を返すを開始する前に、項目または lexographical のインデックスを設定します。</span><span class="sxs-lookup"><span data-stu-id="50109-283">Gets or sets the item or lexographical index before which to begin returning results.</span></span> <span data-ttu-id="50109-284">たとえば、'',' b' のファイル リストに指定された受信者 'と listBefore = が' 'a'、'b'、および、listBefore に戻ります = 'c'、'a ',' b' を返すこともします。</span><span class="sxs-lookup"><span data-stu-id="50109-284">For example, a file list of 'a','b','d' and listBefore='d' will return 'a','b', and a listBefore='c' will also return 'a','b'.</span></span> <span data-ttu-id="50109-285">省略可能。</span><span class="sxs-lookup"><span data-stu-id="50109-285">Optional.</span></span>
            </param>
        <param name="tooId">
            <span data-ttu-id="50109-286">所有者とグループの代わりにわかりやすい名前を返す省略可能なスイッチです。</span><span class="sxs-lookup"><span data-stu-id="50109-286">An optional switch to return friendly names in place of owner and group.</span></span>
            <span data-ttu-id="50109-287">tooid AAD のオブジェクト ID ではなく、false を返しますフレンドリ名を =。</span><span class="sxs-lookup"><span data-stu-id="50109-287">tooid=false returns friendly names instead of the AAD Object ID.</span></span> <span data-ttu-id="50109-288">既定値は true の場合、AAD のオブジェクト Id を取得します。</span><span class="sxs-lookup"><span data-stu-id="50109-288">Default value is true, returning AAD object IDs.</span></span>
            </param>
        <summary>
            <span data-ttu-id="50109-289">省略可能な改ページ調整パラメーターを使用して、ファイルのパスで指定されたファイルの状態オブジェクトの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="50109-289">Get the list of file status objects specified by the file path, with optional pagination parameters</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFileStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileStatusesResult&gt; ListFileStatusAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, Nullable&lt;int&gt; listSize = null, string listAfter = null, string listBefore = null, Nullable&lt;bool&gt; tooId = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.FileStatusesResult&gt; ListFileStatusAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, valuetype System.Nullable`1&lt;int32&gt; listSize, string listAfter, string listBefore, valuetype System.Nullable`1&lt;bool&gt; tooId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.ListFileStatusAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Nullable{System.Int32},System.String,System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListFileStatusAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * Nullable&lt;int&gt; * string * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileStatusesResult&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.ListFileStatusAsync (operations, accountName, path, listSize, listAfter, listBefore, tooId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;ListFileStatusAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileStatusesResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="listSize" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="listAfter" Type="System.String" />
        <Parameter Name="listBefore" Type="System.String" />
        <Parameter Name="tooId" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="50109-290">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="50109-290">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="50109-291">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="50109-291">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="50109-292">Data Lake Store のパス (以降で '/') のリストにディレクトリ。</span><span class="sxs-lookup"><span data-stu-id="50109-292">The Data Lake Store path (starting with '/') of the directory to list.</span></span>
            </param>
        <param name="listSize">
            <span data-ttu-id="50109-293">取得または返されるアイテムの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="50109-293">Gets or sets the number of items to return.</span></span> <span data-ttu-id="50109-294">省略可能。</span><span class="sxs-lookup"><span data-stu-id="50109-294">Optional.</span></span>
            </param>
        <param name="listAfter">
            <span data-ttu-id="50109-295">取得または結果を返すを開始位置となる項目または lexographical インデックスを設定します。</span><span class="sxs-lookup"><span data-stu-id="50109-295">Gets or sets the item or lexographical index after which to begin returning results.</span></span> <span data-ttu-id="50109-296">たとえば、'',' b' のファイル リストに指定された受信者 'と listAfter = 'b' は戻り値は '、および、listAfter = 'c' が戻り値と' です。</span><span class="sxs-lookup"><span data-stu-id="50109-296">For example, a file list of 'a','b','d' and listAfter='b' will return 'd', and a listAfter='c' will also return 'd'.</span></span> <span data-ttu-id="50109-297">省略可能。</span><span class="sxs-lookup"><span data-stu-id="50109-297">Optional.</span></span>
            </param>
        <param name="listBefore">
            <span data-ttu-id="50109-298">取得または結果を返すを開始する前に、項目または lexographical のインデックスを設定します。</span><span class="sxs-lookup"><span data-stu-id="50109-298">Gets or sets the item or lexographical index before which to begin returning results.</span></span> <span data-ttu-id="50109-299">たとえば、'',' b' のファイル リストに指定された受信者 'と listBefore = が' 'a'、'b'、および、listBefore に戻ります = 'c'、'a ',' b' を返すこともします。</span><span class="sxs-lookup"><span data-stu-id="50109-299">For example, a file list of 'a','b','d' and listBefore='d' will return 'a','b', and a listBefore='c' will also return 'a','b'.</span></span> <span data-ttu-id="50109-300">省略可能。</span><span class="sxs-lookup"><span data-stu-id="50109-300">Optional.</span></span>
            </param>
        <param name="tooId">
            <span data-ttu-id="50109-301">所有者とグループの代わりにわかりやすい名前を返す省略可能なスイッチです。</span><span class="sxs-lookup"><span data-stu-id="50109-301">An optional switch to return friendly names in place of owner and group.</span></span>
            <span data-ttu-id="50109-302">tooid AAD のオブジェクト ID ではなく、false を返しますフレンドリ名を =。</span><span class="sxs-lookup"><span data-stu-id="50109-302">tooid=false returns friendly names instead of the AAD Object ID.</span></span> <span data-ttu-id="50109-303">既定値は true の場合、AAD のオブジェクト Id を取得します。</span><span class="sxs-lookup"><span data-stu-id="50109-303">Default value is true, returning AAD object IDs.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="50109-304">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="50109-304">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="50109-305">省略可能な改ページ調整パラメーターを使用して、ファイルのパスで指定されたファイルの状態オブジェクトの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="50109-305">Get the list of file status objects specified by the file path, with optional pagination parameters</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Mkdirs">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult Mkdirs (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, Nullable&lt;int&gt; permission = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult Mkdirs(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, valuetype System.Nullable`1&lt;int32&gt; permission) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.Mkdirs(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Mkdirs (operations As IFileSystemOperations, accountName As String, path As String, Optional permission As Nullable(Of Integer) = null) As FileOperationResult" />
      <MemberSignature Language="F#" Value="static member Mkdirs : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.Mkdirs (operations, accountName, path, permission)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="permission" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="50109-306">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="50109-306">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="50109-307">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="50109-307">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="50109-308">Data Lake Store のパス (以降で '/') を作成するディレクトリ。</span><span class="sxs-lookup"><span data-stu-id="50109-308">The Data Lake Store path (starting with '/') of the directory to create.</span></span>
            </param>
        <param name="permission">
            <span data-ttu-id="50109-309">省略可能な 8 進数のアクセス許可のディレクトリの作成に使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="50109-309">Optional octal permission with which the directory should be created.</span></span>
            </param>
        <summary>
            <span data-ttu-id="50109-310">ディレクトリを作成します。</span><span class="sxs-lookup"><span data-stu-id="50109-310">Creates a directory.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MkdirsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt; MkdirsAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, Nullable&lt;int&gt; permission = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt; MkdirsAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, valuetype System.Nullable`1&lt;int32&gt; permission, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.MkdirsAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member MkdirsAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.MkdirsAsync (operations, accountName, path, permission, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;MkdirsAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="permission" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="50109-311">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="50109-311">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="50109-312">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="50109-312">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="50109-313">Data Lake Store のパス (以降で '/') を作成するディレクトリ。</span><span class="sxs-lookup"><span data-stu-id="50109-313">The Data Lake Store path (starting with '/') of the directory to create.</span></span>
            </param>
        <param name="permission">
            <span data-ttu-id="50109-314">省略可能な 8 進数のアクセス許可のディレクトリの作成に使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="50109-314">Optional octal permission with which the directory should be created.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="50109-315">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="50109-315">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="50109-316">ディレクトリを作成します。</span><span class="sxs-lookup"><span data-stu-id="50109-316">Creates a directory.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ModifyAclEntries">
      <MemberSignature Language="C#" Value="public static void ModifyAclEntries (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string aclspec);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ModifyAclEntries(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string aclspec) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.ModifyAclEntries(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub ModifyAclEntries (operations As IFileSystemOperations, accountName As String, path As String, aclspec As String)" />
      <MemberSignature Language="F#" Value="static member ModifyAclEntries : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.ModifyAclEntries (operations, accountName, path, aclspec)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclspec" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="50109-317">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="50109-317">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="50109-318">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="50109-318">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="50109-319">Data Lake Store のパス (以降で '/') のファイルまたはディレクトリが変更されている ACL を使用します。</span><span class="sxs-lookup"><span data-stu-id="50109-319">The Data Lake Store path (starting with '/') of the file or directory with the ACL being modified.</span></span>
            </param>
        <param name="aclspec">
            <span data-ttu-id="50109-320">形式で、ACL の変更操作に含まれている ACL 仕様 ' [既定値:] ユーザー | グループ | その他の:: r |-w |-x |-'</span><span class="sxs-lookup"><span data-stu-id="50109-320">The ACL specification included in ACL modification operations in the format '[default:]user|group|other::r|-w|-x|-'</span></span>
            </param>
        <summary>
            <span data-ttu-id="50109-321">ファイルまたはフォルダーの既存のアクセス制御リスト (ACL) エントリを変更します。</span><span class="sxs-lookup"><span data-stu-id="50109-321">Modifies existing Access Control List (ACL) entries on a file or folder.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ModifyAclEntriesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ModifyAclEntriesAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string aclspec, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ModifyAclEntriesAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string aclspec, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.ModifyAclEntriesAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ModifyAclEntriesAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.ModifyAclEntriesAsync (operations, accountName, path, aclspec, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;ModifyAclEntriesAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclspec" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="50109-322">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="50109-322">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="50109-323">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="50109-323">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="50109-324">Data Lake Store のパス (以降で '/') のファイルまたはディレクトリが変更されている ACL を使用します。</span><span class="sxs-lookup"><span data-stu-id="50109-324">The Data Lake Store path (starting with '/') of the file or directory with the ACL being modified.</span></span>
            </param>
        <param name="aclspec">
            <span data-ttu-id="50109-325">形式で、ACL の変更操作に含まれている ACL 仕様 ' [既定値:] ユーザー | グループ | その他の:: r |-w |-x |-'</span><span class="sxs-lookup"><span data-stu-id="50109-325">The ACL specification included in ACL modification operations in the format '[default:]user|group|other::r|-w|-x|-'</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="50109-326">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="50109-326">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="50109-327">ファイルまたはフォルダーの既存のアクセス制御リスト (ACL) エントリを変更します。</span><span class="sxs-lookup"><span data-stu-id="50109-327">Modifies existing Access Control List (ACL) entries on a file or folder.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MsConcat">
      <MemberSignature Language="C#" Value="public static void MsConcat (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, System.IO.Stream streamContents, Nullable&lt;bool&gt; deleteSourceDirectory = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void MsConcat(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, class System.IO.Stream streamContents, valuetype System.Nullable`1&lt;bool&gt; deleteSourceDirectory) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.MsConcat(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.IO.Stream,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub MsConcat (operations As IFileSystemOperations, accountName As String, path As String, streamContents As Stream, Optional deleteSourceDirectory As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="static member MsConcat : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * System.IO.Stream * Nullable&lt;bool&gt; -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.MsConcat (operations, accountName, path, streamContents, deleteSourceDirectory)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="streamContents" Type="System.IO.Stream" />
        <Parameter Name="deleteSourceDirectory" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="50109-328">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="50109-328">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="50109-329">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="50109-329">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="50109-330">Data Lake Store のパス (以降で '/') の連結の結果として得られる出力先ファイルです。</span><span class="sxs-lookup"><span data-stu-id="50109-330">The Data Lake Store path (starting with '/') of the destination file resulting from the concatenation.</span></span>
            </param>
        <param name="streamContents">
            <span data-ttu-id="50109-331">Data Lake Store パスの一覧 (以降で '/') のソース ファイルです。</span><span class="sxs-lookup"><span data-stu-id="50109-331">A list of Data Lake Store paths (starting with '/') of the source files.</span></span>
            <span data-ttu-id="50109-332">形式でパスのコンマ区切りの一覧でなければなりません: sources=/file/path/1.txt,/file/path/2.txt,/file/path/lastfile.csv</span><span class="sxs-lookup"><span data-stu-id="50109-332">Must be a comma-separated path list in the format: sources=/file/path/1.txt,/file/path/2.txt,/file/path/lastfile.csv</span></span>
            </param>
        <param name="deleteSourceDirectory">
            <span data-ttu-id="50109-333">指定すると、最適化代わりに各個々 のソース ストリームを削除するには、フォルダーを削除、ソース ストリーム場合は代わりに、同じフォルダーにすべてのストリーム。</span><span class="sxs-lookup"><span data-stu-id="50109-333">Indicates that as an optimization instead of deleting each individual source stream, delete the source stream folder if all streams are in the same folder instead.</span></span> <span data-ttu-id="50109-334">これは、結果、フォルダー内のみのストリームが連結操作の一部とパフォーマンスが大幅に改善します。</span><span class="sxs-lookup"><span data-stu-id="50109-334">This results in a substantial performance improvement when the only streams in the folder are part of the concatenation operation.</span></span> <span data-ttu-id="50109-335">警告: ソース ファイルではないその他のファイルの削除が含まれます。</span><span class="sxs-lookup"><span data-stu-id="50109-335">WARNING: This includes the deletion of any other files that are not source files.</span></span> <span data-ttu-id="50109-336">ソース ファイルがソース ディレクトリのファイルのみの場合は true にのみ設定します。</span><span class="sxs-lookup"><span data-stu-id="50109-336">Only set this to true when source files are the only files in the source directory.</span></span>
            </param>
        <summary>
            <span data-ttu-id="50109-337">出力先ファイル、成功時にすべてのソース ファイルを削除するのには、ソース ファイルのリストを連結します。</span><span class="sxs-lookup"><span data-stu-id="50109-337">Concatenates the list of source files into the destination file, deleting all source files upon success.</span></span> <span data-ttu-id="50109-338">このメソッドは、Concat メソッドよりも多くのソース ファイルのパスを受け取ります。</span><span class="sxs-lookup"><span data-stu-id="50109-338">This method accepts more source file paths than the Concat method.</span></span> <span data-ttu-id="50109-339">このメソッドと、受け取るパラメーターは、使いやすさ、今後のバージョンでの変更の対象はします。</span><span class="sxs-lookup"><span data-stu-id="50109-339">This method and the parameters it accepts are subject to change for usability in an upcoming version.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MsConcatAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task MsConcatAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, System.IO.Stream streamContents, Nullable&lt;bool&gt; deleteSourceDirectory = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task MsConcatAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, class System.IO.Stream streamContents, valuetype System.Nullable`1&lt;bool&gt; deleteSourceDirectory, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.MsConcatAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.IO.Stream,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member MsConcatAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * System.IO.Stream * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.MsConcatAsync (operations, accountName, path, streamContents, deleteSourceDirectory, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;MsConcatAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="streamContents" Type="System.IO.Stream" />
        <Parameter Name="deleteSourceDirectory" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="50109-340">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="50109-340">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="50109-341">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="50109-341">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="50109-342">Data Lake Store のパス (以降で '/') の連結の結果として得られる出力先ファイルです。</span><span class="sxs-lookup"><span data-stu-id="50109-342">The Data Lake Store path (starting with '/') of the destination file resulting from the concatenation.</span></span>
            </param>
        <param name="streamContents">
            <span data-ttu-id="50109-343">Data Lake Store パスの一覧 (以降で '/') のソース ファイルです。</span><span class="sxs-lookup"><span data-stu-id="50109-343">A list of Data Lake Store paths (starting with '/') of the source files.</span></span>
            <span data-ttu-id="50109-344">形式でパスのコンマ区切りの一覧でなければなりません: sources=/file/path/1.txt,/file/path/2.txt,/file/path/lastfile.csv</span><span class="sxs-lookup"><span data-stu-id="50109-344">Must be a comma-separated path list in the format: sources=/file/path/1.txt,/file/path/2.txt,/file/path/lastfile.csv</span></span>
            </param>
        <param name="deleteSourceDirectory">
            <span data-ttu-id="50109-345">指定すると、最適化代わりに各個々 のソース ストリームを削除するには、フォルダーを削除、ソース ストリーム場合は代わりに、同じフォルダーにすべてのストリーム。</span><span class="sxs-lookup"><span data-stu-id="50109-345">Indicates that as an optimization instead of deleting each individual source stream, delete the source stream folder if all streams are in the same folder instead.</span></span> <span data-ttu-id="50109-346">これは、結果、フォルダー内のみのストリームが連結操作の一部とパフォーマンスが大幅に改善します。</span><span class="sxs-lookup"><span data-stu-id="50109-346">This results in a substantial performance improvement when the only streams in the folder are part of the concatenation operation.</span></span> <span data-ttu-id="50109-347">警告: ソース ファイルではないその他のファイルの削除が含まれます。</span><span class="sxs-lookup"><span data-stu-id="50109-347">WARNING: This includes the deletion of any other files that are not source files.</span></span> <span data-ttu-id="50109-348">ソース ファイルがソース ディレクトリのファイルのみの場合は true にのみ設定します。</span><span class="sxs-lookup"><span data-stu-id="50109-348">Only set this to true when source files are the only files in the source directory.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="50109-349">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="50109-349">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="50109-350">出力先ファイル、成功時にすべてのソース ファイルを削除するのには、ソース ファイルのリストを連結します。</span><span class="sxs-lookup"><span data-stu-id="50109-350">Concatenates the list of source files into the destination file, deleting all source files upon success.</span></span> <span data-ttu-id="50109-351">このメソッドは、Concat メソッドよりも多くのソース ファイルのパスを受け取ります。</span><span class="sxs-lookup"><span data-stu-id="50109-351">This method accepts more source file paths than the Concat method.</span></span> <span data-ttu-id="50109-352">このメソッドと、受け取るパラメーターは、使いやすさ、今後のバージョンでの変更の対象はします。</span><span class="sxs-lookup"><span data-stu-id="50109-352">This method and the parameters it accepts are subject to change for usability in an upcoming version.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Open">
      <MemberSignature Language="C#" Value="public static System.IO.Stream Open (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, Nullable&lt;long&gt; length = null, Nullable&lt;long&gt; offset = null, Nullable&lt;Guid&gt; fileSessionId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.IO.Stream Open(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, valuetype System.Nullable`1&lt;int64&gt; length, valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; fileSessionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.Open(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Guid})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Open (operations As IFileSystemOperations, accountName As String, path As String, Optional length As Nullable(Of Long) = null, Optional offset As Nullable(Of Long) = null, Optional fileSessionId As Nullable(Of Guid) = null) As Stream" />
      <MemberSignature Language="F#" Value="static member Open : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;Guid&gt; -&gt; System.IO.Stream" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.Open (operations, accountName, path, length, offset, fileSessionId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IO.Stream</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="length" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="fileSessionId" Type="System.Nullable&lt;System.Guid&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="50109-353">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="50109-353">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="50109-354">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="50109-354">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="50109-355">Data Lake Store のパス (以降で '/') のファイルを開きます。</span><span class="sxs-lookup"><span data-stu-id="50109-355">The Data Lake Store path (starting with '/') of the file to open.</span></span>
            </param>
        <param name="length">
            <span data-ttu-id="50109-356">サーバーが取得しようとするバイト数。</span><span class="sxs-lookup"><span data-stu-id="50109-356">The number of bytes that the server will attempt to retrieve.</span></span> <span data-ttu-id="50109-357">取得されます&lt;長さのバイト数を = です。</span><span class="sxs-lookup"><span data-stu-id="50109-357">It will retrieve &lt;= length bytes.</span></span>
            </param>
        <param name="offset">
            <span data-ttu-id="50109-358">データの読み取りを開始するバイト オフセット。</span><span class="sxs-lookup"><span data-stu-id="50109-358">The byte offset to start reading data from.</span></span>
            </param>
        <param name="fileSessionId">
            <span data-ttu-id="50109-359">1 ファイルが同じ fileSessionId ですべての読み取りを示す省略可能な一意の GUID は、同じクライアントと同じセッションです。</span><span class="sxs-lookup"><span data-stu-id="50109-359">Optional unique GUID per file indicating all the reads with the same fileSessionId are from the same client and same session.</span></span> <span data-ttu-id="50109-360">パフォーマンス上の利点が得られます。</span><span class="sxs-lookup"><span data-stu-id="50109-360">This will give a performance benefit.</span></span>
            </param>
        <summary>
            <span data-ttu-id="50109-361">開き、指定したファイルから読み取ります。</span><span class="sxs-lookup"><span data-stu-id="50109-361">Opens and reads from the specified file.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.IO.Stream&gt; OpenAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, Nullable&lt;long&gt; length = null, Nullable&lt;long&gt; offset = null, Nullable&lt;Guid&gt; fileSessionId = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.IO.Stream&gt; OpenAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, valuetype System.Nullable`1&lt;int64&gt; length, valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; fileSessionId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.OpenAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Guid},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member OpenAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;Guid&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.IO.Stream&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.OpenAsync (operations, accountName, path, length, offset, fileSessionId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;OpenAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.IO.Stream&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="length" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="fileSessionId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="50109-362">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="50109-362">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="50109-363">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="50109-363">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="50109-364">Data Lake Store のパス (以降で '/') のファイルを開きます。</span><span class="sxs-lookup"><span data-stu-id="50109-364">The Data Lake Store path (starting with '/') of the file to open.</span></span>
            </param>
        <param name="length">
            <span data-ttu-id="50109-365">サーバーが取得しようとするバイト数。</span><span class="sxs-lookup"><span data-stu-id="50109-365">The number of bytes that the server will attempt to retrieve.</span></span> <span data-ttu-id="50109-366">取得されます&lt;長さのバイト数を = です。</span><span class="sxs-lookup"><span data-stu-id="50109-366">It will retrieve &lt;= length bytes.</span></span>
            </param>
        <param name="offset">
            <span data-ttu-id="50109-367">データの読み取りを開始するバイト オフセット。</span><span class="sxs-lookup"><span data-stu-id="50109-367">The byte offset to start reading data from.</span></span>
            </param>
        <param name="fileSessionId">
            <span data-ttu-id="50109-368">1 ファイルが同じ fileSessionId ですべての読み取りを示す省略可能な一意の GUID は、同じクライアントと同じセッションです。</span><span class="sxs-lookup"><span data-stu-id="50109-368">Optional unique GUID per file indicating all the reads with the same fileSessionId are from the same client and same session.</span></span> <span data-ttu-id="50109-369">パフォーマンス上の利点が得られます。</span><span class="sxs-lookup"><span data-stu-id="50109-369">This will give a performance benefit.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="50109-370">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="50109-370">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="50109-371">開き、指定したファイルから読み取ります。</span><span class="sxs-lookup"><span data-stu-id="50109-371">Opens and reads from the specified file.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PathExists">
      <MemberSignature Language="C#" Value="public static bool PathExists (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string getFilePath);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool PathExists(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string getFilePath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.PathExists(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function PathExists (operations As IFileSystemOperations, accountName As String, getFilePath As String) As Boolean" />
      <MemberSignature Language="F#" Value="static member PathExists : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string -&gt; bool" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.PathExists (operations, accountName, getFilePath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="getFilePath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="50109-372">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="50109-372">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="50109-373">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="50109-373">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="getFilePath">
            <span data-ttu-id="50109-374">Data Lake Store のパス (以降で '/') のファイルまたはディレクトリの存在をテストします。</span><span class="sxs-lookup"><span data-stu-id="50109-374">The Data Lake Store path (starting with '/') of the file or directory for which to test the existence of.</span></span>
            </param>
        <summary>
            <span data-ttu-id="50109-375">ファイル パスで指定されたファイルまたはディレクトリ オブジェクトの存在をテストします。</span><span class="sxs-lookup"><span data-stu-id="50109-375">Test the existence of a file or directory object specified by the file path.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PathExistsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;bool&gt; PathExistsAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string getFilePath, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;bool&gt; PathExistsAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string getFilePath, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.PathExistsAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PathExistsAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.PathExistsAsync (operations, accountName, getFilePath, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;PathExistsAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="getFilePath" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="50109-376">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="50109-376">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="50109-377">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="50109-377">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="getFilePath">
            <span data-ttu-id="50109-378">Data Lake Store のパス (以降で '/') のファイルまたはディレクトリの存在をテストします。</span><span class="sxs-lookup"><span data-stu-id="50109-378">The Data Lake Store path (starting with '/') of the file or directory for which to test the existence of.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="50109-379">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="50109-379">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="50109-380">ファイル パスで指定されたファイルまたはディレクトリ オブジェクトの存在をテストします。</span><span class="sxs-lookup"><span data-stu-id="50109-380">Test the existence of a file or directory object specified by the file path.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAcl">
      <MemberSignature Language="C#" Value="public static void RemoveAcl (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void RemoveAcl(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.RemoveAcl(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub RemoveAcl (operations As IFileSystemOperations, accountName As String, path As String)" />
      <MemberSignature Language="F#" Value="static member RemoveAcl : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.RemoveAcl (operations, accountName, path)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="50109-381">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="50109-381">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="50109-382">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="50109-382">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="50109-383">Data Lake Store のパス (以降で '/') のファイルまたはディレクトリ ACL を削除します。</span><span class="sxs-lookup"><span data-stu-id="50109-383">The Data Lake Store path (starting with '/') of the file or directory with the ACL being removed.</span></span>
            </param>
        <summary>
            <span data-ttu-id="50109-384">指定したファイルまたはディレクトリの既存のアクセス制御リスト (ACL) を削除します。</span><span class="sxs-lookup"><span data-stu-id="50109-384">Removes the existing Access Control List (ACL) of the specified file or directory.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAclAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RemoveAclAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RemoveAclAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.RemoveAclAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RemoveAclAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.RemoveAclAsync (operations, accountName, path, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;RemoveAclAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="50109-385">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="50109-385">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="50109-386">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="50109-386">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="50109-387">Data Lake Store のパス (以降で '/') のファイルまたはディレクトリ ACL を削除します。</span><span class="sxs-lookup"><span data-stu-id="50109-387">The Data Lake Store path (starting with '/') of the file or directory with the ACL being removed.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="50109-388">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="50109-388">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="50109-389">指定したファイルまたはディレクトリの既存のアクセス制御リスト (ACL) を削除します。</span><span class="sxs-lookup"><span data-stu-id="50109-389">Removes the existing Access Control List (ACL) of the specified file or directory.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAclEntries">
      <MemberSignature Language="C#" Value="public static void RemoveAclEntries (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string aclspec);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void RemoveAclEntries(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string aclspec) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.RemoveAclEntries(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub RemoveAclEntries (operations As IFileSystemOperations, accountName As String, path As String, aclspec As String)" />
      <MemberSignature Language="F#" Value="static member RemoveAclEntries : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.RemoveAclEntries (operations, accountName, path, aclspec)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclspec" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="50109-390">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="50109-390">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="50109-391">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="50109-391">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="50109-392">Data Lake Store のパス (以降で '/') のファイルまたはディレクトリ ACL を削除します。</span><span class="sxs-lookup"><span data-stu-id="50109-392">The Data Lake Store path (starting with '/') of the file or directory with the ACL being removed.</span></span>
            </param>
        <param name="aclspec">
            <span data-ttu-id="50109-393">形式で、ACL の削除操作に含まれている ACL spec ' [既定値:] ユーザー | グループ | その他の '</span><span class="sxs-lookup"><span data-stu-id="50109-393">The ACL spec included in ACL removal operations in the format '[default:]user|group|other'</span></span>
            </param>
        <summary>
            <span data-ttu-id="50109-394">既存のファイルまたはフォルダーのアクセス制御リスト (ACL) エントリを削除します。</span><span class="sxs-lookup"><span data-stu-id="50109-394">Removes existing Access Control List (ACL) entries for a file or folder.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAclEntriesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RemoveAclEntriesAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string aclspec, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RemoveAclEntriesAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string aclspec, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.RemoveAclEntriesAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RemoveAclEntriesAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.RemoveAclEntriesAsync (operations, accountName, path, aclspec, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;RemoveAclEntriesAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclspec" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="50109-395">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="50109-395">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="50109-396">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="50109-396">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="50109-397">Data Lake Store のパス (以降で '/') のファイルまたはディレクトリ ACL を削除します。</span><span class="sxs-lookup"><span data-stu-id="50109-397">The Data Lake Store path (starting with '/') of the file or directory with the ACL being removed.</span></span>
            </param>
        <param name="aclspec">
            <span data-ttu-id="50109-398">形式で、ACL の削除操作に含まれている ACL spec ' [既定値:] ユーザー | グループ | その他の '</span><span class="sxs-lookup"><span data-stu-id="50109-398">The ACL spec included in ACL removal operations in the format '[default:]user|group|other'</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="50109-399">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="50109-399">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="50109-400">既存のファイルまたはフォルダーのアクセス制御リスト (ACL) エントリを削除します。</span><span class="sxs-lookup"><span data-stu-id="50109-400">Removes existing Access Control List (ACL) entries for a file or folder.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveDefaultAcl">
      <MemberSignature Language="C#" Value="public static void RemoveDefaultAcl (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void RemoveDefaultAcl(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.RemoveDefaultAcl(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub RemoveDefaultAcl (operations As IFileSystemOperations, accountName As String, path As String)" />
      <MemberSignature Language="F#" Value="static member RemoveDefaultAcl : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.RemoveDefaultAcl (operations, accountName, path)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="50109-401">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="50109-401">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="50109-402">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="50109-402">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="50109-403">Data Lake Store のパス (以降で '/') の既定の ACL が削除されると同じディレクトリにします。</span><span class="sxs-lookup"><span data-stu-id="50109-403">The Data Lake Store path (starting with '/') of the directory with the default ACL being removed.</span></span>
            </param>
        <summary>
            <span data-ttu-id="50109-404">既存既定のアクセス制御リスト (ACL) の指定されたディレクトリを削除します。</span><span class="sxs-lookup"><span data-stu-id="50109-404">Removes the existing Default Access Control List (ACL) of the specified directory.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveDefaultAclAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RemoveDefaultAclAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RemoveDefaultAclAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.RemoveDefaultAclAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RemoveDefaultAclAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.RemoveDefaultAclAsync (operations, accountName, path, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;RemoveDefaultAclAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="50109-405">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="50109-405">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="50109-406">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="50109-406">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="50109-407">Data Lake Store のパス (以降で '/') の既定の ACL が削除されると同じディレクトリにします。</span><span class="sxs-lookup"><span data-stu-id="50109-407">The Data Lake Store path (starting with '/') of the directory with the default ACL being removed.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="50109-408">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="50109-408">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="50109-409">既存既定のアクセス制御リスト (ACL) の指定されたディレクトリを削除します。</span><span class="sxs-lookup"><span data-stu-id="50109-409">Removes the existing Default Access Control List (ACL) of the specified directory.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Rename">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult Rename (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string destination);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult Rename(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string destination) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.Rename(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Rename (operations As IFileSystemOperations, accountName As String, path As String, destination As String) As FileOperationResult" />
      <MemberSignature Language="F#" Value="static member Rename : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.Rename (operations, accountName, path, destination)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="destination" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="50109-410">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="50109-410">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="50109-411">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="50109-411">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="50109-412">Data Lake Store のパス (以降で '/') のファイルまたはディレクトリに移動または名前変更します。</span><span class="sxs-lookup"><span data-stu-id="50109-412">The Data Lake Store path (starting with '/') of the file or directory to move/rename.</span></span>
            </param>
        <param name="destination">
            <span data-ttu-id="50109-413">移動または名前変更、ファイルまたはフォルダーへのパス</span><span class="sxs-lookup"><span data-stu-id="50109-413">The path to move/rename the file or folder to</span></span>
            </param>
        <summary>
            <span data-ttu-id="50109-414">ファイルまたはディレクトリの名前を変更します。</span><span class="sxs-lookup"><span data-stu-id="50109-414">Rename a file or directory.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RenameAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt; RenameAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string destination, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt; RenameAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string destination, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.RenameAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RenameAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.RenameAsync (operations, accountName, path, destination, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;RenameAsync&gt;d__41))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="destination" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="50109-415">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="50109-415">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="50109-416">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="50109-416">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="50109-417">Data Lake Store のパス (以降で '/') のファイルまたはディレクトリに移動または名前変更します。</span><span class="sxs-lookup"><span data-stu-id="50109-417">The Data Lake Store path (starting with '/') of the file or directory to move/rename.</span></span>
            </param>
        <param name="destination">
            <span data-ttu-id="50109-418">移動または名前変更、ファイルまたはフォルダーへのパス</span><span class="sxs-lookup"><span data-stu-id="50109-418">The path to move/rename the file or folder to</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="50109-419">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="50109-419">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="50109-420">ファイルまたはディレクトリの名前を変更します。</span><span class="sxs-lookup"><span data-stu-id="50109-420">Rename a file or directory.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetAcl">
      <MemberSignature Language="C#" Value="public static void SetAcl (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string aclspec);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void SetAcl(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string aclspec) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.SetAcl(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub SetAcl (operations As IFileSystemOperations, accountName As String, path As String, aclspec As String)" />
      <MemberSignature Language="F#" Value="static member SetAcl : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.SetAcl (operations, accountName, path, aclspec)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclspec" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="50109-421">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="50109-421">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="50109-422">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="50109-422">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="50109-423">Data Lake Store のパス (以降で '/') のファイルまたはディレクトリの ACL を設定します。</span><span class="sxs-lookup"><span data-stu-id="50109-423">The Data Lake Store path (starting with '/') of the file or directory on which to set the ACL.</span></span>
            </param>
        <param name="aclspec">
            <span data-ttu-id="50109-424">形式で ACL を作成する操作に含まれる ACL spec ' [既定値:] ユーザー | グループ | その他の:: r |-w |-x |-'</span><span class="sxs-lookup"><span data-stu-id="50109-424">The ACL spec included in ACL creation operations in the format '[default:]user|group|other::r|-w|-x|-'</span></span>
            </param>
        <summary>
            <span data-ttu-id="50109-425">ファイルまたはフォルダーのアクセス制御リスト (ACL) を設定します。</span><span class="sxs-lookup"><span data-stu-id="50109-425">Sets the Access Control List (ACL) for a file or folder.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetAclAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task SetAclAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string aclspec, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task SetAclAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string aclspec, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.SetAclAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SetAclAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.SetAclAsync (operations, accountName, path, aclspec, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;SetAclAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclspec" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="50109-426">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="50109-426">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="50109-427">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="50109-427">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="50109-428">Data Lake Store のパス (以降で '/') のファイルまたはディレクトリの ACL を設定します。</span><span class="sxs-lookup"><span data-stu-id="50109-428">The Data Lake Store path (starting with '/') of the file or directory on which to set the ACL.</span></span>
            </param>
        <param name="aclspec">
            <span data-ttu-id="50109-429">形式で ACL を作成する操作に含まれる ACL spec ' [既定値:] ユーザー | グループ | その他の:: r |-w |-x |-'</span><span class="sxs-lookup"><span data-stu-id="50109-429">The ACL spec included in ACL creation operations in the format '[default:]user|group|other::r|-w|-x|-'</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="50109-430">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="50109-430">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="50109-431">ファイルまたはフォルダーのアクセス制御リスト (ACL) を設定します。</span><span class="sxs-lookup"><span data-stu-id="50109-431">Sets the Access Control List (ACL) for a file or folder.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetFileExpiry">
      <MemberSignature Language="C#" Value="public static void SetFileExpiry (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, Microsoft.Azure.Management.DataLake.Store.Models.ExpiryOptionType expiryOption, Nullable&lt;long&gt; expireTime = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void SetFileExpiry(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, valuetype Microsoft.Azure.Management.DataLake.Store.Models.ExpiryOptionType expiryOption, valuetype System.Nullable`1&lt;int64&gt; expireTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.SetFileExpiry(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,Microsoft.Azure.Management.DataLake.Store.Models.ExpiryOptionType,System.Nullable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub SetFileExpiry (operations As IFileSystemOperations, accountName As String, path As String, expiryOption As ExpiryOptionType, Optional expireTime As Nullable(Of Long) = null)" />
      <MemberSignature Language="F#" Value="static member SetFileExpiry : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * Microsoft.Azure.Management.DataLake.Store.Models.ExpiryOptionType * Nullable&lt;int64&gt; -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.SetFileExpiry (operations, accountName, path, expiryOption, expireTime)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="expiryOption" Type="Microsoft.Azure.Management.DataLake.Store.Models.ExpiryOptionType" />
        <Parameter Name="expireTime" Type="System.Nullable&lt;System.Int64&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="50109-432">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="50109-432">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="50109-433">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="50109-433">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="50109-434">Data Lake Store のパス (以降で '/') を設定するか、有効期限を削除するファイルのです。</span><span class="sxs-lookup"><span data-stu-id="50109-434">The Data Lake Store path (starting with '/') of the file on which to set or remove the expiration time.</span></span>
            </param>
        <param name="expiryOption">
            <span data-ttu-id="50109-435">ファイルを使用する有効期限の種類を示します。 1。</span><span class="sxs-lookup"><span data-stu-id="50109-435">Indicates the type of expiration to use for the file: 1.</span></span> <span data-ttu-id="50109-436">NeverExpire: ExpireTime は無視されます。</span><span class="sxs-lookup"><span data-stu-id="50109-436">NeverExpire: ExpireTime is ignored.</span></span> <span data-ttu-id="50109-437">2.</span><span class="sxs-lookup"><span data-stu-id="50109-437">2.</span></span> <span data-ttu-id="50109-438">RelativeToNow: ExpireTime は、ファイルの有効期限が更新されたときに、基準に有効期限の日付を表すミリ秒の整数です。</span><span class="sxs-lookup"><span data-stu-id="50109-438">RelativeToNow: ExpireTime is an integer in milliseconds representing the expiration date relative to when file expiration is updated.</span></span> <span data-ttu-id="50109-439">手順 3.</span><span class="sxs-lookup"><span data-stu-id="50109-439">3.</span></span> <span data-ttu-id="50109-440">RelativeToCreationDate: ExpireTime は、ファイルの作成の基準とした有効期限の日付を表すミリ秒の整数です。</span><span class="sxs-lookup"><span data-stu-id="50109-440">RelativeToCreationDate: ExpireTime is an integer in milliseconds representing the expiration date relative to file creation.</span></span>
            4. <span data-ttu-id="50109-441">絶対値: ExpireTime 整数です (ミリ秒単位) の 1970 年 1 月 1 基準とした Unix タイムスタンプとして 00時 00分: 00 です。</span><span class="sxs-lookup"><span data-stu-id="50109-441">Absolute: ExpireTime is an integer in milliseconds, as a Unix timestamp relative to 1/1/1970 00:00:00.</span></span> <span data-ttu-id="50109-442">使用可能な値が含まれます: 'NeverExpire'、'RelativeToNow'、'RelativeToCreationDate'、'Absolute'</span><span class="sxs-lookup"><span data-stu-id="50109-442">Possible values include: 'NeverExpire', 'RelativeToNow', 'RelativeToCreationDate', 'Absolute'</span></span>
            </param>
        <param name="expireTime">
            <span data-ttu-id="50109-443">ファイルは、有効期限が設定された ExpiryOption に対応する時間。</span><span class="sxs-lookup"><span data-stu-id="50109-443">The time that the file will expire, corresponding to the ExpiryOption that was set.</span></span>
            </param>
        <summary>
            <span data-ttu-id="50109-444">設定または指定したファイルに有効期限を削除します。</span><span class="sxs-lookup"><span data-stu-id="50109-444">Sets or removes the expiration time on the specified file.</span></span> <span data-ttu-id="50109-445">この操作は、ファイルに対してのみ実行できます。</span><span class="sxs-lookup"><span data-stu-id="50109-445">This operation can only be executed against files.</span></span> <span data-ttu-id="50109-446">フォルダーを指定することはできません。</span><span class="sxs-lookup"><span data-stu-id="50109-446">Folders are not supported.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetFileExpiryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task SetFileExpiryAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, Microsoft.Azure.Management.DataLake.Store.Models.ExpiryOptionType expiryOption, Nullable&lt;long&gt; expireTime = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task SetFileExpiryAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, valuetype Microsoft.Azure.Management.DataLake.Store.Models.ExpiryOptionType expiryOption, valuetype System.Nullable`1&lt;int64&gt; expireTime, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.SetFileExpiryAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,Microsoft.Azure.Management.DataLake.Store.Models.ExpiryOptionType,System.Nullable{System.Int64},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SetFileExpiryAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * Microsoft.Azure.Management.DataLake.Store.Models.ExpiryOptionType * Nullable&lt;int64&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.SetFileExpiryAsync (operations, accountName, path, expiryOption, expireTime, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;SetFileExpiryAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="expiryOption" Type="Microsoft.Azure.Management.DataLake.Store.Models.ExpiryOptionType" />
        <Parameter Name="expireTime" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="50109-447">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="50109-447">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="50109-448">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="50109-448">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="50109-449">Data Lake Store のパス (以降で '/') を設定するか、有効期限を削除するファイルのです。</span><span class="sxs-lookup"><span data-stu-id="50109-449">The Data Lake Store path (starting with '/') of the file on which to set or remove the expiration time.</span></span>
            </param>
        <param name="expiryOption">
            <span data-ttu-id="50109-450">ファイルを使用する有効期限の種類を示します。 1。</span><span class="sxs-lookup"><span data-stu-id="50109-450">Indicates the type of expiration to use for the file: 1.</span></span> <span data-ttu-id="50109-451">NeverExpire: ExpireTime は無視されます。</span><span class="sxs-lookup"><span data-stu-id="50109-451">NeverExpire: ExpireTime is ignored.</span></span> <span data-ttu-id="50109-452">2.</span><span class="sxs-lookup"><span data-stu-id="50109-452">2.</span></span> <span data-ttu-id="50109-453">RelativeToNow: ExpireTime は、ファイルの有効期限が更新されたときに、基準に有効期限の日付を表すミリ秒の整数です。</span><span class="sxs-lookup"><span data-stu-id="50109-453">RelativeToNow: ExpireTime is an integer in milliseconds representing the expiration date relative to when file expiration is updated.</span></span> <span data-ttu-id="50109-454">手順 3.</span><span class="sxs-lookup"><span data-stu-id="50109-454">3.</span></span> <span data-ttu-id="50109-455">RelativeToCreationDate: ExpireTime は、ファイルの作成の基準とした有効期限の日付を表すミリ秒の整数です。</span><span class="sxs-lookup"><span data-stu-id="50109-455">RelativeToCreationDate: ExpireTime is an integer in milliseconds representing the expiration date relative to file creation.</span></span>
            4. <span data-ttu-id="50109-456">絶対値: ExpireTime 整数です (ミリ秒単位) の 1970 年 1 月 1 基準とした Unix タイムスタンプとして 00時 00分: 00 です。</span><span class="sxs-lookup"><span data-stu-id="50109-456">Absolute: ExpireTime is an integer in milliseconds, as a Unix timestamp relative to 1/1/1970 00:00:00.</span></span> <span data-ttu-id="50109-457">使用可能な値が含まれます: 'NeverExpire'、'RelativeToNow'、'RelativeToCreationDate'、'Absolute'</span><span class="sxs-lookup"><span data-stu-id="50109-457">Possible values include: 'NeverExpire', 'RelativeToNow', 'RelativeToCreationDate', 'Absolute'</span></span>
            </param>
        <param name="expireTime">
            <span data-ttu-id="50109-458">ファイルは、有効期限が設定された ExpiryOption に対応する時間。</span><span class="sxs-lookup"><span data-stu-id="50109-458">The time that the file will expire, corresponding to the ExpiryOption that was set.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="50109-459">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="50109-459">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="50109-460">設定または指定したファイルに有効期限を削除します。</span><span class="sxs-lookup"><span data-stu-id="50109-460">Sets or removes the expiration time on the specified file.</span></span> <span data-ttu-id="50109-461">この操作は、ファイルに対してのみ実行できます。</span><span class="sxs-lookup"><span data-stu-id="50109-461">This operation can only be executed against files.</span></span> <span data-ttu-id="50109-462">フォルダーを指定することはできません。</span><span class="sxs-lookup"><span data-stu-id="50109-462">Folders are not supported.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetOwner">
      <MemberSignature Language="C#" Value="public static void SetOwner (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string owner = null, string group = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void SetOwner(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string owner, string group) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.SetOwner(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub SetOwner (operations As IFileSystemOperations, accountName As String, path As String, Optional owner As String = null, Optional group As String = null)" />
      <MemberSignature Language="F#" Value="static member SetOwner : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.SetOwner (operations, accountName, path, owner, group)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="owner" Type="System.String" />
        <Parameter Name="group" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="50109-463">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="50109-463">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="50109-464">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="50109-464">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="50109-465">Data Lake Store のパス (以降で '/') のファイルまたは所有者を設定する対象のディレクトリ。</span><span class="sxs-lookup"><span data-stu-id="50109-465">The Data Lake Store path (starting with '/') of the file or directory for which to set the owner.</span></span>
            </param>
        <param name="owner">
            <span data-ttu-id="50109-466">ファイルまたはディレクトリの所有者であるユーザーの AAD のオブジェクト ID。</span><span class="sxs-lookup"><span data-stu-id="50109-466">The AAD Object ID of the user owner of the file or directory.</span></span> <span data-ttu-id="50109-467">空の場合は、プロパティは変更されません。</span><span class="sxs-lookup"><span data-stu-id="50109-467">If empty, the property will remain unchanged.</span></span>
            </param>
        <param name="group">
            <span data-ttu-id="50109-468">ファイルまたはディレクトリのグループの所有者の AAD のオブジェクト ID。</span><span class="sxs-lookup"><span data-stu-id="50109-468">The AAD Object ID of the group owner of the file or directory.</span></span> <span data-ttu-id="50109-469">空の場合は、プロパティは変更されません。</span><span class="sxs-lookup"><span data-stu-id="50109-469">If empty, the property will remain unchanged.</span></span>
            </param>
        <summary>
            <span data-ttu-id="50109-470">ファイルまたはディレクトリの所有者を設定します。</span><span class="sxs-lookup"><span data-stu-id="50109-470">Sets the owner of a file or directory.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetOwnerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task SetOwnerAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string owner = null, string group = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task SetOwnerAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string owner, string group, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.SetOwnerAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SetOwnerAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.SetOwnerAsync (operations, accountName, path, owner, group, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;SetOwnerAsync&gt;d__43))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="owner" Type="System.String" />
        <Parameter Name="group" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="50109-471">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="50109-471">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="50109-472">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="50109-472">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="50109-473">Data Lake Store のパス (以降で '/') のファイルまたは所有者を設定する対象のディレクトリ。</span><span class="sxs-lookup"><span data-stu-id="50109-473">The Data Lake Store path (starting with '/') of the file or directory for which to set the owner.</span></span>
            </param>
        <param name="owner">
            <span data-ttu-id="50109-474">ファイルまたはディレクトリの所有者であるユーザーの AAD のオブジェクト ID。</span><span class="sxs-lookup"><span data-stu-id="50109-474">The AAD Object ID of the user owner of the file or directory.</span></span> <span data-ttu-id="50109-475">空の場合は、プロパティは変更されません。</span><span class="sxs-lookup"><span data-stu-id="50109-475">If empty, the property will remain unchanged.</span></span>
            </param>
        <param name="group">
            <span data-ttu-id="50109-476">ファイルまたはディレクトリのグループの所有者の AAD のオブジェクト ID。</span><span class="sxs-lookup"><span data-stu-id="50109-476">The AAD Object ID of the group owner of the file or directory.</span></span> <span data-ttu-id="50109-477">空の場合は、プロパティは変更されません。</span><span class="sxs-lookup"><span data-stu-id="50109-477">If empty, the property will remain unchanged.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="50109-478">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="50109-478">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="50109-479">ファイルまたはディレクトリの所有者を設定します。</span><span class="sxs-lookup"><span data-stu-id="50109-479">Sets the owner of a file or directory.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPermission">
      <MemberSignature Language="C#" Value="public static void SetPermission (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string permission = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void SetPermission(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string permission) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.SetPermission(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub SetPermission (operations As IFileSystemOperations, accountName As String, path As String, Optional permission As String = null)" />
      <MemberSignature Language="F#" Value="static member SetPermission : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.SetPermission (operations, accountName, path, permission)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="permission" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="50109-480">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="50109-480">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="50109-481">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="50109-481">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="50109-482">Data Lake Store のパス (以降で '/') のファイルまたはアクセス許可を設定する対象のディレクトリ。</span><span class="sxs-lookup"><span data-stu-id="50109-482">The Data Lake Store path (starting with '/') of the file or directory for which to set the permission.</span></span>
            </param>
        <param name="permission">
            <span data-ttu-id="50109-483">(つまり、アクセス許可の文字列表現</span><span class="sxs-lookup"><span data-stu-id="50109-483">A string representation of the permission (i.e</span></span> <span data-ttu-id="50109-484">rwx')。</span><span class="sxs-lookup"><span data-stu-id="50109-484">'rwx').</span></span> <span data-ttu-id="50109-485">空の場合、このプロパティは変更されません。</span><span class="sxs-lookup"><span data-stu-id="50109-485">If empty, this property remains unchanged.</span></span>
            </param>
        <summary>
            <span data-ttu-id="50109-486">ファイルまたはフォルダーのアクセス許可を設定します。</span><span class="sxs-lookup"><span data-stu-id="50109-486">Sets the permission of the file or folder.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPermissionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task SetPermissionAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string permission = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task SetPermissionAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string permission, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.SetPermissionAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SetPermissionAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.SetPermissionAsync (operations, accountName, path, permission, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;SetPermissionAsync&gt;d__45))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="permission" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="50109-487">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="50109-487">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="50109-488">ファイル システム操作を実行する Azure Data Lake Store アカウント。</span><span class="sxs-lookup"><span data-stu-id="50109-488">The Azure Data Lake Store account to execute filesystem operations on.</span></span>
            </param>
        <param name="path">
            <span data-ttu-id="50109-489">Data Lake Store のパス (以降で '/') のファイルまたはアクセス許可を設定する対象のディレクトリ。</span><span class="sxs-lookup"><span data-stu-id="50109-489">The Data Lake Store path (starting with '/') of the file or directory for which to set the permission.</span></span>
            </param>
        <param name="permission">
            <span data-ttu-id="50109-490">(つまり、アクセス許可の文字列表現</span><span class="sxs-lookup"><span data-stu-id="50109-490">A string representation of the permission (i.e</span></span> <span data-ttu-id="50109-491">rwx')。</span><span class="sxs-lookup"><span data-stu-id="50109-491">'rwx').</span></span> <span data-ttu-id="50109-492">空の場合、このプロパティは変更されません。</span><span class="sxs-lookup"><span data-stu-id="50109-492">If empty, this property remains unchanged.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="50109-493">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="50109-493">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="50109-494">ファイルまたはフォルダーのアクセス許可を設定します。</span><span class="sxs-lookup"><span data-stu-id="50109-494">Sets the permission of the file or folder.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>