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
            <span data-ttu-id="98334-101">区切り文字で指定される blob の仮想ディレクトリを表します。</span><span class="sxs-lookup"><span data-stu-id="98334-101">Represents a virtual directory of blobs, designated by a delimiter character.</span></span>
            </summary>
    <remarks><span data-ttu-id="98334-102">としてカプセル化されるコンテナー<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer" />オブジェクト、ディレクトリ、およびディレクトリのブロック blob とページ blob を保持します。</span><span class="sxs-lookup"><span data-stu-id="98334-102">Containers, which are encapsulated as <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer" /> objects, hold directories, and directories hold block blobs and page blobs.</span></span> <span data-ttu-id="98334-103">ディレクトリは、サブディレクトリを含めることもできます。</span><span class="sxs-lookup"><span data-stu-id="98334-103">Directories can also contain sub-directories.</span></span></remarks>
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
        <param name="currentToken"><span data-ttu-id="98334-104">前の一覧作成操作によって返される継続トークンです。</span><span class="sxs-lookup"><span data-stu-id="98334-104">A continuation token returned by a previous listing operation.</span></span></param>
        <param name="callback"><span data-ttu-id="98334-105"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="98334-105">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="98334-106">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="98334-106">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="98334-107">仮想ディレクトリ内の blob 項目のコレクションを含む結果セグメントを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="98334-107">Begins an asynchronous operation to return a result segment containing a collection of blob items in the virtual directory.</span></span>
            </summary>
        <returns><span data-ttu-id="98334-108"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="98334-108">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
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
        <param name="useFlatBlobListing"><span data-ttu-id="98334-109">フラット リスト内の blob を一覧表示するかどうか、または仮想ディレクトリで階層的に、blob を一覧表示するかどうかを指定するブール値。</span><span class="sxs-lookup"><span data-stu-id="98334-109">A boolean value that specifies whether to list blobs in a flat listing, or whether to list blobs hierarchically, by virtual directory.</span></span></param>
        <param name="blobListingDetails"><span data-ttu-id="98334-110">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" />一覧に含める項目を記述する列挙です。</span><span class="sxs-lookup"><span data-stu-id="98334-110">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" /> enumeration describing which items to include in the listing.</span></span></param>
        <param name="maxResults"><span data-ttu-id="98334-111">5000 の操作あたりの上限に達するまで、一度に返される結果の最大数を示す正の整数値。</span><span class="sxs-lookup"><span data-stu-id="98334-111">A non-negative integer value that indicates the maximum number of results to be returned at a time, up to the per-operation limit of 5000.</span></span> <span data-ttu-id="98334-112">この値が場合<c>null</c>結果の最大数が返されます、最大 5000 です。</span><span class="sxs-lookup"><span data-stu-id="98334-112">If this value is <c>null</c>, the maximum possible number of results will be returned, up to 5000.</span></span></param>
        <param name="currentToken"><span data-ttu-id="98334-113">前の一覧作成操作によって返される継続トークンです。</span><span class="sxs-lookup"><span data-stu-id="98334-113">A continuation token returned by a previous listing operation.</span></span></param>
        <param name="options"><span data-ttu-id="98334-114">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="98334-114">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="98334-115"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="98334-115">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="98334-116"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="98334-116">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="98334-117">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="98334-117">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="98334-118">仮想ディレクトリ内の blob 項目のコレクションを含む結果セグメントを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="98334-118">Begins an asynchronous operation to return a result segment containing a collection of blob items in the virtual directory.</span></span>
            </summary>
        <returns><span data-ttu-id="98334-119"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="98334-119">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
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
            <span data-ttu-id="98334-120">仮想ディレクトリのコンテナーを取得します。</span><span class="sxs-lookup"><span data-stu-id="98334-120">Gets the container for the virtual directory.</span></span>
            </summary>
        <value><span data-ttu-id="98334-121"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="98334-121">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer" /> object.</span></span></value>
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
        <param name="asyncResult"><span data-ttu-id="98334-122"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="98334-122">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="98334-123">仮想ディレクトリ内の blob 項目のコレクションを含む結果セグメントを返す非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="98334-123">Ends an asynchronous operation to return a result segment containing a collection of blob items in the virtual directory.</span></span>
            </summary>
        <returns><span data-ttu-id="98334-124"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="98334-124">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment" /> object.</span></span></returns>
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
        <param name="blobName"><span data-ttu-id="98334-125">Blob の名前を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="98334-125">A string containing the name of the blob.</span></span></param>
        <summary>
            <span data-ttu-id="98334-126">この仮想ディレクトリ内には、追加 blob への参照を取得します。</span><span class="sxs-lookup"><span data-stu-id="98334-126">Gets a reference to an append blob in this virtual directory.</span></span>
            </summary>
        <returns><span data-ttu-id="98334-127"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="98334-127">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" /> object.</span></span></returns>
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
        <param name="blobName"><span data-ttu-id="98334-128">Blob の名前を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="98334-128">A string containing the name of the blob.</span></span></param>
        <param name="snapshotTime"><span data-ttu-id="98334-129">A <see cref="T:System.DateTimeOffset" /> blob がスナップショットの場合、スナップショットのタイムスタンプを指定します。</span><span class="sxs-lookup"><span data-stu-id="98334-129">A <see cref="T:System.DateTimeOffset" /> specifying the snapshot timestamp, if the blob is a snapshot.</span></span></param>
        <summary>
            <span data-ttu-id="98334-130">この仮想ディレクトリ内には、追加 blob への参照を取得します。</span><span class="sxs-lookup"><span data-stu-id="98334-130">Gets a reference to an append blob in this virtual directory.</span></span>
            </summary>
        <returns><span data-ttu-id="98334-131"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="98334-131">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" /> object.</span></span></returns>
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
        <param name="blobName"><span data-ttu-id="98334-132">Blob の名前を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="98334-132">A string containing the name of the blob.</span></span></param>
        <summary>
            <span data-ttu-id="98334-133">この仮想ディレクトリ内の blob への参照を取得します。</span><span class="sxs-lookup"><span data-stu-id="98334-133">Gets a reference to a blob in this virtual directory.</span></span>
            </summary>
        <returns><span data-ttu-id="98334-134"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="98334-134">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> object.</span></span></returns>
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
        <param name="blobName"><span data-ttu-id="98334-135">Blob の名前を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="98334-135">A string containing the name of the blob.</span></span></param>
        <param name="snapshotTime"><span data-ttu-id="98334-136">A <see cref="T:System.DateTimeOffset" /> blob がスナップショットの場合、スナップショットのタイムスタンプを指定します。</span><span class="sxs-lookup"><span data-stu-id="98334-136">A <see cref="T:System.DateTimeOffset" /> specifying the snapshot timestamp, if the blob is a snapshot.</span></span></param>
        <summary>
            <span data-ttu-id="98334-137">この仮想ディレクトリ内の blob への参照を取得します。</span><span class="sxs-lookup"><span data-stu-id="98334-137">Gets a reference to a blob in this virtual directory.</span></span>
            </summary>
        <returns><span data-ttu-id="98334-138"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="98334-138">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> object.</span></span></returns>
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
        <param name="blobName"><span data-ttu-id="98334-139">Blob の名前を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="98334-139">A string containing the name of the blob.</span></span></param>
        <summary>
            <span data-ttu-id="98334-140">この仮想ディレクトリで、ブロック blob への参照を取得します。</span><span class="sxs-lookup"><span data-stu-id="98334-140">Gets a reference to a block blob in this virtual directory.</span></span>
            </summary>
        <returns><span data-ttu-id="98334-141"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="98334-141">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> object.</span></span></returns>
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
        <param name="blobName"><span data-ttu-id="98334-142">Blob の名前を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="98334-142">A string containing the name of the blob.</span></span></param>
        <param name="snapshotTime"><span data-ttu-id="98334-143">A <see cref="T:System.DateTimeOffset" /> blob がスナップショットの場合、スナップショットのタイムスタンプを指定します。</span><span class="sxs-lookup"><span data-stu-id="98334-143">A <see cref="T:System.DateTimeOffset" /> specifying the snapshot timestamp, if the blob is a snapshot.</span></span></param>
        <summary>
            <span data-ttu-id="98334-144">この仮想ディレクトリで、ブロック blob への参照を取得します。</span><span class="sxs-lookup"><span data-stu-id="98334-144">Gets a reference to a block blob in this virtual directory.</span></span>
            </summary>
        <returns><span data-ttu-id="98334-145"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="98334-145">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> object.</span></span></returns>
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
        <param name="itemName"><span data-ttu-id="98334-146">仮想サブディレクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="98334-146">The name of the virtual subdirectory.</span></span></param>
        <summary>
            <span data-ttu-id="98334-147">この仮想ディレクトリ内の仮想サブディレクトリを返します。</span><span class="sxs-lookup"><span data-stu-id="98334-147">Returns a virtual subdirectory within this virtual directory.</span></span>
            </summary>
        <returns><span data-ttu-id="98334-148">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" />仮想サブディレクトリを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="98334-148">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" /> object representing the virtual subdirectory.</span></span></returns>
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
        <param name="blobName"><span data-ttu-id="98334-149">Blob の名前を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="98334-149">A string containing the name of the blob.</span></span></param>
        <summary>
            <span data-ttu-id="98334-150">この仮想ディレクトリ内のページ blob への参照を取得します。</span><span class="sxs-lookup"><span data-stu-id="98334-150">Gets a reference to a page blob in this virtual directory.</span></span>
            </summary>
        <returns><span data-ttu-id="98334-151"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="98334-151">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" /> object.</span></span></returns>
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
        <param name="blobName"><span data-ttu-id="98334-152">ページ blob の名前。</span><span class="sxs-lookup"><span data-stu-id="98334-152">The name of the page blob.</span></span></param>
        <param name="snapshotTime"><span data-ttu-id="98334-153">A <see cref="T:System.DateTimeOffset" /> blob がスナップショットの場合、スナップショットのタイムスタンプを指定します。</span><span class="sxs-lookup"><span data-stu-id="98334-153">A <see cref="T:System.DateTimeOffset" /> specifying the snapshot timestamp, if the blob is a snapshot.</span></span></param>
        <summary>
            <span data-ttu-id="98334-154">この仮想ディレクトリ内のページ blob への参照を返します。</span><span class="sxs-lookup"><span data-stu-id="98334-154">Returns a reference to a page blob in this virtual directory.</span></span>
            </summary>
        <returns><span data-ttu-id="98334-155"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="98334-155">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" /> object.</span></span></returns>
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
        <param name="useFlatBlobListing"><span data-ttu-id="98334-156">フラット リスト内の blob を一覧表示するかどうか、または仮想ディレクトリで階層的に、blob を一覧表示するかどうかを指定するブール値。</span><span class="sxs-lookup"><span data-stu-id="98334-156">A boolean value that specifies whether to list blobs in a flat listing, or whether to list blobs hierarchically, by virtual directory.</span></span></param>
        <param name="blobListingDetails"><span data-ttu-id="98334-157">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" />一覧に含める項目を記述する列挙です。</span><span class="sxs-lookup"><span data-stu-id="98334-157">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" /> enumeration describing which items to include in the listing.</span></span></param>
        <param name="options"><span data-ttu-id="98334-158">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="98334-158">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="98334-159">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="98334-159">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="98334-160"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="98334-160">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="98334-161">遅延を取得する仮想ディレクトリで、blob の列挙可能なコレクションを返します。</span><span class="sxs-lookup"><span data-stu-id="98334-161">Returns an enumerable collection of the blobs in the virtual directory that are retrieved lazily.</span></span>
            </summary>
        <returns><span data-ttu-id="98334-162">実装するオブジェクトの列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.Blob.IListBlobItem" />遅れてが取得されます。</span><span class="sxs-lookup"><span data-stu-id="98334-162">An enumerable collection of objects that implement <see cref="T:Microsoft.WindowsAzure.Storage.Blob.IListBlobItem" /> and are retrieved lazily.</span></span></returns>
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
        <param name="currentToken"><span data-ttu-id="98334-163">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />前の一覧作成操作によって返されるオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="98334-163">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" /> object returned by a previous listing operation.</span></span></param>
        <summary>
            <span data-ttu-id="98334-164">仮想ディレクトリ内の blob 項目のコレクションを含む結果セグメントを返します。</span><span class="sxs-lookup"><span data-stu-id="98334-164">Returns a result segment containing a collection of blob items in the virtual directory.</span></span>
            </summary>
        <returns><span data-ttu-id="98334-165"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="98334-165">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment" /> object.</span></span></returns>
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
        <param name="useFlatBlobListing"><span data-ttu-id="98334-166">フラット リスト内の blob を一覧表示するかどうか、または仮想ディレクトリで階層的に、blob を一覧表示するかどうかを指定するブール値。</span><span class="sxs-lookup"><span data-stu-id="98334-166">A boolean value that specifies whether to list blobs in a flat listing, or whether to list blobs hierarchically, by virtual directory.</span></span></param>
        <param name="blobListingDetails"><span data-ttu-id="98334-167">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" />一覧に含める項目を記述する列挙です。</span><span class="sxs-lookup"><span data-stu-id="98334-167">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" /> enumeration describing which items to include in the listing.</span></span></param>
        <param name="maxResults"><span data-ttu-id="98334-168">5000 の操作あたりの上限に達するまで、一度に返される結果の最大数を示す正の整数値。</span><span class="sxs-lookup"><span data-stu-id="98334-168">A non-negative integer value that indicates the maximum number of results to be returned at a time, up to the per-operation limit of 5000.</span></span> <span data-ttu-id="98334-169">この値が場合<c>null</c>結果の最大数が返されます、最大 5000 です。</span><span class="sxs-lookup"><span data-stu-id="98334-169">If this value is <c>null</c>, the maximum possible number of results will be returned, up to 5000.</span></span></param>
        <param name="currentToken"><span data-ttu-id="98334-170">前の一覧作成操作によって返される継続トークンです。</span><span class="sxs-lookup"><span data-stu-id="98334-170">A continuation token returned by a previous listing operation.</span></span></param>
        <param name="options"><span data-ttu-id="98334-171">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="98334-171">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="98334-172"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="98334-172">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="98334-173">仮想ディレクトリ内の blob 項目のコレクションを含む結果セグメントを返します。</span><span class="sxs-lookup"><span data-stu-id="98334-173">Returns a result segment containing a collection of blob items in the virtual directory.</span></span>
            </summary>
        <returns><span data-ttu-id="98334-174"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="98334-174">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment" /> object.</span></span></returns>
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
        <param name="currentToken"><span data-ttu-id="98334-175">前の一覧作成操作によって返される継続トークンです。</span><span class="sxs-lookup"><span data-stu-id="98334-175">A continuation token returned by a previous listing operation.</span></span></param>
        <summary>
            <span data-ttu-id="98334-176">仮想ディレクトリ内の blob 項目のコレクションを含む結果セグメントを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="98334-176">Initiates an asynchronous operation to return a result segment containing a collection of blob items in the virtual directory.</span></span>
            </summary>
        <returns><span data-ttu-id="98334-177"><see cref="T:System.Threading.Tasks.Task`1" /> 型の <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="98334-177">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment" />.</span></span></returns>
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
        <param name="currentToken"><span data-ttu-id="98334-178">前の一覧作成操作によって返される継続トークンです。</span><span class="sxs-lookup"><span data-stu-id="98334-178">A continuation token returned by a previous listing operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="98334-179">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="98334-179">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="98334-180">仮想ディレクトリ内の blob 項目のコレクションを含む結果セグメントを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="98334-180">Initiates an asynchronous operation to return a result segment containing a collection of blob items in the virtual directory.</span></span>
            </summary>
        <returns><span data-ttu-id="98334-181"><see cref="T:System.Threading.Tasks.Task`1" /> 型の <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="98334-181">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment" />.</span></span></returns>
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
        <param name="useFlatBlobListing"><span data-ttu-id="98334-182">フラット リスト内の blob を一覧表示するかどうか、または仮想ディレクトリで階層的に、blob を一覧表示するかどうかを指定するブール値。</span><span class="sxs-lookup"><span data-stu-id="98334-182">A boolean value that specifies whether to list blobs in a flat listing, or whether to list blobs hierarchically, by virtual directory.</span></span></param>
        <param name="blobListingDetails"><span data-ttu-id="98334-183">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" />一覧に含める項目を記述する列挙です。</span><span class="sxs-lookup"><span data-stu-id="98334-183">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" /> enumeration describing which items to include in the listing.</span></span></param>
        <param name="maxResults"><span data-ttu-id="98334-184">5000 の操作あたりの上限に達するまで、一度に返される結果の最大数を示す正の整数値。</span><span class="sxs-lookup"><span data-stu-id="98334-184">A non-negative integer value that indicates the maximum number of results to be returned at a time, up to the per-operation limit of 5000.</span></span> <span data-ttu-id="98334-185">この値が場合<c>null</c>結果の最大数が返されます、最大 5000 です。</span><span class="sxs-lookup"><span data-stu-id="98334-185">If this value is <c>null</c>, the maximum possible number of results will be returned, up to 5000.</span></span></param>
        <param name="currentToken"><span data-ttu-id="98334-186">前の一覧作成操作によって返される継続トークンです。</span><span class="sxs-lookup"><span data-stu-id="98334-186">A continuation token returned by a previous listing operation.</span></span></param>
        <param name="options"><span data-ttu-id="98334-187">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="98334-187">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="98334-188"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="98334-188">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="98334-189">仮想ディレクトリ内の blob 項目のコレクションを含む結果セグメントを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="98334-189">Initiates an asynchronous operation to return a result segment containing a collection of blob items in the virtual directory.</span></span>
            </summary>
        <returns><span data-ttu-id="98334-190"><see cref="T:System.Threading.Tasks.Task`1" /> 型の <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="98334-190">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment" />.</span></span></returns>
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
        <param name="useFlatBlobListing"><span data-ttu-id="98334-191">フラット リスト内の blob を一覧表示するかどうか、または仮想ディレクトリで階層的に、blob を一覧表示するかどうかを指定するブール値。</span><span class="sxs-lookup"><span data-stu-id="98334-191">A boolean value that specifies whether to list blobs in a flat listing, or whether to list blobs hierarchically, by virtual directory.</span></span></param>
        <param name="blobListingDetails"><span data-ttu-id="98334-192">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" />一覧に含める項目を記述する列挙です。</span><span class="sxs-lookup"><span data-stu-id="98334-192">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" /> enumeration describing which items to include in the listing.</span></span></param>
        <param name="maxResults"><span data-ttu-id="98334-193">5000 の操作あたりの上限に達するまで、一度に返される結果の最大数を示す正の整数値。</span><span class="sxs-lookup"><span data-stu-id="98334-193">A non-negative integer value that indicates the maximum number of results to be returned at a time, up to the per-operation limit of 5000.</span></span> <span data-ttu-id="98334-194">この値が場合<c>null</c>結果の最大数が返されます、最大 5000 です。</span><span class="sxs-lookup"><span data-stu-id="98334-194">If this value is <c>null</c>, the maximum possible number of results will be returned, up to 5000.</span></span></param>
        <param name="currentToken"><span data-ttu-id="98334-195">前の一覧作成操作によって返される継続トークンです。</span><span class="sxs-lookup"><span data-stu-id="98334-195">A continuation token returned by a previous listing operation.</span></span></param>
        <param name="options"><span data-ttu-id="98334-196">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="98334-196">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="98334-197"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="98334-197">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="98334-198">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="98334-198">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="98334-199">仮想ディレクトリ内の blob 項目のコレクションを含む結果セグメントを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="98334-199">Initiates an asynchronous operation to return a result segment containing a collection of blob items in the virtual directory.</span></span>
            </summary>
        <returns><span data-ttu-id="98334-200"><see cref="T:System.Threading.Tasks.Task`1" /> 型の <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="98334-200">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment" />.</span></span></returns>
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
            <span data-ttu-id="98334-201">仮想ディレクトリの親ディレクトリを取得します。</span><span class="sxs-lookup"><span data-stu-id="98334-201">Gets the parent directory for the virtual directory.</span></span>
            </summary>
        <value><span data-ttu-id="98334-202"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="98334-202">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" /> object.</span></span></value>
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
            <span data-ttu-id="98334-203">プレフィックスを取得します。</span><span class="sxs-lookup"><span data-stu-id="98334-203">Gets the prefix.</span></span>
            </summary>
        <value><span data-ttu-id="98334-204">プレフィックスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="98334-204">A string containing the prefix.</span></span></value>
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
            <span data-ttu-id="98334-205">仮想ディレクトリの Blob サービス クライアントを取得します。</span><span class="sxs-lookup"><span data-stu-id="98334-205">Gets the Blob service client for the virtual directory.</span></span>
            </summary>
        <value><span data-ttu-id="98334-206"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="98334-206">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient" /> object.</span></span></value>
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
            <span data-ttu-id="98334-207">プライマリとセカンダリの両方の場所の blob ディレクトリの Uri を取得します。</span><span class="sxs-lookup"><span data-stu-id="98334-207">Gets the blob directory's URIs for both the primary and secondary locations.</span></span>
            </summary>
        <value><span data-ttu-id="98334-208">型のオブジェクト<see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory.StorageUri" />blob ディレクトリの Uri は、プライマリとセカンダリの両方の場所を格納します。</span><span class="sxs-lookup"><span data-stu-id="98334-208">An object of type <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory.StorageUri" /> containing the blob directory's URIs for both the primary and secondary locations.</span></span></value>
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
            <span data-ttu-id="98334-209">プライマリの場所の仮想ディレクトリを識別する URI を取得します。</span><span class="sxs-lookup"><span data-stu-id="98334-209">Gets the URI that identifies the virtual directory for the primary location.</span></span>
            </summary>
        <value><span data-ttu-id="98334-210">A<see cref="T:System.Uri" />プライマリの場所に、仮想ディレクトリに URI を格納します。</span><span class="sxs-lookup"><span data-stu-id="98334-210">A <see cref="T:System.Uri" /> containing the URI to the virtual directory, at the primary location.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>