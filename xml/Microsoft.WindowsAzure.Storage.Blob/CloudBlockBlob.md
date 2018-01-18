<Type Name="CloudBlockBlob" FullName="Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob">
  <TypeSignature Language="C#" Value="public class CloudBlockBlob : Microsoft.WindowsAzure.Storage.Blob.CloudBlob, Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CloudBlockBlob extends Microsoft.WindowsAzure.Storage.Blob.CloudBlob implements class Microsoft.WindowsAzure.Storage.Blob.ICloudBlob, class Microsoft.WindowsAzure.Storage.Blob.IListBlobItem" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" />
  <TypeSignature Language="VB.NET" Value="Public Class CloudBlockBlob&#xA;Inherits CloudBlob&#xA;Implements ICloudBlob" />
  <TypeSignature Language="F#" Value="type CloudBlockBlob = class&#xA;    inherit CloudBlob&#xA;    interface ICloudBlob&#xA;    interface IListBlobItem" />
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
            <span data-ttu-id="1aa1d-101">一連のブロックとしてアップロードされる blob を表します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-101">Represents a blob that is uploaded as a set of blocks.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudBlockBlob (Uri blobAbsoluteUri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri blobAbsoluteUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.#ctor(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (blobAbsoluteUri As Uri)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob : Uri -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" Usage="new Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob blobAbsoluteUri" />
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
        <param name="blobAbsoluteUri"><span data-ttu-id="1aa1d-102">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-102">A <see cref="T:System.Uri" /> specifying the absolute URI to the blob.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-103">新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" />クラス blob への絶対 URI を使用します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-103">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> class using an absolute URI to the blob.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudBlockBlob (Uri blobAbsoluteUri, Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri blobAbsoluteUri, class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.#ctor(System.Uri,Microsoft.WindowsAzure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (blobAbsoluteUri As Uri, credentials As StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob : Uri * Microsoft.WindowsAzure.Storage.Auth.StorageCredentials -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" Usage="new Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob (blobAbsoluteUri, credentials)" />
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
        <param name="blobAbsoluteUri"><span data-ttu-id="1aa1d-104">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-104">A <see cref="T:System.Uri" /> specifying the absolute URI to the blob.</span></span></param>
        <param name="credentials"><span data-ttu-id="1aa1d-105"><see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-105">A <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-106">新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" />クラス blob への絶対 URI を使用します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-106">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> class using an absolute URI to the blob.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudBlockBlob (Microsoft.WindowsAzure.Storage.StorageUri blobAbsoluteUri, Nullable&lt;DateTimeOffset&gt; snapshotTime, Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.StorageUri blobAbsoluteUri, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshotTime, class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.#ctor(Microsoft.WindowsAzure.Storage.StorageUri,System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (blobAbsoluteUri As StorageUri, snapshotTime As Nullable(Of DateTimeOffset), credentials As StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob : Microsoft.WindowsAzure.Storage.StorageUri * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.Auth.StorageCredentials -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" Usage="new Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob (blobAbsoluteUri, snapshotTime, credentials)" />
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
        <param name="blobAbsoluteUri"><span data-ttu-id="1aa1d-107">A<see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" />プライマリとセカンダリの両方の場所にある blob を絶対 URI を格納します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-107">A <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" /> containing the absolute URI to the blob at both the primary and secondary locations.</span></span></param>
        <param name="snapshotTime"><span data-ttu-id="1aa1d-108">A <see cref="T:System.DateTimeOffset" /> blob がスナップショットの場合、スナップショットのタイムスタンプを指定します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-108">A <see cref="T:System.DateTimeOffset" /> specifying the snapshot timestamp, if the blob is a snapshot.</span></span></param>
        <param name="credentials"><span data-ttu-id="1aa1d-109"><see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-109">A <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-110">新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" />クラス blob への絶対 URI を使用します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-110">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> class using an absolute URI to the blob.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudBlockBlob (Uri blobAbsoluteUri, Nullable&lt;DateTimeOffset&gt; snapshotTime, Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri blobAbsoluteUri, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshotTime, class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.#ctor(System.Uri,System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (blobAbsoluteUri As Uri, snapshotTime As Nullable(Of DateTimeOffset), credentials As StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob : Uri * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.Auth.StorageCredentials -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" Usage="new Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob (blobAbsoluteUri, snapshotTime, credentials)" />
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
        <param name="blobAbsoluteUri"><span data-ttu-id="1aa1d-111">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-111">A <see cref="T:System.Uri" /> specifying the absolute URI to the blob.</span></span></param>
        <param name="snapshotTime"><span data-ttu-id="1aa1d-112">A <see cref="T:System.DateTimeOffset" /> blob がスナップショットの場合、スナップショットのタイムスタンプを指定します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-112">A <see cref="T:System.DateTimeOffset" /> specifying the snapshot timestamp, if the blob is a snapshot.</span></span></param>
        <param name="credentials"><span data-ttu-id="1aa1d-113"><see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-113">A <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-114">新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" />クラス blob への絶対 URI を使用します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-114">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> class using an absolute URI to the blob.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateSnapshot">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreateSnapshot (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreateSnapshot(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginCreateSnapshot(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginCreateSnapshot (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateSnapshot : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreateSnapshot : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginCreateSnapshot (callback, state)" />
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
        <param name="callback"><span data-ttu-id="1aa1d-115"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-115">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="1aa1d-116">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-116">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-117">Blob のスナップショットを作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-117">Begins an asynchronous operation to create a snapshot of the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-118"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-118">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateSnapshot">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreateSnapshot (System.Collections.Generic.IDictionary&lt;string,string&gt; metadata, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreateSnapshot(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; metadata, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginCreateSnapshot(System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateSnapshot : System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreateSnapshot : System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginCreateSnapshot (metadata, accessCondition, options, operationContext, callback, state)" />
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
        <param name="metadata"><span data-ttu-id="1aa1d-119">スナップショットのメタデータを定義する名前と値のペアのコレクション。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-119">A collection of name-value pairs defining the metadata of the snapshot.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="1aa1d-120"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-120">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="1aa1d-121">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-121">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-122">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> 、要求の追加オプションを指定するオブジェクトまたは<c>null</c>です。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-122">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request, or <c>null</c>.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-123"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-123">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="1aa1d-124"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-124">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="1aa1d-125">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-125">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-126">Blob のスナップショットを作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-126">Begins an asynchronous operation to create a snapshot of the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-127"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-127">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDownloadBlockList">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDownloadBlockList (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDownloadBlockList(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginDownloadBlockList(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginDownloadBlockList (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginDownloadBlockList : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDownloadBlockList : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginDownloadBlockList (callback, state)" />
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
        <param name="callback"><span data-ttu-id="1aa1d-128"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-128">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="1aa1d-129">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-129">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-130">指定されたブロック一覧フィルターを使用して、blob のブロックの列挙可能なコレクションを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-130">Begins an asynchronous operation to return an enumerable collection of the blob's blocks, using the specified block list filter.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-131"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-131">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDownloadBlockList">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDownloadBlockList (Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter blockListingFilter, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDownloadBlockList(valuetype Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter blockListingFilter, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginDownloadBlockList(Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginDownloadBlockList : Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDownloadBlockList : Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginDownloadBlockList (blockListingFilter, accessCondition, options, operationContext, callback, state)" />
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
        <Parameter Name="blockListingFilter" Type="Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="blockListingFilter"><span data-ttu-id="1aa1d-132">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter" />コミット後のブロック、コミット前のブロック、またはその両方を返すかどうかを示す列挙値。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-132">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter" /> enumeration value that indicates whether to return committed blocks, uncommitted blocks, or both.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="1aa1d-133"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-133">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="1aa1d-134">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-134">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-135">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-135">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-136"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-136">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="1aa1d-137"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-137">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="1aa1d-138">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-138">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-139">指定されたブロック一覧フィルターを使用して、blob のブロックの列挙可能なコレクションを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-139">Begins an asynchronous operation to return an enumerable collection of the blob's blocks, using the specified block list filter.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-140"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-140">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDownloadText">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDownloadText (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDownloadText(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginDownloadText(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginDownloadText (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginDownloadText : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDownloadText : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginDownloadText (callback, state)" />
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
        <param name="callback"><span data-ttu-id="1aa1d-141"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-141">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="1aa1d-142">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-142">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-143">Blob の内容を文字列としてダウンロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-143">Begins an asynchronous operation to download the blob's contents as a string.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-144"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-144">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDownloadText">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDownloadText (System.Text.Encoding encoding, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDownloadText(class System.Text.Encoding encoding, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginDownloadText(System.Text.Encoding,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginDownloadText : System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDownloadText : System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginDownloadText (encoding, accessCondition, options, operationContext, callback, state)" />
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
        <param name="encoding"><span data-ttu-id="1aa1d-145">使用するテキスト エンコーディングを示すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-145">An object that indicates the text encoding to use.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="1aa1d-146"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-146">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-147">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-147">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-148"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-148">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="1aa1d-149"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-149">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="1aa1d-150">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-150">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-151">Blob の内容を文字列としてダウンロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-151">Begins an asynchronous operation to download the blob's contents as a string.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-152"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-152">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginOpenWrite">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginOpenWrite (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginOpenWrite(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginOpenWrite(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginOpenWrite (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginOpenWrite : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginOpenWrite : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginOpenWrite (callback, state)" />
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
        <param name="callback"><span data-ttu-id="1aa1d-153"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-153">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="1aa1d-154">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-154">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-155">Blob に書き込むためのストリームを開く非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-155">Begins an asynchronous operation to open a stream for writing to the blob.</span></span> <span data-ttu-id="1aa1d-156">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-156">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-157"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-157">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="1aa1d-158">このメソッドへの呼び出しを常に、注意してください、<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginFetchAttributes(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />内部的メソッドです。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-158">Note that this method always makes a call to the <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginFetchAttributes(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" /> method under the covers.</span></span></para>
          <para><span data-ttu-id="1aa1d-159">設定、 <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.StreamWriteSizeInBytes" /> mb 16 KB ~ 100 MB までの範囲のバイトの書き込みは、ブロック サイズを指定するには、このメソッドを呼び出す前に、プロパティです。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-159">Set the <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.StreamWriteSizeInBytes" /> property before calling this method to specify the block size to write, in bytes, ranging from between 16 KB and 100 MB inclusive.</span></span></para>
          <para><span data-ttu-id="1aa1d-160">例外をスローする、上書きすることではなく、blob が存在する場合は、次を参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginOpenWrite(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />です。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-160">To throw an exception if the blob exists instead of overwriting it, see <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginOpenWrite(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginOpenWrite">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginOpenWrite (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginOpenWrite(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginOpenWrite(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginOpenWrite : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginOpenWrite : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginOpenWrite (accessCondition, options, operationContext, callback, state)" />
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
        <param name="accessCondition"><span data-ttu-id="1aa1d-161"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-161">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="1aa1d-162">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-162">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-163">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-163">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-164"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-164">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="1aa1d-165"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-165">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="1aa1d-166">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-166">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-167">Blob に書き込むためのストリームを開く非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-167">Begins an asynchronous operation to open a stream for writing to the blob.</span></span> <span data-ttu-id="1aa1d-168">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-168">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-169"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-169">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="1aa1d-170">このメソッドへの呼び出しを常に、注意してください、<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginFetchAttributes(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />内部的メソッドです。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-170">Note that this method always makes a call to the <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginFetchAttributes(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" /> method under the covers.</span></span></para>
          <para><span data-ttu-id="1aa1d-171">設定、 <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.StreamWriteSizeInBytes" /> mb 16 KB ~ 100 MB までの範囲のバイトの書き込みは、ブロック サイズを指定するには、このメソッドを呼び出す前に、プロパティです。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-171">Set the <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.StreamWriteSizeInBytes" /> property before calling this method to specify the block size to write, in bytes, ranging from between 16 KB and 100 MB inclusive.</span></span></para>
          <para><span data-ttu-id="1aa1d-172">これを上書きする代わりに blob が存在する場合は、例外をスロー、渡す、<see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />オブジェクトを使用して生成<see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />です。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-172">To throw an exception if the blob exists instead of overwriting it, pass in an <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object generated using <see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginPutBlock">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginPutBlock (string blockId, System.IO.Stream blockData, string contentMD5, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginPutBlock(string blockId, class System.IO.Stream blockData, string contentMD5, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginPutBlock(System.String,System.IO.Stream,System.String,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginPutBlock (blockId As String, blockData As Stream, contentMD5 As String, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginPutBlock : string * System.IO.Stream * string * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginPutBlock : string * System.IO.Stream * string * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginPutBlock (blockId, blockData, contentMD5, callback, state)" />
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
        <Parameter Name="blockId" Type="System.String" />
        <Parameter Name="blockData" Type="System.IO.Stream" />
        <Parameter Name="contentMD5" Type="System.String" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="blockId"><span data-ttu-id="1aa1d-173">ブロックを識別する Base64 でエンコードされた文字列。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-173">A Base64-encoded string that identifies the block.</span></span></param>
        <param name="blockData"><span data-ttu-id="1aa1d-174">A<see cref="T:System.IO.Stream" />ブロックのデータを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-174">A <see cref="T:System.IO.Stream" /> object that provides the data for the block.</span></span></param>
        <param name="contentMD5"><span data-ttu-id="1aa1d-175">ブロックのトランザクションの整合性を確保するために使用する省略可能なハッシュ値です。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-175">An optional hash value used to ensure transactional integrity for the block.</span></span> <span data-ttu-id="1aa1d-176">あります<c>null</c>または空の文字列。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-176">May be <c>null</c> or an empty string.</span></span></param>
        <param name="callback"><span data-ttu-id="1aa1d-177"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-177">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="1aa1d-178">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-178">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-179">1 つのブロックをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-179">Begins an asynchronous operation to upload a single block.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-180"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-180">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="1aa1d-181">クライアントは、ネットワーク上でトランザクションの整合性を確保するための手段として特定のブロックの配置操作に関して content-md5 ヘッダーを送信することがあります。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-181">Clients may send the Content-MD5 header for a given Put Block operation as a means to ensure transactional integrity over the wire.</span></span> <span data-ttu-id="1aa1d-182"><paramref name="contentMD5" />パラメーターにより、クライアントは、指定したバイトの範囲に提供することを事前に計算された MD5 値へのアクセスを既に持っています。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-182">The <paramref name="contentMD5" /> parameter permits clients who already have access to a pre-computed MD5 value for a given byte range to provide it.</span></span>
            <span data-ttu-id="1aa1d-183">場合、<see cref="P:BlobRequestOptions.UseTransactionalMd5" />プロパティに設定されている<c>true</c>と<paramref name="contentMD5" />にパラメーターが設定されている<c>null</c>、クライアント ライブラリが MD5 値を内部で計算し、します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-183">If the <see cref="P:BlobRequestOptions.UseTransactionalMd5" /> property is set to <c>true</c> and the <paramref name="contentMD5" /> parameter is set to <c>null</c>, then the client library will calculate the MD5 value internally.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginPutBlock">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginPutBlock (string blockId, System.IO.Stream blockData, string contentMD5, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginPutBlock(string blockId, class System.IO.Stream blockData, string contentMD5, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginPutBlock(System.String,System.IO.Stream,System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginPutBlock : string * System.IO.Stream * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginPutBlock : string * System.IO.Stream * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginPutBlock (blockId, blockData, contentMD5, accessCondition, options, operationContext, callback, state)" />
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
        <Parameter Name="blockId" Type="System.String" />
        <Parameter Name="blockData" Type="System.IO.Stream" />
        <Parameter Name="contentMD5" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="blockId"><span data-ttu-id="1aa1d-184">ブロックを識別する Base64 でエンコードされた文字列。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-184">A Base64-encoded string that identifies the block.</span></span></param>
        <param name="blockData"><span data-ttu-id="1aa1d-185">A<see cref="T:System.IO.Stream" />ブロックのデータを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-185">A <see cref="T:System.IO.Stream" /> object that provides the data for the block.</span></span></param>
        <param name="contentMD5"><span data-ttu-id="1aa1d-186">ブロックのトランザクションの整合性を確保するために使用する省略可能なハッシュ値です。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-186">An optional hash value used to ensure transactional integrity for the block.</span></span> <span data-ttu-id="1aa1d-187">あります<c>null</c>または空の文字列。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-187">May be <c>null</c> or an empty string.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="1aa1d-188"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-188">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="1aa1d-189">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-189">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-190">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> 、要求の追加オプションを指定するオブジェクトまたは<c>null</c>です。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-190">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request, or <c>null</c>.</span></span> <span data-ttu-id="1aa1d-191">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-191">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-192"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-192">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="1aa1d-193"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-193">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="1aa1d-194">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-194">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-195">1 つのブロックをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-195">Begins an asynchronous operation to upload a single block.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-196"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-196">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="1aa1d-197">クライアントは、ネットワーク上でトランザクションの整合性を確保するための手段として特定のブロックの配置操作に関して content-md5 ヘッダーを送信することがあります。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-197">Clients may send the Content-MD5 header for a given Put Block operation as a means to ensure transactional integrity over the wire.</span></span> <span data-ttu-id="1aa1d-198"><paramref name="contentMD5" />パラメーターにより、クライアントは、指定したバイトの範囲に提供することを事前に計算された MD5 値へのアクセスを既に持っています。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-198">The <paramref name="contentMD5" /> parameter permits clients who already have access to a pre-computed MD5 value for a given byte range to provide it.</span></span>
            <span data-ttu-id="1aa1d-199">場合、<see cref="P:BlobRequestOptions.UseTransactionalMd5" />プロパティに設定されている<c>true</c>と<paramref name="contentMD5" />にパラメーターが設定されている<c>null</c>、クライアント ライブラリが MD5 値を内部で計算し、します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-199">If the <see cref="P:BlobRequestOptions.UseTransactionalMd5" /> property is set to <c>true</c> and the <paramref name="contentMD5" /> parameter is set to <c>null</c>, then the client library will calculate the MD5 value internally.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginPutBlockList">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginPutBlockList (System.Collections.Generic.IEnumerable&lt;string&gt; blockList, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginPutBlockList(class System.Collections.Generic.IEnumerable`1&lt;string&gt; blockList, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginPutBlockList(System.Collections.Generic.IEnumerable{System.String},System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginPutBlockList (blockList As IEnumerable(Of String), callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginPutBlockList : seq&lt;string&gt; * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginPutBlockList : seq&lt;string&gt; * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginPutBlockList (blockList, callback, state)" />
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
        <Parameter Name="blockList" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="blockList"><span data-ttu-id="1aa1d-200">列挙可能なコレクションのブロック Id、Base64 でエンコードされた文字列として。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-200">An enumerable collection of block IDs, as Base64-encoded strings.</span></span></param>
        <param name="callback"><span data-ttu-id="1aa1d-201"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-201">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="1aa1d-202">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-202">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-203">新規または既存の blob にブロックの一覧をアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-203">Begins an asynchronous operation to upload a list of blocks to a new or existing blob.</span></span> 
            </summary>
        <returns><span data-ttu-id="1aa1d-204"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-204">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginPutBlockList">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginPutBlockList (System.Collections.Generic.IEnumerable&lt;string&gt; blockList, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginPutBlockList(class System.Collections.Generic.IEnumerable`1&lt;string&gt; blockList, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginPutBlockList(System.Collections.Generic.IEnumerable{System.String},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginPutBlockList : seq&lt;string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginPutBlockList : seq&lt;string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginPutBlockList (blockList, accessCondition, options, operationContext, callback, state)" />
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
        <Parameter Name="blockList" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="blockList"><span data-ttu-id="1aa1d-205">列挙可能なコレクションのブロック Id、Base64 でエンコードされた文字列として。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-205">An enumerable collection of block IDs, as Base64-encoded strings.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="1aa1d-206"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-206">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="1aa1d-207">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-207">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-208">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-208">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-209"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-209">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="1aa1d-210"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-210">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="1aa1d-211">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-211">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-212">新規または既存の blob にブロックの一覧をアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-212">Begins an asynchronous operation to upload a list of blocks to a new or existing blob.</span></span> 
            </summary>
        <returns><span data-ttu-id="1aa1d-213"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-213">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetStandardBlobTier">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetStandardBlobTier (Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier standardBlobTier, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetStandardBlobTier(valuetype Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier standardBlobTier, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginSetStandardBlobTier(Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginSetStandardBlobTier : Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetStandardBlobTier : Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginSetStandardBlobTier (standardBlobTier, callback, state)" />
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
        <Parameter Name="standardBlobTier" Type="Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="standardBlobTier"><span data-ttu-id="1aa1d-214">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier" />を設定する層を表すです。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-214">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier" /> representing the tier to set.</span></span></param>
        <param name="callback"><span data-ttu-id="1aa1d-215"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-215">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="1aa1d-216">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-216">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-217">標準的なストレージ アカウントの blob の層を設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-217">Begins an asynchronous operation to set the tier of the blob on a standard storage account.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-218"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-218">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetStandardBlobTier">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetStandardBlobTier (Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier standardBlobTier, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetStandardBlobTier(valuetype Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier standardBlobTier, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginSetStandardBlobTier(Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginSetStandardBlobTier : Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetStandardBlobTier : Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginSetStandardBlobTier (standardBlobTier, accessCondition, options, operationContext, callback, state)" />
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
        <Parameter Name="standardBlobTier" Type="Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="standardBlobTier"><span data-ttu-id="1aa1d-219">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier" />を設定する層を表すです。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-219">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier" /> representing the tier to set.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="1aa1d-220"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-220">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="1aa1d-221">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-221">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-222">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> 、要求の追加オプションを指定するオブジェクトまたは<c>null</c>です。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-222">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request, or <c>null</c>.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-223"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-223">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="1aa1d-224"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-224">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="1aa1d-225">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-225">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-226">標準的なストレージ アカウントの blob の層を設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-226">Begins an asynchronous operation to set the tier of the blob on a standard storage account.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-227"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-227">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStartCopy">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginStartCopy (Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob source, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginStartCopy(class Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob source, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginStartCopy(Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginStartCopy (source As CloudBlockBlob, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="override this.BeginStartCopy : Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginStartCopy (source, callback, state)" />
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
        <Parameter Name="source" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="1aa1d-228"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-228">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> object.</span></span></param>
        <param name="callback"><span data-ttu-id="1aa1d-229"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-229">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="1aa1d-230">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-230">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-231">このブロック blob を別のブロック blob の内容、プロパティ、およびメタデータのコピーを開始する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-231">Begins an asynchronous operation to start copying another block blob's contents, properties, and metadata to this block blob.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-232"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-232">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStartCopy">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginStartCopy (Microsoft.WindowsAzure.Storage.File.CloudFile source, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginStartCopy(class Microsoft.WindowsAzure.Storage.File.CloudFile source, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginStartCopy(Microsoft.WindowsAzure.Storage.File.CloudFile,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginStartCopy (source As CloudFile, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="override this.BeginStartCopy : Microsoft.WindowsAzure.Storage.File.CloudFile * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginStartCopy (source, callback, state)" />
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
        <Parameter Name="source" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="1aa1d-233"><see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-233">A <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> object.</span></span></param>
        <param name="callback"><span data-ttu-id="1aa1d-234"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-234">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="1aa1d-235">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-235">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-236">このブロック blob にファイルの内容、プロパティ、およびメタデータのコピーを開始する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-236">Begins an asynchronous operation to start copying a file's contents, properties, and metadata to this block blob.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-237"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-237">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStartCopy">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginStartCopy (Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob source, Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginStartCopy(class Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob source, class Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, class Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginStartCopy(Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="override this.BeginStartCopy : Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginStartCopy (source, sourceAccessCondition, destAccessCondition, options, operationContext, callback, state)" />
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
        <Parameter Name="source" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" />
        <Parameter Name="sourceAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="destAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="1aa1d-238"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-238">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> object.</span></span></param>
        <param name="sourceAccessCondition"><span data-ttu-id="1aa1d-239"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー元 blob のアクセス条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-239">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the source blob.</span></span> <span data-ttu-id="1aa1d-240">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-240">If <c>null</c>, no condition is used.</span></span></param>
        <param name="destAccessCondition"><span data-ttu-id="1aa1d-241"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー先 blob のアクセス条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-241">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the destination blob.</span></span> <span data-ttu-id="1aa1d-242">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-242">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-243">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-243">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-244"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-244">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="1aa1d-245"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-245">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="1aa1d-246">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-246">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-247">このブロック blob を別のブロック blob の内容、プロパティ、およびメタデータのコピーを開始する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-247">Begins an asynchronous operation to start copying another block blob's contents, properties, and metadata to this block blob.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-248"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-248">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStartCopy">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginStartCopy (Microsoft.WindowsAzure.Storage.File.CloudFile source, Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginStartCopy(class Microsoft.WindowsAzure.Storage.File.CloudFile source, class Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, class Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginStartCopy(Microsoft.WindowsAzure.Storage.File.CloudFile,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="override this.BeginStartCopy : Microsoft.WindowsAzure.Storage.File.CloudFile * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginStartCopy (source, sourceAccessCondition, destAccessCondition, options, operationContext, callback, state)" />
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
        <Parameter Name="source" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="sourceAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="destAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="1aa1d-249"><see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-249">A <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> object.</span></span></param>
        <param name="sourceAccessCondition"><span data-ttu-id="1aa1d-250"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />ソース ファイルのアクセス条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-250">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the source file.</span></span> <span data-ttu-id="1aa1d-251">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-251">If <c>null</c>, no condition is used.</span></span></param>
        <param name="destAccessCondition"><span data-ttu-id="1aa1d-252"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー先 blob のアクセス条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-252">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the destination blob.</span></span> <span data-ttu-id="1aa1d-253">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-253">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-254">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-254">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-255"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-255">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="1aa1d-256"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-256">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="1aa1d-257">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-257">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-258">このブロック blob にファイルの内容、プロパティ、およびメタデータのコピーを開始する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-258">Begins an asynchronous operation to start copying a file's contents, properties, and metadata to this block blob.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-259"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-259">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUploadFromByteArray">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromByteArray (byte[] buffer, int index, int count, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromByteArray(unsigned int8[] buffer, int32 index, int32 count, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginUploadFromByteArray(System.Byte[],System.Int32,System.Int32,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginUploadFromByteArray (buffer As Byte(), index As Integer, count As Integer, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginUploadFromByteArray : byte[] * int * int * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginUploadFromByteArray : byte[] * int * int * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginUploadFromByteArray (buffer, index, count, callback, state)" />
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
        <param name="buffer"><span data-ttu-id="1aa1d-260">バイト配列。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-260">An array of bytes.</span></span></param>
        <param name="index"><span data-ttu-id="1aa1d-261">Blob のバイトのアップロードを開始位置を示すバッファー内の 0 から始まるバイト オフセット。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-261">The zero-based byte offset in buffer at which to begin uploading bytes to the blob.</span></span></param>
        <param name="count"><span data-ttu-id="1aa1d-262">Blob に書き込まれるバイト数。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-262">The number of bytes to be written to the blob.</span></span></param>
        <param name="callback"><span data-ttu-id="1aa1d-263"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-263">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="1aa1d-264">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-264">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-265">バイト配列の内容を blob にアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-265">Begins an asynchronous operation to upload the contents of a byte array to a blob.</span></span> <span data-ttu-id="1aa1d-266">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-266">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-267"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-267">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUploadFromByteArray">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromByteArray (byte[] buffer, int index, int count, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromByteArray(unsigned int8[] buffer, int32 index, int32 count, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginUploadFromByteArray(System.Byte[],System.Int32,System.Int32,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginUploadFromByteArray : byte[] * int * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginUploadFromByteArray : byte[] * int * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginUploadFromByteArray (buffer, index, count, accessCondition, options, operationContext, callback, state)" />
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
        <param name="buffer"><span data-ttu-id="1aa1d-268">バイト配列。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-268">An array of bytes.</span></span></param>
        <param name="index"><span data-ttu-id="1aa1d-269">Blob のバイトのアップロードを開始位置を示すバッファー内の 0 から始まるバイト オフセット。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-269">The zero-based byte offset in buffer at which to begin uploading bytes to the blob.</span></span></param>
        <param name="count"><span data-ttu-id="1aa1d-270">Blob に書き込まれるバイト数。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-270">The number of bytes to be written to the blob.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="1aa1d-271"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-271">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-272">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-272">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-273"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-273">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="1aa1d-274"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-274">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="1aa1d-275">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-275">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-276">バイト配列の内容を blob にアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-276">Begins an asynchronous operation to upload the contents of a byte array to a blob.</span></span> <span data-ttu-id="1aa1d-277">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-277">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-278"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-278">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUploadFromFile">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromFile (string path, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromFile(string path, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginUploadFromFile(System.String,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginUploadFromFile (path As String, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginUploadFromFile : string * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginUploadFromFile : string * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginUploadFromFile (path, callback, state)" />
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
        <param name="path"><span data-ttu-id="1aa1d-279">Blob コンテンツを提供するファイルのパスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-279">A string containing the file path providing the blob content.</span></span></param>
        <param name="callback"><span data-ttu-id="1aa1d-280"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-280">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="1aa1d-281">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-281">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-282">Blob にファイルをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-282">Begins an asynchronous operation to upload a file to a blob.</span></span> <span data-ttu-id="1aa1d-283">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-283">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-284"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-284">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUploadFromFile">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromFile (string path, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromFile(string path, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginUploadFromFile(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginUploadFromFile : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginUploadFromFile : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginUploadFromFile (path, accessCondition, options, operationContext, callback, state)" />
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
        <param name="path"><span data-ttu-id="1aa1d-285">Blob コンテンツを提供するファイルのパスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-285">A string containing the file path providing the blob content.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="1aa1d-286"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-286">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-287">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-287">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-288"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-288">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="1aa1d-289"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-289">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="1aa1d-290">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-290">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-291">Blob にファイルをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-291">Begins an asynchronous operation to upload a file to a blob.</span></span> <span data-ttu-id="1aa1d-292">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-292">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-293"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-293">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUploadFromStream">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromStream (System.IO.Stream source, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromStream(class System.IO.Stream source, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginUploadFromStream(System.IO.Stream,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginUploadFromStream (source As Stream, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginUploadFromStream : System.IO.Stream * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginUploadFromStream : System.IO.Stream * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginUploadFromStream (source, callback, state)" />
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
        <param name="source"><span data-ttu-id="1aa1d-294">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-294">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="callback"><span data-ttu-id="1aa1d-295"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-295">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="1aa1d-296">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-296">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-297">ブロック blob にストリームをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-297">Begins an asynchronous operation to upload a stream to a block blob.</span></span> <span data-ttu-id="1aa1d-298">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-298">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-299"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-299">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUploadFromStream">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromStream (System.IO.Stream source, long length, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromStream(class System.IO.Stream source, int64 length, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginUploadFromStream(System.IO.Stream,System.Int64,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginUploadFromStream (source As Stream, length As Long, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginUploadFromStream : System.IO.Stream * int64 * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginUploadFromStream : System.IO.Stream * int64 * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginUploadFromStream (source, length, callback, state)" />
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
        <param name="source"><span data-ttu-id="1aa1d-300">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-300">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="length"><span data-ttu-id="1aa1d-301">現在の位置に、ソース ストリームから書き込むバイト数。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-301">The number of bytes to write from the source stream at its current position.</span></span></param>
        <param name="callback"><span data-ttu-id="1aa1d-302"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-302">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="1aa1d-303">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-303">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-304">ブロック blob にストリームをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-304">Begins an asynchronous operation to upload a stream to a block blob.</span></span> <span data-ttu-id="1aa1d-305">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-305">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-306"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-306">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUploadFromStream">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromStream (System.IO.Stream source, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromStream(class System.IO.Stream source, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginUploadFromStream(System.IO.Stream,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginUploadFromStream : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginUploadFromStream : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginUploadFromStream (source, accessCondition, options, operationContext, callback, state)" />
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
        <param name="source"><span data-ttu-id="1aa1d-307">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-307">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="1aa1d-308"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-308">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="1aa1d-309">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-309">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-310">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-310">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-311"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-311">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="1aa1d-312"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-312">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="1aa1d-313">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-313">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-314">ブロック blob にストリームをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-314">Begins an asynchronous operation to upload a stream to a block blob.</span></span> <span data-ttu-id="1aa1d-315">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-315">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-316"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-316">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUploadFromStream">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromStream (System.IO.Stream source, long length, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromStream(class System.IO.Stream source, int64 length, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginUploadFromStream(System.IO.Stream,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginUploadFromStream : System.IO.Stream * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginUploadFromStream : System.IO.Stream * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginUploadFromStream (source, length, accessCondition, options, operationContext, callback, state)" />
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
        <param name="source"><span data-ttu-id="1aa1d-317">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-317">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="length"><span data-ttu-id="1aa1d-318">現在の位置に、ソース ストリームから書き込むバイト数。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-318">The number of bytes to write from the source stream at its current position.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="1aa1d-319"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-319">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="1aa1d-320">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-320">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-321">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-321">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-322"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-322">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="1aa1d-323"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-323">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="1aa1d-324">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-324">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-325">ブロック blob にストリームをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-325">Begins an asynchronous operation to upload a stream to a block blob.</span></span> <span data-ttu-id="1aa1d-326">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-326">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-327"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-327">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUploadText">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadText (string content, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadText(string content, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginUploadText(System.String,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginUploadText (content As String, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginUploadText : string * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginUploadText : string * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginUploadText (content, callback, state)" />
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
        <param name="content"><span data-ttu-id="1aa1d-328">アップロードするテキストを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-328">A string containing the text to upload.</span></span></param>
        <param name="callback"><span data-ttu-id="1aa1d-329"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-329">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="1aa1d-330">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-330">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-331">テキストの文字列を blob にアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-331">Begins an asynchronous operation to upload a string of text to a blob.</span></span> <span data-ttu-id="1aa1d-332">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-332">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-333"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-333">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUploadText">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadText (string content, System.Text.Encoding encoding, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadText(string content, class System.Text.Encoding encoding, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginUploadText(System.String,System.Text.Encoding,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginUploadText : string * System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginUploadText : string * System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginUploadText (content, encoding, accessCondition, options, operationContext, callback, state)" />
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
        <param name="content"><span data-ttu-id="1aa1d-334">アップロードするテキストを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-334">A string containing the text to upload.</span></span></param>
        <param name="encoding"><span data-ttu-id="1aa1d-335">A<see cref="T:System.Text.Encoding" />を使用するテキスト エンコーディングを示すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-335">A <see cref="T:System.Text.Encoding" /> object that indicates the text encoding to use.</span></span> <span data-ttu-id="1aa1d-336">場合<c>null</c>utf-8 が使用されます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-336">If <c>null</c>, UTF-8 will be used.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="1aa1d-337"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-337">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-338">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-338">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-339"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-339">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="1aa1d-340"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-340">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="1aa1d-341">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-341">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-342">テキストの文字列を blob にアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-342">Begins an asynchronous operation to upload a string of text to a blob.</span></span> <span data-ttu-id="1aa1d-343">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-343">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-344"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-344">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSnapshot">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob CreateSnapshot (System.Collections.Generic.IDictionary&lt;string,string&gt; metadata = null, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob CreateSnapshot(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; metadata, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.CreateSnapshot(System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member CreateSnapshot : System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob&#xA;override this.CreateSnapshot : System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" Usage="cloudBlockBlob.CreateSnapshot (metadata, accessCondition, options, operationContext)" />
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
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="metadata" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="metadata"><span data-ttu-id="1aa1d-345">スナップショットのメタデータを定義する名前と値のペアのコレクション。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-345">A collection of name-value pairs defining the metadata of the snapshot.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="1aa1d-346"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-346">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="1aa1d-347">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-347">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-348">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> 、要求の追加オプションを指定するオブジェクトまたは<c>null</c>です。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-348">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request, or <c>null</c>.</span></span> <span data-ttu-id="1aa1d-349">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-349">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-350"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-350">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-351">Blob のスナップショットを作成します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-351">Creates a snapshot of the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-352">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> blob のスナップショットであるオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-352">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> object that is a blob snapshot.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSnapshotAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob&gt; CreateSnapshotAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob&gt; CreateSnapshotAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.CreateSnapshotAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function CreateSnapshotAsync () As Task(Of CloudBlockBlob)" />
      <MemberSignature Language="F#" Value="abstract member CreateSnapshotAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob&gt;&#xA;override this.CreateSnapshotAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob&gt;" Usage="cloudBlockBlob.CreateSnapshotAsync " />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1aa1d-353">Blob のスナップショットを作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-353">Initiates an asynchronous operation to create a snapshot of the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-354">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-354">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSnapshotAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob&gt; CreateSnapshotAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob&gt; CreateSnapshotAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.CreateSnapshotAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateSnapshotAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob&gt;&#xA;override this.CreateSnapshotAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob&gt;" Usage="cloudBlockBlob.CreateSnapshotAsync cancellationToken" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="1aa1d-355">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-355">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-356">Blob のスナップショットを作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-356">Initiates an asynchronous operation to create a snapshot of the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-357">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-357">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSnapshotAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob&gt; CreateSnapshotAsync (System.Collections.Generic.IDictionary&lt;string,string&gt; metadata, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob&gt; CreateSnapshotAsync(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; metadata, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.CreateSnapshotAsync(System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member CreateSnapshotAsync : System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob&gt;&#xA;override this.CreateSnapshotAsync : System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob&gt;" Usage="cloudBlockBlob.CreateSnapshotAsync (metadata, accessCondition, options, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="metadata" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="metadata"><span data-ttu-id="1aa1d-358">スナップショットのメタデータを定義する名前と値のペアのコレクション。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-358">A collection of name-value pairs defining the metadata of the snapshot.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="1aa1d-359"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-359">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="1aa1d-360">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-360">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-361">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-361">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-362"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-362">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-363">Blob のスナップショットを作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-363">Initiates an asynchronous operation to create a snapshot of the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-364">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-364">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSnapshotAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob&gt; CreateSnapshotAsync (System.Collections.Generic.IDictionary&lt;string,string&gt; metadata, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob&gt; CreateSnapshotAsync(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; metadata, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.CreateSnapshotAsync(System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateSnapshotAsync : System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob&gt;&#xA;override this.CreateSnapshotAsync : System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob&gt;" Usage="cloudBlockBlob.CreateSnapshotAsync (metadata, accessCondition, options, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="metadata" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="metadata"><span data-ttu-id="1aa1d-365">スナップショットのメタデータを定義する名前と値のペアのコレクション。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-365">A collection of name-value pairs defining the metadata of the snapshot.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="1aa1d-366"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-366">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="1aa1d-367">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-367">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-368">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-368">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-369"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-369">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="1aa1d-370">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-370">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-371">Blob のスナップショットを作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-371">Initiates an asynchronous operation to create a snapshot of the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-372">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-372">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadBlockList">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt; DownloadBlockList (Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter blockListingFilter = Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter.Committed, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt; DownloadBlockList(valuetype Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter blockListingFilter, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.DownloadBlockList(Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DownloadBlockList : Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt;&#xA;override this.DownloadBlockList : Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt;" Usage="cloudBlockBlob.DownloadBlockList (blockListingFilter, accessCondition, options, operationContext)" />
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
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blockListingFilter" Type="Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="blockListingFilter"><span data-ttu-id="1aa1d-373">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter" />コミット後のブロック、コミット前のブロック、またはその両方を返すかどうかを示す列挙値。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-373">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter" /> enumeration value that indicates whether to return committed blocks, uncommitted blocks, or both.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="1aa1d-374"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-374">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="1aa1d-375">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-375">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-376">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-376">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="1aa1d-377">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-377">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-378"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-378">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-379">指定されたブロック一覧フィルターを使用して、blob のブロックの列挙可能なコレクションを返します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-379">Returns an enumerable collection of the blob's blocks, using the specified block list filter.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-380">実装するオブジェクトの列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.Blob.ListBlockItem" />です。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-380">An enumerable collection of objects implementing <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ListBlockItem" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadBlockListAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt;&gt; DownloadBlockListAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt;&gt; DownloadBlockListAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.DownloadBlockListAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function DownloadBlockListAsync () As Task(Of IEnumerable(Of ListBlockItem))" />
      <MemberSignature Language="F#" Value="abstract member DownloadBlockListAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt;&gt;&#xA;override this.DownloadBlockListAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt;&gt;" Usage="cloudBlockBlob.DownloadBlockListAsync " />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1aa1d-381">指定されたブロック一覧フィルターを使用して、blob のブロックの列挙可能なコレクションを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-381">Initiates an asynchronous operation to return an enumerable collection of the blob's blocks, using the specified block list filter.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-382">A<see cref="T:System.Threading.Tasks.Task`1" />型の列挙可能なコレクションであるオブジェクトを<see cref="T:Microsoft.WindowsAzure.Storage.Blob.ListBlockItem" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-382">A <see cref="T:System.Threading.Tasks.Task`1" /> object that is an enumerable collection of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ListBlockItem" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadBlockListAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt;&gt; DownloadBlockListAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt;&gt; DownloadBlockListAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.DownloadBlockListAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DownloadBlockListAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt;&gt;&#xA;override this.DownloadBlockListAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt;&gt;" Usage="cloudBlockBlob.DownloadBlockListAsync cancellationToken" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="1aa1d-383">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-383">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-384">指定されたブロック一覧フィルターを使用して、blob のブロックの列挙可能なコレクションを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-384">Initiates an asynchronous operation to return an enumerable collection of the blob's blocks, using the specified block list filter.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-385">A<see cref="T:System.Threading.Tasks.Task`1" />型の列挙可能なコレクションであるオブジェクトを<see cref="T:Microsoft.WindowsAzure.Storage.Blob.ListBlockItem" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-385">A <see cref="T:System.Threading.Tasks.Task`1" /> object that is an enumerable collection of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ListBlockItem" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadBlockListAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt;&gt; DownloadBlockListAsync (Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter blockListingFilter, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt;&gt; DownloadBlockListAsync(valuetype Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter blockListingFilter, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.DownloadBlockListAsync(Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DownloadBlockListAsync : Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt;&gt;&#xA;override this.DownloadBlockListAsync : Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt;&gt;" Usage="cloudBlockBlob.DownloadBlockListAsync (blockListingFilter, accessCondition, options, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blockListingFilter" Type="Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="blockListingFilter"><span data-ttu-id="1aa1d-386">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter" />コミット後のブロック、コミット前のブロック、またはその両方を返すかどうかを示す列挙値。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-386">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter" /> enumeration value that indicates whether to return committed blocks, uncommitted blocks, or both.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="1aa1d-387"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-387">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="1aa1d-388">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-388">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-389">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-389">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-390"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-390">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-391">指定されたブロック一覧フィルターを使用して、blob のブロックの列挙可能なコレクションを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-391">Initiates an asynchronous operation to return an enumerable collection of the blob's blocks, using the specified block list filter.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-392">A<see cref="T:System.Threading.Tasks.Task`1" />型の列挙可能なコレクションであるオブジェクトを<see cref="T:Microsoft.WindowsAzure.Storage.Blob.ListBlockItem" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-392">A <see cref="T:System.Threading.Tasks.Task`1" /> object that is an enumerable collection of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ListBlockItem" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadBlockListAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt;&gt; DownloadBlockListAsync (Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter blockListingFilter, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt;&gt; DownloadBlockListAsync(valuetype Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter blockListingFilter, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.DownloadBlockListAsync(Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DownloadBlockListAsync : Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt;&gt;&#xA;override this.DownloadBlockListAsync : Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt;&gt;" Usage="cloudBlockBlob.DownloadBlockListAsync (blockListingFilter, accessCondition, options, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blockListingFilter" Type="Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="blockListingFilter"><span data-ttu-id="1aa1d-393">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter" />コミット後のブロック、コミット前のブロック、またはその両方を返すかどうかを示す列挙値。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-393">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter" /> enumeration value that indicates whether to return committed blocks, uncommitted blocks, or both.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="1aa1d-394"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-394">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="1aa1d-395">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-395">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-396">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-396">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-397"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-397">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="1aa1d-398">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-398">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-399">指定されたブロック一覧フィルターを使用して、blob のブロックの列挙可能なコレクションを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-399">Initiates an asynchronous operation to return an enumerable collection of the blob's blocks, using the specified block list filter.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-400">A<see cref="T:System.Threading.Tasks.Task`1" />型の列挙可能なコレクションであるオブジェクトを<see cref="T:Microsoft.WindowsAzure.Storage.Blob.ListBlockItem" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-400">A <see cref="T:System.Threading.Tasks.Task`1" /> object that is an enumerable collection of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ListBlockItem" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadText">
      <MemberSignature Language="C#" Value="public virtual string DownloadText (System.Text.Encoding encoding = null, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string DownloadText(class System.Text.Encoding encoding, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.DownloadText(System.Text.Encoding,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DownloadText : System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; string&#xA;override this.DownloadText : System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; string" Usage="cloudBlockBlob.DownloadText (encoding, accessCondition, options, operationContext)" />
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
        <param name="encoding"><span data-ttu-id="1aa1d-401">使用するテキスト エンコーディングを示すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-401">An object that indicates the text encoding to use.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="1aa1d-402"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-402">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-403">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-403">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="1aa1d-404">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-404">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-405"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-405">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-406">Blob の内容を文字列としてダウンロードします。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-406">Downloads the blob's contents as a string.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-407">文字列として、blob の内容。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-407">The contents of the blob, as a string.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadTextAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; DownloadTextAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; DownloadTextAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.DownloadTextAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function DownloadTextAsync () As Task(Of String)" />
      <MemberSignature Language="F#" Value="abstract member DownloadTextAsync : unit -&gt; System.Threading.Tasks.Task&lt;string&gt;&#xA;override this.DownloadTextAsync : unit -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudBlockBlob.DownloadTextAsync " />
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
            <span data-ttu-id="1aa1d-408">Blob の内容を文字列としてダウンロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-408">Initiates an asynchronous operation to download the blob's contents as a string.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-409">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>文字列</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-409">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>string</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadTextAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; DownloadTextAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; DownloadTextAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.DownloadTextAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DownloadTextAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;&#xA;override this.DownloadTextAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudBlockBlob.DownloadTextAsync cancellationToken" />
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
        <param name="cancellationToken"><span data-ttu-id="1aa1d-410">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-410">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-411">Blob の内容を文字列としてダウンロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-411">Initiates an asynchronous operation to download the blob's contents as a string.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-412">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>文字列</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-412">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>string</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadTextAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; DownloadTextAsync (System.Text.Encoding encoding, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; DownloadTextAsync(class System.Text.Encoding encoding, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.DownloadTextAsync(System.Text.Encoding,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DownloadTextAsync : System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;string&gt;&#xA;override this.DownloadTextAsync : System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudBlockBlob.DownloadTextAsync (encoding, accessCondition, options, operationContext)" />
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
        <param name="encoding"><span data-ttu-id="1aa1d-413">使用するテキスト エンコーディングを示すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-413">An object that indicates the text encoding to use.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="1aa1d-414"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-414">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-415">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-415">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-416"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-416">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-417">Blob の内容を文字列としてダウンロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-417">Initiates an asynchronous operation to download the blob's contents as a string.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-418">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>文字列</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-418">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>string</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadTextAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; DownloadTextAsync (System.Text.Encoding encoding, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; DownloadTextAsync(class System.Text.Encoding encoding, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.DownloadTextAsync(System.Text.Encoding,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DownloadTextAsync : System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;&#xA;override this.DownloadTextAsync : System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudBlockBlob.DownloadTextAsync (encoding, accessCondition, options, operationContext, cancellationToken)" />
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
        <param name="encoding"><span data-ttu-id="1aa1d-419">使用するテキスト エンコーディングを示すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-419">An object that indicates the text encoding to use.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="1aa1d-420"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-420">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-421">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-421">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-422"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-422">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="1aa1d-423">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-423">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-424">Blob の内容を文字列としてダウンロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-424">Initiates an asynchronous operation to download the blob's contents as a string.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-425">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>文字列</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-425">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>string</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadTextAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; DownloadTextAsync (System.Text.Encoding encoding, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; DownloadTextAsync(class System.Text.Encoding encoding, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.IProgress`1&lt;class Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.DownloadTextAsync(System.Text.Encoding,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.IProgress{Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DownloadTextAsync : System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;&#xA;override this.DownloadTextAsync : System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudBlockBlob.DownloadTextAsync (encoding, accessCondition, options, operationContext, progressHandler, cancellationToken)" />
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
        <param name="encoding"><span data-ttu-id="1aa1d-426">使用するテキスト エンコーディングを示すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-426">An object that indicates the text encoding to use.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="1aa1d-427"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-427">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-428">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-428">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-429"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-429">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="progressHandler"> <span data-ttu-id="1aa1d-430">A<see cref="T:System.IProgress`1" />を処理するオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" />メッセージ。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-430">A <see cref="T:System.IProgress`1" /> object to handle <see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" /> messages.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="1aa1d-431">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-431">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-432">Blob の内容を文字列としてダウンロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-432">Initiates an asynchronous operation to download the blob's contents as a string.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-433">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>文字列</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-433">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>string</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndCreateSnapshot">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob EndCreateSnapshot (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob EndCreateSnapshot(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.EndCreateSnapshot(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndCreateSnapshot (asyncResult As IAsyncResult) As CloudBlockBlob" />
      <MemberSignature Language="F#" Value="abstract member EndCreateSnapshot : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob&#xA;override this.EndCreateSnapshot : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" Usage="cloudBlockBlob.EndCreateSnapshot asyncResult" />
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
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="1aa1d-434"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-434">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-435">Blob のスナップショットを作成する非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-435">Ends an asynchronous operation to create a snapshot of the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-436">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> blob のスナップショットであるオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-436">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> object that is a blob snapshot.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndDownloadBlockList">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt; EndDownloadBlockList (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt; EndDownloadBlockList(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.EndDownloadBlockList(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndDownloadBlockList (asyncResult As IAsyncResult) As IEnumerable(Of ListBlockItem)" />
      <MemberSignature Language="F#" Value="abstract member EndDownloadBlockList : IAsyncResult -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt;&#xA;override this.EndDownloadBlockList : IAsyncResult -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt;" Usage="cloudBlockBlob.EndDownloadBlockList asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="1aa1d-437"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-437">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-438">指定されたブロック一覧フィルターを使用して、blob のブロックの列挙可能なコレクションを返す非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-438">Ends an asynchronous operation to return an enumerable collection of the blob's blocks, using the specified block list filter.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-439">実装するオブジェクトの列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.Blob.ListBlockItem" />です。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-439">An enumerable collection of objects implementing <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ListBlockItem" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndDownloadText">
      <MemberSignature Language="C#" Value="public virtual string EndDownloadText (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string EndDownloadText(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.EndDownloadText(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndDownloadText (asyncResult As IAsyncResult) As String" />
      <MemberSignature Language="F#" Value="abstract member EndDownloadText : IAsyncResult -&gt; string&#xA;override this.EndDownloadText : IAsyncResult -&gt; string" Usage="cloudBlockBlob.EndDownloadText asyncResult" />
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
        <param name="asyncResult"><span data-ttu-id="1aa1d-440"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-440">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-441">Blob の内容を文字列としてダウンロードする非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-441">Ends an asynchronous operation to download the blob's contents as a string.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-442">文字列として、blob の内容。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-442">The contents of the blob, as a string.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndOpenWrite">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream EndOpenWrite (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream EndOpenWrite(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.EndOpenWrite(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndOpenWrite (asyncResult As IAsyncResult) As CloudBlobStream" />
      <MemberSignature Language="F#" Value="abstract member EndOpenWrite : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&#xA;override this.EndOpenWrite : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" Usage="cloudBlockBlob.EndOpenWrite asyncResult" />
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
        <param name="asyncResult"><span data-ttu-id="1aa1d-443"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-443">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-444">Blob に書き込むためのストリームを開く非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-444">Ends an asynchronous operation to open a stream for writing to the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-445">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" /> blob への書き込みに使用します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-445">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" /> to be used for writing to the blob.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndPutBlock">
      <MemberSignature Language="C#" Value="public virtual void EndPutBlock (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndPutBlock(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.EndPutBlock(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndPutBlock (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndPutBlock : IAsyncResult -&gt; unit&#xA;override this.EndPutBlock : IAsyncResult -&gt; unit" Usage="cloudBlockBlob.EndPutBlock asyncResult" />
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
        <param name="asyncResult"><span data-ttu-id="1aa1d-446"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-446">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-447">1 つのブロックをアップロードする非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-447">Ends an asynchronous operation to upload a single block.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndPutBlockList">
      <MemberSignature Language="C#" Value="public virtual void EndPutBlockList (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndPutBlockList(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.EndPutBlockList(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndPutBlockList (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndPutBlockList : IAsyncResult -&gt; unit&#xA;override this.EndPutBlockList : IAsyncResult -&gt; unit" Usage="cloudBlockBlob.EndPutBlockList asyncResult" />
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
        <param name="asyncResult"><span data-ttu-id="1aa1d-448"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-448">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-449">新規または既存の blob にブロックの一覧をアップロードする非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-449">Ends an asynchronous operation to upload a list of blocks to a new or existing blob.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndSetStandardBlobTier">
      <MemberSignature Language="C#" Value="public virtual void EndSetStandardBlobTier (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndSetStandardBlobTier(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.EndSetStandardBlobTier(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndSetStandardBlobTier (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndSetStandardBlobTier : IAsyncResult -&gt; unit&#xA;override this.EndSetStandardBlobTier : IAsyncResult -&gt; unit" Usage="cloudBlockBlob.EndSetStandardBlobTier asyncResult" />
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
        <param name="asyncResult"><span data-ttu-id="1aa1d-450"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-450">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-451">標準的なストレージ アカウントの blob の層を設定する非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-451">Ends an asynchronous operation to set the tier of the blob on a standard storage account.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndUploadFromByteArray">
      <MemberSignature Language="C#" Value="public virtual void EndUploadFromByteArray (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndUploadFromByteArray(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.EndUploadFromByteArray(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndUploadFromByteArray (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndUploadFromByteArray : IAsyncResult -&gt; unit&#xA;override this.EndUploadFromByteArray : IAsyncResult -&gt; unit" Usage="cloudBlockBlob.EndUploadFromByteArray asyncResult" />
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
        <param name="asyncResult"><span data-ttu-id="1aa1d-452"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-452">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-453">バイト配列の内容を blob にアップロードする非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-453">Ends an asynchronous operation to upload the contents of a byte array to a blob.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndUploadFromFile">
      <MemberSignature Language="C#" Value="public virtual void EndUploadFromFile (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndUploadFromFile(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.EndUploadFromFile(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndUploadFromFile (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndUploadFromFile : IAsyncResult -&gt; unit&#xA;override this.EndUploadFromFile : IAsyncResult -&gt; unit" Usage="cloudBlockBlob.EndUploadFromFile asyncResult" />
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
        <param name="asyncResult"><span data-ttu-id="1aa1d-454"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-454">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-455">Blob にファイルをアップロードする非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-455">Ends an asynchronous operation to upload a file to a blob.</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndUploadFromStream">
      <MemberSignature Language="C#" Value="public virtual void EndUploadFromStream (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndUploadFromStream(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.EndUploadFromStream(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndUploadFromStream (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndUploadFromStream : IAsyncResult -&gt; unit&#xA;override this.EndUploadFromStream : IAsyncResult -&gt; unit" Usage="cloudBlockBlob.EndUploadFromStream asyncResult" />
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
        <param name="asyncResult"><span data-ttu-id="1aa1d-456"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-456">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-457">ブロック blob にストリームをアップロードする非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-457">Ends an asynchronous operation to upload a stream to a block blob.</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndUploadText">
      <MemberSignature Language="C#" Value="public virtual void EndUploadText (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndUploadText(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.EndUploadText(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndUploadText (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndUploadText : IAsyncResult -&gt; unit&#xA;override this.EndUploadText : IAsyncResult -&gt; unit" Usage="cloudBlockBlob.EndUploadText asyncResult" />
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
        <param name="asyncResult"><span data-ttu-id="1aa1d-458"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-458">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-459">テキストの文字列を blob にアップロードする非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-459">Ends an asynchronous operation to upload a string of text to a blob.</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenWrite">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream OpenWrite (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream OpenWrite(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.OpenWrite(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member OpenWrite : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&#xA;override this.OpenWrite : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" Usage="cloudBlockBlob.OpenWrite (accessCondition, options, operationContext)" />
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
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><span data-ttu-id="1aa1d-460"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-460">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="1aa1d-461">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-461">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-462">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-462">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="1aa1d-463">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-463">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-464"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-464">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-465">Blob に書き込むためのストリームを開きます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-465">Opens a stream for writing to the blob.</span></span> <span data-ttu-id="1aa1d-466">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-466">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-467">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" /> blob への書き込みに使用します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-467">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" /> to be used for writing to the blob.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="1aa1d-468">このメソッドへの呼び出しを常に、注意してください、<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributes(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />内部的メソッドです。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-468">Note that this method always makes a call to the <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributes(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" /> method under the covers.</span></span></para>
          <para><span data-ttu-id="1aa1d-469">設定、 <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.StreamWriteSizeInBytes" /> mb 16 KB ~ 100 MB までの範囲のバイトの書き込みは、ブロック サイズを指定するには、このメソッドを呼び出す前に、プロパティです。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-469">Set the <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.StreamWriteSizeInBytes" /> property before calling this method to specify the block size to write, in bytes, ranging from between 16 KB and 100 MB inclusive.</span></span></para>
          <para><span data-ttu-id="1aa1d-470">これを上書きする代わりに blob が存在する場合は、例外をスロー、渡す、<see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />オブジェクトを使用して生成<see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />です。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-470">To throw an exception if the blob exists instead of overwriting it, pass in an <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object generated using <see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenWriteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt; OpenWriteAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt; OpenWriteAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.OpenWriteAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function OpenWriteAsync () As Task(Of CloudBlobStream)" />
      <MemberSignature Language="F#" Value="abstract member OpenWriteAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt;&#xA;override this.OpenWriteAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt;" Usage="cloudBlockBlob.OpenWriteAsync " />
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
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1aa1d-471">Blob に書き込むためのストリームを開く非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-471">Initiates an asynchronous operation to open a stream for writing to the blob.</span></span> <span data-ttu-id="1aa1d-472">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-472">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-473">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-473">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="1aa1d-474">このメソッドへの呼び出しを常に、注意してください、<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributesAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />内部的メソッドです。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-474">Note that this method always makes a call to the <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributesAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" /> method under the covers.</span></span></para>
          <para><span data-ttu-id="1aa1d-475">設定、 <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.StreamWriteSizeInBytes" /> mb 16 KB ~ 100 MB までの範囲のバイトの書き込みは、ブロック サイズを指定するには、このメソッドを呼び出す前に、プロパティです。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-475">Set the <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.StreamWriteSizeInBytes" /> property before calling this method to specify the block size to write, in bytes, ranging from between 16 KB and 100 MB inclusive.</span></span></para>
          <para><span data-ttu-id="1aa1d-476">例外をスローする、上書きすることではなく、blob が存在する場合は、次を参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.OpenWriteAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />です。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-476">To throw an exception if the blob exists instead of overwriting it, see <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.OpenWriteAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenWriteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt; OpenWriteAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt; OpenWriteAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.OpenWriteAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OpenWriteAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt;&#xA;override this.OpenWriteAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt;" Usage="cloudBlockBlob.OpenWriteAsync cancellationToken" />
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
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="1aa1d-477">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-477">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-478">Blob に書き込むためのストリームを開く非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-478">Initiates an asynchronous operation to open a stream for writing to the blob.</span></span> <span data-ttu-id="1aa1d-479">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-479">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-480">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-480">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="1aa1d-481">このメソッドへの呼び出しを常に、注意してください、<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributesAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />内部的メソッドです。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-481">Note that this method always makes a call to the <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributesAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" /> method under the covers.</span></span></para>
          <para><span data-ttu-id="1aa1d-482">設定、 <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.StreamWriteSizeInBytes" /> mb 16 KB ~ 100 MB までの範囲のバイトの書き込みは、ブロック サイズを指定するには、このメソッドを呼び出す前に、プロパティです。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-482">Set the <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.StreamWriteSizeInBytes" /> property before calling this method to specify the block size to write, in bytes, ranging from between 16 KB and 100 MB inclusive.</span></span></para>
          <para><span data-ttu-id="1aa1d-483">例外をスローする、上書きすることではなく、blob が存在する場合は、次を参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.OpenWriteAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-483">To throw an exception if the blob exists instead of overwriting it, see <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.OpenWriteAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenWriteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt; OpenWriteAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt; OpenWriteAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.OpenWriteAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member OpenWriteAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt;&#xA;override this.OpenWriteAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt;" Usage="cloudBlockBlob.OpenWriteAsync (accessCondition, options, operationContext)" />
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
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><span data-ttu-id="1aa1d-484"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-484">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="1aa1d-485">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-485">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-486">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-486">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-487"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-487">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-488">Blob に書き込むためのストリームを開く非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-488">Initiates an asynchronous operation to open a stream for writing to the blob.</span></span> <span data-ttu-id="1aa1d-489">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-489">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-490">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-490">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="1aa1d-491">このメソッドへの呼び出しを常に、注意してください、<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributesAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />内部的メソッドです。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-491">Note that this method always makes a call to the <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributesAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" /> method under the covers.</span></span></para>
          <para><span data-ttu-id="1aa1d-492">設定、 <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.StreamWriteSizeInBytes" /> mb 16 KB ~ 100 MB までの範囲のバイトの書き込みは、ブロック サイズを指定するには、このメソッドを呼び出す前に、プロパティです。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-492">Set the <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.StreamWriteSizeInBytes" /> property before calling this method to specify the block size to write, in bytes, ranging from between 16 KB and 100 MB inclusive.</span></span></para>
          <para><span data-ttu-id="1aa1d-493">これを上書きする代わりに blob が存在する場合は、例外をスロー、渡す、<see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />オブジェクトを使用して生成<see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />です。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-493">To throw an exception if the blob exists instead of overwriting it, pass in an <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object generated using <see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenWriteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt; OpenWriteAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt; OpenWriteAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.OpenWriteAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OpenWriteAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt;&#xA;override this.OpenWriteAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt;" Usage="cloudBlockBlob.OpenWriteAsync (accessCondition, options, operationContext, cancellationToken)" />
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
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><span data-ttu-id="1aa1d-494"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-494">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="1aa1d-495">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-495">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-496">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-496">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-497"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-497">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="1aa1d-498">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-498">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-499">Blob に書き込むためのストリームを開く非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-499">Initiates an asynchronous operation to open a stream for writing to the blob.</span></span> <span data-ttu-id="1aa1d-500">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-500">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-501">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-501">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="1aa1d-502">このメソッドへの呼び出しを常に、注意してください、<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributesAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />内部的メソッドです。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-502">Note that this method always makes a call to the <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributesAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" /> method under the covers.</span></span></para>
          <para><span data-ttu-id="1aa1d-503">設定、 <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.StreamWriteSizeInBytes" /> mb 16 KB ~ 100 MB までの範囲のバイトの書き込みは、ブロック サイズを指定するには、このメソッドを呼び出す前に、プロパティです。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-503">Set the <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.StreamWriteSizeInBytes" /> property before calling this method to specify the block size to write, in bytes, ranging from between 16 KB and 100 MB inclusive.</span></span></para>
          <para><span data-ttu-id="1aa1d-504">これを上書きする代わりに blob が存在する場合は、例外をスロー、渡す、<see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />オブジェクトを使用して生成<see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />です。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-504">To throw an exception if the blob exists instead of overwriting it, pass in an <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object generated using <see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="PutBlock">
      <MemberSignature Language="C#" Value="public virtual void PutBlock (string blockId, System.IO.Stream blockData, string contentMD5, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void PutBlock(string blockId, class System.IO.Stream blockData, string contentMD5, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.PutBlock(System.String,System.IO.Stream,System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member PutBlock : string * System.IO.Stream * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.PutBlock : string * System.IO.Stream * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudBlockBlob.PutBlock (blockId, blockData, contentMD5, accessCondition, options, operationContext)" />
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
        <Parameter Name="blockId" Type="System.String" />
        <Parameter Name="blockData" Type="System.IO.Stream" />
        <Parameter Name="contentMD5" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="blockId"><span data-ttu-id="1aa1d-505">ブロックを識別する Base64 でエンコードされた文字列。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-505">A Base64-encoded string that identifies the block.</span></span></param>
        <param name="blockData"><span data-ttu-id="1aa1d-506">A<see cref="T:System.IO.Stream" />ブロックのデータを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-506">A <see cref="T:System.IO.Stream" /> object that provides the data for the block.</span></span></param>
        <param name="contentMD5"><span data-ttu-id="1aa1d-507">ブロックのトランザクションの整合性を確保するために使用する省略可能なハッシュ値です。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-507">An optional hash value used to ensure transactional integrity for the block.</span></span> <span data-ttu-id="1aa1d-508">あります<c>null</c>または空の文字列。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-508">May be <c>null</c> or an empty string.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="1aa1d-509"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-509">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="1aa1d-510">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-510">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-511">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-511">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="1aa1d-512">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-512">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-513"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-513">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-514">1 つのブロックをアップロードします。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-514">Uploads a single block.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="1aa1d-515">クライアントは、ネットワーク上でトランザクションの整合性を確保するための手段として特定のブロックの配置操作に関して content-md5 ヘッダーを送信することがあります。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-515">Clients may send the Content-MD5 header for a given Put Block operation as a means to ensure transactional integrity over the wire.</span></span> <span data-ttu-id="1aa1d-516"><paramref name="contentMD5" />パラメーターにより、クライアントは、指定したバイトの範囲に提供することを事前に計算された MD5 値へのアクセスを既に持っています。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-516">The <paramref name="contentMD5" /> parameter permits clients who already have access to a pre-computed MD5 value for a given byte range to provide it.</span></span>
            <span data-ttu-id="1aa1d-517">場合、<see cref="P:BlobRequestOptions.UseTransactionalMd5" />プロパティに設定されている<c>true</c>と<paramref name="contentMD5" />にパラメーターが設定されている<c>null</c>、クライアント ライブラリが MD5 値を内部で計算し、します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-517">If the <see cref="P:BlobRequestOptions.UseTransactionalMd5" /> property is set to <c>true</c> and the <paramref name="contentMD5" /> parameter is set to <c>null</c>, then the client library will calculate the MD5 value internally.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PutBlockAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task PutBlockAsync (string blockId, System.IO.Stream blockData, string contentMD5);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task PutBlockAsync(string blockId, class System.IO.Stream blockData, string contentMD5) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.PutBlockAsync(System.String,System.IO.Stream,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function PutBlockAsync (blockId As String, blockData As Stream, contentMD5 As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member PutBlockAsync : string * System.IO.Stream * string -&gt; System.Threading.Tasks.Task&#xA;override this.PutBlockAsync : string * System.IO.Stream * string -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.PutBlockAsync (blockId, blockData, contentMD5)" />
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
        <Parameter Name="blockId" Type="System.String" />
        <Parameter Name="blockData" Type="System.IO.Stream" />
        <Parameter Name="contentMD5" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="blockId"><span data-ttu-id="1aa1d-518">ブロックを識別する Base64 でエンコードされた文字列。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-518">A Base64-encoded string that identifies the block.</span></span></param>
        <param name="blockData"><span data-ttu-id="1aa1d-519">A<see cref="T:System.IO.Stream" />ブロックのデータを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-519">A <see cref="T:System.IO.Stream" /> object that provides the data for the block.</span></span></param>
        <param name="contentMD5"><span data-ttu-id="1aa1d-520">ブロックのトランザクションの整合性を確保するために使用する省略可能なハッシュ値です。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-520">An optional hash value used to ensure transactional integrity for the block.</span></span> <span data-ttu-id="1aa1d-521">あります<c>null</c>または空の文字列。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-521">May be <c>null</c> or an empty string.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-522">1 つのブロックをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-522">Initiates an asynchronous operation to upload a single block.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-523">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-523">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="1aa1d-524">クライアントは、ネットワーク上でトランザクションの整合性を確保するための手段として特定のブロックの配置操作に関して content-md5 ヘッダーを送信することがあります。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-524">Clients may send the Content-MD5 header for a given Put Block operation as a means to ensure transactional integrity over the wire.</span></span> <span data-ttu-id="1aa1d-525"><paramref name="contentMD5" />パラメーターにより、クライアントは、指定したバイトの範囲に提供することを事前に計算された MD5 値へのアクセスを既に持っています。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-525">The <paramref name="contentMD5" /> parameter permits clients who already have access to a pre-computed MD5 value for a given byte range to provide it.</span></span>
            <span data-ttu-id="1aa1d-526">場合、<see cref="P:BlobRequestOptions.UseTransactionalMd5" />プロパティに設定されている<c>true</c>と<paramref name="contentMD5" />にパラメーターが設定されている<c>null</c>、クライアント ライブラリが MD5 値を内部で計算し、します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-526">If the <see cref="P:BlobRequestOptions.UseTransactionalMd5" /> property is set to <c>true</c> and the <paramref name="contentMD5" /> parameter is set to <c>null</c>, then the client library will calculate the MD5 value internally.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PutBlockAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task PutBlockAsync (string blockId, System.IO.Stream blockData, string contentMD5, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task PutBlockAsync(string blockId, class System.IO.Stream blockData, string contentMD5, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.PutBlockAsync(System.String,System.IO.Stream,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PutBlockAsync : string * System.IO.Stream * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.PutBlockAsync : string * System.IO.Stream * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.PutBlockAsync (blockId, blockData, contentMD5, cancellationToken)" />
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
        <Parameter Name="blockId" Type="System.String" />
        <Parameter Name="blockData" Type="System.IO.Stream" />
        <Parameter Name="contentMD5" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="blockId"><span data-ttu-id="1aa1d-527">ブロックを識別する Base64 でエンコードされた文字列。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-527">A Base64-encoded string that identifies the block.</span></span></param>
        <param name="blockData"><span data-ttu-id="1aa1d-528">A<see cref="T:System.IO.Stream" />ブロックのデータを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-528">A <see cref="T:System.IO.Stream" /> object that provides the data for the block.</span></span></param>
        <param name="contentMD5"><span data-ttu-id="1aa1d-529">ブロックのトランザクションの整合性を確保するために使用する省略可能なハッシュ値です。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-529">An optional hash value used to ensure transactional integrity for the block.</span></span> <span data-ttu-id="1aa1d-530">あります<c>null</c>または空の文字列。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-530">May be <c>null</c> or an empty string.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="1aa1d-531">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-531">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-532">1 つのブロックをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-532">Initiates an asynchronous operation to upload a single block.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-533">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-533">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="1aa1d-534">クライアントは、ネットワーク上でトランザクションの整合性を確保するための手段として特定のブロックの配置操作に関して content-md5 ヘッダーを送信することがあります。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-534">Clients may send the Content-MD5 header for a given Put Block operation as a means to ensure transactional integrity over the wire.</span></span> <span data-ttu-id="1aa1d-535"><paramref name="contentMD5" />パラメーターにより、クライアントは、指定したバイトの範囲に提供することを事前に計算された MD5 値へのアクセスを既に持っています。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-535">The <paramref name="contentMD5" /> parameter permits clients who already have access to a pre-computed MD5 value for a given byte range to provide it.</span></span>
            <span data-ttu-id="1aa1d-536">場合、<see cref="P:BlobRequestOptions.UseTransactionalMd5" />プロパティに設定されている<c>true</c>と<paramref name="contentMD5" />にパラメーターが設定されている<c>null</c>、クライアント ライブラリが MD5 値を内部で計算し、します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-536">If the <see cref="P:BlobRequestOptions.UseTransactionalMd5" /> property is set to <c>true</c> and the <paramref name="contentMD5" /> parameter is set to <c>null</c>, then the client library will calculate the MD5 value internally.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PutBlockAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task PutBlockAsync (string blockId, System.IO.Stream blockData, string contentMD5, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task PutBlockAsync(string blockId, class System.IO.Stream blockData, string contentMD5, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.PutBlockAsync(System.String,System.IO.Stream,System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member PutBlockAsync : string * System.IO.Stream * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.PutBlockAsync : string * System.IO.Stream * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.PutBlockAsync (blockId, blockData, contentMD5, accessCondition, options, operationContext)" />
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
        <Parameter Name="blockId" Type="System.String" />
        <Parameter Name="blockData" Type="System.IO.Stream" />
        <Parameter Name="contentMD5" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="blockId"><span data-ttu-id="1aa1d-537">ブロックを識別する Base64 でエンコードされた文字列。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-537">A Base64-encoded string that identifies the block.</span></span></param>
        <param name="blockData"><span data-ttu-id="1aa1d-538">A<see cref="T:System.IO.Stream" />ブロックのデータを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-538">A <see cref="T:System.IO.Stream" /> object that provides the data for the block.</span></span></param>
        <param name="contentMD5"><span data-ttu-id="1aa1d-539">ブロックのトランザクションの整合性を確保するために使用する省略可能なハッシュ値です。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-539">An optional hash value used to ensure transactional integrity for the block.</span></span> <span data-ttu-id="1aa1d-540">あります<c>null</c>または空の文字列。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-540">May be <c>null</c> or an empty string.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="1aa1d-541"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-541">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="1aa1d-542">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-542">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-543">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-543">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-544"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-544">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-545">1 つのブロックをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-545">Initiates an asynchronous operation to upload a single block.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-546">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-546">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="1aa1d-547">クライアントは、ネットワーク上でトランザクションの整合性を確保するための手段として特定のブロックの配置操作に関して content-md5 ヘッダーを送信することがあります。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-547">Clients may send the Content-MD5 header for a given Put Block operation as a means to ensure transactional integrity over the wire.</span></span> <span data-ttu-id="1aa1d-548"><paramref name="contentMD5" />パラメーターにより、クライアントは、指定したバイトの範囲に提供することを事前に計算された MD5 値へのアクセスを既に持っています。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-548">The <paramref name="contentMD5" /> parameter permits clients who already have access to a pre-computed MD5 value for a given byte range to provide it.</span></span>
            <span data-ttu-id="1aa1d-549">場合、<see cref="P:BlobRequestOptions.UseTransactionalMd5" />プロパティに設定されている<c>true</c>と<paramref name="contentMD5" />にパラメーターが設定されている<c>null</c>、クライアント ライブラリが MD5 値を内部で計算し、します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-549">If the <see cref="P:BlobRequestOptions.UseTransactionalMd5" /> property is set to <c>true</c> and the <paramref name="contentMD5" /> parameter is set to <c>null</c>, then the client library will calculate the MD5 value internally.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PutBlockAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task PutBlockAsync (string blockId, System.IO.Stream blockData, string contentMD5, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task PutBlockAsync(string blockId, class System.IO.Stream blockData, string contentMD5, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.PutBlockAsync(System.String,System.IO.Stream,System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PutBlockAsync : string * System.IO.Stream * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.PutBlockAsync : string * System.IO.Stream * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.PutBlockAsync (blockId, blockData, contentMD5, accessCondition, options, operationContext, cancellationToken)" />
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
        <Parameter Name="blockId" Type="System.String" />
        <Parameter Name="blockData" Type="System.IO.Stream" />
        <Parameter Name="contentMD5" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="blockId"><span data-ttu-id="1aa1d-550">ブロックを識別する Base64 でエンコードされた文字列。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-550">A Base64-encoded string that identifies the block.</span></span></param>
        <param name="blockData"><span data-ttu-id="1aa1d-551">A<see cref="T:System.IO.Stream" />ブロックのデータを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-551">A <see cref="T:System.IO.Stream" /> object that provides the data for the block.</span></span></param>
        <param name="contentMD5"><span data-ttu-id="1aa1d-552">ブロックのトランザクションの整合性を確保するために使用する省略可能なハッシュ値です。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-552">An optional hash value used to ensure transactional integrity for the block.</span></span> <span data-ttu-id="1aa1d-553">あります<c>null</c>または空の文字列。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-553">May be <c>null</c> or an empty string.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="1aa1d-554"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-554">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="1aa1d-555">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-555">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-556">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-556">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-557"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-557">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="1aa1d-558">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-558">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-559">1 つのブロックをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-559">Initiates an asynchronous operation to upload a single block.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-560">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-560">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="1aa1d-561">クライアントは、ネットワーク上でトランザクションの整合性を確保するための手段として特定のブロックの配置操作に関して content-md5 ヘッダーを送信することがあります。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-561">Clients may send the Content-MD5 header for a given Put Block operation as a means to ensure transactional integrity over the wire.</span></span> <span data-ttu-id="1aa1d-562"><paramref name="contentMD5" />パラメーターにより、クライアントは、指定したバイトの範囲に提供することを事前に計算された MD5 値へのアクセスを既に持っています。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-562">The <paramref name="contentMD5" /> parameter permits clients who already have access to a pre-computed MD5 value for a given byte range to provide it.</span></span>
            <span data-ttu-id="1aa1d-563">場合、<see cref="P:BlobRequestOptions.UseTransactionalMd5" />プロパティに設定されている<c>true</c>と<paramref name="contentMD5" />にパラメーターが設定されている<c>null</c>、クライアント ライブラリが MD5 値を内部で計算し、します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-563">If the <see cref="P:BlobRequestOptions.UseTransactionalMd5" /> property is set to <c>true</c> and the <paramref name="contentMD5" /> parameter is set to <c>null</c>, then the client library will calculate the MD5 value internally.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PutBlockAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task PutBlockAsync (string blockId, System.IO.Stream blockData, string contentMD5, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task PutBlockAsync(string blockId, class System.IO.Stream blockData, string contentMD5, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.IProgress`1&lt;class Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.PutBlockAsync(System.String,System.IO.Stream,System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.IProgress{Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PutBlockAsync : string * System.IO.Stream * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.PutBlockAsync : string * System.IO.Stream * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.PutBlockAsync (blockId, blockData, contentMD5, accessCondition, options, operationContext, progressHandler, cancellationToken)" />
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
        <Parameter Name="blockId" Type="System.String" />
        <Parameter Name="blockData" Type="System.IO.Stream" />
        <Parameter Name="contentMD5" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="progressHandler" Type="System.IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="blockId"><span data-ttu-id="1aa1d-564">ブロックを識別する Base64 でエンコードされた文字列。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-564">A Base64-encoded string that identifies the block.</span></span></param>
        <param name="blockData"><span data-ttu-id="1aa1d-565">A<see cref="T:System.IO.Stream" />ブロックのデータを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-565">A <see cref="T:System.IO.Stream" /> object that provides the data for the block.</span></span></param>
        <param name="contentMD5"><span data-ttu-id="1aa1d-566">ブロックのトランザクションの整合性を確保するために使用する省略可能なハッシュ値です。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-566">An optional hash value used to ensure transactional integrity for the block.</span></span> <span data-ttu-id="1aa1d-567">あります<c>null</c>または空の文字列。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-567">May be <c>null</c> or an empty string.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="1aa1d-568"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-568">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="1aa1d-569">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-569">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-570">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-570">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-571"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-571">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="progressHandler"> <span data-ttu-id="1aa1d-572">A<see cref="T:System.IProgress`1" />を処理するオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" />メッセージ。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-572">A <see cref="T:System.IProgress`1" /> object to handle <see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" /> messages.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="1aa1d-573">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-573">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-574">1 つのブロックをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-574">Initiates an asynchronous operation to upload a single block.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-575">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-575">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="1aa1d-576">クライアントは、ネットワーク上でトランザクションの整合性を確保するための手段として特定のブロックの配置操作に関して content-md5 ヘッダーを送信することがあります。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-576">Clients may send the Content-MD5 header for a given Put Block operation as a means to ensure transactional integrity over the wire.</span></span> <span data-ttu-id="1aa1d-577"><paramref name="contentMD5" />パラメーターにより、クライアントは、指定したバイトの範囲に提供することを事前に計算された MD5 値へのアクセスを既に持っています。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-577">The <paramref name="contentMD5" /> parameter permits clients who already have access to a pre-computed MD5 value for a given byte range to provide it.</span></span>
            <span data-ttu-id="1aa1d-578">場合、<see cref="P:BlobRequestOptions.UseTransactionalMd5" />プロパティに設定されている<c>true</c>と<paramref name="contentMD5" />にパラメーターが設定されている<c>null</c>、クライアント ライブラリが MD5 値を内部で計算し、します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-578">If the <see cref="P:BlobRequestOptions.UseTransactionalMd5" /> property is set to <c>true</c> and the <paramref name="contentMD5" /> parameter is set to <c>null</c>, then the client library will calculate the MD5 value internally.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PutBlockList">
      <MemberSignature Language="C#" Value="public virtual void PutBlockList (System.Collections.Generic.IEnumerable&lt;string&gt; blockList, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void PutBlockList(class System.Collections.Generic.IEnumerable`1&lt;string&gt; blockList, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.PutBlockList(System.Collections.Generic.IEnumerable{System.String},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member PutBlockList : seq&lt;string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.PutBlockList : seq&lt;string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudBlockBlob.PutBlockList (blockList, accessCondition, options, operationContext)" />
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
        <Parameter Name="blockList" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="blockList"><span data-ttu-id="1aa1d-579">列挙可能なコレクションのブロック Id、Base64 でエンコードされた文字列として。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-579">An enumerable collection of block IDs, as Base64-encoded strings.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="1aa1d-580"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-580">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="1aa1d-581">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-581">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-582">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-582">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="1aa1d-583">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-583">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-584"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-584">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-585">新規または既存の blob にブロックの一覧をアップロードします。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-585">Uploads a list of blocks to a new or existing blob.</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PutBlockListAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task PutBlockListAsync (System.Collections.Generic.IEnumerable&lt;string&gt; blockList);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task PutBlockListAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; blockList) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.PutBlockListAsync(System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function PutBlockListAsync (blockList As IEnumerable(Of String)) As Task" />
      <MemberSignature Language="F#" Value="abstract member PutBlockListAsync : seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.PutBlockListAsync : seq&lt;string&gt; -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.PutBlockListAsync blockList" />
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
        <Parameter Name="blockList" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="blockList"><span data-ttu-id="1aa1d-586">列挙可能なコレクションのブロック Id、Base64 でエンコードされた文字列として。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-586">An enumerable collection of block IDs, as Base64-encoded strings.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-587">新規または既存の blob にブロックの一覧をアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-587">Initiates an asynchronous operation to upload a list of blocks to a new or existing blob.</span></span> 
            </summary>
        <returns><span data-ttu-id="1aa1d-588">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-588">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PutBlockListAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task PutBlockListAsync (System.Collections.Generic.IEnumerable&lt;string&gt; blockList, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task PutBlockListAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; blockList, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.PutBlockListAsync(System.Collections.Generic.IEnumerable{System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PutBlockListAsync : seq&lt;string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.PutBlockListAsync : seq&lt;string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.PutBlockListAsync (blockList, cancellationToken)" />
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
        <Parameter Name="blockList" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="blockList"><span data-ttu-id="1aa1d-589">列挙可能なコレクションのブロック Id、Base64 でエンコードされた文字列として。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-589">An enumerable collection of block IDs, as Base64-encoded strings.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="1aa1d-590">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-590">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-591">新規または既存の blob にブロックの一覧をアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-591">Initiates an asynchronous operation to upload a list of blocks to a new or existing blob.</span></span> 
            </summary>
        <returns><span data-ttu-id="1aa1d-592">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-592">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PutBlockListAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task PutBlockListAsync (System.Collections.Generic.IEnumerable&lt;string&gt; blockList, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task PutBlockListAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; blockList, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.PutBlockListAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member PutBlockListAsync : seq&lt;string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.PutBlockListAsync : seq&lt;string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.PutBlockListAsync (blockList, accessCondition, options, operationContext)" />
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
        <Parameter Name="blockList" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="blockList"><span data-ttu-id="1aa1d-593">列挙可能なコレクションのブロック Id、Base64 でエンコードされた文字列として。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-593">An enumerable collection of block IDs, as Base64-encoded strings.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="1aa1d-594"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-594">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="1aa1d-595">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-595">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-596">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-596">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-597"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-597">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-598">新規または既存の blob にブロックの一覧をアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-598">Initiates an asynchronous operation to upload a list of blocks to a new or existing blob.</span></span> 
            </summary>
        <returns><span data-ttu-id="1aa1d-599">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-599">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PutBlockListAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task PutBlockListAsync (System.Collections.Generic.IEnumerable&lt;string&gt; blockList, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task PutBlockListAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; blockList, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.PutBlockListAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PutBlockListAsync : seq&lt;string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.PutBlockListAsync : seq&lt;string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.PutBlockListAsync (blockList, accessCondition, options, operationContext, cancellationToken)" />
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
        <Parameter Name="blockList" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="blockList"><span data-ttu-id="1aa1d-600">列挙可能なコレクションのブロック Id、Base64 でエンコードされた文字列として。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-600">An enumerable collection of block IDs, as Base64-encoded strings.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="1aa1d-601"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-601">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="1aa1d-602">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-602">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-603">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-603">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-604"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-604">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="1aa1d-605">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-605">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-606">新規または既存の blob にブロックの一覧をアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-606">Initiates an asynchronous operation to upload a list of blocks to a new or existing blob.</span></span> 
            </summary>
        <returns><span data-ttu-id="1aa1d-607">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-607">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetStandardBlobTier">
      <MemberSignature Language="C#" Value="public virtual void SetStandardBlobTier (Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier standardBlobTier, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SetStandardBlobTier(valuetype Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier standardBlobTier, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.SetStandardBlobTier(Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetStandardBlobTier : Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.SetStandardBlobTier : Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudBlockBlob.SetStandardBlobTier (standardBlobTier, accessCondition, options, operationContext)" />
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
        <Parameter Name="standardBlobTier" Type="Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="standardBlobTier"><span data-ttu-id="1aa1d-608">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier" />を設定する層を表すです。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-608">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier" /> representing the tier to set.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="1aa1d-609"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-609">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="1aa1d-610">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-610">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-611">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> 、要求の追加オプションを指定するオブジェクトまたは<c>null</c>です。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-611">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request, or <c>null</c>.</span></span> <span data-ttu-id="1aa1d-612">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-612">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-613"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-613">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-614">標準的なストレージ アカウントの blob の層を設定します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-614">Sets the tier of the blob on a standard storage account.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetStandardBlobTierAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetStandardBlobTierAsync (Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier standardBlobTier);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetStandardBlobTierAsync(valuetype Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier standardBlobTier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.SetStandardBlobTierAsync(Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier)" />
      <MemberSignature Language="F#" Value="abstract member SetStandardBlobTierAsync : Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier -&gt; System.Threading.Tasks.Task&#xA;override this.SetStandardBlobTierAsync : Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.SetStandardBlobTierAsync standardBlobTier" />
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
        <Parameter Name="standardBlobTier" Type="Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier" />
      </Parameters>
      <Docs>
        <param name="standardBlobTier"><span data-ttu-id="1aa1d-615">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier" />を設定する層を表すです。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-615">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier" /> representing the tier to set.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-616">標準的なストレージ アカウントの blob の層を設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-616">Initiates an asynchronous operation to set the tier of the blob on a standard storage account.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-617">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-617">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetStandardBlobTierAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetStandardBlobTierAsync (Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier standardBlobTier, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetStandardBlobTierAsync(valuetype Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier standardBlobTier, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.SetStandardBlobTierAsync(Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetStandardBlobTierAsync : Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetStandardBlobTierAsync : Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.SetStandardBlobTierAsync (standardBlobTier, cancellationToken)" />
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
        <Parameter Name="standardBlobTier" Type="Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="standardBlobTier"><span data-ttu-id="1aa1d-618">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier" />を設定する層を表すです。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-618">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier" /> representing the tier to set.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="1aa1d-619">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-619">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-620">標準的なストレージ アカウントの blob の層を設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-620">Initiates an asynchronous operation to set the tier of the blob on a standard storage account.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-621">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-621">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetStandardBlobTierAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetStandardBlobTierAsync (Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier standardBlobTier, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetStandardBlobTierAsync(valuetype Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier standardBlobTier, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.SetStandardBlobTierAsync(Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetStandardBlobTierAsync : Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.SetStandardBlobTierAsync : Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.SetStandardBlobTierAsync (standardBlobTier, accessCondition, options, operationContext)" />
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
        <Parameter Name="standardBlobTier" Type="Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="standardBlobTier"><span data-ttu-id="1aa1d-622">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier" />を設定する層を表すです。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-622">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier" /> representing the tier to set.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="1aa1d-623"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-623">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="1aa1d-624">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-624">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-625">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-625">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-626"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-626">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-627">標準的なストレージ アカウントの blob の層を設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-627">Initiates an asynchronous operation to set the tier of the blob on a standard storage account.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-628">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-628">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetStandardBlobTierAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetStandardBlobTierAsync (Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier standardBlobTier, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetStandardBlobTierAsync(valuetype Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier standardBlobTier, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.SetStandardBlobTierAsync(Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetStandardBlobTierAsync : Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetStandardBlobTierAsync : Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.SetStandardBlobTierAsync (standardBlobTier, accessCondition, options, operationContext, cancellationToken)" />
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
        <Parameter Name="standardBlobTier" Type="Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="standardBlobTier"><span data-ttu-id="1aa1d-629">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier" />を設定する層を表すです。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-629">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier" /> representing the tier to set.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="1aa1d-630"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-630">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="1aa1d-631">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-631">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-632">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-632">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-633"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-633">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="1aa1d-634">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-634">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-635">標準的なストレージ アカウントの blob の層を設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-635">Initiates an asynchronous operation to set the tier of the blob on a standard storage account.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-636">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-636">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartCopy">
      <MemberSignature Language="C#" Value="public virtual string StartCopy (Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob source, Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition = null, Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string StartCopy(class Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob source, class Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, class Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.StartCopy(Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="override this.StartCopy : Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; string" Usage="cloudBlockBlob.StartCopy (source, sourceAccessCondition, destAccessCondition, options, operationContext)" />
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
        <Parameter Name="source" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" />
        <Parameter Name="sourceAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="destAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="1aa1d-637"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-637">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> object.</span></span></param>
        <param name="sourceAccessCondition"><span data-ttu-id="1aa1d-638"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー元 blob のアクセス条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-638">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the source blob.</span></span> <span data-ttu-id="1aa1d-639">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-639">If <c>null</c>, no condition is used.</span></span></param>
        <param name="destAccessCondition"><span data-ttu-id="1aa1d-640"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー先 blob のアクセス条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-640">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the destination blob.</span></span> <span data-ttu-id="1aa1d-641">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-641">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-642">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-642">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="1aa1d-643">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-643">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-644"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-644">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-645">このブロック blob を別のブロック blob の内容、プロパティ、およびメタデータのコピーを開始するための操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-645">Begins an operation to start copying another block blob's contents, properties, and metadata to this block blob.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-646">コピー操作に関連付けられたコピー ID です。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-646">The copy ID associated with the copy operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="1aa1d-647">このメソッドは、blob の ETag、最終更新時刻、および一部のコピー状態をフェッチします。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-647">This method fetches the blob's ETag, last-modified time, and part of the copy state.</span></span>
            <span data-ttu-id="1aa1d-648">コピー ID とコピーのステータス フィールドがフェッチされ、残りのコピーの状態がクリアされます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-648">The copy ID and copy status fields are fetched, and the rest of the copy state is cleared.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StartCopy">
      <MemberSignature Language="C#" Value="public virtual string StartCopy (Microsoft.WindowsAzure.Storage.File.CloudFile source, Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition = null, Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string StartCopy(class Microsoft.WindowsAzure.Storage.File.CloudFile source, class Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, class Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.StartCopy(Microsoft.WindowsAzure.Storage.File.CloudFile,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="override this.StartCopy : Microsoft.WindowsAzure.Storage.File.CloudFile * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; string" Usage="cloudBlockBlob.StartCopy (source, sourceAccessCondition, destAccessCondition, options, operationContext)" />
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
        <Parameter Name="source" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="sourceAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="destAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="1aa1d-649"><see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-649">A <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> object.</span></span></param>
        <param name="sourceAccessCondition"><span data-ttu-id="1aa1d-650"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />ソース ファイルのアクセス条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-650">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the source file.</span></span> <span data-ttu-id="1aa1d-651">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-651">If <c>null</c>, no condition is used.</span></span></param>
        <param name="destAccessCondition"><span data-ttu-id="1aa1d-652"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー先 blob のアクセス条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-652">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the destination blob.</span></span> <span data-ttu-id="1aa1d-653">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-653">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-654">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-654">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="1aa1d-655">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-655">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-656"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-656">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-657">このブロック blob に Azure のファイルの内容、プロパティ、およびメタデータのコピーを開始するための操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-657">Begins an operation to start copying an Azure file's contents, properties, and metadata to this block blob.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-658">コピー操作に関連付けられたコピー ID です。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-658">The copy ID associated with the copy operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="1aa1d-659">このメソッドは、blob の ETag、最終更新時刻、および一部のコピー状態をフェッチします。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-659">This method fetches the blob's ETag, last-modified time, and part of the copy state.</span></span>
            <span data-ttu-id="1aa1d-660">コピー ID とコピーのステータス フィールドがフェッチされ、残りのコピーの状態がクリアされます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-660">The copy ID and copy status fields are fetched, and the rest of the copy state is cleared.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StartCopyAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; StartCopyAsync (Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob source);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; StartCopyAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob source) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.StartCopyAsync(Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function StartCopyAsync (source As CloudBlockBlob) As Task(Of String)" />
      <MemberSignature Language="F#" Value="override this.StartCopyAsync : Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudBlockBlob.StartCopyAsync source" />
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
        <Parameter Name="source" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="1aa1d-661"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-661">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-662">このブロック blob を別のブロック blob の内容、プロパティ、およびメタデータのコピーを開始する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-662">Initiates an asynchronous operation to start copying another block blob's contents, properties, and metadata to this block blob.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-663">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>文字列</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-663">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>string</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartCopyAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; StartCopyAsync (Microsoft.WindowsAzure.Storage.File.CloudFile source);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; StartCopyAsync(class Microsoft.WindowsAzure.Storage.File.CloudFile source) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.StartCopyAsync(Microsoft.WindowsAzure.Storage.File.CloudFile)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function StartCopyAsync (source As CloudFile) As Task(Of String)" />
      <MemberSignature Language="F#" Value="override this.StartCopyAsync : Microsoft.WindowsAzure.Storage.File.CloudFile -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudBlockBlob.StartCopyAsync source" />
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
        <Parameter Name="source" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="1aa1d-664"><see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-664">A <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-665">このブロック blob にファイルの内容、プロパティ、およびメタデータのコピーを開始する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-665">Initiates an asynchronous operation to start copying a file's contents, properties, and metadata to this block blob.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-666">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>文字列</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-666">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>string</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartCopyAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; StartCopyAsync (Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob source, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; StartCopyAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob source, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.StartCopyAsync(Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="override this.StartCopyAsync : Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudBlockBlob.StartCopyAsync (source, cancellationToken)" />
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
        <Parameter Name="source" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="1aa1d-667"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-667">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> object.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="1aa1d-668">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-668">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-669">このブロック blob を別のブロック blob の内容、プロパティ、およびメタデータのコピーを開始する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-669">Initiates an asynchronous operation to start copying another block blob's contents, properties, and metadata to this block blob.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-670">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>文字列</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-670">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>string</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartCopyAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; StartCopyAsync (Microsoft.WindowsAzure.Storage.File.CloudFile source, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; StartCopyAsync(class Microsoft.WindowsAzure.Storage.File.CloudFile source, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.StartCopyAsync(Microsoft.WindowsAzure.Storage.File.CloudFile,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="override this.StartCopyAsync : Microsoft.WindowsAzure.Storage.File.CloudFile * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudBlockBlob.StartCopyAsync (source, cancellationToken)" />
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
        <Parameter Name="source" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="1aa1d-671"><see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-671">A <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> object.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="1aa1d-672">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-672">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-673">このブロック blob にファイルの内容、プロパティ、およびメタデータのコピーを開始する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-673">Initiates an asynchronous operation to start copying a file's contents, properties, and metadata to this block blob.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-674">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>文字列</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-674">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>string</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartCopyAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; StartCopyAsync (Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob source, Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; StartCopyAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob source, class Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, class Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.StartCopyAsync(Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="override this.StartCopyAsync : Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudBlockBlob.StartCopyAsync (source, sourceAccessCondition, destAccessCondition, options, operationContext)" />
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
        <Parameter Name="source" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" />
        <Parameter Name="sourceAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="destAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="1aa1d-675"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-675">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> object.</span></span></param>
        <param name="sourceAccessCondition"><span data-ttu-id="1aa1d-676"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー元 blob のアクセス条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-676">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the source blob.</span></span> <span data-ttu-id="1aa1d-677">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-677">If <c>null</c>, no condition is used.</span></span></param>
        <param name="destAccessCondition"><span data-ttu-id="1aa1d-678"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー先 blob のアクセス条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-678">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the destination blob.</span></span> <span data-ttu-id="1aa1d-679">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-679">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-680">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-680">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-681"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-681">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-682">このブロック blob を別のブロック blob の内容、プロパティ、およびメタデータのコピーを開始する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-682">Initiates an asynchronous operation to start copying another block blob's contents, properties, and metadata to this block blob.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-683">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>文字列</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-683">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>string</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartCopyAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; StartCopyAsync (Microsoft.WindowsAzure.Storage.File.CloudFile source, Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; StartCopyAsync(class Microsoft.WindowsAzure.Storage.File.CloudFile source, class Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, class Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.StartCopyAsync(Microsoft.WindowsAzure.Storage.File.CloudFile,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="override this.StartCopyAsync : Microsoft.WindowsAzure.Storage.File.CloudFile * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudBlockBlob.StartCopyAsync (source, sourceAccessCondition, destAccessCondition, options, operationContext)" />
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
        <Parameter Name="source" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="sourceAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="destAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="1aa1d-684"><see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-684">A <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> object.</span></span></param>
        <param name="sourceAccessCondition"><span data-ttu-id="1aa1d-685"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />ソース ファイルのアクセス条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-685">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the source file.</span></span> <span data-ttu-id="1aa1d-686">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-686">If <c>null</c>, no condition is used.</span></span></param>
        <param name="destAccessCondition"><span data-ttu-id="1aa1d-687"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー先 blob のアクセス条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-687">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the destination blob.</span></span> <span data-ttu-id="1aa1d-688">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-688">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-689">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-689">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-690"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-690">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-691">このブロック blob にファイルの内容、プロパティ、およびメタデータのコピーを開始する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-691">Initiates an asynchronous operation to start copying a file's contents, properties, and metadata to this block blob.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-692">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>文字列</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-692">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>string</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartCopyAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; StartCopyAsync (Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob source, Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; StartCopyAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob source, class Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, class Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.StartCopyAsync(Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="override this.StartCopyAsync : Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudBlockBlob.StartCopyAsync (source, sourceAccessCondition, destAccessCondition, options, operationContext, cancellationToken)" />
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
        <Parameter Name="source" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" />
        <Parameter Name="sourceAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="destAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="1aa1d-693"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-693">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> object.</span></span></param>
        <param name="sourceAccessCondition"><span data-ttu-id="1aa1d-694"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー元 blob のアクセス条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-694">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the source blob.</span></span> <span data-ttu-id="1aa1d-695">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-695">If <c>null</c>, no condition is used.</span></span></param>
        <param name="destAccessCondition"><span data-ttu-id="1aa1d-696"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー先 blob のアクセス条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-696">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the destination blob.</span></span> <span data-ttu-id="1aa1d-697">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-697">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-698">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-698">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-699"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-699">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="1aa1d-700">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-700">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-701">このブロック blob を別のブロック blob の内容、プロパティ、およびメタデータのコピーを開始する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-701">Initiates an asynchronous operation to start copying another block blob's contents, properties, and metadata to this block blob.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-702">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>文字列</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-702">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>string</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartCopyAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; StartCopyAsync (Microsoft.WindowsAzure.Storage.File.CloudFile source, Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; StartCopyAsync(class Microsoft.WindowsAzure.Storage.File.CloudFile source, class Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, class Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.StartCopyAsync(Microsoft.WindowsAzure.Storage.File.CloudFile,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="override this.StartCopyAsync : Microsoft.WindowsAzure.Storage.File.CloudFile * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudBlockBlob.StartCopyAsync (source, sourceAccessCondition, destAccessCondition, options, operationContext, cancellationToken)" />
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
        <Parameter Name="source" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="sourceAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="destAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="1aa1d-703"><see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-703">A <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> object.</span></span></param>
        <param name="sourceAccessCondition"><span data-ttu-id="1aa1d-704"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />ソース ファイルのアクセス条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-704">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the source file.</span></span> <span data-ttu-id="1aa1d-705">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-705">If <c>null</c>, no condition is used.</span></span></param>
        <param name="destAccessCondition"><span data-ttu-id="1aa1d-706"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー先 blob のアクセス条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-706">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the destination blob.</span></span> <span data-ttu-id="1aa1d-707">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-707">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-708">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-708">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-709"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-709">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="1aa1d-710">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-710">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-711">このブロック blob にファイルの内容、プロパティ、およびメタデータのコピーを開始する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-711">Initiates an asynchronous operation to start copying a file's contents, properties, and metadata to this block blob.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-712">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>文字列</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-712">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>string</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StreamWriteSizeInBytes">
      <MemberSignature Language="C#" Value="public int StreamWriteSizeInBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 StreamWriteSizeInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.StreamWriteSizeInBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property StreamWriteSizeInBytes As Integer" />
      <MemberSignature Language="F#" Value="member this.StreamWriteSizeInBytes : int with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.StreamWriteSizeInBytes" />
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
            <span data-ttu-id="1aa1d-713">取得またはブロック blob に書き込むブロック サイズを設定します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-713">Gets or sets the block size for writing to a block blob.</span></span>
            </summary>
        <value><span data-ttu-id="1aa1d-714">(バイト単位) mb 16 KB ~ 100 MB までの範囲内のブロックのサイズ。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-714">The size of a block, in bytes, ranging from between 16 KB and 100 MB inclusive.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromByteArray">
      <MemberSignature Language="C#" Value="public virtual void UploadFromByteArray (byte[] buffer, int index, int count, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void UploadFromByteArray(unsigned int8[] buffer, int32 index, int32 count, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadFromByteArray(System.Byte[],System.Int32,System.Int32,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromByteArray : byte[] * int * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.UploadFromByteArray : byte[] * int * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudBlockBlob.UploadFromByteArray (buffer, index, count, accessCondition, options, operationContext)" />
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
        <param name="buffer"><span data-ttu-id="1aa1d-715">バイト配列。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-715">An array of bytes.</span></span></param>
        <param name="index"><span data-ttu-id="1aa1d-716">Blob のバイトのアップロードを開始位置を示すバッファー内の 0 から始まるバイト オフセット。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-716">The zero-based byte offset in buffer at which to begin uploading bytes to the blob.</span></span></param>
        <param name="count"><span data-ttu-id="1aa1d-717">Blob に書き込まれるバイト数。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-717">The number of bytes to be written to the blob.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="1aa1d-718"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-718">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-719">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-719">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="1aa1d-720">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-720">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-721"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-721">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-722">バイト配列の内容を blob にアップロードします。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-722">Uploads the contents of a byte array to a blob.</span></span> <span data-ttu-id="1aa1d-723">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-723">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromByteArrayAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromByteArrayAsync (byte[] buffer, int index, int count);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromByteArrayAsync(unsigned int8[] buffer, int32 index, int32 count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadFromByteArrayAsync(System.Byte[],System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function UploadFromByteArrayAsync (buffer As Byte(), index As Integer, count As Integer) As Task" />
      <MemberSignature Language="F#" Value="abstract member UploadFromByteArrayAsync : byte[] * int * int -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromByteArrayAsync : byte[] * int * int -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.UploadFromByteArrayAsync (buffer, index, count)" />
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
        <param name="buffer"><span data-ttu-id="1aa1d-724">バイト配列。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-724">An array of bytes.</span></span></param>
        <param name="index"><span data-ttu-id="1aa1d-725">Blob のバイトのアップロードを開始位置を示すバッファー内の 0 から始まるバイト オフセット。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-725">The zero-based byte offset in buffer at which to begin uploading bytes to the blob.</span></span></param>
        <param name="count"><span data-ttu-id="1aa1d-726">Blob に書き込まれるバイト数。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-726">The number of bytes to be written to the blob.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-727">バイト配列の内容を blob にアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-727">Initiates an asynchronous operation to upload the contents of a byte array to a blob.</span></span> <span data-ttu-id="1aa1d-728">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-728">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-729">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-729">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromByteArrayAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromByteArrayAsync (byte[] buffer, int index, int count, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromByteArrayAsync(unsigned int8[] buffer, int32 index, int32 count, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadFromByteArrayAsync(System.Byte[],System.Int32,System.Int32,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromByteArrayAsync : byte[] * int * int * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromByteArrayAsync : byte[] * int * int * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.UploadFromByteArrayAsync (buffer, index, count, cancellationToken)" />
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
        <param name="buffer"><span data-ttu-id="1aa1d-730">バイト配列。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-730">An array of bytes.</span></span></param>
        <param name="index"><span data-ttu-id="1aa1d-731">Blob のバイトのアップロードを開始位置を示すバッファー内の 0 から始まるバイト オフセット。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-731">The zero-based byte offset in buffer at which to begin uploading bytes to the blob.</span></span></param>
        <param name="count"><span data-ttu-id="1aa1d-732">Blob に書き込まれるバイト数。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-732">The number of bytes to be written to the blob.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="1aa1d-733">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-733">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-734">バイト配列の内容を blob にアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-734">Initiates an asynchronous operation to upload the contents of a byte array to a blob.</span></span> <span data-ttu-id="1aa1d-735">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-735">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-736">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-736">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromByteArrayAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromByteArrayAsync (byte[] buffer, int index, int count, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromByteArrayAsync(unsigned int8[] buffer, int32 index, int32 count, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadFromByteArrayAsync(System.Byte[],System.Int32,System.Int32,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromByteArrayAsync : byte[] * int * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromByteArrayAsync : byte[] * int * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.UploadFromByteArrayAsync (buffer, index, count, accessCondition, options, operationContext)" />
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
        <param name="buffer"><span data-ttu-id="1aa1d-737">バイト配列。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-737">An array of bytes.</span></span></param>
        <param name="index"><span data-ttu-id="1aa1d-738">Blob のバイトのアップロードを開始位置を示すバッファー内の 0 から始まるバイト オフセット。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-738">The zero-based byte offset in buffer at which to begin uploading bytes to the blob.</span></span></param>
        <param name="count"><span data-ttu-id="1aa1d-739">Blob に書き込まれるバイト数。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-739">The number of bytes to be written to the blob.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="1aa1d-740"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-740">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-741">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-741">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-742"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-742">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-743">バイト配列の内容を blob にアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-743">Initiates an asynchronous operation to upload the contents of a byte array to a blob.</span></span> <span data-ttu-id="1aa1d-744">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-744">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-745">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-745">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromByteArrayAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromByteArrayAsync (byte[] buffer, int index, int count, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromByteArrayAsync(unsigned int8[] buffer, int32 index, int32 count, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadFromByteArrayAsync(System.Byte[],System.Int32,System.Int32,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromByteArrayAsync : byte[] * int * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromByteArrayAsync : byte[] * int * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.UploadFromByteArrayAsync (buffer, index, count, accessCondition, options, operationContext, cancellationToken)" />
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
        <param name="buffer"><span data-ttu-id="1aa1d-746">バイト配列。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-746">An array of bytes.</span></span></param>
        <param name="index"><span data-ttu-id="1aa1d-747">Blob のバイトのアップロードを開始位置を示すバッファー内の 0 から始まるバイト オフセット。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-747">The zero-based byte offset in buffer at which to begin uploading bytes to the blob.</span></span></param>
        <param name="count"><span data-ttu-id="1aa1d-748">Blob に書き込まれるバイト数。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-748">The number of bytes to be written to the blob.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="1aa1d-749"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-749">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-750">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-750">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-751"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-751">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="1aa1d-752">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-752">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-753">バイト配列の内容を blob にアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-753">Initiates an asynchronous operation to upload the contents of a byte array to a blob.</span></span> <span data-ttu-id="1aa1d-754">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-754">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-755">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-755">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromByteArrayAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromByteArrayAsync (byte[] buffer, int index, int count, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromByteArrayAsync(unsigned int8[] buffer, int32 index, int32 count, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.IProgress`1&lt;class Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadFromByteArrayAsync(System.Byte[],System.Int32,System.Int32,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.IProgress{Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromByteArrayAsync : byte[] * int * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromByteArrayAsync : byte[] * int * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.UploadFromByteArrayAsync (buffer, index, count, accessCondition, options, operationContext, progressHandler, cancellationToken)" />
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
        <param name="buffer"><span data-ttu-id="1aa1d-756">バイト配列。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-756">An array of bytes.</span></span></param>
        <param name="index"><span data-ttu-id="1aa1d-757">Blob のバイトのアップロードを開始位置を示すバッファー内の 0 から始まるバイト オフセット。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-757">The zero-based byte offset in buffer at which to begin uploading bytes to the blob.</span></span></param>
        <param name="count"><span data-ttu-id="1aa1d-758">Blob に書き込まれるバイト数。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-758">The number of bytes to be written to the blob.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="1aa1d-759"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-759">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-760">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-760">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-761"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-761">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="progressHandler"> <span data-ttu-id="1aa1d-762">A<see cref="T:System.IProgress`1" />を処理するオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" />メッセージ。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-762">A <see cref="T:System.IProgress`1" /> object to handle <see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" /> messages.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="1aa1d-763">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-763">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-764">バイト配列の内容を blob にアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-764">Initiates an asynchronous operation to upload the contents of a byte array to a blob.</span></span> <span data-ttu-id="1aa1d-765">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-765">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-766">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-766">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromFile">
      <MemberSignature Language="C#" Value="public virtual void UploadFromFile (string path, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void UploadFromFile(string path, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadFromFile(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromFile : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.UploadFromFile : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudBlockBlob.UploadFromFile (path, accessCondition, options, operationContext)" />
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
        <param name="path"><span data-ttu-id="1aa1d-767">Blob コンテンツを提供するファイルのパスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-767">A string containing the file path providing the blob content.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="1aa1d-768"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-768">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-769">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-769">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="1aa1d-770">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-770">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-771"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-771">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-772">Blob サービスにファイルをアップロードします。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-772">Uploads a file to the Blob service.</span></span> <span data-ttu-id="1aa1d-773">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-773">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromFileAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromFileAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromFileAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadFromFileAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function UploadFromFileAsync (path As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member UploadFromFileAsync : string -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromFileAsync : string -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.UploadFromFileAsync path" />
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
        <param name="path"><span data-ttu-id="1aa1d-774">Blob コンテンツを提供するファイルのパスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-774">A string containing the file path providing the blob content.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-775">Blob にファイルをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-775">Initiates an asynchronous operation to upload a file to a blob.</span></span> <span data-ttu-id="1aa1d-776">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-776">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-777">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-777">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromFileAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromFileAsync (string path, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromFileAsync(string path, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadFromFileAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromFileAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromFileAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.UploadFromFileAsync (path, cancellationToken)" />
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
        <param name="path"><span data-ttu-id="1aa1d-778">Blob コンテンツを提供するファイルのパスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-778">A string containing the file path providing the blob content.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="1aa1d-779">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-779">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-780">Blob にファイルをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-780">Initiates an asynchronous operation to upload a file to a blob.</span></span> <span data-ttu-id="1aa1d-781">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-781">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-782">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-782">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromFileAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromFileAsync (string path, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromFileAsync(string path, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadFromFileAsync(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromFileAsync : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromFileAsync : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.UploadFromFileAsync (path, accessCondition, options, operationContext)" />
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
        <param name="path"><span data-ttu-id="1aa1d-783">Blob コンテンツを提供するファイルのパスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-783">A string containing the file path providing the blob content.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="1aa1d-784"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-784">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-785">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-785">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-786"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-786">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-787">Blob にファイルをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-787">Initiates an asynchronous operation to upload a file to a blob.</span></span> <span data-ttu-id="1aa1d-788">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-788">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-789">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-789">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromFileAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromFileAsync (string path, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromFileAsync(string path, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadFromFileAsync(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromFileAsync : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromFileAsync : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.UploadFromFileAsync (path, accessCondition, options, operationContext, cancellationToken)" />
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
        <param name="path"><span data-ttu-id="1aa1d-790">Blob コンテンツを提供するファイルのパスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-790">A string containing the file path providing the blob content.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="1aa1d-791"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-791">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-792">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-792">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-793"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-793">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="1aa1d-794">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-794">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-795">Blob にファイルをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-795">Initiates an asynchronous operation to upload a file to a blob.</span></span> <span data-ttu-id="1aa1d-796">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-796">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-797">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-797">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromFileAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromFileAsync (string path, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromFileAsync(string path, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.IProgress`1&lt;class Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadFromFileAsync(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.IProgress{Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromFileAsync : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromFileAsync : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.UploadFromFileAsync (path, accessCondition, options, operationContext, progressHandler, cancellationToken)" />
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
        <param name="path"><span data-ttu-id="1aa1d-798">Blob コンテンツを提供するファイルのパスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-798">A string containing the file path providing the blob content.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="1aa1d-799"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-799">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-800">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-800">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-801"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-801">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="progressHandler"> <span data-ttu-id="1aa1d-802">A<see cref="T:System.IProgress`1" />を処理するオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" />メッセージ。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-802">A <see cref="T:System.IProgress`1" /> object to handle <see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" /> messages.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="1aa1d-803">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-803">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-804">Blob にファイルをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-804">Initiates an asynchronous operation to upload a file to a blob.</span></span> <span data-ttu-id="1aa1d-805">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-805">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-806">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-806">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromStream">
      <MemberSignature Language="C#" Value="public virtual void UploadFromStream (System.IO.Stream source, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void UploadFromStream(class System.IO.Stream source, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadFromStream(System.IO.Stream,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromStream : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.UploadFromStream : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudBlockBlob.UploadFromStream (source, accessCondition, options, operationContext)" />
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
        <param name="source"><span data-ttu-id="1aa1d-807">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-807">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="1aa1d-808"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-808">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="1aa1d-809">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-809">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-810">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-810">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="1aa1d-811">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-811">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-812"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-812">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-813">ブロック blob にストリームをアップロードします。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-813">Uploads a stream to a block blob.</span></span> <span data-ttu-id="1aa1d-814">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-814">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromStream">
      <MemberSignature Language="C#" Value="public virtual void UploadFromStream (System.IO.Stream source, long length, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void UploadFromStream(class System.IO.Stream source, int64 length, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadFromStream(System.IO.Stream,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromStream : System.IO.Stream * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.UploadFromStream : System.IO.Stream * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudBlockBlob.UploadFromStream (source, length, accessCondition, options, operationContext)" />
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
        <param name="source"><span data-ttu-id="1aa1d-815">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-815">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="length"><span data-ttu-id="1aa1d-816">現在の位置に、ソース ストリームから書き込むバイト数。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-816">The number of bytes to write from the source stream at its current position.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="1aa1d-817"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-817">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="1aa1d-818">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-818">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-819">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-819">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="1aa1d-820">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-820">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-821"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-821">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-822">ブロック blob にストリームをアップロードします。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-822">Uploads a stream to a block blob.</span></span> <span data-ttu-id="1aa1d-823">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-823">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromStreamAsync (System.IO.Stream source);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromStreamAsync(class System.IO.Stream source) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadFromStreamAsync(System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function UploadFromStreamAsync (source As Stream) As Task" />
      <MemberSignature Language="F#" Value="abstract member UploadFromStreamAsync : System.IO.Stream -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromStreamAsync : System.IO.Stream -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.UploadFromStreamAsync source" />
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
        <param name="source"><span data-ttu-id="1aa1d-824">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-824">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-825">ブロック blob にストリームをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-825">Initiates an asynchronous operation to upload a stream to a block blob.</span></span> <span data-ttu-id="1aa1d-826">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-826">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-827">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-827">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromStreamAsync (System.IO.Stream source, long length);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromStreamAsync(class System.IO.Stream source, int64 length) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadFromStreamAsync(System.IO.Stream,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function UploadFromStreamAsync (source As Stream, length As Long) As Task" />
      <MemberSignature Language="F#" Value="abstract member UploadFromStreamAsync : System.IO.Stream * int64 -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromStreamAsync : System.IO.Stream * int64 -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.UploadFromStreamAsync (source, length)" />
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
        <param name="source"><span data-ttu-id="1aa1d-828">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-828">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="length"><span data-ttu-id="1aa1d-829">現在の位置に、ソース ストリームから書き込むバイト数。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-829">The number of bytes to write from the source stream at its current position.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-830">ブロック blob にストリームをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-830">Initiates an asynchronous operation to upload a stream to a block blob.</span></span> <span data-ttu-id="1aa1d-831">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-831">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-832">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-832">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromStreamAsync (System.IO.Stream source, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromStreamAsync(class System.IO.Stream source, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadFromStreamAsync(System.IO.Stream,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromStreamAsync : System.IO.Stream * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromStreamAsync : System.IO.Stream * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.UploadFromStreamAsync (source, cancellationToken)" />
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
        <param name="source"><span data-ttu-id="1aa1d-833">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-833">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="1aa1d-834">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-834">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-835">ブロック blob にストリームをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-835">Initiates an asynchronous operation to upload a stream to a block blob.</span></span> <span data-ttu-id="1aa1d-836">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-836">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-837">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-837">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromStreamAsync (System.IO.Stream source, long length, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromStreamAsync(class System.IO.Stream source, int64 length, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadFromStreamAsync(System.IO.Stream,System.Int64,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromStreamAsync : System.IO.Stream * int64 * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromStreamAsync : System.IO.Stream * int64 * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.UploadFromStreamAsync (source, length, cancellationToken)" />
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
        <param name="source"><span data-ttu-id="1aa1d-838">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-838">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="length"><span data-ttu-id="1aa1d-839">現在の位置に、ソース ストリームから書き込むバイト数。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-839">The number of bytes to write from the source stream at its current position.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="1aa1d-840">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-840">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-841">ブロック blob にストリームをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-841">Initiates an asynchronous operation to upload a stream to a block blob.</span></span> <span data-ttu-id="1aa1d-842">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-842">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-843">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-843">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromStreamAsync (System.IO.Stream source, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromStreamAsync(class System.IO.Stream source, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadFromStreamAsync(System.IO.Stream,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromStreamAsync : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromStreamAsync : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.UploadFromStreamAsync (source, accessCondition, options, operationContext)" />
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
        <param name="source"><span data-ttu-id="1aa1d-844">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-844">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="1aa1d-845"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-845">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="1aa1d-846">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-846">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-847">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-847">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-848"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-848">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-849">ブロック blob にストリームをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-849">Initiates an asynchronous operation to upload a stream to a block blob.</span></span> <span data-ttu-id="1aa1d-850">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-850">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-851">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-851">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromStreamAsync (System.IO.Stream source, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromStreamAsync(class System.IO.Stream source, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadFromStreamAsync(System.IO.Stream,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromStreamAsync : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromStreamAsync : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.UploadFromStreamAsync (source, accessCondition, options, operationContext, cancellationToken)" />
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
        <param name="source"><span data-ttu-id="1aa1d-852">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-852">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="1aa1d-853"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-853">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="1aa1d-854">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-854">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-855">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-855">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-856"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-856">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="1aa1d-857">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-857">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-858">ブロック blob にストリームをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-858">Initiates an asynchronous operation to upload a stream to a block blob.</span></span> <span data-ttu-id="1aa1d-859">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-859">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-860">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-860">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromStreamAsync (System.IO.Stream source, long length, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromStreamAsync(class System.IO.Stream source, int64 length, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadFromStreamAsync(System.IO.Stream,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromStreamAsync : System.IO.Stream * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromStreamAsync : System.IO.Stream * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.UploadFromStreamAsync (source, length, accessCondition, options, operationContext)" />
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
        <param name="source"><span data-ttu-id="1aa1d-861">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-861">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="length"><span data-ttu-id="1aa1d-862">現在の位置に、ソース ストリームから書き込むバイト数。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-862">The number of bytes to write from the source stream at its current position.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="1aa1d-863"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-863">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="1aa1d-864">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-864">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-865">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-865">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-866"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-866">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-867">ブロック blob にストリームをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-867">Initiates an asynchronous operation to upload a stream to a block blob.</span></span> <span data-ttu-id="1aa1d-868">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-868">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-869">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-869">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromStreamAsync (System.IO.Stream source, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromStreamAsync(class System.IO.Stream source, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.IProgress`1&lt;class Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadFromStreamAsync(System.IO.Stream,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.IProgress{Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromStreamAsync : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromStreamAsync : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.UploadFromStreamAsync (source, accessCondition, options, operationContext, progressHandler, cancellationToken)" />
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
        <param name="source"><span data-ttu-id="1aa1d-870">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-870">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="1aa1d-871"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-871">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="1aa1d-872">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-872">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-873">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-873">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-874"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-874">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="progressHandler"> <span data-ttu-id="1aa1d-875">A<see cref="T:System.IProgress`1" />を処理するオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" />メッセージ。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-875">A <see cref="T:System.IProgress`1" /> object to handle <see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" /> messages.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="1aa1d-876">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-876">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-877">ブロック blob にストリームをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-877">Initiates an asynchronous operation to upload a stream to a block blob.</span></span> <span data-ttu-id="1aa1d-878">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-878">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-879">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-879">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromStreamAsync (System.IO.Stream source, long length, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromStreamAsync(class System.IO.Stream source, int64 length, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadFromStreamAsync(System.IO.Stream,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromStreamAsync : System.IO.Stream * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromStreamAsync : System.IO.Stream * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.UploadFromStreamAsync (source, length, accessCondition, options, operationContext, cancellationToken)" />
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
        <param name="source"><span data-ttu-id="1aa1d-880">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-880">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="length"><span data-ttu-id="1aa1d-881">現在の位置に、ソース ストリームから書き込むバイト数。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-881">The number of bytes to write from the source stream at its current position.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="1aa1d-882"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-882">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="1aa1d-883">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-883">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-884">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-884">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-885"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-885">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="1aa1d-886">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-886">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-887">ブロック blob にストリームをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-887">Initiates an asynchronous operation to upload a stream to a block blob.</span></span> <span data-ttu-id="1aa1d-888">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-888">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-889">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-889">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromStreamAsync (System.IO.Stream source, long length, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromStreamAsync(class System.IO.Stream source, int64 length, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.IProgress`1&lt;class Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadFromStreamAsync(System.IO.Stream,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.IProgress{Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromStreamAsync : System.IO.Stream * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromStreamAsync : System.IO.Stream * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.UploadFromStreamAsync (source, length, accessCondition, options, operationContext, progressHandler, cancellationToken)" />
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
        <param name="source"><span data-ttu-id="1aa1d-890">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-890">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="length"><span data-ttu-id="1aa1d-891">現在の位置に、ソース ストリームから書き込むバイト数。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-891">The number of bytes to write from the source stream at its current position.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="1aa1d-892"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-892">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="1aa1d-893">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-893">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-894">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-894">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-895"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-895">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="progressHandler"> <span data-ttu-id="1aa1d-896">A<see cref="T:System.IProgress`1" />を処理するオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" />メッセージ。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-896">A <see cref="T:System.IProgress`1" /> object to handle <see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" /> messages.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="1aa1d-897">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-897">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-898">ブロック blob にストリームをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-898">Initiates an asynchronous operation to upload a stream to a block blob.</span></span> <span data-ttu-id="1aa1d-899">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-899">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-900">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-900">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadText">
      <MemberSignature Language="C#" Value="public virtual void UploadText (string content, System.Text.Encoding encoding = null, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void UploadText(string content, class System.Text.Encoding encoding, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadText(System.String,System.Text.Encoding,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member UploadText : string * System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.UploadText : string * System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudBlockBlob.UploadText (content, encoding, accessCondition, options, operationContext)" />
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
        <param name="content"><span data-ttu-id="1aa1d-901">アップロードするテキストを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-901">A string containing the text to upload.</span></span></param>
        <param name="encoding"><span data-ttu-id="1aa1d-902">A<see cref="T:System.Text.Encoding" />を使用するテキスト エンコーディングを示すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-902">A <see cref="T:System.Text.Encoding" /> object that indicates the text encoding to use.</span></span> <span data-ttu-id="1aa1d-903">場合<c>null</c>utf-8 が使用されます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-903">If <c>null</c>, UTF-8 will be used.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="1aa1d-904"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-904">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-905">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-905">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="1aa1d-906">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-906">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-907"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-907">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-908">テキストの文字列を blob にアップロードします。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-908">Uploads a string of text to a blob.</span></span> <span data-ttu-id="1aa1d-909">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-909">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadTextAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadTextAsync (string content);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadTextAsync(string content) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadTextAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function UploadTextAsync (content As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member UploadTextAsync : string -&gt; System.Threading.Tasks.Task&#xA;override this.UploadTextAsync : string -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.UploadTextAsync content" />
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
        <param name="content"><span data-ttu-id="1aa1d-910">アップロードするテキストを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-910">A string containing the text to upload.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-911">テキストの文字列を blob にアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-911">Initiates an asynchronous operation to upload a string of text to a blob.</span></span> <span data-ttu-id="1aa1d-912">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-912">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-913">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-913">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadTextAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadTextAsync (string content, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadTextAsync(string content, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadTextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadTextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadTextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.UploadTextAsync (content, cancellationToken)" />
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
        <param name="content"><span data-ttu-id="1aa1d-914">アップロードするテキストを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-914">A string containing the text to upload.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="1aa1d-915">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-915">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-916">テキストの文字列を blob にアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-916">Initiates an asynchronous operation to upload a string of text to a blob.</span></span> <span data-ttu-id="1aa1d-917">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-917">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-918">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-918">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadTextAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadTextAsync (string content, System.Text.Encoding encoding, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadTextAsync(string content, class System.Text.Encoding encoding, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadTextAsync(System.String,System.Text.Encoding,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member UploadTextAsync : string * System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.UploadTextAsync : string * System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.UploadTextAsync (content, encoding, accessCondition, options, operationContext)" />
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
        <param name="content"><span data-ttu-id="1aa1d-919">アップロードするテキストを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-919">A string containing the text to upload.</span></span></param>
        <param name="encoding"><span data-ttu-id="1aa1d-920">A<see cref="T:System.Text.Encoding" />を使用するテキスト エンコーディングを示すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-920">A <see cref="T:System.Text.Encoding" /> object that indicates the text encoding to use.</span></span> <span data-ttu-id="1aa1d-921">場合<c>null</c>utf-8 が使用されます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-921">If <c>null</c>, UTF-8 will be used.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="1aa1d-922"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-922">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-923">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-923">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-924"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-924">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-925">テキストの文字列を blob にアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-925">Initiates an asynchronous operation to upload a string of text to a blob.</span></span> <span data-ttu-id="1aa1d-926">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-926">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-927">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-927">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadTextAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadTextAsync (string content, System.Text.Encoding encoding, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadTextAsync(string content, class System.Text.Encoding encoding, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadTextAsync(System.String,System.Text.Encoding,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadTextAsync : string * System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadTextAsync : string * System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.UploadTextAsync (content, encoding, accessCondition, options, operationContext, cancellationToken)" />
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
        <param name="content"><span data-ttu-id="1aa1d-928">アップロードするテキストを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-928">A string containing the text to upload.</span></span></param>
        <param name="encoding"><span data-ttu-id="1aa1d-929">A<see cref="T:System.Text.Encoding" />を使用するテキスト エンコーディングを示すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-929">A <see cref="T:System.Text.Encoding" /> object that indicates the text encoding to use.</span></span> <span data-ttu-id="1aa1d-930">場合<c>null</c>utf-8 が使用されます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-930">If <c>null</c>, UTF-8 will be used.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="1aa1d-931"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-931">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-932">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-932">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-933"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-933">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="1aa1d-934">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-934">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-935">テキストの文字列を blob にアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-935">Initiates an asynchronous operation to upload a string of text to a blob.</span></span> <span data-ttu-id="1aa1d-936">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-936">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-937">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-937">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadTextAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadTextAsync (string content, System.Text.Encoding encoding, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadTextAsync(string content, class System.Text.Encoding encoding, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.IProgress`1&lt;class Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadTextAsync(System.String,System.Text.Encoding,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.IProgress{Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadTextAsync : string * System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadTextAsync : string * System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.UploadTextAsync (content, encoding, accessCondition, options, operationContext, progressHandler, cancellationToken)" />
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
        <param name="content"><span data-ttu-id="1aa1d-938">アップロードするテキストを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-938">A string containing the text to upload.</span></span></param>
        <param name="encoding"><span data-ttu-id="1aa1d-939">A<see cref="T:System.Text.Encoding" />を使用するテキスト エンコーディングを示すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-939">A <see cref="T:System.Text.Encoding" /> object that indicates the text encoding to use.</span></span> <span data-ttu-id="1aa1d-940">場合<c>null</c>utf-8 が使用されます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-940">If <c>null</c>, UTF-8 will be used.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="1aa1d-941"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-941">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="1aa1d-942">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-942">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1aa1d-943"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-943">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="progressHandler"> <span data-ttu-id="1aa1d-944">A<see cref="T:System.IProgress`1" />を処理するオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" />メッセージ。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-944">A <see cref="T:System.IProgress`1" /> object to handle <see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" /> messages.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="1aa1d-945">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-945">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="1aa1d-946">テキストの文字列を blob にアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-946">Initiates an asynchronous operation to upload a string of text to a blob.</span></span> <span data-ttu-id="1aa1d-947">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-947">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="1aa1d-948">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1aa1d-948">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>