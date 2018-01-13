<Type Name="AdlsInputStream" FullName="Microsoft.Azure.DataLake.Store.AdlsInputStream">
  <TypeSignature Language="C#" Value="public class AdlsInputStream : System.IO.Stream" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AdlsInputStream extends System.IO.Stream" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.DataLake.Store.AdlsInputStream" />
  <TypeSignature Language="VB.NET" Value="Public Class AdlsInputStream&#xA;Inherits Stream" />
  <TypeSignature Language="F#" Value="type AdlsInputStream = class&#xA;    inherit Stream" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
    <AssemblyVersion>0.1.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.IO.Stream</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3f053-101">Data lake 上のファイルからデータを読み取る ADLS 入力ストリーム。</span><span class="sxs-lookup"><span data-stu-id="3f053-101">ADLS Input stream that reads data from a file on Data lake.</span></span> <span data-ttu-id="3f053-102">サーバーからバッファーを一括でデータを読み取るし、要求に従って、クライアントにバッファーされた出力を提供します。</span><span class="sxs-lookup"><span data-stu-id="3f053-102">It reads data in bulk from server to a buffer and then provides buffered output to the client as per request.</span></span>
            <span data-ttu-id="3f053-103">非同期的または同期的にデータを読み取ることができます。</span><span class="sxs-lookup"><span data-stu-id="3f053-103">Data can be read asynchronously/synchronously.</span></span> <span data-ttu-id="3f053-104">連続的にまたはファイルの任意の場所からデータを読み取ることができます。</span><span class="sxs-lookup"><span data-stu-id="3f053-104">Data can be read serially or from arbitrary points in file.</span></span> <span data-ttu-id="3f053-105">読み取りは、トランスポート層まで完全に同期します。</span><span class="sxs-lookup"><span data-stu-id="3f053-105">Read is fully synchronous till the transport layer.</span></span> <span data-ttu-id="3f053-106">ReadAsync が、トランスポート層まで完全に同期されます。</span><span class="sxs-lookup"><span data-stu-id="3f053-106">ReadAsync is fully synchronous till the transport layer.</span></span> 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected AdlsInputStream ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsInputStream.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3f053-107">目的をモックします。</span><span class="sxs-lookup"><span data-stu-id="3f053-107">Only for Mocking purpose.</span></span> <span data-ttu-id="3f053-108">目的のモックにこのクラスから継承し、メソッドをオーバーライド</span><span class="sxs-lookup"><span data-stu-id="3f053-108">For mocking purpose you can inherit from this class and override your methods</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanRead">
      <MemberSignature Language="C#" Value="public override bool CanRead { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool CanRead" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.AdlsInputStream.CanRead" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property CanRead As Boolean" />
      <MemberSignature Language="F#" Value="member this.CanRead : bool" Usage="Microsoft.Azure.DataLake.Store.AdlsInputStream.CanRead" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3f053-109">ストリームがデータを読み取ることができますか</span><span class="sxs-lookup"><span data-stu-id="3f053-109">Whether stream can read data</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanSeek">
      <MemberSignature Language="C#" Value="public override bool CanSeek { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool CanSeek" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.AdlsInputStream.CanSeek" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property CanSeek As Boolean" />
      <MemberSignature Language="F#" Value="member this.CanSeek : bool" Usage="Microsoft.Azure.DataLake.Store.AdlsInputStream.CanSeek" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3f053-110">データをストリームでシークできるかどうか</span><span class="sxs-lookup"><span data-stu-id="3f053-110">Whether the stream can seek data</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanWrite">
      <MemberSignature Language="C#" Value="public override bool CanWrite { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool CanWrite" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.AdlsInputStream.CanWrite" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property CanWrite As Boolean" />
      <MemberSignature Language="F#" Value="member this.CanWrite : bool" Usage="Microsoft.Azure.DataLake.Store.AdlsInputStream.CanWrite" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3f053-111">ストリームがデータを書き込むかどうか</span><span class="sxs-lookup"><span data-stu-id="3f053-111">Whether the stream can write data</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="protected override void Dispose (bool disposing);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void Dispose(bool disposing) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsInputStream.Dispose(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub Dispose (disposing As Boolean)" />
      <MemberSignature Language="F#" Value="override this.Dispose : bool -&gt; unit" Usage="adlsInputStream.Dispose disposing" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disposing" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="disposing"><span data-ttu-id="3f053-112">マネージ コードとアンマネージ リソースを解放する場合は trueアンマネージ リソースだけを解放する場合は false</span><span class="sxs-lookup"><span data-stu-id="3f053-112">true to release both managed and unmanaged resources; false to release only unmanaged resources</span></span></param>
        <summary>
            <span data-ttu-id="3f053-113">ストリームで使用されるアンマネージ リソースを解放し、オプションでマネージ リソースも解放</span><span class="sxs-lookup"><span data-stu-id="3f053-113">Releases the unmanaged resources used by the Stream and optionally releases the managed resources</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Flush">
      <MemberSignature Language="C#" Value="public override void Flush ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Flush() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsInputStream.Flush" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Flush ()" />
      <MemberSignature Language="F#" Value="override this.Flush : unit -&gt; unit" Usage="adlsInputStream.Flush " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3f053-114">サポートされていません</span><span class="sxs-lookup"><span data-stu-id="3f053-114">Not supported</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Length">
      <MemberSignature Language="C#" Value="public override long Length { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Length" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.AdlsInputStream.Length" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property Length As Long" />
      <MemberSignature Language="F#" Value="member this.Length : int64" Usage="Microsoft.Azure.DataLake.Store.AdlsInputStream.Length" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3f053-115">ファイルの合計の長さ</span><span class="sxs-lookup"><span data-stu-id="3f053-115">total Length of the file</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Position">
      <MemberSignature Language="C#" Value="public override long Position { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Position" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.AdlsInputStream.Position" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Property Position As Long" />
      <MemberSignature Language="F#" Value="member this.Position : int64 with get, set" Usage="Microsoft.Azure.DataLake.Store.AdlsInputStream.Position" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3f053-116">先頭からストリームの位置</span><span class="sxs-lookup"><span data-stu-id="3f053-116">Position of the stream from begining</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Read">
      <MemberSignature Language="C#" Value="public override int Read (byte[] output, int offset, int count);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 Read(unsigned int8[] output, int32 offset, int32 count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsInputStream.Read(System.Byte[],System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Read (output As Byte(), offset As Integer, count As Integer) As Integer" />
      <MemberSignature Language="F#" Value="override this.Read : byte[] * int * int -&gt; int" Usage="adlsInputStream.Read (output, offset, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="output" Type="System.Byte[]" />
        <Parameter Name="offset" Type="System.Int32" />
        <Parameter Name="count" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="output"><span data-ttu-id="3f053-117">出力バイト配列</span><span class="sxs-lookup"><span data-stu-id="3f053-117">Output byte array</span></span></param>
        <param name="offset"><span data-ttu-id="3f053-118">データが、呼び出し力配列で配置されるオフセット</span><span class="sxs-lookup"><span data-stu-id="3f053-118">offset at which data should be put in the output array</span></span></param>
        <param name="count"><span data-ttu-id="3f053-119">読み取りバイト数のカウント</span><span class="sxs-lookup"><span data-stu-id="3f053-119">Count of the bytes read</span></span></param>
        <summary>
            <span data-ttu-id="3f053-120">現在のストリームからバイト シーケンスを読み取り、同期操作で読み取られたバイト数だけストリーム内の位置を進めます。</span><span class="sxs-lookup"><span data-stu-id="3f053-120">Reads a sequence of bytes from the current stream and advances the position within the stream by the number of bytes read Synchronous operation.</span></span>
            </summary>
        <returns><span data-ttu-id="3f053-121">読み取られたバイト数</span><span class="sxs-lookup"><span data-stu-id="3f053-121">Number of bytes read</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Read">
      <MemberSignature Language="C#" Value="public int Read (long position, byte[] output, int offset, int count);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance int32 Read(int64 position, unsigned int8[] output, int32 offset, int32 count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsInputStream.Read(System.Int64,System.Byte[],System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function Read (position As Long, output As Byte(), offset As Integer, count As Integer) As Integer" />
      <MemberSignature Language="F#" Value="override this.Read : int64 * byte[] * int * int -&gt; int" Usage="adlsInputStream.Read (position, output, offset, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="position" Type="System.Int64" />
        <Parameter Name="output" Type="System.Byte[]" />
        <Parameter Name="offset" Type="System.Int32" />
        <Parameter Name="count" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="position"><span data-ttu-id="3f053-122">データの読み取りを開始するように場所からファイル内の位置</span><span class="sxs-lookup"><span data-stu-id="3f053-122">Position in the file from where it should start reading data</span></span></param>
        <param name="output"><span data-ttu-id="3f053-123">出力バイト配列</span><span class="sxs-lookup"><span data-stu-id="3f053-123">Output byte array</span></span></param>
        <param name="offset"><span data-ttu-id="3f053-124">データが、呼び出し力配列で配置されるオフセット</span><span class="sxs-lookup"><span data-stu-id="3f053-124">offset at which data should be put in the output array</span></span></param>
        <param name="count"><span data-ttu-id="3f053-125">読み取りバイト数のカウント</span><span class="sxs-lookup"><span data-stu-id="3f053-125">Count of the bytes read</span></span></param>
        <summary>
            <span data-ttu-id="3f053-126">サーバーから直接には、バイト シーケンスを読み取ります。</span><span class="sxs-lookup"><span data-stu-id="3f053-126">Reads a sequence of bytes directly from the server.</span></span> <span data-ttu-id="3f053-127">更新、ストリームでは何もしません。</span><span class="sxs-lookup"><span data-stu-id="3f053-127">It does not update anything in the stream.</span></span>
            </summary>
        <returns><span data-ttu-id="3f053-128">読み取られたバイト数</span><span class="sxs-lookup"><span data-stu-id="3f053-128">Number of bytes read</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadAsync">
      <MemberSignature Language="C#" Value="public override System.Threading.Tasks.Task&lt;int&gt; ReadAsync (byte[] output, int offset, int count, System.Threading.CancellationToken cancelToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.Threading.Tasks.Task`1&lt;int32&gt; ReadAsync(unsigned int8[] output, int32 offset, int32 count, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsInputStream.ReadAsync(System.Byte[],System.Int32,System.Int32,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ReadAsync (output As Byte(), offset As Integer, count As Integer, cancelToken As CancellationToken) As Task(Of Integer)" />
      <MemberSignature Language="F#" Value="override this.ReadAsync : byte[] * int * int * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int&gt;" Usage="adlsInputStream.ReadAsync (output, offset, count, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.AdlsInputStream/&lt;ReadAsync&gt;d__49))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="output" Type="System.Byte[]" />
        <Parameter Name="offset" Type="System.Int32" />
        <Parameter Name="count" Type="System.Int32" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="output"><span data-ttu-id="3f053-129">出力バイト配列</span><span class="sxs-lookup"><span data-stu-id="3f053-129">Output byte array</span></span></param>
        <param name="offset"><span data-ttu-id="3f053-130">データが、呼び出し力配列で配置されるオフセット</span><span class="sxs-lookup"><span data-stu-id="3f053-130">offset at which data should be put in the output array</span></span></param>
        <param name="count"><span data-ttu-id="3f053-131">読み取りバイト数のカウント</span><span class="sxs-lookup"><span data-stu-id="3f053-131">Count of the bytes read</span></span></param>
        <param name="cancelToken"><span data-ttu-id="3f053-132">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="3f053-132">Cancellation Token</span></span></param>
        <summary>
            <span data-ttu-id="3f053-133">現在のストリームからバイト シーケンスを読み取り、非同期操作を読み取られたバイト数だけストリーム内の位置を進めます。</span><span class="sxs-lookup"><span data-stu-id="3f053-133">Reads a sequence of bytes from the current stream and advances the position within the stream by the number of bytes read Asynchronous operation.</span></span>
            </summary>
        <returns><span data-ttu-id="3f053-134">読み取られたバイト数</span><span class="sxs-lookup"><span data-stu-id="3f053-134">Number of bytes read</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;int&gt; ReadAsync (long position, byte[] output, int offset, int count);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int32&gt; ReadAsync(int64 position, unsigned int8[] output, int32 offset, int32 count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsInputStream.ReadAsync(System.Int64,System.Byte[],System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadAsync (position As Long, output As Byte(), offset As Integer, count As Integer) As Task(Of Integer)" />
      <MemberSignature Language="F#" Value="override this.ReadAsync : int64 * byte[] * int * int -&gt; System.Threading.Tasks.Task&lt;int&gt;" Usage="adlsInputStream.ReadAsync (position, output, offset, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.AdlsInputStream/&lt;ReadAsync&gt;d__55))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="position" Type="System.Int64" />
        <Parameter Name="output" Type="System.Byte[]" />
        <Parameter Name="offset" Type="System.Int32" />
        <Parameter Name="count" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="position"><span data-ttu-id="3f053-135">データの読み取りを開始するように場所からファイル内の位置</span><span class="sxs-lookup"><span data-stu-id="3f053-135">Position in the file from where it should start reading data</span></span></param>
        <param name="output"><span data-ttu-id="3f053-136">出力バイト配列</span><span class="sxs-lookup"><span data-stu-id="3f053-136">Output byte array</span></span></param>
        <param name="offset"><span data-ttu-id="3f053-137">データが、呼び出し力配列で配置されるオフセット</span><span class="sxs-lookup"><span data-stu-id="3f053-137">offset at which data should be put in the output array</span></span></param>
        <param name="count"><span data-ttu-id="3f053-138">読み取りバイト数のカウント</span><span class="sxs-lookup"><span data-stu-id="3f053-138">Count of the bytes read</span></span></param>
        <summary>
            <span data-ttu-id="3f053-139">サーバーから直接には、バイト シーケンスを読み取ります。</span><span class="sxs-lookup"><span data-stu-id="3f053-139">Reads a sequence of bytes directly from the server.</span></span> <span data-ttu-id="3f053-140">更新、ストリームでは何もしません。</span><span class="sxs-lookup"><span data-stu-id="3f053-140">It does not update anything in the stream.</span></span>
            </summary>
        <returns><span data-ttu-id="3f053-141">読み取られたバイト数</span><span class="sxs-lookup"><span data-stu-id="3f053-141">Number of bytes read</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Seek">
      <MemberSignature Language="C#" Value="public override long Seek (long offset, System.IO.SeekOrigin origin);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int64 Seek(int64 offset, valuetype System.IO.SeekOrigin origin) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsInputStream.Seek(System.Int64,System.IO.SeekOrigin)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Seek (offset As Long, origin As SeekOrigin) As Long" />
      <MemberSignature Language="F#" Value="override this.Seek : int64 * System.IO.SeekOrigin -&gt; int64" Usage="adlsInputStream.Seek (offset, origin)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="offset" Type="System.Int64" />
        <Parameter Name="origin" Type="System.IO.SeekOrigin" />
      </Parameters>
      <Docs>
        <param name="offset"><span data-ttu-id="3f053-142">Origin パラメーターからのバイト オフセット</span><span class="sxs-lookup"><span data-stu-id="3f053-142">Byte offset relative to the origin parameter</span></span></param>
        <param name="origin"><span data-ttu-id="3f053-143">型の新しい位置を取得するために使用する参照ポイントを示す SeekOrigin の値。</span><span class="sxs-lookup"><span data-stu-id="3f053-143">A value of type SeekOrigin indicating the reference point used to obtain the new position.</span></span></param>
        <summary>
            <span data-ttu-id="3f053-144">SeekOrigin に基づいて、ストリームの位置を更新します。</span><span class="sxs-lookup"><span data-stu-id="3f053-144">Updates the position of the stream based on SeekOrigin</span></span>
            </summary>
        <returns><span data-ttu-id="3f053-145">ストリームの現在の新しい位置</span><span class="sxs-lookup"><span data-stu-id="3f053-145">Current new position of the stream</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetLength">
      <MemberSignature Language="C#" Value="public override void SetLength (long value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void SetLength(int64 value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsInputStream.SetLength(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub SetLength (value As Long)" />
      <MemberSignature Language="F#" Value="override this.SetLength : int64 -&gt; unit" Usage="adlsInputStream.SetLength value" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="value" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="value"></param>
        <summary>
            <span data-ttu-id="3f053-146">サポートされていません</span><span class="sxs-lookup"><span data-stu-id="3f053-146">Not supported</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Write">
      <MemberSignature Language="C#" Value="public override void Write (byte[] buffer, int offset, int count);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Write(unsigned int8[] buffer, int32 offset, int32 count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsInputStream.Write(System.Byte[],System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Write (buffer As Byte(), offset As Integer, count As Integer)" />
      <MemberSignature Language="F#" Value="override this.Write : byte[] * int * int -&gt; unit" Usage="adlsInputStream.Write (buffer, offset, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
        <param name="buffer"></param>
        <param name="offset"></param>
        <param name="count"></param>
        <summary>
            <span data-ttu-id="3f053-147">サポートされていません</span><span class="sxs-lookup"><span data-stu-id="3f053-147">Not supported</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>