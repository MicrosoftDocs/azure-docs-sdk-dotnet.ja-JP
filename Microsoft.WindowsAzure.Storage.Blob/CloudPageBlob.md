<Type Name="CloudPageBlob" FullName="Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob">
  <TypeSignature Language="C#" Value="public class CloudPageBlob : Microsoft.WindowsAzure.Storage.Blob.CloudBlob, Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CloudPageBlob extends Microsoft.WindowsAzure.Storage.Blob.CloudBlob implements class Microsoft.WindowsAzure.Storage.Blob.ICloudBlob, class Microsoft.WindowsAzure.Storage.Blob.IListBlobItem" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />
  <TypeSignature Language="VB.NET" Value="Public Class CloudPageBlob&#xA;Inherits CloudBlob&#xA;Implements ICloudBlob" />
  <TypeSignature Language="F#" Value="type CloudPageBlob = class&#xA;    inherit CloudBlob&#xA;    interface ICloudBlob&#xA;    interface IListBlobItem" />
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
            Microsoft Azure ページ blob を表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudPageBlob (Uri blobAbsoluteUri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri blobAbsoluteUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.#ctor(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (blobAbsoluteUri As Uri)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob : Uri -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" Usage="new Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob blobAbsoluteUri" />
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
        <param name="blobAbsoluteUri">Blob の絶対 URI です。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />クラス blob への絶対 URI を使用します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudPageBlob (Uri blobAbsoluteUri, Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri blobAbsoluteUri, class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.#ctor(System.Uri,Microsoft.WindowsAzure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (blobAbsoluteUri As Uri, credentials As StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob : Uri * Microsoft.WindowsAzure.Storage.Auth.StorageCredentials -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" Usage="new Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob (blobAbsoluteUri, credentials)" />
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
        <param name="blobAbsoluteUri">Blob の絶対 URI です。</param>
        <param name="credentials"><see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> オブジェクト。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />クラス blob への絶対 URI を使用します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudPageBlob (Microsoft.WindowsAzure.Storage.StorageUri blobAbsoluteUri, Nullable&lt;DateTimeOffset&gt; snapshotTime, Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.StorageUri blobAbsoluteUri, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshotTime, class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.#ctor(Microsoft.WindowsAzure.Storage.StorageUri,System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (blobAbsoluteUri As StorageUri, snapshotTime As Nullable(Of DateTimeOffset), credentials As StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob : Microsoft.WindowsAzure.Storage.StorageUri * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.Auth.StorageCredentials -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" Usage="new Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob (blobAbsoluteUri, snapshotTime, credentials)" />
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
        <param name="blobAbsoluteUri">Blob の絶対 URI です。 サービスでは、これは、プライマリの場所での blob の URI を前提としています。</param>
        <param name="snapshotTime">A <see cref="T:System.DateTimeOffset" /> blob がスナップショットの場合、スナップショットのタイムスタンプを指定します。</param>
        <param name="credentials"><see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> オブジェクト。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />クラス blob への絶対 URI を使用します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudPageBlob (Uri blobAbsoluteUri, Nullable&lt;DateTimeOffset&gt; snapshotTime, Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri blobAbsoluteUri, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshotTime, class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.#ctor(System.Uri,System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (blobAbsoluteUri As Uri, snapshotTime As Nullable(Of DateTimeOffset), credentials As StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob : Uri * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.Auth.StorageCredentials -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" Usage="new Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob (blobAbsoluteUri, snapshotTime, credentials)" />
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
        <param name="blobAbsoluteUri">Blob の絶対 URI です。</param>
        <param name="snapshotTime">A <see cref="T:System.DateTimeOffset" /> blob がスナップショットの場合、スナップショットのタイムスタンプを指定します。</param>
        <param name="credentials"><see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> オブジェクト。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />クラス blob への絶対 URI を使用します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginClearPages">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginClearPages (long startOffset, long length, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginClearPages(int64 startOffset, int64 length, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.BeginClearPages(System.Int64,System.Int64,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginClearPages (startOffset As Long, length As Long, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginClearPages : int64 * int64 * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginClearPages : int64 * int64 * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudPageBlob.BeginClearPages (startOffset, length, callback, state)" />
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
        <Parameter Name="startOffset" Type="System.Int64" />
        <Parameter Name="length" Type="System.Int64" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="startOffset">(バイト単位) のページの消去を開始するオフセットです。 オフセットは 512 の倍数である必要があります。</param>
        <param name="length">(バイト単位) をクリアするデータ範囲の長さ。 長さは 512 の倍数である必要があります。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            ページ blob からページを消去する非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginClearPages">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginClearPages (long startOffset, long length, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginClearPages(int64 startOffset, int64 length, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.BeginClearPages(System.Int64,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginClearPages : int64 * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginClearPages : int64 * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudPageBlob.BeginClearPages (startOffset, length, accessCondition, options, operationContext, callback, state)" />
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
        <Parameter Name="startOffset" Type="System.Int64" />
        <Parameter Name="length" Type="System.Int64" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="startOffset">(バイト単位) のページの消去を開始するオフセットです。 オフセットは 512 の倍数である必要があります。</param>
        <param name="length">(バイト単位) をクリアするデータ範囲の長さ。 長さは 512 の倍数である必要があります。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            ページ blob からページを消去する非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreate (long size, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreate(int64 size, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.BeginCreate(System.Int64,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginCreate (size As Long, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginCreate : int64 * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreate : int64 * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudPageBlob.BeginCreate (size, callback, state)" />
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
        <Parameter Name="size" Type="System.Int64" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="size">(バイト単位)、ページ blob の最大サイズ。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            ページ blob を作成する非同期操作を開始します。 Blob が既に存在する場合はこの操作によって上書きされます。 使用して、上書きする代わりに、blob が存在する場合に例外をスローする<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.BeginCreate(System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />です。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreate (long size, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreate(int64 size, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.BeginCreate(System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreate : int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreate : int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudPageBlob.BeginCreate (size, accessCondition, options, operationContext, callback, state)" />
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
        <Parameter Name="size" Type="System.Int64" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="size">(バイト単位)、blob の最大サイズ。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            ページ blob を作成する非同期操作を開始します。 Blob が既に存在する場合はこの操作によって上書きされます。 渡す、上書きする代わりに、blob が存在する場合に例外をスローする、<see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />オブジェクトを使用して生成<see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />です。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreate (long size, Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; premiumPageBlobTier, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreate(int64 size, valuetype System.Nullable`1&lt;valuetype Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; premiumPageBlobTier, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.BeginCreate(System.Int64,System.Nullable{Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreate : int64 * Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreate : int64 * Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudPageBlob.BeginCreate (size, premiumPageBlobTier, accessCondition, options, operationContext, callback, state)" />
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
        <Parameter Name="size" Type="System.Int64" />
        <Parameter Name="premiumPageBlobTier" Type="System.Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="size">(バイト単位)、blob の最大サイズ。</param>
        <param name="premiumPageBlobTier">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            ページ blob を作成する非同期操作を開始します。 Blob が既に存在する場合はこの操作によって上書きされます。 渡す、上書きする代わりに、blob が存在する場合に例外をスローする、<see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />オブジェクトを使用して生成<see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />です。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateSnapshot">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreateSnapshot (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreateSnapshot(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.BeginCreateSnapshot(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginCreateSnapshot (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateSnapshot : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreateSnapshot : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudPageBlob.BeginCreateSnapshot (callback, state)" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.BeginCreateSnapshot(System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateSnapshot : System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreateSnapshot : System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudPageBlob.BeginCreateSnapshot (metadata, accessCondition, options, operationContext, callback, state)" />
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
    <Member MemberName="BeginGetPageRanges">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetPageRanges (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetPageRanges(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.BeginGetPageRanges(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginGetPageRanges (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginGetPageRanges : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetPageRanges : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudPageBlob.BeginGetPageRanges (callback, state)" />
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
            有効なページ範囲の開始および終了バイトのコレクションを返す非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetPageRanges">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetPageRanges (Nullable&lt;long&gt; offset, Nullable&lt;long&gt; length, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetPageRanges(valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;int64&gt; length, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.BeginGetPageRanges(System.Nullable{System.Int64},System.Nullable{System.Int64},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginGetPageRanges : Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetPageRanges : Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudPageBlob.BeginGetPageRanges (offset, length, accessCondition, options, operationContext, callback, state)" />
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
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="length" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="offset">するデータ範囲のリスト ページの範囲の開始オフセット (バイト単位)。 512 の倍数である必要があります。</param>
        <param name="length">リスト ページにどのデータ範囲の範囲の長さ (バイト単位)。 512 の倍数である必要があります。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            有効なページ範囲の開始および終了バイトのコレクションを返す非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetPageRangesDiff">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetPageRangesDiff (DateTimeOffset previousSnapshotTime, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetPageRangesDiff(valuetype System.DateTimeOffset previousSnapshotTime, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.BeginGetPageRangesDiff(System.DateTimeOffset,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginGetPageRangesDiff (previousSnapshotTime As DateTimeOffset, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginGetPageRangesDiff : DateTimeOffset * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetPageRangesDiff : DateTimeOffset * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudPageBlob.BeginGetPageRangesDiff (previousSnapshotTime, callback, state)" />
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
        <Parameter Name="previousSnapshotTime" Type="System.DateTimeOffset" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="previousSnapshotTime">A <see cref="T:System.DateTimeOffset" /> diff の開始点として使用する、スナップショットのタイムスタンプを表すこの CloudPageBlob を表す場合、スナップショット、previousSnapshotTime パラメーターは、現在のスナップショットのタイムスタンプより前でなければなりません。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            指定したスナップショットとこのオブジェクトの間で異なるページ範囲のコレクションを取得する非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetPageRangesDiff">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetPageRangesDiff (DateTimeOffset previousSnapshotTime, Nullable&lt;long&gt; offset, Nullable&lt;long&gt; length, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetPageRangesDiff(valuetype System.DateTimeOffset previousSnapshotTime, valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;int64&gt; length, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.BeginGetPageRangesDiff(System.DateTimeOffset,System.Nullable{System.Int64},System.Nullable{System.Int64},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginGetPageRangesDiff : DateTimeOffset * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetPageRangesDiff : DateTimeOffset * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudPageBlob.BeginGetPageRangesDiff (previousSnapshotTime, offset, length, accessCondition, options, operationContext, callback, state)" />
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
        <Parameter Name="previousSnapshotTime" Type="System.DateTimeOffset" />
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="length" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="previousSnapshotTime">A <see cref="T:System.DateTimeOffset" /> diff の開始点として使用する、スナップショットのタイムスタンプを表すこの CloudPageBlob を表す場合、スナップショット、previousSnapshotTime パラメーターは、現在のスナップショットのタイムスタンプより前でなければなりません。</param>
        <param name="offset">するデータ範囲のリスト ページの範囲の開始オフセット (バイト単位)。 512 の倍数である必要があります。</param>
        <param name="length">リスト ページにどのデータ範囲の範囲の長さ (バイト単位)。 512 の倍数である必要があります。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            指定したスナップショットとこのオブジェクトの間で異なるページ範囲のコレクションを取得する非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginOpenWrite">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginOpenWrite (Nullable&lt;long&gt; size, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginOpenWrite(valuetype System.Nullable`1&lt;int64&gt; size, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.BeginOpenWrite(System.Nullable{System.Int64},System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginOpenWrite (size As Nullable(Of Long), callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginOpenWrite : Nullable&lt;int64&gt; * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginOpenWrite : Nullable&lt;int64&gt; * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudPageBlob.BeginOpenWrite (size, callback, state)" />
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
        <Parameter Name="size" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="size">(バイト単位)、ページ blob のサイズ。 サイズは 512 の倍数である必要があります。 場合<c>null</c>、ページ blob が既に存在する必要があります。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            Blob に書き込むためのストリームを開く非同期操作を開始します。 Blob が既に存在する場合は、blob 内の既存のデータが上書きされます。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>
          <para>このメソッドへの呼び出しを常に、注意してください、<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginFetchAttributes(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />内部的メソッドです。</para>
          <para>設定、<see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.StreamWriteSizeInBytes" />書き込み mb 包括的な 512 ~ 4 MB までの範囲の 512 バイトの倍数では、ページ サイズを指定するには、このメソッドを呼び出す前に、プロパティです。</para>
          <para>例外をスローする、上書きすることではなく、blob が存在する場合は、次を参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.BeginOpenWrite(System.Nullable{System.Int64},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginOpenWrite">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginOpenWrite (Nullable&lt;long&gt; size, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginOpenWrite(valuetype System.Nullable`1&lt;int64&gt; size, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.BeginOpenWrite(System.Nullable{System.Int64},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginOpenWrite : Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginOpenWrite : Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudPageBlob.BeginOpenWrite (size, accessCondition, options, operationContext, callback, state)" />
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
        <Parameter Name="size" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="size">(バイト単位)、ページ blob のサイズ。 サイズは 512 の倍数である必要があります。 場合<c>null</c>、ページ blob が既に存在する必要があります。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            Blob に書き込むためのストリームを開く非同期操作を開始します。 Blob が既に存在する場合は、blob 内の既存のデータが上書きされます。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>
          <para>このメソッドへの呼び出しを常に、注意してください、<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginFetchAttributes(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />内部的メソッドです。</para>
          <para>設定、<see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.StreamWriteSizeInBytes" />書き込み mb 包括的な 512 ~ 4 MB までの範囲の 512 バイトの倍数では、ページ サイズを指定するには、このメソッドを呼び出す前に、プロパティです。</para>
          <para>これを上書きする代わりに blob が存在する場合は、例外をスロー、渡す、<see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />オブジェクトを使用して生成<see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginResize">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginResize (long size, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginResize(int64 size, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.BeginResize(System.Int64,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginResize (size As Long, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginResize : int64 * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginResize : int64 * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudPageBlob.BeginResize (size, callback, state)" />
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
        <Parameter Name="size" Type="System.Int64" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="size">(バイト単位)、ページ blob のサイズ。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            指定されたサイズにページ blob のサイズを変更する非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginResize">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginResize (long size, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginResize(int64 size, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.BeginResize(System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginResize : int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginResize : int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudPageBlob.BeginResize (size, accessCondition, options, operationContext, callback, state)" />
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
        <Parameter Name="size" Type="System.Int64" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="size">(バイト単位)、blob のサイズ。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            指定されたサイズにページ blob のサイズを変更する非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetPremiumBlobTier">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetPremiumBlobTier (Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier premiumPageBlobTier, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetPremiumBlobTier(valuetype Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier premiumPageBlobTier, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.BeginSetPremiumBlobTier(Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginSetPremiumBlobTier : Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetPremiumBlobTier : Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudPageBlob.BeginSetPremiumBlobTier (premiumPageBlobTier, callback, state)" />
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
        <Parameter Name="premiumPageBlobTier" Type="Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="premiumPageBlobTier">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            Premium blob の層に設定する非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetPremiumBlobTier">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetPremiumBlobTier (Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier premiumPageBlobTier, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetPremiumBlobTier(valuetype Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier premiumPageBlobTier, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.BeginSetPremiumBlobTier(Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginSetPremiumBlobTier : Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetPremiumBlobTier : Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudPageBlob.BeginSetPremiumBlobTier (premiumPageBlobTier, options, operationContext, callback, state)" />
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
        <Parameter Name="premiumPageBlobTier" Type="Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="premiumPageBlobTier">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</param>
        <param name="options">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> 、要求の追加オプションを指定するオブジェクトまたは<c>null</c>です。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            Premium blob の層に設定する非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetSequenceNumber">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetSequenceNumber (Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction sequenceNumberAction, Nullable&lt;long&gt; sequenceNumber, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetSequenceNumber(valuetype Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction sequenceNumberAction, valuetype System.Nullable`1&lt;int64&gt; sequenceNumber, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.BeginSetSequenceNumber(Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction,System.Nullable{System.Int64},System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginSetSequenceNumber : Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction * Nullable&lt;int64&gt; * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetSequenceNumber : Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction * Nullable&lt;int64&gt; * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudPageBlob.BeginSetSequenceNumber (sequenceNumberAction, sequenceNumber, callback, state)" />
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
        <Parameter Name="sequenceNumberAction" Type="Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction" />
        <Parameter Name="sequenceNumber" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="sequenceNumberAction">型の値<see cref="T:Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction" />、シーケンス番号に対して実行する操作を示すです。</param>
        <param name="sequenceNumber">シーケンス番号。 このパラメーターに設定<c>null</c>場合<paramref name="sequenceNumberAction" />と等しい<see cref="F:SequenceNumberAction.Increment" />です。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            ページ blob のシーケンス番号を設定する非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetSequenceNumber">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetSequenceNumber (Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction sequenceNumberAction, Nullable&lt;long&gt; sequenceNumber, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetSequenceNumber(valuetype Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction sequenceNumberAction, valuetype System.Nullable`1&lt;int64&gt; sequenceNumber, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.BeginSetSequenceNumber(Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction,System.Nullable{System.Int64},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginSetSequenceNumber : Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetSequenceNumber : Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudPageBlob.BeginSetSequenceNumber (sequenceNumberAction, sequenceNumber, accessCondition, options, operationContext, callback, state)" />
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
        <Parameter Name="sequenceNumberAction" Type="Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction" />
        <Parameter Name="sequenceNumber" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="sequenceNumberAction">型の値<see cref="T:Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction" />、シーケンス番号に対して実行する操作を示すです。</param>
        <param name="sequenceNumber">シーケンス番号。 このパラメーターに設定<c>null</c>場合<paramref name="sequenceNumberAction" />と等しい<see cref="F:SequenceNumberAction.Increment" />です。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            ページ blob のシーケンス番号を設定する非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStartCopy">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginStartCopy (Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob source, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginStartCopy(class Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob source, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.BeginStartCopy(Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginStartCopy (source As CloudPageBlob, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="override this.BeginStartCopy : Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudPageBlob.BeginStartCopy (source, callback, state)" />
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
        <Parameter Name="source" Type="Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="source"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />コピー元 blob はします。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            このページ blob に別のページ blob の内容、プロパティ、およびメタデータのコピーを開始する非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStartCopy">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginStartCopy (Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob source, Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginStartCopy(class Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob source, class Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, class Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.BeginStartCopy(Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="override this.BeginStartCopy : Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudPageBlob.BeginStartCopy (source, sourceAccessCondition, destAccessCondition, options, operationContext, callback, state)" />
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
        <Parameter Name="source" Type="Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />
        <Parameter Name="sourceAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="destAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="source"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />コピー元 blob はします。</param>
        <param name="sourceAccessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー元 blob のアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="destAccessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー先 blob のアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            このページ blob に別のページ blob の内容、プロパティ、およびメタデータのコピーを開始する非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStartCopy">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginStartCopy (Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob source, Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; premiumPageBlobTier, Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginStartCopy(class Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob source, valuetype System.Nullable`1&lt;valuetype Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; premiumPageBlobTier, class Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, class Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.BeginStartCopy(Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob,System.Nullable{Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="override this.BeginStartCopy : Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob * Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudPageBlob.BeginStartCopy (source, premiumPageBlobTier, sourceAccessCondition, destAccessCondition, options, operationContext, callback, state)" />
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
        <Parameter Name="source" Type="Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />
        <Parameter Name="premiumPageBlobTier" Type="System.Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt;" />
        <Parameter Name="sourceAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="destAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="source"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />コピー元 blob はします。</param>
        <param name="premiumPageBlobTier">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</param>
        <param name="sourceAccessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー元 blob のアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="destAccessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー先 blob のアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            このページ blob に別のページ blob の内容、プロパティ、およびメタデータのコピーを開始する非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStartIncrementalCopy">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginStartIncrementalCopy (Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob sourceSnapshot, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginStartIncrementalCopy(class Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob sourceSnapshot, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.BeginStartIncrementalCopy(Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginStartIncrementalCopy (sourceSnapshot As CloudPageBlob, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginStartIncrementalCopy : Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginStartIncrementalCopy : Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudPageBlob.BeginStartIncrementalCopy (sourceSnapshot, callback, state)" />
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
        <Parameter Name="sourceSnapshot" Type="Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="sourceSnapshot"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />コピー元 blob がスナップショットである必要があります。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            別のページ blob の内容、プロパティ、およびページ blob のメタデータの増分のコピーを開始する非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStartIncrementalCopy">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginStartIncrementalCopy (Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob sourceSnapshot, Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginStartIncrementalCopy(class Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob sourceSnapshot, class Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.BeginStartIncrementalCopy(Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginStartIncrementalCopy : Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginStartIncrementalCopy : Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudPageBlob.BeginStartIncrementalCopy (sourceSnapshot, destAccessCondition, options, operationContext, callback, state)" />
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
        <Parameter Name="sourceSnapshot" Type="Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />
        <Parameter Name="destAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="sourceSnapshot"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />コピー元 blob がスナップショットである必要があります。</param>
        <param name="destAccessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー先 blob のアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            別のページ blob の内容、プロパティ、およびページ blob のメタデータの増分のコピーを開始する非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStartIncrementalCopy">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginStartIncrementalCopy (Uri sourceSnapshot, Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginStartIncrementalCopy(class System.Uri sourceSnapshot, class Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.BeginStartIncrementalCopy(System.Uri,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginStartIncrementalCopy : Uri * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginStartIncrementalCopy : Uri * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudPageBlob.BeginStartIncrementalCopy (sourceSnapshot, destAccessCondition, options, operationContext, callback, state)" />
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
        <Parameter Name="sourceSnapshot" Type="System.Uri" />
        <Parameter Name="destAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="sourceSnapshot"><see cref="T:System.Uri" />のコピー元 blob スナップショットをする必要があります。</param>
        <param name="destAccessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー先 blob のアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            この blob を別の blob の内容、プロパティ、およびメタデータのコピーを開始する非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUploadFromByteArray">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromByteArray (byte[] buffer, int index, int count, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromByteArray(unsigned int8[] buffer, int32 index, int32 count, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.BeginUploadFromByteArray(System.Byte[],System.Int32,System.Int32,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginUploadFromByteArray (buffer As Byte(), index As Integer, count As Integer, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginUploadFromByteArray : byte[] * int * int * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginUploadFromByteArray : byte[] * int * int * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudPageBlob.BeginUploadFromByteArray (buffer, index, count, callback, state)" />
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
            バイト配列の内容をページ blob にアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUploadFromByteArray">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromByteArray (byte[] buffer, int index, int count, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromByteArray(unsigned int8[] buffer, int32 index, int32 count, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.BeginUploadFromByteArray(System.Byte[],System.Int32,System.Int32,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginUploadFromByteArray : byte[] * int * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginUploadFromByteArray : byte[] * int * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudPageBlob.BeginUploadFromByteArray (buffer, index, count, accessCondition, options, operationContext, callback, state)" />
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
            バイト配列の内容をページ blob にアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUploadFromByteArray">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromByteArray (byte[] buffer, int index, int count, Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; premiumPageBlobTier, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromByteArray(unsigned int8[] buffer, int32 index, int32 count, valuetype System.Nullable`1&lt;valuetype Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; premiumPageBlobTier, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.BeginUploadFromByteArray(System.Byte[],System.Int32,System.Int32,System.Nullable{Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginUploadFromByteArray : byte[] * int * int * Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginUploadFromByteArray : byte[] * int * int * Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudPageBlob.BeginUploadFromByteArray (buffer, index, count, premiumPageBlobTier, accessCondition, options, operationContext, callback, state)" />
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
        <Parameter Name="premiumPageBlobTier" Type="System.Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt;" />
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
        <param name="premiumPageBlobTier">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            バイト配列の内容をページ blob にアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUploadFromFile">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromFile (string path, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromFile(string path, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.BeginUploadFromFile(System.String,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginUploadFromFile (path As String, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginUploadFromFile : string * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginUploadFromFile : string * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudPageBlob.BeginUploadFromFile (path, callback, state)" />
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
            ページ blob にファイルをアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUploadFromFile">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromFile (string path, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromFile(string path, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.BeginUploadFromFile(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginUploadFromFile : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginUploadFromFile : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudPageBlob.BeginUploadFromFile (path, accessCondition, options, operationContext, callback, state)" />
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
            ページ blob にファイルをアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUploadFromFile">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromFile (string path, Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; premiumPageBlobTier, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromFile(string path, valuetype System.Nullable`1&lt;valuetype Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; premiumPageBlobTier, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.BeginUploadFromFile(System.String,System.Nullable{Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginUploadFromFile : string * Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginUploadFromFile : string * Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudPageBlob.BeginUploadFromFile (path, premiumPageBlobTier, accessCondition, options, operationContext, callback, state)" />
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
        <Parameter Name="premiumPageBlobTier" Type="System.Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="path">Blob コンテンツを提供するファイルのパスを含む文字列。</param>
        <param name="premiumPageBlobTier">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            ページ blob にファイルをアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUploadFromStream">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromStream (System.IO.Stream source, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromStream(class System.IO.Stream source, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.BeginUploadFromStream(System.IO.Stream,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginUploadFromStream (source As Stream, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginUploadFromStream : System.IO.Stream * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginUploadFromStream : System.IO.Stream * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudPageBlob.BeginUploadFromStream (source, callback, state)" />
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
            ページ blob にストリームをアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUploadFromStream">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromStream (System.IO.Stream source, long length, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromStream(class System.IO.Stream source, int64 length, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.BeginUploadFromStream(System.IO.Stream,System.Int64,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginUploadFromStream (source As Stream, length As Long, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginUploadFromStream : System.IO.Stream * int64 * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginUploadFromStream : System.IO.Stream * int64 * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudPageBlob.BeginUploadFromStream (source, length, callback, state)" />
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
            ページ blob にストリームをアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUploadFromStream">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromStream (System.IO.Stream source, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromStream(class System.IO.Stream source, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.BeginUploadFromStream(System.IO.Stream,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginUploadFromStream : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginUploadFromStream : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudPageBlob.BeginUploadFromStream (source, accessCondition, options, operationContext, callback, state)" />
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
            ページ blob にストリームをアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUploadFromStream">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromStream (System.IO.Stream source, long length, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromStream(class System.IO.Stream source, int64 length, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.BeginUploadFromStream(System.IO.Stream,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginUploadFromStream : System.IO.Stream * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginUploadFromStream : System.IO.Stream * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudPageBlob.BeginUploadFromStream (source, length, accessCondition, options, operationContext, callback, state)" />
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
            ページ blob にストリームをアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUploadFromStream">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromStream (System.IO.Stream source, Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; premiumPageBlobTier, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromStream(class System.IO.Stream source, valuetype System.Nullable`1&lt;valuetype Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; premiumPageBlobTier, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.BeginUploadFromStream(System.IO.Stream,System.Nullable{Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginUploadFromStream : System.IO.Stream * Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginUploadFromStream : System.IO.Stream * Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudPageBlob.BeginUploadFromStream (source, premiumPageBlobTier, accessCondition, options, operationContext, callback, state)" />
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
        <Parameter Name="premiumPageBlobTier" Type="System.Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="source">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</param>
        <param name="premiumPageBlobTier">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            ページ blob にストリームをアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUploadFromStream">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromStream (System.IO.Stream source, long length, Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; premiumPageBlobTier, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromStream(class System.IO.Stream source, int64 length, valuetype System.Nullable`1&lt;valuetype Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; premiumPageBlobTier, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.BeginUploadFromStream(System.IO.Stream,System.Int64,System.Nullable{Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginUploadFromStream : System.IO.Stream * int64 * Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginUploadFromStream : System.IO.Stream * int64 * Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudPageBlob.BeginUploadFromStream (source, length, premiumPageBlobTier, accessCondition, options, operationContext, callback, state)" />
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
        <Parameter Name="premiumPageBlobTier" Type="System.Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="source">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</param>
        <param name="length">開始位置からアップロードするストリームのソースからのバイト数を指定します。</param>
        <param name="premiumPageBlobTier">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            ページ blob にストリームをアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginWritePages">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginWritePages (System.IO.Stream pageData, long startOffset, string contentMD5, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginWritePages(class System.IO.Stream pageData, int64 startOffset, string contentMD5, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.BeginWritePages(System.IO.Stream,System.Int64,System.String,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginWritePages (pageData As Stream, startOffset As Long, contentMD5 As String, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginWritePages : System.IO.Stream * int64 * string * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginWritePages : System.IO.Stream * int64 * string * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudPageBlob.BeginWritePages (pageData, startOffset, contentMD5, callback, state)" />
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
        <Parameter Name="pageData" Type="System.IO.Stream" />
        <Parameter Name="startOffset" Type="System.Int64" />
        <Parameter Name="contentMD5" Type="System.String" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="pageData">A<see cref="T:System.IO.Stream" />ページ データを提供するオブジェクト。</param>
        <param name="startOffset">バイト単位での書き込みを開始するオフセットです。 オフセットは 512 の倍数である必要があります。</param>
        <param name="contentMD5">ページのトランザクションの整合性を確保するために使用する省略可能なハッシュ値です。 あります<c>null</c>または空の文字列。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            ページ blob にページを書き込む非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>
            クライアントは、ネットワーク上でトランザクションの整合性を確保するための手段として特定のページの書き込み操作の content-md5 ヘッダーを送信できます。 <paramref name="contentMD5" />パラメーターにより、クライアントは、指定したバイトの範囲に提供することを事前に計算された MD5 値へのアクセスを既に持っています。
            場合、<see cref="P:BlobRequestOptions.UseTransactionalMd5" />プロパティに設定されている<c>true</c>と<paramref name="contentMD5" />にパラメーターが設定されている<c>null</c>、クライアント ライブラリが MD5 値を内部で計算し、します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginWritePages">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginWritePages (System.IO.Stream pageData, long startOffset, string contentMD5, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginWritePages(class System.IO.Stream pageData, int64 startOffset, string contentMD5, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.BeginWritePages(System.IO.Stream,System.Int64,System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginWritePages : System.IO.Stream * int64 * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginWritePages : System.IO.Stream * int64 * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudPageBlob.BeginWritePages (pageData, startOffset, contentMD5, accessCondition, options, operationContext, callback, state)" />
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
        <Parameter Name="pageData" Type="System.IO.Stream" />
        <Parameter Name="startOffset" Type="System.Int64" />
        <Parameter Name="contentMD5" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="pageData">A<see cref="T:System.IO.Stream" />ページ データを提供するオブジェクト。</param>
        <param name="startOffset">バイト単位での書き込みを開始するオフセットです。 オフセットは 512 の倍数である必要があります。</param>
        <param name="contentMD5">ページのトランザクションの整合性を確保するために使用する省略可能なハッシュ値です。 あります<c>null</c>または空の文字列。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            ページ blob にページを書き込む非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>
            クライアントは、ネットワーク上でトランザクションの整合性を確保するための手段として特定のページの書き込み操作の content-md5 ヘッダーを送信できます。 <paramref name="contentMD5" />パラメーターにより、クライアントは、指定したバイトの範囲に提供することを事前に計算された MD5 値へのアクセスを既に持っています。
            場合、<see cref="P:BlobRequestOptions.UseTransactionalMd5" />プロパティに設定されている<c>true</c>と<paramref name="contentMD5" />にパラメーターが設定されている<c>null</c>、クライアント ライブラリが MD5 値を内部で計算し、します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ClearPages">
      <MemberSignature Language="C#" Value="public virtual void ClearPages (long startOffset, long length, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ClearPages(int64 startOffset, int64 length, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.ClearPages(System.Int64,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ClearPages : int64 * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.ClearPages : int64 * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudPageBlob.ClearPages (startOffset, length, accessCondition, options, operationContext)" />
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
        <Parameter Name="startOffset" Type="System.Int64" />
        <Parameter Name="length" Type="System.Int64" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="startOffset">(バイト単位) のページの消去を開始するオフセットです。 オフセットは 512 の倍数である必要があります。</param>
        <param name="length">(バイト単位) をクリアするデータ範囲の長さ。 長さは 512 の倍数である必要があります。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。 場合<c>null</c>既定のオプションは、要求に適用されます。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            ページ blob からページを消去します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClearPagesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task ClearPagesAsync (long startOffset, long length);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ClearPagesAsync(int64 startOffset, int64 length) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.ClearPagesAsync(System.Int64,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ClearPagesAsync (startOffset As Long, length As Long) As Task" />
      <MemberSignature Language="F#" Value="abstract member ClearPagesAsync : int64 * int64 -&gt; System.Threading.Tasks.Task&#xA;override this.ClearPagesAsync : int64 * int64 -&gt; System.Threading.Tasks.Task" Usage="cloudPageBlob.ClearPagesAsync (startOffset, length)" />
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
        <Parameter Name="startOffset" Type="System.Int64" />
        <Parameter Name="length" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="startOffset">(バイト単位) のページの消去を開始するオフセットです。 オフセットは 512 の倍数である必要があります。</param>
        <param name="length">(バイト単位) をクリアするデータ範囲の長さ。 長さは 512 の倍数である必要があります。</param>
        <summary>
            ページ blob からページを消去する非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClearPagesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task ClearPagesAsync (long startOffset, long length, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ClearPagesAsync(int64 startOffset, int64 length, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.ClearPagesAsync(System.Int64,System.Int64,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ClearPagesAsync : int64 * int64 * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.ClearPagesAsync : int64 * int64 * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPageBlob.ClearPagesAsync (startOffset, length, cancellationToken)" />
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
        <Parameter Name="startOffset" Type="System.Int64" />
        <Parameter Name="length" Type="System.Int64" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="startOffset">(バイト単位) のページの消去を開始するオフセットです。 オフセットは 512 の倍数である必要があります。</param>
        <param name="length">(バイト単位) をクリアするデータ範囲の長さ。 長さは 512 の倍数である必要があります。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            ページ blob からページを消去する非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClearPagesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task ClearPagesAsync (long startOffset, long length, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ClearPagesAsync(int64 startOffset, int64 length, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.ClearPagesAsync(System.Int64,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ClearPagesAsync : int64 * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.ClearPagesAsync : int64 * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudPageBlob.ClearPagesAsync (startOffset, length, accessCondition, options, operationContext)" />
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
        <Parameter Name="startOffset" Type="System.Int64" />
        <Parameter Name="length" Type="System.Int64" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="startOffset">(バイト単位) のページの消去を開始するオフセットです。 オフセットは 512 の倍数である必要があります。</param>
        <param name="length">(バイト単位) をクリアするデータ範囲の長さ。 長さは 512 の倍数である必要があります。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            ページ blob からページを消去する非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClearPagesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task ClearPagesAsync (long startOffset, long length, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ClearPagesAsync(int64 startOffset, int64 length, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.ClearPagesAsync(System.Int64,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ClearPagesAsync : int64 * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.ClearPagesAsync : int64 * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPageBlob.ClearPagesAsync (startOffset, length, accessCondition, options, operationContext, cancellationToken)" />
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
        <Parameter Name="startOffset" Type="System.Int64" />
        <Parameter Name="length" Type="System.Int64" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="startOffset">(バイト単位) のページの消去を開始するオフセットです。 オフセットは 512 の倍数である必要があります。</param>
        <param name="length">(バイト単位) をクリアするデータ範囲の長さ。 長さは 512 の倍数である必要があります。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            ページ blob からページを消去する非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public virtual void Create (long size, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Create(int64 size, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.Create(System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member Create : int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.Create : int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudPageBlob.Create (size, accessCondition, options, operationContext)" />
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
        <Parameter Name="size" Type="System.Int64" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="size">(バイト単位)、ページ blob の最大サイズ。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。 場合<c>null</c>既定のオプションは、要求に適用されます。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            ページ blob を作成します。 Blob が既に存在する場合はこの操作によって上書きされます。 渡す、上書きする代わりに、blob が存在する場合に例外をスローする、<see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />オブジェクトを使用して生成<see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />です。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public virtual void Create (long size, Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; premiumPageBlobTier, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Create(int64 size, valuetype System.Nullable`1&lt;valuetype Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; premiumPageBlobTier, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.Create(System.Int64,System.Nullable{Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member Create : int64 * Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.Create : int64 * Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudPageBlob.Create (size, premiumPageBlobTier, accessCondition, options, operationContext)" />
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
        <Parameter Name="size" Type="System.Int64" />
        <Parameter Name="premiumPageBlobTier" Type="System.Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="size">(バイト単位)、ページ blob の最大サイズ。</param>
        <param name="premiumPageBlobTier">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。 場合<c>null</c>既定のオプションは、要求に適用されます。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            ページ blob を作成します。 Blob が既に存在する場合はこの操作によって上書きされます。 渡す、上書きする代わりに、blob が存在する場合に例外をスローする、<see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />オブジェクトを使用して生成<see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />です。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateAsync (long size);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateAsync(int64 size) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.CreateAsync(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function CreateAsync (size As Long) As Task" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : int64 -&gt; System.Threading.Tasks.Task&#xA;override this.CreateAsync : int64 -&gt; System.Threading.Tasks.Task" Usage="cloudPageBlob.CreateAsync size" />
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
        <Parameter Name="size" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="size">(バイト単位)、blob の最大サイズ。</param>
        <summary>
            ページ blob を作成する非同期操作を開始します。 Blob が既に存在する場合はこの操作によって上書きされます。 使用して、上書きする代わりに、blob が存在する場合に例外をスローする<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.CreateAsync(System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />です。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateAsync (long size, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateAsync(int64 size, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.CreateAsync(System.Int64,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : int64 * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.CreateAsync : int64 * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPageBlob.CreateAsync (size, cancellationToken)" />
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
        <Parameter Name="size" Type="System.Int64" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="size">(バイト単位)、blob の最大サイズ。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            ページ blob を作成する非同期操作を開始します。 Blob が既に存在する場合はこの操作によって上書きされます。 使用して、上書きする代わりに、blob が存在する場合に例外をスローする<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.CreateAsync(System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />です。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateAsync (long size, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateAsync(int64 size, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.CreateAsync(System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.CreateAsync : int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudPageBlob.CreateAsync (size, accessCondition, options, operationContext)" />
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
        <Parameter Name="size" Type="System.Int64" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="size">(バイト単位)、blob の最大サイズ。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            ページ blob を作成する非同期操作を開始します。 Blob が既に存在する場合はこの操作によって上書きされます。 渡す、上書きする代わりに、blob が存在する場合に例外をスローする、<see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />オブジェクトを使用して生成<see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />です。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateAsync (long size, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateAsync(int64 size, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.CreateAsync(System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.CreateAsync : int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPageBlob.CreateAsync (size, accessCondition, options, operationContext, cancellationToken)" />
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
        <Parameter Name="size" Type="System.Int64" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="size">(バイト単位)、blob の最大サイズ。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            ページ blob を作成する非同期操作を開始します。 Blob が既に存在する場合はこの操作によって上書きされます。 渡す、上書きする代わりに、blob が存在する場合に例外をスローする、<see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />オブジェクトを使用して生成<see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />です。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateAsync (long size, Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; premiumPageBlobTier, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateAsync(int64 size, valuetype System.Nullable`1&lt;valuetype Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; premiumPageBlobTier, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.CreateAsync(System.Int64,System.Nullable{Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : int64 * Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.CreateAsync : int64 * Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPageBlob.CreateAsync (size, premiumPageBlobTier, accessCondition, options, operationContext, cancellationToken)" />
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
        <Parameter Name="size" Type="System.Int64" />
        <Parameter Name="premiumPageBlobTier" Type="System.Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="size">(バイト単位)、blob の最大サイズ。</param>
        <param name="premiumPageBlobTier">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            ページ blob を作成する非同期操作を開始します。 Blob が既に存在する場合はこの操作によって上書きされます。 渡す、上書きする代わりに、blob が存在する場合に例外をスローする、<see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />オブジェクトを使用して生成<see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />です。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSnapshot">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob CreateSnapshot (System.Collections.Generic.IDictionary&lt;string,string&gt; metadata = null, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob CreateSnapshot(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; metadata, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.CreateSnapshot(System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member CreateSnapshot : System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob&#xA;override this.CreateSnapshot : System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" Usage="cloudPageBlob.CreateSnapshot (metadata, accessCondition, options, operationContext)" />
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
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob</ReturnType>
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
        <returns>A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" /> blob のスナップショットであるオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSnapshotAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob&gt; CreateSnapshotAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob&gt; CreateSnapshotAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.CreateSnapshotAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function CreateSnapshotAsync () As Task(Of CloudPageBlob)" />
      <MemberSignature Language="F#" Value="abstract member CreateSnapshotAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob&gt;&#xA;override this.CreateSnapshotAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob&gt;" Usage="cloudPageBlob.CreateSnapshotAsync " />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Blob のスナップショットを作成する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSnapshotAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob&gt; CreateSnapshotAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob&gt; CreateSnapshotAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.CreateSnapshotAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateSnapshotAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob&gt;&#xA;override this.CreateSnapshotAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob&gt;" Usage="cloudPageBlob.CreateSnapshotAsync cancellationToken" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            Blob のスナップショットを作成する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSnapshotAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob&gt; CreateSnapshotAsync (System.Collections.Generic.IDictionary&lt;string,string&gt; metadata, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob&gt; CreateSnapshotAsync(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; metadata, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.CreateSnapshotAsync(System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member CreateSnapshotAsync : System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob&gt;&#xA;override this.CreateSnapshotAsync : System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob&gt;" Usage="cloudPageBlob.CreateSnapshotAsync (metadata, accessCondition, options, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob&gt;</ReturnType>
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
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSnapshotAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob&gt; CreateSnapshotAsync (System.Collections.Generic.IDictionary&lt;string,string&gt; metadata, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob&gt; CreateSnapshotAsync(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; metadata, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.CreateSnapshotAsync(System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateSnapshotAsync : System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob&gt;&#xA;override this.CreateSnapshotAsync : System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob&gt;" Usage="cloudPageBlob.CreateSnapshotAsync (metadata, accessCondition, options, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob&gt;</ReturnType>
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
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndClearPages">
      <MemberSignature Language="C#" Value="public virtual void EndClearPages (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndClearPages(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.EndClearPages(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndClearPages (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndClearPages : IAsyncResult -&gt; unit&#xA;override this.EndClearPages : IAsyncResult -&gt; unit" Usage="cloudPageBlob.EndClearPages asyncResult" />
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
            ページ blob からページを消去する非同期操作を終了します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndCreate">
      <MemberSignature Language="C#" Value="public virtual void EndCreate (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndCreate(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.EndCreate(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndCreate (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndCreate : IAsyncResult -&gt; unit&#xA;override this.EndCreate : IAsyncResult -&gt; unit" Usage="cloudPageBlob.EndCreate asyncResult" />
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
            ページ blob を作成する非同期操作を終了します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndCreateSnapshot">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob EndCreateSnapshot (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob EndCreateSnapshot(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.EndCreateSnapshot(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndCreateSnapshot (asyncResult As IAsyncResult) As CloudPageBlob" />
      <MemberSignature Language="F#" Value="abstract member EndCreateSnapshot : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob&#xA;override this.EndCreateSnapshot : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" Usage="cloudPageBlob.EndCreateSnapshot asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</param>
        <summary>
            Blob のスナップショットを作成する非同期操作を終了します。
            </summary>
        <returns>A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" /> blob のスナップショットであるオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndGetPageRanges">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.PageRange&gt; EndGetPageRanges (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.PageRange&gt; EndGetPageRanges(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.EndGetPageRanges(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndGetPageRanges (asyncResult As IAsyncResult) As IEnumerable(Of PageRange)" />
      <MemberSignature Language="F#" Value="abstract member EndGetPageRanges : IAsyncResult -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Blob.PageRange&gt;&#xA;override this.EndGetPageRanges : IAsyncResult -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Blob.PageRange&gt;" Usage="cloudPageBlob.EndGetPageRanges asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.PageRange&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</param>
        <summary>
            有効なページ範囲の開始および終了バイトのコレクションを返す非同期操作を終了します。
            </summary>
        <returns>ページ範囲の列挙可能なコレクション。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndGetPageRangesDiff">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.PageDiffRange&gt; EndGetPageRangesDiff (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.PageDiffRange&gt; EndGetPageRangesDiff(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.EndGetPageRangesDiff(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndGetPageRangesDiff (asyncResult As IAsyncResult) As IEnumerable(Of PageDiffRange)" />
      <MemberSignature Language="F#" Value="abstract member EndGetPageRangesDiff : IAsyncResult -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Blob.PageDiffRange&gt;&#xA;override this.EndGetPageRangesDiff : IAsyncResult -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Blob.PageDiffRange&gt;" Usage="cloudPageBlob.EndGetPageRangesDiff asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.PageDiffRange&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</param>
        <summary>
            指定したスナップショットとこのオブジェクトの間で異なるページ範囲のコレクションを取得する非同期操作を終了します。
            </summary>
        <returns>ページ範囲の列挙可能なコレクション。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndOpenWrite">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream EndOpenWrite (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream EndOpenWrite(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.EndOpenWrite(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndOpenWrite (asyncResult As IAsyncResult) As CloudBlobStream" />
      <MemberSignature Language="F#" Value="abstract member EndOpenWrite : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&#xA;override this.EndOpenWrite : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" Usage="cloudPageBlob.EndOpenWrite asyncResult" />
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
    <Member MemberName="EndResize">
      <MemberSignature Language="C#" Value="public virtual void EndResize (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndResize(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.EndResize(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndResize (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndResize : IAsyncResult -&gt; unit&#xA;override this.EndResize : IAsyncResult -&gt; unit" Usage="cloudPageBlob.EndResize asyncResult" />
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
            ページ blob のサイズを変更する非同期操作を終了します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndSetPremiumBlobTier">
      <MemberSignature Language="C#" Value="public virtual void EndSetPremiumBlobTier (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndSetPremiumBlobTier(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.EndSetPremiumBlobTier(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndSetPremiumBlobTier (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndSetPremiumBlobTier : IAsyncResult -&gt; unit&#xA;override this.EndSetPremiumBlobTier : IAsyncResult -&gt; unit" Usage="cloudPageBlob.EndSetPremiumBlobTier asyncResult" />
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
            Premium blob の層に設定する非同期操作を終了します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndSetSequenceNumber">
      <MemberSignature Language="C#" Value="public virtual void EndSetSequenceNumber (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndSetSequenceNumber(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.EndSetSequenceNumber(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndSetSequenceNumber (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndSetSequenceNumber : IAsyncResult -&gt; unit&#xA;override this.EndSetSequenceNumber : IAsyncResult -&gt; unit" Usage="cloudPageBlob.EndSetSequenceNumber asyncResult" />
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
            ページ blob のシーケンス番号を設定する非同期操作を終了します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndStartIncrementalCopy">
      <MemberSignature Language="C#" Value="public virtual string EndStartIncrementalCopy (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string EndStartIncrementalCopy(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.EndStartIncrementalCopy(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndStartIncrementalCopy (asyncResult As IAsyncResult) As String" />
      <MemberSignature Language="F#" Value="abstract member EndStartIncrementalCopy : IAsyncResult -&gt; string&#xA;override this.EndStartIncrementalCopy : IAsyncResult -&gt; string" Usage="cloudPageBlob.EndStartIncrementalCopy asyncResult" />
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
            別の blob の内容、プロパティ、および blob のメタデータの増分のコピーを開始する非同期操作を終了します。
            </summary>
        <returns>コピー操作に関連付けられたコピー ID を表す文字列。</returns>
        <remarks>
            このメソッドは、blob の ETag、最終更新時刻、および一部のコピー状態をフェッチします。
            コピー ID とコピーのステータス フィールドがフェッチされ、残りのコピーの状態がクリアされます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EndUploadFromByteArray">
      <MemberSignature Language="C#" Value="public virtual void EndUploadFromByteArray (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndUploadFromByteArray(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.EndUploadFromByteArray(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndUploadFromByteArray (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndUploadFromByteArray : IAsyncResult -&gt; unit&#xA;override this.EndUploadFromByteArray : IAsyncResult -&gt; unit" Usage="cloudPageBlob.EndUploadFromByteArray asyncResult" />
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
            バイト配列の内容をページ blob にアップロードする非同期操作を終了します。 Blob が既に存在する場合は上書きされます。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndUploadFromFile">
      <MemberSignature Language="C#" Value="public virtual void EndUploadFromFile (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndUploadFromFile(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.EndUploadFromFile(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndUploadFromFile (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndUploadFromFile : IAsyncResult -&gt; unit&#xA;override this.EndUploadFromFile : IAsyncResult -&gt; unit" Usage="cloudPageBlob.EndUploadFromFile asyncResult" />
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
            ページ blob にファイルをアップロードする非同期操作を終了します。 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndUploadFromStream">
      <MemberSignature Language="C#" Value="public virtual void EndUploadFromStream (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndUploadFromStream(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.EndUploadFromStream(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndUploadFromStream (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndUploadFromStream : IAsyncResult -&gt; unit&#xA;override this.EndUploadFromStream : IAsyncResult -&gt; unit" Usage="cloudPageBlob.EndUploadFromStream asyncResult" />
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
            ページ blob にストリームをアップロードする非同期操作を終了します。 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndWritePages">
      <MemberSignature Language="C#" Value="public virtual void EndWritePages (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndWritePages(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.EndWritePages(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndWritePages (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndWritePages : IAsyncResult -&gt; unit&#xA;override this.EndWritePages : IAsyncResult -&gt; unit" Usage="cloudPageBlob.EndWritePages asyncResult" />
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
            ページ blob にページを書き込む非同期操作を終了します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPageRanges">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.PageRange&gt; GetPageRanges (Nullable&lt;long&gt; offset = null, Nullable&lt;long&gt; length = null, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.PageRange&gt; GetPageRanges(valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;int64&gt; length, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.GetPageRanges(System.Nullable{System.Int64},System.Nullable{System.Int64},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetPageRanges : Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Blob.PageRange&gt;&#xA;override this.GetPageRanges : Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Blob.PageRange&gt;" Usage="cloudPageBlob.GetPageRanges (offset, length, accessCondition, options, operationContext)" />
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
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.PageRange&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="length" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="offset">するデータ範囲のリスト ページの範囲の開始オフセット (バイト単位)。 512 の倍数である必要があります。</param>
        <param name="length">リスト ページにどのデータ範囲の範囲の長さ (バイト単位)。 512 の倍数である必要があります。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。 場合<c>null</c>既定のオプションは、要求に適用されます。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            有効なページ範囲の開始および終了バイトのコレクションを取得します。
            </summary>
        <returns>ページ範囲の列挙可能なコレクション。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPageRangesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.PageRange&gt;&gt; GetPageRangesAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.PageRange&gt;&gt; GetPageRangesAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.GetPageRangesAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetPageRangesAsync () As Task(Of IEnumerable(Of PageRange))" />
      <MemberSignature Language="F#" Value="abstract member GetPageRangesAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Blob.PageRange&gt;&gt;&#xA;override this.GetPageRangesAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Blob.PageRange&gt;&gt;" Usage="cloudPageBlob.GetPageRangesAsync " />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.PageRange&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            ページ範囲の開始と終了バイトのコレクションを返す非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型の列挙可能なコレクションであるオブジェクトを<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PageRange" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPageRangesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.PageRange&gt;&gt; GetPageRangesAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.PageRange&gt;&gt; GetPageRangesAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.GetPageRangesAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetPageRangesAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Blob.PageRange&gt;&gt;&#xA;override this.GetPageRangesAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Blob.PageRange&gt;&gt;" Usage="cloudPageBlob.GetPageRangesAsync cancellationToken" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.PageRange&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            ページ範囲の開始と終了バイトのコレクションを返す非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型の列挙可能なコレクションであるオブジェクトを<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PageRange" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPageRangesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.PageRange&gt;&gt; GetPageRangesAsync (Nullable&lt;long&gt; offset, Nullable&lt;long&gt; length, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.PageRange&gt;&gt; GetPageRangesAsync(valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;int64&gt; length, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.GetPageRangesAsync(System.Nullable{System.Int64},System.Nullable{System.Int64},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetPageRangesAsync : Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Blob.PageRange&gt;&gt;&#xA;override this.GetPageRangesAsync : Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Blob.PageRange&gt;&gt;" Usage="cloudPageBlob.GetPageRangesAsync (offset, length, accessCondition, options, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.PageRange&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="length" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="offset">(バイト単位)、データ範囲の開始オフセット。 512 の倍数である必要があります。</param>
        <param name="length">(バイト単位)、データ範囲の長さ。 512 の倍数である必要があります。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            ページ範囲の開始と終了バイトのコレクションを返す非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型の列挙可能なコレクションであるオブジェクトを<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PageRange" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPageRangesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.PageRange&gt;&gt; GetPageRangesAsync (Nullable&lt;long&gt; offset, Nullable&lt;long&gt; length, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.PageRange&gt;&gt; GetPageRangesAsync(valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;int64&gt; length, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.GetPageRangesAsync(System.Nullable{System.Int64},System.Nullable{System.Int64},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetPageRangesAsync : Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Blob.PageRange&gt;&gt;&#xA;override this.GetPageRangesAsync : Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Blob.PageRange&gt;&gt;" Usage="cloudPageBlob.GetPageRangesAsync (offset, length, accessCondition, options, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.PageRange&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="length" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="offset">(バイト単位)、データ範囲の開始オフセット。 512 の倍数である必要があります。</param>
        <param name="length">(バイト単位)、データ範囲の長さ。 512 の倍数である必要があります。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            ページ範囲の開始と終了バイトのコレクションを返す非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型の列挙可能なコレクションであるオブジェクトを<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PageRange" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPageRangesDiff">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.PageDiffRange&gt; GetPageRangesDiff (DateTimeOffset previousSnapshotTime, Nullable&lt;long&gt; offset = null, Nullable&lt;long&gt; length = null, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.PageDiffRange&gt; GetPageRangesDiff(valuetype System.DateTimeOffset previousSnapshotTime, valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;int64&gt; length, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.GetPageRangesDiff(System.DateTimeOffset,System.Nullable{System.Int64},System.Nullable{System.Int64},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetPageRangesDiff : DateTimeOffset * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Blob.PageDiffRange&gt;&#xA;override this.GetPageRangesDiff : DateTimeOffset * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Blob.PageDiffRange&gt;" Usage="cloudPageBlob.GetPageRangesDiff (previousSnapshotTime, offset, length, accessCondition, options, operationContext)" />
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
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.PageDiffRange&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="previousSnapshotTime" Type="System.DateTimeOffset" />
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="length" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="previousSnapshotTime">A <see cref="T:System.DateTimeOffset" /> diff の開始点として使用する、スナップショットのタイムスタンプを表すこの CloudPageBlob を表す場合、スナップショット、previousSnapshotTime パラメーターは、現在のスナップショットのタイムスタンプより前でなければなりません。</param>
        <param name="offset">するデータ範囲のリスト ページの範囲の開始オフセット (バイト単位)。 512 の倍数である必要があります。</param>
        <param name="length">リスト ページにどのデータ範囲の範囲の長さ (バイト単位)。 512 の倍数である必要があります。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。 場合<c>null</c>既定のオプションは、要求に適用されます。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            このオブジェクトと指定したスナップショットの間で異なるページ範囲のコレクションを取得します。
            </summary>
        <returns>ページ範囲の列挙可能なコレクション。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPageRangesDiffAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.PageDiffRange&gt;&gt; GetPageRangesDiffAsync (DateTimeOffset previousSnapshotTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.PageDiffRange&gt;&gt; GetPageRangesDiffAsync(valuetype System.DateTimeOffset previousSnapshotTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.GetPageRangesDiffAsync(System.DateTimeOffset)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetPageRangesDiffAsync (previousSnapshotTime As DateTimeOffset) As Task(Of IEnumerable(Of PageDiffRange))" />
      <MemberSignature Language="F#" Value="abstract member GetPageRangesDiffAsync : DateTimeOffset -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Blob.PageDiffRange&gt;&gt;&#xA;override this.GetPageRangesDiffAsync : DateTimeOffset -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Blob.PageDiffRange&gt;&gt;" Usage="cloudPageBlob.GetPageRangesDiffAsync previousSnapshotTime" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.PageDiffRange&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="previousSnapshotTime" Type="System.DateTimeOffset" />
      </Parameters>
      <Docs>
        <param name="previousSnapshotTime">A <see cref="T:System.DateTimeOffset" /> diff の開始点として使用する、スナップショットのタイムスタンプを表すこの CloudPageBlob を表す場合、スナップショット、previousSnapshotTime パラメーターは、現在のスナップショットのタイムスタンプより前でなければなりません。</param>
        <summary>
            指定したスナップショットとこのオブジェクトの間で異なるページ範囲のコレクションを取得する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型の列挙可能なコレクションであるオブジェクトを<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PageRange" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPageRangesDiffAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.PageDiffRange&gt;&gt; GetPageRangesDiffAsync (DateTimeOffset previousSnapshotTime, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.PageDiffRange&gt;&gt; GetPageRangesDiffAsync(valuetype System.DateTimeOffset previousSnapshotTime, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.GetPageRangesDiffAsync(System.DateTimeOffset,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetPageRangesDiffAsync : DateTimeOffset * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Blob.PageDiffRange&gt;&gt;&#xA;override this.GetPageRangesDiffAsync : DateTimeOffset * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Blob.PageDiffRange&gt;&gt;" Usage="cloudPageBlob.GetPageRangesDiffAsync (previousSnapshotTime, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.PageDiffRange&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="previousSnapshotTime" Type="System.DateTimeOffset" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="previousSnapshotTime">A <see cref="T:System.DateTimeOffset" /> diff の開始点として使用する、スナップショットのタイムスタンプを表すこの CloudPageBlob を表す場合、スナップショット、previousSnapshotTime パラメーターは、現在のスナップショットのタイムスタンプより前でなければなりません。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            指定したスナップショットとこのオブジェクトの間で異なるページ範囲のコレクションを取得する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型の列挙可能なコレクションであるオブジェクトを<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PageRange" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPageRangesDiffAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.PageDiffRange&gt;&gt; GetPageRangesDiffAsync (DateTimeOffset previousSnapshotTime, Nullable&lt;long&gt; offset, Nullable&lt;long&gt; length, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.PageDiffRange&gt;&gt; GetPageRangesDiffAsync(valuetype System.DateTimeOffset previousSnapshotTime, valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;int64&gt; length, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.GetPageRangesDiffAsync(System.DateTimeOffset,System.Nullable{System.Int64},System.Nullable{System.Int64},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetPageRangesDiffAsync : DateTimeOffset * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Blob.PageDiffRange&gt;&gt;&#xA;override this.GetPageRangesDiffAsync : DateTimeOffset * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Blob.PageDiffRange&gt;&gt;" Usage="cloudPageBlob.GetPageRangesDiffAsync (previousSnapshotTime, offset, length, accessCondition, options, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.PageDiffRange&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="previousSnapshotTime" Type="System.DateTimeOffset" />
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="length" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="previousSnapshotTime">A <see cref="T:System.DateTimeOffset" /> diff の開始点として使用する、スナップショットのタイムスタンプを表すこの CloudPageBlob を表す場合、スナップショット、previousSnapshotTime パラメーターは、現在のスナップショットのタイムスタンプより前でなければなりません。</param>
        <param name="offset">(バイト単位)、データ範囲の開始オフセット。 512 の倍数である必要があります。</param>
        <param name="length">(バイト単位)、データ範囲の長さ。 512 の倍数である必要があります。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            指定したスナップショットとこのオブジェクトの間で異なるページ範囲のコレクションを取得する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型の列挙可能なコレクションであるオブジェクトを<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PageRange" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPageRangesDiffAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.PageDiffRange&gt;&gt; GetPageRangesDiffAsync (DateTimeOffset previousSnapshotTime, Nullable&lt;long&gt; offset, Nullable&lt;long&gt; length, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.PageDiffRange&gt;&gt; GetPageRangesDiffAsync(valuetype System.DateTimeOffset previousSnapshotTime, valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;int64&gt; length, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.GetPageRangesDiffAsync(System.DateTimeOffset,System.Nullable{System.Int64},System.Nullable{System.Int64},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetPageRangesDiffAsync : DateTimeOffset * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Blob.PageDiffRange&gt;&gt;&#xA;override this.GetPageRangesDiffAsync : DateTimeOffset * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Blob.PageDiffRange&gt;&gt;" Usage="cloudPageBlob.GetPageRangesDiffAsync (previousSnapshotTime, offset, length, accessCondition, options, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.PageDiffRange&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="previousSnapshotTime" Type="System.DateTimeOffset" />
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="length" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="previousSnapshotTime">A <see cref="T:System.DateTimeOffset" /> diff の開始点として使用する、スナップショットのタイムスタンプを表すこの CloudPageBlob を表す場合、スナップショット、previousSnapshotTime パラメーターは、現在のスナップショットのタイムスタンプより前でなければなりません。</param>
        <param name="offset">(バイト単位)、データ範囲の開始オフセット。 512 の倍数である必要があります。</param>
        <param name="length">(バイト単位)、データ範囲の長さ。 512 の倍数である必要があります。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            指定したスナップショットとこのオブジェクトの間で異なるページ範囲のコレクションを取得する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型の列挙可能なコレクションであるオブジェクトを<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PageRange" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenWrite">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream OpenWrite (Nullable&lt;long&gt; size, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream OpenWrite(valuetype System.Nullable`1&lt;int64&gt; size, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.OpenWrite(System.Nullable{System.Int64},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member OpenWrite : Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&#xA;override this.OpenWrite : Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" Usage="cloudPageBlob.OpenWrite (size, accessCondition, options, operationContext)" />
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
        <Parameter Name="size" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="size">(バイト単位)、ページ blob のサイズ。 サイズは 512 の倍数である必要があります。 場合<c>null</c>、ページ blob が既に存在する必要があります。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。 場合<c>null</c>既定のオプションは、要求に適用されます。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            Blob に書き込むためのストリームを開きます。 Blob が既に存在する場合は、blob 内の既存のデータが上書きされます。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" /> オブジェクト。</returns>
        <remarks>
          <para>このメソッドへの呼び出しを常に、注意してください、<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributes(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />内部的メソッドです。</para>
          <para>設定、 <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.StreamWriteSizeInBytes" /> mb 16 KB と 4 MB までの範囲のバイトの書き込みは、ブロック サイズを指定するには、このメソッドを呼び出す前に、プロパティです。</para>
          <para>これを上書きする代わりに blob が存在する場合は、例外をスロー、渡す、<see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />オブジェクトを使用して生成<see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenWriteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt; OpenWriteAsync (Nullable&lt;long&gt; size);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt; OpenWriteAsync(valuetype System.Nullable`1&lt;int64&gt; size) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.OpenWriteAsync(System.Nullable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function OpenWriteAsync (size As Nullable(Of Long)) As Task(Of CloudBlobStream)" />
      <MemberSignature Language="F#" Value="abstract member OpenWriteAsync : Nullable&lt;int64&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt;&#xA;override this.OpenWriteAsync : Nullable&lt;int64&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt;" Usage="cloudPageBlob.OpenWriteAsync size" />
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
        <Parameter Name="size" Type="System.Nullable&lt;System.Int64&gt;" />
      </Parameters>
      <Docs>
        <param name="size">(バイト単位)、ページ blob のサイズ。 サイズは 512 の倍数である必要があります。 場合<c>null</c>、ページ blob が既に存在する必要があります。</param>
        <summary>
            Blob に書き込むためのストリームを開く非同期操作を開始します。 Blob が既に存在する場合は、blob 内の既存のデータが上書きされます。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" />非同期操作を表すです。</returns>
        <remarks>
          <para>このメソッドへの呼び出しを常に、注意してください、<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributesAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />内部的メソッドです。</para>
          <para>設定、<see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.StreamWriteSizeInBytes" />書き込み mb 包括的な 512 ~ 4 MB までの範囲の 512 バイトの倍数では、ページ サイズを指定するには、このメソッドを呼び出す前に、プロパティです。</para>
          <para>例外をスローする、上書きすることではなく、blob が存在する場合は、次を参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.OpenWriteAsync(System.Nullable{System.Int64},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenWriteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt; OpenWriteAsync (Nullable&lt;long&gt; size, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt; OpenWriteAsync(valuetype System.Nullable`1&lt;int64&gt; size, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.OpenWriteAsync(System.Nullable{System.Int64},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OpenWriteAsync : Nullable&lt;int64&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt;&#xA;override this.OpenWriteAsync : Nullable&lt;int64&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt;" Usage="cloudPageBlob.OpenWriteAsync (size, cancellationToken)" />
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
        <Parameter Name="size" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="size">(バイト単位)、ページ blob のサイズ。 サイズは 512 の倍数である必要があります。 場合<c>null</c>、ページ blob が既に存在する必要があります。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            Blob に書き込むためのストリームを開く非同期操作を開始します。 Blob が既に存在する場合は、blob 内の既存のデータが上書きされます。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" />非同期操作を表すです。</returns>
        <remarks>
          <para>このメソッドへの呼び出しを常に、注意してください、<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributesAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />内部的メソッドです。</para>
          <para>設定、<see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.StreamWriteSizeInBytes" />書き込み mb 包括的な 512 ~ 4 MB までの範囲の 512 バイトの倍数では、ページ サイズを指定するには、このメソッドを呼び出す前に、プロパティです。</para>
          <para>例外をスローする、上書きすることではなく、blob が存在する場合は、次を参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.OpenWriteAsync(System.Nullable{System.Int64},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenWriteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt; OpenWriteAsync (Nullable&lt;long&gt; size, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt; OpenWriteAsync(valuetype System.Nullable`1&lt;int64&gt; size, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.OpenWriteAsync(System.Nullable{System.Int64},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member OpenWriteAsync : Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt;&#xA;override this.OpenWriteAsync : Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt;" Usage="cloudPageBlob.OpenWriteAsync (size, accessCondition, options, operationContext)" />
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
        <Parameter Name="size" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="size">(バイト単位)、ページ blob のサイズ。 サイズは 512 の倍数である必要があります。 場合<c>null</c>、ページ blob が既に存在する必要があります。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            Blob に書き込むためのストリームを開く非同期操作を開始します。 Blob が既に存在する場合は、blob 内の既存のデータが上書きされます。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" />非同期操作を表すです。</returns>
        <remarks>
          <para>このメソッドへの呼び出しを常に、注意してください、<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributesAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />内部的メソッドです。</para>
          <para>設定、<see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.StreamWriteSizeInBytes" />書き込み mb 包括的な 512 ~ 4 MB までの範囲の 512 バイトの倍数では、ページ サイズを指定するには、このメソッドを呼び出す前に、プロパティです。</para>
          <para>これを上書きする代わりに blob が存在する場合は、例外をスロー、渡す、<see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />オブジェクトを使用して生成<see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenWriteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt; OpenWriteAsync (Nullable&lt;long&gt; size, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt; OpenWriteAsync(valuetype System.Nullable`1&lt;int64&gt; size, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.OpenWriteAsync(System.Nullable{System.Int64},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OpenWriteAsync : Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt;&#xA;override this.OpenWriteAsync : Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt;" Usage="cloudPageBlob.OpenWriteAsync (size, accessCondition, options, operationContext, cancellationToken)" />
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
        <Parameter Name="size" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="size">(バイト単位)、ページ blob のサイズ。 サイズは 512 の倍数である必要があります。 場合<c>null</c>、ページ blob が既に存在する必要があります。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            Blob に書き込むためのストリームを開く非同期操作を開始します。 Blob が既に存在する場合は、blob 内の既存のデータが上書きされます。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" />非同期操作を表すです。</returns>
        <remarks>
          <para>このメソッドへの呼び出しを常に、注意してください、<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributesAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />内部的メソッドです。</para>
          <para>設定、<see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.StreamWriteSizeInBytes" />書き込み mb 包括的な 512 ~ 4 MB までの範囲の 512 バイトの倍数では、ページ サイズを指定するには、このメソッドを呼び出す前に、プロパティです。</para>
          <para>これを上書きする代わりに blob が存在する場合は、例外をスロー、渡す、<see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />オブジェクトを使用して生成<see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Resize">
      <MemberSignature Language="C#" Value="public virtual void Resize (long size, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Resize(int64 size, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.Resize(System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member Resize : int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.Resize : int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudPageBlob.Resize (size, accessCondition, options, operationContext)" />
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
        <Parameter Name="size" Type="System.Int64" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="size">(バイト単位)、ページ blob のサイズ。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。 場合<c>null</c>既定のオプションは、要求に適用されます。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            指定されたサイズにページ blob のサイズを変更します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResizeAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task ResizeAsync (long size);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ResizeAsync(int64 size) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.ResizeAsync(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ResizeAsync (size As Long) As Task" />
      <MemberSignature Language="F#" Value="abstract member ResizeAsync : int64 -&gt; System.Threading.Tasks.Task&#xA;override this.ResizeAsync : int64 -&gt; System.Threading.Tasks.Task" Usage="cloudPageBlob.ResizeAsync size" />
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
        <Parameter Name="size" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="size">(バイト単位)、blob のサイズ。</param>
        <summary>
            指定されたサイズにページ blob のサイズを変更する非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResizeAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task ResizeAsync (long size, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ResizeAsync(int64 size, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.ResizeAsync(System.Int64,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ResizeAsync : int64 * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.ResizeAsync : int64 * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPageBlob.ResizeAsync (size, cancellationToken)" />
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
        <Parameter Name="size" Type="System.Int64" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="size">(バイト単位)、blob のサイズ。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            指定されたサイズにページ blob のサイズを変更する非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResizeAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task ResizeAsync (long size, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ResizeAsync(int64 size, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.ResizeAsync(System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ResizeAsync : int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.ResizeAsync : int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudPageBlob.ResizeAsync (size, accessCondition, options, operationContext)" />
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
        <Parameter Name="size" Type="System.Int64" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="size">(バイト単位)、blob のサイズ。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            指定されたサイズにページ blob のサイズを変更する非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResizeAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task ResizeAsync (long size, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ResizeAsync(int64 size, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.ResizeAsync(System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ResizeAsync : int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.ResizeAsync : int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPageBlob.ResizeAsync (size, accessCondition, options, operationContext, cancellationToken)" />
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
        <Parameter Name="size" Type="System.Int64" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="size">(バイト単位)、blob のサイズ。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            指定されたサイズにページ blob のサイズを変更する非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPremiumBlobTier">
      <MemberSignature Language="C#" Value="public virtual void SetPremiumBlobTier (Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier premiumPageBlobTier, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SetPremiumBlobTier(valuetype Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier premiumPageBlobTier, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.SetPremiumBlobTier(Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetPremiumBlobTier : Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.SetPremiumBlobTier : Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudPageBlob.SetPremiumBlobTier (premiumPageBlobTier, options, operationContext)" />
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
        <Parameter Name="premiumPageBlobTier" Type="Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="premiumPageBlobTier">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</param>
        <param name="options">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> 、要求の追加オプションを指定するオブジェクトまたは<c>null</c>です。 場合<c>null</c>既定のオプションは、要求に適用されます。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            Premium blob の層を設定します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPremiumBlobTierAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetPremiumBlobTierAsync (Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier premiumPageBlobTier);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetPremiumBlobTierAsync(valuetype Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier premiumPageBlobTier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.SetPremiumBlobTierAsync(Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier)" />
      <MemberSignature Language="F#" Value="abstract member SetPremiumBlobTierAsync : Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier -&gt; System.Threading.Tasks.Task&#xA;override this.SetPremiumBlobTierAsync : Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier -&gt; System.Threading.Tasks.Task" Usage="cloudPageBlob.SetPremiumBlobTierAsync premiumPageBlobTier" />
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
        <Parameter Name="premiumPageBlobTier" Type="Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />
      </Parameters>
      <Docs>
        <param name="premiumPageBlobTier">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</param>
        <summary>
            Premium blob の層に設定する非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPremiumBlobTierAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetPremiumBlobTierAsync (Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier premiumPageBlobTier, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetPremiumBlobTierAsync(valuetype Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier premiumPageBlobTier, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.SetPremiumBlobTierAsync(Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetPremiumBlobTierAsync : Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetPremiumBlobTierAsync : Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPageBlob.SetPremiumBlobTierAsync (premiumPageBlobTier, cancellationToken)" />
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
        <Parameter Name="premiumPageBlobTier" Type="Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="premiumPageBlobTier">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            Premium blob の層に設定する非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPremiumBlobTierAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetPremiumBlobTierAsync (Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier premiumPageBlobTier, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetPremiumBlobTierAsync(valuetype Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier premiumPageBlobTier, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.SetPremiumBlobTierAsync(Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetPremiumBlobTierAsync : Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.SetPremiumBlobTierAsync : Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudPageBlob.SetPremiumBlobTierAsync (premiumPageBlobTier, options, operationContext)" />
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
        <Parameter Name="premiumPageBlobTier" Type="Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="premiumPageBlobTier">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            Premium blob の層に設定する非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPremiumBlobTierAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetPremiumBlobTierAsync (Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier premiumPageBlobTier, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetPremiumBlobTierAsync(valuetype Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier premiumPageBlobTier, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.SetPremiumBlobTierAsync(Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetPremiumBlobTierAsync : Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetPremiumBlobTierAsync : Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPageBlob.SetPremiumBlobTierAsync (premiumPageBlobTier, options, operationContext, cancellationToken)" />
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
        <Parameter Name="premiumPageBlobTier" Type="Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="premiumPageBlobTier">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            Blob の premium 階層を設定する非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetSequenceNumber">
      <MemberSignature Language="C#" Value="public virtual void SetSequenceNumber (Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction sequenceNumberAction, Nullable&lt;long&gt; sequenceNumber, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SetSequenceNumber(valuetype Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction sequenceNumberAction, valuetype System.Nullable`1&lt;int64&gt; sequenceNumber, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.SetSequenceNumber(Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction,System.Nullable{System.Int64},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetSequenceNumber : Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.SetSequenceNumber : Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudPageBlob.SetSequenceNumber (sequenceNumberAction, sequenceNumber, accessCondition, options, operationContext)" />
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
        <Parameter Name="sequenceNumberAction" Type="Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction" />
        <Parameter Name="sequenceNumber" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="sequenceNumberAction">型の値<see cref="T:Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction" />、シーケンス番号に対して実行する操作を示すです。</param>
        <param name="sequenceNumber">シーケンス番号。 このパラメーターに設定<c>null</c>場合<paramref name="sequenceNumberAction" />と等しい<see cref="F:SequenceNumberAction.Increment" />です。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。 場合<c>null</c>既定のオプションは、要求に適用されます。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            ページ blob のシーケンス番号を設定します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetSequenceNumberAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetSequenceNumberAsync (Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction sequenceNumberAction, Nullable&lt;long&gt; sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetSequenceNumberAsync(valuetype Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction sequenceNumberAction, valuetype System.Nullable`1&lt;int64&gt; sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.SetSequenceNumberAsync(Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction,System.Nullable{System.Int64})" />
      <MemberSignature Language="F#" Value="abstract member SetSequenceNumberAsync : Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction * Nullable&lt;int64&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.SetSequenceNumberAsync : Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction * Nullable&lt;int64&gt; -&gt; System.Threading.Tasks.Task" Usage="cloudPageBlob.SetSequenceNumberAsync (sequenceNumberAction, sequenceNumber)" />
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
        <Parameter Name="sequenceNumberAction" Type="Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction" />
        <Parameter Name="sequenceNumber" Type="System.Nullable&lt;System.Int64&gt;" />
      </Parameters>
      <Docs>
        <param name="sequenceNumberAction">型の値<see cref="T:Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction" />、シーケンス番号に対して実行する操作を示すです。</param>
        <param name="sequenceNumber">シーケンス番号。 このパラメーターに設定<c>null</c>場合<paramref name="sequenceNumberAction" />と等しい<see cref="F:SequenceNumberAction.Increment" />です。</param>
        <summary>
            ページ blob のシーケンス番号を設定する非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetSequenceNumberAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetSequenceNumberAsync (Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction sequenceNumberAction, Nullable&lt;long&gt; sequenceNumber, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetSequenceNumberAsync(valuetype Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction sequenceNumberAction, valuetype System.Nullable`1&lt;int64&gt; sequenceNumber, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.SetSequenceNumberAsync(Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction,System.Nullable{System.Int64},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetSequenceNumberAsync : Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction * Nullable&lt;int64&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetSequenceNumberAsync : Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction * Nullable&lt;int64&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPageBlob.SetSequenceNumberAsync (sequenceNumberAction, sequenceNumber, cancellationToken)" />
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
        <Parameter Name="sequenceNumberAction" Type="Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction" />
        <Parameter Name="sequenceNumber" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sequenceNumberAction">型の値<see cref="T:Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction" />、シーケンス番号に対して実行する操作を示すです。</param>
        <param name="sequenceNumber">シーケンス番号。 このパラメーターに設定<c>null</c>場合<paramref name="sequenceNumberAction" />と等しい<see cref="F:SequenceNumberAction.Increment" />です。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            ページ blob のシーケンス番号を設定する非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetSequenceNumberAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetSequenceNumberAsync (Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction sequenceNumberAction, Nullable&lt;long&gt; sequenceNumber, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetSequenceNumberAsync(valuetype Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction sequenceNumberAction, valuetype System.Nullable`1&lt;int64&gt; sequenceNumber, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.SetSequenceNumberAsync(Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction,System.Nullable{System.Int64},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetSequenceNumberAsync : Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.SetSequenceNumberAsync : Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudPageBlob.SetSequenceNumberAsync (sequenceNumberAction, sequenceNumber, accessCondition, options, operationContext)" />
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
        <Parameter Name="sequenceNumberAction" Type="Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction" />
        <Parameter Name="sequenceNumber" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="sequenceNumberAction">型の値<see cref="T:Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction" />、シーケンス番号に対して実行する操作を示すです。</param>
        <param name="sequenceNumber">シーケンス番号。 このパラメーターに設定<c>null</c>場合<paramref name="sequenceNumberAction" />と等しい<see cref="F:SequenceNumberAction.Increment" />です。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            ページ blob のシーケンス番号を設定する非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetSequenceNumberAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetSequenceNumberAsync (Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction sequenceNumberAction, Nullable&lt;long&gt; sequenceNumber, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetSequenceNumberAsync(valuetype Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction sequenceNumberAction, valuetype System.Nullable`1&lt;int64&gt; sequenceNumber, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.SetSequenceNumberAsync(Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction,System.Nullable{System.Int64},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetSequenceNumberAsync : Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetSequenceNumberAsync : Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPageBlob.SetSequenceNumberAsync (sequenceNumberAction, sequenceNumber, accessCondition, options, operationContext, cancellationToken)" />
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
        <Parameter Name="sequenceNumberAction" Type="Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction" />
        <Parameter Name="sequenceNumber" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sequenceNumberAction">型の値<see cref="T:Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction" />、シーケンス番号に対して実行する操作を示すです。</param>
        <param name="sequenceNumber">シーケンス番号。 このパラメーターに設定<c>null</c>場合<paramref name="sequenceNumberAction" />と等しい<see cref="F:SequenceNumberAction.Increment" />です。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            ページ blob のシーケンス番号を設定する非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartCopy">
      <MemberSignature Language="C#" Value="public virtual string StartCopy (Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob source, Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition = null, Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string StartCopy(class Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob source, class Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, class Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.StartCopy(Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="override this.StartCopy : Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; string" Usage="cloudPageBlob.StartCopy (source, sourceAccessCondition, destAccessCondition, options, operationContext)" />
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
        <Parameter Name="source" Type="Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />
        <Parameter Name="sourceAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="destAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="source"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />コピー元 blob はします。</param>
        <param name="sourceAccessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー元 blob のアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="destAccessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー先 blob のアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。 場合<c>null</c>既定のオプションは、要求に適用されます。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            このページ blob に別のページ blob の内容、プロパティ、およびメタデータのコピーを開始するための操作を開始します。
            </summary>
        <returns>コピー操作に関連付けられたコピー ID です。</returns>
        <remarks>
            このメソッドは、blob の ETag、最終更新時刻、および一部のコピー状態をフェッチします。
            コピー ID とコピーのステータス フィールドがフェッチされ、残りのコピーの状態がクリアされます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StartCopy">
      <MemberSignature Language="C#" Value="public virtual string StartCopy (Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob source, Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; premiumPageBlobTier, Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition = null, Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string StartCopy(class Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob source, valuetype System.Nullable`1&lt;valuetype Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; premiumPageBlobTier, class Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, class Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.StartCopy(Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob,System.Nullable{Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="override this.StartCopy : Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob * Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; string" Usage="cloudPageBlob.StartCopy (source, premiumPageBlobTier, sourceAccessCondition, destAccessCondition, options, operationContext)" />
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
        <Parameter Name="source" Type="Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />
        <Parameter Name="premiumPageBlobTier" Type="System.Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt;" />
        <Parameter Name="sourceAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="destAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="source"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />コピー元 blob はします。</param>
        <param name="premiumPageBlobTier">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</param>
        <param name="sourceAccessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー元 blob のアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="destAccessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー先 blob のアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。 場合<c>null</c>既定のオプションは、要求に適用されます。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            このページ blob に別のページ blob の内容、プロパティ、およびメタデータのコピーを開始するための操作を開始します。
            </summary>
        <returns>コピー操作に関連付けられたコピー ID です。</returns>
        <remarks>
            このメソッドは、blob の ETag、最終更新時刻、および一部のコピー状態をフェッチします。
            コピー ID とコピーのステータス フィールドがフェッチされ、残りのコピーの状態がクリアされます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StartCopyAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; StartCopyAsync (Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob source);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; StartCopyAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob source) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.StartCopyAsync(Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function StartCopyAsync (source As CloudPageBlob) As Task(Of String)" />
      <MemberSignature Language="F#" Value="override this.StartCopyAsync : Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudPageBlob.StartCopyAsync source" />
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
        <Parameter Name="source" Type="Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />
      </Parameters>
      <Docs>
        <param name="source"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />コピー元 blob はします。</param>
        <summary>
            このページ blob に別の blob の内容、プロパティ、およびメタデータのコピーを開始する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>文字列</c>非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartCopyAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; StartCopyAsync (Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob source, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; StartCopyAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob source, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.StartCopyAsync(Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="override this.StartCopyAsync : Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudPageBlob.StartCopyAsync (source, cancellationToken)" />
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
        <Parameter Name="source" Type="Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />コピー元 blob はします。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            このページ blob に別の blob の内容、プロパティ、およびメタデータのコピーを開始する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>文字列</c>非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartCopyAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; StartCopyAsync (Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob source, Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; StartCopyAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob source, class Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, class Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.StartCopyAsync(Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="override this.StartCopyAsync : Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudPageBlob.StartCopyAsync (source, sourceAccessCondition, destAccessCondition, options, operationContext)" />
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
        <Parameter Name="source" Type="Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />
        <Parameter Name="sourceAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="destAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="source"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />コピー元 blob はします。</param>
        <param name="sourceAccessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー元 blob のアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="destAccessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー先 blob のアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            このページ blob に別の blob の内容、プロパティ、およびメタデータのコピーを開始する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>文字列</c>非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartCopyAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; StartCopyAsync (Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob source, Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; StartCopyAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob source, class Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, class Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.StartCopyAsync(Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="override this.StartCopyAsync : Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudPageBlob.StartCopyAsync (source, sourceAccessCondition, destAccessCondition, options, operationContext, cancellationToken)" />
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
        <Parameter Name="source" Type="Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />
        <Parameter Name="sourceAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="destAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />コピー元 blob はします。</param>
        <param name="sourceAccessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー元 blob のアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="destAccessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー先 blob のアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            このページ blob に別の blob の内容、プロパティ、およびメタデータのコピーを開始する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>文字列</c>非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartCopyAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; StartCopyAsync (Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob source, Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; premiumPageBlobTier, Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; StartCopyAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob source, valuetype System.Nullable`1&lt;valuetype Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; premiumPageBlobTier, class Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, class Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.StartCopyAsync(Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob,System.Nullable{Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="override this.StartCopyAsync : Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob * Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudPageBlob.StartCopyAsync (source, premiumPageBlobTier, sourceAccessCondition, destAccessCondition, options, operationContext, cancellationToken)" />
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
        <Parameter Name="source" Type="Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />
        <Parameter Name="premiumPageBlobTier" Type="System.Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt;" />
        <Parameter Name="sourceAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="destAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />コピー元 blob はします。</param>
        <param name="premiumPageBlobTier">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</param>
        <param name="sourceAccessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー元 blob のアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="destAccessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー先 blob のアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            このページ blob に別の blob の内容、プロパティ、およびメタデータのコピーを開始する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>文字列</c>非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartIncrementalCopy">
      <MemberSignature Language="C#" Value="public virtual string StartIncrementalCopy (Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob sourceSnapshot, Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string StartIncrementalCopy(class Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob sourceSnapshot, class Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.StartIncrementalCopy(Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member StartIncrementalCopy : Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; string&#xA;override this.StartIncrementalCopy : Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; string" Usage="cloudPageBlob.StartIncrementalCopy (sourceSnapshot, destAccessCondition, options, operationContext)" />
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
        <Parameter Name="sourceSnapshot" Type="Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />
        <Parameter Name="destAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="sourceSnapshot"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />コピー元 blob がスナップショットである必要があります。</param>
        <param name="destAccessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー先 blob のアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。 場合<c>null</c>既定のオプションは、要求に適用されます。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            別のページ blob の内容、プロパティ、およびページ blob のメタデータの増分のコピーを開始するための操作を開始します。
            </summary>
        <returns>コピー操作に関連付けられたコピー ID です。</returns>
        <remarks>
            このメソッドは、blob の ETag、最終更新時刻、および一部のコピー状態をフェッチします。
            コピー ID とコピーのステータス フィールドがフェッチされ、残りのコピーの状態がクリアされます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StartIncrementalCopy">
      <MemberSignature Language="C#" Value="public virtual string StartIncrementalCopy (Uri sourceSnapshotUri, Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string StartIncrementalCopy(class System.Uri sourceSnapshotUri, class Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.StartIncrementalCopy(System.Uri,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member StartIncrementalCopy : Uri * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; string&#xA;override this.StartIncrementalCopy : Uri * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; string" Usage="cloudPageBlob.StartIncrementalCopy (sourceSnapshotUri, destAccessCondition, options, operationContext)" />
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
        <Parameter Name="sourceSnapshotUri" Type="System.Uri" />
        <Parameter Name="destAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="sourceSnapshotUri"><see cref="T:System.Uri" />のコピー元 blob スナップショットをする必要があります。</param>
        <param name="destAccessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー先 blob のアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。 場合<c>null</c>既定のオプションは、要求に適用されます。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            別のページ blob の内容、プロパティ、およびページ blob のメタデータの増分のコピーを開始するための操作を開始します。
            </summary>
        <returns>コピー操作に関連付けられたコピー ID です。</returns>
        <remarks>
            このメソッドは、blob の ETag、最終更新時刻、および一部のコピー状態をフェッチします。
            コピー ID とコピーのステータス フィールドがフェッチされ、残りのコピーの状態がクリアされます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StartIncrementalCopyAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; StartIncrementalCopyAsync (Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob source);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; StartIncrementalCopyAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob source) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.StartIncrementalCopyAsync(Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function StartIncrementalCopyAsync (source As CloudPageBlob) As Task(Of String)" />
      <MemberSignature Language="F#" Value="abstract member StartIncrementalCopyAsync : Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob -&gt; System.Threading.Tasks.Task&lt;string&gt;&#xA;override this.StartIncrementalCopyAsync : Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudPageBlob.StartIncrementalCopyAsync source" />
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
        <Parameter Name="source" Type="Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />
      </Parameters>
      <Docs>
        <param name="source"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />コピー元 blob がスナップショットである必要があります。</param>
        <summary>
            別の blob の内容、プロパティ、およびページ blob のメタデータの増分のコピーを開始する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>文字列</c>非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartIncrementalCopyAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; StartIncrementalCopyAsync (Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob source, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; StartIncrementalCopyAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob source, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.StartIncrementalCopyAsync(Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member StartIncrementalCopyAsync : Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;&#xA;override this.StartIncrementalCopyAsync : Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudPageBlob.StartIncrementalCopyAsync (source, cancellationToken)" />
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
        <Parameter Name="source" Type="Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />コピー元 blob がスナップショットである必要があります。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            別の blob の内容、プロパティ、およびページ blob のメタデータの増分のコピーを開始する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>文字列</c>非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartIncrementalCopyAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; StartIncrementalCopyAsync (Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob source, Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; StartIncrementalCopyAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob source, class Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.StartIncrementalCopyAsync(Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member StartIncrementalCopyAsync : Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;&#xA;override this.StartIncrementalCopyAsync : Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudPageBlob.StartIncrementalCopyAsync (source, destAccessCondition, options, operationContext, cancellationToken)" />
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
        <Parameter Name="source" Type="Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />
        <Parameter Name="destAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />コピー元 blob がスナップショットである必要があります。</param>
        <param name="destAccessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー先 blob のアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            別の blob の内容、プロパティ、およびページ blob のメタデータの増分のコピーを開始する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>文字列</c>非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StreamWriteSizeInBytes">
      <MemberSignature Language="C#" Value="public int StreamWriteSizeInBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 StreamWriteSizeInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.StreamWriteSizeInBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property StreamWriteSizeInBytes As Integer" />
      <MemberSignature Language="F#" Value="member this.StreamWriteSizeInBytes : int with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.StreamWriteSizeInBytes" />
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
            取得またはページ blob ストリームに書き込むときにバッファーに書き込むバイト数を設定します。
            </summary>
        <value>バッファーに mb 512 バイトと 4 MB までのバイト数。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromByteArray">
      <MemberSignature Language="C#" Value="public virtual void UploadFromByteArray (byte[] buffer, int index, int count, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void UploadFromByteArray(unsigned int8[] buffer, int32 index, int32 count, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.UploadFromByteArray(System.Byte[],System.Int32,System.Int32,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromByteArray : byte[] * int * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.UploadFromByteArray : byte[] * int * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudPageBlob.UploadFromByteArray (buffer, index, count, accessCondition, options, operationContext)" />
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
            バイト配列の内容をページ blob にアップロードします。 Blob が既に存在する場合は上書きされます。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromByteArray">
      <MemberSignature Language="C#" Value="public virtual void UploadFromByteArray (byte[] buffer, int index, int count, Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; premiumPageBlobTier, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void UploadFromByteArray(unsigned int8[] buffer, int32 index, int32 count, valuetype System.Nullable`1&lt;valuetype Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; premiumPageBlobTier, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.UploadFromByteArray(System.Byte[],System.Int32,System.Int32,System.Nullable{Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromByteArray : byte[] * int * int * Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.UploadFromByteArray : byte[] * int * int * Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudPageBlob.UploadFromByteArray (buffer, index, count, premiumPageBlobTier, accessCondition, options, operationContext)" />
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
        <Parameter Name="premiumPageBlobTier" Type="System.Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="buffer">バイト配列。</param>
        <param name="index">Blob のバイトのアップロードを開始位置を示すバッファー内の 0 から始まるバイト オフセット。</param>
        <param name="count">Blob に書き込まれるバイト数。</param>
        <param name="premiumPageBlobTier">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。 場合<c>null</c>既定のオプションは、要求に適用されます。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            バイト配列の内容をページ blob にアップロードします。 Blob が既に存在する場合は上書きされます。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromByteArrayAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromByteArrayAsync (byte[] buffer, int index, int count);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromByteArrayAsync(unsigned int8[] buffer, int32 index, int32 count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.UploadFromByteArrayAsync(System.Byte[],System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function UploadFromByteArrayAsync (buffer As Byte(), index As Integer, count As Integer) As Task" />
      <MemberSignature Language="F#" Value="abstract member UploadFromByteArrayAsync : byte[] * int * int -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromByteArrayAsync : byte[] * int * int -&gt; System.Threading.Tasks.Task" Usage="cloudPageBlob.UploadFromByteArrayAsync (buffer, index, count)" />
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
            バイト配列の内容をページ blob にアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromByteArrayAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromByteArrayAsync (byte[] buffer, int index, int count, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromByteArrayAsync(unsigned int8[] buffer, int32 index, int32 count, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.UploadFromByteArrayAsync(System.Byte[],System.Int32,System.Int32,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromByteArrayAsync : byte[] * int * int * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromByteArrayAsync : byte[] * int * int * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPageBlob.UploadFromByteArrayAsync (buffer, index, count, cancellationToken)" />
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
            バイト配列の内容をページ blob にアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromByteArrayAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromByteArrayAsync (byte[] buffer, int index, int count, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromByteArrayAsync(unsigned int8[] buffer, int32 index, int32 count, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.UploadFromByteArrayAsync(System.Byte[],System.Int32,System.Int32,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromByteArrayAsync : byte[] * int * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromByteArrayAsync : byte[] * int * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudPageBlob.UploadFromByteArrayAsync (buffer, index, count, accessCondition, options, operationContext)" />
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
            バイト配列の内容をページ blob にアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromByteArrayAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromByteArrayAsync (byte[] buffer, int index, int count, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromByteArrayAsync(unsigned int8[] buffer, int32 index, int32 count, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.UploadFromByteArrayAsync(System.Byte[],System.Int32,System.Int32,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromByteArrayAsync : byte[] * int * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromByteArrayAsync : byte[] * int * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPageBlob.UploadFromByteArrayAsync (buffer, index, count, accessCondition, options, operationContext, cancellationToken)" />
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
            バイト配列の内容をページ blob にアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromByteArrayAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromByteArrayAsync (byte[] buffer, int index, int count, Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; premiumPageBlobTier, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromByteArrayAsync(unsigned int8[] buffer, int32 index, int32 count, valuetype System.Nullable`1&lt;valuetype Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; premiumPageBlobTier, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.UploadFromByteArrayAsync(System.Byte[],System.Int32,System.Int32,System.Nullable{Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromByteArrayAsync : byte[] * int * int * Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromByteArrayAsync : byte[] * int * int * Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPageBlob.UploadFromByteArrayAsync (buffer, index, count, premiumPageBlobTier, accessCondition, options, operationContext, cancellationToken)" />
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
        <Parameter Name="premiumPageBlobTier" Type="System.Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="buffer">バイト配列。</param>
        <param name="index">Blob のバイトのアップロードを開始位置を示すバッファー内の 0 から始まるバイト オフセット。</param>
        <param name="count">Blob に書き込まれるバイト数。</param>
        <param name="premiumPageBlobTier">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            バイト配列の内容をページ blob にアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromByteArrayAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromByteArrayAsync (byte[] buffer, int index, int count, Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; premiumPageBlobTier, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromByteArrayAsync(unsigned int8[] buffer, int32 index, int32 count, valuetype System.Nullable`1&lt;valuetype Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; premiumPageBlobTier, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.IProgress`1&lt;class Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.UploadFromByteArrayAsync(System.Byte[],System.Int32,System.Int32,System.Nullable{Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.IProgress{Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromByteArrayAsync : byte[] * int * int * Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromByteArrayAsync : byte[] * int * int * Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPageBlob.UploadFromByteArrayAsync (buffer, index, count, premiumPageBlobTier, accessCondition, options, operationContext, progressHandler, cancellationToken)" />
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
        <Parameter Name="premiumPageBlobTier" Type="System.Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt;" />
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
        <param name="premiumPageBlobTier">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="progressHandler"> A<see cref="T:System.IProgress`1" />を処理するオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" />メッセージ。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            バイト配列の内容をページ blob にアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromFile">
      <MemberSignature Language="C#" Value="public virtual void UploadFromFile (string path, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void UploadFromFile(string path, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.UploadFromFile(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromFile : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.UploadFromFile : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudPageBlob.UploadFromFile (path, accessCondition, options, operationContext)" />
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
            ページ blob にファイルをアップロードします。 Blob が既に存在する場合は上書きされます。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromFile">
      <MemberSignature Language="C#" Value="public virtual void UploadFromFile (string path, Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; premiumPageBlobTier, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void UploadFromFile(string path, valuetype System.Nullable`1&lt;valuetype Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; premiumPageBlobTier, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.UploadFromFile(System.String,System.Nullable{Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromFile : string * Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.UploadFromFile : string * Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudPageBlob.UploadFromFile (path, premiumPageBlobTier, accessCondition, options, operationContext)" />
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
        <Parameter Name="premiumPageBlobTier" Type="System.Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="path">Blob コンテンツを提供するファイルのパスを含む文字列。</param>
        <param name="premiumPageBlobTier">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。 場合<c>null</c>既定のオプションは、要求に適用されます。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            ページ blob にファイルをアップロードします。 Blob が既に存在する場合は上書きされます。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromFileAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromFileAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromFileAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.UploadFromFileAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function UploadFromFileAsync (path As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member UploadFromFileAsync : string -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromFileAsync : string -&gt; System.Threading.Tasks.Task" Usage="cloudPageBlob.UploadFromFileAsync path" />
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
            ページ blob にファイルをアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromFileAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromFileAsync (string path, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromFileAsync(string path, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.UploadFromFileAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromFileAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromFileAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPageBlob.UploadFromFileAsync (path, cancellationToken)" />
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
            ページ blob にファイルをアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromFileAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromFileAsync (string path, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromFileAsync(string path, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.UploadFromFileAsync(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromFileAsync : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromFileAsync : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudPageBlob.UploadFromFileAsync (path, accessCondition, options, operationContext)" />
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
            ページ blob にファイルをアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromFileAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromFileAsync (string path, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromFileAsync(string path, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.UploadFromFileAsync(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromFileAsync : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromFileAsync : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPageBlob.UploadFromFileAsync (path, accessCondition, options, operationContext, cancellationToken)" />
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
            ページ blob にファイルをアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromFileAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromFileAsync (string path, Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; premiumPageBlobTier, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromFileAsync(string path, valuetype System.Nullable`1&lt;valuetype Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; premiumPageBlobTier, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.UploadFromFileAsync(System.String,System.Nullable{Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromFileAsync : string * Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromFileAsync : string * Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPageBlob.UploadFromFileAsync (path, premiumPageBlobTier, accessCondition, options, operationContext, cancellationToken)" />
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
        <Parameter Name="premiumPageBlobTier" Type="System.Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">Blob コンテンツを提供するファイルのパスを含む文字列。</param>
        <param name="premiumPageBlobTier">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            ページ blob にファイルをアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromFileAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromFileAsync (string path, Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; premiumPageBlobTier, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromFileAsync(string path, valuetype System.Nullable`1&lt;valuetype Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; premiumPageBlobTier, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.IProgress`1&lt;class Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.UploadFromFileAsync(System.String,System.Nullable{Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.IProgress{Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromFileAsync : string * Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromFileAsync : string * Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPageBlob.UploadFromFileAsync (path, premiumPageBlobTier, accessCondition, options, operationContext, progressHandler, cancellationToken)" />
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
        <Parameter Name="premiumPageBlobTier" Type="System.Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="progressHandler" Type="System.IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">Blob コンテンツを提供するファイルのパスを含む文字列。</param>
        <param name="premiumPageBlobTier">A<see cref="!:PageBlobTier" />を設定する層を表すです。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="progressHandler"> A<see cref="T:System.IProgress`1" />を処理するオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" />メッセージ。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            ページ blob にファイルをアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromStream">
      <MemberSignature Language="C#" Value="public virtual void UploadFromStream (System.IO.Stream source, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void UploadFromStream(class System.IO.Stream source, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.UploadFromStream(System.IO.Stream,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromStream : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.UploadFromStream : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudPageBlob.UploadFromStream (source, accessCondition, options, operationContext)" />
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
            ストリームをページ blob にアップロードします。 Blob が既に存在する場合は上書きされます。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromStream">
      <MemberSignature Language="C#" Value="public virtual void UploadFromStream (System.IO.Stream source, long length, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void UploadFromStream(class System.IO.Stream source, int64 length, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.UploadFromStream(System.IO.Stream,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromStream : System.IO.Stream * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.UploadFromStream : System.IO.Stream * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudPageBlob.UploadFromStream (source, length, accessCondition, options, operationContext)" />
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
            ストリームをページ blob にアップロードします。 Blob が既に存在する場合は上書きされます。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromStream">
      <MemberSignature Language="C#" Value="public virtual void UploadFromStream (System.IO.Stream source, Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; premiumPageBlobTier, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void UploadFromStream(class System.IO.Stream source, valuetype System.Nullable`1&lt;valuetype Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; premiumPageBlobTier, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.UploadFromStream(System.IO.Stream,System.Nullable{Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromStream : System.IO.Stream * Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.UploadFromStream : System.IO.Stream * Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudPageBlob.UploadFromStream (source, premiumPageBlobTier, accessCondition, options, operationContext)" />
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
        <Parameter Name="premiumPageBlobTier" Type="System.Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="source">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</param>
        <param name="premiumPageBlobTier">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。 場合<c>null</c>既定のオプションは、要求に適用されます。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            ストリームをページ blob にアップロードします。 Blob が既に存在する場合は上書きされます。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromStream">
      <MemberSignature Language="C#" Value="public virtual void UploadFromStream (System.IO.Stream source, long length, Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; premiumPageBlobTier, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void UploadFromStream(class System.IO.Stream source, int64 length, valuetype System.Nullable`1&lt;valuetype Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; premiumPageBlobTier, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.UploadFromStream(System.IO.Stream,System.Int64,System.Nullable{Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromStream : System.IO.Stream * int64 * Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.UploadFromStream : System.IO.Stream * int64 * Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudPageBlob.UploadFromStream (source, length, premiumPageBlobTier, accessCondition, options, operationContext)" />
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
        <Parameter Name="premiumPageBlobTier" Type="System.Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="source">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</param>
        <param name="length">現在の位置に、ソース ストリームから書き込むバイト数。</param>
        <param name="premiumPageBlobTier">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。 場合<c>null</c>既定のオプションは、要求に適用されます。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            ストリームをページ blob にアップロードします。 Blob が既に存在する場合は上書きされます。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromStreamAsync (System.IO.Stream source);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromStreamAsync(class System.IO.Stream source) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.UploadFromStreamAsync(System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function UploadFromStreamAsync (source As Stream) As Task" />
      <MemberSignature Language="F#" Value="abstract member UploadFromStreamAsync : System.IO.Stream -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromStreamAsync : System.IO.Stream -&gt; System.Threading.Tasks.Task" Usage="cloudPageBlob.UploadFromStreamAsync source" />
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
            ページ blob にストリームをアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromStreamAsync (System.IO.Stream source, long length);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromStreamAsync(class System.IO.Stream source, int64 length) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.UploadFromStreamAsync(System.IO.Stream,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function UploadFromStreamAsync (source As Stream, length As Long) As Task" />
      <MemberSignature Language="F#" Value="abstract member UploadFromStreamAsync : System.IO.Stream * int64 -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromStreamAsync : System.IO.Stream * int64 -&gt; System.Threading.Tasks.Task" Usage="cloudPageBlob.UploadFromStreamAsync (source, length)" />
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
            ページ blob にストリームをアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromStreamAsync (System.IO.Stream source, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromStreamAsync(class System.IO.Stream source, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.UploadFromStreamAsync(System.IO.Stream,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromStreamAsync : System.IO.Stream * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromStreamAsync : System.IO.Stream * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPageBlob.UploadFromStreamAsync (source, cancellationToken)" />
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
            ページ blob にストリームをアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromStreamAsync (System.IO.Stream source, long length, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromStreamAsync(class System.IO.Stream source, int64 length, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.UploadFromStreamAsync(System.IO.Stream,System.Int64,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromStreamAsync : System.IO.Stream * int64 * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromStreamAsync : System.IO.Stream * int64 * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPageBlob.UploadFromStreamAsync (source, length, cancellationToken)" />
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
            ページ blob にストリームをアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromStreamAsync (System.IO.Stream source, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromStreamAsync(class System.IO.Stream source, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.UploadFromStreamAsync(System.IO.Stream,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromStreamAsync : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromStreamAsync : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudPageBlob.UploadFromStreamAsync (source, accessCondition, options, operationContext)" />
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
            ページ blob にストリームをアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromStreamAsync (System.IO.Stream source, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromStreamAsync(class System.IO.Stream source, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.UploadFromStreamAsync(System.IO.Stream,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromStreamAsync : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromStreamAsync : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPageBlob.UploadFromStreamAsync (source, accessCondition, options, operationContext, cancellationToken)" />
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
            ページ blob にストリームをアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromStreamAsync (System.IO.Stream source, long length, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromStreamAsync(class System.IO.Stream source, int64 length, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.UploadFromStreamAsync(System.IO.Stream,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromStreamAsync : System.IO.Stream * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromStreamAsync : System.IO.Stream * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudPageBlob.UploadFromStreamAsync (source, length, accessCondition, options, operationContext)" />
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
            ページ blob にストリームをアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromStreamAsync (System.IO.Stream source, long length, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromStreamAsync(class System.IO.Stream source, int64 length, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.UploadFromStreamAsync(System.IO.Stream,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromStreamAsync : System.IO.Stream * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromStreamAsync : System.IO.Stream * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPageBlob.UploadFromStreamAsync (source, length, accessCondition, options, operationContext, cancellationToken)" />
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
            ページ blob にストリームをアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromStreamAsync (System.IO.Stream source, Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; premiumPageBlobTier, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromStreamAsync(class System.IO.Stream source, valuetype System.Nullable`1&lt;valuetype Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; premiumPageBlobTier, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.UploadFromStreamAsync(System.IO.Stream,System.Nullable{Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromStreamAsync : System.IO.Stream * Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromStreamAsync : System.IO.Stream * Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPageBlob.UploadFromStreamAsync (source, premiumPageBlobTier, accessCondition, options, operationContext, cancellationToken)" />
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
        <Parameter Name="premiumPageBlobTier" Type="System.Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</param>
        <param name="premiumPageBlobTier">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            ページ blob にストリームをアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromStreamAsync (System.IO.Stream source, long length, Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; premiumPageBlobTier, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromStreamAsync(class System.IO.Stream source, int64 length, valuetype System.Nullable`1&lt;valuetype Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; premiumPageBlobTier, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.UploadFromStreamAsync(System.IO.Stream,System.Int64,System.Nullable{Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromStreamAsync : System.IO.Stream * int64 * Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromStreamAsync : System.IO.Stream * int64 * Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPageBlob.UploadFromStreamAsync (source, length, premiumPageBlobTier, accessCondition, options, operationContext, cancellationToken)" />
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
        <Parameter Name="premiumPageBlobTier" Type="System.Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</param>
        <param name="length">現在の位置に、ソース ストリームから書き込むバイト数。</param>
        <param name="premiumPageBlobTier">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            ページ blob にストリームをアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromStreamAsync (System.IO.Stream source, Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; premiumPageBlobTier, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromStreamAsync(class System.IO.Stream source, valuetype System.Nullable`1&lt;valuetype Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; premiumPageBlobTier, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.IProgress`1&lt;class Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.UploadFromStreamAsync(System.IO.Stream,System.Nullable{Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.IProgress{Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromStreamAsync : System.IO.Stream * Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromStreamAsync : System.IO.Stream * Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPageBlob.UploadFromStreamAsync (source, premiumPageBlobTier, accessCondition, options, operationContext, progressHandler, cancellationToken)" />
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
        <Parameter Name="premiumPageBlobTier" Type="System.Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="progressHandler" Type="System.IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</param>
        <param name="premiumPageBlobTier">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="progressHandler"> A<see cref="T:System.IProgress`1" />を処理するオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" />メッセージ。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            ページ blob にストリームをアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromStreamAsync (System.IO.Stream source, long length, Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; premiumPageBlobTier, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromStreamAsync(class System.IO.Stream source, int64 length, valuetype System.Nullable`1&lt;valuetype Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; premiumPageBlobTier, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.IProgress`1&lt;class Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.UploadFromStreamAsync(System.IO.Stream,System.Int64,System.Nullable{Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.IProgress{Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromStreamAsync : System.IO.Stream * int64 * Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromStreamAsync : System.IO.Stream * int64 * Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPageBlob.UploadFromStreamAsync (source, length, premiumPageBlobTier, accessCondition, options, operationContext, progressHandler, cancellationToken)" />
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
        <Parameter Name="premiumPageBlobTier" Type="System.Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="progressHandler" Type="System.IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</param>
        <param name="length">現在の位置に、ソース ストリームから書き込むバイト数。</param>
        <param name="premiumPageBlobTier">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="progressHandler"> A<see cref="T:System.IProgress`1" />を処理するオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" />メッセージ。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            ページ blob にストリームをアップロードする非同期操作を開始します。 Blob が既に存在する場合は上書きされます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WritePages">
      <MemberSignature Language="C#" Value="public virtual void WritePages (System.IO.Stream pageData, long startOffset, string contentMD5 = null, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void WritePages(class System.IO.Stream pageData, int64 startOffset, string contentMD5, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.WritePages(System.IO.Stream,System.Int64,System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member WritePages : System.IO.Stream * int64 * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.WritePages : System.IO.Stream * int64 * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudPageBlob.WritePages (pageData, startOffset, contentMD5, accessCondition, options, operationContext)" />
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
        <Parameter Name="pageData" Type="System.IO.Stream" />
        <Parameter Name="startOffset" Type="System.Int64" />
        <Parameter Name="contentMD5" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="pageData">A<see cref="T:System.IO.Stream" />ページ データを提供するオブジェクト。</param>
        <param name="startOffset">バイト単位での書き込みを開始するオフセットです。 オフセットは 512 の倍数である必要があります。</param>
        <param name="contentMD5">ページのトランザクションの整合性を確保するために使用する省略可能なハッシュ値です。 あります<c>null</c>または空の文字列。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。 場合<c>null</c>既定のオプションは、要求に適用されます。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            ページ blob にページに書き込みます。
            </summary>
        <remarks>
            クライアントは、ネットワーク上でトランザクションの整合性を確保するための手段として特定のページの書き込み操作の content-md5 ヘッダーを送信できます。 <paramref name="contentMD5" />パラメーターにより、クライアントは、指定したバイトの範囲に提供することを事前に計算された MD5 値へのアクセスを既に持っています。
            場合、<see cref="P:BlobRequestOptions.UseTransactionalMd5" />プロパティに設定されている<c>true</c>と<paramref name="contentMD5" />にパラメーターが設定されている<c>null</c>、クライアント ライブラリが MD5 値を内部で計算し、します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="WritePagesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task WritePagesAsync (System.IO.Stream pageData, long startOffset, string contentMD5);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task WritePagesAsync(class System.IO.Stream pageData, int64 startOffset, string contentMD5) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.WritePagesAsync(System.IO.Stream,System.Int64,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function WritePagesAsync (pageData As Stream, startOffset As Long, contentMD5 As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member WritePagesAsync : System.IO.Stream * int64 * string -&gt; System.Threading.Tasks.Task&#xA;override this.WritePagesAsync : System.IO.Stream * int64 * string -&gt; System.Threading.Tasks.Task" Usage="cloudPageBlob.WritePagesAsync (pageData, startOffset, contentMD5)" />
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
        <Parameter Name="pageData" Type="System.IO.Stream" />
        <Parameter Name="startOffset" Type="System.Int64" />
        <Parameter Name="contentMD5" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="pageData">A<see cref="T:System.IO.Stream" />ページ データを提供するオブジェクト。</param>
        <param name="startOffset">バイト単位での書き込みを開始するオフセットです。 オフセットは 512 の倍数である必要があります。</param>
        <param name="contentMD5">ページのトランザクションの整合性を確保するために使用する省略可能なハッシュ値です。 あります<c>null</c>または空の文字列。</param>
        <summary>
            ページ blob にページを書き込む非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            クライアントは、ネットワーク上でトランザクションの整合性を確保するための手段として特定のページの書き込み操作の content-md5 ヘッダーを送信できます。 <paramref name="contentMD5" />パラメーターにより、クライアントは、指定したバイトの範囲に提供することを事前に計算された MD5 値へのアクセスを既に持っています。
            場合、<see cref="P:BlobRequestOptions.UseTransactionalMd5" />プロパティに設定されている<c>true</c>と<paramref name="contentMD5" />にパラメーターが設定されている<c>null</c>、クライアント ライブラリが MD5 値を内部で計算し、します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="WritePagesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task WritePagesAsync (System.IO.Stream pageData, long startOffset, string contentMD5, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task WritePagesAsync(class System.IO.Stream pageData, int64 startOffset, string contentMD5, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.WritePagesAsync(System.IO.Stream,System.Int64,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member WritePagesAsync : System.IO.Stream * int64 * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.WritePagesAsync : System.IO.Stream * int64 * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPageBlob.WritePagesAsync (pageData, startOffset, contentMD5, cancellationToken)" />
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
        <Parameter Name="pageData" Type="System.IO.Stream" />
        <Parameter Name="startOffset" Type="System.Int64" />
        <Parameter Name="contentMD5" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="pageData">A<see cref="T:System.IO.Stream" />ページ データを提供するオブジェクト。</param>
        <param name="startOffset">バイト単位での書き込みを開始するオフセットです。 オフセットは 512 の倍数である必要があります。</param>
        <param name="contentMD5">ページのトランザクションの整合性を確保するために使用する省略可能なハッシュ値です。 あります<c>null</c>または空の文字列。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            ページ blob にページを書き込む非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            クライアントは、ネットワーク上でトランザクションの整合性を確保するための手段として特定のページの書き込み操作の content-md5 ヘッダーを送信できます。 <paramref name="contentMD5" />パラメーターにより、クライアントは、指定したバイトの範囲に提供することを事前に計算された MD5 値へのアクセスを既に持っています。
            場合、<see cref="P:BlobRequestOptions.UseTransactionalMd5" />プロパティに設定されている<c>true</c>と<paramref name="contentMD5" />にパラメーターが設定されている<c>null</c>、クライアント ライブラリが MD5 値を内部で計算し、します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="WritePagesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task WritePagesAsync (System.IO.Stream pageData, long startOffset, string contentMD5, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task WritePagesAsync(class System.IO.Stream pageData, int64 startOffset, string contentMD5, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.WritePagesAsync(System.IO.Stream,System.Int64,System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member WritePagesAsync : System.IO.Stream * int64 * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.WritePagesAsync : System.IO.Stream * int64 * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudPageBlob.WritePagesAsync (pageData, startOffset, contentMD5, accessCondition, options, operationContext)" />
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
        <Parameter Name="pageData" Type="System.IO.Stream" />
        <Parameter Name="startOffset" Type="System.Int64" />
        <Parameter Name="contentMD5" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="pageData">A<see cref="T:System.IO.Stream" />ページ データを提供するオブジェクト。</param>
        <param name="startOffset">バイト単位での書き込みを開始するオフセットです。 オフセットは 512 の倍数である必要があります。</param>
        <param name="contentMD5">ページのトランザクションの整合性を確保するために使用する省略可能なハッシュ値です。 あります<c>null</c>または空の文字列。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            ページ blob にページを書き込む非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            クライアントは、ネットワーク上でトランザクションの整合性を確保するための手段として特定のページの書き込み操作の content-md5 ヘッダーを送信できます。 <paramref name="contentMD5" />パラメーターにより、クライアントは、指定したバイトの範囲に提供することを事前に計算された MD5 値へのアクセスを既に持っています。
            場合、<see cref="P:BlobRequestOptions.UseTransactionalMd5" />プロパティに設定されている<c>true</c>と<paramref name="contentMD5" />にパラメーターが設定されている<c>null</c>、クライアント ライブラリが MD5 値を内部で計算し、します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="WritePagesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task WritePagesAsync (System.IO.Stream pageData, long startOffset, string contentMD5, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task WritePagesAsync(class System.IO.Stream pageData, int64 startOffset, string contentMD5, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.WritePagesAsync(System.IO.Stream,System.Int64,System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member WritePagesAsync : System.IO.Stream * int64 * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.WritePagesAsync : System.IO.Stream * int64 * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPageBlob.WritePagesAsync (pageData, startOffset, contentMD5, accessCondition, options, operationContext, cancellationToken)" />
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
        <Parameter Name="pageData" Type="System.IO.Stream" />
        <Parameter Name="startOffset" Type="System.Int64" />
        <Parameter Name="contentMD5" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="pageData">A<see cref="T:System.IO.Stream" />ページ データを提供するオブジェクト。</param>
        <param name="startOffset">バイト単位での書き込みを開始するオフセットです。 オフセットは 512 の倍数である必要があります。</param>
        <param name="contentMD5">ページのトランザクションの整合性を確保するために使用する省略可能なハッシュ値です。 あります<c>null</c>または空の文字列。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            ページ blob にページを書き込む非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            クライアントは、ネットワーク上でトランザクションの整合性を確保するための手段として特定のページの書き込み操作の content-md5 ヘッダーを送信できます。 <paramref name="contentMD5" />パラメーターにより、クライアントは、指定したバイトの範囲に提供することを事前に計算された MD5 値へのアクセスを既に持っています。
            場合、<see cref="P:BlobRequestOptions.UseTransactionalMd5" />プロパティに設定されている<c>true</c>と<paramref name="contentMD5" />にパラメーターが設定されている<c>null</c>、クライアント ライブラリが MD5 値を内部で計算し、します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="WritePagesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task WritePagesAsync (System.IO.Stream pageData, long startOffset, string contentMD5, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task WritePagesAsync(class System.IO.Stream pageData, int64 startOffset, string contentMD5, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.IProgress`1&lt;class Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.WritePagesAsync(System.IO.Stream,System.Int64,System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.IProgress{Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member WritePagesAsync : System.IO.Stream * int64 * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.WritePagesAsync : System.IO.Stream * int64 * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPageBlob.WritePagesAsync (pageData, startOffset, contentMD5, accessCondition, options, operationContext, progressHandler, cancellationToken)" />
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
        <Parameter Name="pageData" Type="System.IO.Stream" />
        <Parameter Name="startOffset" Type="System.Int64" />
        <Parameter Name="contentMD5" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="progressHandler" Type="System.IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="pageData">A<see cref="T:System.IO.Stream" />ページ データを提供するオブジェクト。</param>
        <param name="startOffset">バイト単位での書き込みを開始するオフセットです。 オフセットは 512 の倍数である必要があります。</param>
        <param name="contentMD5">ページのトランザクションの整合性を確保するために使用する省略可能なハッシュ値です。 あります<c>null</c>または空の文字列。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="progressHandler"> A<see cref="T:System.IProgress`1" />を処理するオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" />メッセージ。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            ページ blob にページを書き込む非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
            クライアントは、ネットワーク上でトランザクションの整合性を確保するための手段として特定のページの書き込み操作の content-md5 ヘッダーを送信できます。 <paramref name="contentMD5" />パラメーターにより、クライアントは、指定したバイトの範囲に提供することを事前に計算された MD5 値へのアクセスを既に持っています。
            場合、<see cref="P:BlobRequestOptions.UseTransactionalMd5" />プロパティに設定されている<c>true</c>と<paramref name="contentMD5" />にパラメーターが設定されている<c>null</c>、クライアント ライブラリが MD5 値を内部で計算し、します。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>