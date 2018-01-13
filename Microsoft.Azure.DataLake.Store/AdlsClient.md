<Type Name="AdlsClient" FullName="Microsoft.Azure.DataLake.Store.AdlsClient">
  <TypeSignature Language="C#" Value="public class AdlsClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi AdlsClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.DataLake.Store.AdlsClient" />
  <TypeSignature Language="VB.NET" Value="Public Class AdlsClient" />
  <TypeSignature Language="F#" Value="type AdlsClient = class" />
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
            Azure data lake store のクライアントです。 呼び出す簡単かつコア Api よりも使いやすくする REST API の操作を実行するパブリック Api が含まれています。 コア Api は、自由度が高く、ADLSClient 提供よく使用される形式を提供します。
            これには、承認トークンとトークンの更新がカプセル化します。 受け取り、ServiceClientCredential または文字列 auth をトークンをこのクラスのインスタンスを返すためのファクトリ メソッドが含まれています。 すべての操作で async および sync バージョンを提供します。 すべての同期メソッドが例外を作成する非同期メソッドでの待機し、同時実行の追加します。 現在このクラスは、継承コンス トラクターを公開がないためです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected AdlsClient ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Moq テストの protected コンス トラクター
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountFQDN">
      <MemberSignature Language="C#" Value="public string AccountFQDN { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AccountFQDN" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.AdlsClient.AccountFQDN" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccountFQDN As String" />
      <MemberSignature Language="F#" Value="member this.AccountFQDN : string" Usage="Microsoft.Azure.DataLake.Store.AdlsClient.AccountFQDN" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            完全なドメイン名を含む azure データ lake store アカウント名
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddUserAgentSuffix">
      <MemberSignature Language="C#" Value="public void AddUserAgentSuffix (string suffix);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void AddUserAgentSuffix(string suffix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.AddUserAgentSuffix(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub AddUserAgentSuffix (suffix As String)" />
      <MemberSignature Language="F#" Value="member this.AddUserAgentSuffix : string -&gt; unit" Usage="adlsClient.AddUserAgentSuffix suffix" />
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
        <Parameter Name="suffix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="suffix">ユーザー エージェントのサフィックス</param>
        <summary>
            ユーザー エージェントのサフィックスを追加します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BulkDownload">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus BulkDownload (string srcPath, string destPath, int numThreads = -1, Microsoft.Azure.DataLake.Store.IfExists shouldOverwrite = Microsoft.Azure.DataLake.Store.IfExists.Overwrite, IProgress&lt;Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus&gt; progressTracker = null, bool notRecurse = false, bool resume = false, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus BulkDownload(string srcPath, string destPath, int32 numThreads, valuetype Microsoft.Azure.DataLake.Store.IfExists shouldOverwrite, class System.IProgress`1&lt;class Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus&gt; progressTracker, bool notRecurse, bool resume, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.BulkDownload(System.String,System.String,System.Int32,Microsoft.Azure.DataLake.Store.IfExists,System.IProgress{Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus},System.Boolean,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BulkDownload (srcPath As String, destPath As String, Optional numThreads As Integer = -1, Optional shouldOverwrite As IfExists = Microsoft.Azure.DataLake.Store.IfExists.Overwrite, Optional progressTracker As IProgress(Of TransferStatus) = null, Optional notRecurse As Boolean = false, Optional resume As Boolean = false, Optional cancelToken As CancellationToken = null) As TransferStatus" />
      <MemberSignature Language="F#" Value="abstract member BulkDownload : string * string * int * Microsoft.Azure.DataLake.Store.IfExists * IProgress&lt;Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus&gt; * bool * bool * System.Threading.CancellationToken -&gt; Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus&#xA;override this.BulkDownload : string * string * int * Microsoft.Azure.DataLake.Store.IfExists * IProgress&lt;Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus&gt; * bool * bool * System.Threading.CancellationToken -&gt; Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus" Usage="adlsClient.BulkDownload (srcPath, destPath, numThreads, shouldOverwrite, progressTracker, notRecurse, resume, cancelToken)" />
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
        <param name="numThreads">成功しなかった場合のスレッドの数になります (8 回の物理コアの数) のスレッドの既定の数</param>
        <param name="shouldOverwrite">上書きするか、変換先が存在する場合は、省略するかどうか</param>
        <param name="progressTracker">ファイル転送の進捗状況を追跡するために Progresstracker</param>
        <param name="notRecurse">True の場合は列挙 else レベルの 1 つは再帰的な列挙まで</param>
        <param name="resume">True の場合、たい最後の転送からを再開するには</param>
        <param name="cancelToken">トークンをキャンセルします。</param>
        <summary>
            ディレクトリまたはファイルをリモート サーバーからローカルにダウンロードします。 コピー先ディレクトリの下にソース ディレクトリの下にあるコンテンツを転送します。 ソース ファイルを転送し、転送先のパスとして保存します。
            </summary>
        <returns>ダウンロードの詳細をカプセル化する転送状態</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BulkUpload">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus BulkUpload (string srcPath, string destPath, int numThreads = -1, Microsoft.Azure.DataLake.Store.IfExists shouldOverwrite = Microsoft.Azure.DataLake.Store.IfExists.Overwrite, IProgress&lt;Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus&gt; progressTracker = null, bool notRecurse = false, bool resume = false, bool isBinary = false, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus BulkUpload(string srcPath, string destPath, int32 numThreads, valuetype Microsoft.Azure.DataLake.Store.IfExists shouldOverwrite, class System.IProgress`1&lt;class Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus&gt; progressTracker, bool notRecurse, bool resume, bool isBinary, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.BulkUpload(System.String,System.String,System.Int32,Microsoft.Azure.DataLake.Store.IfExists,System.IProgress{Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus},System.Boolean,System.Boolean,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BulkUpload (srcPath As String, destPath As String, Optional numThreads As Integer = -1, Optional shouldOverwrite As IfExists = Microsoft.Azure.DataLake.Store.IfExists.Overwrite, Optional progressTracker As IProgress(Of TransferStatus) = null, Optional notRecurse As Boolean = false, Optional resume As Boolean = false, Optional isBinary As Boolean = false, Optional cancelToken As CancellationToken = null) As TransferStatus" />
      <MemberSignature Language="F#" Value="abstract member BulkUpload : string * string * int * Microsoft.Azure.DataLake.Store.IfExists * IProgress&lt;Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus&gt; * bool * bool * bool * System.Threading.CancellationToken -&gt; Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus&#xA;override this.BulkUpload : string * string * int * Microsoft.Azure.DataLake.Store.IfExists * IProgress&lt;Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus&gt; * bool * bool * bool * System.Threading.CancellationToken -&gt; Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus" Usage="adlsClient.BulkUpload (srcPath, destPath, numThreads, shouldOverwrite, progressTracker, notRecurse, resume, isBinary, cancelToken)" />
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
        <param name="numThreads">成功しなかった場合のスレッドの数になります (8 回の物理コアの数) のスレッドの既定の数</param>
        <param name="shouldOverwrite">上書きするか、変換先が存在する場合は、省略するかどうか</param>
        <param name="progressTracker">ファイル転送の進捗状況を追跡するために Progresstracker</param>
        <param name="notRecurse">True の場合は列挙 else レベルの 1 つは再帰的な列挙まで</param>
        <param name="resume">True の場合、たい最後の転送からを再開するには</param>
        <param name="isBinary">False の場合は、改行文字境界でデータ lake にファイルを書き込みます。 True の場合、この guranteed はありません、アップロードは速くなります。</param>
        <param name="cancelToken">キャンセル トークン</param>
        <summary>
            ディレクトリまたはローカルからリモートへのファイルをアップロードします。 コピー先ディレクトリの下にソース ディレクトリの下にあるコンテンツを転送します。 ソース ファイルを転送し、転送先のパスとして保存します。
            </summary>
        <returns>アップロードの詳細をカプセル化する転送状態</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ChangeAcl">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.DataLake.Store.AclTools.AclProcessorStats ChangeAcl (string path, System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; aclEntries, Microsoft.Azure.DataLake.Store.AclTools.RequestedAclType type, int threadCount = -1);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.DataLake.Store.AclTools.AclProcessorStats ChangeAcl(string path, class System.Collections.Generic.List`1&lt;class Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; aclEntries, valuetype Microsoft.Azure.DataLake.Store.AclTools.RequestedAclType type, int32 threadCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.ChangeAcl(System.String,System.Collections.Generic.List{Microsoft.Azure.DataLake.Store.Acl.AclEntry},Microsoft.Azure.DataLake.Store.AclTools.RequestedAclType,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ChangeAcl (path As String, aclEntries As List(Of AclEntry), type As RequestedAclType, Optional threadCount As Integer = -1) As AclProcessorStats" />
      <MemberSignature Language="F#" Value="abstract member ChangeAcl : string * System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; * Microsoft.Azure.DataLake.Store.AclTools.RequestedAclType * int -&gt; Microsoft.Azure.DataLake.Store.AclTools.AclProcessorStats&#xA;override this.ChangeAcl : string * System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; * Microsoft.Azure.DataLake.Store.AclTools.RequestedAclType * int -&gt; Microsoft.Azure.DataLake.Store.AclTools.AclProcessorStats" Usage="adlsClient.ChangeAcl (path, aclEntries, type, threadCount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.DataLake.Store.AclTools.AclProcessorStats</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclEntries" Type="System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt;" />
        <Parameter Name="type" Type="Microsoft.Azure.DataLake.Store.AclTools.RequestedAclType" />
        <Parameter Name="threadCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="path">Acl の変更を開始する場所からルート ディレクトリのパス</param>
        <param name="aclEntries">または、追加設定または入力に応じてを削除する Acl エントリ</param>
        <param name="type">変更の種類<see cref="T:Microsoft.Azure.DataLake.Store.AclTools.RequestedAclType" /></param>
        <param name="threadCount">使用するスレッドの数</param>
        <summary>
            (変更セットおよび削除) の Acl が変更、ディレクトリ ツリーを再帰的に
            </summary>
        <returns>ファイルとディレクトリを処理の統計情報の合計数</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckAccess">
      <MemberSignature Language="C#" Value="public virtual bool CheckAccess (string path, string rwx, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool CheckAccess(string path, string rwx, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.CheckAccess(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function CheckAccess (path As String, rwx As String, Optional cancelToken As CancellationToken = null) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member CheckAccess : string * string * System.Threading.CancellationToken -&gt; bool&#xA;override this.CheckAccess : string * string * System.Threading.CancellationToken -&gt; bool" Usage="adlsClient.CheckAccess (path, rwx, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="rwx" Type="System.String" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">ファイルまたはディレクトリのパス</param>
        <param name="rwx">"Rwx"の文字列形式のチェックインを許可します。 例をユーザーがかどうかに読み取りを参照する場合は、アクセス許可を実行、文字列になります r x </param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            ユーザー/グループが、指定されたパスへのアクセスを指定したかを確認します。
            </summary>
        <returns>クライアントでは、それ以外の場合は false のパスへのアクセスがある場合は true。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckAccessAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; CheckAccessAsync (string path, string rwx, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CheckAccessAsync(string path, string rwx, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.CheckAccessAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function CheckAccessAsync (path As String, rwx As String, Optional cancelToken As CancellationToken = null) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member CheckAccessAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.CheckAccessAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="adlsClient.CheckAccessAsync (path, rwx, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.AdlsClient/&lt;CheckAccessAsync&gt;d__59))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="rwx" Type="System.String" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">ファイルまたはディレクトリのパス</param>
        <param name="rwx">"Rwx"の文字列形式のチェックインを許可します。 例をユーザーがかどうかに読み取りを参照する場合は、アクセス許可を実行、文字列になります r x </param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            ユーザー/グループが、指定されたパスへのアクセスを指定したかどうかは非同期的に確認します。
            </summary>
        <returns>クライアントでは、それ以外の場合は false のパスへのアクセスがある場合は true。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckExists">
      <MemberSignature Language="C#" Value="public virtual bool CheckExists (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool CheckExists(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.CheckExists(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function CheckExists (path As String) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member CheckExists : string -&gt; bool&#xA;override this.CheckExists : string -&gt; bool" Usage="adlsClient.CheckExists path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">パス名</param>
        <summary>
            ファイルまたはディレクトリが存在するかどうかを確認します。
            </summary>
        <returns>パスには、他の false が存在する場合は true。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientId">
      <MemberSignature Language="C#" Value="public long ClientId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ClientId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.AdlsClient.ClientId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ClientId As Long" />
      <MemberSignature Language="F#" Value="member this.ClientId : int64" Usage="Microsoft.Azure.DataLake.Store.AdlsClient.ClientId" />
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
            クライアント オブジェクト ID
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConcatenateFiles">
      <MemberSignature Language="C#" Value="public virtual void ConcatenateFiles (string destination, System.Collections.Generic.List&lt;string&gt; concatFiles, bool deleteSource = false, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ConcatenateFiles(string destination, class System.Collections.Generic.List`1&lt;string&gt; concatFiles, bool deleteSource, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.ConcatenateFiles(System.String,System.Collections.Generic.List{System.String},System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub ConcatenateFiles (destination As String, concatFiles As List(Of String), Optional deleteSource As Boolean = false, Optional cancelToken As CancellationToken = null)" />
      <MemberSignature Language="F#" Value="abstract member ConcatenateFiles : string * System.Collections.Generic.List&lt;string&gt; * bool * System.Threading.CancellationToken -&gt; unit&#xA;override this.ConcatenateFiles : string * System.Collections.Generic.List&lt;string&gt; * bool * System.Threading.CancellationToken -&gt; unit" Usage="adlsClient.ConcatenateFiles (destination, concatFiles, deleteSource, cancelToken)" />
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
        <Parameter Name="destination" Type="System.String" />
        <Parameter Name="concatFiles" Type="System.Collections.Generic.List&lt;System.String&gt;" />
        <Parameter Name="deleteSource" Type="System.Boolean" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="destination">変換先のパス</param>
        <param name="concatFiles">ソース ファイルのパスを含むリスト</param>
        <param name="deleteSource">True の場合、削除、ソース ディレクトリその下にあるすべてのファイルを連結する場合</param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            対象のファイルにソース ファイルを連結する同期 API
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConcatenateFilesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task ConcatenateFilesAsync (string destination, System.Collections.Generic.List&lt;string&gt; concatFiles, bool deleteSource = false, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ConcatenateFilesAsync(string destination, class System.Collections.Generic.List`1&lt;string&gt; concatFiles, bool deleteSource, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.ConcatenateFilesAsync(System.String,System.Collections.Generic.List{System.String},System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ConcatenateFilesAsync (destination As String, concatFiles As List(Of String), Optional deleteSource As Boolean = false, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member ConcatenateFilesAsync : string * System.Collections.Generic.List&lt;string&gt; * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.ConcatenateFilesAsync : string * System.Collections.Generic.List&lt;string&gt; * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="adlsClient.ConcatenateFilesAsync (destination, concatFiles, deleteSource, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.AdlsClient/&lt;ConcatenateFilesAsync&gt;d__53))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="destination" Type="System.String" />
        <Parameter Name="concatFiles" Type="System.Collections.Generic.List&lt;System.String&gt;" />
        <Parameter Name="deleteSource" Type="System.Boolean" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="destination">変換先のパス</param>
        <param name="concatFiles">ソース ファイルのパスを含むリスト</param>
        <param name="deleteSource">True の場合、削除、ソース ディレクトリその下にあるすべてのファイルを連結する場合</param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            対象のファイルにソース ファイルを連結する非同期 API
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConcurrentAppend">
      <MemberSignature Language="C#" Value="public virtual void ConcurrentAppend (string path, bool autoCreate, byte[] dataBytes, int offset, int length);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ConcurrentAppend(string path, bool autoCreate, unsigned int8[] dataBytes, int32 offset, int32 length) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.ConcurrentAppend(System.String,System.Boolean,System.Byte[],System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub ConcurrentAppend (path As String, autoCreate As Boolean, dataBytes As Byte(), offset As Integer, length As Integer)" />
      <MemberSignature Language="F#" Value="abstract member ConcurrentAppend : string * bool * byte[] * int * int -&gt; unit&#xA;override this.ConcurrentAppend : string * bool * byte[] * int * int -&gt; unit" Usage="adlsClient.ConcurrentAppend (path, autoCreate, dataBytes, offset, length)" />
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
      </Parameters>
      <Docs>
        <param name="path">ファイルのパス</param>
        <param name="autoCreate"></param>
        <param name="dataBytes">ファイルに書き込むバイトの配列</param>
        <param name="offset">バイト配列内のオフセットします。</param>
        <param name="length">オフセット位置から書き込むバイト数</param>
        <summary>
            同時実行を同期 API は、サーバーに追加します。 オフセットが発生する追加サーバーによって決定されます。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConcurrentAppendAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task ConcurrentAppendAsync (string path, bool autoCreate, byte[] dataBytes, int offset, int length, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ConcurrentAppendAsync(string path, bool autoCreate, unsigned int8[] dataBytes, int32 offset, int32 length, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.ConcurrentAppendAsync(System.String,System.Boolean,System.Byte[],System.Int32,System.Int32,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ConcurrentAppendAsync (path As String, autoCreate As Boolean, dataBytes As Byte(), offset As Integer, length As Integer, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member ConcurrentAppendAsync : string * bool * byte[] * int * int * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.ConcurrentAppendAsync : string * bool * byte[] * int * int * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="adlsClient.ConcurrentAppendAsync (path, autoCreate, dataBytes, offset, length, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.AdlsClient/&lt;ConcurrentAppendAsync&gt;d__78))</AttributeName>
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
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">ファイルのパス</param>
        <param name="autoCreate"></param>
        <param name="dataBytes">ファイルに書き込むバイトの配列</param>
        <param name="offset">バイト配列内のオフセットします。</param>
        <param name="length">オフセット位置から書き込むバイト数</param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            同時実行を実行する非同期 API は、サーバーに追加します。 オフセットが発生する追加サーバーによって決定されます。 非同期操作です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateClient">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.DataLake.Store.AdlsClient CreateClient (string accountFqdn, Microsoft.Rest.ServiceClientCredentials creds);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.DataLake.Store.AdlsClient CreateClient(string accountFqdn, class Microsoft.Rest.ServiceClientCredentials creds) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.CreateClient(System.String,Microsoft.Rest.ServiceClientCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateClient (accountFqdn As String, creds As ServiceClientCredentials) As AdlsClient" />
      <MemberSignature Language="F#" Value="static member CreateClient : string * Microsoft.Rest.ServiceClientCredentials -&gt; Microsoft.Azure.DataLake.Store.AdlsClient" Usage="Microsoft.Azure.DataLake.Store.AdlsClient.CreateClient (accountFqdn, creds)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.DataLake.Store.AdlsClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountFqdn" Type="System.String" />
        <Parameter Name="creds" Type="Microsoft.Rest.ServiceClientCredentials" />
      </Parameters>
      <Docs>
        <param name="accountFqdn">完全なドメイン名 (例: contoso.azuredatalakestore.net) を含む azure データ lake store アカウント名</param>
        <param name="creds">認証トークンを取得する資格情報</param>
        <summary>
            返す、AdlsClient ファクトリ メソッド
            </summary>
        <returns>AdlsClient</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateClient">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.DataLake.Store.AdlsClient CreateClient (string accountFqdn, string token);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.DataLake.Store.AdlsClient CreateClient(string accountFqdn, string token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.CreateClient(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateClient (accountFqdn As String, token As String) As AdlsClient" />
      <MemberSignature Language="F#" Value="static member CreateClient : string * string -&gt; Microsoft.Azure.DataLake.Store.AdlsClient" Usage="Microsoft.Azure.DataLake.Store.AdlsClient.CreateClient (accountFqdn, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.DataLake.Store.AdlsClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountFqdn" Type="System.String" />
        <Parameter Name="token" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="accountFqdn">完全なドメイン名 (例: contoso.azuredatalakestore.net) を含む azure データ lake store アカウント名</param>
        <param name="token">完全承認トークンの例: Bearing: abcddsfere しています.</param>
        <summary>
            返す、AdlsClient ファクトリ メソッド
            </summary>
        <returns>AdlsClient</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDirectory">
      <MemberSignature Language="C#" Value="public virtual bool CreateDirectory (string dirName, string octalPermission = null, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool CreateDirectory(string dirName, string octalPermission, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.CreateDirectory(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function CreateDirectory (dirName As String, Optional octalPermission As String = null, Optional cancelToken As CancellationToken = null) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member CreateDirectory : string * string * System.Threading.CancellationToken -&gt; bool&#xA;override this.CreateDirectory : string * string * System.Threading.CancellationToken -&gt; bool" Usage="adlsClient.CreateDirectory (dirName, octalPermission, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
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
        <param name="dirName">ディレクトリの名前</param>
        <param name="octalPermission">8 進数のアクセス許可</param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            ディレクトリを作成する同期 API
            </summary>
        <returns>それ以外の場合は false、ディレクトリを作成する場合は true。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDirectoryAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; CreateDirectoryAsync (string dirName, string octalPermission = null, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CreateDirectoryAsync(string dirName, string octalPermission, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.CreateDirectoryAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function CreateDirectoryAsync (dirName As String, Optional octalPermission As String = null, Optional cancelToken As CancellationToken = null) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member CreateDirectoryAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.CreateDirectoryAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="adlsClient.CreateDirectoryAsync (dirName, octalPermission, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.AdlsClient/&lt;CreateDirectoryAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="dirName" Type="System.String" />
        <Parameter Name="octalPermission" Type="System.String" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="dirName">ディレクトリの名前</param>
        <param name="octalPermission">8 進数のアクセス許可</param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            ディレクトリを作成する非同期 API
            </summary>
        <returns>それ以外の場合は false、ディレクトリを作成する場合は true。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFile">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.DataLake.Store.AdlsOutputStream CreateFile (string filename, Microsoft.Azure.DataLake.Store.IfExists mode, string octalPermission = null, bool createParent = true);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.DataLake.Store.AdlsOutputStream CreateFile(string filename, valuetype Microsoft.Azure.DataLake.Store.IfExists mode, string octalPermission, bool createParent) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.CreateFile(System.String,Microsoft.Azure.DataLake.Store.IfExists,System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function CreateFile (filename As String, mode As IfExists, Optional octalPermission As String = null, Optional createParent As Boolean = true) As AdlsOutputStream" />
      <MemberSignature Language="F#" Value="abstract member CreateFile : string * Microsoft.Azure.DataLake.Store.IfExists * string * bool -&gt; Microsoft.Azure.DataLake.Store.AdlsOutputStream&#xA;override this.CreateFile : string * Microsoft.Azure.DataLake.Store.IfExists * string * bool -&gt; Microsoft.Azure.DataLake.Store.AdlsOutputStream" Usage="adlsClient.CreateFile (filename, mode, octalPermission, createParent)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
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
        <param name="mode">モードは上書きする場合は、既存のファイルを上書き</param>
        <param name="octalPermission">8 進数のアクセス許可文字列</param>
        <param name="createParent">True の場合は、存在しない親ディレクトリを作成します。</param>
        <summary>
            ファイルを作成してデータ ADLS でそのファイルを書き込むストリームを返す同期 API です。 排他アクセスでファイルを開く - を開くには、同じファイルで追加しようとするとは、このストリームが開いている間は失敗します。  
            
            スレッド処理: 返されたストリームはスレッド セーフであります。
            </summary>
        <returns>出力ストリーム</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFileAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.DataLake.Store.AdlsOutputStream&gt; CreateFileAsync (string filename, Microsoft.Azure.DataLake.Store.IfExists mode, string octalPermission = null, bool createParent = true, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.DataLake.Store.AdlsOutputStream&gt; CreateFileAsync(string filename, valuetype Microsoft.Azure.DataLake.Store.IfExists mode, string octalPermission, bool createParent, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.CreateFileAsync(System.String,Microsoft.Azure.DataLake.Store.IfExists,System.String,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function CreateFileAsync (filename As String, mode As IfExists, Optional octalPermission As String = null, Optional createParent As Boolean = true, Optional cancelToken As CancellationToken = null) As Task(Of AdlsOutputStream)" />
      <MemberSignature Language="F#" Value="abstract member CreateFileAsync : string * Microsoft.Azure.DataLake.Store.IfExists * string * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.DataLake.Store.AdlsOutputStream&gt;&#xA;override this.CreateFileAsync : string * Microsoft.Azure.DataLake.Store.IfExists * string * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.DataLake.Store.AdlsOutputStream&gt;" Usage="adlsClient.CreateFileAsync (filename, mode, octalPermission, createParent, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.AdlsClient/&lt;CreateFileAsync&gt;d__43))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.DataLake.Store.AdlsOutputStream&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filename" Type="System.String" />
        <Parameter Name="mode" Type="Microsoft.Azure.DataLake.Store.IfExists" />
        <Parameter Name="octalPermission" Type="System.String" />
        <Parameter Name="createParent" Type="System.Boolean" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="filename">ファイル名</param>
        <param name="mode">モードは上書きする場合は、既存のファイルを上書き</param>
        <param name="octalPermission">8 進数のアクセス許可文字列を null にすることができます。</param>
        <param name="createParent">True の場合は、存在しない親ディレクトリを作成します。</param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            ファイルを作成してデータ ADLS でそのファイルを書き込むストリームを返す非同期 API です。 排他アクセスでファイルを開く - を開くには、同じファイルで追加しようとするとは、このストリームが開いている間は失敗します。 
            
            スレッド処理: 返されたストリームはスレッド セーフであります。
            </summary>
        <returns>出力ストリーム</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public virtual bool Delete (string path, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Delete(string path, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.Delete(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function Delete (path As String, Optional cancelToken As CancellationToken = null) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Delete : string * System.Threading.CancellationToken -&gt; bool&#xA;override this.Delete : string * System.Threading.CancellationToken -&gt; bool" Usage="adlsClient.Delete (path, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
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
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            ファイルまたはディレクトリを削除する api を同期します。 ディレクトリが空の場合のみ削除されます。
            </summary>
        <returns>パスが削除された場合は true 正しく else false。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; DeleteAsync (string path, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteAsync(string path, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.DeleteAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function DeleteAsync (path As String, Optional cancelToken As CancellationToken = null) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.DeleteAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="adlsClient.DeleteAsync (path, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.AdlsClient/&lt;DeleteAsync&gt;d__45))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">ファイルまたはディレクトリのパス</param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            ファイルまたはディレクトリを削除する非同期 api です。 ディレクトリが空の場合のみ削除されます。
            </summary>
        <returns>パスが削除された場合は true 正しく else false。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteRecursive">
      <MemberSignature Language="C#" Value="public virtual bool DeleteRecursive (string path, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool DeleteRecursive(string path, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.DeleteRecursive(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function DeleteRecursive (path As String, Optional cancelToken As CancellationToken = null) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member DeleteRecursive : string * System.Threading.CancellationToken -&gt; bool&#xA;override this.DeleteRecursive : string * System.Threading.CancellationToken -&gt; bool" Usage="adlsClient.DeleteRecursive (path, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
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
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            ファイルまたはディレクトリの再帰的に削除する api を同期します。 空でないディレクトリである場合、削除、サブディレクトリまたはファイル。
            </summary>
        <returns>パスが削除された場合は true 正しく else false。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteRecursiveAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; DeleteRecursiveAsync (string path, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteRecursiveAsync(string path, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.DeleteRecursiveAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function DeleteRecursiveAsync (path As String, Optional cancelToken As CancellationToken = null) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member DeleteRecursiveAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.DeleteRecursiveAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="adlsClient.DeleteRecursiveAsync (path, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.AdlsClient/&lt;DeleteRecursiveAsync&gt;d__47))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">ファイルまたはディレクトリのパス</param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            ファイルまたはディレクトリの再帰的に削除する非同期 api
            </summary>
        <returns>パスが削除された場合は true 正しく else false。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnumerateDirectory">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.DataLake.Store.DirectoryEntry&gt; EnumerateDirectory (string path, Microsoft.Azure.DataLake.Store.UserGroupRepresentation userIdFormat = Microsoft.Azure.DataLake.Store.UserGroupRepresentation.ObjectID, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.DataLake.Store.DirectoryEntry&gt; EnumerateDirectory(string path, valuetype Microsoft.Azure.DataLake.Store.UserGroupRepresentation userIdFormat, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.EnumerateDirectory(System.String,Microsoft.Azure.DataLake.Store.UserGroupRepresentation,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EnumerateDirectory (path As String, Optional userIdFormat As UserGroupRepresentation = Microsoft.Azure.DataLake.Store.UserGroupRepresentation.ObjectID, Optional cancelToken As CancellationToken = null) As IEnumerable(Of DirectoryEntry)" />
      <MemberSignature Language="F#" Value="abstract member EnumerateDirectory : string * Microsoft.Azure.DataLake.Store.UserGroupRepresentation * System.Threading.CancellationToken -&gt; seq&lt;Microsoft.Azure.DataLake.Store.DirectoryEntry&gt;&#xA;override this.EnumerateDirectory : string * Microsoft.Azure.DataLake.Store.UserGroupRepresentation * System.Threading.CancellationToken -&gt; seq&lt;Microsoft.Azure.DataLake.Store.DirectoryEntry&gt;" Usage="adlsClient.EnumerateDirectory (path, userIdFormat, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
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
        <param name="path">ディレクトリのパス</param>
        <param name="userIdFormat">ユーザーまたはグループのオブジェクトの表現方法</param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            サブディレクトリまたはディレクトリに含まれているファイルを列挙する列挙可能な値を返します。
            既定 listAfter と listBefore は空と enuerate すべてのディレクトリ エントリです。
            </summary>
        <returns>内容を列挙する列挙可能です</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAclStatus">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.DataLake.Store.Acl.AclStatus GetAclStatus (string path, Microsoft.Azure.DataLake.Store.UserGroupRepresentation userIdFormat = Microsoft.Azure.DataLake.Store.UserGroupRepresentation.ObjectID, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.DataLake.Store.Acl.AclStatus GetAclStatus(string path, valuetype Microsoft.Azure.DataLake.Store.UserGroupRepresentation userIdFormat, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.GetAclStatus(System.String,Microsoft.Azure.DataLake.Store.UserGroupRepresentation,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetAclStatus (path As String, Optional userIdFormat As UserGroupRepresentation = Microsoft.Azure.DataLake.Store.UserGroupRepresentation.ObjectID, Optional cancelToken As CancellationToken = null) As AclStatus" />
      <MemberSignature Language="F#" Value="abstract member GetAclStatus : string * Microsoft.Azure.DataLake.Store.UserGroupRepresentation * System.Threading.CancellationToken -&gt; Microsoft.Azure.DataLake.Store.Acl.AclStatus&#xA;override this.GetAclStatus : string * Microsoft.Azure.DataLake.Store.UserGroupRepresentation * System.Threading.CancellationToken -&gt; Microsoft.Azure.DataLake.Store.Acl.AclStatus" Usage="adlsClient.GetAclStatus (path, userIdFormat, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
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
    <Member MemberName="GetAclStatusAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.DataLake.Store.Acl.AclStatus&gt; GetAclStatusAsync (string path, Microsoft.Azure.DataLake.Store.UserGroupRepresentation userIdFormat = Microsoft.Azure.DataLake.Store.UserGroupRepresentation.ObjectID, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.DataLake.Store.Acl.AclStatus&gt; GetAclStatusAsync(string path, valuetype Microsoft.Azure.DataLake.Store.UserGroupRepresentation userIdFormat, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.GetAclStatusAsync(System.String,Microsoft.Azure.DataLake.Store.UserGroupRepresentation,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetAclStatusAsync (path As String, Optional userIdFormat As UserGroupRepresentation = Microsoft.Azure.DataLake.Store.UserGroupRepresentation.ObjectID, Optional cancelToken As CancellationToken = null) As Task(Of AclStatus)" />
      <MemberSignature Language="F#" Value="abstract member GetAclStatusAsync : string * Microsoft.Azure.DataLake.Store.UserGroupRepresentation * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.DataLake.Store.Acl.AclStatus&gt;&#xA;override this.GetAclStatusAsync : string * Microsoft.Azure.DataLake.Store.UserGroupRepresentation * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.DataLake.Store.Acl.AclStatus&gt;" Usage="adlsClient.GetAclStatusAsync (path, userIdFormat, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.AdlsClient/&lt;GetAclStatusAsync&gt;d__75))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.DataLake.Store.Acl.AclStatus&gt;</ReturnType>
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
            ACL エントリの一覧、所有者 ID、グループ ID、8 進数のアクセス許可およびファイルまたはディレクトリの (ディレクトリ) の場合のみ sticky ビットを非同期に取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAppendStream">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.DataLake.Store.AdlsOutputStream GetAppendStream (string filename, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.DataLake.Store.AdlsOutputStream GetAppendStream(string filename, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.GetAppendStream(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetAppendStream (filename As String, Optional cancelToken As CancellationToken = null) As AdlsOutputStream" />
      <MemberSignature Language="F#" Value="abstract member GetAppendStream : string * System.Threading.CancellationToken -&gt; Microsoft.Azure.DataLake.Store.AdlsOutputStream&#xA;override this.GetAppendStream : string * System.Threading.CancellationToken -&gt; Microsoft.Azure.DataLake.Store.AdlsOutputStream" Usage="adlsClient.GetAppendStream (filename, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
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
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            ADLS 内のファイルにデータを書き込むストリームを返す同期 API です。 排他アクセスでファイルを開く - を開くには、同じファイルで追加しようとするとは、このストリームが開いている間は失敗します。  
            
            スレッド処理: 返されたストリームはスレッド セーフであります。
            </summary>
        <returns>出力ストリーム</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAppendStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.DataLake.Store.AdlsOutputStream&gt; GetAppendStreamAsync (string filename, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.DataLake.Store.AdlsOutputStream&gt; GetAppendStreamAsync(string filename, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.GetAppendStreamAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetAppendStreamAsync (filename As String, Optional cancelToken As CancellationToken = null) As Task(Of AdlsOutputStream)" />
      <MemberSignature Language="F#" Value="abstract member GetAppendStreamAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.DataLake.Store.AdlsOutputStream&gt;&#xA;override this.GetAppendStreamAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.DataLake.Store.AdlsOutputStream&gt;" Usage="adlsClient.GetAppendStreamAsync (filename, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.AdlsClient/&lt;GetAppendStreamAsync&gt;d__41))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.DataLake.Store.AdlsOutputStream&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filename" Type="System.String" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="filename">ファイル名</param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            ADLS 内のファイルにデータを書き込むストリームを返す非同期 API です。 排他アクセスでファイルを開く - を開くには、同じファイルで追加しようとするとは、このストリームが開いている間は失敗します。 
            
            スレッド処理: 返されたストリームはスレッド セーフであります。
            </summary>
        <returns>出力ストリーム</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetContentSummary">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.DataLake.Store.ContentSummary GetContentSummary (string path, int numThreads = -1, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.DataLake.Store.ContentSummary GetContentSummary(string path, int32 numThreads, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.GetContentSummary(System.String,System.Int32,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetContentSummary (path As String, Optional numThreads As Integer = -1, Optional cancelToken As CancellationToken = null) As ContentSummary" />
      <MemberSignature Language="F#" Value="abstract member GetContentSummary : string * int * System.Threading.CancellationToken -&gt; Microsoft.Azure.DataLake.Store.ContentSummary&#xA;override this.GetContentSummary : string * int * System.Threading.CancellationToken -&gt; Microsoft.Azure.DataLake.Store.ContentSummary" Usage="adlsClient.GetContentSummary (path, numThreads, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.DataLake.Store.ContentSummary</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="numThreads" Type="System.Int32" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">ディレクトリまたはファイルのパス</param>
        <param name="numThreads">スレッドの数</param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            ファイルまたはディレクトリのコンテンツの概要を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDirectoryEntry">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.DataLake.Store.DirectoryEntry GetDirectoryEntry (string path, Microsoft.Azure.DataLake.Store.UserGroupRepresentation userIdFormat = Microsoft.Azure.DataLake.Store.UserGroupRepresentation.ObjectID, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.DataLake.Store.DirectoryEntry GetDirectoryEntry(string path, valuetype Microsoft.Azure.DataLake.Store.UserGroupRepresentation userIdFormat, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.GetDirectoryEntry(System.String,Microsoft.Azure.DataLake.Store.UserGroupRepresentation,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetDirectoryEntry (path As String, Optional userIdFormat As UserGroupRepresentation = Microsoft.Azure.DataLake.Store.UserGroupRepresentation.ObjectID, Optional cancelToken As CancellationToken = null) As DirectoryEntry" />
      <MemberSignature Language="F#" Value="abstract member GetDirectoryEntry : string * Microsoft.Azure.DataLake.Store.UserGroupRepresentation * System.Threading.CancellationToken -&gt; Microsoft.Azure.DataLake.Store.DirectoryEntry&#xA;override this.GetDirectoryEntry : string * Microsoft.Azure.DataLake.Store.UserGroupRepresentation * System.Threading.CancellationToken -&gt; Microsoft.Azure.DataLake.Store.DirectoryEntry" Usage="adlsClient.GetDirectoryEntry (path, userIdFormat, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
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
        <param name="userIdFormat">ユーザーまたはグループのオブジェクトの表現方法</param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            メタ データなどの完全なパス、種類 (ファイルまたはディレクトリ)、グループ、ユーザー、アクセス許可、長さ、最終アクセス時刻、最終更新時刻、有効期限、acl ビット、レプリケーション係数を同期的に取得します。
            </summary>
        <returns>ファイルまたはディレクトリのメタデータを返します</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDirectoryEntryAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.DataLake.Store.DirectoryEntry&gt; GetDirectoryEntryAsync (string path, Microsoft.Azure.DataLake.Store.UserGroupRepresentation uid = Microsoft.Azure.DataLake.Store.UserGroupRepresentation.ObjectID, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.DataLake.Store.DirectoryEntry&gt; GetDirectoryEntryAsync(string path, valuetype Microsoft.Azure.DataLake.Store.UserGroupRepresentation uid, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.GetDirectoryEntryAsync(System.String,Microsoft.Azure.DataLake.Store.UserGroupRepresentation,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetDirectoryEntryAsync (path As String, Optional uid As UserGroupRepresentation = Microsoft.Azure.DataLake.Store.UserGroupRepresentation.ObjectID, Optional cancelToken As CancellationToken = null) As Task(Of DirectoryEntry)" />
      <MemberSignature Language="F#" Value="abstract member GetDirectoryEntryAsync : string * Microsoft.Azure.DataLake.Store.UserGroupRepresentation * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.DataLake.Store.DirectoryEntry&gt;&#xA;override this.GetDirectoryEntryAsync : string * Microsoft.Azure.DataLake.Store.UserGroupRepresentation * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.DataLake.Store.DirectoryEntry&gt;" Usage="adlsClient.GetDirectoryEntryAsync (path, uid, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.AdlsClient/&lt;GetDirectoryEntryAsync&gt;d__51))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.DataLake.Store.DirectoryEntry&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="uid" Type="Microsoft.Azure.DataLake.Store.UserGroupRepresentation" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">ファイルまたはディレクトリのパス</param>
        <param name="uid">ユーザーまたはグループのオブジェクトの表現方法</param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            メタ データなどの完全なパス、種類 (ファイルまたはディレクトリ)、グループ、ユーザー、アクセス許可、長さ、最終アクセス時刻、最終更新時刻、有効期限、acl ビット、レプリケーション係数を非同期に取得します。
            </summary>
        <returns>ファイルまたはディレクトリのメタデータを返します</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetExceptionFromResponse">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.DataLake.Store.AdlsException GetExceptionFromResponse (Microsoft.Azure.DataLake.Store.OperationResponse resp, string defaultMessage);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.DataLake.Store.AdlsException GetExceptionFromResponse(class Microsoft.Azure.DataLake.Store.OperationResponse resp, string defaultMessage) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.GetExceptionFromResponse(Microsoft.Azure.DataLake.Store.OperationResponse,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetExceptionFromResponse (resp As OperationResponse, defaultMessage As String) As AdlsException" />
      <MemberSignature Language="F#" Value="member this.GetExceptionFromResponse : Microsoft.Azure.DataLake.Store.OperationResponse * string -&gt; Microsoft.Azure.DataLake.Store.AdlsException" Usage="adlsClient.GetExceptionFromResponse (resp, defaultMessage)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.DataLake.Store.AdlsException</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="defaultMessage" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resp">応答のカプセル化するエラーまたは例外</param>
        <param name="defaultMessage">既定のメッセージ</param>
        <summary>
            サーバーからの応答に基づく ADLS 例外を返します
            </summary>
        <returns>Adls 例外</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFileProperties">
      <MemberSignature Language="C#" Value="public virtual void GetFileProperties (string path, bool getAclUsage, string dumpFileName, bool getDiskUsage = true, bool saveToLocal = true, int numThreads = -1, bool displayFiles = false, bool hideConsistentAcl = true, long maxDepth = 9223372036854775807);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void GetFileProperties(string path, bool getAclUsage, string dumpFileName, bool getDiskUsage, bool saveToLocal, int32 numThreads, bool displayFiles, bool hideConsistentAcl, int64 maxDepth) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.GetFileProperties(System.String,System.Boolean,System.String,System.Boolean,System.Boolean,System.Int32,System.Boolean,System.Boolean,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub GetFileProperties (path As String, getAclUsage As Boolean, dumpFileName As String, Optional getDiskUsage As Boolean = true, Optional saveToLocal As Boolean = true, Optional numThreads As Integer = -1, Optional displayFiles As Boolean = false, Optional hideConsistentAcl As Boolean = true, Optional maxDepth As Long = 9223372036854775807)" />
      <MemberSignature Language="F#" Value="abstract member GetFileProperties : string * bool * string * bool * bool * int * bool * bool * int64 -&gt; unit&#xA;override this.GetFileProperties : string * bool * string * bool * bool * int * bool * bool * int64 -&gt; unit" Usage="adlsClient.GetFileProperties (path, getAclUsage, dumpFileName, getDiskUsage, saveToLocal, numThreads, displayFiles, hideConsistentAcl, maxDepth)" />
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
        <Parameter Name="getAclUsage" Type="System.Boolean" />
        <Parameter Name="dumpFileName" Type="System.String" />
        <Parameter Name="getDiskUsage" Type="System.Boolean" />
        <Parameter Name="saveToLocal" Type="System.Boolean" />
        <Parameter Name="numThreads" Type="System.Int32" />
        <Parameter Name="displayFiles" Type="System.Boolean" />
        <Parameter Name="displayConsistentAcl" Type="System.Boolean" />
        <Parameter Name="maxDepth" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="path">ファイルまたはディレクトリのパス</param>
        <param name="getAclUsage">Acl の使用状況したい場合は true。</param>
        <param name="dumpFileName">ACL またはディスクの使用状況のダンプを含むファイル名</param>
        <param name="getDiskUsage">ディスク使用量したい場合は true。</param>
        <param name="saveToLocal">保存が他にも含むローカル ファイルに保存する場合は true。</param>
        <param name="numThreads">スレッドの数</param>
        <param name="displayFiles">ファイルのプロパティを表示したい場合は true。 おを既定では、ディレクトリのプロパティを表示します。</param>
        <param name="hideConsistentAcl">場合は true を指定し、触れませんダンプ ディレクトリまたはファイルの acl のプロパティがある場合、親ディレクトリは、すべての子孫の同一の acl を持っています。 Ex: (「/」) のルートに同じ Acl がある場合は、すべてのルートのみの Acl を紹介し、それはの子孫、します。 このフラグが false の場合、おを表示するすべてのディレクトリまたはファイルの Acl</param>
        <param name="maxDepth">最大の深さがこれまでプロパティを表示します。</param>
        <summary>
            再帰的にダンプ alldirectories のファイルのプロパティまたは/と指定されたファイルのパスをローカルまたは含むファイルです。 ファイルのプロパティには、ディスク使用量または Acl またはその両方を指定できます。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetReadStream">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.DataLake.Store.AdlsInputStream GetReadStream (string filename, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.DataLake.Store.AdlsInputStream GetReadStream(string filename, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.GetReadStream(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetReadStream (filename As String, Optional cancelToken As CancellationToken = null) As AdlsInputStream" />
      <MemberSignature Language="F#" Value="abstract member GetReadStream : string * System.Threading.CancellationToken -&gt; Microsoft.Azure.DataLake.Store.AdlsInputStream&#xA;override this.GetReadStream : string * System.Threading.CancellationToken -&gt; Microsoft.Azure.DataLake.Store.AdlsInputStream" Usage="adlsClient.GetReadStream (filename, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
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
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            ADLS 内のファイルからデータを読み取るストリームを返す同期 API
            </summary>
        <returns>入力ストリーム</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetReadStream">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.DataLake.Store.AdlsInputStream GetReadStream (string filename, int bufferCapacity, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.DataLake.Store.AdlsInputStream GetReadStream(string filename, int32 bufferCapacity, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.GetReadStream(System.String,System.Int32,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetReadStream (filename As String, bufferCapacity As Integer, Optional cancelToken As CancellationToken = null) As AdlsInputStream" />
      <MemberSignature Language="F#" Value="abstract member GetReadStream : string * int * System.Threading.CancellationToken -&gt; Microsoft.Azure.DataLake.Store.AdlsInputStream&#xA;override this.GetReadStream : string * int * System.Threading.CancellationToken -&gt; Microsoft.Azure.DataLake.Store.AdlsInputStream" Usage="adlsClient.GetReadStream (filename, bufferCapacity, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.DataLake.Store.AdlsInputStream</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filename" Type="System.String" />
        <Parameter Name="bufferCapacity" Type="System.Int32" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="filename">ファイル名</param>
        <param name="bufferCapacity"> バッファーの容量</param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            ADLS 内のファイルからデータを読み取るストリームを返す同期 API
            </summary>
        <returns>入力ストリーム</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetReadStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.DataLake.Store.AdlsInputStream&gt; GetReadStreamAsync (string filename, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.DataLake.Store.AdlsInputStream&gt; GetReadStreamAsync(string filename, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.GetReadStreamAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetReadStreamAsync (filename As String, Optional cancelToken As CancellationToken = null) As Task(Of AdlsInputStream)" />
      <MemberSignature Language="F#" Value="abstract member GetReadStreamAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.DataLake.Store.AdlsInputStream&gt;&#xA;override this.GetReadStreamAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.DataLake.Store.AdlsInputStream&gt;" Usage="adlsClient.GetReadStreamAsync (filename, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.AdlsClient/&lt;GetReadStreamAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.DataLake.Store.AdlsInputStream&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filename" Type="System.String" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="filename">ファイル名</param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            ADLS 内のファイルからデータを読み取るストリームを返す非同期 API
            </summary>
        <returns>入力ストリーム</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetReadStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.DataLake.Store.AdlsInputStream&gt; GetReadStreamAsync (string filename, int bufferCapacity, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.DataLake.Store.AdlsInputStream&gt; GetReadStreamAsync(string filename, int32 bufferCapacity, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.GetReadStreamAsync(System.String,System.Int32,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetReadStreamAsync (filename As String, bufferCapacity As Integer, Optional cancelToken As CancellationToken = null) As Task(Of AdlsInputStream)" />
      <MemberSignature Language="F#" Value="abstract member GetReadStreamAsync : string * int * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.DataLake.Store.AdlsInputStream&gt;&#xA;override this.GetReadStreamAsync : string * int * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.DataLake.Store.AdlsInputStream&gt;" Usage="adlsClient.GetReadStreamAsync (filename, bufferCapacity, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.AdlsClient/&lt;GetReadStreamAsync&gt;d__39))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.DataLake.Store.AdlsInputStream&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filename" Type="System.String" />
        <Parameter Name="bufferCapacity" Type="System.Int32" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="filename">ファイル名</param>
        <param name="bufferCapacity"> バッファーの容量</param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            ADLS 内のファイルからデータを読み取るストリームを返す非同期 API
            </summary>
        <returns>入力ストリーム</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ModifyAclEntries">
      <MemberSignature Language="C#" Value="public virtual void ModifyAclEntries (string path, System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; aclSpec, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ModifyAclEntries(string path, class System.Collections.Generic.List`1&lt;class Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; aclSpec, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.ModifyAclEntries(System.String,System.Collections.Generic.List{Microsoft.Azure.DataLake.Store.Acl.AclEntry},System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub ModifyAclEntries (path As String, aclSpec As List(Of AclEntry), Optional cancelToken As CancellationToken = null)" />
      <MemberSignature Language="F#" Value="abstract member ModifyAclEntries : string * System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; * System.Threading.CancellationToken -&gt; unit&#xA;override this.ModifyAclEntries : string * System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; * System.Threading.CancellationToken -&gt; unit" Usage="adlsClient.ModifyAclEntries (path, aclSpec, cancelToken)" />
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
        <Parameter Name="aclSpec" Type="System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt;" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">ファイルまたはディレクトリのパス</param>
        <param name="aclSpec">変更する Acl エントリの一覧</param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            ファイルの acl エントリを変更またはディレクトリが指定した ACL リスト。 既存の ACL を結合で指定したリスト ボックスの一覧です。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ModifyAclEntriesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task ModifyAclEntriesAsync (string path, System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; aclSpec, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ModifyAclEntriesAsync(string path, class System.Collections.Generic.List`1&lt;class Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; aclSpec, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.ModifyAclEntriesAsync(System.String,System.Collections.Generic.List{Microsoft.Azure.DataLake.Store.Acl.AclEntry},System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ModifyAclEntriesAsync (path As String, aclSpec As List(Of AclEntry), Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member ModifyAclEntriesAsync : string * System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.ModifyAclEntriesAsync : string * System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="adlsClient.ModifyAclEntriesAsync (path, aclSpec, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.AdlsClient/&lt;ModifyAclEntriesAsync&gt;d__63))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclSpec" Type="System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt;" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">ファイルまたはディレクトリのパス</param>
        <param name="aclSpec">変更する Acl エントリの一覧</param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            非同期的にファイルの acl エントリを変更またはディレクトリが指定した ACL リスト。 既存の ACL を結合で指定したリスト ボックスの一覧です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAclEntries">
      <MemberSignature Language="C#" Value="public virtual void RemoveAclEntries (string path, System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; aclSpec, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RemoveAclEntries(string path, class System.Collections.Generic.List`1&lt;class Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; aclSpec, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.RemoveAclEntries(System.String,System.Collections.Generic.List{Microsoft.Azure.DataLake.Store.Acl.AclEntry},System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub RemoveAclEntries (path As String, aclSpec As List(Of AclEntry), Optional cancelToken As CancellationToken = null)" />
      <MemberSignature Language="F#" Value="abstract member RemoveAclEntries : string * System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; * System.Threading.CancellationToken -&gt; unit&#xA;override this.RemoveAclEntries : string * System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; * System.Threading.CancellationToken -&gt; unit" Usage="adlsClient.RemoveAclEntries (path, aclSpec, cancelToken)" />
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
        <Parameter Name="aclSpec" Type="System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt;" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">ファイルまたはディレクトリのパス</param>
        <param name="aclSpec">削除する Acl エントリの一覧</param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            削除は、ファイルまたはディレクトリの Acl エントリを指定します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAclEntriesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task RemoveAclEntriesAsync (string path, System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; aclSpec, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveAclEntriesAsync(string path, class System.Collections.Generic.List`1&lt;class Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; aclSpec, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.RemoveAclEntriesAsync(System.String,System.Collections.Generic.List{Microsoft.Azure.DataLake.Store.Acl.AclEntry},System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function RemoveAclEntriesAsync (path As String, aclSpec As List(Of AclEntry), Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member RemoveAclEntriesAsync : string * System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.RemoveAclEntriesAsync : string * System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="adlsClient.RemoveAclEntriesAsync (path, aclSpec, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.AdlsClient/&lt;RemoveAclEntriesAsync&gt;d__69))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
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
            非同期的にファイルまたはディレクトリの指定の Acl エントリを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAllAcls">
      <MemberSignature Language="C#" Value="public virtual void RemoveAllAcls (string path, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RemoveAllAcls(string path, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.RemoveAllAcls(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub RemoveAllAcls (path As String, Optional cancelToken As CancellationToken = null)" />
      <MemberSignature Language="F#" Value="abstract member RemoveAllAcls : string * System.Threading.CancellationToken -&gt; unit&#xA;override this.RemoveAllAcls : string * System.Threading.CancellationToken -&gt; unit" Usage="adlsClient.RemoveAllAcls (path, cancelToken)" />
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
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">ファイルまたはディレクトリのパス</param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            ファイルまたはディレクトリのすべての Acl エントリを削除します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAllAclsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task RemoveAllAclsAsync (string path, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveAllAclsAsync(string path, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.RemoveAllAclsAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function RemoveAllAclsAsync (path As String, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member RemoveAllAclsAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.RemoveAllAclsAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="adlsClient.RemoveAllAclsAsync (path, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.AdlsClient/&lt;RemoveAllAclsAsync&gt;d__71))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">ファイルまたはディレクトリのパス</param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            非同期的にファイルまたはディレクトリのすべての Acl エントリを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveDefaultAcls">
      <MemberSignature Language="C#" Value="public virtual void RemoveDefaultAcls (string path, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RemoveDefaultAcls(string path, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.RemoveDefaultAcls(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub RemoveDefaultAcls (path As String, Optional cancelToken As CancellationToken = null)" />
      <MemberSignature Language="F#" Value="abstract member RemoveDefaultAcls : string * System.Threading.CancellationToken -&gt; unit&#xA;override this.RemoveDefaultAcls : string * System.Threading.CancellationToken -&gt; unit" Usage="adlsClient.RemoveDefaultAcls (path, cancelToken)" />
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
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">ファイルまたはディレクトリのパス</param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            ファイルまたはディレクトリのすべての Acl エントリの AclScope デフォルトを削除します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveDefaultAclsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task RemoveDefaultAclsAsync (string path, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveDefaultAclsAsync(string path, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.RemoveDefaultAclsAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function RemoveDefaultAclsAsync (path As String, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member RemoveDefaultAclsAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.RemoveDefaultAclsAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="adlsClient.RemoveDefaultAclsAsync (path, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.AdlsClient/&lt;RemoveDefaultAclsAsync&gt;d__73))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">ファイルまたはディレクトリのパス</param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            非同期的にファイルまたはディレクトリのすべての Acl エントリの AclScope デフォルトを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Rename">
      <MemberSignature Language="C#" Value="public virtual bool Rename (string path, string destination, bool overwrite = false, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Rename(string path, string destination, bool overwrite, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.Rename(System.String,System.String,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function Rename (path As String, destination As String, Optional overwrite As Boolean = false, Optional cancelToken As CancellationToken = null) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Rename : string * string * bool * System.Threading.CancellationToken -&gt; bool&#xA;override this.Rename : string * string * bool * System.Threading.CancellationToken -&gt; bool" Usage="adlsClient.Rename (path, destination, overwrite, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
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
        <param name="path">ソース ファイルまたはディレクトリのパス</param>
        <param name="destination">移行先パス</param>
        <param name="overwrite">ファイル: true は、ディレクトリに存在する場合、変換先にファイルを上書きする場合: 先ディレクトリが存在するかどうかは、このフラグの使用はありません。 移行先の下にあるソースの 1 つのレベルを格納します。
                                    このフラグを使用して、失敗の名前を変更がない場合は、移行先パスにある 1 つのレベルをソースと同じ名前を持つサブディレクトリがあります。  </param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            ファイルまたはディレクトリの名前を変更する同期 API です。
            ディレクトリの名前を変更する: 宛先の下にあるソース ディレクトリの 1 つのレベルを配置し、変換先が存在する場合。
            </summary>
        <returns>パスの名前を変更する場合は true 正しく else false。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RenameAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; RenameAsync (string path, string destination, bool overwrite = false, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; RenameAsync(string path, string destination, bool overwrite, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.RenameAsync(System.String,System.String,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function RenameAsync (path As String, destination As String, Optional overwrite As Boolean = false, Optional cancelToken As CancellationToken = null) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member RenameAsync : string * string * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.RenameAsync : string * string * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="adlsClient.RenameAsync (path, destination, overwrite, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.AdlsClient/&lt;RenameAsync&gt;d__49))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="destination" Type="System.String" />
        <Parameter Name="overwrite" Type="System.Boolean" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">ソース ファイルまたはディレクトリのパス</param>
        <param name="destination">移行先パスです。 ディレクトリの: 宛先の下にあるソース ディレクトリの 1 つのレベルを配置し、変換先が存在する場合。 %T が、移行先パスにある 1 つのレベルをソースと同じ名前を持つサブディレクトリである場合は、名前の変更が失敗します。</param>
        <param name="overwrite">ファイル: 場合は true は、存在する場合、変換先ファイルを上書きします。 フォルダーの名前を変更すると、ターゲットの上書きが発生することはします。</param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            ファイルまたはディレクトリの名前を変更する非同期 API です。
            ディレクトリの名前を変更する: 宛先の下にあるソース ディレクトリの 1 つのレベルを配置し、変換先が存在する場合。
            </summary>
        <returns>パスの名前を変更する場合は true 正しく else false。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetAcl">
      <MemberSignature Language="C#" Value="public virtual void SetAcl (string path, System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; aclSpec, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SetAcl(string path, class System.Collections.Generic.List`1&lt;class Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; aclSpec, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.SetAcl(System.String,System.Collections.Generic.List{Microsoft.Azure.DataLake.Store.Acl.AclEntry},System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub SetAcl (path As String, aclSpec As List(Of AclEntry), Optional cancelToken As CancellationToken = null)" />
      <MemberSignature Language="F#" Value="abstract member SetAcl : string * System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; * System.Threading.CancellationToken -&gt; unit&#xA;override this.SetAcl : string * System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; * System.Threading.CancellationToken -&gt; unit" Usage="adlsClient.SetAcl (path, aclSpec, cancelToken)" />
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
        <Parameter Name="aclSpec" Type="System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt;" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">ファイルまたはディレクトリのパス</param>
        <param name="aclSpec">設定する Acl エントリの一覧 </param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            ファイルまたはディレクトリの Acl エントリを設定します。 パスの既存の Acl エントリのデータをワイプします。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetAclAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetAclAsync (string path, System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; aclSpec, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetAclAsync(string path, class System.Collections.Generic.List`1&lt;class Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; aclSpec, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.SetAclAsync(System.String,System.Collections.Generic.List{Microsoft.Azure.DataLake.Store.Acl.AclEntry},System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function SetAclAsync (path As String, aclSpec As List(Of AclEntry), Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member SetAclAsync : string * System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetAclAsync : string * System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="adlsClient.SetAclAsync (path, aclSpec, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.AdlsClient/&lt;SetAclAsync&gt;d__65))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclSpec" Type="System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt;" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">ファイルまたはディレクトリのパス</param>
        <param name="aclSpec">設定する Acl エントリの一覧 </param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            ファイルまたはディレクトリの Acl エントリを非同期に設定します。 パスの既存の Acl エントリのデータをワイプします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetExpiryTime">
      <MemberSignature Language="C#" Value="public virtual void SetExpiryTime (string path, Microsoft.Azure.DataLake.Store.ExpiryOption eopt, long expiryTime, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SetExpiryTime(string path, valuetype Microsoft.Azure.DataLake.Store.ExpiryOption eopt, int64 expiryTime, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.SetExpiryTime(System.String,Microsoft.Azure.DataLake.Store.ExpiryOption,System.Int64,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub SetExpiryTime (path As String, eopt As ExpiryOption, expiryTime As Long, Optional cancelToken As CancellationToken = null)" />
      <MemberSignature Language="F#" Value="abstract member SetExpiryTime : string * Microsoft.Azure.DataLake.Store.ExpiryOption * int64 * System.Threading.CancellationToken -&gt; unit&#xA;override this.SetExpiryTime : string * Microsoft.Azure.DataLake.Store.ExpiryOption * int64 * System.Threading.CancellationToken -&gt; unit" Usage="adlsClient.SetExpiryTime (path, eopt, expiryTime, cancelToken)" />
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
        <Parameter Name="eopt" Type="Microsoft.Azure.DataLake.Store.ExpiryOption" />
        <Parameter Name="expiryTime" Type="System.Int64" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">ファイルのパス</param>
        <param name="eopt">例については有効期限のメソッドの別の型: 有効期限はありません、now、expiryTime を評価する方法を定義するなどの基準としました。</param>
        <param name="expiryTime">有効期限時刻の値 (ミリ秒単位)。 解釈はどのような ExpiryOption を置いた依存します。</param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            同期的に期限を設定します
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetExpiryTimeAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetExpiryTimeAsync (string path, Microsoft.Azure.DataLake.Store.ExpiryOption eopt, long expiryTime, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetExpiryTimeAsync(string path, valuetype Microsoft.Azure.DataLake.Store.ExpiryOption eopt, int64 expiryTime, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.SetExpiryTimeAsync(System.String,Microsoft.Azure.DataLake.Store.ExpiryOption,System.Int64,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function SetExpiryTimeAsync (path As String, eopt As ExpiryOption, expiryTime As Long, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member SetExpiryTimeAsync : string * Microsoft.Azure.DataLake.Store.ExpiryOption * int64 * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetExpiryTimeAsync : string * Microsoft.Azure.DataLake.Store.ExpiryOption * int64 * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="adlsClient.SetExpiryTimeAsync (path, eopt, expiryTime, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.AdlsClient/&lt;SetExpiryTimeAsync&gt;d__57))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="eopt" Type="Microsoft.Azure.DataLake.Store.ExpiryOption" />
        <Parameter Name="expiryTime" Type="System.Int64" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">ファイルのパス</param>
        <param name="eopt">例については有効期限のメソッドの別の型: 有効期限はありません、now、expiryTime を評価する方法を定義するなどの基準としました。</param>
        <param name="expiryTime">有効期限の時刻値。 解釈はどのような ExpiryOption を置いた依存します。</param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            非同期的に期限を設定します
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetOwner">
      <MemberSignature Language="C#" Value="public virtual void SetOwner (string path, string owner, string group, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SetOwner(string path, string owner, string group, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.SetOwner(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub SetOwner (path As String, owner As String, group As String, Optional cancelToken As CancellationToken = null)" />
      <MemberSignature Language="F#" Value="abstract member SetOwner : string * string * string * System.Threading.CancellationToken -&gt; unit&#xA;override this.SetOwner : string * string * string * System.Threading.CancellationToken -&gt; unit" Usage="adlsClient.SetOwner (path, owner, group, cancelToken)" />
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
        <Parameter Name="owner" Type="System.String" />
        <Parameter Name="group" Type="System.String" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">ファイルまたはディレクトリのパス</param>
        <param name="owner">所有者の ID</param>
        <param name="group">グループ ID</param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            所有者を設定または/およびパスのグループ
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetOwnerAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetOwnerAsync (string path, string owner, string group, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetOwnerAsync(string path, string owner, string group, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.SetOwnerAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function SetOwnerAsync (path As String, owner As String, group As String, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member SetOwnerAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetOwnerAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="adlsClient.SetOwnerAsync (path, owner, group, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.AdlsClient/&lt;SetOwnerAsync&gt;d__68))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="owner" Type="System.String" />
        <Parameter Name="group" Type="System.String" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">ファイルまたはディレクトリのパス</param>
        <param name="owner">所有者の ID</param>
        <param name="group">グループ ID</param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            非同期的に所有者を設定または/およびパスのグループ
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPermission">
      <MemberSignature Language="C#" Value="public virtual void SetPermission (string path, string permission, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SetPermission(string path, string permission, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.SetPermission(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub SetPermission (path As String, permission As String, Optional cancelToken As CancellationToken = null)" />
      <MemberSignature Language="F#" Value="abstract member SetPermission : string * string * System.Threading.CancellationToken -&gt; unit&#xA;override this.SetPermission : string * string * System.Threading.CancellationToken -&gt; unit" Usage="adlsClient.SetPermission (path, permission, cancelToken)" />
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
        <Parameter Name="permission" Type="System.String" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">ファイルまたはディレクトリのパス</param>
        <param name="permission">Unix 8 進数形式のチェックインを許可します。 たとえば、ユーザーが所有者が読み取る場合に表示する場合、書き込みアクセス許可を実行するすべてのグループが書き込みアクセス許可を読み取り、文字列のアクセス許可を 741 となる他のユーザーに読み取り </param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            指定したパスのアクセス許可を設定します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPermissionAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetPermissionAsync (string path, string permission, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetPermissionAsync(string path, string permission, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.SetPermissionAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function SetPermissionAsync (path As String, permission As String, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member SetPermissionAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetPermissionAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="adlsClient.SetPermissionAsync (path, permission, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.AdlsClient/&lt;SetPermissionAsync&gt;d__61))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="permission" Type="System.String" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">ファイルまたはディレクトリのパス</param>
        <param name="permission">Unix 8 進数形式のチェックインを許可します。 たとえば、ユーザーが所有者が読み取る場合に表示する場合、書き込みアクセス許可を実行するすべてのグループが書き込みアクセス許可を読み取り、文字列のアクセス許可を 741 となる他のユーザーに読み取り </param>
        <param name="cancelToken">CancellationToken 要求を取り消します</param>
        <summary>
            指定したパスのアクセス許可を非同期に設定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetToken">
      <MemberSignature Language="C#" Value="public void SetToken (string accessToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void SetToken(string accessToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsClient.SetToken(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub SetToken (accessToken As String)" />
      <MemberSignature Language="F#" Value="member this.SetToken : string -&gt; unit" Usage="adlsClient.SetToken accessToken" />
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
        <Parameter Name="accessToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="accessToken">アクセス トークン</param>
        <summary>
            認証トークンを設定します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>