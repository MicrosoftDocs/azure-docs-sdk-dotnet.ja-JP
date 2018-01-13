<Type Name="FileSystemOperationsExtensions" FullName="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class FileSystemOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit FileSystemOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module FileSystemOperationsExtensions" />
  <TypeSignature Language="F#" Value="type FileSystemOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            FileSystemOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Append">
      <MemberSignature Language="C#" Value="public static void Append (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, System.IO.Stream streamContents, Nullable&lt;long&gt; offset = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag = null, Nullable&lt;Guid&gt; leaseId = null, Nullable&lt;Guid&gt; fileSessionId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Append(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, class System.IO.Stream streamContents, valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; leaseId, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; fileSessionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.Append(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.IO.Stream,System.Nullable{System.Int64},System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag},System.Nullable{System.Guid},System.Nullable{System.Guid})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Append (operations As IFileSystemOperations, accountName As String, path As String, streamContents As Stream, Optional offset As Nullable(Of Long) = null, Optional syncFlag As Nullable(Of SyncFlag) = null, Optional leaseId As Nullable(Of Guid) = null, Optional fileSessionId As Nullable(Of Guid) = null)" />
      <MemberSignature Language="F#" Value="static member Append : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * System.IO.Stream * Nullable&lt;int64&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; * Nullable&lt;Guid&gt; * Nullable&lt;Guid&gt; -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.Append (operations, accountName, path, streamContents, offset, syncFlag, leaseId, fileSessionId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="streamContents" Type="System.IO.Stream" />
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="syncFlag" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt;" />
        <Parameter Name="leaseId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="fileSessionId" Type="System.Nullable&lt;System.Guid&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') を追加するファイルのです。
            </param>
        <param name="streamContents">
            ファイルに追加するときに含めるファイルの内容。
            </param>
        <param name="offset">
            追加操作を開始するためのストリームの省略可能なオフセット。 既定では、ストリームの末尾に追加します。
            </param>
        <param name="syncFlag">
            必要に応じて、同時実行の追加が完了した後の対処方法を示します。
            データことを示しますより多くのデータは、クライアントですぐに送信される、ファイル ハンドルの開く/ロックされているままにする (を含むファイルの長さ、最終更新時刻) ファイルのメタデータは更新されません。 メタデータことを示しますより多くのデータは、クライアントですぐに送信される、ファイル ハンドルのままにするオープン/ロックされているファイルのメタデータが更新を取得する必要があります。 閉じることを示します、クライアントにデータの送信が行われますが、ファイル ハンドルが閉じられた/ロック解除、する必要がありますファイル メタデータが更新を取得する必要があります。 使用可能な値が含まれます: 'データ'、'METADATA'、'終了'
            </param>
        <param name="leaseId">
            省略可能な一意の GUID ファイルごとに単一ライター セマンティクスは、そのためには同じ leaseId でファイルを追加するクライアントだけが許可されることを意味することを確認します。
            </param>
        <param name="fileSessionId">
            1 ファイルすべてを示す省略可能な一意の GUID、同じ追加 fileSessionId は、同じクライアントと同じセッションからです。 SyncFlag がデータまたはメタデータの場合、パフォーマンスが向上が得られます。
            </param>
        <summary>
            使用のシリアルを指定したファイルに追加します。 注: ターゲットは ConcurrentAppend によって追加されたデータを含めないでください。 ConcurrentAppend と追加を同義です。 使用することはできません。ターゲット ファイルが変更されたこれらのいずれかを使用して追加のオプションと、ターゲット ファイルで、その他の追加オプションは使用できません。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppendAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task AppendAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, System.IO.Stream streamContents, Nullable&lt;long&gt; offset = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag = null, Nullable&lt;Guid&gt; leaseId = null, Nullable&lt;Guid&gt; fileSessionId = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task AppendAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, class System.IO.Stream streamContents, valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; leaseId, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; fileSessionId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.AppendAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.IO.Stream,System.Nullable{System.Int64},System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag},System.Nullable{System.Guid},System.Nullable{System.Guid},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member AppendAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * System.IO.Stream * Nullable&lt;int64&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; * Nullable&lt;Guid&gt; * Nullable&lt;Guid&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.AppendAsync (operations, accountName, path, streamContents, offset, syncFlag, leaseId, fileSessionId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;AppendAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="streamContents" Type="System.IO.Stream" />
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="syncFlag" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt;" />
        <Parameter Name="leaseId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="fileSessionId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') を追加するファイルのです。
            </param>
        <param name="streamContents">
            ファイルに追加するときに含めるファイルの内容。
            </param>
        <param name="offset">
            追加操作を開始するためのストリームの省略可能なオフセット。 既定では、ストリームの末尾に追加します。
            </param>
        <param name="syncFlag">
            必要に応じて、同時実行の追加が完了した後の対処方法を示します。
            データことを示しますより多くのデータは、クライアントですぐに送信される、ファイル ハンドルの開く/ロックされているままにする (を含むファイルの長さ、最終更新時刻) ファイルのメタデータは更新されません。 メタデータことを示しますより多くのデータは、クライアントですぐに送信される、ファイル ハンドルのままにするオープン/ロックされているファイルのメタデータが更新を取得する必要があります。 閉じることを示します、クライアントにデータの送信が行われますが、ファイル ハンドルが閉じられた/ロック解除、する必要がありますファイル メタデータが更新を取得する必要があります。 使用可能な値が含まれます: 'データ'、'METADATA'、'終了'
            </param>
        <param name="leaseId">
            省略可能な一意の GUID ファイルごとに単一ライター セマンティクスは、そのためには同じ leaseId でファイルを追加するクライアントだけが許可されることを意味することを確認します。
            </param>
        <param name="fileSessionId">
            1 ファイルすべてを示す省略可能な一意の GUID、同じ追加 fileSessionId は、同じクライアントと同じセッションからです。 SyncFlag がデータまたはメタデータの場合、パフォーマンスが向上が得られます。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            使用のシリアルを指定したファイルに追加します。 注: ターゲットは ConcurrentAppend によって追加されたデータを含めないでください。 ConcurrentAppend と追加を同義です。 使用することはできません。ターゲット ファイルが変更されたこれらのいずれかを使用して追加のオプションと、ターゲット ファイルで、その他の追加オプションは使用できません。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckAccess">
      <MemberSignature Language="C#" Value="public static void CheckAccess (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string fsaction);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void CheckAccess(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string fsaction) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.CheckAccess(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub CheckAccess (operations As IFileSystemOperations, accountName As String, path As String, fsaction As String)" />
      <MemberSignature Language="F#" Value="static member CheckAccess : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.CheckAccess (operations, accountName, path, fsaction)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="fsaction" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') のファイルまたはディレクトリのアクセスをチェックします。
            </param>
        <param name="fsaction">
            正規表現パターンに一致する文字列形式でのシステム操作読み取り/書き込み/実行のファイル ' [rwx-] \ {3\}'
            </param>
        <summary>
            かどうか、指定のアクセスは、指定されたパスを確認します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckAccessAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CheckAccessAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string fsaction, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CheckAccessAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string fsaction, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.CheckAccessAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckAccessAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.CheckAccessAsync (operations, accountName, path, fsaction, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;CheckAccessAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="fsaction" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') のファイルまたはディレクトリのアクセスをチェックします。
            </param>
        <param name="fsaction">
            正規表現パターンに一致する文字列形式でのシステム操作読み取り/書き込み/実行のファイル ' [rwx-] \ {3\}'
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            かどうか、指定のアクセスは、指定されたパスを確認します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Concat">
      <MemberSignature Language="C#" Value="public static void Concat (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, System.Collections.Generic.IList&lt;string&gt; sources);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Concat(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, class System.Collections.Generic.IList`1&lt;string&gt; sources) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.Concat(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Concat (operations As IFileSystemOperations, accountName As String, path As String, sources As IList(Of String))" />
      <MemberSignature Language="F#" Value="static member Concat : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * System.Collections.Generic.IList&lt;string&gt; -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.Concat (operations, accountName, path, sources)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="sources" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') の連結の結果として得られる出力先ファイルです。
            </param>
        <param name="sources">
            一連のコンマ区切りの Data Lake Store パス (以降で '/') を連結する順序で連結するファイルのです。
            </param>
        <summary>
            出力先ファイル、成功時にすべてのソース ファイルを削除するのには、ソース ファイルのリストを連結します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConcatAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ConcatAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, System.Collections.Generic.IList&lt;string&gt; sources, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ConcatAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, class System.Collections.Generic.IList`1&lt;string&gt; sources, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.ConcatAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Collections.Generic.IList{System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ConcatAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * System.Collections.Generic.IList&lt;string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.ConcatAsync (operations, accountName, path, sources, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;ConcatAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="sources" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') の連結の結果として得られる出力先ファイルです。
            </param>
        <param name="sources">
            一連のコンマ区切りの Data Lake Store パス (以降で '/') を連結する順序で連結するファイルのです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            出力先ファイル、成功時にすべてのソース ファイルを削除するのには、ソース ファイルのリストを連結します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConcurrentAppend">
      <MemberSignature Language="C#" Value="public static void ConcurrentAppend (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, System.IO.Stream streamContents, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.AppendModeType&gt; appendMode = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ConcurrentAppend(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, class System.IO.Stream streamContents, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.AppendModeType&gt; appendMode, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.ConcurrentAppend(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.IO.Stream,System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.AppendModeType},System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub ConcurrentAppend (operations As IFileSystemOperations, accountName As String, path As String, streamContents As Stream, Optional appendMode As Nullable(Of AppendModeType) = null, Optional syncFlag As Nullable(Of SyncFlag) = null)" />
      <MemberSignature Language="F#" Value="static member ConcurrentAppend : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * System.IO.Stream * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.AppendModeType&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.ConcurrentAppend (operations, accountName, path, streamContents, appendMode, syncFlag)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="streamContents" Type="System.IO.Stream" />
        <Parameter Name="appendMode" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.AppendModeType&gt;" />
        <Parameter Name="syncFlag" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') の同時実行を使用して、追加する追加ファイルです。
            </param>
        <param name="streamContents">
            ファイルに追加するときに含めるファイルの内容。
            </param>
        <param name="appendMode">
            その存在または追加の既存のファイルを開くだけしていない場合、同時実行の追加の呼び出しはファイルを作成する必要がありますを示します。 使用可能な値が含まれます '自動 ' の作成。
            </param>
        <param name="syncFlag">
            必要に応じて、同時実行の追加が完了した後の対処方法を示します。
            データことを示しますより多くのデータは、クライアントですぐに送信される、ファイル ハンドルの開く/ロックされているままにする (を含むファイルの長さ、最終更新時刻) ファイルのメタデータは更新されません。 メタデータことを示しますより多くのデータは、クライアントですぐに送信される、ファイル ハンドルのままにするオープン/ロックされているファイルのメタデータが更新を取得する必要があります。 閉じることを示します、クライアントにデータの送信が行われますが、ファイル ハンドルが閉じられた/ロック解除、する必要がありますファイル メタデータが更新を取得する必要があります。 使用可能な値が含まれます: 'データ'、'METADATA'、'終了'
            </param>
        <summary>
            必要に応じて、指定されたファイルに追加されますがまだ存在しない場合、まずファイルを作成します。 このメソッドは、ファイルに複数の同時追加をサポートします。 注: ターゲットは作成または通常の (シリアル) Append によって追加されたデータを含めないでください。 ConcurrentAppend と追加を同義です。 使用することはできません。ターゲット ファイルが変更されたこれらのいずれかを使用して追加のオプションと、ターゲット ファイルで、その他の追加オプションは使用できません。
            ConcurrentAppend 順序は保証されませんし、ランディング ターゲット ファイルのデータの重複が発生することができます。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConcurrentAppendAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ConcurrentAppendAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, System.IO.Stream streamContents, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.AppendModeType&gt; appendMode = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ConcurrentAppendAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, class System.IO.Stream streamContents, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.AppendModeType&gt; appendMode, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.ConcurrentAppendAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.IO.Stream,System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.AppendModeType},System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ConcurrentAppendAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * System.IO.Stream * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.AppendModeType&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.ConcurrentAppendAsync (operations, accountName, path, streamContents, appendMode, syncFlag, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;ConcurrentAppendAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="streamContents" Type="System.IO.Stream" />
        <Parameter Name="appendMode" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.AppendModeType&gt;" />
        <Parameter Name="syncFlag" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') の同時実行を使用して、追加する追加ファイルです。
            </param>
        <param name="streamContents">
            ファイルに追加するときに含めるファイルの内容。
            </param>
        <param name="appendMode">
            その存在または追加の既存のファイルを開くだけしていない場合、同時実行の追加の呼び出しはファイルを作成する必要がありますを示します。 使用可能な値が含まれます '自動 ' の作成。
            </param>
        <param name="syncFlag">
            必要に応じて、同時実行の追加が完了した後の対処方法を示します。
            データことを示しますより多くのデータは、クライアントですぐに送信される、ファイル ハンドルの開く/ロックされているままにする (を含むファイルの長さ、最終更新時刻) ファイルのメタデータは更新されません。 メタデータことを示しますより多くのデータは、クライアントですぐに送信される、ファイル ハンドルのままにするオープン/ロックされているファイルのメタデータが更新を取得する必要があります。 閉じることを示します、クライアントにデータの送信が行われますが、ファイル ハンドルが閉じられた/ロック解除、する必要がありますファイル メタデータが更新を取得する必要があります。 使用可能な値が含まれます: 'データ'、'METADATA'、'終了'
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            必要に応じて、指定されたファイルに追加されますがまだ存在しない場合、まずファイルを作成します。 このメソッドは、ファイルに複数の同時追加をサポートします。 注: ターゲットは作成または通常の (シリアル) Append によって追加されたデータを含めないでください。 ConcurrentAppend と追加を同義です。 使用することはできません。ターゲット ファイルが変更されたこれらのいずれかを使用して追加のオプションと、ターゲット ファイルで、その他の追加オプションは使用できません。
            ConcurrentAppend 順序は保証されませんし、ランディング ターゲット ファイルのデータの重複が発生することができます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static void Create (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, System.IO.Stream streamContents = null, Nullable&lt;bool&gt; overwrite = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag = null, Nullable&lt;Guid&gt; leaseId = null, Nullable&lt;int&gt; permission = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Create(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, class System.IO.Stream streamContents, valuetype System.Nullable`1&lt;bool&gt; overwrite, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; leaseId, valuetype System.Nullable`1&lt;int32&gt; permission) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.Create(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.IO.Stream,System.Nullable{System.Boolean},System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag},System.Nullable{System.Guid},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Create (operations As IFileSystemOperations, accountName As String, path As String, Optional streamContents As Stream = null, Optional overwrite As Nullable(Of Boolean) = null, Optional syncFlag As Nullable(Of SyncFlag) = null, Optional leaseId As Nullable(Of Guid) = null, Optional permission As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * System.IO.Stream * Nullable&lt;bool&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; * Nullable&lt;Guid&gt; * Nullable&lt;int&gt; -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.Create (operations, accountName, path, streamContents, overwrite, syncFlag, leaseId, permission)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="streamContents" Type="System.IO.Stream" />
        <Parameter Name="overwrite" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="syncFlag" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt;" />
        <Parameter Name="leaseId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="permission" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') のファイルを作成します。
            </param>
        <param name="streamContents">
            ファイルを作成するときに含めるファイルの内容。 このパラメーターは省略可能な指定されていない場合、空のファイルに結果として得られます。
            </param>
        <param name="overwrite">
            場合を示す値、ファイルは上書きする必要があります。
            </param>
        <param name="syncFlag">
            必要に応じて作成の完了後に行う作業を示します。 データことを示しますより多くのデータは、クライアントですぐに送信される、ファイル ハンドルの開く/ロックされているままにする (を含むファイルの長さ、最終更新時刻) ファイルのメタデータは更新されません。 メタデータことを示しますより多くのデータは、クライアントですぐに送信される、ファイル ハンドルのままにするオープン/ロックされているファイルのメタデータが更新を取得する必要があります。 閉じることを示します、クライアントにデータの送信が行われますが、ファイル ハンドルが閉じられた/ロック解除、する必要がありますファイル メタデータが更新を取得する必要があります。 使用可能な値が含まれます: 'データ'、'METADATA'、'終了'
            </param>
        <param name="leaseId">
            省略可能な一意の GUID ファイルごとに単一ライター セマンティクスは、そのためには同じ leaseId でファイルを追加するクライアントだけが許可されることを意味することを確認します。
            </param>
        <param name="permission">
            名前のないユーザー、マスクおよびファイルの作成時に設定される他のアクセス許可の 8 進数表現です。 指定しない場合、これらのコンテナーから継承します。
            </param>
        <summary>
            必要に応じて指定された内容でファイルを作成します。 注: コンテンツを指定する場合、結果として得られるファイルは変更できません ConcurrentAppend を使用します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CreateAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, System.IO.Stream streamContents = null, Nullable&lt;bool&gt; overwrite = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag = null, Nullable&lt;Guid&gt; leaseId = null, Nullable&lt;int&gt; permission = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CreateAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, class System.IO.Stream streamContents, valuetype System.Nullable`1&lt;bool&gt; overwrite, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; leaseId, valuetype System.Nullable`1&lt;int32&gt; permission, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.CreateAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.IO.Stream,System.Nullable{System.Boolean},System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag},System.Nullable{System.Guid},System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * System.IO.Stream * Nullable&lt;bool&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; * Nullable&lt;Guid&gt; * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.CreateAsync (operations, accountName, path, streamContents, overwrite, syncFlag, leaseId, permission, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;CreateAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="streamContents" Type="System.IO.Stream" />
        <Parameter Name="overwrite" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="syncFlag" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt;" />
        <Parameter Name="leaseId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="permission" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') のファイルを作成します。
            </param>
        <param name="streamContents">
            ファイルを作成するときに含めるファイルの内容。 このパラメーターは省略可能な指定されていない場合、空のファイルに結果として得られます。
            </param>
        <param name="overwrite">
            場合を示す値、ファイルは上書きする必要があります。
            </param>
        <param name="syncFlag">
            必要に応じて作成の完了後に行う作業を示します。 データことを示しますより多くのデータは、クライアントですぐに送信される、ファイル ハンドルの開く/ロックされているままにする (を含むファイルの長さ、最終更新時刻) ファイルのメタデータは更新されません。 メタデータことを示しますより多くのデータは、クライアントですぐに送信される、ファイル ハンドルのままにするオープン/ロックされているファイルのメタデータが更新を取得する必要があります。 閉じることを示します、クライアントにデータの送信が行われますが、ファイル ハンドルが閉じられた/ロック解除、する必要がありますファイル メタデータが更新を取得する必要があります。 使用可能な値が含まれます: 'データ'、'METADATA'、'終了'
            </param>
        <param name="leaseId">
            省略可能な一意の GUID ファイルごとに単一ライター セマンティクスは、そのためには同じ leaseId でファイルを追加するクライアントだけが許可されることを意味することを確認します。
            </param>
        <param name="permission">
            名前のないユーザー、マスクおよびファイルの作成時に設定される他のアクセス許可の 8 進数表現です。 指定しない場合、これらのコンテナーから継承します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            必要に応じて指定された内容でファイルを作成します。 注: コンテンツを指定する場合、結果として得られるファイルは変更できません ConcurrentAppend を使用します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult Delete (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, Nullable&lt;bool&gt; recursive = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult Delete(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, valuetype System.Nullable`1&lt;bool&gt; recursive) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.Delete(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IFileSystemOperations, accountName As String, path As String, Optional recursive As Nullable(Of Boolean) = null) As FileOperationResult" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.Delete (operations, accountName, path, recursive)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') のファイルまたはディレクトリを削除します。
            </param>
        <param name="recursive">
            削除が再帰的になるかどうかを示す、省略可能なスイッチ
            </param>
        <summary>
            要求されたファイルまたはディレクトリ、必要に応じて再帰的に削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt; DeleteAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, Nullable&lt;bool&gt; recursive = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt; DeleteAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, valuetype System.Nullable`1&lt;bool&gt; recursive, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.DeleteAsync (operations, accountName, path, recursive, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;DeleteAsync&gt;d__39))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') のファイルまたはディレクトリを削除します。
            </param>
        <param name="recursive">
            削除が再帰的になるかどうかを示す、省略可能なスイッチ
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            要求されたファイルまたはディレクトリ、必要に応じて再帰的に削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAclStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Store.Models.AclStatusResult GetAclStatus (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, Nullable&lt;bool&gt; tooId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Store.Models.AclStatusResult GetAclStatus(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, valuetype System.Nullable`1&lt;bool&gt; tooId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.GetAclStatus(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAclStatus (operations As IFileSystemOperations, accountName As String, path As String, Optional tooId As Nullable(Of Boolean) = null) As AclStatusResult" />
      <MemberSignature Language="F#" Value="static member GetAclStatus : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.DataLake.Store.Models.AclStatusResult" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.GetAclStatus (operations, accountName, path, tooId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.AclStatusResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="tooId" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') のファイルまたはディレクトリの ACL を取得します。
            </param>
        <param name="tooId">
            ACL エントリのオブジェクト ID の代わりにわかりやすい名前を返す省略可能なスイッチです。 tooid AAD のオブジェクト ID ではなく、false を返しますフレンドリ名を =。
            既定値は true の場合、AAD のオブジェクト Id を取得します。
            </param>
        <summary>
            指定したファイルまたはディレクトリのアクセス制御リスト (ACL) エントリを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAclStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.AclStatusResult&gt; GetAclStatusAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, Nullable&lt;bool&gt; tooId = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.AclStatusResult&gt; GetAclStatusAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, valuetype System.Nullable`1&lt;bool&gt; tooId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.GetAclStatusAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAclStatusAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.AclStatusResult&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.GetAclStatusAsync (operations, accountName, path, tooId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;GetAclStatusAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.AclStatusResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="tooId" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') のファイルまたはディレクトリの ACL を取得します。
            </param>
        <param name="tooId">
            ACL エントリのオブジェクト ID の代わりにわかりやすい名前を返す省略可能なスイッチです。 tooid AAD のオブジェクト ID ではなく、false を返しますフレンドリ名を =。
            既定値は true の場合、AAD のオブジェクト Id を取得します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したファイルまたはディレクトリのアクセス制御リスト (ACL) エントリを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetContentSummary">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Store.Models.ContentSummaryResult GetContentSummary (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Store.Models.ContentSummaryResult GetContentSummary(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.GetContentSummary(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetContentSummary (operations As IFileSystemOperations, accountName As String, path As String) As ContentSummaryResult" />
      <MemberSignature Language="F#" Value="static member GetContentSummary : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string -&gt; Microsoft.Azure.Management.DataLake.Store.Models.ContentSummaryResult" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.GetContentSummary (operations, accountName, path)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.ContentSummaryResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') の概要を取得する対象のファイルです。
            </param>
        <summary>
            ファイル パスで指定された、ファイルのコンテンツの集計オブジェクトを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetContentSummaryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.ContentSummaryResult&gt; GetContentSummaryAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.ContentSummaryResult&gt; GetContentSummaryAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.GetContentSummaryAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetContentSummaryAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.ContentSummaryResult&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.GetContentSummaryAsync (operations, accountName, path, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;GetContentSummaryAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.ContentSummaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') の概要を取得する対象のファイルです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ファイル パスで指定された、ファイルのコンテンツの集計オブジェクトを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFileStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Store.Models.FileStatusResult GetFileStatus (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, Nullable&lt;bool&gt; tooId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Store.Models.FileStatusResult GetFileStatus(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, valuetype System.Nullable`1&lt;bool&gt; tooId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.GetFileStatus(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetFileStatus (operations As IFileSystemOperations, accountName As String, path As String, Optional tooId As Nullable(Of Boolean) = null) As FileStatusResult" />
      <MemberSignature Language="F#" Value="static member GetFileStatus : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.DataLake.Store.Models.FileStatusResult" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.GetFileStatus (operations, accountName, path, tooId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.FileStatusResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="tooId" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') のファイルまたは状態を取得する対象のディレクトリ。
            </param>
        <param name="tooId">
            所有者とグループの代わりにわかりやすい名前を返す省略可能なスイッチです。
            tooid AAD のオブジェクト ID ではなく、false を返しますフレンドリ名を =。 既定値は true の場合、AAD のオブジェクト Id を取得します。
            </param>
        <summary>
            ファイルのパスで指定されたファイルの状態オブジェクトを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFileStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileStatusResult&gt; GetFileStatusAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, Nullable&lt;bool&gt; tooId = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.FileStatusResult&gt; GetFileStatusAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, valuetype System.Nullable`1&lt;bool&gt; tooId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.GetFileStatusAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetFileStatusAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileStatusResult&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.GetFileStatusAsync (operations, accountName, path, tooId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;GetFileStatusAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileStatusResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="tooId" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') のファイルまたは状態を取得する対象のディレクトリ。
            </param>
        <param name="tooId">
            所有者とグループの代わりにわかりやすい名前を返す省略可能なスイッチです。
            tooid AAD のオブジェクト ID ではなく、false を返しますフレンドリ名を =。 既定値は true の場合、AAD のオブジェクト Id を取得します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ファイルのパスで指定されたファイルの状態オブジェクトを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFileStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Store.Models.FileStatusesResult ListFileStatus (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, Nullable&lt;int&gt; listSize = null, string listAfter = null, string listBefore = null, Nullable&lt;bool&gt; tooId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Store.Models.FileStatusesResult ListFileStatus(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, valuetype System.Nullable`1&lt;int32&gt; listSize, string listAfter, string listBefore, valuetype System.Nullable`1&lt;bool&gt; tooId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.ListFileStatus(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Nullable{System.Int32},System.String,System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListFileStatus (operations As IFileSystemOperations, accountName As String, path As String, Optional listSize As Nullable(Of Integer) = null, Optional listAfter As String = null, Optional listBefore As String = null, Optional tooId As Nullable(Of Boolean) = null) As FileStatusesResult" />
      <MemberSignature Language="F#" Value="static member ListFileStatus : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * Nullable&lt;int&gt; * string * string * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.DataLake.Store.Models.FileStatusesResult" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.ListFileStatus (operations, accountName, path, listSize, listAfter, listBefore, tooId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.FileStatusesResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="listSize" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="listAfter" Type="System.String" />
        <Parameter Name="listBefore" Type="System.String" />
        <Parameter Name="tooId" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') のリストにディレクトリ。
            </param>
        <param name="listSize">
            取得または返されるアイテムの数を設定します。 省略可能。
            </param>
        <param name="listAfter">
            取得または結果を返すを開始位置となる項目または lexographical インデックスを設定します。 たとえば、'',' b' のファイル リストに指定された受信者 'と listAfter = 'b' は戻り値は '、および、listAfter = 'c' が戻り値と' です。 省略可能。
            </param>
        <param name="listBefore">
            取得または結果を返すを開始する前に、項目または lexographical のインデックスを設定します。 たとえば、'',' b' のファイル リストに指定された受信者 'と listBefore = が' 'a'、'b'、および、listBefore に戻ります = 'c'、'a ',' b' を返すこともします。 省略可能。
            </param>
        <param name="tooId">
            所有者とグループの代わりにわかりやすい名前を返す省略可能なスイッチです。
            tooid AAD のオブジェクト ID ではなく、false を返しますフレンドリ名を =。 既定値は true の場合、AAD のオブジェクト Id を取得します。
            </param>
        <summary>
            省略可能な改ページ調整パラメーターを使用して、ファイルのパスで指定されたファイルの状態オブジェクトの一覧を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFileStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileStatusesResult&gt; ListFileStatusAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, Nullable&lt;int&gt; listSize = null, string listAfter = null, string listBefore = null, Nullable&lt;bool&gt; tooId = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.FileStatusesResult&gt; ListFileStatusAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, valuetype System.Nullable`1&lt;int32&gt; listSize, string listAfter, string listBefore, valuetype System.Nullable`1&lt;bool&gt; tooId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.ListFileStatusAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Nullable{System.Int32},System.String,System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListFileStatusAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * Nullable&lt;int&gt; * string * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileStatusesResult&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.ListFileStatusAsync (operations, accountName, path, listSize, listAfter, listBefore, tooId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;ListFileStatusAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileStatusesResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="listSize" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="listAfter" Type="System.String" />
        <Parameter Name="listBefore" Type="System.String" />
        <Parameter Name="tooId" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') のリストにディレクトリ。
            </param>
        <param name="listSize">
            取得または返されるアイテムの数を設定します。 省略可能。
            </param>
        <param name="listAfter">
            取得または結果を返すを開始位置となる項目または lexographical インデックスを設定します。 たとえば、'',' b' のファイル リストに指定された受信者 'と listAfter = 'b' は戻り値は '、および、listAfter = 'c' が戻り値と' です。 省略可能。
            </param>
        <param name="listBefore">
            取得または結果を返すを開始する前に、項目または lexographical のインデックスを設定します。 たとえば、'',' b' のファイル リストに指定された受信者 'と listBefore = が' 'a'、'b'、および、listBefore に戻ります = 'c'、'a ',' b' を返すこともします。 省略可能。
            </param>
        <param name="tooId">
            所有者とグループの代わりにわかりやすい名前を返す省略可能なスイッチです。
            tooid AAD のオブジェクト ID ではなく、false を返しますフレンドリ名を =。 既定値は true の場合、AAD のオブジェクト Id を取得します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            省略可能な改ページ調整パラメーターを使用して、ファイルのパスで指定されたファイルの状態オブジェクトの一覧を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Mkdirs">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult Mkdirs (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, Nullable&lt;int&gt; permission = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult Mkdirs(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, valuetype System.Nullable`1&lt;int32&gt; permission) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.Mkdirs(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Mkdirs (operations As IFileSystemOperations, accountName As String, path As String, Optional permission As Nullable(Of Integer) = null) As FileOperationResult" />
      <MemberSignature Language="F#" Value="static member Mkdirs : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.Mkdirs (operations, accountName, path, permission)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="permission" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') を作成するディレクトリ。
            </param>
        <param name="permission">
            省略可能な 8 進数のアクセス許可のディレクトリの作成に使用する必要があります。
            </param>
        <summary>
            ディレクトリを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MkdirsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt; MkdirsAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, Nullable&lt;int&gt; permission = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt; MkdirsAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, valuetype System.Nullable`1&lt;int32&gt; permission, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.MkdirsAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member MkdirsAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.MkdirsAsync (operations, accountName, path, permission, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;MkdirsAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="permission" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') を作成するディレクトリ。
            </param>
        <param name="permission">
            省略可能な 8 進数のアクセス許可のディレクトリの作成に使用する必要があります。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ディレクトリを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ModifyAclEntries">
      <MemberSignature Language="C#" Value="public static void ModifyAclEntries (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string aclspec);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ModifyAclEntries(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string aclspec) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.ModifyAclEntries(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub ModifyAclEntries (operations As IFileSystemOperations, accountName As String, path As String, aclspec As String)" />
      <MemberSignature Language="F#" Value="static member ModifyAclEntries : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.ModifyAclEntries (operations, accountName, path, aclspec)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclspec" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') のファイルまたはディレクトリが変更されている ACL を使用します。
            </param>
        <param name="aclspec">
            形式で、ACL の変更操作に含まれている ACL 仕様 ' [既定値:] ユーザー | グループ | その他の:: r |-w |-x |-'
            </param>
        <summary>
            ファイルまたはフォルダーの既存のアクセス制御リスト (ACL) エントリを変更します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ModifyAclEntriesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ModifyAclEntriesAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string aclspec, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ModifyAclEntriesAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string aclspec, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.ModifyAclEntriesAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ModifyAclEntriesAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.ModifyAclEntriesAsync (operations, accountName, path, aclspec, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;ModifyAclEntriesAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclspec" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') のファイルまたはディレクトリが変更されている ACL を使用します。
            </param>
        <param name="aclspec">
            形式で、ACL の変更操作に含まれている ACL 仕様 ' [既定値:] ユーザー | グループ | その他の:: r |-w |-x |-'
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ファイルまたはフォルダーの既存のアクセス制御リスト (ACL) エントリを変更します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MsConcat">
      <MemberSignature Language="C#" Value="public static void MsConcat (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, System.IO.Stream streamContents, Nullable&lt;bool&gt; deleteSourceDirectory = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void MsConcat(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, class System.IO.Stream streamContents, valuetype System.Nullable`1&lt;bool&gt; deleteSourceDirectory) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.MsConcat(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.IO.Stream,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub MsConcat (operations As IFileSystemOperations, accountName As String, path As String, streamContents As Stream, Optional deleteSourceDirectory As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="static member MsConcat : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * System.IO.Stream * Nullable&lt;bool&gt; -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.MsConcat (operations, accountName, path, streamContents, deleteSourceDirectory)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="streamContents" Type="System.IO.Stream" />
        <Parameter Name="deleteSourceDirectory" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') の連結の結果として得られる出力先ファイルです。
            </param>
        <param name="streamContents">
            Data Lake Store パスの一覧 (以降で '/') のソース ファイルです。
            形式でパスのコンマ区切りの一覧でなければなりません: sources=/file/path/1.txt,/file/path/2.txt,/file/path/lastfile.csv
            </param>
        <param name="deleteSourceDirectory">
            指定すると、最適化代わりに各個々 のソース ストリームを削除するには、フォルダーを削除、ソース ストリーム場合は代わりに、同じフォルダーにすべてのストリーム。 これは、結果、フォルダー内のみのストリームが連結操作の一部とパフォーマンスが大幅に改善します。 警告: ソース ファイルではないその他のファイルの削除が含まれます。 ソース ファイルがソース ディレクトリのファイルのみの場合は true にのみ設定します。
            </param>
        <summary>
            出力先ファイル、成功時にすべてのソース ファイルを削除するのには、ソース ファイルのリストを連結します。 このメソッドは、Concat メソッドよりも多くのソース ファイルのパスを受け取ります。 このメソッドと、受け取るパラメーターは、使いやすさ、今後のバージョンでの変更の対象はします。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MsConcatAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task MsConcatAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, System.IO.Stream streamContents, Nullable&lt;bool&gt; deleteSourceDirectory = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task MsConcatAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, class System.IO.Stream streamContents, valuetype System.Nullable`1&lt;bool&gt; deleteSourceDirectory, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.MsConcatAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.IO.Stream,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member MsConcatAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * System.IO.Stream * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.MsConcatAsync (operations, accountName, path, streamContents, deleteSourceDirectory, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;MsConcatAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="streamContents" Type="System.IO.Stream" />
        <Parameter Name="deleteSourceDirectory" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') の連結の結果として得られる出力先ファイルです。
            </param>
        <param name="streamContents">
            Data Lake Store パスの一覧 (以降で '/') のソース ファイルです。
            形式でパスのコンマ区切りの一覧でなければなりません: sources=/file/path/1.txt,/file/path/2.txt,/file/path/lastfile.csv
            </param>
        <param name="deleteSourceDirectory">
            指定すると、最適化代わりに各個々 のソース ストリームを削除するには、フォルダーを削除、ソース ストリーム場合は代わりに、同じフォルダーにすべてのストリーム。 これは、結果、フォルダー内のみのストリームが連結操作の一部とパフォーマンスが大幅に改善します。 警告: ソース ファイルではないその他のファイルの削除が含まれます。 ソース ファイルがソース ディレクトリのファイルのみの場合は true にのみ設定します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            出力先ファイル、成功時にすべてのソース ファイルを削除するのには、ソース ファイルのリストを連結します。 このメソッドは、Concat メソッドよりも多くのソース ファイルのパスを受け取ります。 このメソッドと、受け取るパラメーターは、使いやすさ、今後のバージョンでの変更の対象はします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Open">
      <MemberSignature Language="C#" Value="public static System.IO.Stream Open (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, Nullable&lt;long&gt; length = null, Nullable&lt;long&gt; offset = null, Nullable&lt;Guid&gt; fileSessionId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.IO.Stream Open(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, valuetype System.Nullable`1&lt;int64&gt; length, valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; fileSessionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.Open(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Guid})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Open (operations As IFileSystemOperations, accountName As String, path As String, Optional length As Nullable(Of Long) = null, Optional offset As Nullable(Of Long) = null, Optional fileSessionId As Nullable(Of Guid) = null) As Stream" />
      <MemberSignature Language="F#" Value="static member Open : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;Guid&gt; -&gt; System.IO.Stream" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.Open (operations, accountName, path, length, offset, fileSessionId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IO.Stream</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="length" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="fileSessionId" Type="System.Nullable&lt;System.Guid&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') のファイルを開きます。
            </param>
        <param name="length">
            サーバーが取得しようとするバイト数。 取得されます&lt;長さのバイト数を = です。
            </param>
        <param name="offset">
            データの読み取りを開始するバイト オフセット。
            </param>
        <param name="fileSessionId">
            1 ファイルが同じ fileSessionId ですべての読み取りを示す省略可能な一意の GUID は、同じクライアントと同じセッションです。 パフォーマンス上の利点が得られます。
            </param>
        <summary>
            開き、指定したファイルから読み取ります。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.IO.Stream&gt; OpenAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, Nullable&lt;long&gt; length = null, Nullable&lt;long&gt; offset = null, Nullable&lt;Guid&gt; fileSessionId = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.IO.Stream&gt; OpenAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, valuetype System.Nullable`1&lt;int64&gt; length, valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; fileSessionId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.OpenAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Guid},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member OpenAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;Guid&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.IO.Stream&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.OpenAsync (operations, accountName, path, length, offset, fileSessionId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;OpenAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.IO.Stream&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="length" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="fileSessionId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') のファイルを開きます。
            </param>
        <param name="length">
            サーバーが取得しようとするバイト数。 取得されます&lt;長さのバイト数を = です。
            </param>
        <param name="offset">
            データの読み取りを開始するバイト オフセット。
            </param>
        <param name="fileSessionId">
            1 ファイルが同じ fileSessionId ですべての読み取りを示す省略可能な一意の GUID は、同じクライアントと同じセッションです。 パフォーマンス上の利点が得られます。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            開き、指定したファイルから読み取ります。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PathExists">
      <MemberSignature Language="C#" Value="public static bool PathExists (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string getFilePath);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool PathExists(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string getFilePath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.PathExists(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function PathExists (operations As IFileSystemOperations, accountName As String, getFilePath As String) As Boolean" />
      <MemberSignature Language="F#" Value="static member PathExists : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string -&gt; bool" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.PathExists (operations, accountName, getFilePath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="getFilePath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="getFilePath">
            Data Lake Store のパス (以降で '/') のファイルまたはディレクトリの存在をテストします。
            </param>
        <summary>
            ファイル パスで指定されたファイルまたはディレクトリ オブジェクトの存在をテストします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PathExistsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;bool&gt; PathExistsAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string getFilePath, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;bool&gt; PathExistsAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string getFilePath, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.PathExistsAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PathExistsAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.PathExistsAsync (operations, accountName, getFilePath, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;PathExistsAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="getFilePath" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="getFilePath">
            Data Lake Store のパス (以降で '/') のファイルまたはディレクトリの存在をテストします。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ファイル パスで指定されたファイルまたはディレクトリ オブジェクトの存在をテストします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAcl">
      <MemberSignature Language="C#" Value="public static void RemoveAcl (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void RemoveAcl(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.RemoveAcl(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub RemoveAcl (operations As IFileSystemOperations, accountName As String, path As String)" />
      <MemberSignature Language="F#" Value="static member RemoveAcl : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.RemoveAcl (operations, accountName, path)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') のファイルまたはディレクトリ ACL を削除します。
            </param>
        <summary>
            指定したファイルまたはディレクトリの既存のアクセス制御リスト (ACL) を削除します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAclAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RemoveAclAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RemoveAclAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.RemoveAclAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RemoveAclAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.RemoveAclAsync (operations, accountName, path, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;RemoveAclAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') のファイルまたはディレクトリ ACL を削除します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したファイルまたはディレクトリの既存のアクセス制御リスト (ACL) を削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAclEntries">
      <MemberSignature Language="C#" Value="public static void RemoveAclEntries (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string aclspec);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void RemoveAclEntries(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string aclspec) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.RemoveAclEntries(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub RemoveAclEntries (operations As IFileSystemOperations, accountName As String, path As String, aclspec As String)" />
      <MemberSignature Language="F#" Value="static member RemoveAclEntries : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.RemoveAclEntries (operations, accountName, path, aclspec)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclspec" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') のファイルまたはディレクトリ ACL を削除します。
            </param>
        <param name="aclspec">
            形式で、ACL の削除操作に含まれている ACL spec ' [既定値:] ユーザー | グループ | その他の '
            </param>
        <summary>
            既存のファイルまたはフォルダーのアクセス制御リスト (ACL) エントリを削除します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAclEntriesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RemoveAclEntriesAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string aclspec, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RemoveAclEntriesAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string aclspec, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.RemoveAclEntriesAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RemoveAclEntriesAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.RemoveAclEntriesAsync (operations, accountName, path, aclspec, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;RemoveAclEntriesAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclspec" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') のファイルまたはディレクトリ ACL を削除します。
            </param>
        <param name="aclspec">
            形式で、ACL の削除操作に含まれている ACL spec ' [既定値:] ユーザー | グループ | その他の '
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            既存のファイルまたはフォルダーのアクセス制御リスト (ACL) エントリを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveDefaultAcl">
      <MemberSignature Language="C#" Value="public static void RemoveDefaultAcl (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void RemoveDefaultAcl(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.RemoveDefaultAcl(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub RemoveDefaultAcl (operations As IFileSystemOperations, accountName As String, path As String)" />
      <MemberSignature Language="F#" Value="static member RemoveDefaultAcl : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.RemoveDefaultAcl (operations, accountName, path)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') の既定の ACL が削除されると同じディレクトリにします。
            </param>
        <summary>
            既存既定のアクセス制御リスト (ACL) の指定されたディレクトリを削除します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveDefaultAclAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RemoveDefaultAclAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RemoveDefaultAclAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.RemoveDefaultAclAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RemoveDefaultAclAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.RemoveDefaultAclAsync (operations, accountName, path, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;RemoveDefaultAclAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') の既定の ACL が削除されると同じディレクトリにします。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            既存既定のアクセス制御リスト (ACL) の指定されたディレクトリを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Rename">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult Rename (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string destination);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult Rename(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string destination) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.Rename(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Rename (operations As IFileSystemOperations, accountName As String, path As String, destination As String) As FileOperationResult" />
      <MemberSignature Language="F#" Value="static member Rename : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.Rename (operations, accountName, path, destination)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="destination" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') のファイルまたはディレクトリに移動または名前変更します。
            </param>
        <param name="destination">
            移動または名前変更、ファイルまたはフォルダーへのパス
            </param>
        <summary>
            ファイルまたはディレクトリの名前を変更します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RenameAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt; RenameAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string destination, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt; RenameAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string destination, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.RenameAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RenameAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.RenameAsync (operations, accountName, path, destination, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;RenameAsync&gt;d__41))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="destination" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') のファイルまたはディレクトリに移動または名前変更します。
            </param>
        <param name="destination">
            移動または名前変更、ファイルまたはフォルダーへのパス
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ファイルまたはディレクトリの名前を変更します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetAcl">
      <MemberSignature Language="C#" Value="public static void SetAcl (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string aclspec);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void SetAcl(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string aclspec) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.SetAcl(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub SetAcl (operations As IFileSystemOperations, accountName As String, path As String, aclspec As String)" />
      <MemberSignature Language="F#" Value="static member SetAcl : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.SetAcl (operations, accountName, path, aclspec)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclspec" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') のファイルまたはディレクトリの ACL を設定します。
            </param>
        <param name="aclspec">
            形式で ACL を作成する操作に含まれる ACL spec ' [既定値:] ユーザー | グループ | その他の:: r |-w |-x |-'
            </param>
        <summary>
            ファイルまたはフォルダーのアクセス制御リスト (ACL) を設定します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetAclAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task SetAclAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string aclspec, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task SetAclAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string aclspec, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.SetAclAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SetAclAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.SetAclAsync (operations, accountName, path, aclspec, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;SetAclAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclspec" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') のファイルまたはディレクトリの ACL を設定します。
            </param>
        <param name="aclspec">
            形式で ACL を作成する操作に含まれる ACL spec ' [既定値:] ユーザー | グループ | その他の:: r |-w |-x |-'
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ファイルまたはフォルダーのアクセス制御リスト (ACL) を設定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetFileExpiry">
      <MemberSignature Language="C#" Value="public static void SetFileExpiry (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, Microsoft.Azure.Management.DataLake.Store.Models.ExpiryOptionType expiryOption, Nullable&lt;long&gt; expireTime = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void SetFileExpiry(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, valuetype Microsoft.Azure.Management.DataLake.Store.Models.ExpiryOptionType expiryOption, valuetype System.Nullable`1&lt;int64&gt; expireTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.SetFileExpiry(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,Microsoft.Azure.Management.DataLake.Store.Models.ExpiryOptionType,System.Nullable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub SetFileExpiry (operations As IFileSystemOperations, accountName As String, path As String, expiryOption As ExpiryOptionType, Optional expireTime As Nullable(Of Long) = null)" />
      <MemberSignature Language="F#" Value="static member SetFileExpiry : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * Microsoft.Azure.Management.DataLake.Store.Models.ExpiryOptionType * Nullable&lt;int64&gt; -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.SetFileExpiry (operations, accountName, path, expiryOption, expireTime)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="expiryOption" Type="Microsoft.Azure.Management.DataLake.Store.Models.ExpiryOptionType" />
        <Parameter Name="expireTime" Type="System.Nullable&lt;System.Int64&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') を設定するか、有効期限を削除するファイルのです。
            </param>
        <param name="expiryOption">
            ファイルを使用する有効期限の種類を示します。 1。 NeverExpire: ExpireTime は無視されます。 2. RelativeToNow: ExpireTime は、ファイルの有効期限が更新されたときに、基準に有効期限の日付を表すミリ秒の整数です。 手順 3. RelativeToCreationDate: ExpireTime は、ファイルの作成の基準とした有効期限の日付を表すミリ秒の整数です。
            4. 絶対値: ExpireTime 整数です (ミリ秒単位) の 1970 年 1 月 1 基準とした Unix タイムスタンプとして 00時 00分: 00 です。 使用可能な値が含まれます: 'NeverExpire'、'RelativeToNow'、'RelativeToCreationDate'、'Absolute'
            </param>
        <param name="expireTime">
            ファイルは、有効期限が設定された ExpiryOption に対応する時間。
            </param>
        <summary>
            設定または指定したファイルに有効期限を削除します。 この操作は、ファイルに対してのみ実行できます。 フォルダーを指定することはできません。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetFileExpiryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task SetFileExpiryAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, Microsoft.Azure.Management.DataLake.Store.Models.ExpiryOptionType expiryOption, Nullable&lt;long&gt; expireTime = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task SetFileExpiryAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, valuetype Microsoft.Azure.Management.DataLake.Store.Models.ExpiryOptionType expiryOption, valuetype System.Nullable`1&lt;int64&gt; expireTime, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.SetFileExpiryAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,Microsoft.Azure.Management.DataLake.Store.Models.ExpiryOptionType,System.Nullable{System.Int64},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SetFileExpiryAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * Microsoft.Azure.Management.DataLake.Store.Models.ExpiryOptionType * Nullable&lt;int64&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.SetFileExpiryAsync (operations, accountName, path, expiryOption, expireTime, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;SetFileExpiryAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="expiryOption" Type="Microsoft.Azure.Management.DataLake.Store.Models.ExpiryOptionType" />
        <Parameter Name="expireTime" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') を設定するか、有効期限を削除するファイルのです。
            </param>
        <param name="expiryOption">
            ファイルを使用する有効期限の種類を示します。 1。 NeverExpire: ExpireTime は無視されます。 2. RelativeToNow: ExpireTime は、ファイルの有効期限が更新されたときに、基準に有効期限の日付を表すミリ秒の整数です。 手順 3. RelativeToCreationDate: ExpireTime は、ファイルの作成の基準とした有効期限の日付を表すミリ秒の整数です。
            4. 絶対値: ExpireTime 整数です (ミリ秒単位) の 1970 年 1 月 1 基準とした Unix タイムスタンプとして 00時 00分: 00 です。 使用可能な値が含まれます: 'NeverExpire'、'RelativeToNow'、'RelativeToCreationDate'、'Absolute'
            </param>
        <param name="expireTime">
            ファイルは、有効期限が設定された ExpiryOption に対応する時間。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            設定または指定したファイルに有効期限を削除します。 この操作は、ファイルに対してのみ実行できます。 フォルダーを指定することはできません。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetOwner">
      <MemberSignature Language="C#" Value="public static void SetOwner (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string owner = null, string group = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void SetOwner(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string owner, string group) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.SetOwner(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub SetOwner (operations As IFileSystemOperations, accountName As String, path As String, Optional owner As String = null, Optional group As String = null)" />
      <MemberSignature Language="F#" Value="static member SetOwner : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.SetOwner (operations, accountName, path, owner, group)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="owner" Type="System.String" />
        <Parameter Name="group" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') のファイルまたは所有者を設定する対象のディレクトリ。
            </param>
        <param name="owner">
            ファイルまたはディレクトリの所有者であるユーザーの AAD のオブジェクト ID。 空の場合は、プロパティは変更されません。
            </param>
        <param name="group">
            ファイルまたはディレクトリのグループの所有者の AAD のオブジェクト ID。 空の場合は、プロパティは変更されません。
            </param>
        <summary>
            ファイルまたはディレクトリの所有者を設定します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetOwnerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task SetOwnerAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string owner = null, string group = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task SetOwnerAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string owner, string group, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.SetOwnerAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SetOwnerAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.SetOwnerAsync (operations, accountName, path, owner, group, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;SetOwnerAsync&gt;d__43))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="owner" Type="System.String" />
        <Parameter Name="group" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') のファイルまたは所有者を設定する対象のディレクトリ。
            </param>
        <param name="owner">
            ファイルまたはディレクトリの所有者であるユーザーの AAD のオブジェクト ID。 空の場合は、プロパティは変更されません。
            </param>
        <param name="group">
            ファイルまたはディレクトリのグループの所有者の AAD のオブジェクト ID。 空の場合は、プロパティは変更されません。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ファイルまたはディレクトリの所有者を設定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPermission">
      <MemberSignature Language="C#" Value="public static void SetPermission (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string permission = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void SetPermission(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string permission) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.SetPermission(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub SetPermission (operations As IFileSystemOperations, accountName As String, path As String, Optional permission As String = null)" />
      <MemberSignature Language="F#" Value="static member SetPermission : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.SetPermission (operations, accountName, path, permission)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="permission" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') のファイルまたはアクセス許可を設定する対象のディレクトリ。
            </param>
        <param name="permission">
            (つまり、アクセス許可の文字列表現 rwx')。 空の場合、このプロパティは変更されません。
            </param>
        <summary>
            ファイルまたはフォルダーのアクセス許可を設定します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPermissionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task SetPermissionAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string permission = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task SetPermissionAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string permission, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.SetPermissionAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SetPermissionAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.SetPermissionAsync (operations, accountName, path, permission, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;SetPermissionAsync&gt;d__45))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="permission" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') のファイルまたはアクセス許可を設定する対象のディレクトリ。
            </param>
        <param name="permission">
            (つまり、アクセス許可の文字列表現 rwx')。 空の場合、このプロパティは変更されません。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ファイルまたはフォルダーのアクセス許可を設定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>