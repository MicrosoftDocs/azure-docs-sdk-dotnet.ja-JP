<Type Name="CloudBlobDirectory" FullName="Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory">
  <TypeSignature Language="C#" Value="public class CloudBlobDirectory : Microsoft.WindowsAzure.Storage.Blob.IListBlobItem" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CloudBlobDirectory extends System.Object implements class Microsoft.WindowsAzure.Storage.Blob.IListBlobItem" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" />
  <TypeSignature Language="VB.NET" Value="Public Class CloudBlobDirectory&#xA;Implements IListBlobItem" />
  <TypeSignature Language="F#" Value="type CloudBlobDirectory = class&#xA;    interface IListBlobItem" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.WindowsAzure.Storage.Blob.IListBlobItem</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            区切り文字で指定される blob の仮想ディレクトリを表します。
            </summary>
    <remarks>としてカプセル化されるコンテナー<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer" />オブジェクト、ディレクトリ、およびディレクトリのブロック blob とページ blob を保持します。 ディレクトリは、サブディレクトリを含めることもできます。</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginListBlobsSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListBlobsSegmented (Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListBlobsSegmented(class Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory.BeginListBlobsSegmented(Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginListBlobsSegmented (currentToken As BlobContinuationToken, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginListBlobsSegmented : Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginListBlobsSegmented : Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobDirectory.BeginListBlobsSegmented (currentToken, callback, state)" />
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
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="currentToken">前の一覧作成操作によって返される継続トークンです。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            仮想ディレクトリ内の blob 項目のコレクションを含む結果セグメントを返す非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListBlobsSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListBlobsSegmented (bool useFlatBlobListing, Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails blobListingDetails, Nullable&lt;int&gt; maxResults, Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListBlobsSegmented(bool useFlatBlobListing, valuetype Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails blobListingDetails, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory.BeginListBlobsSegmented(System.Boolean,Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginListBlobsSegmented : bool * Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginListBlobsSegmented : bool * Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobDirectory.BeginListBlobsSegmented (useFlatBlobListing, blobListingDetails, maxResults, currentToken, options, operationContext, callback, state)" />
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
        <Parameter Name="useFlatBlobListing" Type="System.Boolean" />
        <Parameter Name="blobListingDetails" Type="Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="useFlatBlobListing">フラット リスト内の blob を一覧表示するかどうか、または仮想ディレクトリで階層的に、blob を一覧表示するかどうかを指定するブール値。</param>
        <param name="blobListingDetails">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" />一覧に含める項目を記述する列挙です。</param>
        <param name="maxResults">5000 の操作あたりの上限に達するまで、一度に返される結果の最大数を示す正の整数値。 この値が場合<c>null</c>結果の最大数が返されます、最大 5000 です。</param>
        <param name="currentToken">前の一覧作成操作によって返される継続トークンです。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            仮想ディレクトリ内の blob 項目のコレクションを含む結果セグメントを返す非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Container">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer Container { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer Container" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory.Container" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Container As CloudBlobContainer" />
      <MemberSignature Language="F#" Value="member this.Container : Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer" Usage="Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory.Container" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            仮想ディレクトリのコンテナーを取得します。
            </summary>
        <value><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer" /> オブジェクト。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndListBlobsSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment EndListBlobsSegmented (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment EndListBlobsSegmented(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory.EndListBlobsSegmented(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndListBlobsSegmented (asyncResult As IAsyncResult) As BlobResultSegment" />
      <MemberSignature Language="F#" Value="abstract member EndListBlobsSegmented : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&#xA;override this.EndListBlobsSegmented : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment" Usage="cloudBlobDirectory.EndListBlobsSegmented asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</param>
        <summary>
            仮想ディレクトリ内の blob 項目のコレクションを含む結果セグメントを返す非同期操作を終了します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAppendBlobReference">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob GetAppendBlobReference (string blobName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob GetAppendBlobReference(string blobName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory.GetAppendBlobReference(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetAppendBlobReference (blobName As String) As CloudAppendBlob" />
      <MemberSignature Language="F#" Value="abstract member GetAppendBlobReference : string -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob&#xA;override this.GetAppendBlobReference : string -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" Usage="cloudBlobDirectory.GetAppendBlobReference blobName" />
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
        <Parameter Name="blobName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="blobName">Blob の名前を含む文字列。</param>
        <summary>
            この仮想ディレクトリ内には、追加 blob への参照を取得します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAppendBlobReference">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob GetAppendBlobReference (string blobName, Nullable&lt;DateTimeOffset&gt; snapshotTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob GetAppendBlobReference(string blobName, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshotTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory.GetAppendBlobReference(System.String,System.Nullable{System.DateTimeOffset})" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetAppendBlobReference (blobName As String, snapshotTime As Nullable(Of DateTimeOffset)) As CloudAppendBlob" />
      <MemberSignature Language="F#" Value="abstract member GetAppendBlobReference : string * Nullable&lt;DateTimeOffset&gt; -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob&#xA;override this.GetAppendBlobReference : string * Nullable&lt;DateTimeOffset&gt; -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" Usage="cloudBlobDirectory.GetAppendBlobReference (blobName, snapshotTime)" />
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
        <Parameter Name="blobName" Type="System.String" />
        <Parameter Name="snapshotTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
      </Parameters>
      <Docs>
        <param name="blobName">Blob の名前を含む文字列。</param>
        <param name="snapshotTime">A <see cref="T:System.DateTimeOffset" /> blob がスナップショットの場合、スナップショットのタイムスタンプを指定します。</param>
        <summary>
            この仮想ディレクトリ内には、追加 blob への参照を取得します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBlobReference">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.CloudBlob GetBlobReference (string blobName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.CloudBlob GetBlobReference(string blobName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory.GetBlobReference(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetBlobReference (blobName As String) As CloudBlob" />
      <MemberSignature Language="F#" Value="abstract member GetBlobReference : string -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlob&#xA;override this.GetBlobReference : string -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlob" Usage="cloudBlobDirectory.GetBlobReference blobName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.CloudBlob</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blobName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="blobName">Blob の名前を含む文字列。</param>
        <summary>
            この仮想ディレクトリ内の blob への参照を取得します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBlobReference">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.CloudBlob GetBlobReference (string blobName, Nullable&lt;DateTimeOffset&gt; snapshotTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.CloudBlob GetBlobReference(string blobName, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshotTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory.GetBlobReference(System.String,System.Nullable{System.DateTimeOffset})" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetBlobReference (blobName As String, snapshotTime As Nullable(Of DateTimeOffset)) As CloudBlob" />
      <MemberSignature Language="F#" Value="abstract member GetBlobReference : string * Nullable&lt;DateTimeOffset&gt; -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlob&#xA;override this.GetBlobReference : string * Nullable&lt;DateTimeOffset&gt; -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlob" Usage="cloudBlobDirectory.GetBlobReference (blobName, snapshotTime)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.CloudBlob</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blobName" Type="System.String" />
        <Parameter Name="snapshotTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
      </Parameters>
      <Docs>
        <param name="blobName">Blob の名前を含む文字列。</param>
        <param name="snapshotTime">A <see cref="T:System.DateTimeOffset" /> blob がスナップショットの場合、スナップショットのタイムスタンプを指定します。</param>
        <summary>
            この仮想ディレクトリ内の blob への参照を取得します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBlockBlobReference">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob GetBlockBlobReference (string blobName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob GetBlockBlobReference(string blobName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory.GetBlockBlobReference(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetBlockBlobReference (blobName As String) As CloudBlockBlob" />
      <MemberSignature Language="F#" Value="abstract member GetBlockBlobReference : string -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob&#xA;override this.GetBlockBlobReference : string -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" Usage="cloudBlobDirectory.GetBlockBlobReference blobName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blobName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="blobName">Blob の名前を含む文字列。</param>
        <summary>
            この仮想ディレクトリで、ブロック blob への参照を取得します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBlockBlobReference">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob GetBlockBlobReference (string blobName, Nullable&lt;DateTimeOffset&gt; snapshotTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob GetBlockBlobReference(string blobName, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshotTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory.GetBlockBlobReference(System.String,System.Nullable{System.DateTimeOffset})" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetBlockBlobReference (blobName As String, snapshotTime As Nullable(Of DateTimeOffset)) As CloudBlockBlob" />
      <MemberSignature Language="F#" Value="abstract member GetBlockBlobReference : string * Nullable&lt;DateTimeOffset&gt; -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob&#xA;override this.GetBlockBlobReference : string * Nullable&lt;DateTimeOffset&gt; -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" Usage="cloudBlobDirectory.GetBlockBlobReference (blobName, snapshotTime)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blobName" Type="System.String" />
        <Parameter Name="snapshotTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
      </Parameters>
      <Docs>
        <param name="blobName">Blob の名前を含む文字列。</param>
        <param name="snapshotTime">A <see cref="T:System.DateTimeOffset" /> blob がスナップショットの場合、スナップショットのタイムスタンプを指定します。</param>
        <summary>
            この仮想ディレクトリで、ブロック blob への参照を取得します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDirectoryReference">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory GetDirectoryReference (string itemName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory GetDirectoryReference(string itemName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory.GetDirectoryReference(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetDirectoryReference (itemName As String) As CloudBlobDirectory" />
      <MemberSignature Language="F#" Value="abstract member GetDirectoryReference : string -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory&#xA;override this.GetDirectoryReference : string -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" Usage="cloudBlobDirectory.GetDirectoryReference itemName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="itemName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="itemName">仮想サブディレクトリの名前。</param>
        <summary>
            この仮想ディレクトリ内の仮想サブディレクトリを返します。
            </summary>
        <returns>A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" />仮想サブディレクトリを表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPageBlobReference">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob GetPageBlobReference (string blobName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob GetPageBlobReference(string blobName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory.GetPageBlobReference(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetPageBlobReference (blobName As String) As CloudPageBlob" />
      <MemberSignature Language="F#" Value="abstract member GetPageBlobReference : string -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob&#xA;override this.GetPageBlobReference : string -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" Usage="cloudBlobDirectory.GetPageBlobReference blobName" />
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
        <Parameter Name="blobName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="blobName">Blob の名前を含む文字列。</param>
        <summary>
            この仮想ディレクトリ内のページ blob への参照を取得します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPageBlobReference">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob GetPageBlobReference (string blobName, Nullable&lt;DateTimeOffset&gt; snapshotTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob GetPageBlobReference(string blobName, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshotTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory.GetPageBlobReference(System.String,System.Nullable{System.DateTimeOffset})" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetPageBlobReference (blobName As String, snapshotTime As Nullable(Of DateTimeOffset)) As CloudPageBlob" />
      <MemberSignature Language="F#" Value="abstract member GetPageBlobReference : string * Nullable&lt;DateTimeOffset&gt; -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob&#xA;override this.GetPageBlobReference : string * Nullable&lt;DateTimeOffset&gt; -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" Usage="cloudBlobDirectory.GetPageBlobReference (blobName, snapshotTime)" />
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
        <Parameter Name="blobName" Type="System.String" />
        <Parameter Name="snapshotTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
      </Parameters>
      <Docs>
        <param name="blobName">ページ blob の名前。</param>
        <param name="snapshotTime">A <see cref="T:System.DateTimeOffset" /> blob がスナップショットの場合、スナップショットのタイムスタンプを指定します。</param>
        <summary>
            この仮想ディレクトリ内のページ blob への参照を返します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBlobs">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.IListBlobItem&gt; ListBlobs (bool useFlatBlobListing = false, Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails blobListingDetails = Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails.None, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.IListBlobItem&gt; ListBlobs(bool useFlatBlobListing, valuetype Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails blobListingDetails, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory.ListBlobs(System.Boolean,Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ListBlobs : bool * Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Blob.IListBlobItem&gt;&#xA;override this.ListBlobs : bool * Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Blob.IListBlobItem&gt;" Usage="cloudBlobDirectory.ListBlobs (useFlatBlobListing, blobListingDetails, options, operationContext)" />
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
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.IListBlobItem&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="useFlatBlobListing" Type="System.Boolean" />
        <Parameter Name="blobListingDetails" Type="Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="useFlatBlobListing">フラット リスト内の blob を一覧表示するかどうか、または仮想ディレクトリで階層的に、blob を一覧表示するかどうかを指定するブール値。</param>
        <param name="blobListingDetails">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" />一覧に含める項目を記述する列挙です。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。 場合<c>null</c>既定のオプションは、要求に適用されます。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            遅延を取得する仮想ディレクトリで、blob の列挙可能なコレクションを返します。
            </summary>
        <returns>実装するオブジェクトの列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.Blob.IListBlobItem" />遅れてが取得されます。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBlobsSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment ListBlobsSegmented (Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment ListBlobsSegmented(class Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory.ListBlobsSegmented(Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ListBlobsSegmented (currentToken As BlobContinuationToken) As BlobResultSegment" />
      <MemberSignature Language="F#" Value="abstract member ListBlobsSegmented : Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken -&gt; Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&#xA;override this.ListBlobsSegmented : Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken -&gt; Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment" Usage="cloudBlobDirectory.ListBlobsSegmented currentToken" />
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
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />
      </Parameters>
      <Docs>
        <param name="currentToken">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />前の一覧作成操作によって返されるオブジェクト。</param>
        <summary>
            仮想ディレクトリ内の blob 項目のコレクションを含む結果セグメントを返します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBlobsSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment ListBlobsSegmented (bool useFlatBlobListing, Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails blobListingDetails, Nullable&lt;int&gt; maxResults, Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment ListBlobsSegmented(bool useFlatBlobListing, valuetype Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails blobListingDetails, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory.ListBlobsSegmented(System.Boolean,Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ListBlobsSegmented : bool * Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&#xA;override this.ListBlobsSegmented : bool * Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment" Usage="cloudBlobDirectory.ListBlobsSegmented (useFlatBlobListing, blobListingDetails, maxResults, currentToken, options, operationContext)" />
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
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="useFlatBlobListing" Type="System.Boolean" />
        <Parameter Name="blobListingDetails" Type="Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="useFlatBlobListing">フラット リスト内の blob を一覧表示するかどうか、または仮想ディレクトリで階層的に、blob を一覧表示するかどうかを指定するブール値。</param>
        <param name="blobListingDetails">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" />一覧に含める項目を記述する列挙です。</param>
        <param name="maxResults">5000 の操作あたりの上限に達するまで、一度に返される結果の最大数を示す正の整数値。 この値が場合<c>null</c>結果の最大数が返されます、最大 5000 です。</param>
        <param name="currentToken">前の一覧作成操作によって返される継続トークンです。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            仮想ディレクトリ内の blob 項目のコレクションを含む結果セグメントを返します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBlobsSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt; ListBlobsSegmentedAsync (Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt; ListBlobsSegmentedAsync(class Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory.ListBlobsSegmentedAsync(Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ListBlobsSegmentedAsync (currentToken As BlobContinuationToken) As Task(Of BlobResultSegment)" />
      <MemberSignature Language="F#" Value="abstract member ListBlobsSegmentedAsync : Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt;&#xA;override this.ListBlobsSegmentedAsync : Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt;" Usage="cloudBlobDirectory.ListBlobsSegmentedAsync currentToken" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />
      </Parameters>
      <Docs>
        <param name="currentToken">前の一覧作成操作によって返される継続トークンです。</param>
        <summary>
            仮想ディレクトリ内の blob 項目のコレクションを含む結果セグメントを返す非同期操作を開始します。
            </summary>
        <returns><see cref="T:System.Threading.Tasks.Task`1" /> 型の <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBlobsSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt; ListBlobsSegmentedAsync (Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt; ListBlobsSegmentedAsync(class Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory.ListBlobsSegmentedAsync(Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListBlobsSegmentedAsync : Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt;&#xA;override this.ListBlobsSegmentedAsync : Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt;" Usage="cloudBlobDirectory.ListBlobsSegmentedAsync (currentToken, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="currentToken">前の一覧作成操作によって返される継続トークンです。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            仮想ディレクトリ内の blob 項目のコレクションを含む結果セグメントを返す非同期操作を開始します。
            </summary>
        <returns><see cref="T:System.Threading.Tasks.Task`1" /> 型の <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBlobsSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt; ListBlobsSegmentedAsync (bool useFlatBlobListing, Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails blobListingDetails, Nullable&lt;int&gt; maxResults, Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt; ListBlobsSegmentedAsync(bool useFlatBlobListing, valuetype Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails blobListingDetails, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory.ListBlobsSegmentedAsync(System.Boolean,Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ListBlobsSegmentedAsync : bool * Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt;&#xA;override this.ListBlobsSegmentedAsync : bool * Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt;" Usage="cloudBlobDirectory.ListBlobsSegmentedAsync (useFlatBlobListing, blobListingDetails, maxResults, currentToken, options, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="useFlatBlobListing" Type="System.Boolean" />
        <Parameter Name="blobListingDetails" Type="Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="useFlatBlobListing">フラット リスト内の blob を一覧表示するかどうか、または仮想ディレクトリで階層的に、blob を一覧表示するかどうかを指定するブール値。</param>
        <param name="blobListingDetails">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" />一覧に含める項目を記述する列挙です。</param>
        <param name="maxResults">5000 の操作あたりの上限に達するまで、一度に返される結果の最大数を示す正の整数値。 この値が場合<c>null</c>結果の最大数が返されます、最大 5000 です。</param>
        <param name="currentToken">前の一覧作成操作によって返される継続トークンです。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            仮想ディレクトリ内の blob 項目のコレクションを含む結果セグメントを返す非同期操作を開始します。
            </summary>
        <returns><see cref="T:System.Threading.Tasks.Task`1" /> 型の <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBlobsSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt; ListBlobsSegmentedAsync (bool useFlatBlobListing, Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails blobListingDetails, Nullable&lt;int&gt; maxResults, Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt; ListBlobsSegmentedAsync(bool useFlatBlobListing, valuetype Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails blobListingDetails, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory.ListBlobsSegmentedAsync(System.Boolean,Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListBlobsSegmentedAsync : bool * Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt;&#xA;override this.ListBlobsSegmentedAsync : bool * Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt;" Usage="cloudBlobDirectory.ListBlobsSegmentedAsync (useFlatBlobListing, blobListingDetails, maxResults, currentToken, options, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="useFlatBlobListing" Type="System.Boolean" />
        <Parameter Name="blobListingDetails" Type="Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="useFlatBlobListing">フラット リスト内の blob を一覧表示するかどうか、または仮想ディレクトリで階層的に、blob を一覧表示するかどうかを指定するブール値。</param>
        <param name="blobListingDetails">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" />一覧に含める項目を記述する列挙です。</param>
        <param name="maxResults">5000 の操作あたりの上限に達するまで、一度に返される結果の最大数を示す正の整数値。 この値が場合<c>null</c>結果の最大数が返されます、最大 5000 です。</param>
        <param name="currentToken">前の一覧作成操作によって返される継続トークンです。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            仮想ディレクトリ内の blob 項目のコレクションを含む結果セグメントを返す非同期操作を開始します。
            </summary>
        <returns><see cref="T:System.Threading.Tasks.Task`1" /> 型の <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parent">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory Parent { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory Parent" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory.Parent" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Parent As CloudBlobDirectory" />
      <MemberSignature Language="F#" Value="member this.Parent : Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" Usage="Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory.Parent" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Storage.Blob.IListBlobItem.Parent</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            仮想ディレクトリの親ディレクトリを取得します。
            </summary>
        <value><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" /> オブジェクト。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Prefix">
      <MemberSignature Language="C#" Value="public string Prefix { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Prefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory.Prefix" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Prefix As String" />
      <MemberSignature Language="F#" Value="member this.Prefix : string" Usage="Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory.Prefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            プレフィックスを取得します。
            </summary>
        <value>プレフィックスを含む文字列。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceClient">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient ServiceClient { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient ServiceClient" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory.ServiceClient" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceClient As CloudBlobClient" />
      <MemberSignature Language="F#" Value="member this.ServiceClient : Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient" Usage="Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory.ServiceClient" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            仮想ディレクトリの Blob サービス クライアントを取得します。
            </summary>
        <value><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient" /> オブジェクト。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageUri">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.StorageUri StorageUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.StorageUri StorageUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory.StorageUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StorageUri As StorageUri" />
      <MemberSignature Language="F#" Value="member this.StorageUri : Microsoft.WindowsAzure.Storage.StorageUri" Usage="Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory.StorageUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.StorageUri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            プライマリとセカンダリの両方の場所の blob ディレクトリの Uri を取得します。
            </summary>
        <value>型のオブジェクト<see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory.StorageUri" />blob ディレクトリの Uri は、プライマリとセカンダリの両方の場所を格納します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Uri">
      <MemberSignature Language="C#" Value="public Uri Uri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Uri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory.Uri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Uri As Uri" />
      <MemberSignature Language="F#" Value="member this.Uri : Uri" Usage="Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory.Uri" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Storage.Blob.IListBlobItem.Uri</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            プライマリの場所の仮想ディレクトリを識別する URI を取得します。
            </summary>
        <value>A<see cref="T:System.Uri" />プライマリの場所に、仮想ディレクトリに URI を格納します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>