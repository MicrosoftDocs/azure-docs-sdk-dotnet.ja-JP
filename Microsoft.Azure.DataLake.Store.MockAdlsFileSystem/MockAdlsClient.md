<Type Name="MockAdlsClient" FullName="Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient">
  <TypeSignature Language="C#" Value="public sealed class MockAdlsClient : Microsoft.Azure.DataLake.Store.AdlsClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit MockAdlsClient extends Microsoft.Azure.DataLake.Store.AdlsClient" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class MockAdlsClient&#xA;Inherits AdlsClient" />
  <TypeSignature Language="F#" Value="type MockAdlsClient = class&#xA;    inherit AdlsClient" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.DataLake.Store.AdlsClient</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            モック Adls クライアント。 すべての操作は、メモリ内で実行されます。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BulkDownload">
      <MemberSignature Language="C#" Value="public override Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus BulkDownload (string srcPath, string destPath, int numThreads = -1, Microsoft.Azure.DataLake.Store.IfExists shouldOverwrite = Microsoft.Azure.DataLake.Store.IfExists.Overwrite, IProgress&lt;Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus&gt; progressTracker = null, bool notRecurse = false, bool resume = false, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus BulkDownload(string srcPath, string destPath, int32 numThreads, valuetype Microsoft.Azure.DataLake.Store.IfExists shouldOverwrite, class System.IProgress`1&lt;class Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus&gt; progressTracker, bool notRecurse, bool resume, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient.BulkDownload(System.String,System.String,System.Int32,Microsoft.Azure.DataLake.Store.IfExists,System.IProgress{Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus},System.Boolean,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function BulkDownload (srcPath As String, destPath As String, Optional numThreads As Integer = -1, Optional shouldOverwrite As IfExists = Microsoft.Azure.DataLake.Store.IfExists.Overwrite, Optional progressTracker As IProgress(Of TransferStatus) = null, Optional notRecurse As Boolean = false, Optional resume As Boolean = false, Optional cancelToken As CancellationToken = null) As TransferStatus" />
      <MemberSignature Language="F#" Value="override this.BulkDownload : string * string * int * Microsoft.Azure.DataLake.Store.IfExists * IProgress&lt;Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus&gt; * bool * bool * System.Threading.CancellationToken -&gt; Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus" Usage="mockAdlsClient.BulkDownload (srcPath, destPath, numThreads, shouldOverwrite, progressTracker, notRecurse, resume, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="srcPath" Type="System.String" />
        <Parameter Name="destPath" Type="System.String" />
        <Parameter Name="numThreads" Type="System.Int32" />
        <Parameter Name="shouldOverwrite" Type="Microsoft.Azure.DataLake.Store.IfExists" />
        <Parameter Name="progressTracker" Type="System.IProgress&lt;Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus&gt;" />
        <Parameter Name="notRecurse" Type="System.Boolean" />
        <Parameter Name="resume" Type="System.Boolean" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="srcPath">リモート ソース パス</param>
        <param name="destPath">ローカルのコピー先のパス。 ディレクトリに常になります。</param>
        <param name="numThreads">未使用</param>
        <param name="shouldOverwrite">上書きするか、変換先が存在する場合は、省略するかどうか</param>
        <param name="progressTracker">未使用</param>
        <param name="notRecurse">未使用</param>
        <param name="resume">未使用</param>
        <param name="cancelToken">To be added.</param>
        <summary>
            ローカル ファイルに保存およびメモリ ストリームからデータを読み取ります
            </summary>
        <returns>ダウンロードの詳細をカプセル化する転送状態</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BulkUpload">
      <MemberSignature Language="C#" Value="public override Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus BulkUpload (string srcPath, string destPath, int numThreads = -1, Microsoft.Azure.DataLake.Store.IfExists shouldOverwrite = Microsoft.Azure.DataLake.Store.IfExists.Overwrite, IProgress&lt;Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus&gt; progressTracker = null, bool notRecurse = false, bool resume = false, bool isBinary = false, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus BulkUpload(string srcPath, string destPath, int32 numThreads, valuetype Microsoft.Azure.DataLake.Store.IfExists shouldOverwrite, class System.IProgress`1&lt;class Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus&gt; progressTracker, bool notRecurse, bool resume, bool isBinary, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient.BulkUpload(System.String,System.String,System.Int32,Microsoft.Azure.DataLake.Store.IfExists,System.IProgress{Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus},System.Boolean,System.Boolean,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function BulkUpload (srcPath As String, destPath As String, Optional numThreads As Integer = -1, Optional shouldOverwrite As IfExists = Microsoft.Azure.DataLake.Store.IfExists.Overwrite, Optional progressTracker As IProgress(Of TransferStatus) = null, Optional notRecurse As Boolean = false, Optional resume As Boolean = false, Optional isBinary As Boolean = false, Optional cancelToken As CancellationToken = null) As TransferStatus" />
      <MemberSignature Language="F#" Value="override this.BulkUpload : string * string * int * Microsoft.Azure.DataLake.Store.IfExists * IProgress&lt;Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus&gt; * bool * bool * bool * System.Threading.CancellationToken -&gt; Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus" Usage="mockAdlsClient.BulkUpload (srcPath, destPath, numThreads, shouldOverwrite, progressTracker, notRecurse, resume, isBinary, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="srcPath" Type="System.String" />
        <Parameter Name="destPath" Type="System.String" />
        <Parameter Name="numThreads" Type="System.Int32" />
        <Parameter Name="shouldOverwrite" Type="Microsoft.Azure.DataLake.Store.IfExists" />
        <Parameter Name="progressTracker" Type="System.IProgress&lt;Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus&gt;" />
        <Parameter Name="notRecurse" Type="System.Boolean" />
        <Parameter Name="resume" Type="System.Boolean" />
        <Parameter Name="isBinary" Type="System.Boolean" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="srcPath">ローカルのソース パス</param>
        <param name="destPath">リモート宛先パス - ディレクトリ必要があります。</param>
        <param name="numThreads">未使用</param>
        <param name="shouldOverwrite">上書きするか、変換先が存在する場合は、省略するかどうか</param>
        <param name="progressTracker">未使用</param>
        <param name="notRecurse">未使用</param>
        <param name="resume">未使用</param>
        <param name="isBinary">未使用</param>
        <param name="cancelToken">To be added.</param>
        <summary>
            ファイルのみが一括アップロードされます。 ローカル ファイルを読み取り、エントリのメモリ ストリームを保持
            </summary>
        <returns>アップロードの詳細をカプセル化する転送状態</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConcatenateFiles">
      <MemberSignature Language="C#" Value="public override void ConcatenateFiles (string destination, System.Collections.Generic.List&lt;string&gt; concatFiles, bool deleteSource = false, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void ConcatenateFiles(string destination, class System.Collections.Generic.List`1&lt;string&gt; concatFiles, bool deleteSource, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient.ConcatenateFiles(System.String,System.Collections.Generic.List{System.String},System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub ConcatenateFiles (destination As String, concatFiles As List(Of String), Optional deleteSource As Boolean = false, Optional cancelToken As CancellationToken = null)" />
      <MemberSignature Language="F#" Value="override this.ConcatenateFiles : string * System.Collections.Generic.List&lt;string&gt; * bool * System.Threading.CancellationToken -&gt; unit" Usage="mockAdlsClient.ConcatenateFiles (destination, concatFiles, deleteSource, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="destination" Type="System.String" />
        <Parameter Name="concatFiles" Type="System.Collections.Generic.List&lt;System.String&gt;" />
        <Parameter Name="deleteSource" Type="System.Boolean" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="destination">宛先エントリ</param>
        <param name="concatFiles">Concat ファイル</param>
        <param name="deleteSource">ソースを削除する場合は true。</param>
        <param name="cancelToken">キャンセル トークン</param>
        <summary>
            Concats メモリ ストリーム ソースのエントリの新しいメモリ ストリームにマージし
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDirectory">
      <MemberSignature Language="C#" Value="public override bool CreateDirectory (string dirName, string octalPermission = null, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool CreateDirectory(string dirName, string octalPermission, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient.CreateDirectory(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CreateDirectory (dirName As String, Optional octalPermission As String = null, Optional cancelToken As CancellationToken = null) As Boolean" />
      <MemberSignature Language="F#" Value="override this.CreateDirectory : string * string * System.Threading.CancellationToken -&gt; bool" Usage="mockAdlsClient.CreateDirectory (dirName, octalPermission, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="dirName" Type="System.String" />
        <Parameter Name="octalPermission" Type="System.String" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="dirName">ディレクトリ名</param>
        <param name="octalPermission">8 進数のアクセス許可</param>
        <param name="cancelToken">Cacnellation トークン</param>
        <summary>
            作成、内部辞書内にあるディレクトリのエントリをディレクトリ-を作成します。
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFile">
      <MemberSignature Language="C#" Value="public override Microsoft.Azure.DataLake.Store.AdlsOutputStream CreateFile (string filename, Microsoft.Azure.DataLake.Store.IfExists mode, string octalPermission = null, bool createParent = true);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.Azure.DataLake.Store.AdlsOutputStream CreateFile(string filename, valuetype Microsoft.Azure.DataLake.Store.IfExists mode, string octalPermission, bool createParent) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient.CreateFile(System.String,Microsoft.Azure.DataLake.Store.IfExists,System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CreateFile (filename As String, mode As IfExists, Optional octalPermission As String = null, Optional createParent As Boolean = true) As AdlsOutputStream" />
      <MemberSignature Language="F#" Value="override this.CreateFile : string * Microsoft.Azure.DataLake.Store.IfExists * string * bool -&gt; Microsoft.Azure.DataLake.Store.AdlsOutputStream" Usage="mockAdlsClient.CreateFile (filename, mode, octalPermission, createParent)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.DataLake.Store.AdlsOutputStream</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filename" Type="System.String" />
        <Parameter Name="mode" Type="Microsoft.Azure.DataLake.Store.IfExists" />
        <Parameter Name="octalPermission" Type="System.String" />
        <Parameter Name="createParent" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="filename">ファイル名</param>
        <param name="mode">場合に失敗したりする上書き仕掛けてが存在します。</param>
        <param name="octalPermission">アクセス許可文字列</param>
        <param name="createParent">親を作成する場合は true。 ディレクトリ - 現在影響を与えません</param>
        <summary>
            新しいファイルの内部ディクショナリへのエントリを作成します。 AclStatus、DirectoryEntry およびメモリ ストリーム エントリをカプセル化します。
            </summary>
        <returns>モック ADls 出力ストリーム</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public override bool Delete (string path, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Delete(string path, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient.Delete(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Delete (path As String, Optional cancelToken As CancellationToken = null) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Delete : string * System.Threading.CancellationToken -&gt; bool" Usage="mockAdlsClient.Delete (path, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">ファイルまたはディレクトリのパス</param>
        <param name="cancelToken">キャンセル トークン</param>
        <summary>
            内部辞書からエントリを削除します。
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteRecursive">
      <MemberSignature Language="C#" Value="public override bool DeleteRecursive (string path, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool DeleteRecursive(string path, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient.DeleteRecursive(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function DeleteRecursive (path As String, Optional cancelToken As CancellationToken = null) As Boolean" />
      <MemberSignature Language="F#" Value="override this.DeleteRecursive : string * System.Threading.CancellationToken -&gt; bool" Usage="mockAdlsClient.DeleteRecursive (path, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">ディレクトリまたはファイルのパス</param>
        <param name="cancelToken">キャンセル トークン</param>
        <summary>
            ディレクトリまたは削除ファイル内のすべてのエントリを削除します。
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnumerateDirectory">
      <MemberSignature Language="C#" Value="public override System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.DataLake.Store.DirectoryEntry&gt; EnumerateDirectory (string path, Microsoft.Azure.DataLake.Store.UserGroupRepresentation userIdFormat = Microsoft.Azure.DataLake.Store.UserGroupRepresentation.ObjectID, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.DataLake.Store.DirectoryEntry&gt; EnumerateDirectory(string path, valuetype Microsoft.Azure.DataLake.Store.UserGroupRepresentation userIdFormat, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient.EnumerateDirectory(System.String,Microsoft.Azure.DataLake.Store.UserGroupRepresentation,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function EnumerateDirectory (path As String, Optional userIdFormat As UserGroupRepresentation = Microsoft.Azure.DataLake.Store.UserGroupRepresentation.ObjectID, Optional cancelToken As CancellationToken = null) As IEnumerable(Of DirectoryEntry)" />
      <MemberSignature Language="F#" Value="override this.EnumerateDirectory : string * Microsoft.Azure.DataLake.Store.UserGroupRepresentation * System.Threading.CancellationToken -&gt; seq&lt;Microsoft.Azure.DataLake.Store.DirectoryEntry&gt;" Usage="mockAdlsClient.EnumerateDirectory (path, userIdFormat, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.DataLake.Store.DirectoryEntry&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="userIdFormat" Type="Microsoft.Azure.DataLake.Store.UserGroupRepresentation" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">ディレクトリまたはファイルのパス</param>
        <param name="userIdFormat">ユーザーまたはグループの Id の形式</param>
        <param name="cancelToken">キャンセル トークン</param>
        <summary>
            指定したディレクトリの下に含まれるエントリの一覧を返します
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAclStatus">
      <MemberSignature Language="C#" Value="public override Microsoft.Azure.DataLake.Store.Acl.AclStatus GetAclStatus (string path, Microsoft.Azure.DataLake.Store.UserGroupRepresentation userIdFormat = Microsoft.Azure.DataLake.Store.UserGroupRepresentation.ObjectID, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.Azure.DataLake.Store.Acl.AclStatus GetAclStatus(string path, valuetype Microsoft.Azure.DataLake.Store.UserGroupRepresentation userIdFormat, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient.GetAclStatus(System.String,Microsoft.Azure.DataLake.Store.UserGroupRepresentation,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetAclStatus (path As String, Optional userIdFormat As UserGroupRepresentation = Microsoft.Azure.DataLake.Store.UserGroupRepresentation.ObjectID, Optional cancelToken As CancellationToken = null) As AclStatus" />
      <MemberSignature Language="F#" Value="override this.GetAclStatus : string * Microsoft.Azure.DataLake.Store.UserGroupRepresentation * System.Threading.CancellationToken -&gt; Microsoft.Azure.DataLake.Store.Acl.AclStatus" Usage="mockAdlsClient.GetAclStatus (path, userIdFormat, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.DataLake.Store.Acl.AclStatus</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="userIdFormat" Type="Microsoft.Azure.DataLake.Store.UserGroupRepresentation" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">ファイルまたはディレクトリのパス</param>
        <param name="userIdFormat">ユーザー/グループ オブジェクトを表現する方法</param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            ACL エントリの一覧、所有者 ID、グループ ID、8 進数のアクセス許可およびファイルまたはディレクトリの (ディレクトリ) の場合のみ sticky ビットを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAppendStream">
      <MemberSignature Language="C#" Value="public override Microsoft.Azure.DataLake.Store.AdlsOutputStream GetAppendStream (string filename, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.Azure.DataLake.Store.AdlsOutputStream GetAppendStream(string filename, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient.GetAppendStream(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetAppendStream (filename As String, Optional cancelToken As CancellationToken = null) As AdlsOutputStream" />
      <MemberSignature Language="F#" Value="override this.GetAppendStream : string * System.Threading.CancellationToken -&gt; Microsoft.Azure.DataLake.Store.AdlsOutputStream" Usage="mockAdlsClient.GetAppendStream (filename, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.DataLake.Store.AdlsOutputStream</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filename" Type="System.String" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="filename">ファイル名</param>
        <param name="cancelToken">キャンセル トークン</param>
        <summary>
            モック adls 出力ストリーム内のカプセル化されたファイルに追加メモリ ストリームを返します。
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDirectoryEntry">
      <MemberSignature Language="C#" Value="public override Microsoft.Azure.DataLake.Store.DirectoryEntry GetDirectoryEntry (string path, Microsoft.Azure.DataLake.Store.UserGroupRepresentation userIdFormat = Microsoft.Azure.DataLake.Store.UserGroupRepresentation.ObjectID, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.Azure.DataLake.Store.DirectoryEntry GetDirectoryEntry(string path, valuetype Microsoft.Azure.DataLake.Store.UserGroupRepresentation userIdFormat, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient.GetDirectoryEntry(System.String,Microsoft.Azure.DataLake.Store.UserGroupRepresentation,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetDirectoryEntry (path As String, Optional userIdFormat As UserGroupRepresentation = Microsoft.Azure.DataLake.Store.UserGroupRepresentation.ObjectID, Optional cancelToken As CancellationToken = null) As DirectoryEntry" />
      <MemberSignature Language="F#" Value="override this.GetDirectoryEntry : string * Microsoft.Azure.DataLake.Store.UserGroupRepresentation * System.Threading.CancellationToken -&gt; Microsoft.Azure.DataLake.Store.DirectoryEntry" Usage="mockAdlsClient.GetDirectoryEntry (path, userIdFormat, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.DataLake.Store.DirectoryEntry</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="userIdFormat" Type="Microsoft.Azure.DataLake.Store.UserGroupRepresentation" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">ファイルまたはディレクトリのパス</param>
        <param name="userIdFormat">ユーザーまたはグループの Id の形式</param>
        <param name="cancelToken">キャンセル トークン</param>
        <summary>
            ディレクトリまたはファイルの情報を取得します。
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMockClient">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient GetMockClient ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient GetMockClient() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient.GetMockClient" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetMockClient () As MockAdlsClient" />
      <MemberSignature Language="F#" Value="static member GetMockClient : unit -&gt; Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient" Usage="Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient.GetMockClient " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            モック adls クライアントのインスタンスを返すファクトリ メソッド
            </summary>
        <returns>モック ADls クライアント</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetReadStream">
      <MemberSignature Language="C#" Value="public override Microsoft.Azure.DataLake.Store.AdlsInputStream GetReadStream (string filename, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.Azure.DataLake.Store.AdlsInputStream GetReadStream(string filename, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient.GetReadStream(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetReadStream (filename As String, Optional cancelToken As CancellationToken = null) As AdlsInputStream" />
      <MemberSignature Language="F#" Value="override this.GetReadStream : string * System.Threading.CancellationToken -&gt; Microsoft.Azure.DataLake.Store.AdlsInputStream" Usage="mockAdlsClient.GetReadStream (filename, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.DataLake.Store.AdlsInputStream</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filename" Type="System.String" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="filename">ファイル名</param>
        <param name="cancelToken">キャンセル トークン</param>
        <summary>
            ファイルのデータを読み取るためのメモリ ストリームを返します
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ModifyAclEntries">
      <MemberSignature Language="C#" Value="public override void ModifyAclEntries (string path, System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; aclSpec, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void ModifyAclEntries(string path, class System.Collections.Generic.List`1&lt;class Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; aclSpec, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient.ModifyAclEntries(System.String,System.Collections.Generic.List{Microsoft.Azure.DataLake.Store.Acl.AclEntry},System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub ModifyAclEntries (path As String, aclSpec As List(Of AclEntry), Optional cancelToken As CancellationToken = null)" />
      <MemberSignature Language="F#" Value="override this.ModifyAclEntries : string * System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; * System.Threading.CancellationToken -&gt; unit" Usage="mockAdlsClient.ModifyAclEntries (path, aclSpec, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclSpec" Type="System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt;" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">ファイルまたはディレクトリのパス</param>
        <param name="aclSpec">Acl リストを追加するには</param>
        <param name="cancelToken">キャンセル トークン</param>
        <summary>
            指定したパスの acl エントリを追加します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAclEntries">
      <MemberSignature Language="C#" Value="public override void RemoveAclEntries (string path, System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; aclSpec, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void RemoveAclEntries(string path, class System.Collections.Generic.List`1&lt;class Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; aclSpec, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient.RemoveAclEntries(System.String,System.Collections.Generic.List{Microsoft.Azure.DataLake.Store.Acl.AclEntry},System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub RemoveAclEntries (path As String, aclSpec As List(Of AclEntry), Optional cancelToken As CancellationToken = null)" />
      <MemberSignature Language="F#" Value="override this.RemoveAclEntries : string * System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; * System.Threading.CancellationToken -&gt; unit" Usage="mockAdlsClient.RemoveAclEntries (path, aclSpec, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclSpec" Type="System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt;" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">ファイルまたはディレクトリのパス</param>
        <param name="aclSpec">削除する Acl エントリの一覧</param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            削除は、ファイルまたはメモリに保持する内部 AclStatus からディレクトリの Acl エントリを指定します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAllAcls">
      <MemberSignature Language="C#" Value="public override void RemoveAllAcls (string path, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void RemoveAllAcls(string path, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient.RemoveAllAcls(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub RemoveAllAcls (path As String, Optional cancelToken As CancellationToken = null)" />
      <MemberSignature Language="F#" Value="override this.RemoveAllAcls : string * System.Threading.CancellationToken -&gt; unit" Usage="mockAdlsClient.RemoveAllAcls (path, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">ファイルまたはディレクトリのパス</param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            メモリに保持する内部 AclStatus からファイルまたはディレクトリのすべての Acl エントリを削除します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveDefaultAcls">
      <MemberSignature Language="C#" Value="public override void RemoveDefaultAcls (string path, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void RemoveDefaultAcls(string path, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient.RemoveDefaultAcls(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub RemoveDefaultAcls (path As String, Optional cancelToken As CancellationToken = null)" />
      <MemberSignature Language="F#" Value="override this.RemoveDefaultAcls : string * System.Threading.CancellationToken -&gt; unit" Usage="mockAdlsClient.RemoveDefaultAcls (path, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">ファイルまたはディレクトリのパス</param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            メモリに保持する内部 AclStatus からファイルまたはディレクトリのすべての Acl エントリの AclScope デフォルトを削除します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Rename">
      <MemberSignature Language="C#" Value="public override bool Rename (string path, string destination, bool overwrite = false, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Rename(string path, string destination, bool overwrite, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient.Rename(System.String,System.String,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Rename (path As String, destination As String, Optional overwrite As Boolean = false, Optional cancelToken As CancellationToken = null) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Rename : string * string * bool * System.Threading.CancellationToken -&gt; bool" Usage="mockAdlsClient.Rename (path, destination, overwrite, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="destination" Type="System.String" />
        <Parameter Name="overwrite" Type="System.Boolean" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">ソースのパス名</param>
        <param name="destination">移行先パス</param>
        <param name="overwrite">ターゲット ファイルを上書きする場合は true。</param>
        <param name="cancelToken">キャンセル トークン</param>
        <summary>
            ソースのエントリを削除し、ソースのエントリの同じメタデータを持つ内部ディクショナリ内に新しいエントリを追加
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetAcl">
      <MemberSignature Language="C#" Value="public override void SetAcl (string path, System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; aclSpec, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void SetAcl(string path, class System.Collections.Generic.List`1&lt;class Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; aclSpec, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient.SetAcl(System.String,System.Collections.Generic.List{Microsoft.Azure.DataLake.Store.Acl.AclEntry},System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub SetAcl (path As String, aclSpec As List(Of AclEntry), Optional cancelToken As CancellationToken = null)" />
      <MemberSignature Language="F#" Value="override this.SetAcl : string * System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; * System.Threading.CancellationToken -&gt; unit" Usage="mockAdlsClient.SetAcl (path, aclSpec, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclSpec" Type="System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt;" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">ファイルまたはディレクトリのパス</param>
        <param name="aclSpec">Acl リストを設定するには</param>
        <param name="cancelToken">キャンセル トークン</param>
        <summary>
            指定されたパスに新しい acl エントリを設定します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetExpiryTime">
      <MemberSignature Language="C#" Value="public override void SetExpiryTime (string path, Microsoft.Azure.DataLake.Store.ExpiryOption eopt, long expiryTime, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void SetExpiryTime(string path, valuetype Microsoft.Azure.DataLake.Store.ExpiryOption eopt, int64 expiryTime, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient.SetExpiryTime(System.String,Microsoft.Azure.DataLake.Store.ExpiryOption,System.Int64,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub SetExpiryTime (path As String, eopt As ExpiryOption, expiryTime As Long, Optional cancelToken As CancellationToken = null)" />
      <MemberSignature Language="F#" Value="override this.SetExpiryTime : string * Microsoft.Azure.DataLake.Store.ExpiryOption * int64 * System.Threading.CancellationToken -&gt; unit" Usage="mockAdlsClient.SetExpiryTime (path, eopt, expiryTime, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="eopt" Type="Microsoft.Azure.DataLake.Store.ExpiryOption" />
        <Parameter Name="expiryTime" Type="System.Int64" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">ファイルまたはディレクトリのパス</param>
        <param name="eopt">有効期限オプション</param>
        <param name="expiryTime">有効期限</param>
        <param name="cancelToken">キャンセル トークン</param>
        <summary>
            ファイルの有効期限を設定します。 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetOwner">
      <MemberSignature Language="C#" Value="public override void SetOwner (string path, string owner, string group, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void SetOwner(string path, string owner, string group, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient.SetOwner(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub SetOwner (path As String, owner As String, group As String, Optional cancelToken As CancellationToken = null)" />
      <MemberSignature Language="F#" Value="override this.SetOwner : string * string * string * System.Threading.CancellationToken -&gt; unit" Usage="mockAdlsClient.SetOwner (path, owner, group, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="owner" Type="System.String" />
        <Parameter Name="group" Type="System.String" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">ファイルまたはディレクトリのパス</param>
        <param name="owner">所有者の guid</param>
        <param name="group">グループの guid</param>
        <param name="cancelToken">キャンセル トークン</param>
        <summary>
            所有者とパスのグループを設定します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPermission">
      <MemberSignature Language="C#" Value="public override void SetPermission (string path, string permission, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void SetPermission(string path, string permission, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.MockAdlsFileSystem.MockAdlsClient.SetPermission(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub SetPermission (path As String, permission As String, Optional cancelToken As CancellationToken = null)" />
      <MemberSignature Language="F#" Value="override this.SetPermission : string * string * System.Threading.CancellationToken -&gt; unit" Usage="mockAdlsClient.SetPermission (path, permission, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="permission" Type="System.String" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">ファイルまたはディレクトリのパス</param>
        <param name="permission">アクセス許可文字列</param>
        <param name="cancelToken">キャンセル トークン</param>
        <summary>
            指定されたパスのアクセス許可文字列を設定します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>