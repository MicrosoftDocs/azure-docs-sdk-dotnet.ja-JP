<Type Name="IFileSystemOperations" FullName="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations">
  <TypeSignature Language="C#" Value="public interface IFileSystemOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IFileSystemOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IFileSystemOperations" />
  <TypeSignature Language="F#" Value="type IFileSystemOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            FileSystemOperations 操作です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AppendWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; AppendWithHttpMessagesAsync (string accountName, string path, System.IO.Stream streamContents, Nullable&lt;long&gt; offset = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag = null, Nullable&lt;Guid&gt; leaseId = null, Nullable&lt;Guid&gt; fileSessionId = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; AppendWithHttpMessagesAsync(string accountName, string path, class System.IO.Stream streamContents, valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; leaseId, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; fileSessionId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.AppendWithHttpMessagesAsync(System.String,System.String,System.IO.Stream,System.Nullable{System.Int64},System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag},System.Nullable{System.Guid},System.Nullable{System.Guid},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AppendWithHttpMessagesAsync : string * string * System.IO.Stream * Nullable&lt;int64&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; * Nullable&lt;Guid&gt; * Nullable&lt;Guid&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iFileSystemOperations.AppendWithHttpMessagesAsync (accountName, path, streamContents, offset, syncFlag, leaseId, fileSessionId, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="streamContents" Type="System.IO.Stream" />
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="syncFlag" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt;" />
        <Parameter Name="leaseId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="fileSessionId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
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
            追加操作を開始するためのストリームの省略可能なオフセット。
            既定では、ストリームの末尾に追加します。
            </param>
        <param name="syncFlag">
            必要に応じて、同時実行の追加が完了した後の対処方法を示します。 データことを示しますより多くのデータは、クライアントですぐに送信される、ファイル ハンドルの開く/ロックされているままにする (を含むファイルの長さ、最終更新時刻) ファイルのメタデータは更新されません。 メタデータことを示しますより多くのデータは、クライアントですぐに送信される、ファイル ハンドルのままにするオープン/ロックされているファイルのメタデータが更新を取得する必要があります。 閉じることを示します、クライアントにデータの送信が行われますが、ファイル ハンドルが閉じられた/ロック解除、する必要がありますファイル メタデータが更新を取得する必要があります。 使用可能な値が含まれます: 'データ'、'METADATA'、'終了'
            </param>
        <param name="leaseId">
            省略可能な一意の GUID ファイルごとに単一ライター セマンティクスは、そのためには同じ leaseId でファイルを追加するクライアントだけが許可されることを意味することを確認します。
            </param>
        <param name="fileSessionId">
            1 ファイルすべてを示す省略可能な一意の GUID、同じ追加 fileSessionId は、同じクライアントと同じセッションからです。 SyncFlag がデータまたはメタデータの場合、パフォーマンスが向上が得られます。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            使用のシリアルを指定したファイルに追加します。 注: ターゲットは ConcurrentAppend によって追加されたデータを含めないでください。 ConcurrentAppend と追加を同義です。 使用することはできません。ターゲット ファイルが変更されたこれらのいずれかを使用して追加のオプションと、ターゲット ファイルで、その他の追加オプションは使用できません。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CheckAccessWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; CheckAccessWithHttpMessagesAsync (string accountName, string path, string fsaction, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; CheckAccessWithHttpMessagesAsync(string accountName, string path, string fsaction, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.CheckAccessWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CheckAccessWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iFileSystemOperations.CheckAccessWithHttpMessagesAsync (accountName, path, fsaction, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="fsaction" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') のファイルまたはディレクトリのアクセスをチェックします。
            </param>
        <param name="fsaction">
            正規表現パターンに一致する文字列形式でのシステム操作読み取り/書き込み/実行のファイル ' [rwx-] \ {3\}'
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            かどうか、指定のアクセスは、指定されたパスを確認します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ConcatWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; ConcatWithHttpMessagesAsync (string accountName, string path, System.Collections.Generic.IList&lt;string&gt; sources, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; ConcatWithHttpMessagesAsync(string accountName, string path, class System.Collections.Generic.IList`1&lt;string&gt; sources, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.ConcatWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ConcatWithHttpMessagesAsync : string * string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iFileSystemOperations.ConcatWithHttpMessagesAsync (accountName, path, sources, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="sources" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') の連結の結果として得られる出力先ファイルです。
            </param>
        <param name="sources">
            一連のコンマ区切りの Data Lake Store パス (以降で '/') を連結する順序で連結するファイルのです。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            出力先ファイル、成功時にすべてのソース ファイルを削除するのには、ソース ファイルのリストを連結します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ConcurrentAppendWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; ConcurrentAppendWithHttpMessagesAsync (string accountName, string path, System.IO.Stream streamContents, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.AppendModeType&gt; appendMode = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; ConcurrentAppendWithHttpMessagesAsync(string accountName, string path, class System.IO.Stream streamContents, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.AppendModeType&gt; appendMode, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.ConcurrentAppendWithHttpMessagesAsync(System.String,System.String,System.IO.Stream,System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.AppendModeType},System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ConcurrentAppendWithHttpMessagesAsync : string * string * System.IO.Stream * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.AppendModeType&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iFileSystemOperations.ConcurrentAppendWithHttpMessagesAsync (accountName, path, streamContents, appendMode, syncFlag, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="streamContents" Type="System.IO.Stream" />
        <Parameter Name="appendMode" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.AppendModeType&gt;" />
        <Parameter Name="syncFlag" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
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
            必要に応じて、同時実行の追加が完了した後の対処方法を示します。 データことを示しますより多くのデータは、クライアントですぐに送信される、ファイル ハンドルの開く/ロックされているままにする (を含むファイルの長さ、最終更新時刻) ファイルのメタデータは更新されません。 メタデータことを示しますより多くのデータは、クライアントですぐに送信される、ファイル ハンドルのままにするオープン/ロックされているファイルのメタデータが更新を取得する必要があります。 閉じることを示します、クライアントにデータの送信が行われますが、ファイル ハンドルが閉じられた/ロック解除、する必要がありますファイル メタデータが更新を取得する必要があります。 使用可能な値が含まれます: 'データ'、'METADATA'、'終了'
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            必要に応じて、指定されたファイルに追加されますがまだ存在しない場合、まずファイルを作成します。 このメソッドは、ファイルに複数の同時追加をサポートします。 注: ターゲットは作成または通常の (シリアル) Append によって追加されたデータを含めないでください。 ConcurrentAppend と追加を同義です。 使用することはできません。ターゲット ファイルが変更されたこれらのいずれかを使用して追加のオプションと、ターゲット ファイルで、その他の追加オプションは使用できません。 ConcurrentAppend 順序は保証されませんし、ランディング ターゲット ファイルのデータの重複が発生することができます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; CreateWithHttpMessagesAsync (string accountName, string path, System.IO.Stream streamContents = null, Nullable&lt;bool&gt; overwrite = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag = null, Nullable&lt;Guid&gt; leaseId = null, Nullable&lt;int&gt; permission = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; CreateWithHttpMessagesAsync(string accountName, string path, class System.IO.Stream streamContents, valuetype System.Nullable`1&lt;bool&gt; overwrite, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; leaseId, valuetype System.Nullable`1&lt;int32&gt; permission, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.CreateWithHttpMessagesAsync(System.String,System.String,System.IO.Stream,System.Nullable{System.Boolean},System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag},System.Nullable{System.Guid},System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateWithHttpMessagesAsync : string * string * System.IO.Stream * Nullable&lt;bool&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; * Nullable&lt;Guid&gt; * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iFileSystemOperations.CreateWithHttpMessagesAsync (accountName, path, streamContents, overwrite, syncFlag, leaseId, permission, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="streamContents" Type="System.IO.Stream" />
        <Parameter Name="overwrite" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="syncFlag" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt;" />
        <Parameter Name="leaseId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="permission" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
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
            必要に応じて作成の完了後に行う作業を示します。
            データことを示しますより多くのデータは、クライアントですぐに送信される、ファイル ハンドルの開く/ロックされているままにする (を含むファイルの長さ、最終更新時刻) ファイルのメタデータは更新されません。 メタデータことを示しますより多くのデータは、クライアントですぐに送信される、ファイル ハンドルのままにするオープン/ロックされているファイルのメタデータが更新を取得する必要があります。 閉じることを示します、クライアントにデータの送信が行われますが、ファイル ハンドルが閉じられた/ロック解除、する必要がありますファイル メタデータが更新を取得する必要があります。 使用可能な値が含まれます: 'データ'、'METADATA'、'終了'
            </param>
        <param name="leaseId">
            省略可能な一意の GUID ファイルごとに単一ライター セマンティクスは、そのためには同じ leaseId でファイルを追加するクライアントだけが許可されることを意味することを確認します。
            </param>
        <param name="permission">
            名前のないユーザー、マスクおよびファイルの作成時に設定される他のアクセス許可の 8 進数表現です。 指定しない場合、これらのコンテナーから継承します。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            必要に応じて指定された内容でファイルを作成します。 注: コンテンツを指定する場合、結果として得られるファイルは変更できません ConcurrentAppend を使用します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;&gt; DeleteWithHttpMessagesAsync (string accountName, string path, Nullable&lt;bool&gt; recursive = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;&gt; DeleteWithHttpMessagesAsync(string accountName, string path, valuetype System.Nullable`1&lt;bool&gt; recursive, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;&gt;" Usage="iFileSystemOperations.DeleteWithHttpMessagesAsync (accountName, path, recursive, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') のファイルまたはディレクトリを削除します。
            </param>
        <param name="recursive">
            削除が再帰的になるかどうかを示す、省略可能なスイッチ
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            要求されたファイルまたはディレクトリ、必要に応じて再帰的に削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DownloadFile">
      <MemberSignature Language="C#" Value="public void DownloadFile (string accountName, string sourcePath, string destinationPath, int threadCount = -1, bool resume = false, bool overwrite = false, IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferProgress&gt; progressTracker = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DownloadFile(string accountName, string sourcePath, string destinationPath, int32 threadCount, bool resume, bool overwrite, class System.IProgress`1&lt;class Microsoft.Azure.Management.DataLake.Store.TransferProgress&gt; progressTracker, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.DownloadFile(System.String,System.String,System.String,System.Int32,System.Boolean,System.Boolean,System.IProgress{Microsoft.Azure.Management.DataLake.Store.TransferProgress},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DownloadFile : string * string * string * int * bool * bool * IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferProgress&gt; * System.Threading.CancellationToken -&gt; unit" Usage="iFileSystemOperations.DownloadFile (accountName, sourcePath, destinationPath, threadCount, resume, overwrite, progressTracker, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="sourcePath" Type="System.String" />
        <Parameter Name="destinationPath" Type="System.String" />
        <Parameter Name="threadCount" Type="System.Int32" />
        <Parameter Name="resume" Type="System.Boolean" />
        <Parameter Name="overwrite" Type="System.Boolean" />
        <Parameter Name="progressTracker" Type="System.IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferProgress&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="sourcePath">
            Data Lake Store のパス (以降で '/') のファイルをダウンロードします。
            </param>
        <param name="destinationPath">
            ファイルをダウンロードするローカル パスです。 ディレクトリが指定されている場合、ファイル名は、同じであるソース ファイル名として
            </param>
        <param name="threadCount">
            ダウンロード中に使用するスレッドの最大数。 既定では、この番号はに基づいて計算ファイルのサイズ。
            </param>
        <param name="resume">
            このダウンロードは、障害が発生した以前のダウンロードの継続タスクを示すスイッチです。 既定値は false です。
            </param>
        <param name="overwrite">
            このダウンロードを示す、スイッチを上書きする、ターゲット ファイルが存在する場合。 既定値は false、およびターゲット ファイルが存在する場合は、ダウンロードに失敗するが高速されます。
            </param>
        <param name="progressTracker">
            非同期的にダウンロード操作の進行状況を追跡するために使用できる省略可能なデリゲート。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された Data Lake Store アカウントからファイルをダウンロードします。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            操作に無効なステータス コードが返されるときにスローされます。
            </exception>
        <exception cref="T:System.Threading.Tasks.TaskCanceledException">
            操作の完了に時間がかかる場合、またはユーザーが明示的にキャンセルするとスローされます。
            </exception>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.InvalidMetadataException">
            再開のメタデータが壊れているか、現在の操作に関連付けられていない場合にスローされます。
            </exception>
        <exception cref="T:System.IO.FileNotFoundException">
            ソース パスが見つからない場合にスローされます。
            </exception>
        <exception cref="T:System.InvalidOperationException">
            無効なダウンロードを試行または操作中にファイルが外部で変更された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.TransferFailedException">
            転送操作が失敗した場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DownloadFolder">
      <MemberSignature Language="C#" Value="public void DownloadFolder (string accountName, string sourcePath, string destinationPath, int perFileThreadCount = -1, int concurrentFileCount = -1, bool resume = false, bool overwrite = false, bool recurse = false, IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress&gt; progressTracker = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DownloadFolder(string accountName, string sourcePath, string destinationPath, int32 perFileThreadCount, int32 concurrentFileCount, bool resume, bool overwrite, bool recurse, class System.IProgress`1&lt;class Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress&gt; progressTracker, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.DownloadFolder(System.String,System.String,System.String,System.Int32,System.Int32,System.Boolean,System.Boolean,System.Boolean,System.IProgress{Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DownloadFolder : string * string * string * int * int * bool * bool * bool * IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress&gt; * System.Threading.CancellationToken -&gt; unit" Usage="iFileSystemOperations.DownloadFolder (accountName, sourcePath, destinationPath, perFileThreadCount, concurrentFileCount, resume, overwrite, recurse, progressTracker, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="sourcePath" Type="System.String" />
        <Parameter Name="destinationPath" Type="System.String" />
        <Parameter Name="perFileThreadCount" Type="System.Int32" />
        <Parameter Name="concurrentFileCount" Type="System.Int32" />
        <Parameter Name="resume" Type="System.Boolean" />
        <Parameter Name="overwrite" Type="System.Boolean" />
        <Parameter Name="recurse" Type="System.Boolean" />
        <Parameter Name="progressTracker" Type="System.IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="sourcePath">
            Data Lake Store のパス (以降で '/') をダウンロードするディレクトリ。
            </param>
        <param name="destinationPath">
            ダウンロードするフォルダーへのローカル パス。
            </param>
        <param name="perFileThreadCount">
            ダウンロード中にファイルごとに使用するスレッドの最大数。 既定では、この番号はに基づいて計算フォルダー構造と平均ファイルのサイズ。
            </param>
        <param name="concurrentFileCount">
            同時にダウンロードするファイルの最大数。 既定では、この番号はに基づいて計算のフォルダー構造およびファイルの数。
            </param>
        <param name="resume">
            このダウンロードは、障害が発生した以前のダウンロードの継続タスクを示すスイッチです。 既定値は false です。
            </param>
        <param name="overwrite">
            このダウンロードを示すスイッチは、存在する場合、ターゲット ディレクトリの内容を上書きする必要があります。 既定値は false に設定し、ダウンロードは高速なフェールオーバー ターゲットの場所が存在する場合。
            </param>
        <param name="recurse">
            このダウンロードを示すスイッチは、ソース ディレクトリを再帰的にまたは最上位レベルだけをダウンロードする必要があります。 既定値は false の場合、最上位レベルだけがダウンロードされます。
            </param>
        <param name="progressTracker">
            非同期的にダウンロード操作の進行状況を追跡するために使用できる省略可能なデリゲート。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された Data Lake Store アカウントからフォルダーをダウンロードします。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            操作に無効なステータス コードが返されるときにスローされます。
            </exception>
        <exception cref="T:System.Threading.Tasks.TaskCanceledException">
            操作の完了に時間がかかる場合、またはユーザーが明示的にキャンセルするとスローされます。
            </exception>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.InvalidMetadataException">
            再開のメタデータが壊れているか、現在の操作に関連付けられていない場合にスローされます。
            </exception>
        <exception cref="T:System.IO.FileNotFoundException">
            ソース パスが見つからない場合にスローされます。
            </exception>
        <exception cref="T:System.InvalidOperationException">
            無効なダウンロードを試行またはファイル/フォルダーは、操作中に外部で変更する場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.TransferFailedException">
            転送操作が失敗した場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetAclStatusWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.AclStatusResult&gt;&gt; GetAclStatusWithHttpMessagesAsync (string accountName, string path, Nullable&lt;bool&gt; tooId = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.AclStatusResult&gt;&gt; GetAclStatusWithHttpMessagesAsync(string accountName, string path, valuetype System.Nullable`1&lt;bool&gt; tooId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.GetAclStatusWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAclStatusWithHttpMessagesAsync : string * string * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.AclStatusResult&gt;&gt;" Usage="iFileSystemOperations.GetAclStatusWithHttpMessagesAsync (accountName, path, tooId, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.AclStatusResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="tooId" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') のファイルまたはディレクトリの ACL を取得します。
            </param>
        <param name="tooId">
            ACL エントリのオブジェクト ID の代わりにわかりやすい名前を返す省略可能なスイッチです。 tooid AAD のオブジェクト ID ではなく、false を返しますフレンドリ名を =。 既定値は true の場合、AAD のオブジェクト Id を取得します。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したファイルまたはディレクトリのアクセス制御リスト (ACL) エントリを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetContentSummaryWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.ContentSummaryResult&gt;&gt; GetContentSummaryWithHttpMessagesAsync (string accountName, string path, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.ContentSummaryResult&gt;&gt; GetContentSummaryWithHttpMessagesAsync(string accountName, string path, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.GetContentSummaryWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetContentSummaryWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.ContentSummaryResult&gt;&gt;" Usage="iFileSystemOperations.GetContentSummaryWithHttpMessagesAsync (accountName, path, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.ContentSummaryResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') の概要を取得する対象のファイルです。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ファイル パスで指定された、ファイルのコンテンツの集計オブジェクトを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetFileStatusWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileStatusResult&gt;&gt; GetFileStatusWithHttpMessagesAsync (string accountName, string path, Nullable&lt;bool&gt; tooId = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.FileStatusResult&gt;&gt; GetFileStatusWithHttpMessagesAsync(string accountName, string path, valuetype System.Nullable`1&lt;bool&gt; tooId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.GetFileStatusWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetFileStatusWithHttpMessagesAsync : string * string * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileStatusResult&gt;&gt;" Usage="iFileSystemOperations.GetFileStatusWithHttpMessagesAsync (accountName, path, tooId, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileStatusResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="tooId" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') のファイルまたは状態を取得する対象のディレクトリ。
            </param>
        <param name="tooId">
            所有者とグループの代わりにわかりやすい名前を返す省略可能なスイッチです。 tooid AAD のオブジェクト ID ではなく、false を返しますフレンドリ名を =。 既定値は true の場合、AAD のオブジェクト Id を取得します。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ファイルのパスで指定されたファイルの状態オブジェクトを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListFileStatusWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileStatusesResult&gt;&gt; ListFileStatusWithHttpMessagesAsync (string accountName, string path, Nullable&lt;int&gt; listSize = null, string listAfter = null, string listBefore = null, Nullable&lt;bool&gt; tooId = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.FileStatusesResult&gt;&gt; ListFileStatusWithHttpMessagesAsync(string accountName, string path, valuetype System.Nullable`1&lt;int32&gt; listSize, string listAfter, string listBefore, valuetype System.Nullable`1&lt;bool&gt; tooId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.ListFileStatusWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int32},System.String,System.String,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListFileStatusWithHttpMessagesAsync : string * string * Nullable&lt;int&gt; * string * string * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileStatusesResult&gt;&gt;" Usage="iFileSystemOperations.ListFileStatusWithHttpMessagesAsync (accountName, path, listSize, listAfter, listBefore, tooId, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileStatusesResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="listSize" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="listAfter" Type="System.String" />
        <Parameter Name="listBefore" Type="System.String" />
        <Parameter Name="tooId" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
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
            所有者とグループの代わりにわかりやすい名前を返す省略可能なスイッチです。 tooid AAD のオブジェクト ID ではなく、false を返しますフレンドリ名を =。 既定値は true の場合、AAD のオブジェクト Id を取得します。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            省略可能な改ページ調整パラメーターを使用して、ファイルのパスで指定されたファイルの状態オブジェクトの一覧を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MkdirsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;&gt; MkdirsWithHttpMessagesAsync (string accountName, string path, Nullable&lt;int&gt; permission = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;&gt; MkdirsWithHttpMessagesAsync(string accountName, string path, valuetype System.Nullable`1&lt;int32&gt; permission, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.MkdirsWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member MkdirsWithHttpMessagesAsync : string * string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;&gt;" Usage="iFileSystemOperations.MkdirsWithHttpMessagesAsync (accountName, path, permission, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="permission" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') を作成するディレクトリ。
            </param>
        <param name="permission">
            省略可能な 8 進数のアクセス許可のディレクトリの作成に使用する必要があります。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ディレクトリを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ModifyAclEntriesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; ModifyAclEntriesWithHttpMessagesAsync (string accountName, string path, string aclspec, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; ModifyAclEntriesWithHttpMessagesAsync(string accountName, string path, string aclspec, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.ModifyAclEntriesWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ModifyAclEntriesWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iFileSystemOperations.ModifyAclEntriesWithHttpMessagesAsync (accountName, path, aclspec, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclspec" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') のファイルまたはディレクトリが変更されている ACL を使用します。
            </param>
        <param name="aclspec">
            形式で、ACL の変更操作に含まれている ACL 仕様 ' [既定値:] ユーザー | グループ | その他の:: r |-w |-x |-'
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ファイルまたはフォルダーの既存のアクセス制御リスト (ACL) エントリを変更します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MsConcatWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; MsConcatWithHttpMessagesAsync (string accountName, string path, System.IO.Stream streamContents, Nullable&lt;bool&gt; deleteSourceDirectory = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; MsConcatWithHttpMessagesAsync(string accountName, string path, class System.IO.Stream streamContents, valuetype System.Nullable`1&lt;bool&gt; deleteSourceDirectory, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.MsConcatWithHttpMessagesAsync(System.String,System.String,System.IO.Stream,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member MsConcatWithHttpMessagesAsync : string * string * System.IO.Stream * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iFileSystemOperations.MsConcatWithHttpMessagesAsync (accountName, path, streamContents, deleteSourceDirectory, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="streamContents" Type="System.IO.Stream" />
        <Parameter Name="deleteSourceDirectory" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') の連結の結果として得られる出力先ファイルです。
            </param>
        <param name="streamContents">
            Data Lake Store パスの一覧 (以降で '/') のソース ファイルです。 形式でパスのコンマ区切りの一覧でなければなりません: sources=/file/path/1.txt,/file/path/2.txt,/file/path/lastfile.csv
            </param>
        <param name="deleteSourceDirectory">
            指定すると、最適化代わりに各個々 のソース ストリームを削除するには、フォルダーを削除、ソース ストリーム場合は代わりに、同じフォルダーにすべてのストリーム。 これは、結果、フォルダー内のみのストリームが連結操作の一部とパフォーマンスが大幅に改善します。 警告: ソース ファイルではないその他のファイルの削除が含まれます。
            ソース ファイルがソース ディレクトリのファイルのみの場合は true にのみ設定します。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            出力先ファイル、成功時にすべてのソース ファイルを削除するのには、ソース ファイルのリストを連結します。 このメソッドは、Concat メソッドよりも多くのソース ファイルのパスを受け取ります。 このメソッドと、受け取るパラメーターは、使いやすさ、今後のバージョンでの変更の対象はします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="OpenWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.IO.Stream&gt;&gt; OpenWithHttpMessagesAsync (string accountName, string path, Nullable&lt;long&gt; length = null, Nullable&lt;long&gt; offset = null, Nullable&lt;Guid&gt; fileSessionId = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.IO.Stream&gt;&gt; OpenWithHttpMessagesAsync(string accountName, string path, valuetype System.Nullable`1&lt;int64&gt; length, valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; fileSessionId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.OpenWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Guid},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OpenWithHttpMessagesAsync : string * string * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;Guid&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.IO.Stream&gt;&gt;" Usage="iFileSystemOperations.OpenWithHttpMessagesAsync (accountName, path, length, offset, fileSessionId, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.IO.Stream&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="length" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="fileSessionId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
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
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            開き、指定したファイルから読み取ります。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="PathExistsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;bool&gt;&gt; PathExistsWithHttpMessagesAsync (string accountName, string getFilePath, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;bool&gt;&gt; PathExistsWithHttpMessagesAsync(string accountName, string getFilePath, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.PathExistsWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PathExistsWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;bool&gt;&gt;" Usage="iFileSystemOperations.PathExistsWithHttpMessagesAsync (accountName, getFilePath, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Boolean&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="getFilePath" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="getFilePath">
            Data Lake Store のパス (以降で '/') のファイルまたはテスト対象のディレクトリ。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ファイル パスで指定されたファイルまたはディレクトリ オブジェクトの存在をテストします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="RemoveAclEntriesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; RemoveAclEntriesWithHttpMessagesAsync (string accountName, string path, string aclspec, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; RemoveAclEntriesWithHttpMessagesAsync(string accountName, string path, string aclspec, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.RemoveAclEntriesWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RemoveAclEntriesWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iFileSystemOperations.RemoveAclEntriesWithHttpMessagesAsync (accountName, path, aclspec, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclspec" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') のファイルまたはディレクトリ ACL を削除します。
            </param>
        <param name="aclspec">
            形式で、ACL の削除操作に含まれている ACL spec ' [既定値:] ユーザー | グループ | その他の '
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            既存のファイルまたはフォルダーのアクセス制御リスト (ACL) エントリを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveAclWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; RemoveAclWithHttpMessagesAsync (string accountName, string path, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; RemoveAclWithHttpMessagesAsync(string accountName, string path, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.RemoveAclWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RemoveAclWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iFileSystemOperations.RemoveAclWithHttpMessagesAsync (accountName, path, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') のファイルまたはディレクトリ ACL を削除します。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したファイルまたはディレクトリの既存のアクセス制御リスト (ACL) を削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveDefaultAclWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; RemoveDefaultAclWithHttpMessagesAsync (string accountName, string path, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; RemoveDefaultAclWithHttpMessagesAsync(string accountName, string path, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.RemoveDefaultAclWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RemoveDefaultAclWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iFileSystemOperations.RemoveDefaultAclWithHttpMessagesAsync (accountName, path, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') の既定の ACL が削除されると同じディレクトリにします。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            既存既定のアクセス制御リスト (ACL) の指定されたディレクトリを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RenameWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;&gt; RenameWithHttpMessagesAsync (string accountName, string path, string destination, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;&gt; RenameWithHttpMessagesAsync(string accountName, string path, string destination, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.RenameWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RenameWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;&gt;" Usage="iFileSystemOperations.RenameWithHttpMessagesAsync (accountName, path, destination, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="destination" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') のファイルまたはディレクトリに移動または名前変更します。
            </param>
        <param name="destination">
            移動または名前変更、ファイルまたはフォルダーへのパス
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ファイルまたはディレクトリの名前を変更します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="SetAclWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; SetAclWithHttpMessagesAsync (string accountName, string path, string aclspec, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; SetAclWithHttpMessagesAsync(string accountName, string path, string aclspec, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.SetAclWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetAclWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iFileSystemOperations.SetAclWithHttpMessagesAsync (accountName, path, aclspec, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclspec" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') のファイルまたはディレクトリの ACL を設定します。
            </param>
        <param name="aclspec">
            形式で ACL を作成する操作に含まれる ACL spec ' [既定値:] ユーザー | グループ | その他の:: r |-w |-x |-'
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ファイルまたはフォルダーのアクセス制御リスト (ACL) を設定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="SetFileExpiryWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; SetFileExpiryWithHttpMessagesAsync (string accountName, string path, Microsoft.Azure.Management.DataLake.Store.Models.ExpiryOptionType expiryOption, Nullable&lt;long&gt; expireTime = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; SetFileExpiryWithHttpMessagesAsync(string accountName, string path, valuetype Microsoft.Azure.Management.DataLake.Store.Models.ExpiryOptionType expiryOption, valuetype System.Nullable`1&lt;int64&gt; expireTime, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.SetFileExpiryWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.DataLake.Store.Models.ExpiryOptionType,System.Nullable{System.Int64},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetFileExpiryWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.DataLake.Store.Models.ExpiryOptionType * Nullable&lt;int64&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iFileSystemOperations.SetFileExpiryWithHttpMessagesAsync (accountName, path, expiryOption, expireTime, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="expiryOption" Type="Microsoft.Azure.Management.DataLake.Store.Models.ExpiryOptionType" />
        <Parameter Name="expireTime" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') を設定するか、有効期限を削除するファイルのです。
            </param>
        <param name="expiryOption">
            ファイルを使用する有効期限の種類を示します。 1。
            NeverExpire: ExpireTime は無視されます。 2. RelativeToNow: ExpireTime は、ファイルの有効期限が更新されたときに、基準に有効期限の日付を表すミリ秒の整数です。 手順 3.
            RelativeToCreationDate: ExpireTime は、ファイルの作成の基準とした有効期限の日付を表すミリ秒の整数です。 4.
            絶対値: ExpireTime 整数です (ミリ秒単位) の 1970 年 1 月 1 基準とした Unix タイムスタンプとして 00時 00分: 00 です。 使用可能な値が含まれます: 'NeverExpire'、'RelativeToNow'、'RelativeToCreationDate'、'Absolute'
            </param>
        <param name="expireTime">
            ファイルは、有効期限が設定された ExpiryOption に対応する時間。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            設定または指定したファイルに有効期限を削除します。 この操作は、ファイルに対してのみ実行できます。 フォルダーを指定することはできません。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="SetOwnerWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; SetOwnerWithHttpMessagesAsync (string accountName, string path, string owner = null, string group = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; SetOwnerWithHttpMessagesAsync(string accountName, string path, string owner, string group, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.SetOwnerWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetOwnerWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iFileSystemOperations.SetOwnerWithHttpMessagesAsync (accountName, path, owner, group, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="owner" Type="System.String" />
        <Parameter Name="group" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
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
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ファイルまたはディレクトリの所有者を設定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="SetPermissionWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; SetPermissionWithHttpMessagesAsync (string accountName, string path, string permission = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; SetPermissionWithHttpMessagesAsync(string accountName, string path, string permission, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.SetPermissionWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetPermissionWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iFileSystemOperations.SetPermissionWithHttpMessagesAsync (accountName, path, permission, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="permission" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="path">
            Data Lake Store のパス (以降で '/') のファイルまたはアクセス許可を設定する対象のディレクトリ。
            </param>
        <param name="permission">
            (つまり、アクセス許可の文字列表現 rwx')。 空の場合、このプロパティは変更されません。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ファイルまたはフォルダーのアクセス許可を設定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UploadFile">
      <MemberSignature Language="C#" Value="public void UploadFile (string accountName, string sourcePath, string destinationPath, int threadCount = -1, bool resume = false, bool overwrite = false, bool uploadAsBinary = false, IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferProgress&gt; progressTracker = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void UploadFile(string accountName, string sourcePath, string destinationPath, int32 threadCount, bool resume, bool overwrite, bool uploadAsBinary, class System.IProgress`1&lt;class Microsoft.Azure.Management.DataLake.Store.TransferProgress&gt; progressTracker, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.UploadFile(System.String,System.String,System.String,System.Int32,System.Boolean,System.Boolean,System.Boolean,System.IProgress{Microsoft.Azure.Management.DataLake.Store.TransferProgress},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFile : string * string * string * int * bool * bool * bool * IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferProgress&gt; * System.Threading.CancellationToken -&gt; unit" Usage="iFileSystemOperations.UploadFile (accountName, sourcePath, destinationPath, threadCount, resume, overwrite, uploadAsBinary, progressTracker, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="sourcePath" Type="System.String" />
        <Parameter Name="destinationPath" Type="System.String" />
        <Parameter Name="threadCount" Type="System.Int32" />
        <Parameter Name="resume" Type="System.Boolean" />
        <Parameter Name="overwrite" Type="System.Boolean" />
        <Parameter Name="uploadAsBinary" Type="System.Boolean" />
        <Parameter Name="progressTracker" Type="System.IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferProgress&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="sourcePath">
            Data Lake Store アカウントにアップロードするローカル ソース ファイルです。
            </param>
        <param name="destinationPath">
            Data Lake Store のパス (以降で '/')、ディレクトリまたはディレクトリとファイル名にアップロードするのです。
            </param>
        <param name="threadCount">
            アップロード中に使用するスレッドの最大数。 既定では、この番号はに基づいて計算ファイルのサイズ。
            </param>
        <param name="resume">
            このアップロードが、障害が発生した以前のアップロードの継続タスクであることを示すスイッチです。 既定値は false です。
            </param>
        <param name="overwrite">
            このアップロードを示すスイッチは、存在する場合、ターゲット ファイルを上書きします。 既定値は false に設定し、アップロードは高速なフェールオーバー ターゲット ファイルが存在する場合。
            </param>
        <param name="uploadAsBinary">
            このアップロードを示すスイッチは、パフォーマンスは多少向上レコード境界の整合性は保証されませんがバイナリとしてファイルを扱う必要があります。
            </param>
        <param name="progressTracker">
            非同期的にアップロード操作の進行状況を追跡するために使用できる省略可能なデリゲート。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された Data Lake Store アカウントにファイルをアップロードします。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            操作に無効なステータス コードが返されるときにスローされます。
            </exception>
        <exception cref="T:System.Threading.Tasks.TaskCanceledException">
            操作の完了に時間がかかる場合、またはユーザーが明示的にキャンセルするとスローされます。
            </exception>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.InvalidMetadataException">
            再開のメタデータが壊れているか、現在の操作に関連付けられていない場合にスローされます。
            </exception>
        <exception cref="T:System.IO.FileNotFoundException">
            ソース パスが見つからない場合にスローされます。
            </exception>
        <exception cref="T:System.InvalidOperationException">
            無効なアップロードの試行または操作中に、ファイルが外部で変更された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.TransferFailedException">
            転送操作が失敗した場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UploadFolder">
      <MemberSignature Language="C#" Value="public void UploadFolder (string accountName, string sourcePath, string destinationPath, int perFileThreadCount = -1, int concurrentFileCount = -1, bool resume = false, bool overwrite = false, bool uploadAsBinary = false, bool recurse = false, IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress&gt; progressTracker = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void UploadFolder(string accountName, string sourcePath, string destinationPath, int32 perFileThreadCount, int32 concurrentFileCount, bool resume, bool overwrite, bool uploadAsBinary, bool recurse, class System.IProgress`1&lt;class Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress&gt; progressTracker, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.UploadFolder(System.String,System.String,System.String,System.Int32,System.Int32,System.Boolean,System.Boolean,System.Boolean,System.Boolean,System.IProgress{Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFolder : string * string * string * int * int * bool * bool * bool * bool * IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress&gt; * System.Threading.CancellationToken -&gt; unit" Usage="iFileSystemOperations.UploadFolder (accountName, sourcePath, destinationPath, perFileThreadCount, concurrentFileCount, resume, overwrite, uploadAsBinary, recurse, progressTracker, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="sourcePath" Type="System.String" />
        <Parameter Name="destinationPath" Type="System.String" />
        <Parameter Name="perFileThreadCount" Type="System.Int32" />
        <Parameter Name="concurrentFileCount" Type="System.Int32" />
        <Parameter Name="resume" Type="System.Boolean" />
        <Parameter Name="overwrite" Type="System.Boolean" />
        <Parameter Name="uploadAsBinary" Type="System.Boolean" />
        <Parameter Name="recurse" Type="System.Boolean" />
        <Parameter Name="progressTracker" Type="System.IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            ファイル システム操作を実行する Azure Data Lake Store アカウント。
            </param>
        <param name="sourcePath">
            Data Lake Store アカウントにアップロードするローカル ソース フォルダーです。
            </param>
        <param name="destinationPath">
            Data Lake Store のパス (以降で '/') にアップロードするディレクトリ。
            </param>
        <param name="perFileThreadCount">
            アップロード中にファイルごとに使用するスレッドの最大数。 既定では、この番号はに基づいて計算フォルダー構造と平均ファイルのサイズ。
            </param>
        <param name="concurrentFileCount">
            一度にアップロードするファイルの最大数。 既定では、この番号はに基づいて計算のフォルダー構造およびファイルの数。
            </param>
        <param name="resume">
            このアップロードが、障害が発生した以前のアップロードの継続タスクであることを示すスイッチです。 既定値は false です。
            </param>
        <param name="overwrite">
            存在する場合、このアップロードを示すスイッチはターゲット ディレクトリの内容を上書きする必要があります。 既定値は false に設定し、アップロードは高速なフェールオーバー ターゲットの場所が存在する場合。
            </param>
        <param name="uploadAsBinary">
            このアップロードを示すスイッチは、パフォーマンスは多少向上レコード境界の整合性は保証されませんがバイナリとしてすべてのデータを扱う必要があります。 これは混合のバイナリとテキスト ファイルまたはバイナリのみのディレクトリのサイズの大きいフォルダーをお勧めします。 既定値は false
            </param>
        <param name="recurse">
            このアップロードを示すスイッチには、ソース ディレクトリを再帰的にまたは最上位レベルだけをアップロードする必要があります。 既定値は false の場合、最上位レベルだけがアップロードされるようにします。
            </param>
        <param name="progressTracker">
            非同期的にアップロード操作の進行状況を追跡するために使用できる省略可能なデリゲート。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された Data Lake Store アカウントにフォルダーをアップロードします。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            操作に無効なステータス コードが返されるときにスローされます。
            </exception>
        <exception cref="T:System.Threading.Tasks.TaskCanceledException">
            操作の完了に時間がかかる場合、またはユーザーが明示的にキャンセルするとスローされます。
            </exception>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.InvalidMetadataException">
            再開のメタデータが壊れているか、現在の操作に関連付けられていない場合にスローされます。
            </exception>
        <exception cref="T:System.IO.FileNotFoundException">
            ソース パスが見つからない場合にスローされます。
            </exception>
        <exception cref="T:System.InvalidOperationException">
            無効なアップロードしようとすると、またはファイル/フォルダーが操作中に外部から変更されたがスローされます。
            </exception>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.TransferFailedException">
            転送操作が失敗した場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>