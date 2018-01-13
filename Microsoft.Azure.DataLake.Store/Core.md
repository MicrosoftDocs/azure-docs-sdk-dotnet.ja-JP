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
            コア レイヤーです。 REST Api のメソッドが含まれています。 各 rest api コマンドをサーバーに、HTTP 要求を送信します。
            作成、APPEND、開く、CONCURRENTAPPEND の async および sync の両方のバージョンであること。 ある理由は、アプリケーションが大きく、明示的なスレッドを使用して、非同期を使用してこれらの操作を行っているかどうか、内部的に await threadpool で不要なスレッドを作成コンテキストの切り替えによりパフォーマンスが低下するとします。 アプリケーションでは、アップローダーとダウンローダーの場合、明示的なスレッドを作成できます。
            これらすべての操作では、同期バージョン MakeCall の WebTransport レイヤーも呼び出します。
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
        <param name="path">ファイルのパス</param>
        <param name="leaseId">ファイルの編集を行うことができます、クライアントはその他のクライアント ファイル上のリースを取得する際に、リース ID を含む文字列 </param>
        <param name="sessionId">サーバーに簡単にファイル ハンドラー (ストリーム) を取得するために使用する UUID</param>
        <param name="flag">ファイルのメタデータなどの長さ、変更されたときにデータを渡す SyncFlag.METADATA のバイトを書き込むときに、SyncFlag.DATA を渡すインスタント ファイルの実際のデータと一致するように更新する必要があります。 SyncFlag.METADATA GetFileStatus と ListStatus を渡した後に一貫性のあるデータを返します。
                               以上のデータを追加する必要がある、ファイルのメタデータを更新、リースの解放およびストリームが閉じているときに、SyncFlag.CLOSE を渡す  </param>
        <param name="offsetFile">データの追加をファイル内のオフセットします。</param>
        <param name="dataBytes">ファイルに書き込むバイトの配列</param>
        <param name="offset">バイト配列内のオフセットします。</param>
        <param name="length">オフセット位置から書き込むバイト数</param>
        <param name="client">ADLS クライアント</param>
        <param name="req">Http 要求の動作を変更するオプション </param>
        <param name="resp">Http 要求の応答/出力の格納します。 </param>
        <summary>
            データをファイルに追加します。 これは、同期操作です。
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
        <param name="path">ファイルのパス</param>
        <param name="leaseId">ファイルの編集を行うことができます、クライアントはその他のクライアント ファイル上のリースを取得する際に、リース ID を含む文字列 </param>
        <param name="sessionId">サーバーに簡単にファイル ハンドラー (ストリーム) を取得するために使用する UUID</param>
        <param name="flag">ファイルのメタデータなどの長さ、変更されたときにデータを渡す SyncFlag.METADATA のバイトを書き込むときに、SyncFlag.DATA を渡すインスタント ファイルの実際のデータと一致するように更新する必要があります。 SyncFlag.METADATA GetFileStatus と ListStatus を渡した後に一貫性のあるデータを返します。
                               以上のデータを追加する必要がある、ファイルのメタデータを更新、リースの解放およびストリームが閉じているときに、SyncFlag.CLOSE を渡す  </param>
        <param name="offsetFile">データの追加をファイル内のオフセットします。</param>
        <param name="dataBytes">ファイルに書き込むバイトの配列</param>
        <param name="offset">バイト配列内のオフセットします。</param>
        <param name="length">オフセット位置から書き込むバイト数</param>
        <param name="client">ADLS クライアント</param>
        <param name="req">Http 要求の動作を変更するオプション </param>
        <param name="resp">Http 要求の応答/出力の格納します。 </param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            データをファイルに追加します。 これは非同期操作です。
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
        <param name="path">ファイルまたはディレクトリのパス</param>
        <param name="rwx">"Rwx"の文字列形式のチェックインを許可します。 例をユーザーがかどうかに読み取りを参照する場合は、アクセス許可を実行、文字列になります r x </param>
        <param name="client">ADLS クライアント</param>
        <param name="req">Http 要求の動作を変更するオプション </param>
        <param name="resp">Http 要求の応答/出力の格納します。 </param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            ユーザー/グループが、指定されたパスへのアクセスを指定したかを確認します。
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
        <param name="path">変換先のパス</param>
        <param name="sourceFiles">ソース ファイルのパスを含むリスト</param>
        <param name="client">ADLS クライアント</param>
        <param name="req">Http 要求の動作を変更するオプション </param>
        <param name="resp">Http 要求の応答/出力の格納します。 </param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            対象のファイルにソース ファイルを連結します。 既定ではソース ディレクトリを削除しません。
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
        <param name="path">変換先のパス</param>
        <param name="sourceFiles">ソース ファイルのパスを含むリスト</param>
        <param name="deleteSourceDirectory">True の場合、削除、ソース ディレクトリその下にあるすべてのファイルを連結する場合</param>
        <param name="client">ADLS クライアント</param>
        <param name="req">Http 要求の動作を変更するオプション </param>
        <param name="resp">Http 要求の応答/出力の格納します。 </param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            対象のファイルにソース ファイルを連結します。
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
        <param name="path">ファイルのパス</param>
        <param name="autoCreate"></param>
        <param name="dataBytes">ファイルに書き込むバイトの配列</param>
        <param name="offset">バイト配列内のオフセットします。</param>
        <param name="length">オフセット位置から書き込むバイト数</param>
        <param name="client">ADLS クライアント</param>
        <param name="req">Http 要求の動作を変更するオプション </param>
        <param name="resp">Http 要求の応答/出力の格納します。 </param>
        <summary>
            実行のサーバーで同時実行を同期的に追加します。 オフセットが発生する追加はサーバーによって決まります
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
        <param name="path">ファイルのパス</param>
        <param name="autoCreate"></param>
        <param name="dataBytes">ファイルに書き込むバイトの配列</param>
        <param name="offset">バイト配列内のオフセットします。</param>
        <param name="length">オフセット位置から書き込むバイト数</param>
        <param name="client">ADLS クライアント</param>
        <param name="req">Http 要求の動作を変更するオプション </param>
        <param name="resp">Http 要求の応答/出力の格納します。 </param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            実行サーバーで同時実行が非同期的に追加します。 オフセットが発生する追加はサーバーによって決まります
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
        <param name="path">ファイルのパス</param>
        <param name="overwrite">フラグが true の場合、既存のファイルが上書きされます。</param>
        <param name="octalPermission">8 進数のアクセス許可文字列</param>
        <param name="leaseId">ファイルの編集を行うことができます、クライアントはその他のクライアント ファイル上のリースを取得する際に、リース ID を含む文字列 </param>
        <param name="sessionId">サーバーに簡単にファイル ハンドラー (ストリーム) を取得するために使用する UUID</param>
        <param name="createParent">True の場合は、存在しない親ディレクトリを作成します。</param>
        <param name="flag">ファイルのメタデータなどの長さ、変更されたときにデータを渡す SyncFlag.METADATA のバイトを書き込むときに、SyncFlag.DATA を渡すインスタント ファイルの実際のデータと一致するように更新する必要があります。 SyncFlag.METADATA GetFileStatus と ListStatus を渡した後に一貫性のあるデータを返します。
                               以上のデータを追加する必要がある、ファイルのメタデータを更新、リースの解放およびストリームが閉じているときに、SyncFlag.CLOSE を渡す  </param>
        <param name="dataBytes">ファイルに書き込むバイトの配列</param>
        <param name="offset">バイト配列内のオフセットします。</param>
        <param name="length">オフセット位置から書き込むバイト数</param>
        <param name="client">ADLS クライアント</param>
        <param name="req">Http 要求の動作を変更するオプション </param>
        <param name="resp">Http 要求の応答/出力の格納します。 </param>
        <summary>
            新しいファイルを作成します。 これは、同期操作です。
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
        <param name="path">ファイルのパス</param>
        <param name="overwrite">フラグが true の場合、既存のファイルが上書きされます。</param>
        <param name="octalPermission">8 進数のアクセス許可文字列</param>
        <param name="leaseId">ファイルの編集を行うことができます、クライアントはその他のクライアント ファイル上のリースを取得する際に、リース ID を含む文字列 </param>
        <param name="sessionId">サーバーに簡単にファイル ハンドラー (ストリーム) を取得するために使用する UUID</param>
        <param name="createParent">True の場合は、存在しない親ディレクトリを作成します。</param>
        <param name="flag">ファイルのメタデータなどの長さ、変更されたときにデータを渡す SyncFlag.METADATA のバイトを書き込むときに、SyncFlag.DATA を渡すインスタント ファイルの実際のデータと一致するように更新する必要があります。 SyncFlag.METADATA GetFileStatus と ListStatus を渡した後に一貫性のあるデータを返します。
                               以上のデータを追加する必要がある、ファイルのメタデータを更新、リースの解放およびストリームが閉じているときに、SyncFlag.CLOSE を渡す  </param>
        <param name="dataBytes">ファイルに書き込むバイトの配列</param>
        <param name="offset">バイト配列内のオフセットします。</param>
        <param name="length">オフセット位置から書き込むバイト数</param>
        <param name="client">ADLS クライアント</param>
        <param name="req">Http 要求の動作を変更するオプション </param>
        <param name="resp">Http 要求の応答/出力の格納します。 </param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            新しいファイルを作成します。 これは非同期操作です。
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
        <param name="path">ファイルまたはディレクトリのパス</param>
        <param name="recursive"></param>
        <param name="client">ADLS クライアント</param>
        <param name="req">Http 要求の動作を変更するオプション </param>
        <param name="resp">Http 要求の応答/出力の格納します。 </param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            ファイルまたはディレクトリを削除します。
            </summary>
        <returns>削除が成功した場合は true。</returns>
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
        <param name="path">ファイルまたはディレクトリのパス</param>
        <param name="userIdFormat">ユーザー/グループ オブジェクトを表現する方法</param>
        <param name="client">ADLS クライアント</param>
        <param name="req">Http 要求の動作を変更するオプション </param>
        <param name="resp">Http 要求の応答/出力の格納します。 </param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            ACL エントリの一覧、所有者 ID、グループ ID、8 進数のアクセス許可およびファイルまたはディレクトリの (ディレクトリ) の場合のみ sticky ビットを取得します。
            </summary>
        <returns>Acl 情報: ACL エントリの一覧、所有者 ID、ID、8 進数のアクセス許可、および sticky ビットをグループ化</returns>
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
        <param name="path">ディレクトリまたはファイルのパス</param>
        <param name="client">ADLS クライアント</param>
        <param name="req">Http 要求の動作を変更するオプション </param>
        <param name="resp">Http 要求の応答/出力の格納します。 </param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            ファイルまたはディレクトリのコンテンツの概要を取得します。
            </summary>
        <returns>パスの ContentSummary</returns>
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
        <param name="path">ファイルまたはディレクトリのパス</param>
        <param name="userIdFormat">ユーザーまたはグループのオブジェクトの表現方法</param>
        <param name="client">ADLS クライアント</param>
        <param name="req">Http 要求の動作を変更するオプション </param>
        <param name="resp">Http 要求の応答/出力の格納します。 </param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            完全なパス、種類 (ファイルまたはディレクトリ)、グループ、ユーザー、アクセス許可、長さ、メタ データを取得最終アクセス時刻、最終更新時刻、有効期限、acl ビット、レプリケーション係数
            </summary>
        <returns>ファイルまたはディレクトリのメタデータを返します</returns>
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
        <param name="path">ディレクトリのパス</param>
        <param name="listAfter">ファイル名をサーバーからファイルの一覧を取得する必要があります。</param>
        <param name="listBefore">これまでは、サーバーからファイルの一覧を取得するファイル名</param>
        <param name="listSize">サーバーから取得するリストのサイズ</param>
        <param name="userIdFormat">ユーザーまたはグループのオブジェクトの表現方法</param>
        <param name="client">ADLS クライアント</param>
        <param name="req">Http 要求の動作を変更するオプション </param>
        <param name="resp">Http 要求の応答/出力の格納します。 </param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            サブディレクトリまたはディレクトリに含まれているファイルを一覧表示します。
            </summary>
        <returns>Directoryentries の一覧</returns>
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
        <param name="path">ディレクトリのパス</param>
        <param name="octalPermission">8 進数のアクセス許可</param>
        <param name="client">ADLS クライアント</param>
        <param name="req">Http 要求の動作を変更するオプション </param>
        <param name="resp">Http 要求の応答/出力の格納します。 </param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            ディレクトリを作成します。 
            </summary>
        <returns>それ以外の場合は false、ディレクトリを作成する場合は true。</returns>
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
        <param name="path">ファイルまたはディレクトリのパス</param>
        <param name="aclSpecList">変更する Acl エントリの一覧</param>
        <param name="client">ADLS クライアント</param>
        <param name="req">Http 要求の動作を変更するオプション </param>
        <param name="resp">Http 要求の応答/出力の格納します。 </param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            ファイルの acl エントリを変更またはディレクトリが指定した ACL リスト。 既存の ACL を結合で指定したリスト ボックスの一覧です。
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
        <param name="path">ファイルまたはディレクトリのパス</param>
        <param name="aclSpec">コンマで区切られます ACL エントリを含む AclSpec 文字列 </param>
        <param name="client">ADLS クライアント</param>
        <param name="req">Http 要求の動作を変更するオプション </param>
        <param name="resp">Http 要求の応答/出力の格納します。 </param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            ファイルの acl エントリを変更またはディレクトリが指定した ACL リスト。 既存の ACL を結合で指定したリスト ボックスの一覧です。
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
        <param name="path">ファイルのパス</param>
        <param name="sessionId">サーバーに簡単にファイル ハンドラー (ストリーム) を取得するために使用する UUID</param>
        <param name="offsetFile">データを読み取った位置を示すファイル内のオフセットします。</param>
        <param name="buffer"> データの読み取りを格納するバッファー</param>
        <param name="offset">データが読み取られるバッファー内のオフセットします。</param>
        <param name="lengthFile">読み取られるデータの長さ</param>
        <param name="client">ADLS クライアント</param>
        <param name="req">Http 要求の動作を変更するオプション </param>
        <param name="resp">Http 要求の応答/出力の格納します。 </param>
        <summary>
            サーバーからファイルを読み取ります。 これは、同期操作です。
            </summary>
        <returns>読み取られたバイト数</returns>
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
        <param name="path">ファイルのパス</param>
        <param name="sessionId">サーバーに簡単にファイル ハンドラー (ストリーム) を取得するために使用する UUID</param>
        <param name="offsetFile">データを読み取った位置を示すファイル内のオフセットします。</param>
        <param name="buffer"> データの読み取りを格納するバッファー</param>
        <param name="offset">データが読み取られるバッファー内のオフセットします。</param>
        <param name="lengthFile">読み取られるデータの長さ</param>
        <param name="client">ADLS クライアント</param>
        <param name="req">Http 要求の動作を変更するオプション </param>
        <param name="resp">Http 要求の応答/出力の格納します。 </param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            サーバーからファイルを読み取ります。 これは非同期操作です。
            </summary>
        <returns>読み取られたバイト数</returns>
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
        <param name="path">ファイルまたはディレクトリのパス</param>
        <param name="client">ADLS クライアント</param>
        <param name="req">Http 要求の動作を変更するオプション </param>
        <param name="resp">Http 要求の応答/出力の格納します。 </param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            ファイルまたはディレクトリのすべての Acl エントリを削除します。
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
        <param name="path">ファイルまたはディレクトリのパス</param>
        <param name="aclSpecList">削除する Acl エントリの一覧</param>
        <param name="client">ADLS クライアント</param>
        <param name="req">Http 要求の動作を変更するオプション </param>
        <param name="resp">Http 要求の応答/出力の格納します。 </param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            削除は、ファイルまたはディレクトリの Acl エントリを指定します。
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
        <param name="path">ファイルまたはディレクトリのパス</param>
        <param name="aclSpec">削除する Acl エントリを含む文字列</param>
        <param name="client">ADLS クライアント</param>
        <param name="req">Http 要求の動作を変更するオプション </param>
        <param name="resp">Http 要求の応答/出力の格納します。 </param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            削除は、ファイルまたはディレクトリの Acl エントリを指定します。
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
        <param name="path">ファイルまたはディレクトリのパス</param>
        <param name="client">ADLS クライアント</param>
        <param name="req">Http 要求の動作を変更するオプション </param>
        <param name="resp">Http 要求の応答/出力の格納します。 </param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            ファイルまたはディレクトリのすべての Acl エントリの AclScope デフォルトを削除します。
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
        <param name="path">ソース ファイルまたはディレクトリのパス</param>
        <param name="destination">移行先パス</param>
        <param name="overwrite">ファイル: true は、ディレクトリに存在する場合、変換先にファイルを上書きする場合: 先ディレクトリが存在するかどうかは、このフラグの使用はありません。 移行先の下にあるソースの 1 つのレベルを格納します。
                                    転送先のパスの下にある 1 つのレベルをソースと同じ名前を持つサブディレクトリの場合、このフラグの使用がありません。 名前の変更が失敗します。  </param>
        <param name="client">ADLS クライアント</param>
        <param name="req">Http 要求の動作を変更するオプション </param>
        <param name="resp">Http 要求の応答/出力の格納します。 </param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            パスの名前を変更します。
            ディレクトリの名前を変更する: 宛先の下にあるソース ディレクトリの 1 つのレベルを配置し、変換先が存在する場合。
            </summary>
        <returns>名前の変更が成功した else false の場合は true。</returns>
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
        <param name="path">ファイルまたはディレクトリのパス</param>
        <param name="aclSpecList">設定する Acl エントリの一覧 </param>
        <param name="client">ADLS クライアント</param>
        <param name="req">Http 要求の動作を変更するオプション </param>
        <param name="resp">Http 要求の応答/出力の格納します。 </param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            ファイルまたはディレクトリの Acl エントリを設定します。 パスの既存の Acl エントリのデータをワイプします。
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
        <param name="path">ファイルまたはディレクトリのパス</param>
        <param name="aclSpec">コンマで区切られます ACL エントリを含む AclSpec 文字列 </param>
        <param name="client">ADLS クライアント</param>
        <param name="req">Http 要求の動作を変更するオプション </param>
        <param name="resp">Http 要求の応答/出力の格納します。 </param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            ファイルまたはディレクトリの Acl エントリを設定します。 パスの既存の Acl エントリのデータをワイプします。
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
        <param name="path">ファイルのパス</param>
        <param name="opt">例については有効期限のメソッドの別の型: 有効期限はありません、now、expiryTime を評価する方法を定義するなどの基準としました。</param>
        <param name="expiryTime">有効期限の時刻値。 Interepreation がどの ExpiryOption を置いた異なります</param>
        <param name="client">ADLS クライアント</param>
        <param name="req">Http 要求の動作を変更するオプション </param>
        <param name="resp">Http 要求の応答/出力の格納します。 </param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            有効期限を設定します。
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
        <param name="path">ファイルまたはディレクトリのパス</param>
        <param name="user">パスの所有者の Id</param>
        <param name="group">パスのグループ Id</param>
        <param name="client">ADLS クライアント</param>
        <param name="req">Http 要求の動作を変更するオプション </param>
        <param name="resp">Http 要求の応答/出力の格納します。 </param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            所有者を設定または/およびパスのグループ
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
        <param name="path">ファイルまたはディレクトリのパス</param>
        <param name="permission">Unix 8 進数形式のチェックインを許可します。 たとえば、ユーザーが所有者が読み取る場合に表示する場合、書き込みアクセス許可を実行するすべてのグループが書き込みアクセス許可を読み取り、文字列のアクセス許可を 741 となる他のユーザーに読み取り </param>
        <param name="client">ADLS クライアント</param>
        <param name="req">Http 要求の動作を変更するオプション </param>
        <param name="resp">Http 要求の応答/出力の格納します。 </param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            指定したパスのアクセス許可を設定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>