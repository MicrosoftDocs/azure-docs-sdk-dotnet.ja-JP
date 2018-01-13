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
            このクラスは、パフォーマンスを向上させるためにメモリ ストリームの上書きを APM 読み取り/書き込みを提供します。
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
            0 に初期化される拡張可能な容量 SyncMemoryStream クラスの新しいインスタンスを初期化します。
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
        <param name="buffer">現在のストリームを作成する符号なしバイトの配列。</param>
        <summary>
            指定したバイト配列に基づく SyncMemoryStream クラスの新しいサイズを変更できないインスタンスを初期化します。 
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
        <param name="buffer">現在のストリームを作成する符号なしバイトの配列。</param>
        <param name="index">開始位置となるストリーム バッファーへのインデックス。</param>
        <summary>
            バイト配列の指定した領域 (インデックス) に基づいて SyncMemoryStream クラスの新しいサイズを変更できないインスタンスを初期化します。 
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
        <param name="buffer">現在のストリームを作成する符号なしバイトの配列。</param>
        <param name="index">開始位置となるストリーム バッファーへのインデックス。</param>
        <param name="count">バイト単位のストリーム長。</param>
        <summary>
            バイト配列の指定した領域 (インデックス) に基づいて SyncMemoryStream クラスの新しいサイズを変更できないインスタンスを初期化します。 
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
        <param name="asyncResult">終了させる保留状態の非同期リクエストへの参照。</param>
        <summary>
            非同期書き込み操作を終了します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>