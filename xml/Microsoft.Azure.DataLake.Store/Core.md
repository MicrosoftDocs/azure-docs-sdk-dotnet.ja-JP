<Type Name="Core" FullName="Microsoft.Azure.DataLake.Store.Core">
  <TypeSignature Language="C#" Value="public class Core" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Core extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.DataLake.Store.Core" />
  <TypeSignature Language="VB.NET" Value="Public Class Core" />
  <TypeSignature Language="F#" Value="type Core = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
    <AssemblyVersion>0.1.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a1ab2-101">コア レイヤーです。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-101">Core layer.</span></span> <span data-ttu-id="a1ab2-102">REST Api のメソッドが含まれています。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-102">It contains methods for REST APIs.</span></span> <span data-ttu-id="a1ab2-103">各 rest api コマンドをサーバーに、HTTP 要求を送信します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-103">For each rest api command it sends a HTTP request to server.</span></span>
            <span data-ttu-id="a1ab2-104">作成、APPEND、開く、CONCURRENTAPPEND の async および sync の両方のバージョンであること。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-104">We have both async and sync versions of CREATE, APPEND, OPEN, CONCURRENTAPPEND.</span></span> <span data-ttu-id="a1ab2-105">ある理由は、アプリケーションが大きく、明示的なスレッドを使用して、非同期を使用してこれらの操作を行っているかどうか、内部的に await threadpool で不要なスレッドを作成コンテキストの切り替えによりパフォーマンスが低下するとします。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-105">The reason we have that is if the application is doing these operations heavily using explicit threads, then using async-await internally creates unecessary threads in threadpool and performance degrades due to context switching.</span></span> <span data-ttu-id="a1ab2-106">アプリケーションでは、アップローダーとダウンローダーの場合、明示的なスレッドを作成できます。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-106">Application can create explicit threads in cases of uploader and downloader.</span></span>
            <span data-ttu-id="a1ab2-107">これらすべての操作では、同期バージョン MakeCall の WebTransport レイヤーも呼び出します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-107">All these operation also call sync versions of MakeCall in WebTransport layer.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Core ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Append">
      <MemberSignature Language="C#" Value="public static void Append (string path, string leaseId, string sessionId, Microsoft.Azure.DataLake.Store.SyncFlag flag, long offsetFile, byte[] dataBytes, int offset, int length, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Append(string path, string leaseId, string sessionId, valuetype Microsoft.Azure.DataLake.Store.SyncFlag flag, int64 offsetFile, unsigned int8[] dataBytes, int32 offset, int32 length, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.Append(System.String,System.String,System.String,Microsoft.Azure.DataLake.Store.SyncFlag,System.Int64,System.Byte[],System.Int32,System.Int32,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub Append (path As String, leaseId As String, sessionId As String, flag As SyncFlag, offsetFile As Long, dataBytes As Byte(), offset As Integer, length As Integer, client As AdlsClient, req As RequestOptions, resp As OperationResponse)" />
      <MemberSignature Language="F#" Value="static member Append : string * string * string * Microsoft.Azure.DataLake.Store.SyncFlag * int64 * byte[] * int * int * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse -&gt; unit" Usage="Microsoft.Azure.DataLake.Store.Core.Append (path, leaseId, sessionId, flag, offsetFile, dataBytes, offset, length, client, req, resp)" />
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
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="leaseId" Type="System.String" />
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="flag" Type="Microsoft.Azure.DataLake.Store.SyncFlag" />
        <Parameter Name="offsetFile" Type="System.Int64" />
        <Parameter Name="dataBytes" Type="System.Byte[]" />
        <Parameter Name="offset" Type="System.Int32" />
        <Parameter Name="length" Type="System.Int32" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="a1ab2-108">ファイルのパス</span><span class="sxs-lookup"><span data-stu-id="a1ab2-108">Path of the file</span></span></param>
        <param name="leaseId"><span data-ttu-id="a1ab2-109">ファイルの編集を行うことができます、クライアントはその他のクライアント ファイル上のリースを取得する際に、リース ID を含む文字列</span><span class="sxs-lookup"><span data-stu-id="a1ab2-109">String containing the lease ID, when a client obtains a lease on a file no other client can make edits to the file</span></span> </param>
        <param name="sessionId"><span data-ttu-id="a1ab2-110">サーバーに簡単にファイル ハンドラー (ストリーム) を取得するために使用する UUID</span><span class="sxs-lookup"><span data-stu-id="a1ab2-110">UUID that is used to obtain the file handler (stream) easily at server</span></span></param>
        <param name="flag"><span data-ttu-id="a1ab2-111">ファイルのメタデータなどの長さ、変更されたときにデータを渡す SyncFlag.METADATA のバイトを書き込むときに、SyncFlag.DATA を渡すインスタント ファイルの実際のデータと一致するように更新する必要があります。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-111">Pass SyncFlag.DATA when writing bytes of data Pass SyncFlag.METADATA when metadata of the file like length, modified instant needs to be updated to be consistent with the actual data of file.</span></span> <span data-ttu-id="a1ab2-112">SyncFlag.METADATA GetFileStatus と ListStatus を渡した後に一貫性のあるデータを返します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-112">After passing SyncFlag.METADATA GetFileStatus and ListStatus returns consistent data.</span></span>
                               <span data-ttu-id="a1ab2-113">以上のデータを追加する必要がある、ファイルのメタデータを更新、リースの解放およびストリームが閉じているときに、SyncFlag.CLOSE を渡す</span><span class="sxs-lookup"><span data-stu-id="a1ab2-113">Pass SyncFlag.CLOSE when no more data needs to be appended, file metadata is updated, lease is released and the stream is closed</span></span>  </param>
        <param name="offsetFile"><span data-ttu-id="a1ab2-114">データの追加をファイル内のオフセットします。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-114">Offset in the file at which data will be appended</span></span></param>
        <param name="dataBytes"><span data-ttu-id="a1ab2-115">ファイルに書き込むバイトの配列</span><span class="sxs-lookup"><span data-stu-id="a1ab2-115">Array of bytes to write to the file</span></span></param>
        <param name="offset"><span data-ttu-id="a1ab2-116">バイト配列内のオフセットします。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-116">Offset in the byte array</span></span></param>
        <param name="length"><span data-ttu-id="a1ab2-117">オフセット位置から書き込むバイト数</span><span class="sxs-lookup"><span data-stu-id="a1ab2-117">Number of bytes to write from the offset</span></span></param>
        <param name="client"><span data-ttu-id="a1ab2-118">ADLS クライアント</span><span class="sxs-lookup"><span data-stu-id="a1ab2-118">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="a1ab2-119">Http 要求の動作を変更するオプション</span><span class="sxs-lookup"><span data-stu-id="a1ab2-119">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="a1ab2-120">Http 要求の応答/出力の格納します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-120">Stores the response/ouput of the Http request</span></span> </param>
        <summary>
            <span data-ttu-id="a1ab2-121">データをファイルに追加します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-121">Append data to file.</span></span> <span data-ttu-id="a1ab2-122">これは、同期操作です。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-122">This is a synchronous operation.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppendAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task AppendAsync (string path, string leaseId, string sessionId, Microsoft.Azure.DataLake.Store.SyncFlag flag, long offsetFile, byte[] dataBytes, int offset, int length, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task AppendAsync(string path, string leaseId, string sessionId, valuetype Microsoft.Azure.DataLake.Store.SyncFlag flag, int64 offsetFile, unsigned int8[] dataBytes, int32 offset, int32 length, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.AppendAsync(System.String,System.String,System.String,Microsoft.Azure.DataLake.Store.SyncFlag,System.Int64,System.Byte[],System.Int32,System.Int32,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function AppendAsync (path As String, leaseId As String, sessionId As String, flag As SyncFlag, offsetFile As Long, dataBytes As Byte(), offset As Integer, length As Integer, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="static member AppendAsync : string * string * string * Microsoft.Azure.DataLake.Store.SyncFlag * int64 * byte[] * int * int * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.DataLake.Store.Core.AppendAsync (path, leaseId, sessionId, flag, offsetFile, dataBytes, offset, length, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;AppendAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="leaseId" Type="System.String" />
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="flag" Type="Microsoft.Azure.DataLake.Store.SyncFlag" />
        <Parameter Name="offsetFile" Type="System.Int64" />
        <Parameter Name="dataBytes" Type="System.Byte[]" />
        <Parameter Name="offset" Type="System.Int32" />
        <Parameter Name="length" Type="System.Int32" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="a1ab2-123">ファイルのパス</span><span class="sxs-lookup"><span data-stu-id="a1ab2-123">Path of the file</span></span></param>
        <param name="leaseId"><span data-ttu-id="a1ab2-124">ファイルの編集を行うことができます、クライアントはその他のクライアント ファイル上のリースを取得する際に、リース ID を含む文字列</span><span class="sxs-lookup"><span data-stu-id="a1ab2-124">String containing the lease ID, when a client obtains a lease on a file no other client can make edits to the file</span></span> </param>
        <param name="sessionId"><span data-ttu-id="a1ab2-125">サーバーに簡単にファイル ハンドラー (ストリーム) を取得するために使用する UUID</span><span class="sxs-lookup"><span data-stu-id="a1ab2-125">UUID that is used to obtain the file handler (stream) easily at server</span></span></param>
        <param name="flag"><span data-ttu-id="a1ab2-126">ファイルのメタデータなどの長さ、変更されたときにデータを渡す SyncFlag.METADATA のバイトを書き込むときに、SyncFlag.DATA を渡すインスタント ファイルの実際のデータと一致するように更新する必要があります。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-126">Pass SyncFlag.DATA when writing bytes of data Pass SyncFlag.METADATA when metadata of the file like length, modified instant needs to be updated to be consistent with the actual data of file.</span></span> <span data-ttu-id="a1ab2-127">SyncFlag.METADATA GetFileStatus と ListStatus を渡した後に一貫性のあるデータを返します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-127">After passing SyncFlag.METADATA GetFileStatus and ListStatus returns consistent data.</span></span>
                               <span data-ttu-id="a1ab2-128">以上のデータを追加する必要がある、ファイルのメタデータを更新、リースの解放およびストリームが閉じているときに、SyncFlag.CLOSE を渡す</span><span class="sxs-lookup"><span data-stu-id="a1ab2-128">Pass SyncFlag.CLOSE when no more data needs to be appended, file metadata is updated, lease is released and the stream is closed</span></span>  </param>
        <param name="offsetFile"><span data-ttu-id="a1ab2-129">データの追加をファイル内のオフセットします。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-129">Offset in the file at which data will be appended</span></span></param>
        <param name="dataBytes"><span data-ttu-id="a1ab2-130">ファイルに書き込むバイトの配列</span><span class="sxs-lookup"><span data-stu-id="a1ab2-130">Array of bytes to write to the file</span></span></param>
        <param name="offset"><span data-ttu-id="a1ab2-131">バイト配列内のオフセットします。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-131">Offset in the byte array</span></span></param>
        <param name="length"><span data-ttu-id="a1ab2-132">オフセット位置から書き込むバイト数</span><span class="sxs-lookup"><span data-stu-id="a1ab2-132">Number of bytes to write from the offset</span></span></param>
        <param name="client"><span data-ttu-id="a1ab2-133">ADLS クライアント</span><span class="sxs-lookup"><span data-stu-id="a1ab2-133">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="a1ab2-134">Http 要求の動作を変更するオプション</span><span class="sxs-lookup"><span data-stu-id="a1ab2-134">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="a1ab2-135">Http 要求の応答/出力の格納します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-135">Stores the response/ouput of the Http request</span></span> </param>
        <param name="cancelToken"><span data-ttu-id="a1ab2-136">CancellationToken 要求を取り消します</span><span class="sxs-lookup"><span data-stu-id="a1ab2-136">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="a1ab2-137">データをファイルに追加します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-137">Append data to file.</span></span> <span data-ttu-id="a1ab2-138">これは非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-138">This is an asynchronous operation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckAccessSync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CheckAccessSync (string path, string rwx, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CheckAccessSync(string path, string rwx, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.CheckAccessSync(System.String,System.String,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CheckAccessSync (path As String, rwx As String, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="static member CheckAccessSync : string * string * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.DataLake.Store.Core.CheckAccessSync (path, rwx, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;CheckAccessSync&gt;d__20))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="rwx" Type="System.String" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="a1ab2-139">ファイルまたはディレクトリのパス</span><span class="sxs-lookup"><span data-stu-id="a1ab2-139">Path of the file or directory</span></span></param>
        <param name="rwx"><span data-ttu-id="a1ab2-140">"Rwx"の文字列形式のチェックインを許可します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-140">Permission to check in "rwx" string form.</span></span> <span data-ttu-id="a1ab2-141">例をユーザーがかどうかに読み取りを参照する場合は、アクセス許可を実行、文字列になります r x</span><span class="sxs-lookup"><span data-stu-id="a1ab2-141">For example if the user wants to see if it has read, execute permission, the string would be r-x</span></span> </param>
        <param name="client"><span data-ttu-id="a1ab2-142">ADLS クライアント</span><span class="sxs-lookup"><span data-stu-id="a1ab2-142">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="a1ab2-143">Http 要求の動作を変更するオプション</span><span class="sxs-lookup"><span data-stu-id="a1ab2-143">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="a1ab2-144">Http 要求の応答/出力の格納します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-144">Stores the response/ouput of the Http request</span></span> </param>
        <param name="cancelToken"><span data-ttu-id="a1ab2-145">CancellationToken 要求を取り消します</span><span class="sxs-lookup"><span data-stu-id="a1ab2-145">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="a1ab2-146">ユーザー/グループが、指定されたパスへのアクセスを指定したかを確認します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-146">Checks if the user/group has specified access of the given path</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConcatAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ConcatAsync (string path, System.Collections.Generic.List&lt;string&gt; sourceFiles, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ConcatAsync(string path, class System.Collections.Generic.List`1&lt;string&gt; sourceFiles, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.ConcatAsync(System.String,System.Collections.Generic.List{System.String},Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ConcatAsync (path As String, sourceFiles As List(Of String), client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="static member ConcatAsync : string * System.Collections.Generic.List&lt;string&gt; * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.DataLake.Store.Core.ConcatAsync (path, sourceFiles, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;ConcatAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="sourceFiles" Type="System.Collections.Generic.List&lt;System.String&gt;" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="a1ab2-147">変換先のパス</span><span class="sxs-lookup"><span data-stu-id="a1ab2-147">Path of the destination</span></span></param>
        <param name="sourceFiles"><span data-ttu-id="a1ab2-148">ソース ファイルのパスを含むリスト</span><span class="sxs-lookup"><span data-stu-id="a1ab2-148">List containing paths of the source files</span></span></param>
        <param name="client"><span data-ttu-id="a1ab2-149">ADLS クライアント</span><span class="sxs-lookup"><span data-stu-id="a1ab2-149">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="a1ab2-150">Http 要求の動作を変更するオプション</span><span class="sxs-lookup"><span data-stu-id="a1ab2-150">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="a1ab2-151">Http 要求の応答/出力の格納します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-151">Stores the response/ouput of the Http request</span></span> </param>
        <param name="cancelToken"><span data-ttu-id="a1ab2-152">CancellationToken 要求を取り消します</span><span class="sxs-lookup"><span data-stu-id="a1ab2-152">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="a1ab2-153">対象のファイルにソース ファイルを連結します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-153">Concatenate source files to a destination file.</span></span> <span data-ttu-id="a1ab2-154">既定ではソース ディレクトリを削除しません。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-154">By default it wont delete source directory</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConcatAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ConcatAsync (string path, System.Collections.Generic.List&lt;string&gt; sourceFiles, bool deleteSourceDirectory, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ConcatAsync(string path, class System.Collections.Generic.List`1&lt;string&gt; sourceFiles, bool deleteSourceDirectory, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.ConcatAsync(System.String,System.Collections.Generic.List{System.String},System.Boolean,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ConcatAsync (path As String, sourceFiles As List(Of String), deleteSourceDirectory As Boolean, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="static member ConcatAsync : string * System.Collections.Generic.List&lt;string&gt; * bool * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.DataLake.Store.Core.ConcatAsync (path, sourceFiles, deleteSourceDirectory, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;ConcatAsync&gt;d__16))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="sourceFiles" Type="System.Collections.Generic.List&lt;System.String&gt;" />
        <Parameter Name="deleteSourceDirectory" Type="System.Boolean" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="a1ab2-155">変換先のパス</span><span class="sxs-lookup"><span data-stu-id="a1ab2-155">Path of the destination</span></span></param>
        <param name="sourceFiles"><span data-ttu-id="a1ab2-156">ソース ファイルのパスを含むリスト</span><span class="sxs-lookup"><span data-stu-id="a1ab2-156">List containing paths of the source files</span></span></param>
        <param name="deleteSourceDirectory"><span data-ttu-id="a1ab2-157">True の場合、削除、ソース ディレクトリその下にあるすべてのファイルを連結する場合</span><span class="sxs-lookup"><span data-stu-id="a1ab2-157">If true then deletes the source directory if all the files under it are concatenated</span></span></param>
        <param name="client"><span data-ttu-id="a1ab2-158">ADLS クライアント</span><span class="sxs-lookup"><span data-stu-id="a1ab2-158">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="a1ab2-159">Http 要求の動作を変更するオプション</span><span class="sxs-lookup"><span data-stu-id="a1ab2-159">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="a1ab2-160">Http 要求の応答/出力の格納します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-160">Stores the response/ouput of the Http request</span></span> </param>
        <param name="cancelToken"><span data-ttu-id="a1ab2-161">CancellationToken 要求を取り消します</span><span class="sxs-lookup"><span data-stu-id="a1ab2-161">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="a1ab2-162">対象のファイルにソース ファイルを連結します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-162">Concatenate source files to a destination file</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConcurrentAppend">
      <MemberSignature Language="C#" Value="public static void ConcurrentAppend (string path, bool autoCreate, byte[] dataBytes, int offset, int length, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ConcurrentAppend(string path, bool autoCreate, unsigned int8[] dataBytes, int32 offset, int32 length, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.ConcurrentAppend(System.String,System.Boolean,System.Byte[],System.Int32,System.Int32,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub ConcurrentAppend (path As String, autoCreate As Boolean, dataBytes As Byte(), offset As Integer, length As Integer, client As AdlsClient, req As RequestOptions, resp As OperationResponse)" />
      <MemberSignature Language="F#" Value="static member ConcurrentAppend : string * bool * byte[] * int * int * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse -&gt; unit" Usage="Microsoft.Azure.DataLake.Store.Core.ConcurrentAppend (path, autoCreate, dataBytes, offset, length, client, req, resp)" />
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
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="autoCreate" Type="System.Boolean" />
        <Parameter Name="dataBytes" Type="System.Byte[]" />
        <Parameter Name="offset" Type="System.Int32" />
        <Parameter Name="length" Type="System.Int32" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="a1ab2-163">ファイルのパス</span><span class="sxs-lookup"><span data-stu-id="a1ab2-163">Path of the file</span></span></param>
        <param name="autoCreate"></param>
        <param name="dataBytes"><span data-ttu-id="a1ab2-164">ファイルに書き込むバイトの配列</span><span class="sxs-lookup"><span data-stu-id="a1ab2-164">Array of bytes to write to the file</span></span></param>
        <param name="offset"><span data-ttu-id="a1ab2-165">バイト配列内のオフセットします。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-165">Offset in the byte array</span></span></param>
        <param name="length"><span data-ttu-id="a1ab2-166">オフセット位置から書き込むバイト数</span><span class="sxs-lookup"><span data-stu-id="a1ab2-166">Number of bytes to write from the offset</span></span></param>
        <param name="client"><span data-ttu-id="a1ab2-167">ADLS クライアント</span><span class="sxs-lookup"><span data-stu-id="a1ab2-167">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="a1ab2-168">Http 要求の動作を変更するオプション</span><span class="sxs-lookup"><span data-stu-id="a1ab2-168">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="a1ab2-169">Http 要求の応答/出力の格納します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-169">Stores the response/ouput of the Http request</span></span> </param>
        <summary>
            <span data-ttu-id="a1ab2-170">実行のサーバーで同時実行を同期的に追加します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-170">Performs concurrent append synchronously at server.</span></span> <span data-ttu-id="a1ab2-171">オフセットが発生する追加はサーバーによって決まります</span><span class="sxs-lookup"><span data-stu-id="a1ab2-171">The offset at which append will occur is determined by server</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConcurrentAppendAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ConcurrentAppendAsync (string path, bool autoCreate, byte[] dataBytes, int offset, int length, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ConcurrentAppendAsync(string path, bool autoCreate, unsigned int8[] dataBytes, int32 offset, int32 length, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.ConcurrentAppendAsync(System.String,System.Boolean,System.Byte[],System.Int32,System.Int32,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ConcurrentAppendAsync (path As String, autoCreate As Boolean, dataBytes As Byte(), offset As Integer, length As Integer, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="static member ConcurrentAppendAsync : string * bool * byte[] * int * int * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.DataLake.Store.Core.ConcurrentAppendAsync (path, autoCreate, dataBytes, offset, length, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;ConcurrentAppendAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="autoCreate" Type="System.Boolean" />
        <Parameter Name="dataBytes" Type="System.Byte[]" />
        <Parameter Name="offset" Type="System.Int32" />
        <Parameter Name="length" Type="System.Int32" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="a1ab2-172">ファイルのパス</span><span class="sxs-lookup"><span data-stu-id="a1ab2-172">Path of the file</span></span></param>
        <param name="autoCreate"></param>
        <param name="dataBytes"><span data-ttu-id="a1ab2-173">ファイルに書き込むバイトの配列</span><span class="sxs-lookup"><span data-stu-id="a1ab2-173">Array of bytes to write to the file</span></span></param>
        <param name="offset"><span data-ttu-id="a1ab2-174">バイト配列内のオフセットします。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-174">Offset in the byte array</span></span></param>
        <param name="length"><span data-ttu-id="a1ab2-175">オフセット位置から書き込むバイト数</span><span class="sxs-lookup"><span data-stu-id="a1ab2-175">Number of bytes to write from the offset</span></span></param>
        <param name="client"><span data-ttu-id="a1ab2-176">ADLS クライアント</span><span class="sxs-lookup"><span data-stu-id="a1ab2-176">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="a1ab2-177">Http 要求の動作を変更するオプション</span><span class="sxs-lookup"><span data-stu-id="a1ab2-177">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="a1ab2-178">Http 要求の応答/出力の格納します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-178">Stores the response/ouput of the Http request</span></span> </param>
        <param name="cancelToken"><span data-ttu-id="a1ab2-179">CancellationToken 要求を取り消します</span><span class="sxs-lookup"><span data-stu-id="a1ab2-179">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="a1ab2-180">実行サーバーで同時実行が非同期的に追加します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-180">Performs concurrent append asynchronously at server.</span></span> <span data-ttu-id="a1ab2-181">オフセットが発生する追加はサーバーによって決まります</span><span class="sxs-lookup"><span data-stu-id="a1ab2-181">The offset at which append will occur is determined by server</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static void Create (string path, bool overwrite, string octalPermission, string leaseId, string sessionId, bool createParent, Microsoft.Azure.DataLake.Store.SyncFlag flag, byte[] dataBytes, int offset, int length, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Create(string path, bool overwrite, string octalPermission, string leaseId, string sessionId, bool createParent, valuetype Microsoft.Azure.DataLake.Store.SyncFlag flag, unsigned int8[] dataBytes, int32 offset, int32 length, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.Create(System.String,System.Boolean,System.String,System.String,System.String,System.Boolean,Microsoft.Azure.DataLake.Store.SyncFlag,System.Byte[],System.Int32,System.Int32,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub Create (path As String, overwrite As Boolean, octalPermission As String, leaseId As String, sessionId As String, createParent As Boolean, flag As SyncFlag, dataBytes As Byte(), offset As Integer, length As Integer, client As AdlsClient, req As RequestOptions, resp As OperationResponse)" />
      <MemberSignature Language="F#" Value="static member Create : string * bool * string * string * string * bool * Microsoft.Azure.DataLake.Store.SyncFlag * byte[] * int * int * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse -&gt; unit" Usage="Microsoft.Azure.DataLake.Store.Core.Create (path, overwrite, octalPermission, leaseId, sessionId, createParent, flag, dataBytes, offset, length, client, req, resp)" />
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
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="overwrite" Type="System.Boolean" />
        <Parameter Name="octalPermission" Type="System.String" />
        <Parameter Name="leaseId" Type="System.String" />
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="createParent" Type="System.Boolean" />
        <Parameter Name="flag" Type="Microsoft.Azure.DataLake.Store.SyncFlag" />
        <Parameter Name="dataBytes" Type="System.Byte[]" />
        <Parameter Name="offset" Type="System.Int32" />
        <Parameter Name="length" Type="System.Int32" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="a1ab2-182">ファイルのパス</span><span class="sxs-lookup"><span data-stu-id="a1ab2-182">Path of the file</span></span></param>
        <param name="overwrite"><span data-ttu-id="a1ab2-183">フラグが true の場合、既存のファイルが上書きされます。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-183">Overwrites the existing file if the flag is true</span></span></param>
        <param name="octalPermission"><span data-ttu-id="a1ab2-184">8 進数のアクセス許可文字列</span><span class="sxs-lookup"><span data-stu-id="a1ab2-184">Octal permission string</span></span></param>
        <param name="leaseId"><span data-ttu-id="a1ab2-185">ファイルの編集を行うことができます、クライアントはその他のクライアント ファイル上のリースを取得する際に、リース ID を含む文字列</span><span class="sxs-lookup"><span data-stu-id="a1ab2-185">String containing the lease ID, when a client obtains a lease on a file no other client can make edits to the file</span></span> </param>
        <param name="sessionId"><span data-ttu-id="a1ab2-186">サーバーに簡単にファイル ハンドラー (ストリーム) を取得するために使用する UUID</span><span class="sxs-lookup"><span data-stu-id="a1ab2-186">UUID that is used to obtain the file handler (stream) easily at server</span></span></param>
        <param name="createParent"><span data-ttu-id="a1ab2-187">True の場合は、存在しない親ディレクトリを作成します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-187">If true creates any non-existing parent directories</span></span></param>
        <param name="flag"><span data-ttu-id="a1ab2-188">ファイルのメタデータなどの長さ、変更されたときにデータを渡す SyncFlag.METADATA のバイトを書き込むときに、SyncFlag.DATA を渡すインスタント ファイルの実際のデータと一致するように更新する必要があります。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-188">Pass SyncFlag.DATA when writing bytes of data Pass SyncFlag.METADATA when metadata of the file like length, modified instant needs to be updated to be consistent with the actual data of file.</span></span> <span data-ttu-id="a1ab2-189">SyncFlag.METADATA GetFileStatus と ListStatus を渡した後に一貫性のあるデータを返します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-189">After passing SyncFlag.METADATA GetFileStatus and ListStatus returns consistent data.</span></span>
                               <span data-ttu-id="a1ab2-190">以上のデータを追加する必要がある、ファイルのメタデータを更新、リースの解放およびストリームが閉じているときに、SyncFlag.CLOSE を渡す</span><span class="sxs-lookup"><span data-stu-id="a1ab2-190">Pass SyncFlag.CLOSE when no more data needs to be appended, file metadata is updated, lease is released and the stream is closed</span></span>  </param>
        <param name="dataBytes"><span data-ttu-id="a1ab2-191">ファイルに書き込むバイトの配列</span><span class="sxs-lookup"><span data-stu-id="a1ab2-191">Array of bytes to write to the file</span></span></param>
        <param name="offset"><span data-ttu-id="a1ab2-192">バイト配列内のオフセットします。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-192">Offset in the byte array</span></span></param>
        <param name="length"><span data-ttu-id="a1ab2-193">オフセット位置から書き込むバイト数</span><span class="sxs-lookup"><span data-stu-id="a1ab2-193">Number of bytes to write from the offset</span></span></param>
        <param name="client"><span data-ttu-id="a1ab2-194">ADLS クライアント</span><span class="sxs-lookup"><span data-stu-id="a1ab2-194">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="a1ab2-195">Http 要求の動作を変更するオプション</span><span class="sxs-lookup"><span data-stu-id="a1ab2-195">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="a1ab2-196">Http 要求の応答/出力の格納します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-196">Stores the response/ouput of the Http request</span></span> </param>
        <summary>
            <span data-ttu-id="a1ab2-197">新しいファイルを作成します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-197">Create a new file.</span></span> <span data-ttu-id="a1ab2-198">これは、同期操作です。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-198">This is a synchronous operation.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CreateAsync (string path, bool overwrite, string octalPermission, string leaseId, string sessionId, bool createParent, Microsoft.Azure.DataLake.Store.SyncFlag flag, byte[] dataBytes, int offset, int length, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CreateAsync(string path, bool overwrite, string octalPermission, string leaseId, string sessionId, bool createParent, valuetype Microsoft.Azure.DataLake.Store.SyncFlag flag, unsigned int8[] dataBytes, int32 offset, int32 length, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.CreateAsync(System.String,System.Boolean,System.String,System.String,System.String,System.Boolean,Microsoft.Azure.DataLake.Store.SyncFlag,System.Byte[],System.Int32,System.Int32,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateAsync (path As String, overwrite As Boolean, octalPermission As String, leaseId As String, sessionId As String, createParent As Boolean, flag As SyncFlag, dataBytes As Byte(), offset As Integer, length As Integer, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="static member CreateAsync : string * bool * string * string * string * bool * Microsoft.Azure.DataLake.Store.SyncFlag * byte[] * int * int * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.DataLake.Store.Core.CreateAsync (path, overwrite, octalPermission, leaseId, sessionId, createParent, flag, dataBytes, offset, length, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;CreateAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="overwrite" Type="System.Boolean" />
        <Parameter Name="octalPermission" Type="System.String" />
        <Parameter Name="leaseId" Type="System.String" />
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="createParent" Type="System.Boolean" />
        <Parameter Name="flag" Type="Microsoft.Azure.DataLake.Store.SyncFlag" />
        <Parameter Name="dataBytes" Type="System.Byte[]" />
        <Parameter Name="offset" Type="System.Int32" />
        <Parameter Name="length" Type="System.Int32" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="a1ab2-199">ファイルのパス</span><span class="sxs-lookup"><span data-stu-id="a1ab2-199">Path of the file</span></span></param>
        <param name="overwrite"><span data-ttu-id="a1ab2-200">フラグが true の場合、既存のファイルが上書きされます。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-200">Overwrites the existing file if the flag is true</span></span></param>
        <param name="octalPermission"><span data-ttu-id="a1ab2-201">8 進数のアクセス許可文字列</span><span class="sxs-lookup"><span data-stu-id="a1ab2-201">Octal permission string</span></span></param>
        <param name="leaseId"><span data-ttu-id="a1ab2-202">ファイルの編集を行うことができます、クライアントはその他のクライアント ファイル上のリースを取得する際に、リース ID を含む文字列</span><span class="sxs-lookup"><span data-stu-id="a1ab2-202">String containing the lease ID, when a client obtains a lease on a file no other client can make edits to the file</span></span> </param>
        <param name="sessionId"><span data-ttu-id="a1ab2-203">サーバーに簡単にファイル ハンドラー (ストリーム) を取得するために使用する UUID</span><span class="sxs-lookup"><span data-stu-id="a1ab2-203">UUID that is used to obtain the file handler (stream) easily at server</span></span></param>
        <param name="createParent"><span data-ttu-id="a1ab2-204">True の場合は、存在しない親ディレクトリを作成します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-204">If true creates any non-existing parent directories</span></span></param>
        <param name="flag"><span data-ttu-id="a1ab2-205">ファイルのメタデータなどの長さ、変更されたときにデータを渡す SyncFlag.METADATA のバイトを書き込むときに、SyncFlag.DATA を渡すインスタント ファイルの実際のデータと一致するように更新する必要があります。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-205">Pass SyncFlag.DATA when writing bytes of data Pass SyncFlag.METADATA when metadata of the file like length, modified instant needs to be updated to be consistent with the actual data of file.</span></span> <span data-ttu-id="a1ab2-206">SyncFlag.METADATA GetFileStatus と ListStatus を渡した後に一貫性のあるデータを返します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-206">After passing SyncFlag.METADATA GetFileStatus and ListStatus returns consistent data.</span></span>
                               <span data-ttu-id="a1ab2-207">以上のデータを追加する必要がある、ファイルのメタデータを更新、リースの解放およびストリームが閉じているときに、SyncFlag.CLOSE を渡す</span><span class="sxs-lookup"><span data-stu-id="a1ab2-207">Pass SyncFlag.CLOSE when no more data needs to be appended, file metadata is updated, lease is released and the stream is closed</span></span>  </param>
        <param name="dataBytes"><span data-ttu-id="a1ab2-208">ファイルに書き込むバイトの配列</span><span class="sxs-lookup"><span data-stu-id="a1ab2-208">Array of bytes to write to the file</span></span></param>
        <param name="offset"><span data-ttu-id="a1ab2-209">バイト配列内のオフセットします。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-209">Offset in the byte array</span></span></param>
        <param name="length"><span data-ttu-id="a1ab2-210">オフセット位置から書き込むバイト数</span><span class="sxs-lookup"><span data-stu-id="a1ab2-210">Number of bytes to write from the offset</span></span></param>
        <param name="client"><span data-ttu-id="a1ab2-211">ADLS クライアント</span><span class="sxs-lookup"><span data-stu-id="a1ab2-211">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="a1ab2-212">Http 要求の動作を変更するオプション</span><span class="sxs-lookup"><span data-stu-id="a1ab2-212">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="a1ab2-213">Http 要求の応答/出力の格納します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-213">Stores the response/ouput of the Http request</span></span> </param>
        <param name="cancelToken"><span data-ttu-id="a1ab2-214">CancellationToken 要求を取り消します</span><span class="sxs-lookup"><span data-stu-id="a1ab2-214">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="a1ab2-215">新しいファイルを作成します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-215">Create a new file.</span></span> <span data-ttu-id="a1ab2-216">これは非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-216">This is an asynchronous operation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;bool&gt; DeleteAsync (string path, bool recursive, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteAsync(string path, bool recursive, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.DeleteAsync(System.String,System.Boolean,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function DeleteAsync (path As String, recursive As Boolean, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : string * bool * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="Microsoft.Azure.DataLake.Store.Core.DeleteAsync (path, recursive, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;DeleteAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="recursive" Type="System.Boolean" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="a1ab2-217">ファイルまたはディレクトリのパス</span><span class="sxs-lookup"><span data-stu-id="a1ab2-217">Path of the file or directory</span></span></param>
        <param name="recursive"></param>
        <param name="client"><span data-ttu-id="a1ab2-218">ADLS クライアント</span><span class="sxs-lookup"><span data-stu-id="a1ab2-218">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="a1ab2-219">Http 要求の動作を変更するオプション</span><span class="sxs-lookup"><span data-stu-id="a1ab2-219">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="a1ab2-220">Http 要求の応答/出力の格納します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-220">Stores the response/ouput of the Http request</span></span> </param>
        <param name="cancelToken"><span data-ttu-id="a1ab2-221">CancellationToken 要求を取り消します</span><span class="sxs-lookup"><span data-stu-id="a1ab2-221">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="a1ab2-222">ファイルまたはディレクトリを削除します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-222">Deletes a file or directory</span></span>
            </summary>
        <returns><span data-ttu-id="a1ab2-223">削除が成功した場合は true。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-223">True if delete is successful</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAclStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.DataLake.Store.Acl.AclStatus&gt; GetAclStatusAsync (string path, Nullable&lt;Microsoft.Azure.DataLake.Store.UserGroupRepresentation&gt; userIdFormat, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.DataLake.Store.Acl.AclStatus&gt; GetAclStatusAsync(string path, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.DataLake.Store.UserGroupRepresentation&gt; userIdFormat, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.GetAclStatusAsync(System.String,System.Nullable{Microsoft.Azure.DataLake.Store.UserGroupRepresentation},Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetAclStatusAsync (path As String, userIdFormat As Nullable(Of UserGroupRepresentation), client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task(Of AclStatus)" />
      <MemberSignature Language="F#" Value="static member GetAclStatusAsync : string * Nullable&lt;Microsoft.Azure.DataLake.Store.UserGroupRepresentation&gt; * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.DataLake.Store.Acl.AclStatus&gt;" Usage="Microsoft.Azure.DataLake.Store.Core.GetAclStatusAsync (path, userIdFormat, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;GetAclStatusAsync&gt;d__32))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.DataLake.Store.Acl.AclStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="userIdFormat" Type="System.Nullable&lt;Microsoft.Azure.DataLake.Store.UserGroupRepresentation&gt;" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="a1ab2-224">ファイルまたはディレクトリのパス</span><span class="sxs-lookup"><span data-stu-id="a1ab2-224">Path of the file or directory</span></span></param>
        <param name="userIdFormat"><span data-ttu-id="a1ab2-225">ユーザー/グループ オブジェクトを表現する方法</span><span class="sxs-lookup"><span data-stu-id="a1ab2-225">way to represent the user/group object</span></span></param>
        <param name="client"><span data-ttu-id="a1ab2-226">ADLS クライアント</span><span class="sxs-lookup"><span data-stu-id="a1ab2-226">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="a1ab2-227">Http 要求の動作を変更するオプション</span><span class="sxs-lookup"><span data-stu-id="a1ab2-227">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="a1ab2-228">Http 要求の応答/出力の格納します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-228">Stores the response/ouput of the Http request</span></span> </param>
        <param name="cancelToken"><span data-ttu-id="a1ab2-229">CancellationToken 要求を取り消します</span><span class="sxs-lookup"><span data-stu-id="a1ab2-229">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="a1ab2-230">ACL エントリの一覧、所有者 ID、グループ ID、8 進数のアクセス許可およびファイルまたはディレクトリの (ディレクトリ) の場合のみ sticky ビットを取得します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-230">Gets the ACL entry list, owner ID, group ID, octal permission and sticky bit (only for a directory) of the file/directory</span></span>
            </summary>
        <returns><span data-ttu-id="a1ab2-231">Acl 情報: ACL エントリの一覧、所有者 ID、ID、8 進数のアクセス許可、および sticky ビットをグループ化</span><span class="sxs-lookup"><span data-stu-id="a1ab2-231">Acl information: ACL entry list, owner ID, group ID, octal permission and sticky bit</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetContentSummaryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.DataLake.Store.ContentSummary&gt; GetContentSummaryAsync (string path, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.DataLake.Store.ContentSummary&gt; GetContentSummaryAsync(string path, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.GetContentSummaryAsync(System.String,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetContentSummaryAsync (path As String, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task(Of ContentSummary)" />
      <MemberSignature Language="F#" Value="static member GetContentSummaryAsync : string * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.DataLake.Store.ContentSummary&gt;" Usage="Microsoft.Azure.DataLake.Store.Core.GetContentSummaryAsync (path, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;GetContentSummaryAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.DataLake.Store.ContentSummary&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="a1ab2-232">ディレクトリまたはファイルのパス</span><span class="sxs-lookup"><span data-stu-id="a1ab2-232">Path of the directory or file</span></span></param>
        <param name="client"><span data-ttu-id="a1ab2-233">ADLS クライアント</span><span class="sxs-lookup"><span data-stu-id="a1ab2-233">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="a1ab2-234">Http 要求の動作を変更するオプション</span><span class="sxs-lookup"><span data-stu-id="a1ab2-234">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="a1ab2-235">Http 要求の応答/出力の格納します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-235">Stores the response/ouput of the Http request</span></span> </param>
        <param name="cancelToken"><span data-ttu-id="a1ab2-236">CancellationToken 要求を取り消します</span><span class="sxs-lookup"><span data-stu-id="a1ab2-236">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="a1ab2-237">ファイルまたはディレクトリのコンテンツの概要を取得します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-237">Gets content summary of a file or directory</span></span>
            </summary>
        <returns><span data-ttu-id="a1ab2-238">パスの ContentSummary</span><span class="sxs-lookup"><span data-stu-id="a1ab2-238">ContentSummary of the path</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFileStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.DataLake.Store.DirectoryEntry&gt; GetFileStatusAsync (string path, Nullable&lt;Microsoft.Azure.DataLake.Store.UserGroupRepresentation&gt; userIdFormat, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.DataLake.Store.DirectoryEntry&gt; GetFileStatusAsync(string path, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.DataLake.Store.UserGroupRepresentation&gt; userIdFormat, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.GetFileStatusAsync(System.String,System.Nullable{Microsoft.Azure.DataLake.Store.UserGroupRepresentation},Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFileStatusAsync (path As String, userIdFormat As Nullable(Of UserGroupRepresentation), client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task(Of DirectoryEntry)" />
      <MemberSignature Language="F#" Value="static member GetFileStatusAsync : string * Nullable&lt;Microsoft.Azure.DataLake.Store.UserGroupRepresentation&gt; * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.DataLake.Store.DirectoryEntry&gt;" Usage="Microsoft.Azure.DataLake.Store.Core.GetFileStatusAsync (path, userIdFormat, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;GetFileStatusAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.DataLake.Store.DirectoryEntry&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="userIdFormat" Type="System.Nullable&lt;Microsoft.Azure.DataLake.Store.UserGroupRepresentation&gt;" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="a1ab2-239">ファイルまたはディレクトリのパス</span><span class="sxs-lookup"><span data-stu-id="a1ab2-239">Path of the file or directory</span></span></param>
        <param name="userIdFormat"><span data-ttu-id="a1ab2-240">ユーザーまたはグループのオブジェクトの表現方法</span><span class="sxs-lookup"><span data-stu-id="a1ab2-240">Way the user or group object will be represented</span></span></param>
        <param name="client"><span data-ttu-id="a1ab2-241">ADLS クライアント</span><span class="sxs-lookup"><span data-stu-id="a1ab2-241">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="a1ab2-242">Http 要求の動作を変更するオプション</span><span class="sxs-lookup"><span data-stu-id="a1ab2-242">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="a1ab2-243">Http 要求の応答/出力の格納します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-243">Stores the response/ouput of the Http request</span></span> </param>
        <param name="cancelToken"><span data-ttu-id="a1ab2-244">CancellationToken 要求を取り消します</span><span class="sxs-lookup"><span data-stu-id="a1ab2-244">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="a1ab2-245">完全なパス、種類 (ファイルまたはディレクトリ)、グループ、ユーザー、アクセス許可、長さ、メタ データを取得最終アクセス時刻、最終更新時刻、有効期限、acl ビット、レプリケーション係数</span><span class="sxs-lookup"><span data-stu-id="a1ab2-245">Gets meta data like full path, type (file or directory), group, user, permission, length,last Access Time,last Modified Time, expiry time, acl Bit, replication Factor</span></span>
            </summary>
        <returns><span data-ttu-id="a1ab2-246">ファイルまたはディレクトリのメタデータを返します</span><span class="sxs-lookup"><span data-stu-id="a1ab2-246">Returns the metadata of the file or directory</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.DirectoryEntry&gt;&gt; ListStatusAsync (string path, string listAfter, string listBefore, int listSize, Nullable&lt;Microsoft.Azure.DataLake.Store.UserGroupRepresentation&gt; userIdFormat, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.List`1&lt;class Microsoft.Azure.DataLake.Store.DirectoryEntry&gt;&gt; ListStatusAsync(string path, string listAfter, string listBefore, int32 listSize, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.DataLake.Store.UserGroupRepresentation&gt; userIdFormat, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.ListStatusAsync(System.String,System.String,System.String,System.Int32,System.Nullable{Microsoft.Azure.DataLake.Store.UserGroupRepresentation},Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ListStatusAsync (path As String, listAfter As String, listBefore As String, listSize As Integer, userIdFormat As Nullable(Of UserGroupRepresentation), client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task(Of List(Of DirectoryEntry))" />
      <MemberSignature Language="F#" Value="static member ListStatusAsync : string * string * string * int * Nullable&lt;Microsoft.Azure.DataLake.Store.UserGroupRepresentation&gt; * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.DirectoryEntry&gt;&gt;" Usage="Microsoft.Azure.DataLake.Store.Core.ListStatusAsync (path, listAfter, listBefore, listSize, userIdFormat, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;ListStatusAsync&gt;d__18))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.DirectoryEntry&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="listAfter" Type="System.String" />
        <Parameter Name="listBefore" Type="System.String" />
        <Parameter Name="listSize" Type="System.Int32" />
        <Parameter Name="userIdFormat" Type="System.Nullable&lt;Microsoft.Azure.DataLake.Store.UserGroupRepresentation&gt;" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="a1ab2-247">ディレクトリのパス</span><span class="sxs-lookup"><span data-stu-id="a1ab2-247">Path of the directory</span></span></param>
        <param name="listAfter"><span data-ttu-id="a1ab2-248">ファイル名をサーバーからファイルの一覧を取得する必要があります。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-248">Filename after which list of files should be obtained from server</span></span></param>
        <param name="listBefore"><span data-ttu-id="a1ab2-249">これまでは、サーバーからファイルの一覧を取得するファイル名</span><span class="sxs-lookup"><span data-stu-id="a1ab2-249">Filename till which list of files should be obtained from server</span></span></param>
        <param name="listSize"><span data-ttu-id="a1ab2-250">サーバーから取得するリストのサイズ</span><span class="sxs-lookup"><span data-stu-id="a1ab2-250">List size to obtain from server</span></span></param>
        <param name="userIdFormat"><span data-ttu-id="a1ab2-251">ユーザーまたはグループのオブジェクトの表現方法</span><span class="sxs-lookup"><span data-stu-id="a1ab2-251">Way the user or group object will be represented</span></span></param>
        <param name="client"><span data-ttu-id="a1ab2-252">ADLS クライアント</span><span class="sxs-lookup"><span data-stu-id="a1ab2-252">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="a1ab2-253">Http 要求の動作を変更するオプション</span><span class="sxs-lookup"><span data-stu-id="a1ab2-253">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="a1ab2-254">Http 要求の応答/出力の格納します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-254">Stores the response/ouput of the Http request</span></span> </param>
        <param name="cancelToken"><span data-ttu-id="a1ab2-255">CancellationToken 要求を取り消します</span><span class="sxs-lookup"><span data-stu-id="a1ab2-255">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="a1ab2-256">サブディレクトリまたはディレクトリに含まれているファイルを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-256">Lists the sub-directories or files contained in a directory</span></span>
            </summary>
        <returns><span data-ttu-id="a1ab2-257">Directoryentries の一覧</span><span class="sxs-lookup"><span data-stu-id="a1ab2-257">List of directoryentries</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MkdirsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;bool&gt; MkdirsAsync (string path, string octalPermission, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;bool&gt; MkdirsAsync(string path, string octalPermission, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.MkdirsAsync(System.String,System.String,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function MkdirsAsync (path As String, octalPermission As String, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="static member MkdirsAsync : string * string * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="Microsoft.Azure.DataLake.Store.Core.MkdirsAsync (path, octalPermission, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;MkdirsAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="octalPermission" Type="System.String" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="a1ab2-258">ディレクトリのパス</span><span class="sxs-lookup"><span data-stu-id="a1ab2-258">Path of the directory</span></span></param>
        <param name="octalPermission"><span data-ttu-id="a1ab2-259">8 進数のアクセス許可</span><span class="sxs-lookup"><span data-stu-id="a1ab2-259">Octal Permission</span></span></param>
        <param name="client"><span data-ttu-id="a1ab2-260">ADLS クライアント</span><span class="sxs-lookup"><span data-stu-id="a1ab2-260">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="a1ab2-261">Http 要求の動作を変更するオプション</span><span class="sxs-lookup"><span data-stu-id="a1ab2-261">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="a1ab2-262">Http 要求の応答/出力の格納します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-262">Stores the response/ouput of the Http request</span></span> </param>
        <param name="cancelToken"><span data-ttu-id="a1ab2-263">CancellationToken 要求を取り消します</span><span class="sxs-lookup"><span data-stu-id="a1ab2-263">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="a1ab2-264">ディレクトリを作成します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-264">Creates a directory.</span></span> 
            </summary>
        <returns><span data-ttu-id="a1ab2-265">それ以外の場合は false、ディレクトリを作成する場合は true。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-265">true if it creates the directory else false</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ModifyAclEntriesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ModifyAclEntriesAsync (string path, System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; aclSpecList, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ModifyAclEntriesAsync(string path, class System.Collections.Generic.List`1&lt;class Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; aclSpecList, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.ModifyAclEntriesAsync(System.String,System.Collections.Generic.List{Microsoft.Azure.DataLake.Store.Acl.AclEntry},Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ModifyAclEntriesAsync (path As String, aclSpecList As List(Of AclEntry), client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="static member ModifyAclEntriesAsync : string * System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.DataLake.Store.Core.ModifyAclEntriesAsync (path, aclSpecList, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;ModifyAclEntriesAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclSpecList" Type="System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt;" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="a1ab2-266">ファイルまたはディレクトリのパス</span><span class="sxs-lookup"><span data-stu-id="a1ab2-266">Path of the file or directory</span></span></param>
        <param name="aclSpecList"><span data-ttu-id="a1ab2-267">変更する Acl エントリの一覧</span><span class="sxs-lookup"><span data-stu-id="a1ab2-267">List of Acl Entries to modify</span></span></param>
        <param name="client"><span data-ttu-id="a1ab2-268">ADLS クライアント</span><span class="sxs-lookup"><span data-stu-id="a1ab2-268">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="a1ab2-269">Http 要求の動作を変更するオプション</span><span class="sxs-lookup"><span data-stu-id="a1ab2-269">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="a1ab2-270">Http 要求の応答/出力の格納します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-270">Stores the response/ouput of the Http request</span></span> </param>
        <param name="cancelToken"><span data-ttu-id="a1ab2-271">CancellationToken 要求を取り消します</span><span class="sxs-lookup"><span data-stu-id="a1ab2-271">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="a1ab2-272">ファイルの acl エントリを変更またはディレクトリが指定した ACL リスト。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-272">Modifies acl entries of a file or directory with given ACL list.</span></span> <span data-ttu-id="a1ab2-273">既存の ACL を結合で指定したリスト ボックスの一覧です。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-273">It merges the exisitng ACL list with given list.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ModifyAclEntriesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ModifyAclEntriesAsync (string path, string aclSpec, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ModifyAclEntriesAsync(string path, string aclSpec, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.ModifyAclEntriesAsync(System.String,System.String,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ModifyAclEntriesAsync (path As String, aclSpec As String, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="static member ModifyAclEntriesAsync : string * string * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.DataLake.Store.Core.ModifyAclEntriesAsync (path, aclSpec, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;ModifyAclEntriesAsync&gt;d__24))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclSpec" Type="System.String" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="a1ab2-274">ファイルまたはディレクトリのパス</span><span class="sxs-lookup"><span data-stu-id="a1ab2-274">Path of the file or directory</span></span></param>
        <param name="aclSpec"><span data-ttu-id="a1ab2-275">コンマで区切られます ACL エントリを含む AclSpec 文字列</span><span class="sxs-lookup"><span data-stu-id="a1ab2-275">AclSpec string that contains the ACL entries delimited by comma</span></span> </param>
        <param name="client"><span data-ttu-id="a1ab2-276">ADLS クライアント</span><span class="sxs-lookup"><span data-stu-id="a1ab2-276">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="a1ab2-277">Http 要求の動作を変更するオプション</span><span class="sxs-lookup"><span data-stu-id="a1ab2-277">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="a1ab2-278">Http 要求の応答/出力の格納します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-278">Stores the response/ouput of the Http request</span></span> </param>
        <param name="cancelToken"><span data-ttu-id="a1ab2-279">CancellationToken 要求を取り消します</span><span class="sxs-lookup"><span data-stu-id="a1ab2-279">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="a1ab2-280">ファイルの acl エントリを変更またはディレクトリが指定した ACL リスト。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-280">Modifies acl entries of a file or directory with given ACL list.</span></span> <span data-ttu-id="a1ab2-281">既存の ACL を結合で指定したリスト ボックスの一覧です。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-281">It merges the exisitng ACL list with given list.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Open">
      <MemberSignature Language="C#" Value="public static int Open (string path, string sessionId, long offsetFile, byte[] buffer, int offset, int lengthFile, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig int32 Open(string path, string sessionId, int64 offsetFile, unsigned int8[] buffer, int32 offset, int32 lengthFile, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.Open(System.String,System.String,System.Int64,System.Byte[],System.Int32,System.Int32,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Open (path As String, sessionId As String, offsetFile As Long, buffer As Byte(), offset As Integer, lengthFile As Integer, client As AdlsClient, req As RequestOptions, resp As OperationResponse) As Integer" />
      <MemberSignature Language="F#" Value="static member Open : string * string * int64 * byte[] * int * int * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse -&gt; int" Usage="Microsoft.Azure.DataLake.Store.Core.Open (path, sessionId, offsetFile, buffer, offset, lengthFile, client, req, resp)" />
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
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="offsetFile" Type="System.Int64" />
        <Parameter Name="buffer" Type="System.Byte[]" />
        <Parameter Name="offset" Type="System.Int32" />
        <Parameter Name="lengthFile" Type="System.Int32" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="a1ab2-282">ファイルのパス</span><span class="sxs-lookup"><span data-stu-id="a1ab2-282">Path of the file</span></span></param>
        <param name="sessionId"><span data-ttu-id="a1ab2-283">サーバーに簡単にファイル ハンドラー (ストリーム) を取得するために使用する UUID</span><span class="sxs-lookup"><span data-stu-id="a1ab2-283">UUID that is used to obtain the file handler (stream) easily at server</span></span></param>
        <param name="offsetFile"><span data-ttu-id="a1ab2-284">データを読み取った位置を示すファイル内のオフセットします。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-284">Offset in the file at which data will be read from</span></span></param>
        <param name="buffer"> <span data-ttu-id="a1ab2-285">データの読み取りを格納するバッファー</span><span class="sxs-lookup"><span data-stu-id="a1ab2-285">Buffer where data read will be stored</span></span></param>
        <param name="offset"><span data-ttu-id="a1ab2-286">データが読み取られるバッファー内のオフセットします。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-286">Offset in buffer where data will be read</span></span></param>
        <param name="lengthFile"><span data-ttu-id="a1ab2-287">読み取られるデータの長さ</span><span class="sxs-lookup"><span data-stu-id="a1ab2-287">Length of the data to be read</span></span></param>
        <param name="client"><span data-ttu-id="a1ab2-288">ADLS クライアント</span><span class="sxs-lookup"><span data-stu-id="a1ab2-288">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="a1ab2-289">Http 要求の動作を変更するオプション</span><span class="sxs-lookup"><span data-stu-id="a1ab2-289">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="a1ab2-290">Http 要求の応答/出力の格納します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-290">Stores the response/ouput of the Http request</span></span> </param>
        <summary>
            <span data-ttu-id="a1ab2-291">サーバーからファイルを読み取ります。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-291">Reads a file from server.</span></span> <span data-ttu-id="a1ab2-292">これは、同期操作です。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-292">This is synchronous operation.</span></span>
            </summary>
        <returns><span data-ttu-id="a1ab2-293">読み取られたバイト数</span><span class="sxs-lookup"><span data-stu-id="a1ab2-293">Number of bytes read</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;int&gt; OpenAsync (string path, string sessionId, long offsetFile, byte[] buffer, int offset, int lengthFile, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;int32&gt; OpenAsync(string path, string sessionId, int64 offsetFile, unsigned int8[] buffer, int32 offset, int32 lengthFile, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.OpenAsync(System.String,System.String,System.Int64,System.Byte[],System.Int32,System.Int32,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function OpenAsync (path As String, sessionId As String, offsetFile As Long, buffer As Byte(), offset As Integer, lengthFile As Integer, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task(Of Integer)" />
      <MemberSignature Language="F#" Value="static member OpenAsync : string * string * int64 * byte[] * int * int * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int&gt;" Usage="Microsoft.Azure.DataLake.Store.Core.OpenAsync (path, sessionId, offsetFile, buffer, offset, lengthFile, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;OpenAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="offsetFile" Type="System.Int64" />
        <Parameter Name="buffer" Type="System.Byte[]" />
        <Parameter Name="offset" Type="System.Int32" />
        <Parameter Name="lengthFile" Type="System.Int32" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="a1ab2-294">ファイルのパス</span><span class="sxs-lookup"><span data-stu-id="a1ab2-294">Path of the file</span></span></param>
        <param name="sessionId"><span data-ttu-id="a1ab2-295">サーバーに簡単にファイル ハンドラー (ストリーム) を取得するために使用する UUID</span><span class="sxs-lookup"><span data-stu-id="a1ab2-295">UUID that is used to obtain the file handler (stream) easily at server</span></span></param>
        <param name="offsetFile"><span data-ttu-id="a1ab2-296">データを読み取った位置を示すファイル内のオフセットします。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-296">Offset in the file at which data will be read from</span></span></param>
        <param name="buffer"> <span data-ttu-id="a1ab2-297">データの読み取りを格納するバッファー</span><span class="sxs-lookup"><span data-stu-id="a1ab2-297">Buffer where data read will be stored</span></span></param>
        <param name="offset"><span data-ttu-id="a1ab2-298">データが読み取られるバッファー内のオフセットします。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-298">Offset in buffer where data will be read</span></span></param>
        <param name="lengthFile"><span data-ttu-id="a1ab2-299">読み取られるデータの長さ</span><span class="sxs-lookup"><span data-stu-id="a1ab2-299">Length of the data to be read</span></span></param>
        <param name="client"><span data-ttu-id="a1ab2-300">ADLS クライアント</span><span class="sxs-lookup"><span data-stu-id="a1ab2-300">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="a1ab2-301">Http 要求の動作を変更するオプション</span><span class="sxs-lookup"><span data-stu-id="a1ab2-301">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="a1ab2-302">Http 要求の応答/出力の格納します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-302">Stores the response/ouput of the Http request</span></span> </param>
        <param name="cancelToken"><span data-ttu-id="a1ab2-303">CancellationToken 要求を取り消します</span><span class="sxs-lookup"><span data-stu-id="a1ab2-303">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="a1ab2-304">サーバーからファイルを読み取ります。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-304">Reads a file from server.</span></span> <span data-ttu-id="a1ab2-305">これは非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-305">This is an asynchronous operation.</span></span>
            </summary>
        <returns><span data-ttu-id="a1ab2-306">読み取られたバイト数</span><span class="sxs-lookup"><span data-stu-id="a1ab2-306">Number of bytes read</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAclAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RemoveAclAsync (string path, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RemoveAclAsync(string path, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.RemoveAclAsync(System.String,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function RemoveAclAsync (path As String, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="static member RemoveAclAsync : string * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.DataLake.Store.Core.RemoveAclAsync (path, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;RemoveAclAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="a1ab2-307">ファイルまたはディレクトリのパス</span><span class="sxs-lookup"><span data-stu-id="a1ab2-307">Path of the file or directory</span></span></param>
        <param name="client"><span data-ttu-id="a1ab2-308">ADLS クライアント</span><span class="sxs-lookup"><span data-stu-id="a1ab2-308">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="a1ab2-309">Http 要求の動作を変更するオプション</span><span class="sxs-lookup"><span data-stu-id="a1ab2-309">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="a1ab2-310">Http 要求の応答/出力の格納します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-310">Stores the response/ouput of the Http request</span></span> </param>
        <param name="cancelToken"><span data-ttu-id="a1ab2-311">CancellationToken 要求を取り消します</span><span class="sxs-lookup"><span data-stu-id="a1ab2-311">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="a1ab2-312">ファイルまたはディレクトリのすべての Acl エントリを削除します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-312">Removes all Acl Entries for a file or directory.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAclEntriesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RemoveAclEntriesAsync (string path, System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; aclSpecList, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RemoveAclEntriesAsync(string path, class System.Collections.Generic.List`1&lt;class Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; aclSpecList, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.RemoveAclEntriesAsync(System.String,System.Collections.Generic.List{Microsoft.Azure.DataLake.Store.Acl.AclEntry},Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function RemoveAclEntriesAsync (path As String, aclSpecList As List(Of AclEntry), client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="static member RemoveAclEntriesAsync : string * System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.DataLake.Store.Core.RemoveAclEntriesAsync (path, aclSpecList, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;RemoveAclEntriesAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclSpecList" Type="System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt;" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="a1ab2-313">ファイルまたはディレクトリのパス</span><span class="sxs-lookup"><span data-stu-id="a1ab2-313">Path of the file or directory</span></span></param>
        <param name="aclSpecList"><span data-ttu-id="a1ab2-314">削除する Acl エントリの一覧</span><span class="sxs-lookup"><span data-stu-id="a1ab2-314">List of Acl Entries to remove</span></span></param>
        <param name="client"><span data-ttu-id="a1ab2-315">ADLS クライアント</span><span class="sxs-lookup"><span data-stu-id="a1ab2-315">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="a1ab2-316">Http 要求の動作を変更するオプション</span><span class="sxs-lookup"><span data-stu-id="a1ab2-316">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="a1ab2-317">Http 要求の応答/出力の格納します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-317">Stores the response/ouput of the Http request</span></span> </param>
        <param name="cancelToken"><span data-ttu-id="a1ab2-318">CancellationToken 要求を取り消します</span><span class="sxs-lookup"><span data-stu-id="a1ab2-318">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="a1ab2-319">削除は、ファイルまたはディレクトリの Acl エントリを指定します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-319">Removes specified Acl Entries for a file or directory.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAclEntriesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RemoveAclEntriesAsync (string path, string aclSpec, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RemoveAclEntriesAsync(string path, string aclSpec, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.RemoveAclEntriesAsync(System.String,System.String,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function RemoveAclEntriesAsync (path As String, aclSpec As String, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="static member RemoveAclEntriesAsync : string * string * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.DataLake.Store.Core.RemoveAclEntriesAsync (path, aclSpec, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;RemoveAclEntriesAsync&gt;d__28))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclSpec" Type="System.String" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="a1ab2-320">ファイルまたはディレクトリのパス</span><span class="sxs-lookup"><span data-stu-id="a1ab2-320">Path of the file or directory</span></span></param>
        <param name="aclSpec"><span data-ttu-id="a1ab2-321">削除する Acl エントリを含む文字列</span><span class="sxs-lookup"><span data-stu-id="a1ab2-321">string containing Acl Entries to remove</span></span></param>
        <param name="client"><span data-ttu-id="a1ab2-322">ADLS クライアント</span><span class="sxs-lookup"><span data-stu-id="a1ab2-322">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="a1ab2-323">Http 要求の動作を変更するオプション</span><span class="sxs-lookup"><span data-stu-id="a1ab2-323">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="a1ab2-324">Http 要求の応答/出力の格納します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-324">Stores the response/ouput of the Http request</span></span> </param>
        <param name="cancelToken"><span data-ttu-id="a1ab2-325">CancellationToken 要求を取り消します</span><span class="sxs-lookup"><span data-stu-id="a1ab2-325">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="a1ab2-326">削除は、ファイルまたはディレクトリの Acl エントリを指定します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-326">Removes specified Acl Entries for a file or directory.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveDefaultAclAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RemoveDefaultAclAsync (string path, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RemoveDefaultAclAsync(string path, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.RemoveDefaultAclAsync(System.String,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function RemoveDefaultAclAsync (path As String, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="static member RemoveDefaultAclAsync : string * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.DataLake.Store.Core.RemoveDefaultAclAsync (path, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;RemoveDefaultAclAsync&gt;d__30))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="a1ab2-327">ファイルまたはディレクトリのパス</span><span class="sxs-lookup"><span data-stu-id="a1ab2-327">Path of the file or directory</span></span></param>
        <param name="client"><span data-ttu-id="a1ab2-328">ADLS クライアント</span><span class="sxs-lookup"><span data-stu-id="a1ab2-328">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="a1ab2-329">Http 要求の動作を変更するオプション</span><span class="sxs-lookup"><span data-stu-id="a1ab2-329">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="a1ab2-330">Http 要求の応答/出力の格納します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-330">Stores the response/ouput of the Http request</span></span> </param>
        <param name="cancelToken"><span data-ttu-id="a1ab2-331">CancellationToken 要求を取り消します</span><span class="sxs-lookup"><span data-stu-id="a1ab2-331">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="a1ab2-332">ファイルまたはディレクトリのすべての Acl エントリの AclScope デフォルトを削除します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-332">Removes all Acl Entries of AclScope default for a file or directory.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RenameAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;bool&gt; RenameAsync (string path, string destination, bool overwrite, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;bool&gt; RenameAsync(string path, string destination, bool overwrite, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.RenameAsync(System.String,System.String,System.Boolean,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function RenameAsync (path As String, destination As String, overwrite As Boolean, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="static member RenameAsync : string * string * bool * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="Microsoft.Azure.DataLake.Store.Core.RenameAsync (path, destination, overwrite, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;RenameAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="destination" Type="System.String" />
        <Parameter Name="overwrite" Type="System.Boolean" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="a1ab2-333">ソース ファイルまたはディレクトリのパス</span><span class="sxs-lookup"><span data-stu-id="a1ab2-333">Path of the source file or directory</span></span></param>
        <param name="destination"><span data-ttu-id="a1ab2-334">移行先パス</span><span class="sxs-lookup"><span data-stu-id="a1ab2-334">Destination path</span></span></param>
        <param name="overwrite"><span data-ttu-id="a1ab2-335">ファイル: true は、ディレクトリに存在する場合、変換先にファイルを上書きする場合: 先ディレクトリが存在するかどうかは、このフラグの使用はありません。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-335">For file: If true then overwrites the destination file if it exists For directory: If the destination directory exists, then this flag has no use.</span></span> <span data-ttu-id="a1ab2-336">移行先の下にあるソースの 1 つのレベルを格納します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-336">Because it puts the source one level under destination.</span></span>
                                    <span data-ttu-id="a1ab2-337">転送先のパスの下にある 1 つのレベルをソースと同じ名前を持つサブディレクトリの場合、このフラグの使用がありません。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-337">If there is a subdirectory with same name as source one level under the destination path, this flag has no use.</span></span> <span data-ttu-id="a1ab2-338">名前の変更が失敗します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-338">Rename fails</span></span>  </param>
        <param name="client"><span data-ttu-id="a1ab2-339">ADLS クライアント</span><span class="sxs-lookup"><span data-stu-id="a1ab2-339">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="a1ab2-340">Http 要求の動作を変更するオプション</span><span class="sxs-lookup"><span data-stu-id="a1ab2-340">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="a1ab2-341">Http 要求の応答/出力の格納します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-341">Stores the response/ouput of the Http request</span></span> </param>
        <param name="cancelToken"><span data-ttu-id="a1ab2-342">CancellationToken 要求を取り消します</span><span class="sxs-lookup"><span data-stu-id="a1ab2-342">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="a1ab2-343">パスの名前を変更します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-343">Renames a path.</span></span>
            <span data-ttu-id="a1ab2-344">ディレクトリの名前を変更する: 宛先の下にあるソース ディレクトリの 1 つのレベルを配置し、変換先が存在する場合。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-344">For renaming directory: If the destination exists then it puts the source directory one level under the destination.</span></span>
            </summary>
        <returns><span data-ttu-id="a1ab2-345">名前の変更が成功した else false の場合は true。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-345">True if rename is successful else false</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetAclAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task SetAclAsync (string path, System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; aclSpecList, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task SetAclAsync(string path, class System.Collections.Generic.List`1&lt;class Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; aclSpecList, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.SetAclAsync(System.String,System.Collections.Generic.List{Microsoft.Azure.DataLake.Store.Acl.AclEntry},Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function SetAclAsync (path As String, aclSpecList As List(Of AclEntry), client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="static member SetAclAsync : string * System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.DataLake.Store.Core.SetAclAsync (path, aclSpecList, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;SetAclAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclSpecList" Type="System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt;" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="a1ab2-346">ファイルまたはディレクトリのパス</span><span class="sxs-lookup"><span data-stu-id="a1ab2-346">Path of the file or directory</span></span></param>
        <param name="aclSpecList"><span data-ttu-id="a1ab2-347">設定する Acl エントリの一覧</span><span class="sxs-lookup"><span data-stu-id="a1ab2-347">List of Acl Entries to set</span></span> </param>
        <param name="client"><span data-ttu-id="a1ab2-348">ADLS クライアント</span><span class="sxs-lookup"><span data-stu-id="a1ab2-348">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="a1ab2-349">Http 要求の動作を変更するオプション</span><span class="sxs-lookup"><span data-stu-id="a1ab2-349">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="a1ab2-350">Http 要求の応答/出力の格納します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-350">Stores the response/ouput of the Http request</span></span> </param>
        <param name="cancelToken"><span data-ttu-id="a1ab2-351">CancellationToken 要求を取り消します</span><span class="sxs-lookup"><span data-stu-id="a1ab2-351">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="a1ab2-352">ファイルまたはディレクトリの Acl エントリを設定します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-352">Sets Acl Entries for a file or directory.</span></span> <span data-ttu-id="a1ab2-353">パスの既存の Acl エントリのデータをワイプします。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-353">It wipes out the existing Acl entries for the path.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetAclAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task SetAclAsync (string path, string aclSpec, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task SetAclAsync(string path, string aclSpec, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.SetAclAsync(System.String,System.String,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function SetAclAsync (path As String, aclSpec As String, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="static member SetAclAsync : string * string * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.DataLake.Store.Core.SetAclAsync (path, aclSpec, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;SetAclAsync&gt;d__26))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclSpec" Type="System.String" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="a1ab2-354">ファイルまたはディレクトリのパス</span><span class="sxs-lookup"><span data-stu-id="a1ab2-354">Path of the file or directory</span></span></param>
        <param name="aclSpec"><span data-ttu-id="a1ab2-355">コンマで区切られます ACL エントリを含む AclSpec 文字列</span><span class="sxs-lookup"><span data-stu-id="a1ab2-355">AclSpec string that contains the ACL entries delimited by comma</span></span> </param>
        <param name="client"><span data-ttu-id="a1ab2-356">ADLS クライアント</span><span class="sxs-lookup"><span data-stu-id="a1ab2-356">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="a1ab2-357">Http 要求の動作を変更するオプション</span><span class="sxs-lookup"><span data-stu-id="a1ab2-357">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="a1ab2-358">Http 要求の応答/出力の格納します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-358">Stores the response/ouput of the Http request</span></span> </param>
        <param name="cancelToken"><span data-ttu-id="a1ab2-359">CancellationToken 要求を取り消します</span><span class="sxs-lookup"><span data-stu-id="a1ab2-359">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="a1ab2-360">ファイルまたはディレクトリの Acl エントリを設定します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-360">Sets Acl Entries for a file or directory.</span></span> <span data-ttu-id="a1ab2-361">パスの既存の Acl エントリのデータをワイプします。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-361">It wipes out the existing Acl entries for the path.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetExpiryTimeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task SetExpiryTimeAsync (string path, Microsoft.Azure.DataLake.Store.ExpiryOption opt, long expiryTime, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task SetExpiryTimeAsync(string path, valuetype Microsoft.Azure.DataLake.Store.ExpiryOption opt, int64 expiryTime, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.SetExpiryTimeAsync(System.String,Microsoft.Azure.DataLake.Store.ExpiryOption,System.Int64,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function SetExpiryTimeAsync (path As String, opt As ExpiryOption, expiryTime As Long, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="static member SetExpiryTimeAsync : string * Microsoft.Azure.DataLake.Store.ExpiryOption * int64 * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.DataLake.Store.Core.SetExpiryTimeAsync (path, opt, expiryTime, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;SetExpiryTimeAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="opt" Type="Microsoft.Azure.DataLake.Store.ExpiryOption" />
        <Parameter Name="expiryTime" Type="System.Int64" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="a1ab2-362">ファイルのパス</span><span class="sxs-lookup"><span data-stu-id="a1ab2-362">Path of the file</span></span></param>
        <param name="opt"><span data-ttu-id="a1ab2-363">例については有効期限のメソッドの別の型: 有効期限はありません、now、expiryTime を評価する方法を定義するなどの基準としました。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-363">Different type of expiry method for example: never expire, relative to now, etc that defines how to evaluate expiryTime</span></span></param>
        <param name="expiryTime"><span data-ttu-id="a1ab2-364">有効期限の時刻値。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-364">Expiry time value.</span></span> <span data-ttu-id="a1ab2-365">Interepreation がどの ExpiryOption を置いた異なります</span><span class="sxs-lookup"><span data-stu-id="a1ab2-365">It's interepreation depends on what ExpiryOption user passes</span></span></param>
        <param name="client"><span data-ttu-id="a1ab2-366">ADLS クライアント</span><span class="sxs-lookup"><span data-stu-id="a1ab2-366">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="a1ab2-367">Http 要求の動作を変更するオプション</span><span class="sxs-lookup"><span data-stu-id="a1ab2-367">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="a1ab2-368">Http 要求の応答/出力の格納します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-368">Stores the response/ouput of the Http request</span></span> </param>
        <param name="cancelToken"><span data-ttu-id="a1ab2-369">CancellationToken 要求を取り消します</span><span class="sxs-lookup"><span data-stu-id="a1ab2-369">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="a1ab2-370">有効期限を設定します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-370">Set the expiry time</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetOwnerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task SetOwnerAsync (string path, string user, string group, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task SetOwnerAsync(string path, string user, string group, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.SetOwnerAsync(System.String,System.String,System.String,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function SetOwnerAsync (path As String, user As String, group As String, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="static member SetOwnerAsync : string * string * string * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.DataLake.Store.Core.SetOwnerAsync (path, user, group, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;SetOwnerAsync&gt;d__22))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="user" Type="System.String" />
        <Parameter Name="group" Type="System.String" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="a1ab2-371">ファイルまたはディレクトリのパス</span><span class="sxs-lookup"><span data-stu-id="a1ab2-371">Path of file or directory</span></span></param>
        <param name="user"><span data-ttu-id="a1ab2-372">パスの所有者の Id</span><span class="sxs-lookup"><span data-stu-id="a1ab2-372">Owner Id of the path</span></span></param>
        <param name="group"><span data-ttu-id="a1ab2-373">パスのグループ Id</span><span class="sxs-lookup"><span data-stu-id="a1ab2-373">Group Id of the path</span></span></param>
        <param name="client"><span data-ttu-id="a1ab2-374">ADLS クライアント</span><span class="sxs-lookup"><span data-stu-id="a1ab2-374">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="a1ab2-375">Http 要求の動作を変更するオプション</span><span class="sxs-lookup"><span data-stu-id="a1ab2-375">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="a1ab2-376">Http 要求の応答/出力の格納します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-376">Stores the response/ouput of the Http request</span></span> </param>
        <param name="cancelToken"><span data-ttu-id="a1ab2-377">CancellationToken 要求を取り消します</span><span class="sxs-lookup"><span data-stu-id="a1ab2-377">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="a1ab2-378">所有者を設定または/およびパスのグループ</span><span class="sxs-lookup"><span data-stu-id="a1ab2-378">Sets the owner or/and group of the path</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPermissionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task SetPermissionAsync (string path, string permission, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task SetPermissionAsync(string path, string permission, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.SetPermissionAsync(System.String,System.String,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function SetPermissionAsync (path As String, permission As String, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="static member SetPermissionAsync : string * string * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.DataLake.Store.Core.SetPermissionAsync (path, permission, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;SetPermissionAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="permission" Type="System.String" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="a1ab2-379">ファイルまたはディレクトリのパス</span><span class="sxs-lookup"><span data-stu-id="a1ab2-379">Path of the file or directory</span></span></param>
        <param name="permission"><span data-ttu-id="a1ab2-380">Unix 8 進数形式のチェックインを許可します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-380">Permission to check in unix octal form.</span></span> <span data-ttu-id="a1ab2-381">たとえば、ユーザーが所有者が読み取る場合に表示する場合、書き込みアクセス許可を実行するすべてのグループが書き込みアクセス許可を読み取り、文字列のアクセス許可を 741 となる他のユーザーに読み取り</span><span class="sxs-lookup"><span data-stu-id="a1ab2-381">For example if the user wants to see if owner has read, write execute permission, all groups has read write permission and others has read permission the string would be 741</span></span> </param>
        <param name="client"><span data-ttu-id="a1ab2-382">ADLS クライアント</span><span class="sxs-lookup"><span data-stu-id="a1ab2-382">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="a1ab2-383">Http 要求の動作を変更するオプション</span><span class="sxs-lookup"><span data-stu-id="a1ab2-383">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="a1ab2-384">Http 要求の応答/出力の格納します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-384">Stores the response/ouput of the Http request</span></span> </param>
        <param name="cancelToken"><span data-ttu-id="a1ab2-385">CancellationToken 要求を取り消します</span><span class="sxs-lookup"><span data-stu-id="a1ab2-385">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="a1ab2-386">指定したパスのアクセス許可を設定します。</span><span class="sxs-lookup"><span data-stu-id="a1ab2-386">Sets the permission of the specified path</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>