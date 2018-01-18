<Type Name="MockAdlsInputStream" FullName="Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsInputStream">
  <TypeSignature Language="C#" Value="public sealed class MockAdlsInputStream : Microsoft.Azure.DataLake.Store.AdlsInputStream" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit MockAdlsInputStream extends Microsoft.Azure.DataLake.Store.AdlsInputStream" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsInputStream" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class MockAdlsInputStream&#xA;Inherits AdlsInputStream" />
  <TypeSignature Language="F#" Value="type MockAdlsInputStream = class&#xA;    inherit AdlsInputStream" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.DataLake.Store.AdlsInputStream</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="22457-101">単体テストのモック Adls 入力ストリーム</span><span class="sxs-lookup"><span data-stu-id="22457-101">Mock Adls Input stream for unit test</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="protected override void Dispose (bool disposing);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void Dispose(bool disposing) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsInputStream.Dispose(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub Dispose (disposing As Boolean)" />
      <MemberSignature Language="F#" Value="override this.Dispose : bool -&gt; unit" Usage="mockAdlsInputStream.Dispose disposing" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disposing" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="disposing"><span data-ttu-id="22457-102">マネージ コードとアンマネージ リソースを解放する場合は trueアンマネージ リソースだけを解放する場合は false</span><span class="sxs-lookup"><span data-stu-id="22457-102">true to release both managed and unmanaged resources; false to release only unmanaged resources</span></span></param>
        <summary>
            <span data-ttu-id="22457-103">ストリームで使用されているアンマネージ リソースを解放し、必要に応じてマネージ リソースも解放します。</span><span class="sxs-lookup"><span data-stu-id="22457-103">Releases the unmanaged resources used by the Stream and optionally releases the managed resources.</span></span> <span data-ttu-id="22457-104">この実装では破棄しない基になるストリーム読み取りと書き込みの両方のストリームを使用したのでです。</span><span class="sxs-lookup"><span data-stu-id="22457-104">For this implementation, we do not dispose the underlying stream since we use the stream for both read and write.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Length">
      <MemberSignature Language="C#" Value="public override long Length { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Length" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsInputStream.Length" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property Length As Long" />
      <MemberSignature Language="F#" Value="member this.Length : int64" Usage="Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsInputStream.Length" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="22457-105">取得専用のストリームの長さを設定できません。</span><span class="sxs-lookup"><span data-stu-id="22457-105">Length of the stream, Cannot be set only retrieved</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Position">
      <MemberSignature Language="C#" Value="public override long Position { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Position" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsInputStream.Position" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Property Position As Long" />
      <MemberSignature Language="F#" Value="member this.Position : int64 with get, set" Usage="Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsInputStream.Position" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="22457-106">先頭からストリームの位置</span><span class="sxs-lookup"><span data-stu-id="22457-106">Position of the stream from begining</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Read">
      <MemberSignature Language="C#" Value="public override int Read (byte[] output, int offset, int count);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 Read(unsigned int8[] output, int32 offset, int32 count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsInputStream.Read(System.Byte[],System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Read (output As Byte(), offset As Integer, count As Integer) As Integer" />
      <MemberSignature Language="F#" Value="override this.Read : byte[] * int * int -&gt; int" Usage="mockAdlsInputStream.Read (output, offset, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
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
        <param name="output"><span data-ttu-id="22457-107">出力バイト配列</span><span class="sxs-lookup"><span data-stu-id="22457-107">Output byte array</span></span></param>
        <param name="offset"><span data-ttu-id="22457-108">データが、呼び出し力配列で配置されるオフセット</span><span class="sxs-lookup"><span data-stu-id="22457-108">offset at which data should be put in the output array</span></span></param>
        <param name="count"><span data-ttu-id="22457-109">読み取りバイト数のカウント</span><span class="sxs-lookup"><span data-stu-id="22457-109">Count of the bytes read</span></span></param>
        <summary>
            <span data-ttu-id="22457-110">現在の基になるストリームからバイトのシーケンスを読み取り、同期操作で読み取られたバイト数だけストリーム内の位置を進めます。</span><span class="sxs-lookup"><span data-stu-id="22457-110">Reads a sequence of bytes from the current underlying stream and advances the position within the stream by the number of bytes read Synchronous operation.</span></span>
            </summary>
        <returns><span data-ttu-id="22457-111">読み取られたバイト数</span><span class="sxs-lookup"><span data-stu-id="22457-111">Number of bytes read</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadAsync">
      <MemberSignature Language="C#" Value="public override System.Threading.Tasks.Task&lt;int&gt; ReadAsync (byte[] output, int offset, int count, System.Threading.CancellationToken cancelToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.Threading.Tasks.Task`1&lt;int32&gt; ReadAsync(unsigned int8[] output, int32 offset, int32 count, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsInputStream.ReadAsync(System.Byte[],System.Int32,System.Int32,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ReadAsync (output As Byte(), offset As Integer, count As Integer, cancelToken As CancellationToken) As Task(Of Integer)" />
      <MemberSignature Language="F#" Value="override this.ReadAsync : byte[] * int * int * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int&gt;" Usage="mockAdlsInputStream.ReadAsync (output, offset, count, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsInputStream/&lt;ReadAsync&gt;d__8))</AttributeName>
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
        <param name="output"><span data-ttu-id="22457-112">出力バイト配列</span><span class="sxs-lookup"><span data-stu-id="22457-112">Output byte array</span></span></param>
        <param name="offset"><span data-ttu-id="22457-113">データが、呼び出し力配列で配置されるオフセット</span><span class="sxs-lookup"><span data-stu-id="22457-113">offset at which data should be put in the output array</span></span></param>
        <param name="count"><span data-ttu-id="22457-114">読み取りバイト数のカウント</span><span class="sxs-lookup"><span data-stu-id="22457-114">Count of the bytes read</span></span></param>
        <param name="cancelToken"><span data-ttu-id="22457-115">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="22457-115">Cancellation Token</span></span></param>
        <summary>
            <span data-ttu-id="22457-116">現在基になるストリームからバイトのシーケンスを読み取り、非同期操作を読み取られたバイト数だけストリーム内の位置を進めます。</span><span class="sxs-lookup"><span data-stu-id="22457-116">Reads a sequence of bytes from the current underlying stream and advances the position within the stream by the number of bytes read Asynchronous operation.</span></span>
            </summary>
        <returns><span data-ttu-id="22457-117">読み取られたバイト数</span><span class="sxs-lookup"><span data-stu-id="22457-117">Number of bytes read</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Seek">
      <MemberSignature Language="C#" Value="public override long Seek (long offset, System.IO.SeekOrigin origin);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int64 Seek(int64 offset, valuetype System.IO.SeekOrigin origin) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsInputStream.Seek(System.Int64,System.IO.SeekOrigin)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Seek (offset As Long, origin As SeekOrigin) As Long" />
      <MemberSignature Language="F#" Value="override this.Seek : int64 * System.IO.SeekOrigin -&gt; int64" Usage="mockAdlsInputStream.Seek (offset, origin)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
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
        <param name="offset"><span data-ttu-id="22457-118">Origin パラメーターからのバイト オフセット</span><span class="sxs-lookup"><span data-stu-id="22457-118">Byte offset relative to the origin parameter</span></span></param>
        <param name="origin"><span data-ttu-id="22457-119">型の新しい位置を取得するために使用する参照ポイントを示す SeekOrigin の値。</span><span class="sxs-lookup"><span data-stu-id="22457-119">A value of type SeekOrigin indicating the reference point used to obtain the new position.</span></span></param>
        <summary>
            <span data-ttu-id="22457-120">SeekOrigin に基づいて基になるストリームの位置を更新します。</span><span class="sxs-lookup"><span data-stu-id="22457-120">Updates the position of the underlying stream based on SeekOrigin</span></span>
            </summary>
        <returns><span data-ttu-id="22457-121">ストリームの現在の新しい位置</span><span class="sxs-lookup"><span data-stu-id="22457-121">Current new position of the stream</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>