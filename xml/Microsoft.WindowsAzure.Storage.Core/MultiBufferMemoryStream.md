<Type Name="MultiBufferMemoryStream" FullName="Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream">
  <TypeSignature Language="C#" Value="public class MultiBufferMemoryStream : System.IO.Stream" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MultiBufferMemoryStream extends System.IO.Stream" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream" />
  <TypeSignature Language="VB.NET" Value="Public Class MultiBufferMemoryStream&#xA;Inherits Stream" />
  <TypeSignature Language="F#" Value="type MultiBufferMemoryStream = class&#xA;    inherit Stream" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.IO.Stream</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="56c3d-101">バッキング ストアとしてメモリ マルチバッファー ストリームを作成します。</span><span class="sxs-lookup"><span data-stu-id="56c3d-101">Creates a multi-buffer stream whose backing store is memory.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiBufferMemoryStream (Microsoft.WindowsAzure.Storage.IBufferManager bufferManager, int bufferSize = 65536);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.IBufferManager bufferManager, int32 bufferSize) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream.#ctor(Microsoft.WindowsAzure.Storage.IBufferManager,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (bufferManager As IBufferManager, Optional bufferSize As Integer = 65536)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream : Microsoft.WindowsAzure.Storage.IBufferManager * int -&gt; Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream" Usage="new Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream (bufferManager, bufferSize)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="bufferManager" Type="Microsoft.WindowsAzure.Storage.IBufferManager" />
        <Parameter Name="bufferSize" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="bufferManager"><span data-ttu-id="56c3d-102"><see cref="T:Microsoft.WindowsAzure.Storage.IBufferManager" />取得およびストリームのバッファーを返すために使用します。</span><span class="sxs-lookup"><span data-stu-id="56c3d-102">The <see cref="T:Microsoft.WindowsAzure.Storage.IBufferManager" /> to use to acquire and return buffers for the stream.</span></span> <span data-ttu-id="56c3d-103">あります<c>null</c>です。</span><span class="sxs-lookup"><span data-stu-id="56c3d-103">May be <c>null</c>.</span></span></param>
        <param name="bufferSize"><span data-ttu-id="56c3d-104">各ブロックを使用するバッファー サイズ。</span><span class="sxs-lookup"><span data-stu-id="56c3d-104">The buffer size to use for each block.</span></span> <span data-ttu-id="56c3d-105">既定のサイズは、64 KB です。</span><span class="sxs-lookup"><span data-stu-id="56c3d-105">The default size is 64 KB.</span></span> <span data-ttu-id="56c3d-106">このパラメーターは無視する場合に、<see cref="T:Microsoft.WindowsAzure.Storage.IBufferManager" />が指定されています。</span><span class="sxs-lookup"><span data-stu-id="56c3d-106">Note that this parameter is disregarded when an <see cref="T:Microsoft.WindowsAzure.Storage.IBufferManager" /> is specified.</span></span></param>
        <summary>
             <span data-ttu-id="56c3d-107">新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream" />指定されたバッファー マネージャーを持つクラス。</span><span class="sxs-lookup"><span data-stu-id="56c3d-107">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream" /> class with the specified buffer manager.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginFastCopyTo">
      <MemberSignature Language="C#" Value="public IAsyncResult BeginFastCopyTo (System.IO.Stream destination, Nullable&lt;DateTime&gt; expiryTime, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.IAsyncResult BeginFastCopyTo(class System.IO.Stream destination, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; expiryTime, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream.BeginFastCopyTo(System.IO.Stream,System.Nullable{System.DateTime},System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function BeginFastCopyTo (destination As Stream, expiryTime As Nullable(Of DateTime), callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="member this.BeginFastCopyTo : System.IO.Stream * Nullable&lt;DateTime&gt; * AsyncCallback * obj -&gt; IAsyncResult" Usage="multiBufferMemoryStream.BeginFastCopyTo (destination, expiryTime, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="destination" Type="System.IO.Stream" />
        <Parameter Name="expiryTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="destination"><span data-ttu-id="56c3d-108">現在のストリームの内容のコピー先のストリーム。</span><span class="sxs-lookup"><span data-stu-id="56c3d-108">The stream to which the contents of the current stream will be copied.</span></span></param>
        <param name="expiryTime"><span data-ttu-id="56c3d-109">有効期限の日時を示す DateTime です。</span><span class="sxs-lookup"><span data-stu-id="56c3d-109">DateTime indicating the expiry time.</span></span></param>
        <param name="callback"><span data-ttu-id="56c3d-110">コピーが完了するときに呼び出されるオプションの非同期コールバック。</span><span class="sxs-lookup"><span data-stu-id="56c3d-110">An optional asynchronous callback, to be called when the copy is complete.</span></span></param>
        <param name="state"><span data-ttu-id="56c3d-111">この特定の非同期コピー要求を他の要求と区別するユーザー指定のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="56c3d-111">A user-provided object that distinguishes this particular asynchronous copy request from other requests.</span></span></param>
        <summary>
            <span data-ttu-id="56c3d-112">非同期の高速コピー操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="56c3d-112">Begins an asynchronous fast-copy operation.</span></span>
            </summary>
        <returns><span data-ttu-id="56c3d-113">非同期のコピーは、保留になっていることを表す IAsyncResult。</span><span class="sxs-lookup"><span data-stu-id="56c3d-113">An IAsyncResult that represents the asynchronous copy, which could still be pending.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRead">
      <MemberSignature Language="C#" Value="public override IAsyncResult BeginRead (byte[] buffer, int offset, int count, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.IAsyncResult BeginRead(unsigned int8[] buffer, int32 offset, int32 count, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream.BeginRead(System.Byte[],System.Int32,System.Int32,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function BeginRead (buffer As Byte(), offset As Integer, count As Integer, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.BeginRead : byte[] * int * int * AsyncCallback * obj -&gt; IAsyncResult" Usage="multiBufferMemoryStream.BeginRead (buffer, offset, count, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="buffer" Type="System.Byte[]" />
        <Parameter Name="offset" Type="System.Int32" />
        <Parameter Name="count" Type="System.Int32" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="buffer"><span data-ttu-id="56c3d-114">このメソッドが返されるとき、バッファーは現在のソースから読み取ったバイトにより置き換えられた、オフセットから (オフセット + データの個数 - 1) の間の値を持つ指定されたバイト配列を含みます。</span><span class="sxs-lookup"><span data-stu-id="56c3d-114">When this method returns, the buffer contains the specified byte array with the values between offset and (offset + count - 1) replaced by the bytes read from the current source.</span></span></param>
        <param name="offset"><span data-ttu-id="56c3d-115">現在のストリームから読み取ったデータの格納を開始する位置を示す バッファ内の0 から始まるバイト オフセット。</span><span class="sxs-lookup"><span data-stu-id="56c3d-115">The zero-based byte offset in buffer at which to begin storing the data read from the current stream.</span></span></param>
        <param name="count"><span data-ttu-id="56c3d-116">読み取るバイトの最大数。</span><span class="sxs-lookup"><span data-stu-id="56c3d-116">The maximum number of bytes to be read.</span></span></param>
        <param name="callback"><span data-ttu-id="56c3d-117">読み取り完了時に呼び出されるオプションの非同期コールバック。</span><span class="sxs-lookup"><span data-stu-id="56c3d-117">An optional asynchronous callback, to be called when the read is complete.</span></span></param>
        <param name="state"><span data-ttu-id="56c3d-118">この特定の非同期読み取り要求を他の要求と区別するために使用するユーザー指定のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="56c3d-118">A user-provided object that distinguishes this particular asynchronous read request from other requests.</span></span></param>
        <summary>
            <span data-ttu-id="56c3d-119">非同期の読み込み動作を開始します。</span><span class="sxs-lookup"><span data-stu-id="56c3d-119">Begins an asynchronous read operation.</span></span>
            </summary>
        <returns><span data-ttu-id="56c3d-120">非同期の読み取りは、保留になっていることを表す IAsyncResult。</span><span class="sxs-lookup"><span data-stu-id="56c3d-120">An IAsyncResult that represents the asynchronous read, which could still be pending.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginWrite">
      <MemberSignature Language="C#" Value="public override IAsyncResult BeginWrite (byte[] buffer, int offset, int count, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.IAsyncResult BeginWrite(unsigned int8[] buffer, int32 offset, int32 count, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream.BeginWrite(System.Byte[],System.Int32,System.Int32,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function BeginWrite (buffer As Byte(), offset As Integer, count As Integer, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.BeginWrite : byte[] * int * int * AsyncCallback * obj -&gt; IAsyncResult" Usage="multiBufferMemoryStream.BeginWrite (buffer, offset, count, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="buffer" Type="System.Byte[]" />
        <Parameter Name="offset" Type="System.Int32" />
        <Parameter Name="count" Type="System.Int32" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="buffer"><span data-ttu-id="56c3d-121">データの書き込み元となるバッファー。</span><span class="sxs-lookup"><span data-stu-id="56c3d-121">The buffer to write data from.</span></span></param>
        <param name="offset"><span data-ttu-id="56c3d-122">現在のストリームにバイトのコピーを開始する位置を示すバッファー内の 0 から始まるバイト オフセット。</span><span class="sxs-lookup"><span data-stu-id="56c3d-122">The zero-based byte offset in buffer at which to begin copying bytes to the current stream.</span></span></param>
        <param name="count"><span data-ttu-id="56c3d-123">書き込むバイト数。</span><span class="sxs-lookup"><span data-stu-id="56c3d-123">The number of bytes to write.</span></span></param>
        <param name="callback"><span data-ttu-id="56c3d-124">書き込みの完了時に呼び出されるオプションの非同期コールバック。</span><span class="sxs-lookup"><span data-stu-id="56c3d-124">An optional asynchronous callback, to be called when the write is complete.</span></span></param>
        <param name="state"><span data-ttu-id="56c3d-125">この特定の非同期書き込み要求を他の要求と区別するために使用するユーザー指定のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="56c3d-125">A user-provided object that distinguishes this particular asynchronous write request from other requests.</span></span></param>
        <summary>
            <span data-ttu-id="56c3d-126">非同期の書き込み操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="56c3d-126">Begins an asynchronous write operation.</span></span>
            </summary>
        <returns><span data-ttu-id="56c3d-127">保留になっている可能性があります、非同期の書き込みを表す IAsyncResult。</span><span class="sxs-lookup"><span data-stu-id="56c3d-127">An IAsyncResult that represents the asynchronous write, which could still be pending.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanRead">
      <MemberSignature Language="C#" Value="public override bool CanRead { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool CanRead" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream.CanRead" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property CanRead As Boolean" />
      <MemberSignature Language="F#" Value="member this.CanRead : bool" Usage="Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream.CanRead" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="56c3d-128">現在のストリームが読み取りをサポートしているかどうかを示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="56c3d-128">Gets a value indicating whether the current stream supports reading.</span></span>
            </summary>
        <value>
          <span data-ttu-id="56c3d-129"><c>true</c>ストリームが読み取りをサポートする場合はそれ以外の場合、 <c>false</c>です。</span><span class="sxs-lookup"><span data-stu-id="56c3d-129"><c>true</c> if the stream supports reading; otherwise, <c>false</c>.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanSeek">
      <MemberSignature Language="C#" Value="public override bool CanSeek { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool CanSeek" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream.CanSeek" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property CanSeek As Boolean" />
      <MemberSignature Language="F#" Value="member this.CanSeek : bool" Usage="Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream.CanSeek" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="56c3d-130">現在のストリームがシークをサポートしているかどうかを示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="56c3d-130">Gets a value indicating whether the current stream supports seeking.</span></span>
            </summary>
        <value>
          <span data-ttu-id="56c3d-131"><c>true</c>ストリームがシークをサポートする場合はそれ以外の場合、 <c>false</c>です。</span><span class="sxs-lookup"><span data-stu-id="56c3d-131"><c>true</c> if the stream supports seeking; otherwise, <c>false</c>.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanWrite">
      <MemberSignature Language="C#" Value="public override bool CanWrite { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool CanWrite" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream.CanWrite" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property CanWrite As Boolean" />
      <MemberSignature Language="F#" Value="member this.CanWrite : bool" Usage="Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream.CanWrite" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="56c3d-132">現在のストリームが書き込みをサポートしているかどうかを示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="56c3d-132">Gets a value indicating whether the current stream supports writing.</span></span>
            </summary>
        <value>
          <span data-ttu-id="56c3d-133"><c>true</c>ストリームが書き込みをサポートする場合はそれ以外の場合、 <c>false</c>です。</span><span class="sxs-lookup"><span data-stu-id="56c3d-133"><c>true</c> if the stream supports writing; otherwise, <c>false</c>.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ComputeMD5Hash">
      <MemberSignature Language="C#" Value="public string ComputeMD5Hash ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string ComputeMD5Hash() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream.ComputeMD5Hash" />
      <MemberSignature Language="VB.NET" Value="Public Function ComputeMD5Hash () As String" />
      <MemberSignature Language="F#" Value="member this.ComputeMD5Hash : unit -&gt; string" Usage="multiBufferMemoryStream.ComputeMD5Hash " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="56c3d-134">このストリームのハッシュ値を計算します。</span><span class="sxs-lookup"><span data-stu-id="56c3d-134">Computes the hash value for this stream.</span></span>
            </summary>
        <returns><span data-ttu-id="56c3d-135">計算されたハッシュ値の文字列表現。</span><span class="sxs-lookup"><span data-stu-id="56c3d-135">String representation of the computed hash value.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="protected override void Dispose (bool disposing);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void Dispose(bool disposing) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream.Dispose(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub Dispose (disposing As Boolean)" />
      <MemberSignature Language="F#" Value="override this.Dispose : bool -&gt; unit" Usage="multiBufferMemoryStream.Dispose disposing" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disposing" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="disposing"><span data-ttu-id="56c3d-136">マネージ リソースとアンマネージ リソースの両方を解放する場合は true、アンマネージ リソースだけを解放する場合は false。</span><span class="sxs-lookup"><span data-stu-id="56c3d-136">true to release both managed and unmanaged resources; false to release only unmanaged resources.</span></span></param>
        <summary>
            <span data-ttu-id="56c3d-137">
                      <see cref="T:Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream" /> によって使用されているすべてのリソースを解放します。</span><span class="sxs-lookup"><span data-stu-id="56c3d-137">Releases all resources used by the <see cref="T:Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream" />.</span></span>
</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndFastCopyTo">
      <MemberSignature Language="C#" Value="public void EndFastCopyTo (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void EndFastCopyTo(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream.EndFastCopyTo(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Sub EndFastCopyTo (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="member this.EndFastCopyTo : IAsyncResult -&gt; unit" Usage="multiBufferMemoryStream.EndFastCopyTo asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="56c3d-138">終了させる保留状態の非同期リクエストへの参照。</span><span class="sxs-lookup"><span data-stu-id="56c3d-138">The reference to the pending asynchronous request to finish.</span></span></param>
        <summary>
            <span data-ttu-id="56c3d-139">非同期のコピー操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="56c3d-139">Ends an asynchronous copy operation.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndRead">
      <MemberSignature Language="C#" Value="public override int EndRead (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 EndRead(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream.EndRead(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function EndRead (asyncResult As IAsyncResult) As Integer" />
      <MemberSignature Language="F#" Value="override this.EndRead : IAsyncResult -&gt; int" Usage="multiBufferMemoryStream.EndRead asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="56c3d-140">終了させる保留状態の非同期リクエストへの参照。</span><span class="sxs-lookup"><span data-stu-id="56c3d-140">The reference to the pending asynchronous request to finish.</span></span></param>
        <summary>
            <span data-ttu-id="56c3d-141">保留中の非同期読み取りが完了するまで待機します。</span><span class="sxs-lookup"><span data-stu-id="56c3d-141">Waits for the pending asynchronous read to complete.</span></span>
            </summary>
        <returns><span data-ttu-id="56c3d-142">バッファーに読み取られた合計バイト数。</span><span class="sxs-lookup"><span data-stu-id="56c3d-142">The total number of bytes read into the buffer.</span></span> <span data-ttu-id="56c3d-143">要求されたバイト数をその時点で読み取れなかった場合、この値は要求されたバイト数より小さくなることがあります。ストリームの末尾に達していた場合は 0 になります。</span><span class="sxs-lookup"><span data-stu-id="56c3d-143">This can be less than the number of bytes requested if that many bytes are not currently available, or zero if the end of the stream has been reached.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndWrite">
      <MemberSignature Language="C#" Value="public override void EndWrite (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void EndWrite(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream.EndWrite(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub EndWrite (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.EndWrite : IAsyncResult -&gt; unit" Usage="multiBufferMemoryStream.EndWrite asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="56c3d-144">終了させる保留状態の非同期リクエストへの参照。</span><span class="sxs-lookup"><span data-stu-id="56c3d-144">The reference to the pending asynchronous request to finish.</span></span></param>
        <summary>
            <span data-ttu-id="56c3d-145">非同期書き込み操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="56c3d-145">Ends an asynchronous write operation.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FastCopyTo">
      <MemberSignature Language="C#" Value="public void FastCopyTo (System.IO.Stream destination, Nullable&lt;DateTime&gt; expiryTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void FastCopyTo(class System.IO.Stream destination, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; expiryTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream.FastCopyTo(System.IO.Stream,System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub FastCopyTo (destination As Stream, expiryTime As Nullable(Of DateTime))" />
      <MemberSignature Language="F#" Value="member this.FastCopyTo : System.IO.Stream * Nullable&lt;DateTime&gt; -&gt; unit" Usage="multiBufferMemoryStream.FastCopyTo (destination, expiryTime)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="destination" Type="System.IO.Stream" />
        <Parameter Name="expiryTime" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="destination"><span data-ttu-id="56c3d-146">現在のストリームの内容のコピー先のストリーム。</span><span class="sxs-lookup"><span data-stu-id="56c3d-146">The stream to which the contents of the current stream will be copied.</span></span></param>
        <param name="expiryTime"><span data-ttu-id="56c3d-147">有効期限の日時を示す DateTime です。</span><span class="sxs-lookup"><span data-stu-id="56c3d-147">A DateTime indicating the expiry time.</span></span></param>
        <summary>
            <span data-ttu-id="56c3d-148">現在のストリームからバイトを読み取り、別のストリームに書き込みます。</span><span class="sxs-lookup"><span data-stu-id="56c3d-148">Reads the bytes from the current stream and writes them to another stream.</span></span> <span data-ttu-id="56c3d-149">このメソッドは、一時バッファーにデータをコピーするのではなく、コピー先のストリームに直接書き込みます。</span><span class="sxs-lookup"><span data-stu-id="56c3d-149">This method writes directly to the destination stream, rather than copying the data into a temporary buffer.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Flush">
      <MemberSignature Language="C#" Value="public override void Flush ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Flush() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream.Flush" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Flush ()" />
      <MemberSignature Language="F#" Value="override this.Flush : unit -&gt; unit" Usage="multiBufferMemoryStream.Flush " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="56c3d-150">ストリームがメモリ内ストリームとして、任意の操作は実行されません。</span><span class="sxs-lookup"><span data-stu-id="56c3d-150">Does not perform any operation, as the stream is an in-memory stream.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Length">
      <MemberSignature Language="C#" Value="public override long Length { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Length" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream.Length" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property Length As Long" />
      <MemberSignature Language="F#" Value="member this.Length : int64" Usage="Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream.Length" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="56c3d-151">ストリーム長 (バイト単位) を取得します。</span><span class="sxs-lookup"><span data-stu-id="56c3d-151">Gets the length in bytes of the stream.</span></span>
            </summary>
        <value><span data-ttu-id="56c3d-152">ストリーム長 (バイト単位) を表す long 値。</span><span class="sxs-lookup"><span data-stu-id="56c3d-152">A long value representing the length of the stream in bytes.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Position">
      <MemberSignature Language="C#" Value="public override long Position { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Position" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream.Position" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Property Position As Long" />
      <MemberSignature Language="F#" Value="member this.Position : int64 with get, set" Usage="Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream.Position" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="56c3d-153">現在のストリーム内の位置を取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="56c3d-153">Gets or sets the position within the current stream.</span></span>
            </summary>
        <value><span data-ttu-id="56c3d-154">ストリーム内の現在位置。</span><span class="sxs-lookup"><span data-stu-id="56c3d-154">The current position within the stream.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Read">
      <MemberSignature Language="C#" Value="public override int Read (byte[] buffer, int offset, int count);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 Read(unsigned int8[] buffer, int32 offset, int32 count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream.Read(System.Byte[],System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Read (buffer As Byte(), offset As Integer, count As Integer) As Integer" />
      <MemberSignature Language="F#" Value="override this.Read : byte[] * int * int -&gt; int" Usage="multiBufferMemoryStream.Read (buffer, offset, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="buffer" Type="System.Byte[]" />
        <Parameter Name="offset" Type="System.Int32" />
        <Parameter Name="count" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="buffer"><span data-ttu-id="56c3d-155">このメソッドが返されるとき、バッファーは現在のソースから読み取ったバイトにより置き換えられた、オフセットから (オフセット + データの個数 - 1) の間の値を持つ指定されたバイト配列を含みます。</span><span class="sxs-lookup"><span data-stu-id="56c3d-155">When this method returns, the buffer contains the specified byte array with the values between offset and (offset + count - 1) replaced by the bytes read from the current source.</span></span></param>
        <param name="offset"><span data-ttu-id="56c3d-156">現在のストリームから読み取ったデータの格納を開始する位置を示す バッファ内の0 から始まるバイト オフセット。</span><span class="sxs-lookup"><span data-stu-id="56c3d-156">The zero-based byte offset in buffer at which to begin storing the data read from the current stream.</span></span></param>
        <param name="count"><span data-ttu-id="56c3d-157">読み取るバイトの最大数。</span><span class="sxs-lookup"><span data-stu-id="56c3d-157">The maximum number of bytes to be read.</span></span></param>
        <summary>
            <span data-ttu-id="56c3d-158">現在のストリームからバイトのブロックを読み取り、データをバッファーに書き込みます。</span><span class="sxs-lookup"><span data-stu-id="56c3d-158">Reads a block of bytes from the current stream and writes the data to a buffer.</span></span>
            </summary>
        <returns><span data-ttu-id="56c3d-159">バッファーに読み取られた合計バイト数。</span><span class="sxs-lookup"><span data-stu-id="56c3d-159">The total number of bytes read into the buffer.</span></span> <span data-ttu-id="56c3d-160">要求されたバイト数をその時点で読み取れなかった場合、この値は要求されたバイト数より小さくなることがあります。ストリームの末尾に達していた場合は 0 になります。</span><span class="sxs-lookup"><span data-stu-id="56c3d-160">This can be less than the number of bytes requested if that many bytes are not currently available, or zero if the end of the stream has been reached.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Seek">
      <MemberSignature Language="C#" Value="public override long Seek (long offset, System.IO.SeekOrigin origin);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int64 Seek(int64 offset, valuetype System.IO.SeekOrigin origin) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream.Seek(System.Int64,System.IO.SeekOrigin)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Seek (offset As Long, origin As SeekOrigin) As Long" />
      <MemberSignature Language="F#" Value="override this.Seek : int64 * System.IO.SeekOrigin -&gt; int64" Usage="multiBufferMemoryStream.Seek (offset, origin)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="offset" Type="System.Int64" />
        <Parameter Name="origin" Type="System.IO.SeekOrigin" />
      </Parameters>
      <Docs>
        <param name="offset"><span data-ttu-id="56c3d-161">Origin パラメーターからのバイト オフセット。</span><span class="sxs-lookup"><span data-stu-id="56c3d-161">A byte offset relative to the origin parameter.</span></span></param>
        <param name="origin"><span data-ttu-id="56c3d-162">新しい位置を取得するために使用する参照ポイントを示す System.IO.SeekOrigin 型の値です。</span><span class="sxs-lookup"><span data-stu-id="56c3d-162">A value of type System.IO.SeekOrigin indicating the reference point used to obtain the new position.</span></span></param>
        <summary>
            <span data-ttu-id="56c3d-163">現在のストリーム内の位置を設定します。</span><span class="sxs-lookup"><span data-stu-id="56c3d-163">Sets the position within the current stream.</span></span>
            </summary>
        <returns><span data-ttu-id="56c3d-164">現在のストリーム内の新しい位置。</span><span class="sxs-lookup"><span data-stu-id="56c3d-164">The new position within the current stream.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="56c3d-165">場合にスロー <paramref name="offset" /> SeekOrigin に対して無効です。</span><span class="sxs-lookup"><span data-stu-id="56c3d-165">Thrown if <paramref name="offset" /> is invalid for SeekOrigin.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="SetLength">
      <MemberSignature Language="C#" Value="public override void SetLength (long value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void SetLength(int64 value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream.SetLength(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub SetLength (value As Long)" />
      <MemberSignature Language="F#" Value="override this.SetLength : int64 -&gt; unit" Usage="multiBufferMemoryStream.SetLength value" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="value" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="value"><span data-ttu-id="56c3d-166">現在のストリームの希望の長さ (バイト数)。</span><span class="sxs-lookup"><span data-stu-id="56c3d-166">The desired length of the current stream in bytes.</span></span></param>
        <summary>
            <span data-ttu-id="56c3d-167">現在のストリームの長さを設定します。</span><span class="sxs-lookup"><span data-stu-id="56c3d-167">Sets the length of the current stream.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="56c3d-168">場合、<paramref name="value" />が負の値。</span><span class="sxs-lookup"><span data-stu-id="56c3d-168">If the <paramref name="value" /> is negative.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Write">
      <MemberSignature Language="C#" Value="public override void Write (byte[] buffer, int offset, int count);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Write(unsigned int8[] buffer, int32 offset, int32 count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream.Write(System.Byte[],System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Write (buffer As Byte(), offset As Integer, count As Integer)" />
      <MemberSignature Language="F#" Value="override this.Write : byte[] * int * int -&gt; unit" Usage="multiBufferMemoryStream.Write (buffer, offset, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="buffer" Type="System.Byte[]" />
        <Parameter Name="offset" Type="System.Int32" />
        <Parameter Name="count" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="buffer"><span data-ttu-id="56c3d-169">データの書き込み元となるバッファー。</span><span class="sxs-lookup"><span data-stu-id="56c3d-169">The buffer to write data from.</span></span></param>
        <param name="offset"><span data-ttu-id="56c3d-170">現在のストリームにバイトのコピーを開始する位置を示すバッファー内の 0 から始まるバイト オフセット。</span><span class="sxs-lookup"><span data-stu-id="56c3d-170">The zero-based byte offset in buffer at which to begin copying bytes to the current stream.</span></span></param>
        <param name="count"><span data-ttu-id="56c3d-171">書き込むバイト数。</span><span class="sxs-lookup"><span data-stu-id="56c3d-171">The number of bytes to write.</span></span> </param>
        <summary>
            <span data-ttu-id="56c3d-172">バッファーから読み取ったデータを使用して、現在のストリームにバイトのブロックを書き込みます。</span><span class="sxs-lookup"><span data-stu-id="56c3d-172">Writes a block of bytes to the current stream using data read from a buffer.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>