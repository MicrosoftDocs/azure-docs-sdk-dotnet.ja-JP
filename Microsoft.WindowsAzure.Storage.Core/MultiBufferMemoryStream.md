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
            バッキング ストアとしてメモリ マルチバッファー ストリームを作成します。
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
        <param name="bufferManager"><see cref="T:Microsoft.WindowsAzure.Storage.IBufferManager" />取得およびストリームのバッファーを返すために使用します。 あります<c>null</c>です。</param>
        <param name="bufferSize">各ブロックを使用するバッファー サイズ。 既定のサイズは、64 KB です。 このパラメーターは無視する場合に、<see cref="T:Microsoft.WindowsAzure.Storage.IBufferManager" />が指定されています。</param>
        <summary>
             新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream" />指定されたバッファー マネージャーを持つクラス。
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
        <param name="destination">現在のストリームの内容のコピー先のストリーム。</param>
        <param name="expiryTime">有効期限の日時を示す DateTime です。</param>
        <param name="callback">コピーが完了するときに呼び出されるオプションの非同期コールバック。</param>
        <param name="state">この特定の非同期コピー要求を他の要求と区別するユーザー指定のオブジェクト。</param>
        <summary>
            非同期の高速コピー操作を開始します。
            </summary>
        <returns>非同期のコピーは、保留になっていることを表す IAsyncResult。</returns>
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
        <param name="buffer">このメソッドが返されるとき、バッファーは現在のソースから読み取ったバイトにより置き換えられた、オフセットから (オフセット + データの個数 - 1) の間の値を持つ指定されたバイト配列を含みます。</param>
        <param name="offset">現在のストリームから読み取ったデータの格納を開始する位置を示す バッファ内の0 から始まるバイト オフセット。</param>
        <param name="count">読み取るバイトの最大数。</param>
        <param name="callback">読み取り完了時に呼び出されるオプションの非同期コールバック。</param>
        <param name="state">この特定の非同期読み取り要求を他の要求と区別するために使用するユーザー指定のオブジェクト。</param>
        <summary>
            非同期の読み込み動作を開始します。
            </summary>
        <returns>非同期の読み取りは、保留になっていることを表す IAsyncResult。</returns>
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
        <param name="buffer">データの書き込み元となるバッファー。</param>
        <param name="offset">現在のストリームにバイトのコピーを開始する位置を示すバッファー内の 0 から始まるバイト オフセット。</param>
        <param name="count">書き込むバイト数。</param>
        <param name="callback">書き込みの完了時に呼び出されるオプションの非同期コールバック。</param>
        <param name="state">この特定の非同期書き込み要求を他の要求と区別するために使用するユーザー指定のオブジェクト。</param>
        <summary>
            非同期の書き込み操作を開始します。
            </summary>
        <returns>保留になっている可能性があります、非同期の書き込みを表す IAsyncResult。</returns>
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
            現在のストリームが読み取りをサポートしているかどうかを示す値を取得します。
            </summary>
        <value>
          <c>true</c>ストリームが読み取りをサポートする場合はそれ以外の場合、 <c>false</c>です。</value>
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
            現在のストリームがシークをサポートしているかどうかを示す値を取得します。
            </summary>
        <value>
          <c>true</c>ストリームがシークをサポートする場合はそれ以外の場合、 <c>false</c>です。</value>
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
            現在のストリームが書き込みをサポートしているかどうかを示す値を取得します。
            </summary>
        <value>
          <c>true</c>ストリームが書き込みをサポートする場合はそれ以外の場合、 <c>false</c>です。</value>
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
            このストリームのハッシュ値を計算します。
            </summary>
        <returns>計算されたハッシュ値の文字列表現。</returns>
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
        <param name="disposing">マネージ リソースとアンマネージ リソースの両方を解放する場合は true、アンマネージ リソースだけを解放する場合は false。</param>
        <summary>
            
                      <see cref="T:Microsoft.WindowsAzure.Storage.Core.MultiBufferMemoryStream" /> によって使用されているすべてのリソースを解放します。
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
        <param name="asyncResult">終了させる保留状態の非同期リクエストへの参照。</param>
        <summary>
            非同期のコピー操作を終了します。
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
        <param name="asyncResult">終了させる保留状態の非同期リクエストへの参照。</param>
        <summary>
            保留中の非同期読み取りが完了するまで待機します。
            </summary>
        <returns>バッファーに読み取られた合計バイト数。 要求されたバイト数をその時点で読み取れなかった場合、この値は要求されたバイト数より小さくなることがあります。ストリームの末尾に達していた場合は 0 になります。</returns>
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
        <param name="asyncResult">終了させる保留状態の非同期リクエストへの参照。</param>
        <summary>
            非同期書き込み操作を終了します。
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
        <param name="destination">現在のストリームの内容のコピー先のストリーム。</param>
        <param name="expiryTime">有効期限の日時を示す DateTime です。</param>
        <summary>
            現在のストリームからバイトを読み取り、別のストリームに書き込みます。 このメソッドは、一時バッファーにデータをコピーするのではなく、コピー先のストリームに直接書き込みます。
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
            ストリームがメモリ内ストリームとして、任意の操作は実行されません。
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
            ストリーム長 (バイト単位) を取得します。
            </summary>
        <value>ストリーム長 (バイト単位) を表す long 値。</value>
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
            現在のストリーム内の位置を取得または設定します。
            </summary>
        <value>ストリーム内の現在位置。</value>
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
        <param name="buffer">このメソッドが返されるとき、バッファーは現在のソースから読み取ったバイトにより置き換えられた、オフセットから (オフセット + データの個数 - 1) の間の値を持つ指定されたバイト配列を含みます。</param>
        <param name="offset">現在のストリームから読み取ったデータの格納を開始する位置を示す バッファ内の0 から始まるバイト オフセット。</param>
        <param name="count">読み取るバイトの最大数。</param>
        <summary>
            現在のストリームからバイトのブロックを読み取り、データをバッファーに書き込みます。
            </summary>
        <returns>バッファーに読み取られた合計バイト数。 要求されたバイト数をその時点で読み取れなかった場合、この値は要求されたバイト数より小さくなることがあります。ストリームの末尾に達していた場合は 0 になります。</returns>
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
        <param name="offset">Origin パラメーターからのバイト オフセット。</param>
        <param name="origin">新しい位置を取得するために使用する参照ポイントを示す System.IO.SeekOrigin 型の値です。</param>
        <summary>
            現在のストリーム内の位置を設定します。
            </summary>
        <returns>現在のストリーム内の新しい位置。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">場合にスロー <paramref name="offset" /> SeekOrigin に対して無効です。</exception>
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
        <param name="value">現在のストリームの希望の長さ (バイト数)。</param>
        <summary>
            現在のストリームの長さを設定します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">場合、<paramref name="value" />が負の値。</exception>
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
        <param name="buffer">データの書き込み元となるバッファー。</param>
        <param name="offset">現在のストリームにバイトのコピーを開始する位置を示すバッファー内の 0 から始まるバイト オフセット。</param>
        <param name="count">書き込むバイト数。 </param>
        <summary>
            バッファーから読み取ったデータを使用して、現在のストリームにバイトのブロックを書き込みます。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>