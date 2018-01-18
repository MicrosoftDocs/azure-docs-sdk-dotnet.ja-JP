<Type Name="IFrontEndAdapter" FullName="Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter">
  <TypeSignature Language="C#" Value="public interface IFrontEndAdapter" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IFrontEndAdapter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter" />
  <TypeSignature Language="VB.NET" Value="Public Interface IFrontEndAdapter" />
  <TypeSignature Language="F#" Value="type IFrontEndAdapter = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5beda-101">DataLakeTransferClient が動作するために、フロント エンドから必要な操作を定義します。</span><span class="sxs-lookup"><span data-stu-id="5beda-101">Defines operations that the DataLakeTransferClient needs from the FrontEnd in order to operate</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AppendToStream">
      <MemberSignature Language="C#" Value="public void AppendToStream (string streamPath, byte[] data, long offset, int length);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void AppendToStream(string streamPath, unsigned int8[] data, int64 offset, int32 length) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter.AppendToStream(System.String,System.Byte[],System.Int64,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub AppendToStream (streamPath As String, data As Byte(), offset As Long, length As Integer)" />
      <MemberSignature Language="F#" Value="abstract member AppendToStream : string * byte[] * int64 * int -&gt; unit" Usage="iFrontEndAdapter.AppendToStream (streamPath, data, offset, length)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="streamPath" Type="System.String" />
        <Parameter Name="data" Type="System.Byte[]" />
        <Parameter Name="offset" Type="System.Int64" />
        <Parameter Name="length" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="streamPath"><span data-ttu-id="5beda-102">ストリームへの相対パスです。</span><span class="sxs-lookup"><span data-stu-id="5beda-102">The relative path to the stream.</span></span></param>
        <param name="data"><span data-ttu-id="5beda-103">ストリームに追加されるバイトの配列。</span><span class="sxs-lookup"><span data-stu-id="5beda-103">An array of bytes to be appended to the stream.</span></span></param>
        <param name="offset"><span data-ttu-id="5beda-104">ストリームに追加するオフセットです。</span><span class="sxs-lookup"><span data-stu-id="5beda-104">The offset at which to append to the stream.</span></span></param>
        <param name="length"><span data-ttu-id="5beda-105">(0 から始まる) を追加するバイト数。</span><span class="sxs-lookup"><span data-stu-id="5beda-105">The number of bytes to append (starting at 0).</span></span></param>
        <summary>
            <span data-ttu-id="5beda-106">指定されたストリームの末尾に指定したバイト配列を追加します。</span><span class="sxs-lookup"><span data-stu-id="5beda-106">Appends the given byte array to the end of a given stream.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="5beda-107">追加するデータが null または空の場合は。</span><span class="sxs-lookup"><span data-stu-id="5beda-107">If the data to be appended is null or empty.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Concatenate">
      <MemberSignature Language="C#" Value="public void Concatenate (string targetStreamPath, string[] inputStreamPaths, bool isDownload = false);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Concatenate(string targetStreamPath, string[] inputStreamPaths, bool isDownload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter.Concatenate(System.String,System.String[],System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Concatenate (targetStreamPath As String, inputStreamPaths As String(), Optional isDownload As Boolean = false)" />
      <MemberSignature Language="F#" Value="abstract member Concatenate : string * string[] * bool -&gt; unit" Usage="iFrontEndAdapter.Concatenate (targetStreamPath, inputStreamPaths, isDownload)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="targetStreamPath" Type="System.String" />
        <Parameter Name="inputStreamPaths" Type="System.String[]" />
        <Parameter Name="isDownload" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="targetStreamPath"><span data-ttu-id="5beda-108">対象のストリームへの相対パスです。</span><span class="sxs-lookup"><span data-stu-id="5beda-108">The relative path to the target stream.</span></span></param>
        <param name="inputStreamPaths"><span data-ttu-id="5beda-109">入力ストリームへのパスの順序付けされた配列。</span><span class="sxs-lookup"><span data-stu-id="5beda-109">An ordered array of paths to the input streams.</span></span></param>
        <param name="isDownload"><span data-ttu-id="5beda-110">場合に設定<c>true</c> [は download] で、サーバー上の代わりに、ローカル コンピューター上のストリームが連結されますおを意味します。</span><span class="sxs-lookup"><span data-stu-id="5beda-110">if set to <c>true</c> [is download], meaning we will concatenate the streams on the local machine instead of on the server.</span></span></param>
        <summary>
            <span data-ttu-id="5beda-111">指定された対象のストリームに (順序で) 指定された入力ストリームを連結します。</span><span class="sxs-lookup"><span data-stu-id="5beda-111">Concatenates the given input streams (in order) into the given target stream.</span></span>
            <span data-ttu-id="5beda-112">この操作の最後に、入力ストリームは削除されます。</span><span class="sxs-lookup"><span data-stu-id="5beda-112">At the end of this operation, input streams will be deleted.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateStream">
      <MemberSignature Language="C#" Value="public void CreateStream (string streamPath, bool overwrite, byte[] data, int byteCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void CreateStream(string streamPath, bool overwrite, unsigned int8[] data, int32 byteCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter.CreateStream(System.String,System.Boolean,System.Byte[],System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CreateStream (streamPath As String, overwrite As Boolean, data As Byte(), byteCount As Integer)" />
      <MemberSignature Language="F#" Value="abstract member CreateStream : string * bool * byte[] * int -&gt; unit" Usage="iFrontEndAdapter.CreateStream (streamPath, overwrite, data, byteCount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="streamPath" Type="System.String" />
        <Parameter Name="overwrite" Type="System.Boolean" />
        <Parameter Name="data" Type="System.Byte[]" />
        <Parameter Name="byteCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="streamPath"><span data-ttu-id="5beda-113">ストリームへの相対パスです。</span><span class="sxs-lookup"><span data-stu-id="5beda-113">The relative path to the stream.</span></span></param>
        <param name="overwrite"><span data-ttu-id="5beda-114">既存のストリームを上書きするかどうか。</span><span class="sxs-lookup"><span data-stu-id="5beda-114">Whether to overwrite an existing stream.</span></span></param>
        <param name="data"><span data-ttu-id="5beda-115">データ。</span><span class="sxs-lookup"><span data-stu-id="5beda-115">The data.</span></span></param>
        <param name="byteCount"><span data-ttu-id="5beda-116">バイト数。</span><span class="sxs-lookup"><span data-stu-id="5beda-116">The byte count.</span></span></param>
        <summary>
            <span data-ttu-id="5beda-117">指定されたパスに新しい、空のストリームを作成します。</span><span class="sxs-lookup"><span data-stu-id="5beda-117">Creates a new, empty stream at the given path.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteStream">
      <MemberSignature Language="C#" Value="public void DeleteStream (string streamPath, bool recurse = false, bool isDownload = false);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DeleteStream(string streamPath, bool recurse, bool isDownload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter.DeleteStream(System.String,System.Boolean,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteStream (streamPath As String, Optional recurse As Boolean = false, Optional isDownload As Boolean = false)" />
      <MemberSignature Language="F#" Value="abstract member DeleteStream : string * bool * bool -&gt; unit" Usage="iFrontEndAdapter.DeleteStream (streamPath, recurse, isDownload)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="streamPath" Type="System.String" />
        <Parameter Name="recurse" Type="System.Boolean" />
        <Parameter Name="isDownload" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="streamPath"><span data-ttu-id="5beda-118">ストリームへの相対パスです。</span><span class="sxs-lookup"><span data-stu-id="5beda-118">The relative path to the stream.</span></span></param>
        <param name="recurse"><span data-ttu-id="5beda-119">場合設定<c>true</c> [recurse] です。</span><span class="sxs-lookup"><span data-stu-id="5beda-119">if set to <c>true</c> [recurse].</span></span> <span data-ttu-id="5beda-120">これはフォルダー ストリームにのみ使用されます。</span><span class="sxs-lookup"><span data-stu-id="5beda-120">This is used for folder streams only.</span></span></param>
        <param name="isDownload"><span data-ttu-id="5beda-121">場合に設定<c>true</c> [ダウンロードは]、つまり、ローカル コンピューターの代わりに、サーバー上でストリームは削除されます。</span><span class="sxs-lookup"><span data-stu-id="5beda-121">if set to <c>true</c> [is download], meaning we will delete a stream on the local machine instead of on the server.</span></span></param>
        <summary>
            <span data-ttu-id="5beda-122">指定されたパスに既存のストリームを削除します。</span><span class="sxs-lookup"><span data-stu-id="5beda-122">Deletes an existing stream at the given path.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStreamLength">
      <MemberSignature Language="C#" Value="public long GetStreamLength (string streamPath, bool isDownload = false);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int64 GetStreamLength(string streamPath, bool isDownload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter.GetStreamLength(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetStreamLength (streamPath As String, Optional isDownload As Boolean = false) As Long" />
      <MemberSignature Language="F#" Value="abstract member GetStreamLength : string * bool -&gt; int64" Usage="iFrontEndAdapter.GetStreamLength (streamPath, isDownload)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="streamPath" Type="System.String" />
        <Parameter Name="isDownload" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="streamPath"><span data-ttu-id="5beda-123">ストリームへの相対パスです。</span><span class="sxs-lookup"><span data-stu-id="5beda-123">The relative path to the stream.</span></span></param>
        <param name="isDownload"><span data-ttu-id="5beda-124">場合に設定<c>true</c> [ダウンロードは]、つまり、ローカル コンピューター上の代わりに、サーバーにストリームの長さを紹介します。</span><span class="sxs-lookup"><span data-stu-id="5beda-124">if set to <c>true</c> [is download], meaning we will get the stream length on the local machine instead of on the server.</span></span></param>
        <summary>
            <span data-ttu-id="5beda-125">バイト単位のストリームの長さを示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="5beda-125">Gets a value indicating the length of a stream, in bytes.</span></span>
            </summary>
        <returns><span data-ttu-id="5beda-126">バイト単位のストリームの長さ。</span><span class="sxs-lookup"><span data-stu-id="5beda-126">The length of the stream, in bytes.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDirectory">
      <MemberSignature Language="C#" Value="public bool IsDirectory (string streamPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool IsDirectory(string streamPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter.IsDirectory(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function IsDirectory (streamPath As String) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member IsDirectory : string -&gt; bool" Usage="iFrontEndAdapter.IsDirectory streamPath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="streamPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="streamPath"><span data-ttu-id="5beda-127">ストリームへの相対パスです。</span><span class="sxs-lookup"><span data-stu-id="5beda-127">The relative path to the stream.</span></span></param>
        <summary>
            <span data-ttu-id="5beda-128">かどうかを使用してストリーム、サーバー上のパスが指定されたディレクトリまたは終端ファイル。</span><span class="sxs-lookup"><span data-stu-id="5beda-128">Determines if the stream with given path on the server is a directory or a terminating file.</span></span>
            <span data-ttu-id="5beda-129">これは、ダウンロード専用に使用します。</span><span class="sxs-lookup"><span data-stu-id="5beda-129">This is used exclusively for download.</span></span>
            </summary>
        <returns><span data-ttu-id="5beda-130">ストリームがディレクトリ、それ以外の場合に設定されている場合は true。</span><span class="sxs-lookup"><span data-stu-id="5beda-130">True if the stream is a directory, false otherwise.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListDirectory">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,long&gt; ListDirectory (string directoryPath, bool recursive);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IDictionary`2&lt;string, int64&gt; ListDirectory(string directoryPath, bool recursive) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter.ListDirectory(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function ListDirectory (directoryPath As String, recursive As Boolean) As IDictionary(Of String, Long)" />
      <MemberSignature Language="F#" Value="abstract member ListDirectory : string * bool -&gt; System.Collections.Generic.IDictionary&lt;string, int64&gt;" Usage="iFrontEndAdapter.ListDirectory (directoryPath, recursive)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="directoryPath" Type="System.String" />
        <Parameter Name="recursive" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="directoryPath"><span data-ttu-id="5beda-131">ディレクトリのパス。</span><span class="sxs-lookup"><span data-stu-id="5beda-131">The directory path.</span></span></param>
        <param name="recursive"><span data-ttu-id="5beda-132">場合設定<c>true</c> [再帰] です。</span><span class="sxs-lookup"><span data-stu-id="5beda-132">if set to <c>true</c> [recursive].</span></span></param>
        <summary>
            <span data-ttu-id="5beda-133">指定された Data Lake Store ディレクトリを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="5beda-133">Lists the Data Lake Store directory specified.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5beda-134">文字列のパスとその対応するファイルのサイズ、(バイト単位) の一覧。</span><span class="sxs-lookup"><span data-stu-id="5beda-134">The list of string paths and their corresponding file sizes, in bytes.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadStream">
      <MemberSignature Language="C#" Value="public System.IO.Stream ReadStream (string streamPath, long offset, long length, bool isDownload = false);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.IO.Stream ReadStream(string streamPath, int64 offset, int64 length, bool isDownload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter.ReadStream(System.String,System.Int64,System.Int64,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadStream (streamPath As String, offset As Long, length As Long, Optional isDownload As Boolean = false) As Stream" />
      <MemberSignature Language="F#" Value="abstract member ReadStream : string * int64 * int64 * bool -&gt; System.IO.Stream" Usage="iFrontEndAdapter.ReadStream (streamPath, offset, length, isDownload)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IO.Stream</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="streamPath" Type="System.String" />
        <Parameter Name="offset" Type="System.Int64" />
        <Parameter Name="length" Type="System.Int64" />
        <Parameter Name="isDownload" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="streamPath"><span data-ttu-id="5beda-135">ストリームへの相対パスです。</span><span class="sxs-lookup"><span data-stu-id="5beda-135">The relative path to the stream.</span></span></param>
        <param name="offset"><span data-ttu-id="5beda-136">ストリームに追加するオフセットです。</span><span class="sxs-lookup"><span data-stu-id="5beda-136">The offset at which to append to the stream.</span></span></param>
        <param name="length"><span data-ttu-id="5beda-137">(0 から始まる) を追加するバイト数。</span><span class="sxs-lookup"><span data-stu-id="5beda-137">The number of bytes to append (starting at 0).</span></span></param>
        <param name="isDownload"><span data-ttu-id="5beda-138">場合に設定<c>true</c> [ダウンロードは、] を読み取ったり、ローカル コンピューターではなくサーバーにストリームを開くことを意味します。</span><span class="sxs-lookup"><span data-stu-id="5beda-138">if set to <c>true</c> [is download], meaning we will open a stream on the server to read from, instead of the local machine.</span></span></param>
        <summary>
            <span data-ttu-id="5beda-139">指定された指定のストリームのパスを読み取るのためのストリームを開きます</span><span class="sxs-lookup"><span data-stu-id="5beda-139">Opens a stream for reading given the speficied stream path</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="5beda-140">追加するデータが null または空の場合は。</span><span class="sxs-lookup"><span data-stu-id="5beda-140">If the data to be appended is null or empty.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="StreamExists">
      <MemberSignature Language="C#" Value="public bool StreamExists (string streamPath, bool isDownload = false);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool StreamExists(string streamPath, bool isDownload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter.StreamExists(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function StreamExists (streamPath As String, Optional isDownload As Boolean = false) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member StreamExists : string * bool -&gt; bool" Usage="iFrontEndAdapter.StreamExists (streamPath, isDownload)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="streamPath" Type="System.String" />
        <Parameter Name="isDownload" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="streamPath"><span data-ttu-id="5beda-141">ストリームへの相対パスです。</span><span class="sxs-lookup"><span data-stu-id="5beda-141">The relative path to the stream.</span></span></param>
        <param name="isDownload"><span data-ttu-id="5beda-142">場合に設定<c>true</c> [は download] で、ローカル コンピューターの代わりに、サーバー上に、ストリームが存在する場合をテストします。 つまりです。</span><span class="sxs-lookup"><span data-stu-id="5beda-142">if set to <c>true</c> [is download], meaning we will test if the stream exists on the local machine instead of on the server.</span></span></param>
        <summary>
            <span data-ttu-id="5beda-143">かどうかをストリームが指定されたパスに存在します。</span><span class="sxs-lookup"><span data-stu-id="5beda-143">Determines if the stream with given path exists.</span></span>
            </summary>
        <returns><span data-ttu-id="5beda-144">ストリームが存在する場合、false それ以外の場合は true。</span><span class="sxs-lookup"><span data-stu-id="5beda-144">True if the stream exists, false otherwise.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>