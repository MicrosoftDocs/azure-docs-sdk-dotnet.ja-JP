<Type Name="SyncMemoryStream" FullName="Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream">
  <TypeSignature Language="C#" Value="public class SyncMemoryStream : System.IO.MemoryStream" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SyncMemoryStream extends System.IO.MemoryStream" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream" />
  <TypeSignature Language="VB.NET" Value="Public Class SyncMemoryStream&#xA;Inherits MemoryStream" />
  <TypeSignature Language="F#" Value="type SyncMemoryStream = class&#xA;    inherit MemoryStream" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.IO.MemoryStream</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7035c-101">このクラスは、パフォーマンスを向上させるためにメモリ ストリームの上書きを APM 読み取り/書き込みを提供します。</span><span class="sxs-lookup"><span data-stu-id="7035c-101">This class provides APM Read/Write overrides for memory stream to improve performance.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SyncMemoryStream ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7035c-102">0 に初期化される拡張可能な容量 SyncMemoryStream クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7035c-102">Initializes a new instance of the SyncMemoryStream class with an expandable capacity initialized to zero.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SyncMemoryStream (byte[] buffer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(unsigned int8[] buffer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream.#ctor(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (buffer As Byte())" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream : byte[] -&gt; Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream" Usage="new Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream buffer" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="buffer" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="buffer"><span data-ttu-id="7035c-103">現在のストリームを作成する符号なしバイトの配列。</span><span class="sxs-lookup"><span data-stu-id="7035c-103">The array of unsigned bytes from which to create the current stream.</span></span></param>
        <summary>
            <span data-ttu-id="7035c-104">指定したバイト配列に基づく SyncMemoryStream クラスの新しいサイズを変更できないインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7035c-104">Initializes a new non-resizable instance of the SyncMemoryStream class based on the specified byte array.</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SyncMemoryStream (byte[] buffer, int index);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(unsigned int8[] buffer, int32 index) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream.#ctor(System.Byte[],System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (buffer As Byte(), index As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream : byte[] * int -&gt; Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream" Usage="new Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream (buffer, index)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="buffer" Type="System.Byte[]" />
        <Parameter Name="index" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="buffer"><span data-ttu-id="7035c-105">現在のストリームを作成する符号なしバイトの配列。</span><span class="sxs-lookup"><span data-stu-id="7035c-105">The array of unsigned bytes from which to create the current stream.</span></span></param>
        <param name="index"><span data-ttu-id="7035c-106">開始位置となるストリーム バッファーへのインデックス。</span><span class="sxs-lookup"><span data-stu-id="7035c-106">The index into buffer at which the stream begins.</span></span></param>
        <summary>
            <span data-ttu-id="7035c-107">バイト配列の指定した領域 (インデックス) に基づいて SyncMemoryStream クラスの新しいサイズを変更できないインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7035c-107">Initializes a new non-resizable instance of the SyncMemoryStream class based on the specified region (index) of a byte array.</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SyncMemoryStream (byte[] buffer, int index, int count);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(unsigned int8[] buffer, int32 index, int32 count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream.#ctor(System.Byte[],System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (buffer As Byte(), index As Integer, count As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream : byte[] * int * int -&gt; Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream" Usage="new Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream (buffer, index, count)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="buffer" Type="System.Byte[]" />
        <Parameter Name="index" Type="System.Int32" />
        <Parameter Name="count" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="buffer"><span data-ttu-id="7035c-108">現在のストリームを作成する符号なしバイトの配列。</span><span class="sxs-lookup"><span data-stu-id="7035c-108">The array of unsigned bytes from which to create the current stream.</span></span></param>
        <param name="index"><span data-ttu-id="7035c-109">開始位置となるストリーム バッファーへのインデックス。</span><span class="sxs-lookup"><span data-stu-id="7035c-109">The index into buffer at which the stream begins.</span></span></param>
        <param name="count"><span data-ttu-id="7035c-110">バイト単位のストリーム長。</span><span class="sxs-lookup"><span data-stu-id="7035c-110">The length of the stream in bytes.</span></span></param>
        <summary>
            <span data-ttu-id="7035c-111">バイト配列の指定した領域 (インデックス) に基づいて SyncMemoryStream クラスの新しいサイズを変更できないインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7035c-111">Initializes a new non-resizable instance of the SyncMemoryStream class based on the specified region (index) of a byte array.</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRead">
      <MemberSignature Language="C#" Value="public override IAsyncResult BeginRead (byte[] buffer, int offset, int count, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.IAsyncResult BeginRead(unsigned int8[] buffer, int32 offset, int32 count, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream.BeginRead(System.Byte[],System.Int32,System.Int32,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function BeginRead (buffer As Byte(), offset As Integer, count As Integer, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.BeginRead : byte[] * int * int * AsyncCallback * obj -&gt; IAsyncResult" Usage="syncMemoryStream.BeginRead (buffer, offset, count, callback, state)" />
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
        <param name="buffer"><span data-ttu-id="7035c-112">このメソッドが返されるとき、バッファーは現在のソースから読み取ったバイトにより置き換えられた、オフセットから (オフセット + データの個数 - 1) の間の値を持つ指定されたバイト配列を含みます。</span><span class="sxs-lookup"><span data-stu-id="7035c-112">When this method returns, the buffer contains the specified byte array with the values between offset and (offset + count - 1) replaced by the bytes read from the current source.</span></span></param>
        <param name="offset"><span data-ttu-id="7035c-113">現在のストリームから読み取ったデータの格納を開始する位置を示す バッファ内の0 から始まるバイト オフセット。</span><span class="sxs-lookup"><span data-stu-id="7035c-113">The zero-based byte offset in buffer at which to begin storing the data read from the current stream.</span></span></param>
        <param name="count"><span data-ttu-id="7035c-114">読み取るバイトの最大数。</span><span class="sxs-lookup"><span data-stu-id="7035c-114">The maximum number of bytes to be read.</span></span></param>
        <param name="callback"><span data-ttu-id="7035c-115">読み取り完了時に呼び出されるオプションの非同期コールバック。</span><span class="sxs-lookup"><span data-stu-id="7035c-115">An optional asynchronous callback, to be called when the read is complete.</span></span></param>
        <param name="state"><span data-ttu-id="7035c-116">この特定の非同期読み取り要求を他の要求と区別するために使用するユーザー指定のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="7035c-116">A user-provided object that distinguishes this particular asynchronous read request from other requests.</span></span></param>
        <summary>
            <span data-ttu-id="7035c-117">非同期の読み込み動作を開始します。</span><span class="sxs-lookup"><span data-stu-id="7035c-117">Begins an asynchronous read operation.</span></span>
            </summary>
        <returns><span data-ttu-id="7035c-118">非同期の読み取りは、保留になっていることを表す IAsyncResult。</span><span class="sxs-lookup"><span data-stu-id="7035c-118">An IAsyncResult that represents the asynchronous read, which could still be pending.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginWrite">
      <MemberSignature Language="C#" Value="public override IAsyncResult BeginWrite (byte[] buffer, int offset, int count, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.IAsyncResult BeginWrite(unsigned int8[] buffer, int32 offset, int32 count, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream.BeginWrite(System.Byte[],System.Int32,System.Int32,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function BeginWrite (buffer As Byte(), offset As Integer, count As Integer, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.BeginWrite : byte[] * int * int * AsyncCallback * obj -&gt; IAsyncResult" Usage="syncMemoryStream.BeginWrite (buffer, offset, count, callback, state)" />
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
        <param name="buffer"><span data-ttu-id="7035c-119">データの書き込み元となるバッファー。</span><span class="sxs-lookup"><span data-stu-id="7035c-119">The buffer to write data from.</span></span></param>
        <param name="offset"><span data-ttu-id="7035c-120">現在のストリームにバイトのコピーを開始する位置を示すバッファー内の 0 から始まるバイト オフセット。</span><span class="sxs-lookup"><span data-stu-id="7035c-120">The zero-based byte offset in buffer at which to begin copying bytes to the current stream.</span></span></param>
        <param name="count"><span data-ttu-id="7035c-121">書き込むバイト数。</span><span class="sxs-lookup"><span data-stu-id="7035c-121">The number of bytes to write.</span></span></param>
        <param name="callback"><span data-ttu-id="7035c-122">書き込みの完了時に呼び出されるオプションの非同期コールバック。</span><span class="sxs-lookup"><span data-stu-id="7035c-122">An optional asynchronous callback, to be called when the write is complete.</span></span></param>
        <param name="state"><span data-ttu-id="7035c-123">この特定の非同期書き込み要求を他の要求と区別するために使用するユーザー指定のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="7035c-123">A user-provided object that distinguishes this particular asynchronous write request from other requests.</span></span></param>
        <summary>
            <span data-ttu-id="7035c-124">非同期の書き込み操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="7035c-124">Begins an asynchronous write operation.</span></span>
            </summary>
        <returns><span data-ttu-id="7035c-125">保留になっている可能性があります、非同期の書き込みを表す IAsyncResult。</span><span class="sxs-lookup"><span data-stu-id="7035c-125">An IAsyncResult that represents the asynchronous write, which could still be pending.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndRead">
      <MemberSignature Language="C#" Value="public override int EndRead (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 EndRead(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream.EndRead(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function EndRead (asyncResult As IAsyncResult) As Integer" />
      <MemberSignature Language="F#" Value="override this.EndRead : IAsyncResult -&gt; int" Usage="syncMemoryStream.EndRead asyncResult" />
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
        <param name="asyncResult"><span data-ttu-id="7035c-126">終了させる保留状態の非同期リクエストへの参照。</span><span class="sxs-lookup"><span data-stu-id="7035c-126">The reference to the pending asynchronous request to finish.</span></span></param>
        <summary>
            <span data-ttu-id="7035c-127">保留中の非同期読み取りが完了するまで待機します。</span><span class="sxs-lookup"><span data-stu-id="7035c-127">Waits for the pending asynchronous read to complete.</span></span>
            </summary>
        <returns><span data-ttu-id="7035c-128">バッファーに読み取られた合計バイト数。</span><span class="sxs-lookup"><span data-stu-id="7035c-128">The total number of bytes read into the buffer.</span></span> <span data-ttu-id="7035c-129">要求されたバイト数をその時点で読み取れなかった場合、この値は要求されたバイト数より小さくなることがあります。ストリームの末尾に達していた場合は 0 になります。</span><span class="sxs-lookup"><span data-stu-id="7035c-129">This can be less than the number of bytes requested if that many bytes are not currently available, or zero if the end of the stream has been reached.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndWrite">
      <MemberSignature Language="C#" Value="public override void EndWrite (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void EndWrite(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream.EndWrite(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub EndWrite (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.EndWrite : IAsyncResult -&gt; unit" Usage="syncMemoryStream.EndWrite asyncResult" />
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
        <param name="asyncResult"><span data-ttu-id="7035c-130">終了させる保留状態の非同期リクエストへの参照。</span><span class="sxs-lookup"><span data-stu-id="7035c-130">The reference to the pending asynchronous request to finish.</span></span></param>
        <summary>
            <span data-ttu-id="7035c-131">非同期書き込み操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="7035c-131">Ends an asynchronous write operation.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>