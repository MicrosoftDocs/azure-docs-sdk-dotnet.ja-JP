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
            DataLakeTransferClient が動作するために、フロント エンドから必要な操作を定義します。
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
        <param name="streamPath">ストリームへの相対パスです。</param>
        <param name="data">ストリームに追加されるバイトの配列。</param>
        <param name="offset">ストリームに追加するオフセットです。</param>
        <param name="length">(0 から始まる) を追加するバイト数。</param>
        <summary>
            指定されたストリームの末尾に指定したバイト配列を追加します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">追加するデータが null または空の場合は。</exception>
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
        <param name="targetStreamPath">対象のストリームへの相対パスです。</param>
        <param name="inputStreamPaths">入力ストリームへのパスの順序付けされた配列。</param>
        <param name="isDownload">場合に設定<c>true</c> [は download] で、サーバー上の代わりに、ローカル コンピューター上のストリームが連結されますおを意味します。</param>
        <summary>
            指定された対象のストリームに (順序で) 指定された入力ストリームを連結します。
            この操作の最後に、入力ストリームは削除されます。
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
        <param name="streamPath">ストリームへの相対パスです。</param>
        <param name="overwrite">既存のストリームを上書きするかどうか。</param>
        <param name="data">データ。</param>
        <param name="byteCount">バイト数。</param>
        <summary>
            指定されたパスに新しい、空のストリームを作成します。
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
        <param name="streamPath">ストリームへの相対パスです。</param>
        <param name="recurse">場合設定<c>true</c> [recurse] です。 これはフォルダー ストリームにのみ使用されます。</param>
        <param name="isDownload">場合に設定<c>true</c> [ダウンロードは]、つまり、ローカル コンピューターの代わりに、サーバー上でストリームは削除されます。</param>
        <summary>
            指定されたパスに既存のストリームを削除します。
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
        <param name="streamPath">ストリームへの相対パスです。</param>
        <param name="isDownload">場合に設定<c>true</c> [ダウンロードは]、つまり、ローカル コンピューター上の代わりに、サーバーにストリームの長さを紹介します。</param>
        <summary>
            バイト単位のストリームの長さを示す値を取得します。
            </summary>
        <returns>バイト単位のストリームの長さ。</returns>
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
        <param name="streamPath">ストリームへの相対パスです。</param>
        <summary>
            かどうかを使用してストリーム、サーバー上のパスが指定されたディレクトリまたは終端ファイル。
            これは、ダウンロード専用に使用します。
            </summary>
        <returns>ストリームがディレクトリ、それ以外の場合に設定されている場合は true。</returns>
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
        <param name="directoryPath">ディレクトリのパス。</param>
        <param name="recursive">場合設定<c>true</c> [再帰] です。</param>
        <summary>
            指定された Data Lake Store ディレクトリを一覧表示します。
            </summary>
        <returns>
            文字列のパスとその対応するファイルのサイズ、(バイト単位) の一覧。
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
        <param name="streamPath">ストリームへの相対パスです。</param>
        <param name="offset">ストリームに追加するオフセットです。</param>
        <param name="length">(0 から始まる) を追加するバイト数。</param>
        <param name="isDownload">場合に設定<c>true</c> [ダウンロードは、] を読み取ったり、ローカル コンピューターではなくサーバーにストリームを開くことを意味します。</param>
        <summary>
            指定された指定のストリームのパスを読み取るのためのストリームを開きます
            </summary>
        <returns />
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">追加するデータが null または空の場合は。</exception>
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
        <param name="streamPath">ストリームへの相対パスです。</param>
        <param name="isDownload">場合に設定<c>true</c> [は download] で、ローカル コンピューターの代わりに、サーバー上に、ストリームが存在する場合をテストします。 つまりです。</param>
        <summary>
            かどうかをストリームが指定されたパスに存在します。
            </summary>
        <returns>ストリームが存在する場合、false それ以外の場合は true。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>