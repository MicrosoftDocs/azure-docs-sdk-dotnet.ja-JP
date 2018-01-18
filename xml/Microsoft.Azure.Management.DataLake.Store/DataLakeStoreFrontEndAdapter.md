<Type Name="DataLakeStoreFrontEndAdapter" FullName="Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFrontEndAdapter">
  <TypeSignature Language="C#" Value="public class DataLakeStoreFrontEndAdapter : Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataLakeStoreFrontEndAdapter extends System.Object implements class Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFrontEndAdapter" />
  <TypeSignature Language="VB.NET" Value="Public Class DataLakeStoreFrontEndAdapter&#xA;Implements IFrontEndAdapter" />
  <TypeSignature Language="F#" Value="type DataLakeStoreFrontEndAdapter = class&#xA;    interface IFrontEndAdapter" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="51b35-101">DataLake ストアと通信し、フロント エンド アダプター。</span><span class="sxs-lookup"><span data-stu-id="51b35-101">A front end adapter that communicates with the DataLake Store.</span></span>
            <span data-ttu-id="51b35-102">これは、特定の効率性の制限があります、syncrhonous 呼び出しアダプターです。</span><span class="sxs-lookup"><span data-stu-id="51b35-102">This is a syncrhonous call adapter, which has certain efficiency limitations.</span></span>
            <span data-ttu-id="51b35-103">今後、作成される新しいアダプターは、メソッドを実装して非同期的に検討してください。</span><span class="sxs-lookup"><span data-stu-id="51b35-103">In the future, new adapters that are created should consider implementing the methods asynchronously.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeStoreFrontEndAdapter (string accountName, Microsoft.Azure.Management.DataLake.Store.IDataLakeStoreFileSystemManagementClient client);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string accountName, class Microsoft.Azure.Management.DataLake.Store.IDataLakeStoreFileSystemManagementClient client) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFrontEndAdapter.#ctor(System.String,Microsoft.Azure.Management.DataLake.Store.IDataLakeStoreFileSystemManagementClient)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (accountName As String, client As IDataLakeStoreFileSystemManagementClient)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFrontEndAdapter : string * Microsoft.Azure.Management.DataLake.Store.IDataLakeStoreFileSystemManagementClient -&gt; Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFrontEndAdapter" Usage="new Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFrontEndAdapter (accountName, client)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="client" Type="Microsoft.Azure.Management.DataLake.Store.IDataLakeStoreFileSystemManagementClient" />
      </Parameters>
      <Docs>
        <param name="accountName"><span data-ttu-id="51b35-104">アカウントの名前です。</span><span class="sxs-lookup"><span data-stu-id="51b35-104">Name of the account.</span></span></param>
        <param name="client"><span data-ttu-id="51b35-105">クライアントです。</span><span class="sxs-lookup"><span data-stu-id="51b35-105">The client.</span></span></param>
        <summary>
            <span data-ttu-id="51b35-106"><see cref="T:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFrontEndAdapter" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="51b35-106">Initializes a new instance of the <see cref="T:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFrontEndAdapter" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeStoreFrontEndAdapter (string accountName, Microsoft.Azure.Management.DataLake.Store.IDataLakeStoreFileSystemManagementClient client, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string accountName, class Microsoft.Azure.Management.DataLake.Store.IDataLakeStoreFileSystemManagementClient client, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFrontEndAdapter.#ctor(System.String,Microsoft.Azure.Management.DataLake.Store.IDataLakeStoreFileSystemManagementClient,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (accountName As String, client As IDataLakeStoreFileSystemManagementClient, token As CancellationToken)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFrontEndAdapter : string * Microsoft.Azure.Management.DataLake.Store.IDataLakeStoreFileSystemManagementClient * System.Threading.CancellationToken -&gt; Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFrontEndAdapter" Usage="new Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFrontEndAdapter (accountName, client, token)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="client" Type="Microsoft.Azure.Management.DataLake.Store.IDataLakeStoreFileSystemManagementClient" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName"><span data-ttu-id="51b35-107">アカウントの名前です。</span><span class="sxs-lookup"><span data-stu-id="51b35-107">Name of the account.</span></span></param>
        <param name="client"><span data-ttu-id="51b35-108">クライアントです。</span><span class="sxs-lookup"><span data-stu-id="51b35-108">The client.</span></span></param>
        <param name="token"><span data-ttu-id="51b35-109">トークン。</span><span class="sxs-lookup"><span data-stu-id="51b35-109">The token.</span></span></param>
        <summary>
            <span data-ttu-id="51b35-110"><see cref="T:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFrontEndAdapter" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="51b35-110">Initializes a new instance of the <see cref="T:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFrontEndAdapter" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppendToStream">
      <MemberSignature Language="C#" Value="public void AppendToStream (string streamPath, byte[] data, long offset, int byteCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void AppendToStream(string streamPath, unsigned int8[] data, int64 offset, int32 byteCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFrontEndAdapter.AppendToStream(System.String,System.Byte[],System.Int64,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub AppendToStream (streamPath As String, data As Byte(), offset As Long, byteCount As Integer)" />
      <MemberSignature Language="F#" Value="abstract member AppendToStream : string * byte[] * int64 * int -&gt; unit&#xA;override this.AppendToStream : string * byte[] * int64 * int -&gt; unit" Usage="dataLakeStoreFrontEndAdapter.AppendToStream (streamPath, data, offset, byteCount)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter.AppendToStream(System.String,System.Byte[],System.Int64,System.Int32)</InterfaceMember>
      </Implements>
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
        <Parameter Name="byteCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="streamPath"><span data-ttu-id="51b35-111">ストリームのパスです。</span><span class="sxs-lookup"><span data-stu-id="51b35-111">The stream path.</span></span></param>
        <param name="data"><span data-ttu-id="51b35-112">データ。</span><span class="sxs-lookup"><span data-stu-id="51b35-112">The data.</span></span></param>
        <param name="offset"><span data-ttu-id="51b35-113">オフセット。</span><span class="sxs-lookup"><span data-stu-id="51b35-113">The offset.</span></span></param>
        <param name="byteCount"><span data-ttu-id="51b35-114">バイト数。</span><span class="sxs-lookup"><span data-stu-id="51b35-114">The byte count.</span></span></param>
        <summary>
            <span data-ttu-id="51b35-115">ストリームに追加します。</span><span class="sxs-lookup"><span data-stu-id="51b35-115">Appends to stream.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Threading.Tasks.TaskCanceledException" />
      </Docs>
    </Member>
    <Member MemberName="Concatenate">
      <MemberSignature Language="C#" Value="public void Concatenate (string targetStreamPath, string[] inputStreamPaths, bool isDownload = false);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Concatenate(string targetStreamPath, string[] inputStreamPaths, bool isDownload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFrontEndAdapter.Concatenate(System.String,System.String[],System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Concatenate (targetStreamPath As String, inputStreamPaths As String(), Optional isDownload As Boolean = false)" />
      <MemberSignature Language="F#" Value="abstract member Concatenate : string * string[] * bool -&gt; unit&#xA;override this.Concatenate : string * string[] * bool -&gt; unit" Usage="dataLakeStoreFrontEndAdapter.Concatenate (targetStreamPath, inputStreamPaths, isDownload)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter.Concatenate(System.String,System.String[],System.Boolean)</InterfaceMember>
      </Implements>
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
        <param name="targetStreamPath"><span data-ttu-id="51b35-116">対象のストリームへの相対パスです。</span><span class="sxs-lookup"><span data-stu-id="51b35-116">The relative path to the target stream.</span></span></param>
        <param name="inputStreamPaths"><span data-ttu-id="51b35-117">入力ストリームへのパスの順序付けされた配列。</span><span class="sxs-lookup"><span data-stu-id="51b35-117">An ordered array of paths to the input streams.</span></span></param>
        <param name="isDownload"><span data-ttu-id="51b35-118">場合に設定<c>true</c> [は download] で、サーバー上の代わりに、ローカル コンピューター上のストリームが連結されますおを意味します。</span><span class="sxs-lookup"><span data-stu-id="51b35-118">if set to <c>true</c> [is download], meaning we will concatenate the streams on the local machine instead of on the server.</span></span></param>
        <summary>
            <span data-ttu-id="51b35-119">指定された対象のストリームに (順序で) 指定された入力ストリームを連結します。</span><span class="sxs-lookup"><span data-stu-id="51b35-119">Concatenates the given input streams (in order) into the given target stream.</span></span>
            <span data-ttu-id="51b35-120">この操作の最後に、入力ストリームは削除されます。</span><span class="sxs-lookup"><span data-stu-id="51b35-120">At the end of this operation, input streams will be deleted.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Threading.Tasks.TaskCanceledException" />
      </Docs>
    </Member>
    <Member MemberName="CreateStream">
      <MemberSignature Language="C#" Value="public void CreateStream (string streamPath, bool overwrite, byte[] data, int byteCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void CreateStream(string streamPath, bool overwrite, unsigned int8[] data, int32 byteCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFrontEndAdapter.CreateStream(System.String,System.Boolean,System.Byte[],System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CreateStream (streamPath As String, overwrite As Boolean, data As Byte(), byteCount As Integer)" />
      <MemberSignature Language="F#" Value="abstract member CreateStream : string * bool * byte[] * int -&gt; unit&#xA;override this.CreateStream : string * bool * byte[] * int -&gt; unit" Usage="dataLakeStoreFrontEndAdapter.CreateStream (streamPath, overwrite, data, byteCount)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter.CreateStream(System.String,System.Boolean,System.Byte[],System.Int32)</InterfaceMember>
      </Implements>
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
        <param name="streamPath"><span data-ttu-id="51b35-121">ストリームへの相対パスです。</span><span class="sxs-lookup"><span data-stu-id="51b35-121">The relative path to the stream.</span></span></param>
        <param name="overwrite"><span data-ttu-id="51b35-122">既存のストリームを上書きするかどうか。</span><span class="sxs-lookup"><span data-stu-id="51b35-122">Whether to overwrite an existing stream.</span></span></param>
        <param name="data"><span data-ttu-id="51b35-123">データ。</span><span class="sxs-lookup"><span data-stu-id="51b35-123">The data.</span></span></param>
        <param name="byteCount"><span data-ttu-id="51b35-124">バイト数。</span><span class="sxs-lookup"><span data-stu-id="51b35-124">The byte count.</span></span></param>
        <summary>
            <span data-ttu-id="51b35-125">指定されたパスに新しい、空のストリームを作成します。</span><span class="sxs-lookup"><span data-stu-id="51b35-125">Creates a new, empty stream at the given path.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Threading.Tasks.TaskCanceledException" />
      </Docs>
    </Member>
    <Member MemberName="DeleteStream">
      <MemberSignature Language="C#" Value="public void DeleteStream (string streamPath, bool recurse = false, bool isDownload = false);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DeleteStream(string streamPath, bool recurse, bool isDownload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFrontEndAdapter.DeleteStream(System.String,System.Boolean,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteStream (streamPath As String, Optional recurse As Boolean = false, Optional isDownload As Boolean = false)" />
      <MemberSignature Language="F#" Value="abstract member DeleteStream : string * bool * bool -&gt; unit&#xA;override this.DeleteStream : string * bool * bool -&gt; unit" Usage="dataLakeStoreFrontEndAdapter.DeleteStream (streamPath, recurse, isDownload)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter.DeleteStream(System.String,System.Boolean,System.Boolean)</InterfaceMember>
      </Implements>
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
        <param name="streamPath"><span data-ttu-id="51b35-126">ストリームへの相対パスです。</span><span class="sxs-lookup"><span data-stu-id="51b35-126">The relative path to the stream.</span></span></param>
        <param name="recurse"><span data-ttu-id="51b35-127">場合設定<c>true</c> [recurse] です。</span><span class="sxs-lookup"><span data-stu-id="51b35-127">if set to <c>true</c> [recurse].</span></span> <span data-ttu-id="51b35-128">これはフォルダー ストリームにのみ使用されます。</span><span class="sxs-lookup"><span data-stu-id="51b35-128">This is used for folder streams only.</span></span></param>
        <param name="isDownload"><span data-ttu-id="51b35-129">場合に設定<c>true</c> [ダウンロードは]、つまり、ローカル コンピューターの代わりに、サーバー上でストリームは削除されます。</span><span class="sxs-lookup"><span data-stu-id="51b35-129">if set to <c>true</c> [is download], meaning we will delete a stream on the local machine instead of on the server.</span></span></param>
        <summary>
            <span data-ttu-id="51b35-130">指定されたパスに既存のストリームを削除します。</span><span class="sxs-lookup"><span data-stu-id="51b35-130">Deletes an existing stream at the given path.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Threading.Tasks.TaskCanceledException" />
      </Docs>
    </Member>
    <Member MemberName="GetStreamLength">
      <MemberSignature Language="C#" Value="public long GetStreamLength (string streamPath, bool isDownload = false);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int64 GetStreamLength(string streamPath, bool isDownload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFrontEndAdapter.GetStreamLength(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetStreamLength (streamPath As String, Optional isDownload As Boolean = false) As Long" />
      <MemberSignature Language="F#" Value="abstract member GetStreamLength : string * bool -&gt; int64&#xA;override this.GetStreamLength : string * bool -&gt; int64" Usage="dataLakeStoreFrontEndAdapter.GetStreamLength (streamPath, isDownload)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter.GetStreamLength(System.String,System.Boolean)</InterfaceMember>
      </Implements>
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
        <param name="streamPath"><span data-ttu-id="51b35-131">ストリームへの相対パスです。</span><span class="sxs-lookup"><span data-stu-id="51b35-131">The relative path to the stream.</span></span></param>
        <param name="isDownload"><span data-ttu-id="51b35-132">場合に設定<c>true</c> [ダウンロードは]、つまり、ローカル コンピューター上の代わりに、サーバーにストリームの長さを紹介します。</span><span class="sxs-lookup"><span data-stu-id="51b35-132">if set to <c>true</c> [is download], meaning we will get the stream length on the local machine instead of on the server.</span></span></param>
        <summary>
            <span data-ttu-id="51b35-133">バイト単位のストリームの長さを示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="51b35-133">Gets a value indicating the length of a stream, in bytes.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="51b35-134">バイト単位のストリームの長さ。</span><span class="sxs-lookup"><span data-stu-id="51b35-134">The length of the stream, in bytes.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Threading.Tasks.TaskCanceledException" />
      </Docs>
    </Member>
    <Member MemberName="IsDirectory">
      <MemberSignature Language="C#" Value="public bool IsDirectory (string streamPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool IsDirectory(string streamPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFrontEndAdapter.IsDirectory(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function IsDirectory (streamPath As String) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member IsDirectory : string -&gt; bool&#xA;override this.IsDirectory : string -&gt; bool" Usage="dataLakeStoreFrontEndAdapter.IsDirectory streamPath" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter.IsDirectory(System.String)</InterfaceMember>
      </Implements>
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
        <param name="streamPath"><span data-ttu-id="51b35-135">ストリームへの相対パスです。</span><span class="sxs-lookup"><span data-stu-id="51b35-135">The relative path to the stream.</span></span></param>
        <summary>
            <span data-ttu-id="51b35-136">かどうかを使用してストリーム、サーバー上のパスが指定されたディレクトリまたは終端ファイル。</span><span class="sxs-lookup"><span data-stu-id="51b35-136">Determines if the stream with given path on the server is a directory or a terminating file.</span></span>
            <span data-ttu-id="51b35-137">これは、ダウンロード専用に使用します。</span><span class="sxs-lookup"><span data-stu-id="51b35-137">This is used exclusively for download.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="51b35-138">ストリームがディレクトリ、それ以外の場合に設定されている場合は true。</span><span class="sxs-lookup"><span data-stu-id="51b35-138">True if the stream is a directory, false otherwise.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Threading.Tasks.TaskCanceledException" />
      </Docs>
    </Member>
    <Member MemberName="ListDirectory">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,long&gt; ListDirectory (string directoryPath, bool recursive);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IDictionary`2&lt;string, int64&gt; ListDirectory(string directoryPath, bool recursive) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFrontEndAdapter.ListDirectory(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function ListDirectory (directoryPath As String, recursive As Boolean) As IDictionary(Of String, Long)" />
      <MemberSignature Language="F#" Value="abstract member ListDirectory : string * bool -&gt; System.Collections.Generic.IDictionary&lt;string, int64&gt;&#xA;override this.ListDirectory : string * bool -&gt; System.Collections.Generic.IDictionary&lt;string, int64&gt;" Usage="dataLakeStoreFrontEndAdapter.ListDirectory (directoryPath, recursive)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter.ListDirectory(System.String,System.Boolean)</InterfaceMember>
      </Implements>
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
        <param name="directoryPath"><span data-ttu-id="51b35-139">ディレクトリのパス。</span><span class="sxs-lookup"><span data-stu-id="51b35-139">The directory path.</span></span></param>
        <param name="recursive"><span data-ttu-id="51b35-140">場合設定<c>true</c> [再帰] です。</span><span class="sxs-lookup"><span data-stu-id="51b35-140">if set to <c>true</c> [recursive].</span></span></param>
        <summary>
            <span data-ttu-id="51b35-141">指定された Data Lake Store ディレクトリを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="51b35-141">Lists the Data Lake Store directory specified.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="51b35-142">文字列のパスとその対応するファイルのサイズ、(バイト単位) の一覧。</span><span class="sxs-lookup"><span data-stu-id="51b35-142">The list of string paths and their corresponding file sizes, in bytes.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadStream">
      <MemberSignature Language="C#" Value="public System.IO.Stream ReadStream (string streamPath, long offset, long length, bool isDownload = false);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.IO.Stream ReadStream(string streamPath, int64 offset, int64 length, bool isDownload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFrontEndAdapter.ReadStream(System.String,System.Int64,System.Int64,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadStream (streamPath As String, offset As Long, length As Long, Optional isDownload As Boolean = false) As Stream" />
      <MemberSignature Language="F#" Value="abstract member ReadStream : string * int64 * int64 * bool -&gt; System.IO.Stream&#xA;override this.ReadStream : string * int64 * int64 * bool -&gt; System.IO.Stream" Usage="dataLakeStoreFrontEndAdapter.ReadStream (streamPath, offset, length, isDownload)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter.ReadStream(System.String,System.Int64,System.Int64,System.Boolean)</InterfaceMember>
      </Implements>
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
        <param name="streamPath">To be added.</param>
        <param name="offset">To be added.</param>
        <param name="length">To be added.</param>
        <param name="isDownload">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StreamExists">
      <MemberSignature Language="C#" Value="public bool StreamExists (string streamPath, bool isDownload = false);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool StreamExists(string streamPath, bool isDownload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFrontEndAdapter.StreamExists(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function StreamExists (streamPath As String, Optional isDownload As Boolean = false) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member StreamExists : string * bool -&gt; bool&#xA;override this.StreamExists : string * bool -&gt; bool" Usage="dataLakeStoreFrontEndAdapter.StreamExists (streamPath, isDownload)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter.StreamExists(System.String,System.Boolean)</InterfaceMember>
      </Implements>
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
        <param name="streamPath"><span data-ttu-id="51b35-143">ストリームへの相対パスです。</span><span class="sxs-lookup"><span data-stu-id="51b35-143">The relative path to the stream.</span></span></param>
        <param name="isDownload"><span data-ttu-id="51b35-144">場合に設定<c>true</c> [は download] で、ローカル コンピューターの代わりに、サーバー上に、ストリームが存在する場合をテストします。 つまりです。</span><span class="sxs-lookup"><span data-stu-id="51b35-144">if set to <c>true</c> [is download], meaning we will test if the stream exists on the local machine instead of on the server.</span></span></param>
        <summary>
            <span data-ttu-id="51b35-145">かどうかをストリームが指定されたパスに存在します。</span><span class="sxs-lookup"><span data-stu-id="51b35-145">Determines if the stream with given path exists.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="51b35-146">ストリームが存在する場合、false それ以外の場合は true。</span><span class="sxs-lookup"><span data-stu-id="51b35-146">True if the stream exists, false otherwise.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Threading.Tasks.TaskCanceledException" />
      </Docs>
    </Member>
  </Members>
</Type>