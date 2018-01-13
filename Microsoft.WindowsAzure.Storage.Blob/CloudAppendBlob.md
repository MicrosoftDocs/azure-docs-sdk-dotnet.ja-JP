<Type Name="CloudAppendBlob" FullName="Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob">
  <TypeSignature Language="C#" Value="public class CloudAppendBlob : Microsoft.WindowsAzure.Storage.Blob.CloudBlob, Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CloudAppendBlob extends Microsoft.WindowsAzure.Storage.Blob.CloudBlob implements class Microsoft.WindowsAzure.Storage.Blob.ICloudBlob, class Microsoft.WindowsAzure.Storage.Blob.IListBlobItem" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" />
  <TypeSignature Language="VB.NET" Value="Public Class CloudAppendBlob&#xA;Inherits CloudBlob&#xA;Implements ICloudBlob" />
  <TypeSignature Language="F#" Value="type CloudAppendBlob = class&#xA;    inherit CloudBlob&#xA;    interface ICloudBlob&#xA;    interface IListBlobItem" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.WindowsAzure.Storage.Blob.CloudBlob</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.WindowsAzure.Storage.Blob.ICloudBlob</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            追加 blob、ブロックのデータを常に、blob の最後にコミットする blob の種類を表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudAppendBlob (Uri blobAbsoluteUri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri blobAbsoluteUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.#ctor(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (blobAbsoluteUri As Uri)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob : Uri -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" Usage="new Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob blobAbsoluteUri" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="blobAbsoluteUri" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="blobAbsoluteUri">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" />クラス blob への絶対 URI を使用します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudAppendBlob (Uri blobAbsoluteUri, Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri blobAbsoluteUri, class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.#ctor(System.Uri,Microsoft.WindowsAzure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (blobAbsoluteUri As Uri, credentials As StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob : Uri * Microsoft.WindowsAzure.Storage.Auth.StorageCredentials -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" Usage="new Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob (blobAbsoluteUri, credentials)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="blobAbsoluteUri" Type="System.Uri" />
        <Parameter Name="credentials" Type="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />
      </Parameters>
      <Docs>
        <param name="blobAbsoluteUri">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</param>
        <param name="credentials"><see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> オブジェクト。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" />クラス blob への絶対 URI を使用します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudAppendBlob (Microsoft.WindowsAzure.Storage.StorageUri blobAbsoluteUri, Nullable&lt;DateTimeOffset&gt; snapshotTime, Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.StorageUri blobAbsoluteUri, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshotTime, class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.#ctor(Microsoft.WindowsAzure.Storage.StorageUri,System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (blobAbsoluteUri As StorageUri, snapshotTime As Nullable(Of DateTimeOffset), credentials As StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob : Microsoft.WindowsAzure.Storage.StorageUri * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.Auth.StorageCredentials -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" Usage="new Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob (blobAbsoluteUri, snapshotTime, credentials)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="blobAbsoluteUri" Type="Microsoft.WindowsAzure.Storage.StorageUri" />
        <Parameter Name="snapshotTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="credentials" Type="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />
      </Parameters>
      <Docs>
        <param name="blobAbsoluteUri">A<see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" />プライマリとセカンダリの両方の場所にある blob を絶対 URI を格納します。</param>
        <param name="snapshotTime">A <see cref="T:System.DateTimeOffset" /> blob がスナップショットの場合、スナップショットのタイムスタンプを指定します。</param>
        <param name="credentials"><see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> オブジェクト。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" />クラス blob への絶対 URI を使用します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudAppendBlob (Uri blobAbsoluteUri, Nullable&lt;DateTimeOffset&gt; snapshotTime, Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri blobAbsoluteUri, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshotTime, class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.#ctor(System.Uri,System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (blobAbsoluteUri As Uri, snapshotTime As Nullable(Of DateTimeOffset), credentials As StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob : Uri * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.Auth.StorageCredentials -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" Usage="new Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob (blobAbsoluteUri, snapshotTime, credentials)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="blobAbsoluteUri" Type="System.Uri" />
        <Parameter Name="snapshotTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="credentials" Type="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />
      </Parameters>
      <Docs>
        <param name="blobAbsoluteUri">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</param>
        <param name="snapshotTime">A <see cref="T:System.DateTimeOffset" /> blob がスナップショットの場合、スナップショットのタイムスタンプを指定します。</param>
        <param name="credentials"><see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> オブジェクト。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" />クラス blob への絶対 URI を使用します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppendBlock">
      <MemberSignature Language="C#" Value="public virtual long AppendBlock (System.IO.Stream blockData, string contentMD5 = null, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int64 AppendBlock(class System.IO.Stream blockData, string contentMD5, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendBlock(System.IO.Stream,System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member AppendBlock : System.IO.Stream * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; int64&#xA;override this.AppendBlock : System.IO.Stream * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; int64" Usage="cloudAppendBlob.AppendBlock (blockData, contentMD5, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blockData" Type="System.IO.Stream" />
        <Parameter Name="contentMD5" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="blockData">A<see cref="T:System.IO.Stream" />ブロックのデータを提供するオブジェクト。</param>
        <param name="contentMD5">ブロックのトランザクションの整合性を確保するために使用する省略可能なハッシュ値です。 あります<c>null</c>または空の文字列。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。 場合<c>null</c>既定のオプションは、要求に適用されます。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            Blob の末尾に新しいデータのブロックをコミットします。
            </summary>
        <returns>オフセット、ブロックが追加されました。</returns>
        <remarks>
            クライアントは、ネットワーク上でトランザクションの整合性を確保するための手段として特定の Append Block 操作に関して content-md5 ヘッダーを送信できます。 <paramref name="contentMD5" />パラメーターにより、クライアントは、指定したバイトの範囲に提供することを事前に計算された MD5 値へのアクセスを既に持っています。
            場合、<see cref="P:BlobRequestOptions.UseTransactionalMd5" />プロパティに設定されている<c>true</c>と<paramref name="contentMD5" />にパラメーターが設定されている<c>null</c>、クライアント ライブラリが MD5 値を内部で計算し、します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AppendBlockAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;long&gt; AppendBlockAsync (System.IO.Stream blockData, string contentMD5 = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;int64&gt; AppendBlockAsync(class System.IO.Stream blockData, string contentMD5) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendBlockAsync(System.IO.Stream,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function AppendBlockAsync (blockData As Stream, Optional contentMD5 As String = null) As Task(Of Long)" />
      <MemberSignature Language="F#" Value="abstract member AppendBlockAsync : System.IO.Stream * string -&gt; System.Threading.Tasks.Task&lt;int64&gt;&#xA;override this.AppendBlockAsync : System.IO.Stream * string -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="cloudAppendBlob.AppendBlockAsync (blockData, contentMD5)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blockData" Type="System.IO.Stream" />
        <Parameter Name="contentMD5" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="blockData">A<see cref="T:System.IO.Stream" />ブロックのデータを提供するオブジェクト。</param>
        <param name="contentMD5">ブロックのトランザクションの整合性を確保するために使用する省略可能なハッシュ値です。 あります<c>null</c>または空の文字列。</param>
        <summary>
            Blob の末尾に新しいデータのブロックをコミットする非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            クライアントは、ネットワーク上でトランザクションの整合性を確保するための手段として特定の Append Block 操作に関して content-md5 ヘッダーを送信できます。 <paramref name="contentMD5" />パラメーターにより、クライアントは、指定したバイトの範囲に提供することを事前に計算された MD5 値へのアクセスを既に持っています。
            場合、<see cref="P:BlobRequestOptions.UseTransactionalMd5" />プロパティに設定されている<c>true</c>と<paramref name="contentMD5" />にパラメーターが設定されている<c>null</c>、クライアント ライブラリが MD5 値を内部で計算し、します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AppendBlockAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;long&gt; AppendBlockAsync (System.IO.Stream blockData, string contentMD5, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;int64&gt; AppendBlockAsync(class System.IO.Stream blockData, string contentMD5, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendBlockAsync(System.IO.Stream,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AppendBlockAsync : System.IO.Stream * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int64&gt;&#xA;override this.AppendBlockAsync : System.IO.Stream * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="cloudAppendBlob.AppendBlockAsync (blockData, contentMD5, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blockData" Type="System.IO.Stream" />
        <Parameter Name="contentMD5" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="blockData">A<see cref="T:System.IO.Stream" />ブロックのデータを提供するオブジェクト。</param>
        <param name="contentMD5">ブロックのトランザクションの整合性を確保するために使用する省略可能なハッシュ値です。 あります<c>null</c>または空の文字列。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            Blob の末尾に新しいデータのブロックをコミットする非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            クライアントは、ネットワーク上でトランザクションの整合性を確保するための手段として特定のブロックの配置操作に関して content-md5 ヘッダーを送信することがあります。 <paramref name="contentMD5" />パラメーターにより、クライアントは、指定したバイトの範囲に提供することを事前に計算された MD5 値へのアクセスを既に持っています。
            場合、<see cref="P:BlobRequestOptions.UseTransactionalMd5" />プロパティに設定されている<c>true</c>と<paramref name="contentMD5" />にパラメーターが設定されている<c>null</c>、クライアント ライブラリが MD5 値を内部で計算し、します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AppendBlockAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;long&gt; AppendBlockAsync (System.IO.Stream blockData, string contentMD5, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;int64&gt; AppendBlockAsync(class System.IO.Stream blockData, string contentMD5, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendBlockAsync(System.IO.Stream,System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member AppendBlockAsync : System.IO.Stream * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;int64&gt;&#xA;override this.AppendBlockAsync : System.IO.Stream * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="cloudAppendBlob.AppendBlockAsync (blockData, contentMD5, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blockData" Type="System.IO.Stream" />
        <Parameter Name="contentMD5" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="blockData">A<see cref="T:System.IO.Stream" />ブロックのデータを提供するオブジェクト。</param>
        <param name="contentMD5">ブロックのトランザクションの整合性を確保するために使用する省略可能なハッシュ値です。 あります<c>null</c>または空の文字列。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            Blob の末尾に新しいデータのブロックをコミットする非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            クライアントは、ネットワーク上でトランザクションの整合性を確保するための手段として特定の Append Block 操作に関して content-md5 ヘッダーを送信できます。 <paramref name="contentMD5" />パラメーターにより、クライアントは、指定したバイトの範囲に提供することを事前に計算された MD5 値へのアクセスを既に持っています。
            場合、<see cref="P:BlobRequestOptions.UseTransactionalMd5" />プロパティに設定されている<c>true</c>と<paramref name="contentMD5" />にパラメーターが設定されている<c>null</c>、クライアント ライブラリが MD5 値を内部で計算し、します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AppendBlockAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;long&gt; AppendBlockAsync (System.IO.Stream blockData, string contentMD5, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;int64&gt; AppendBlockAsync(class System.IO.Stream blockData, string contentMD5, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendBlockAsync(System.IO.Stream,System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AppendBlockAsync : System.IO.Stream * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int64&gt;&#xA;override this.AppendBlockAsync : System.IO.Stream * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="cloudAppendBlob.AppendBlockAsync (blockData, contentMD5, accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blockData" Type="System.IO.Stream" />
        <Parameter Name="contentMD5" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="blockData">A<see cref="T:System.IO.Stream" />ブロックのデータを提供するオブジェクト。</param>
        <param name="contentMD5">ブロックのトランザクションの整合性を確保するために使用する省略可能なハッシュ値です。 あります<c>null</c>または空の文字列。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            Blob の末尾に新しいデータのブロックをコミットする非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            クライアントは、ネットワーク上でトランザクションの整合性を確保するための手段として特定の Append Block 操作に関して content-md5 ヘッダーを送信できます。 <paramref name="contentMD5" />パラメーターにより、クライアントは、指定したバイトの範囲に提供することを事前に計算された MD5 値へのアクセスを既に持っています。
            場合、<see cref="P:BlobRequestOptions.UseTransactionalMd5" />プロパティに設定されている<c>true</c>と<paramref name="contentMD5" />にパラメーターが設定されている<c>null</c>、クライアント ライブラリが MD5 値を内部で計算し、します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AppendBlockAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;long&gt; AppendBlockAsync (System.IO.Stream blockData, string contentMD5, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;int64&gt; AppendBlockAsync(class System.IO.Stream blockData, string contentMD5, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.IProgress`1&lt;class Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendBlockAsync(System.IO.Stream,System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.IProgress{Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AppendBlockAsync : System.IO.Stream * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int64&gt;&#xA;override this.AppendBlockAsync : System.IO.Stream * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="cloudAppendBlob.AppendBlockAsync (blockData, contentMD5, accessCondition, options, operationContext, progressHandler, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blockData" Type="System.IO.Stream" />
        <Parameter Name="contentMD5" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="progressHandler" Type="System.IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="blockData">A<see cref="T:System.IO.Stream" />ブロックのデータを提供するオブジェクト。</param>
        <param name="contentMD5">ブロックのトランザクションの整合性を確保するために使用する省略可能なハッシュ値です。 あります<c>null</c>または空の文字列。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="progressHandler"> A<see cref="T:System.IProgress`1" />を処理するオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" />メッセージ。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            Blob の末尾に新しいデータのブロックをコミットする非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            クライアントは、ネットワーク上でトランザクションの整合性を確保するための手段として特定の Append Block 操作に関して content-md5 ヘッダーを送信できます。 <paramref name="contentMD5" />パラメーターにより、クライアントは、指定したバイトの範囲に提供することを事前に計算された MD5 値へのアクセスを既に持っています。
            場合、<see cref="P:BlobRequestOptions.UseTransactionalMd5" />プロパティに設定されている<c>true</c>と<paramref name="contentMD5" />にパラメーターが設定されている<c>null</c>、クライアント ライブラリが MD5 値を内部で計算し、します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AppendFromByteArray">
      <MemberSignature Language="C#" Value="public virtual void AppendFromByteArray (byte[] buffer, int index, int count, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void AppendFromByteArray(unsigned int8[] buffer, int32 index, int32 count, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromByteArray(System.Byte[],System.Int32,System.Int32,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member AppendFromByteArray : byte[] * int * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.AppendFromByteArray : byte[] * int * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudAppendBlob.AppendFromByteArray (buffer, index, count, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="buffer" Type="System.Byte[]" />
        <Parameter Name="index" Type="System.Int32" />
        <Parameter Name="count" Type="System.Int32" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="buffer">バイト配列。</param>
        <param name="index">Blob のバイトのアップロードを開始位置を示すバッファー内の 0 から始まるバイト オフセット。</param>
        <param name="count">Blob に書き込まれるバイト数。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。 場合<c>null</c>既定のオプションは、要求に適用されます。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            追加 blob をバイト配列の内容を追加します。単一ライターのシナリオでのみ推奨されます。
            </summary>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。        
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AppendFromByteArrayAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task AppendFromByteArrayAsync (byte[] buffer, int index, int count);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AppendFromByteArrayAsync(unsigned int8[] buffer, int32 index, int32 count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromByteArrayAsync(System.Byte[],System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function AppendFromByteArrayAsync (buffer As Byte(), index As Integer, count As Integer) As Task" />
      <MemberSignature Language="F#" Value="abstract member AppendFromByteArrayAsync : byte[] * int * int -&gt; System.Threading.Tasks.Task&#xA;override this.AppendFromByteArrayAsync : byte[] * int * int -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.AppendFromByteArrayAsync (buffer, index, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="buffer" Type="System.Byte[]" />
        <Parameter Name="index" Type="System.Int32" />
        <Parameter Name="count" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="buffer">バイト配列。</param>
        <param name="index">Blob のバイトのアップロードを開始位置を示すバッファー内の 0 から始まるバイト オフセット。</param>
        <param name="count">Blob に書き込まれるバイト数。</param>
        <summary>
            追加 blob にバイト配列の内容を追加する非同期操作を開始します。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。        
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AppendFromByteArrayAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task AppendFromByteArrayAsync (byte[] buffer, int index, int count, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AppendFromByteArrayAsync(unsigned int8[] buffer, int32 index, int32 count, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromByteArrayAsync(System.Byte[],System.Int32,System.Int32,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AppendFromByteArrayAsync : byte[] * int * int * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.AppendFromByteArrayAsync : byte[] * int * int * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.AppendFromByteArrayAsync (buffer, index, count, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="buffer" Type="System.Byte[]" />
        <Parameter Name="index" Type="System.Int32" />
        <Parameter Name="count" Type="System.Int32" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="buffer">バイト配列。</param>
        <param name="index">Blob のバイトのアップロードを開始位置を示すバッファー内の 0 から始まるバイト オフセット。</param>
        <param name="count">Blob に書き込まれるバイト数。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            追加 blob にバイト配列の内容を追加する非同期操作を開始します。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。        
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AppendFromByteArrayAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task AppendFromByteArrayAsync (byte[] buffer, int index, int count, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AppendFromByteArrayAsync(unsigned int8[] buffer, int32 index, int32 count, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromByteArrayAsync(System.Byte[],System.Int32,System.Int32,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member AppendFromByteArrayAsync : byte[] * int * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.AppendFromByteArrayAsync : byte[] * int * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.AppendFromByteArrayAsync (buffer, index, count, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="buffer" Type="System.Byte[]" />
        <Parameter Name="index" Type="System.Int32" />
        <Parameter Name="count" Type="System.Int32" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="buffer">バイト配列。</param>
        <param name="index">Blob のバイトのアップロードを開始位置を示すバッファー内の 0 から始まるバイト オフセット。</param>
        <param name="count">Blob に書き込まれるバイト数。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            追加 blob にバイト配列の内容を追加する非同期操作を開始します。この API は、API は内部的に複数のライターのシナリオでは機能しませんが、重複するブロックを回避する追加オフセット条件ヘッダーを使用するため、単一ライターのシナリオで厳密に使用する必要があります。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AppendFromByteArrayAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task AppendFromByteArrayAsync (byte[] buffer, int index, int count, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AppendFromByteArrayAsync(unsigned int8[] buffer, int32 index, int32 count, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromByteArrayAsync(System.Byte[],System.Int32,System.Int32,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AppendFromByteArrayAsync : byte[] * int * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.AppendFromByteArrayAsync : byte[] * int * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.AppendFromByteArrayAsync (buffer, index, count, accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="buffer" Type="System.Byte[]" />
        <Parameter Name="index" Type="System.Int32" />
        <Parameter Name="count" Type="System.Int32" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="buffer">バイト配列。</param>
        <param name="index">Blob のバイトのアップロードを開始位置を示すバッファー内の 0 から始まるバイト オフセット。</param>
        <param name="count">Blob に書き込まれるバイト数。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            バイト配列の内容を追加 blob にアップロードする非同期操作を開始します。この API は、API は内部的に複数のライターのシナリオでは機能しませんが、重複するブロックを回避する追加オフセット条件ヘッダーを使用するため、単一ライターのシナリオで厳密に使用する必要があります。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AppendFromByteArrayAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task AppendFromByteArrayAsync (byte[] buffer, int index, int count, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AppendFromByteArrayAsync(unsigned int8[] buffer, int32 index, int32 count, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.IProgress`1&lt;class Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromByteArrayAsync(System.Byte[],System.Int32,System.Int32,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.IProgress{Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AppendFromByteArrayAsync : byte[] * int * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.AppendFromByteArrayAsync : byte[] * int * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.AppendFromByteArrayAsync (buffer, index, count, accessCondition, options, operationContext, progressHandler, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="buffer" Type="System.Byte[]" />
        <Parameter Name="index" Type="System.Int32" />
        <Parameter Name="count" Type="System.Int32" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="progressHandler" Type="System.IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="buffer">バイト配列。</param>
        <param name="index">Blob のバイトのアップロードを開始位置を示すバッファー内の 0 から始まるバイト オフセット。</param>
        <param name="count">Blob に書き込まれるバイト数。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="progressHandler"> A<see cref="T:System.IProgress`1" />を処理するオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" />メッセージ。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            バイト配列の内容を追加 blob にアップロードする非同期操作を開始します。この API は、API は内部的に複数のライターのシナリオでは機能しませんが、重複するブロックを回避する追加オフセット条件ヘッダーを使用するため、単一ライターのシナリオで厳密に使用する必要があります。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AppendFromFile">
      <MemberSignature Language="C#" Value="public virtual void AppendFromFile (string path, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void AppendFromFile(string path, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromFile(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member AppendFromFile : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.AppendFromFile : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudAppendBlob.AppendFromFile (path, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="path">Blob コンテンツを提供するファイルのパスを含む文字列。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。 場合<c>null</c>既定のオプションは、要求に適用されます。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            追加 blob にファイルを追加します。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。        
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AppendFromFileAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task AppendFromFileAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AppendFromFileAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromFileAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function AppendFromFileAsync (path As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member AppendFromFileAsync : string -&gt; System.Threading.Tasks.Task&#xA;override this.AppendFromFileAsync : string -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.AppendFromFileAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Blob コンテンツを提供するファイルのパスを含む文字列。</param>
        <summary>
            追加 blob にファイルを追加する非同期操作を開始します。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。        
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AppendFromFileAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task AppendFromFileAsync (string path, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AppendFromFileAsync(string path, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromFileAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AppendFromFileAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.AppendFromFileAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.AppendFromFileAsync (path, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">Blob コンテンツを提供するファイルのパスを含む文字列。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            追加 blob にファイルを追加する非同期操作を開始します。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。        
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AppendFromFileAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task AppendFromFileAsync (string path, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AppendFromFileAsync(string path, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromFileAsync(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member AppendFromFileAsync : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.AppendFromFileAsync : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.AppendFromFileAsync (path, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="path">Blob コンテンツを提供するファイルのパスを含む文字列。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            追加 blob にファイルを追加する非同期操作を開始します。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。        
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AppendFromFileAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task AppendFromFileAsync (string path, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AppendFromFileAsync(string path, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromFileAsync(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AppendFromFileAsync : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.AppendFromFileAsync : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.AppendFromFileAsync (path, accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">Blob コンテンツを提供するファイルのパスを含む文字列。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            追加 blob にファイルを追加する非同期操作を開始します。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。        
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AppendFromFileAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task AppendFromFileAsync (string path, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AppendFromFileAsync(string path, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.IProgress`1&lt;class Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromFileAsync(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.IProgress{Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AppendFromFileAsync : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.AppendFromFileAsync : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.AppendFromFileAsync (path, accessCondition, options, operationContext, progressHandler, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="progressHandler" Type="System.IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">Blob コンテンツを提供するファイルのパスを含む文字列。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="progressHandler"> A<see cref="T:System.IProgress`1" />を処理するオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" />メッセージ。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            追加 blob にファイルを追加する非同期操作を開始します。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。        
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AppendFromStream">
      <MemberSignature Language="C#" Value="public virtual void AppendFromStream (System.IO.Stream source, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void AppendFromStream(class System.IO.Stream source, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromStream(System.IO.Stream,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member AppendFromStream : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.AppendFromStream : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudAppendBlob.AppendFromStream (source, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.IO.Stream" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="source">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。 場合<c>null</c>既定のオプションは、要求に適用されます。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            追加 blob にストリームを追加します。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。        
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AppendFromStream">
      <MemberSignature Language="C#" Value="public virtual void AppendFromStream (System.IO.Stream source, long length, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void AppendFromStream(class System.IO.Stream source, int64 length, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromStream(System.IO.Stream,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member AppendFromStream : System.IO.Stream * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.AppendFromStream : System.IO.Stream * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudAppendBlob.AppendFromStream (source, length, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.IO.Stream" />
        <Parameter Name="length" Type="System.Int64" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="source">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</param>
        <param name="length">現在の位置に、ソース ストリームから書き込むバイト数。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。 場合<c>null</c>既定のオプションは、要求に適用されます。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            追加 blob にストリームを追加します。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。        
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AppendFromStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task AppendFromStreamAsync (System.IO.Stream source);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AppendFromStreamAsync(class System.IO.Stream source) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromStreamAsync(System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function AppendFromStreamAsync (source As Stream) As Task" />
      <MemberSignature Language="F#" Value="abstract member AppendFromStreamAsync : System.IO.Stream -&gt; System.Threading.Tasks.Task&#xA;override this.AppendFromStreamAsync : System.IO.Stream -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.AppendFromStreamAsync source" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="source">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</param>
        <summary>
            追加 blob にストリームを追加する非同期操作を開始します。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。        
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AppendFromStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task AppendFromStreamAsync (System.IO.Stream source, long length);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AppendFromStreamAsync(class System.IO.Stream source, int64 length) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromStreamAsync(System.IO.Stream,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function AppendFromStreamAsync (source As Stream, length As Long) As Task" />
      <MemberSignature Language="F#" Value="abstract member AppendFromStreamAsync : System.IO.Stream * int64 -&gt; System.Threading.Tasks.Task&#xA;override this.AppendFromStreamAsync : System.IO.Stream * int64 -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.AppendFromStreamAsync (source, length)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.IO.Stream" />
        <Parameter Name="length" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="source">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</param>
        <param name="length">現在の位置に、ソース ストリームから書き込むバイト数。</param>
        <summary>
            追加 blob にストリームを追加する非同期操作を開始します。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。        
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AppendFromStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task AppendFromStreamAsync (System.IO.Stream source, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AppendFromStreamAsync(class System.IO.Stream source, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromStreamAsync(System.IO.Stream,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AppendFromStreamAsync : System.IO.Stream * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.AppendFromStreamAsync : System.IO.Stream * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.AppendFromStreamAsync (source, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.IO.Stream" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            追加 blob にストリームを追加する非同期操作を開始します。 単一ライターのシナリオでのみ推奨されます。        
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。        
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AppendFromStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task AppendFromStreamAsync (System.IO.Stream source, long length, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AppendFromStreamAsync(class System.IO.Stream source, int64 length, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromStreamAsync(System.IO.Stream,System.Int64,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AppendFromStreamAsync : System.IO.Stream * int64 * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.AppendFromStreamAsync : System.IO.Stream * int64 * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.AppendFromStreamAsync (source, length, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.IO.Stream" />
        <Parameter Name="length" Type="System.Int64" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</param>
        <param name="length">現在の位置に、ソース ストリームから書き込むバイト数。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            追加 blob にストリームを追加する非同期操作を開始します。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。        
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AppendFromStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task AppendFromStreamAsync (System.IO.Stream source, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AppendFromStreamAsync(class System.IO.Stream source, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromStreamAsync(System.IO.Stream,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member AppendFromStreamAsync : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.AppendFromStreamAsync : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.AppendFromStreamAsync (source, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.IO.Stream" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="source">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            追加 blob にストリームを追加する非同期操作を開始します。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。        
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AppendFromStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task AppendFromStreamAsync (System.IO.Stream source, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AppendFromStreamAsync(class System.IO.Stream source, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromStreamAsync(System.IO.Stream,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AppendFromStreamAsync : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.AppendFromStreamAsync : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.AppendFromStreamAsync (source, accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.IO.Stream" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            追加 blob にストリームを追加する非同期操作を開始します。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。        
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AppendFromStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task AppendFromStreamAsync (System.IO.Stream source, long length, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AppendFromStreamAsync(class System.IO.Stream source, int64 length, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromStreamAsync(System.IO.Stream,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member AppendFromStreamAsync : System.IO.Stream * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.AppendFromStreamAsync : System.IO.Stream * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.AppendFromStreamAsync (source, length, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.IO.Stream" />
        <Parameter Name="length" Type="System.Int64" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="source">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</param>
        <param name="length">現在の位置に、ソース ストリームから書き込むバイト数。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            追加 blob にストリームを追加する非同期操作を開始します。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。        
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AppendFromStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task AppendFromStreamAsync (System.IO.Stream source, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AppendFromStreamAsync(class System.IO.Stream source, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.IProgress`1&lt;class Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromStreamAsync(System.IO.Stream,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.IProgress{Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AppendFromStreamAsync : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.AppendFromStreamAsync : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.AppendFromStreamAsync (source, accessCondition, options, operationContext, progressHandler, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.IO.Stream" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="progressHandler" Type="System.IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="progressHandler"> A<see cref="T:System.IProgress`1" />を処理するオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" />メッセージ。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            追加 blob にストリームを追加する非同期操作を開始します。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。        
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AppendFromStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task AppendFromStreamAsync (System.IO.Stream source, long length, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AppendFromStreamAsync(class System.IO.Stream source, int64 length, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromStreamAsync(System.IO.Stream,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AppendFromStreamAsync : System.IO.Stream * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.AppendFromStreamAsync : System.IO.Stream * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.AppendFromStreamAsync (source, length, accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.IO.Stream" />
        <Parameter Name="length" Type="System.Int64" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</param>
        <param name="length">現在の位置に、ソース ストリームから書き込むバイト数。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            追加 blob にストリームを追加する非同期操作を開始します。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。        
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AppendFromStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task AppendFromStreamAsync (System.IO.Stream source, long length, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AppendFromStreamAsync(class System.IO.Stream source, int64 length, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.IProgress`1&lt;class Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromStreamAsync(System.IO.Stream,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.IProgress{Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AppendFromStreamAsync : System.IO.Stream * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.AppendFromStreamAsync : System.IO.Stream * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.AppendFromStreamAsync (source, length, accessCondition, options, operationContext, progressHandler, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.IO.Stream" />
        <Parameter Name="length" Type="System.Int64" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="progressHandler" Type="System.IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</param>
        <param name="length">現在の位置に、ソース ストリームから書き込むバイト数。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="progressHandler"> A<see cref="T:System.IProgress`1" />を処理するオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" />メッセージ。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            追加 blob にストリームを追加する非同期操作を開始します。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。        
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AppendText">
      <MemberSignature Language="C#" Value="public virtual void AppendText (string content, System.Text.Encoding encoding = null, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void AppendText(string content, class System.Text.Encoding encoding, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendText(System.String,System.Text.Encoding,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member AppendText : string * System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.AppendText : string * System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudAppendBlob.AppendText (content, encoding, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="content" Type="System.String" />
        <Parameter Name="encoding" Type="System.Text.Encoding" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="content">アップロードするテキストを含む文字列。</param>
        <param name="encoding">A<see cref="T:System.Text.Encoding" />を使用するテキスト エンコーディングを示すオブジェクト。 場合<c>null</c>utf-8 が使用されます。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。 場合<c>null</c>既定のオプションは、要求に適用されます。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            追加 blob にテキスト文字列を追加します。 この API は、API は内部的に複数のライターのシナリオでは機能しませんが、重複するブロックを回避する追加オフセット条件ヘッダーを使用するため、単一ライターのシナリオで厳密に使用する必要があります。
            </summary>
        <remarks>
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AppendTextAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task AppendTextAsync (string content);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AppendTextAsync(string content) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendTextAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function AppendTextAsync (content As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member AppendTextAsync : string -&gt; System.Threading.Tasks.Task&#xA;override this.AppendTextAsync : string -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.AppendTextAsync content" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="content" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="content">アップロードするテキストを含む文字列。</param>
        <summary>
            追加 blob にテキストの文字列を追加する非同期操作を開始します。 この API は、API は内部的に複数のライターのシナリオでは機能しませんが、重複するブロックを回避する追加オフセット条件ヘッダーを使用するため、単一ライターのシナリオで厳密に使用する必要があります。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppendTextAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task AppendTextAsync (string content, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AppendTextAsync(string content, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendTextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AppendTextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.AppendTextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.AppendTextAsync (content, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="content" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="content">アップロードするテキストを含む文字列。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            追加 blob にテキストの文字列を追加する非同期操作を開始します。 この API は、API は内部的に複数のライターのシナリオでは機能しませんが、重複するブロックを回避する追加オフセット条件ヘッダーを使用するため、単一ライターのシナリオで厳密に使用する必要があります。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppendTextAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task AppendTextAsync (string content, System.Text.Encoding encoding, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AppendTextAsync(string content, class System.Text.Encoding encoding, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendTextAsync(System.String,System.Text.Encoding,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member AppendTextAsync : string * System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.AppendTextAsync : string * System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.AppendTextAsync (content, encoding, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="content" Type="System.String" />
        <Parameter Name="encoding" Type="System.Text.Encoding" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="content">アップロードするテキストを含む文字列。</param>
        <param name="encoding">A<see cref="T:System.Text.Encoding" />を使用するテキスト エンコーディングを示すオブジェクト。 場合<c>null</c>utf-8 が使用されます。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            追加 blob にテキストの文字列を追加する非同期操作を開始します。 この API は、API は内部的に複数のライターのシナリオでは機能しませんが、重複するブロックを回避する追加オフセット条件ヘッダーを使用するため、単一ライターのシナリオで厳密に使用する必要があります。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AppendTextAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task AppendTextAsync (string content, System.Text.Encoding encoding, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AppendTextAsync(string content, class System.Text.Encoding encoding, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendTextAsync(System.String,System.Text.Encoding,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AppendTextAsync : string * System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.AppendTextAsync : string * System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.AppendTextAsync (content, encoding, accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="content" Type="System.String" />
        <Parameter Name="encoding" Type="System.Text.Encoding" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="content">アップロードするテキストを含む文字列。</param>
        <param name="encoding">A<see cref="T:System.Text.Encoding" />を使用するテキスト エンコーディングを示すオブジェクト。 場合<c>null</c>utf-8 が使用されます。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            追加 blob にテキストの文字列を追加する非同期操作を開始します。 この API は、API は内部的に複数のライターのシナリオでは機能しませんが、重複するブロックを回避する追加オフセット条件ヘッダーを使用するため、単一ライターのシナリオで厳密に使用する必要があります。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AppendTextAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task AppendTextAsync (string content, System.Text.Encoding encoding, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AppendTextAsync(string content, class System.Text.Encoding encoding, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.IProgress`1&lt;class Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendTextAsync(System.String,System.Text.Encoding,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.IProgress{Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AppendTextAsync : string * System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.AppendTextAsync : string * System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.AppendTextAsync (content, encoding, accessCondition, options, operationContext, progressHandler, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="content" Type="System.String" />
        <Parameter Name="encoding" Type="System.Text.Encoding" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="progressHandler" Type="System.IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="content">アップロードするテキストを含む文字列。</param>
        <param name="encoding">A<see cref="T:System.Text.Encoding" />を使用するテキスト エンコーディングを示すオブジェクト。 場合<c>null</c>utf-8 が使用されます。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="progressHandler"> A<see cref="T:System.IProgress`1" />を処理するオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" />メッセージ。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            追加 blob にテキストの文字列を追加する非同期操作を開始します。 この API は、API は内部的に複数のライターのシナリオでは機能しませんが、重複するブロックを回避する追加オフセット条件ヘッダーを使用するため、単一ライターのシナリオで厳密に使用する必要があります。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginAppendBlock">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginAppendBlock (System.IO.Stream blockData, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginAppendBlock(class System.IO.Stream blockData, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginAppendBlock(System.IO.Stream,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginAppendBlock (blockData As Stream, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginAppendBlock : System.IO.Stream * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginAppendBlock : System.IO.Stream * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudAppendBlob.BeginAppendBlock (blockData, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blockData" Type="System.IO.Stream" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="blockData">A<see cref="T:System.IO.Stream" />ブロックのデータを提供するオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            Blob の末尾に新しいデータのブロックをコミットする非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginAppendBlock">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginAppendBlock (System.IO.Stream blockData, string contentMD5, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginAppendBlock(class System.IO.Stream blockData, string contentMD5, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginAppendBlock(System.IO.Stream,System.String,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginAppendBlock (blockData As Stream, contentMD5 As String, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginAppendBlock : System.IO.Stream * string * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginAppendBlock : System.IO.Stream * string * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudAppendBlob.BeginAppendBlock (blockData, contentMD5, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blockData" Type="System.IO.Stream" />
        <Parameter Name="contentMD5" Type="System.String" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="blockData">A<see cref="T:System.IO.Stream" />ブロックのデータを提供するオブジェクト。</param>
        <param name="contentMD5">ブロックのトランザクションの整合性を確保するために使用する省略可能なハッシュ値です。 あります<c>null</c>または空の文字列。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            Blob の末尾に新しいデータのブロックをコミットする非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>
            クライアントは、ネットワーク上でトランザクションの整合性を確保するための手段として特定の Append Block 操作に関して content-md5 ヘッダーを送信できます。 <paramref name="contentMD5" />パラメーターにより、クライアントは、指定したバイトの範囲に提供することを事前に計算された MD5 値へのアクセスを既に持っています。
            場合、<see cref="P:BlobRequestOptions.UseTransactionalMd5" />プロパティに設定されている<c>true</c>と<paramref name="contentMD5" />にパラメーターが設定されている<c>null</c>、クライアント ライブラリが MD5 値を内部で計算し、します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginAppendBlock">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginAppendBlock (System.IO.Stream blockData, string contentMD5, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginAppendBlock(class System.IO.Stream blockData, string contentMD5, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginAppendBlock(System.IO.Stream,System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginAppendBlock : System.IO.Stream * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginAppendBlock : System.IO.Stream * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudAppendBlob.BeginAppendBlock (blockData, contentMD5, accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blockData" Type="System.IO.Stream" />
        <Parameter Name="contentMD5" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="blockData">A<see cref="T:System.IO.Stream" />ブロックのデータを提供するオブジェクト。</param>
        <param name="contentMD5">ブロックのトランザクションの整合性を確保するために使用する省略可能なハッシュ値です。 あります<c>null</c>または空の文字列。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            Blob の末尾に新しいデータのブロックをコミットする非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>
            クライアントは、ネットワーク上でトランザクションの整合性を確保するための手段として特定の Append Block 操作に関して content-md5 ヘッダーを送信できます。 <paramref name="contentMD5" />パラメーターにより、クライアントは、指定したバイトの範囲に提供することを事前に計算された MD5 値へのアクセスを既に持っています。
            場合、<see cref="P:BlobRequestOptions.UseTransactionalMd5" />プロパティに設定されている<c>true</c>と<paramref name="contentMD5" />にパラメーターが設定されている<c>null</c>、クライアント ライブラリが MD5 値を内部で計算し、します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginAppendFromByteArray">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginAppendFromByteArray (byte[] buffer, int index, int count, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginAppendFromByteArray(unsigned int8[] buffer, int32 index, int32 count, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginAppendFromByteArray(System.Byte[],System.Int32,System.Int32,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginAppendFromByteArray (buffer As Byte(), index As Integer, count As Integer, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginAppendFromByteArray : byte[] * int * int * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginAppendFromByteArray : byte[] * int * int * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudAppendBlob.BeginAppendFromByteArray (buffer, index, count, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="buffer" Type="System.Byte[]" />
        <Parameter Name="index" Type="System.Int32" />
        <Parameter Name="count" Type="System.Int32" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="buffer">バイト配列。</param>
        <param name="index">Blob のバイトのアップロードを開始位置を示すバッファー内の 0 から始まるバイト オフセット。</param>
        <param name="count">Blob に書き込まれるバイト数。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            追加 blob にバイト配列の内容を追加する非同期操作を開始します。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。        
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginAppendFromByteArray">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginAppendFromByteArray (byte[] buffer, int index, int count, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginAppendFromByteArray(unsigned int8[] buffer, int32 index, int32 count, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginAppendFromByteArray(System.Byte[],System.Int32,System.Int32,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginAppendFromByteArray : byte[] * int * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginAppendFromByteArray : byte[] * int * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudAppendBlob.BeginAppendFromByteArray (buffer, index, count, accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="buffer" Type="System.Byte[]" />
        <Parameter Name="index" Type="System.Int32" />
        <Parameter Name="count" Type="System.Int32" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="buffer">バイト配列。</param>
        <param name="index">Blob のバイトのアップロードを開始位置を示すバッファー内の 0 から始まるバイト オフセット。</param>
        <param name="count">Blob に書き込まれるバイト数。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            追加 blob にバイト配列の内容を追加する非同期操作を開始します。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。        
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginAppendFromFile">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginAppendFromFile (string path, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginAppendFromFile(string path, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginAppendFromFile(System.String,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginAppendFromFile (path As String, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginAppendFromFile : string * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginAppendFromFile : string * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudAppendBlob.BeginAppendFromFile (path, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="path">Blob コンテンツを提供するファイルのパスを含む文字列。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            追加 blob にファイルを追加する非同期操作を開始します。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。        
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginAppendFromFile">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginAppendFromFile (string path, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginAppendFromFile(string path, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginAppendFromFile(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginAppendFromFile : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginAppendFromFile : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudAppendBlob.BeginAppendFromFile (path, accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="path">Blob コンテンツを提供するファイルのパスを含む文字列。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            追加 blob にファイルを追加する非同期操作を開始します。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。        
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginAppendFromStream">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginAppendFromStream (System.IO.Stream source, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginAppendFromStream(class System.IO.Stream source, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginAppendFromStream(System.IO.Stream,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginAppendFromStream (source As Stream, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginAppendFromStream : System.IO.Stream * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginAppendFromStream : System.IO.Stream * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudAppendBlob.BeginAppendFromStream (source, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.IO.Stream" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="source">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            追加 blob にストリームを追加する非同期操作を開始します。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。        
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginAppendFromStream">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginAppendFromStream (System.IO.Stream source, long length, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginAppendFromStream(class System.IO.Stream source, int64 length, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginAppendFromStream(System.IO.Stream,System.Int64,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginAppendFromStream (source As Stream, length As Long, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginAppendFromStream : System.IO.Stream * int64 * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginAppendFromStream : System.IO.Stream * int64 * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudAppendBlob.BeginAppendFromStream (source, length, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.IO.Stream" />
        <Parameter Name="length" Type="System.Int64" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="source">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</param>
        <param name="length">開始位置からアップロードするストリームのソースからのバイト数を指定します。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            追加 blob にストリームを追加する非同期操作を開始します。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。        
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginAppendFromStream">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginAppendFromStream (System.IO.Stream source, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginAppendFromStream(class System.IO.Stream source, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginAppendFromStream(System.IO.Stream,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginAppendFromStream : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginAppendFromStream : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudAppendBlob.BeginAppendFromStream (source, accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.IO.Stream" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="source">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            追加 blob にストリームを追加する非同期操作を開始します。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。        
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginAppendFromStream">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginAppendFromStream (System.IO.Stream source, long length, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginAppendFromStream(class System.IO.Stream source, int64 length, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginAppendFromStream(System.IO.Stream,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginAppendFromStream : System.IO.Stream * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginAppendFromStream : System.IO.Stream * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudAppendBlob.BeginAppendFromStream (source, length, accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.IO.Stream" />
        <Parameter Name="length" Type="System.Int64" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="source">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</param>
        <param name="length">開始位置からアップロードするストリームのソースからのバイト数を指定します。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            追加 blob にストリームを追加する非同期操作を開始します。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。        
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginAppendText">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginAppendText (string content, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginAppendText(string content, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginAppendText(System.String,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginAppendText (content As String, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginAppendText : string * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginAppendText : string * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudAppendBlob.BeginAppendText (content, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="content" Type="System.String" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="content">アップロードするテキストを含む文字列。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            追加 blob にテキストの文字列を追加する非同期操作を開始します。 この API は、API は内部的に複数のライターのシナリオでは機能しませんが、重複するブロックを回避する追加オフセット条件ヘッダーを使用するため、単一ライターのシナリオで厳密に使用する必要があります。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginAppendText">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginAppendText (string content, System.Text.Encoding encoding, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginAppendText(string content, class System.Text.Encoding encoding, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginAppendText(System.String,System.Text.Encoding,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginAppendText : string * System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginAppendText : string * System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudAppendBlob.BeginAppendText (content, encoding, accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="content" Type="System.String" />
        <Parameter Name="encoding" Type="System.Text.Encoding" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="content">アップロードするテキストを含む文字列。</param>
        <param name="encoding">A<see cref="T:System.Text.Encoding" />を使用するテキスト エンコーディングを示すオブジェクト。 場合<c>null</c>utf-8 が使用されます。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            追加 blob にテキストの文字列を追加する非同期操作を開始します。 この API は、API は内部的に複数のライターのシナリオでは機能しませんが、重複するブロックを回避する追加オフセット条件ヘッダーを使用するため、単一ライターのシナリオで厳密に使用する必要があります。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrReplace">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreateOrReplace (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreateOrReplace(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginCreateOrReplace(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginCreateOrReplace (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrReplace : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreateOrReplace : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudAppendBlob.BeginCreateOrReplace (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            空の追加 blob を作成する非同期操作を開始します。 Blob が既に存在する場合はこの操作によって上書きされます。 使用して、上書きする代わりに、blob が存在する場合に例外をスローする<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginCreateOrReplace(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />です。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrReplace">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreateOrReplace (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreateOrReplace(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginCreateOrReplace(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrReplace : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreateOrReplace : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudAppendBlob.BeginCreateOrReplace (accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            空の追加 blob を作成する非同期操作を開始します。 Blob が既に存在する場合はこの操作によって上書きされます。 渡す、上書きする代わりに、blob が存在する場合に例外をスローする、<see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />オブジェクトを使用して生成<see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />です。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateSnapshot">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreateSnapshot (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreateSnapshot(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginCreateSnapshot(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginCreateSnapshot (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateSnapshot : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreateSnapshot : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudAppendBlob.BeginCreateSnapshot (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            Blob のスナップショットを作成する非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateSnapshot">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreateSnapshot (System.Collections.Generic.IDictionary&lt;string,string&gt; metadata, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreateSnapshot(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; metadata, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginCreateSnapshot(System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateSnapshot : System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreateSnapshot : System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudAppendBlob.BeginCreateSnapshot (metadata, accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="metadata" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="metadata">スナップショットのメタデータを定義する名前と値のペアのコレクション。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> 、要求の追加オプションを指定するオブジェクトまたは<c>null</c>です。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            Blob のスナップショットを作成する非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDownloadText">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDownloadText (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDownloadText(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginDownloadText(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginDownloadText (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginDownloadText : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDownloadText : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudAppendBlob.BeginDownloadText (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            Blob の内容を文字列としてダウンロードする非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDownloadText">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDownloadText (System.Text.Encoding encoding, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDownloadText(class System.Text.Encoding encoding, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginDownloadText(System.Text.Encoding,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginDownloadText : System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDownloadText : System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudAppendBlob.BeginDownloadText (encoding, accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="encoding" Type="System.Text.Encoding" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="encoding">使用するテキスト エンコーディングを示すオブジェクト。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            Blob の内容を文字列としてダウンロードする非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginOpenWrite">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginOpenWrite (bool createNew, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginOpenWrite(bool createNew, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginOpenWrite(System.Boolean,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginOpenWrite (createNew As Boolean, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginOpenWrite : bool * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginOpenWrite : bool * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudAppendBlob.BeginOpenWrite (createNew, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="createNew" Type="System.Boolean" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="createNew">使用して<c>true</c>追加して、新しい blob を作成または既存のものを上書きする<c>false</c>既存の blob に追加します。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            Blob に書き込むためのストリームを開く非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>
            このメソッドへの呼び出しを常に、注意してください、<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginFetchAttributes(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />内部的メソッドです。
            設定、 <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.StreamWriteSizeInBytes" /> mb 16 KB と 4 MB までの範囲のバイトの書き込みは、ブロック サイズを指定するには、このメソッドを呼び出す前に、プロパティです。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginOpenWrite">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginOpenWrite (bool createNew, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginOpenWrite(bool createNew, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginOpenWrite(System.Boolean,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginOpenWrite : bool * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginOpenWrite : bool * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudAppendBlob.BeginOpenWrite (createNew, accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="createNew" Type="System.Boolean" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="createNew">使用して<c>true</c>追加して、新しい blob を作成または既存のものを上書きする<c>false</c>既存の blob に追加します。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            Blob に書き込むためのストリームを開く非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>
            このメソッドへの呼び出しを常に、注意してください、<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginFetchAttributes(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />内部的メソッドです。
            設定、 <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.StreamWriteSizeInBytes" /> mb 16 KB と 4 MB までの範囲のバイトの書き込みは、ブロック サイズを指定するには、このメソッドを呼び出す前に、プロパティです。
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStartCopy">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginStartCopy (Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob source, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginStartCopy(class Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob source, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginStartCopy(Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginStartCopy (source As CloudAppendBlob, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="override this.BeginStartCopy : Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudAppendBlob.BeginStartCopy (source, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="source"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" /> オブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            この追加 blob を別の追加 blob の内容、プロパティ、およびメタデータのコピーを開始する非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStartCopy">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginStartCopy (Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob source, Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginStartCopy(class Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob source, class Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, class Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginStartCopy(Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="override this.BeginStartCopy : Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudAppendBlob.BeginStartCopy (source, sourceAccessCondition, destAccessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" />
        <Parameter Name="sourceAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="destAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="source"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" /> オブジェクト。</param>
        <param name="sourceAccessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー元 blob のアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="destAccessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー先 blob のアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            この追加 blob を別の追加 blob の内容、プロパティ、およびメタデータのコピーを開始する非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUploadFromByteArray">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromByteArray (byte[] buffer, int index, int count, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromByteArray(unsigned int8[] buffer, int32 index, int32 count, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginUploadFromByteArray(System.Byte[],System.Int32,System.Int32,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginUploadFromByteArray (buffer As Byte(), index As Integer, count As Integer, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginUploadFromByteArray : byte[] * int * int * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginUploadFromByteArray : byte[] * int * int * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudAppendBlob.BeginUploadFromByteArray (buffer, index, count, callback, state)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.BeginUploadFromByteArray(System.Byte[],System.Int32,System.Int32,System.AsyncCallback,System.Object)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="buffer" Type="System.Byte[]" />
        <Parameter Name="index" Type="System.Int32" />
        <Parameter Name="count" Type="System.Int32" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="buffer">バイト配列。</param>
        <param name="index">Blob のバイトのアップロードを開始位置を示すバッファー内の 0 から始まるバイト オフセット。</param>
        <param name="count">Blob に書き込まれるバイト数。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            バイト配列の内容を追加 blob にアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。
            既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginAppendFromByteArray(System.Byte[],System.Int32,System.Int32,System.AsyncCallback,System.Object)" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUploadFromByteArray">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromByteArray (byte[] buffer, int index, int count, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromByteArray(unsigned int8[] buffer, int32 index, int32 count, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginUploadFromByteArray(System.Byte[],System.Int32,System.Int32,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginUploadFromByteArray : byte[] * int * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginUploadFromByteArray : byte[] * int * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudAppendBlob.BeginUploadFromByteArray (buffer, index, count, accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.BeginUploadFromByteArray(System.Byte[],System.Int32,System.Int32,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="buffer" Type="System.Byte[]" />
        <Parameter Name="index" Type="System.Int32" />
        <Parameter Name="count" Type="System.Int32" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="buffer">バイト配列。</param>
        <param name="index">Blob のバイトのアップロードを開始位置を示すバッファー内の 0 から始まるバイト オフセット。</param>
        <param name="count">Blob に書き込まれるバイト数。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            バイト配列の内容を追加 blob にアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginAppendFromByteArray(System.Byte[],System.Int32,System.Int32,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUploadFromFile">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromFile (string path, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromFile(string path, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginUploadFromFile(System.String,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginUploadFromFile (path As String, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginUploadFromFile : string * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginUploadFromFile : string * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudAppendBlob.BeginUploadFromFile (path, callback, state)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.BeginUploadFromFile(System.String,System.AsyncCallback,System.Object)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="path">Blob コンテンツを提供するファイルのパスを含む文字列。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            追加 blob にファイルをアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。        
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginAppendFromFile(System.String,System.AsyncCallback,System.Object)" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUploadFromFile">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromFile (string path, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromFile(string path, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginUploadFromFile(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginUploadFromFile : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginUploadFromFile : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudAppendBlob.BeginUploadFromFile (path, accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.BeginUploadFromFile(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="path">Blob コンテンツを提供するファイルのパスを含む文字列。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            追加 blob にファイルをアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。        
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginAppendFromFile(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUploadFromStream">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromStream (System.IO.Stream source, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromStream(class System.IO.Stream source, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginUploadFromStream(System.IO.Stream,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginUploadFromStream (source As Stream, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginUploadFromStream : System.IO.Stream * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginUploadFromStream : System.IO.Stream * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudAppendBlob.BeginUploadFromStream (source, callback, state)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.BeginUploadFromStream(System.IO.Stream,System.AsyncCallback,System.Object)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.IO.Stream" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="source">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            追加 blob にストリームをアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。        
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginAppendFromStream(System.IO.Stream,System.AsyncCallback,System.Object)" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUploadFromStream">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromStream (System.IO.Stream source, long length, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromStream(class System.IO.Stream source, int64 length, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginUploadFromStream(System.IO.Stream,System.Int64,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginUploadFromStream (source As Stream, length As Long, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginUploadFromStream : System.IO.Stream * int64 * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginUploadFromStream : System.IO.Stream * int64 * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudAppendBlob.BeginUploadFromStream (source, length, callback, state)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.BeginUploadFromStream(System.IO.Stream,System.Int64,System.AsyncCallback,System.Object)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.IO.Stream" />
        <Parameter Name="length" Type="System.Int64" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="source">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</param>
        <param name="length">開始位置からアップロードするストリームのソースからのバイト数を指定します。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            追加 blob にストリームをアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。        
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginAppendFromStream(System.IO.Stream,System.Int64,System.AsyncCallback,System.Object)" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUploadFromStream">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromStream (System.IO.Stream source, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromStream(class System.IO.Stream source, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginUploadFromStream(System.IO.Stream,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginUploadFromStream : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginUploadFromStream : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudAppendBlob.BeginUploadFromStream (source, accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.BeginUploadFromStream(System.IO.Stream,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.IO.Stream" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="source">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            追加 blob にストリームをアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。        
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginAppendFromStream(System.IO.Stream,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUploadFromStream">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromStream (System.IO.Stream source, long length, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromStream(class System.IO.Stream source, int64 length, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginUploadFromStream(System.IO.Stream,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginUploadFromStream : System.IO.Stream * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginUploadFromStream : System.IO.Stream * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudAppendBlob.BeginUploadFromStream (source, length, accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.BeginUploadFromStream(System.IO.Stream,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.IO.Stream" />
        <Parameter Name="length" Type="System.Int64" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="source">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</param>
        <param name="length">開始位置からアップロードするストリームのソースからのバイト数を指定します。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            追加 blob にストリームをアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。        
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginAppendFromStream(System.IO.Stream,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUploadText">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadText (string content, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadText(string content, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginUploadText(System.String,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginUploadText (content As String, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginUploadText : string * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginUploadText : string * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudAppendBlob.BeginUploadText (content, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="content" Type="System.String" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="content">アップロードするテキストを含む文字列。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            テキストの文字列を追加 blob にアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。
            既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginAppendText(System.String,System.AsyncCallback,System.Object)" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUploadText">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadText (string content, System.Text.Encoding encoding, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadText(string content, class System.Text.Encoding encoding, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginUploadText(System.String,System.Text.Encoding,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginUploadText : string * System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginUploadText : string * System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudAppendBlob.BeginUploadText (content, encoding, accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="content" Type="System.String" />
        <Parameter Name="encoding" Type="System.Text.Encoding" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="content">アップロードするテキストを含む文字列。</param>
        <param name="encoding">A<see cref="T:System.Text.Encoding" />を使用するテキスト エンコーディングを示すオブジェクト。 場合<c>null</c>utf-8 が使用されます。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            テキストの文字列を追加 blob にアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginAppendText(System.String,System.Text.Encoding,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrReplace">
      <MemberSignature Language="C#" Value="public virtual void CreateOrReplace (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void CreateOrReplace(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.CreateOrReplace(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrReplace : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.CreateOrReplace : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudAppendBlob.CreateOrReplace (accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。 場合<c>null</c>既定のオプションは、要求に適用されます。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            空の追加 blob を作成します。 Blob が既に存在する場合はこの操作によって上書きされます。 渡す、上書きする代わりに、blob が存在する場合に例外をスローする、<see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />オブジェクトを使用して生成<see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />です。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrReplaceAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateOrReplaceAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateOrReplaceAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.CreateOrReplaceAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function CreateOrReplaceAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member CreateOrReplaceAsync : unit -&gt; System.Threading.Tasks.Task&#xA;override this.CreateOrReplaceAsync : unit -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.CreateOrReplaceAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            空の追加 blob を作成する非同期操作を開始します。 Blob が既に存在する場合はこの操作によって上書きされます。 使用して、上書きする代わりに、blob が存在する場合に例外をスローする<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.CreateOrReplaceAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />です。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrReplaceAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateOrReplaceAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateOrReplaceAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.CreateOrReplaceAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrReplaceAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.CreateOrReplaceAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.CreateOrReplaceAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            追加 blob を作成する非同期操作を開始します。 Blob が既に存在する場合はこの操作によって上書きされます。 使用して、上書きする代わりに、blob が存在する場合に例外をスローする<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.CreateOrReplaceAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />です。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrReplaceAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateOrReplaceAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateOrReplaceAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.CreateOrReplaceAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrReplaceAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.CreateOrReplaceAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.CreateOrReplaceAsync (accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            空の追加 blob を作成する非同期操作を開始します。 Blob が既に存在する場合はこの操作によって上書きされます。 渡す、上書きする代わりに、blob が存在する場合に例外をスローする、<see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />オブジェクトを使用して生成<see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />です。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrReplaceAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateOrReplaceAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateOrReplaceAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.CreateOrReplaceAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrReplaceAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.CreateOrReplaceAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.CreateOrReplaceAsync (accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            空の追加 blob を作成する非同期操作を開始します。 Blob が既に存在する場合はこの操作によって上書きされます。 渡す、上書きする代わりに、blob が存在する場合に例外をスローする、<see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />オブジェクトを使用して生成<see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />です。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSnapshot">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob CreateSnapshot (System.Collections.Generic.IDictionary&lt;string,string&gt; metadata = null, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob CreateSnapshot(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; metadata, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.CreateSnapshot(System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member CreateSnapshot : System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob&#xA;override this.CreateSnapshot : System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" Usage="cloudAppendBlob.CreateSnapshot (metadata, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="metadata" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="metadata">スナップショットのメタデータを定義する名前と値のペアのコレクション。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> 、要求の追加オプションを指定するオブジェクトまたは<c>null</c>です。 場合<c>null</c>既定のオプションは、要求に適用されます。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            Blob のスナップショットを作成します。
            </summary>
        <returns>A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" /> blob のスナップショットであるオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSnapshotAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob&gt; CreateSnapshotAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob&gt; CreateSnapshotAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.CreateSnapshotAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function CreateSnapshotAsync () As Task(Of CloudAppendBlob)" />
      <MemberSignature Language="F#" Value="abstract member CreateSnapshotAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob&gt;&#xA;override this.CreateSnapshotAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob&gt;" Usage="cloudAppendBlob.CreateSnapshotAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Blob のスナップショットを作成する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSnapshotAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob&gt; CreateSnapshotAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob&gt; CreateSnapshotAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.CreateSnapshotAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateSnapshotAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob&gt;&#xA;override this.CreateSnapshotAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob&gt;" Usage="cloudAppendBlob.CreateSnapshotAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            Blob のスナップショットを作成する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSnapshotAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob&gt; CreateSnapshotAsync (System.Collections.Generic.IDictionary&lt;string,string&gt; metadata, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob&gt; CreateSnapshotAsync(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; metadata, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.CreateSnapshotAsync(System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member CreateSnapshotAsync : System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob&gt;&#xA;override this.CreateSnapshotAsync : System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob&gt;" Usage="cloudAppendBlob.CreateSnapshotAsync (metadata, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="metadata" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="metadata">スナップショットのメタデータを定義する名前と値のペアのコレクション。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            Blob のスナップショットを作成する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSnapshotAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob&gt; CreateSnapshotAsync (System.Collections.Generic.IDictionary&lt;string,string&gt; metadata, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob&gt; CreateSnapshotAsync(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; metadata, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.CreateSnapshotAsync(System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateSnapshotAsync : System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob&gt;&#xA;override this.CreateSnapshotAsync : System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob&gt;" Usage="cloudAppendBlob.CreateSnapshotAsync (metadata, accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="metadata" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="metadata">スナップショットのメタデータを定義する名前と値のペアのコレクション。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            Blob のスナップショットを作成する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadText">
      <MemberSignature Language="C#" Value="public virtual string DownloadText (System.Text.Encoding encoding = null, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string DownloadText(class System.Text.Encoding encoding, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.DownloadText(System.Text.Encoding,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DownloadText : System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; string&#xA;override this.DownloadText : System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; string" Usage="cloudAppendBlob.DownloadText (encoding, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="encoding" Type="System.Text.Encoding" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="encoding">使用するテキスト エンコーディングを示すオブジェクト。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。 場合<c>null</c>既定のオプションは、要求に適用されます。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            Blob の内容を文字列としてダウンロードします。
            </summary>
        <returns>文字列として、blob の内容。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadTextAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; DownloadTextAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; DownloadTextAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.DownloadTextAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function DownloadTextAsync () As Task(Of String)" />
      <MemberSignature Language="F#" Value="abstract member DownloadTextAsync : unit -&gt; System.Threading.Tasks.Task&lt;string&gt;&#xA;override this.DownloadTextAsync : unit -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudAppendBlob.DownloadTextAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Blob の内容を文字列としてダウンロードする非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>文字列</c>非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadTextAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; DownloadTextAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; DownloadTextAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.DownloadTextAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DownloadTextAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;&#xA;override this.DownloadTextAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudAppendBlob.DownloadTextAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            Blob の内容を文字列としてダウンロードする非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>文字列</c>非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadTextAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; DownloadTextAsync (System.Text.Encoding encoding, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; DownloadTextAsync(class System.Text.Encoding encoding, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.DownloadTextAsync(System.Text.Encoding,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DownloadTextAsync : System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;string&gt;&#xA;override this.DownloadTextAsync : System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudAppendBlob.DownloadTextAsync (encoding, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="encoding" Type="System.Text.Encoding" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="encoding">使用するテキスト エンコーディングを示すオブジェクト。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            Blob の内容を文字列としてダウンロードする非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>文字列</c>非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadTextAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; DownloadTextAsync (System.Text.Encoding encoding, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; DownloadTextAsync(class System.Text.Encoding encoding, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.DownloadTextAsync(System.Text.Encoding,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DownloadTextAsync : System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;&#xA;override this.DownloadTextAsync : System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudAppendBlob.DownloadTextAsync (encoding, accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="encoding" Type="System.Text.Encoding" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="encoding">使用するテキスト エンコーディングを示すオブジェクト。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            Blob の内容を文字列としてダウンロードする非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>文字列</c>非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadTextAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; DownloadTextAsync (System.Text.Encoding encoding, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; DownloadTextAsync(class System.Text.Encoding encoding, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.IProgress`1&lt;class Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.DownloadTextAsync(System.Text.Encoding,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.IProgress{Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DownloadTextAsync : System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;&#xA;override this.DownloadTextAsync : System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudAppendBlob.DownloadTextAsync (encoding, accessCondition, options, operationContext, progressHandler, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="encoding" Type="System.Text.Encoding" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="progressHandler" Type="System.IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="encoding">使用するテキスト エンコーディングを示すオブジェクト。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="progressHandler"> A<see cref="T:System.IProgress`1" />を処理するオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" />メッセージ。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            Blob の内容を文字列としてダウンロードする非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>文字列</c>非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndAppendBlock">
      <MemberSignature Language="C#" Value="public virtual long EndAppendBlock (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int64 EndAppendBlock(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.EndAppendBlock(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndAppendBlock (asyncResult As IAsyncResult) As Long" />
      <MemberSignature Language="F#" Value="abstract member EndAppendBlock : IAsyncResult -&gt; int64&#xA;override this.EndAppendBlock : IAsyncResult -&gt; int64" Usage="cloudAppendBlob.EndAppendBlock asyncResult" />
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
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</param>
        <summary>
            Blob の末尾に新しいデータのブロックをコミットする非同期操作を終了します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndAppendFromByteArray">
      <MemberSignature Language="C#" Value="public virtual void EndAppendFromByteArray (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndAppendFromByteArray(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.EndAppendFromByteArray(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndAppendFromByteArray (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndAppendFromByteArray : IAsyncResult -&gt; unit&#xA;override this.EndAppendFromByteArray : IAsyncResult -&gt; unit" Usage="cloudAppendBlob.EndAppendFromByteArray asyncResult" />
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
        <param name="asyncResult"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</param>
        <summary>
            追加 blob にバイト配列の内容を追加する非同期操作を終了します。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndAppendFromFile">
      <MemberSignature Language="C#" Value="public virtual void EndAppendFromFile (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndAppendFromFile(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.EndAppendFromFile(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndAppendFromFile (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndAppendFromFile : IAsyncResult -&gt; unit&#xA;override this.EndAppendFromFile : IAsyncResult -&gt; unit" Usage="cloudAppendBlob.EndAppendFromFile asyncResult" />
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
        <param name="asyncResult"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</param>
        <summary>
            追加 blob にファイルをアップロードする非同期操作を終了します。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。        
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EndAppendFromStream">
      <MemberSignature Language="C#" Value="public virtual void EndAppendFromStream (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndAppendFromStream(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.EndAppendFromStream(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndAppendFromStream (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndAppendFromStream : IAsyncResult -&gt; unit&#xA;override this.EndAppendFromStream : IAsyncResult -&gt; unit" Usage="cloudAppendBlob.EndAppendFromStream asyncResult" />
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
        <param name="asyncResult"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</param>
        <summary>
            追加 blob にストリームを追加する非同期操作を終了します。 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndAppendText">
      <MemberSignature Language="C#" Value="public virtual void EndAppendText (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndAppendText(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.EndAppendText(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndAppendText (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndAppendText : IAsyncResult -&gt; unit&#xA;override this.EndAppendText : IAsyncResult -&gt; unit" Usage="cloudAppendBlob.EndAppendText asyncResult" />
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
        <param name="asyncResult"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</param>
        <summary>
            追加 blob にテキストの文字列を追加する非同期操作を終了します。 この API は、API は内部的に複数のライターのシナリオでは機能しませんが、重複するブロックを回避する追加オフセット条件ヘッダーを使用するため、単一ライターのシナリオで厳密に使用する必要があります。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndCreateOrReplace">
      <MemberSignature Language="C#" Value="public virtual void EndCreateOrReplace (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndCreateOrReplace(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.EndCreateOrReplace(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndCreateOrReplace (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndCreateOrReplace : IAsyncResult -&gt; unit&#xA;override this.EndCreateOrReplace : IAsyncResult -&gt; unit" Usage="cloudAppendBlob.EndCreateOrReplace asyncResult" />
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
        <param name="asyncResult"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</param>
        <summary>
            追加 blob を作成する非同期操作を終了します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndCreateSnapshot">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob EndCreateSnapshot (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob EndCreateSnapshot(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.EndCreateSnapshot(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndCreateSnapshot (asyncResult As IAsyncResult) As CloudAppendBlob" />
      <MemberSignature Language="F#" Value="abstract member EndCreateSnapshot : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob&#xA;override this.EndCreateSnapshot : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" Usage="cloudAppendBlob.EndCreateSnapshot asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</param>
        <summary>
            Blob のスナップショットを作成する非同期操作を終了します。
            </summary>
        <returns>A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" /> blob のスナップショットであるオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndDownloadText">
      <MemberSignature Language="C#" Value="public virtual string EndDownloadText (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string EndDownloadText(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.EndDownloadText(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndDownloadText (asyncResult As IAsyncResult) As String" />
      <MemberSignature Language="F#" Value="abstract member EndDownloadText : IAsyncResult -&gt; string&#xA;override this.EndDownloadText : IAsyncResult -&gt; string" Usage="cloudAppendBlob.EndDownloadText asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</param>
        <summary>
            Blob の内容を文字列としてダウンロードする非同期操作を終了します。
            </summary>
        <returns>文字列として、blob の内容。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndOpenWrite">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream EndOpenWrite (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream EndOpenWrite(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.EndOpenWrite(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndOpenWrite (asyncResult As IAsyncResult) As CloudBlobStream" />
      <MemberSignature Language="F#" Value="abstract member EndOpenWrite : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&#xA;override this.EndOpenWrite : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" Usage="cloudAppendBlob.EndOpenWrite asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</param>
        <summary>
            Blob に書き込むためのストリームを開く非同期操作を終了します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndUploadFromByteArray">
      <MemberSignature Language="C#" Value="public virtual void EndUploadFromByteArray (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndUploadFromByteArray(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.EndUploadFromByteArray(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndUploadFromByteArray (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndUploadFromByteArray : IAsyncResult -&gt; unit&#xA;override this.EndUploadFromByteArray : IAsyncResult -&gt; unit" Usage="cloudAppendBlob.EndUploadFromByteArray asyncResult" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.EndUploadFromByteArray(System.IAsyncResult)</InterfaceMember>
      </Implements>
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
        <param name="asyncResult"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</param>
        <summary>
            バイト配列の内容を追加 blob にアップロードする非同期操作を終了します。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。        
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EndUploadFromFile">
      <MemberSignature Language="C#" Value="public virtual void EndUploadFromFile (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndUploadFromFile(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.EndUploadFromFile(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndUploadFromFile (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndUploadFromFile : IAsyncResult -&gt; unit&#xA;override this.EndUploadFromFile : IAsyncResult -&gt; unit" Usage="cloudAppendBlob.EndUploadFromFile asyncResult" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.EndUploadFromFile(System.IAsyncResult)</InterfaceMember>
      </Implements>
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
        <param name="asyncResult"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</param>
        <summary>
            追加 blob にファイルをアップロードする非同期操作を終了します。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。        
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EndUploadFromStream">
      <MemberSignature Language="C#" Value="public virtual void EndUploadFromStream (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndUploadFromStream(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.EndUploadFromStream(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndUploadFromStream (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndUploadFromStream : IAsyncResult -&gt; unit&#xA;override this.EndUploadFromStream : IAsyncResult -&gt; unit" Usage="cloudAppendBlob.EndUploadFromStream asyncResult" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.EndUploadFromStream(System.IAsyncResult)</InterfaceMember>
      </Implements>
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
        <param name="asyncResult"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</param>
        <summary>
            追加 blob にストリームをアップロードする非同期操作を終了します。 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndUploadText">
      <MemberSignature Language="C#" Value="public virtual void EndUploadText (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndUploadText(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.EndUploadText(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndUploadText (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndUploadText : IAsyncResult -&gt; unit&#xA;override this.EndUploadText : IAsyncResult -&gt; unit" Usage="cloudAppendBlob.EndUploadText asyncResult" />
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
        <param name="asyncResult"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</param>
        <summary>
            テキストの文字列を追加 blob にアップロードする非同期操作を終了します。 この API は、API は内部的に複数のライターのシナリオでは機能しませんが、重複するブロックを回避する追加オフセット条件ヘッダーを使用するため、単一ライターのシナリオで厳密に使用する必要があります。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenWrite">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream OpenWrite (bool createNew, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream OpenWrite(bool createNew, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.OpenWrite(System.Boolean,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member OpenWrite : bool * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&#xA;override this.OpenWrite : bool * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" Usage="cloudAppendBlob.OpenWrite (createNew, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="createNew" Type="System.Boolean" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="createNew">使用して<c>true</c>追加して、新しい blob を作成または既存のものを上書きする<c>false</c>既存の blob に追加します。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。 場合<c>null</c>既定のオプションは、要求に適用されます。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            Blob に書き込むためのストリームを開きます。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" /> オブジェクト。</returns>
        <remarks>
            このメソッドへの呼び出しを常に、注意してください、<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributes(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />内部的メソッドです。
            設定、 <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.StreamWriteSizeInBytes" /> mb 16 KB と 4 MB までの範囲のバイトの書き込みは、ブロック サイズを指定するには、このメソッドを呼び出す前に、プロパティです。
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenWriteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt; OpenWriteAsync (bool createNew);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt; OpenWriteAsync(bool createNew) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.OpenWriteAsync(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function OpenWriteAsync (createNew As Boolean) As Task(Of CloudBlobStream)" />
      <MemberSignature Language="F#" Value="abstract member OpenWriteAsync : bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt;&#xA;override this.OpenWriteAsync : bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt;" Usage="cloudAppendBlob.OpenWriteAsync createNew" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="createNew" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="createNew">使用して<c>true</c>追加して、新しい blob を作成または既存のものを上書きする<c>false</c>既存の blob に追加します。</param>
        <summary>
            Blob に書き込むためのストリームを開く非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" />非同期操作を表すです。</returns>
        <remarks>
            このメソッドへの呼び出しを常に、注意してください、<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginFetchAttributes(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />内部的メソッドです。
            設定、 <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.StreamWriteSizeInBytes" /> mb 16 KB と 4 MB までの範囲のバイトの書き込みは、ブロック サイズを指定するには、このメソッドを呼び出す前に、プロパティです。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenWriteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt; OpenWriteAsync (bool createNew, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt; OpenWriteAsync(bool createNew, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.OpenWriteAsync(System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OpenWriteAsync : bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt;&#xA;override this.OpenWriteAsync : bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt;" Usage="cloudAppendBlob.OpenWriteAsync (createNew, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="createNew" Type="System.Boolean" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="createNew">使用して<c>true</c>追加して、新しい blob を作成または既存のものを上書きする<c>false</c>既存の blob に追加します。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            Blob に書き込むためのストリームを開く非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" />非同期操作を表すです。</returns>
        <remarks>
            このメソッドへの呼び出しを常に、注意してください、<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributesAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />内部的メソッドです。
            設定、 <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.StreamWriteSizeInBytes" /> mb 16 KB と 4 MB までの範囲のバイトの書き込みは、ブロック サイズを指定するには、このメソッドを呼び出す前に、プロパティです。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenWriteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt; OpenWriteAsync (bool createNew, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt; OpenWriteAsync(bool createNew, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.OpenWriteAsync(System.Boolean,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member OpenWriteAsync : bool * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt;&#xA;override this.OpenWriteAsync : bool * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt;" Usage="cloudAppendBlob.OpenWriteAsync (createNew, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="createNew" Type="System.Boolean" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="createNew">使用して<c>true</c>追加して、新しい blob を作成または既存のものを上書きする<c>false</c>既存の blob に追加します。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            Blob に書き込むためのストリームを開く非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" />非同期操作を表すです。</returns>
        <remarks>
            このメソッドへの呼び出しを常に、注意してください、<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributesAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />内部的メソッドです。
            設定、 <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.StreamWriteSizeInBytes" /> mb 16 KB と 4 MB までの範囲のバイトの書き込みは、ブロック サイズを指定するには、このメソッドを呼び出す前に、プロパティです。
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenWriteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt; OpenWriteAsync (bool createNew, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt; OpenWriteAsync(bool createNew, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.OpenWriteAsync(System.Boolean,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OpenWriteAsync : bool * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt;&#xA;override this.OpenWriteAsync : bool * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt;" Usage="cloudAppendBlob.OpenWriteAsync (createNew, accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="createNew" Type="System.Boolean" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="createNew">使用して<c>true</c>追加して、新しい blob を作成または既存のものを上書きする<c>false</c>既存の blob に追加します。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            Blob に書き込むためのストリームを開く非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" />非同期操作を表すです。</returns>
        <remarks>
            このメソッドへの呼び出しを常に、注意してください、<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributesAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />内部的メソッドです。
            設定、 <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.StreamWriteSizeInBytes" /> mb 16 KB と 4 MB までの範囲のバイトの書き込みは、ブロック サイズを指定するには、このメソッドを呼び出す前に、プロパティです。
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StartCopy">
      <MemberSignature Language="C#" Value="public virtual string StartCopy (Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob source, Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition = null, Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string StartCopy(class Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob source, class Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, class Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.StartCopy(Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="override this.StartCopy : Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; string" Usage="cloudAppendBlob.StartCopy (source, sourceAccessCondition, destAccessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" />
        <Parameter Name="sourceAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="destAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="source"><see cref="T:System.Uri" />コピー元 blob のです。</param>
        <param name="sourceAccessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー元 blob のアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="destAccessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー先 blob のアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。 場合<c>null</c>既定のオプションは、要求に適用されます。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            この追加 blob を別の追加 blob の内容、プロパティ、およびメタデータのコピーを開始するための操作を開始します。
            </summary>
        <returns>コピー操作に関連付けられたコピー ID です。</returns>
        <remarks>
            このメソッドは、blob の ETag、最終更新時刻、および一部のコピー状態をフェッチします。
            コピー ID とコピーのステータス フィールドがフェッチされ、残りのコピーの状態がクリアされます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StartCopyAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; StartCopyAsync (Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob source);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; StartCopyAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob source) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.StartCopyAsync(Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function StartCopyAsync (source As CloudAppendBlob) As Task(Of String)" />
      <MemberSignature Language="F#" Value="override this.StartCopyAsync : Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudAppendBlob.StartCopyAsync source" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" />
      </Parameters>
      <Docs>
        <param name="source"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" /> オブジェクト。</param>
        <summary>
            この追加 blob を別の追加 blob の内容、プロパティ、およびメタデータのコピーを開始する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>文字列</c>非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartCopyAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; StartCopyAsync (Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob source, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; StartCopyAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob source, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.StartCopyAsync(Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="override this.StartCopyAsync : Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudAppendBlob.StartCopyAsync (source, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" /> オブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            この追加 blob を別の追加 blob の内容、プロパティ、およびメタデータのコピーを開始する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>文字列</c>非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartCopyAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; StartCopyAsync (Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob source, Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; StartCopyAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob source, class Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, class Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.StartCopyAsync(Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="override this.StartCopyAsync : Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudAppendBlob.StartCopyAsync (source, sourceAccessCondition, destAccessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" />
        <Parameter Name="sourceAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="destAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="source"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" /> オブジェクト。</param>
        <param name="sourceAccessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー元 blob のアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="destAccessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー先 blob のアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            この追加 blob を別の追加 blob の内容、プロパティ、およびメタデータのコピーを開始する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>文字列</c>非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartCopyAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; StartCopyAsync (Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob source, Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; StartCopyAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob source, class Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, class Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.StartCopyAsync(Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="override this.StartCopyAsync : Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudAppendBlob.StartCopyAsync (source, sourceAccessCondition, destAccessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" />
        <Parameter Name="sourceAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="destAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" /> オブジェクト。</param>
        <param name="sourceAccessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー元 blob のアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="destAccessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー先 blob のアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            この追加 blob を別の追加 blob の内容、プロパティ、およびメタデータのコピーを開始する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>文字列</c>非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StreamWriteSizeInBytes">
      <MemberSignature Language="C#" Value="public int StreamWriteSizeInBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 StreamWriteSizeInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.StreamWriteSizeInBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property StreamWriteSizeInBytes As Integer" />
      <MemberSignature Language="F#" Value="member this.StreamWriteSizeInBytes : int with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.StreamWriteSizeInBytes" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.StreamWriteSizeInBytes</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または追加 blob ストリームに書き込むときにバッファーに書き込むバイト数を設定します。
            </summary>
        <value>(バイト単位) mb 16 KB と 4 MB までの範囲内のブロックのサイズ。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromByteArray">
      <MemberSignature Language="C#" Value="public virtual void UploadFromByteArray (byte[] buffer, int index, int count, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void UploadFromByteArray(unsigned int8[] buffer, int32 index, int32 count, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.UploadFromByteArray(System.Byte[],System.Int32,System.Int32,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromByteArray : byte[] * int * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.UploadFromByteArray : byte[] * int * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudAppendBlob.UploadFromByteArray (buffer, index, count, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.UploadFromByteArray(System.Byte[],System.Int32,System.Int32,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="buffer" Type="System.Byte[]" />
        <Parameter Name="index" Type="System.Int32" />
        <Parameter Name="count" Type="System.Int32" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="buffer">バイト配列。</param>
        <param name="index">Blob のバイトのアップロードを開始位置を示すバッファー内の 0 から始まるバイト オフセット。</param>
        <param name="count">Blob に書き込まれるバイト数。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。 場合<c>null</c>既定のオプションは、要求に適用されます。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            バイト配列の内容を追加 blob にアップロードします。 Blob が既に存在する場合は上書きされます。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。        
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromByteArray(System.Byte[],System.Int32,System.Int32,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromByteArrayAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromByteArrayAsync (byte[] buffer, int index, int count);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromByteArrayAsync(unsigned int8[] buffer, int32 index, int32 count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.UploadFromByteArrayAsync(System.Byte[],System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function UploadFromByteArrayAsync (buffer As Byte(), index As Integer, count As Integer) As Task" />
      <MemberSignature Language="F#" Value="abstract member UploadFromByteArrayAsync : byte[] * int * int -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromByteArrayAsync : byte[] * int * int -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.UploadFromByteArrayAsync (buffer, index, count)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.UploadFromByteArrayAsync(System.Byte[],System.Int32,System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="buffer" Type="System.Byte[]" />
        <Parameter Name="index" Type="System.Int32" />
        <Parameter Name="count" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="buffer">バイト配列。</param>
        <param name="index">Blob のバイトのアップロードを開始位置を示すバッファー内の 0 から始まるバイト オフセット。</param>
        <param name="count">Blob に書き込まれるバイト数。</param>
        <summary>
            バイト配列の内容を追加 blob にアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。
            既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromByteArrayAsync(System.Byte[],System.Int32,System.Int32)" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromByteArrayAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromByteArrayAsync (byte[] buffer, int index, int count, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromByteArrayAsync(unsigned int8[] buffer, int32 index, int32 count, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.UploadFromByteArrayAsync(System.Byte[],System.Int32,System.Int32,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromByteArrayAsync : byte[] * int * int * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromByteArrayAsync : byte[] * int * int * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.UploadFromByteArrayAsync (buffer, index, count, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.UploadFromByteArrayAsync(System.Byte[],System.Int32,System.Int32,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="buffer" Type="System.Byte[]" />
        <Parameter Name="index" Type="System.Int32" />
        <Parameter Name="count" Type="System.Int32" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="buffer">バイト配列。</param>
        <param name="index">Blob のバイトのアップロードを開始位置を示すバッファー内の 0 から始まるバイト オフセット。</param>
        <param name="count">Blob に書き込まれるバイト数。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            バイト配列の内容を追加 blob にアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。
            既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromByteArrayAsync(System.Byte[],System.Int32,System.Int32,System.Threading.CancellationToken)" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromByteArrayAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromByteArrayAsync (byte[] buffer, int index, int count, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromByteArrayAsync(unsigned int8[] buffer, int32 index, int32 count, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.UploadFromByteArrayAsync(System.Byte[],System.Int32,System.Int32,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromByteArrayAsync : byte[] * int * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromByteArrayAsync : byte[] * int * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.UploadFromByteArrayAsync (buffer, index, count, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.UploadFromByteArrayAsync(System.Byte[],System.Int32,System.Int32,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="buffer" Type="System.Byte[]" />
        <Parameter Name="index" Type="System.Int32" />
        <Parameter Name="count" Type="System.Int32" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="buffer">バイト配列。</param>
        <param name="index">Blob のバイトのアップロードを開始位置を示すバッファー内の 0 から始まるバイト オフセット。</param>
        <param name="count">Blob に書き込まれるバイト数。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            バイト配列の内容を追加 blob にアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromByteArrayAsync(System.Byte[],System.Int32,System.Int32,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromByteArrayAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromByteArrayAsync (byte[] buffer, int index, int count, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromByteArrayAsync(unsigned int8[] buffer, int32 index, int32 count, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.UploadFromByteArrayAsync(System.Byte[],System.Int32,System.Int32,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromByteArrayAsync : byte[] * int * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromByteArrayAsync : byte[] * int * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.UploadFromByteArrayAsync (buffer, index, count, accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.UploadFromByteArrayAsync(System.Byte[],System.Int32,System.Int32,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="buffer" Type="System.Byte[]" />
        <Parameter Name="index" Type="System.Int32" />
        <Parameter Name="count" Type="System.Int32" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="buffer">バイト配列。</param>
        <param name="index">Blob のバイトのアップロードを開始位置を示すバッファー内の 0 から始まるバイト オフセット。</param>
        <param name="count">Blob に書き込まれるバイト数。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            バイト配列の内容を追加 blob にアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromByteArrayAsync(System.Byte[],System.Int32,System.Int32,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromByteArrayAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromByteArrayAsync (byte[] buffer, int index, int count, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromByteArrayAsync(unsigned int8[] buffer, int32 index, int32 count, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.IProgress`1&lt;class Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.UploadFromByteArrayAsync(System.Byte[],System.Int32,System.Int32,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.IProgress{Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromByteArrayAsync : byte[] * int * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromByteArrayAsync : byte[] * int * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.UploadFromByteArrayAsync (buffer, index, count, accessCondition, options, operationContext, progressHandler, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="buffer" Type="System.Byte[]" />
        <Parameter Name="index" Type="System.Int32" />
        <Parameter Name="count" Type="System.Int32" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="progressHandler" Type="System.IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="buffer">バイト配列。</param>
        <param name="index">Blob のバイトのアップロードを開始位置を示すバッファー内の 0 から始まるバイト オフセット。</param>
        <param name="count">Blob に書き込まれるバイト数。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="progressHandler"> A<see cref="T:System.IProgress`1" />を処理するオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" />メッセージ。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            バイト配列の内容を追加 blob にアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromByteArrayAsync(System.Byte[],System.Int32,System.Int32,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromFile">
      <MemberSignature Language="C#" Value="public virtual void UploadFromFile (string path, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void UploadFromFile(string path, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.UploadFromFile(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromFile : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.UploadFromFile : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudAppendBlob.UploadFromFile (path, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.UploadFromFile(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="path">Blob コンテンツを提供するファイルのパスを含む文字列。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。 場合<c>null</c>既定のオプションは、要求に適用されます。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            追加 blob にファイルをアップロードします。 Blob が既に存在する場合は上書きされます。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。        
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromFile(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromFileAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromFileAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromFileAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.UploadFromFileAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function UploadFromFileAsync (path As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member UploadFromFileAsync : string -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromFileAsync : string -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.UploadFromFileAsync path" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.UploadFromFileAsync(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Blob コンテンツを提供するファイルのパスを含む文字列。</param>
        <summary>
            追加 blob にファイルをアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。        
            既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromFileAsync(System.String)" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromFileAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromFileAsync (string path, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromFileAsync(string path, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.UploadFromFileAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromFileAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromFileAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.UploadFromFileAsync (path, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.UploadFromFileAsync(System.String,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">Blob コンテンツを提供するファイルのパスを含む文字列。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            追加 blob にファイルをアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。        
            既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromFileAsync(System.String,System.Threading.CancellationToken)" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromFileAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromFileAsync (string path, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromFileAsync(string path, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.UploadFromFileAsync(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromFileAsync : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromFileAsync : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.UploadFromFileAsync (path, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.UploadFromFileAsync(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="path">Blob コンテンツを提供するファイルのパスを含む文字列。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            追加 blob にファイルをアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。        
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromFileAsync(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromFileAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromFileAsync (string path, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromFileAsync(string path, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.UploadFromFileAsync(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromFileAsync : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromFileAsync : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.UploadFromFileAsync (path, accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.UploadFromFileAsync(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">Blob コンテンツを提供するファイルのパスを含む文字列。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            追加 blob にファイルをアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。        
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromFileAsync(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromFileAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromFileAsync (string path, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromFileAsync(string path, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.IProgress`1&lt;class Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.UploadFromFileAsync(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.IProgress{Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromFileAsync : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromFileAsync : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.UploadFromFileAsync (path, accessCondition, options, operationContext, progressHandler, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="progressHandler" Type="System.IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">Blob コンテンツを提供するファイルのパスを含む文字列。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="progressHandler"> A<see cref="T:System.IProgress`1" />を処理するオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" />メッセージ。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            追加 blob にファイルをアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。        
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromFileAsync(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromStream">
      <MemberSignature Language="C#" Value="public virtual void UploadFromStream (System.IO.Stream source, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void UploadFromStream(class System.IO.Stream source, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.UploadFromStream(System.IO.Stream,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromStream : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.UploadFromStream : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudAppendBlob.UploadFromStream (source, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.UploadFromStream(System.IO.Stream,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.IO.Stream" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="source">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。 場合<c>null</c>既定のオプションは、要求に適用されます。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            追加 blob にストリームをアップロードします。 Blob が既に存在する場合は上書きされます。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。        
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromStream(System.IO.Stream,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromStream">
      <MemberSignature Language="C#" Value="public virtual void UploadFromStream (System.IO.Stream source, long length, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void UploadFromStream(class System.IO.Stream source, int64 length, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.UploadFromStream(System.IO.Stream,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromStream : System.IO.Stream * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.UploadFromStream : System.IO.Stream * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudAppendBlob.UploadFromStream (source, length, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.UploadFromStream(System.IO.Stream,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.IO.Stream" />
        <Parameter Name="length" Type="System.Int64" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="source">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</param>
        <param name="length">現在の位置に、ソース ストリームから書き込むバイト数。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。 場合<c>null</c>既定のオプションは、要求に適用されます。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            追加 blob にストリームをアップロードします。 Blob が既に存在する場合は上書きされます。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。        
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromStream(System.IO.Stream,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromStreamAsync (System.IO.Stream source);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromStreamAsync(class System.IO.Stream source) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.UploadFromStreamAsync(System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function UploadFromStreamAsync (source As Stream) As Task" />
      <MemberSignature Language="F#" Value="abstract member UploadFromStreamAsync : System.IO.Stream -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromStreamAsync : System.IO.Stream -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.UploadFromStreamAsync source" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.UploadFromStreamAsync(System.IO.Stream)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="source">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</param>
        <summary>
            追加 blob にストリームをアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromStreamAsync(System.IO.Stream)" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromStreamAsync (System.IO.Stream source, long length);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromStreamAsync(class System.IO.Stream source, int64 length) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.UploadFromStreamAsync(System.IO.Stream,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function UploadFromStreamAsync (source As Stream, length As Long) As Task" />
      <MemberSignature Language="F#" Value="abstract member UploadFromStreamAsync : System.IO.Stream * int64 -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromStreamAsync : System.IO.Stream * int64 -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.UploadFromStreamAsync (source, length)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.UploadFromStreamAsync(System.IO.Stream,System.Int64)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.IO.Stream" />
        <Parameter Name="length" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="source">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</param>
        <param name="length">現在の位置に、ソース ストリームから書き込むバイト数。</param>
        <summary>
            追加 blob にストリームをアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromStreamAsync(System.IO.Stream,System.Int64)" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromStreamAsync (System.IO.Stream source, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromStreamAsync(class System.IO.Stream source, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.UploadFromStreamAsync(System.IO.Stream,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromStreamAsync : System.IO.Stream * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromStreamAsync : System.IO.Stream * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.UploadFromStreamAsync (source, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.UploadFromStreamAsync(System.IO.Stream,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.IO.Stream" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            追加 blob にストリームをアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromStreamAsync(System.IO.Stream,System.Threading.CancellationToken)" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromStreamAsync (System.IO.Stream source, long length, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromStreamAsync(class System.IO.Stream source, int64 length, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.UploadFromStreamAsync(System.IO.Stream,System.Int64,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromStreamAsync : System.IO.Stream * int64 * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromStreamAsync : System.IO.Stream * int64 * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.UploadFromStreamAsync (source, length, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.UploadFromStreamAsync(System.IO.Stream,System.Int64,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.IO.Stream" />
        <Parameter Name="length" Type="System.Int64" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</param>
        <param name="length">現在の位置に、ソース ストリームから書き込むバイト数。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            追加 blob にストリームをアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromStreamAsync(System.IO.Stream,System.Int64,System.Threading.CancellationToken)" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromStreamAsync (System.IO.Stream source, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromStreamAsync(class System.IO.Stream source, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.UploadFromStreamAsync(System.IO.Stream,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromStreamAsync : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromStreamAsync : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.UploadFromStreamAsync (source, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.UploadFromStreamAsync(System.IO.Stream,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.IO.Stream" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="source">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            追加 blob にストリームをアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。        
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromStreamAsync(System.IO.Stream,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromStreamAsync (System.IO.Stream source, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromStreamAsync(class System.IO.Stream source, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.UploadFromStreamAsync(System.IO.Stream,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromStreamAsync : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromStreamAsync : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.UploadFromStreamAsync (source, accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.UploadFromStreamAsync(System.IO.Stream,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.IO.Stream" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            追加 blob にストリームをアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。        
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromStreamAsync(System.IO.Stream,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromStreamAsync (System.IO.Stream source, long length, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromStreamAsync(class System.IO.Stream source, int64 length, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.UploadFromStreamAsync(System.IO.Stream,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromStreamAsync : System.IO.Stream * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromStreamAsync : System.IO.Stream * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.UploadFromStreamAsync (source, length, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.UploadFromStreamAsync(System.IO.Stream,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.IO.Stream" />
        <Parameter Name="length" Type="System.Int64" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="source">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</param>
        <param name="length">現在の位置に、ソース ストリームから書き込むバイト数。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            追加 blob にストリームをアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。        
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromStreamAsync(System.IO.Stream,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromStreamAsync (System.IO.Stream source, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromStreamAsync(class System.IO.Stream source, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.IProgress`1&lt;class Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.UploadFromStreamAsync(System.IO.Stream,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.IProgress{Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromStreamAsync : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromStreamAsync : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.UploadFromStreamAsync (source, accessCondition, options, operationContext, progressHandler, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.IO.Stream" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="progressHandler" Type="System.IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="progressHandler"> A<see cref="T:System.IProgress`1" />を処理するオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" />メッセージ。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            追加 blob にストリームをアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。        
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromStreamAsync(System.IO.Stream,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromStreamAsync (System.IO.Stream source, long length, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromStreamAsync(class System.IO.Stream source, int64 length, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.UploadFromStreamAsync(System.IO.Stream,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromStreamAsync : System.IO.Stream * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromStreamAsync : System.IO.Stream * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.UploadFromStreamAsync (source, length, accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.UploadFromStreamAsync(System.IO.Stream,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.IO.Stream" />
        <Parameter Name="length" Type="System.Int64" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</param>
        <param name="length">現在の位置に、ソース ストリームから書き込むバイト数。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            追加 blob にストリームをアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。        
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromStreamAsync(System.IO.Stream,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromStreamAsync (System.IO.Stream source, long length, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromStreamAsync(class System.IO.Stream source, int64 length, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.IProgress`1&lt;class Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.UploadFromStreamAsync(System.IO.Stream,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.IProgress{Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromStreamAsync : System.IO.Stream * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromStreamAsync : System.IO.Stream * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.UploadFromStreamAsync (source, length, accessCondition, options, operationContext, progressHandler, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.IO.Stream" />
        <Parameter Name="length" Type="System.Int64" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="progressHandler" Type="System.IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</param>
        <param name="length">現在の位置に、ソース ストリームから書き込むバイト数。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="progressHandler"> A<see cref="T:System.IProgress`1" />を処理するオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" />メッセージ。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            追加 blob にストリームをアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。        
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromStreamAsync(System.IO.Stream,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadText">
      <MemberSignature Language="C#" Value="public virtual void UploadText (string content, System.Text.Encoding encoding = null, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void UploadText(string content, class System.Text.Encoding encoding, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.UploadText(System.String,System.Text.Encoding,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member UploadText : string * System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.UploadText : string * System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudAppendBlob.UploadText (content, encoding, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="content" Type="System.String" />
        <Parameter Name="encoding" Type="System.Text.Encoding" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="content">アップロードするテキストを含む文字列。</param>
        <param name="encoding">A<see cref="T:System.Text.Encoding" />を使用するテキスト エンコーディングを示すオブジェクト。 場合<c>null</c>utf-8 が使用されます。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。 場合<c>null</c>既定のオプションは、要求に適用されます。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            テキストの文字列を追加 blob にアップロードします。 Blob が既に存在する場合は上書きされます。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendText(System.String,System.Text.Encoding,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadTextAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadTextAsync (string content);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadTextAsync(string content) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.UploadTextAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function UploadTextAsync (content As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member UploadTextAsync : string -&gt; System.Threading.Tasks.Task&#xA;override this.UploadTextAsync : string -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.UploadTextAsync content" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="content" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="content">アップロードするテキストを含む文字列。</param>
        <summary>
            テキストの文字列を追加 blob にアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。
            既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendTextAsync(System.String)" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadTextAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadTextAsync (string content, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadTextAsync(string content, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.UploadTextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadTextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadTextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.UploadTextAsync (content, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="content" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="content">アップロードするテキストを含む文字列。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            テキストの文字列を追加 blob にアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendTextAsync(System.String,System.Threading.CancellationToken)" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadTextAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadTextAsync (string content, System.Text.Encoding encoding, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadTextAsync(string content, class System.Text.Encoding encoding, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.UploadTextAsync(System.String,System.Text.Encoding,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member UploadTextAsync : string * System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.UploadTextAsync : string * System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.UploadTextAsync (content, encoding, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="content" Type="System.String" />
        <Parameter Name="encoding" Type="System.Text.Encoding" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="content">アップロードするテキストを含む文字列。</param>
        <param name="encoding">A<see cref="T:System.Text.Encoding" />を使用するテキスト エンコーディングを示すオブジェクト。 場合<c>null</c>utf-8 が使用されます。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            テキストの文字列を追加 blob にアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendTextAsync(System.String,System.Text.Encoding,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadTextAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadTextAsync (string content, System.Text.Encoding encoding, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadTextAsync(string content, class System.Text.Encoding encoding, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.UploadTextAsync(System.String,System.Text.Encoding,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadTextAsync : string * System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadTextAsync : string * System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.UploadTextAsync (content, encoding, accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="content" Type="System.String" />
        <Parameter Name="encoding" Type="System.Text.Encoding" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="content">アップロードするテキストを含む文字列。</param>
        <param name="encoding">A<see cref="T:System.Text.Encoding" />を使用するテキスト エンコーディングを示すオブジェクト。 場合<c>null</c>utf-8 が使用されます。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            テキストの文字列を追加 blob にアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendTextAsync(System.String,System.Text.Encoding,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadTextAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadTextAsync (string content, System.Text.Encoding encoding, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadTextAsync(string content, class System.Text.Encoding encoding, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.IProgress`1&lt;class Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.UploadTextAsync(System.String,System.Text.Encoding,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.IProgress{Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadTextAsync : string * System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadTextAsync : string * System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudAppendBlob.UploadTextAsync (content, encoding, accessCondition, options, operationContext, progressHandler, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="content" Type="System.String" />
        <Parameter Name="encoding" Type="System.Text.Encoding" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="progressHandler" Type="System.IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="content">アップロードするテキストを含む文字列。</param>
        <param name="encoding">A<see cref="T:System.Text.Encoding" />を使用するテキスト エンコーディングを示すオブジェクト。 場合<c>null</c>utf-8 が使用されます。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="progressHandler"> A<see cref="T:System.IProgress`1" />を処理するオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" />メッセージ。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            テキストの文字列を追加 blob にアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。 単一ライターのシナリオでのみ推奨されます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            単一ライターのシナリオでのみ、このメソッドを使用します。 内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。
            単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。
            既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendTextAsync(System.String,System.Text.Encoding,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />です。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>