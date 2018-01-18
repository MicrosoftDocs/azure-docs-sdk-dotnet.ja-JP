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
            <span data-ttu-id="8d0f4-101">Microsoft Azure ページ blob を表します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-101">Represents a Microsoft Azure page blob.</span></span>
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
        <param name="blobAbsoluteUri"><span data-ttu-id="8d0f4-102">Blob の絶対 URI です。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-102">The absolute URI to the blob.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-103">新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />クラス blob への絶対 URI を使用します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-103">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" /> class using an absolute URI to the blob.</span></span>
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
        <param name="blobAbsoluteUri"><span data-ttu-id="8d0f4-104">Blob の絶対 URI です。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-104">The absolute URI to the blob.</span></span></param>
        <param name="credentials"><span data-ttu-id="8d0f4-105"><see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-105">A <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-106">新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />クラス blob への絶対 URI を使用します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-106">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" /> class using an absolute URI to the blob.</span></span>
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
        <param name="blobAbsoluteUri"><span data-ttu-id="8d0f4-107">Blob の絶対 URI です。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-107">The absolute URI to the blob.</span></span> <span data-ttu-id="8d0f4-108">サービスでは、これは、プライマリの場所での blob の URI を前提としています。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-108">The service assumes this is the URI for the blob in the primary location.</span></span></param>
        <param name="snapshotTime"><span data-ttu-id="8d0f4-109">A <see cref="T:System.DateTimeOffset" /> blob がスナップショットの場合、スナップショットのタイムスタンプを指定します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-109">A <see cref="T:System.DateTimeOffset" /> specifying the snapshot timestamp, if the blob is a snapshot.</span></span></param>
        <param name="credentials"><span data-ttu-id="8d0f4-110"><see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-110">A <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-111">新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />クラス blob への絶対 URI を使用します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-111">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" /> class using an absolute URI to the blob.</span></span>
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
        <param name="blobAbsoluteUri"><span data-ttu-id="8d0f4-112">Blob の絶対 URI です。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-112">The absolute URI to the blob.</span></span></param>
        <param name="snapshotTime"><span data-ttu-id="8d0f4-113">A <see cref="T:System.DateTimeOffset" /> blob がスナップショットの場合、スナップショットのタイムスタンプを指定します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-113">A <see cref="T:System.DateTimeOffset" /> specifying the snapshot timestamp, if the blob is a snapshot.</span></span></param>
        <param name="credentials"><span data-ttu-id="8d0f4-114"><see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-114">A <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-115">新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />クラス blob への絶対 URI を使用します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-115">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" /> class using an absolute URI to the blob.</span></span>
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
        <param name="startOffset"><span data-ttu-id="8d0f4-116">(バイト単位) のページの消去を開始するオフセットです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-116">The offset at which to begin clearing pages, in bytes.</span></span> <span data-ttu-id="8d0f4-117">オフセットは 512 の倍数である必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-117">The offset must be a multiple of 512.</span></span></param>
        <param name="length"><span data-ttu-id="8d0f4-118">(バイト単位) をクリアするデータ範囲の長さ。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-118">The length of the data range to be cleared, in bytes.</span></span> <span data-ttu-id="8d0f4-119">長さは 512 の倍数である必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-119">The length must be a multiple of 512.</span></span></param>
        <param name="callback"><span data-ttu-id="8d0f4-120"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-120">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="8d0f4-121">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-121">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-122">ページ blob からページを消去する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-122">Begins an asynchronous operation to clear pages from a page blob.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-123"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-123">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
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
        <param name="startOffset"><span data-ttu-id="8d0f4-124">(バイト単位) のページの消去を開始するオフセットです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-124">The offset at which to begin clearing pages, in bytes.</span></span> <span data-ttu-id="8d0f4-125">オフセットは 512 の倍数である必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-125">The offset must be a multiple of 512.</span></span></param>
        <param name="length"><span data-ttu-id="8d0f4-126">(バイト単位) をクリアするデータ範囲の長さ。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-126">The length of the data range to be cleared, in bytes.</span></span> <span data-ttu-id="8d0f4-127">長さは 512 の倍数である必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-127">The length must be a multiple of 512.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-128"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-128">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-129">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-129">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-130">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-130">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-131"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-131">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="8d0f4-132"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-132">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="8d0f4-133">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-133">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-134">ページ blob からページを消去する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-134">Begins an asynchronous operation to clear pages from a page blob.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-135"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-135">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
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
        <param name="size"><span data-ttu-id="8d0f4-136">(バイト単位)、ページ blob の最大サイズ。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-136">The maximum size of the page blob, in bytes.</span></span></param>
        <param name="callback"><span data-ttu-id="8d0f4-137"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-137">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="8d0f4-138">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-138">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-139">ページ blob を作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-139">Begins an asynchronous operation to create a page blob.</span></span> <span data-ttu-id="8d0f4-140">Blob が既に存在する場合はこの操作によって上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-140">If the blob already exists, this operation will overwrite it.</span></span> <span data-ttu-id="8d0f4-141">使用して、上書きする代わりに、blob が存在する場合に例外をスローする<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.BeginCreate(System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />です。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-141">To throw an exception if the blob exists, instead of overwriting, use <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.BeginCreate(System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-142"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-142">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
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
        <param name="size"><span data-ttu-id="8d0f4-143">(バイト単位)、blob の最大サイズ。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-143">The maximum size of the blob, in bytes.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-144"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-144">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-145">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-145">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-146">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-146">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-147"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-147">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="8d0f4-148"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-148">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="8d0f4-149">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-149">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-150">ページ blob を作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-150">Begins an asynchronous operation to create a page blob.</span></span> <span data-ttu-id="8d0f4-151">Blob が既に存在する場合はこの操作によって上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-151">If the blob already exists, this operation will overwrite it.</span></span> <span data-ttu-id="8d0f4-152">渡す、上書きする代わりに、blob が存在する場合に例外をスローする、<see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />オブジェクトを使用して生成<see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />です。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-152">To throw an exception if the blob exists, instead of overwriting, pass in an <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object generated using <see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-153"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-153">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
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
        <param name="size"><span data-ttu-id="8d0f4-154">(バイト単位)、blob の最大サイズ。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-154">The maximum size of the blob, in bytes.</span></span></param>
        <param name="premiumPageBlobTier"><span data-ttu-id="8d0f4-155">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-155">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" /> representing the tier to set.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-156"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-156">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-157">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-157">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-158">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-158">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-159"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-159">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="8d0f4-160"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-160">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="8d0f4-161">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-161">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-162">ページ blob を作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-162">Begins an asynchronous operation to create a page blob.</span></span> <span data-ttu-id="8d0f4-163">Blob が既に存在する場合はこの操作によって上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-163">If the blob already exists, this operation will overwrite it.</span></span> <span data-ttu-id="8d0f4-164">渡す、上書きする代わりに、blob が存在する場合に例外をスローする、<see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />オブジェクトを使用して生成<see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />です。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-164">To throw an exception if the blob exists, instead of overwriting, pass in an <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object generated using <see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-165"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-165">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
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
        <param name="callback"><span data-ttu-id="8d0f4-166"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-166">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="8d0f4-167">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-167">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-168">Blob のスナップショットを作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-168">Begins an asynchronous operation to create a snapshot of the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-169"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-169">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
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
        <param name="metadata"><span data-ttu-id="8d0f4-170">スナップショットのメタデータを定義する名前と値のペアのコレクション。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-170">A collection of name-value pairs defining the metadata of the snapshot.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-171"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-171">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-172">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-172">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-173">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> 、要求の追加オプションを指定するオブジェクトまたは<c>null</c>です。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-173">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request, or <c>null</c>.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-174"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-174">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="8d0f4-175"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-175">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="8d0f4-176">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-176">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-177">Blob のスナップショットを作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-177">Begins an asynchronous operation to create a snapshot of the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-178"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-178">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
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
        <param name="callback"><span data-ttu-id="8d0f4-179"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-179">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="8d0f4-180">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-180">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-181">有効なページ範囲の開始および終了バイトのコレクションを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-181">Begins an asynchronous operation to return a collection of valid page ranges and their starting and ending bytes.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-182"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-182">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
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
        <param name="offset"><span data-ttu-id="8d0f4-183">するデータ範囲のリスト ページの範囲の開始オフセット (バイト単位)。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-183">The starting offset of the data range over which to list page ranges, in bytes.</span></span> <span data-ttu-id="8d0f4-184">512 の倍数である必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-184">Must be a multiple of 512.</span></span></param>
        <param name="length"><span data-ttu-id="8d0f4-185">リスト ページにどのデータ範囲の範囲の長さ (バイト単位)。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-185">The length of the data range over which to list page ranges, in bytes.</span></span> <span data-ttu-id="8d0f4-186">512 の倍数である必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-186">Must be a multiple of 512.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-187"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-187">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-188">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-188">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-189">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-189">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-190"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-190">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="8d0f4-191"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-191">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="8d0f4-192">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-192">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-193">有効なページ範囲の開始および終了バイトのコレクションを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-193">Begins an asynchronous operation to return a collection of valid page ranges and their starting and ending bytes.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-194"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-194">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
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
        <param name="previousSnapshotTime"><span data-ttu-id="8d0f4-195">A <see cref="T:System.DateTimeOffset" /> diff の開始点として使用する、スナップショットのタイムスタンプを表すこの CloudPageBlob を表す場合、スナップショット、previousSnapshotTime パラメーターは、現在のスナップショットのタイムスタンプより前でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-195">A <see cref="T:System.DateTimeOffset" /> representing the snapshot timestamp to use as the starting point for the diff. If this CloudPageBlob represents a snapshot, the previousSnapshotTime parameter must be prior to the current snapshot timestamp.</span></span></param>
        <param name="callback"><span data-ttu-id="8d0f4-196"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-196">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="8d0f4-197">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-197">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-198">指定したスナップショットとこのオブジェクトの間で異なるページ範囲のコレクションを取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-198">Begins an asynchronous operation to return the collection of page ranges that differ between a specified snapshot and this object.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-199"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-199">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
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
        <param name="previousSnapshotTime"><span data-ttu-id="8d0f4-200">A <see cref="T:System.DateTimeOffset" /> diff の開始点として使用する、スナップショットのタイムスタンプを表すこの CloudPageBlob を表す場合、スナップショット、previousSnapshotTime パラメーターは、現在のスナップショットのタイムスタンプより前でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-200">A <see cref="T:System.DateTimeOffset" /> representing the snapshot timestamp to use as the starting point for the diff. If this CloudPageBlob represents a snapshot, the previousSnapshotTime parameter must be prior to the current snapshot timestamp.</span></span></param>
        <param name="offset"><span data-ttu-id="8d0f4-201">するデータ範囲のリスト ページの範囲の開始オフセット (バイト単位)。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-201">The starting offset of the data range over which to list page ranges, in bytes.</span></span> <span data-ttu-id="8d0f4-202">512 の倍数である必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-202">Must be a multiple of 512.</span></span></param>
        <param name="length"><span data-ttu-id="8d0f4-203">リスト ページにどのデータ範囲の範囲の長さ (バイト単位)。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-203">The length of the data range over which to list page ranges, in bytes.</span></span> <span data-ttu-id="8d0f4-204">512 の倍数である必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-204">Must be a multiple of 512.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-205"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-205">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-206">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-206">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-207">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-207">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-208"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-208">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="8d0f4-209"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-209">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="8d0f4-210">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-210">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-211">指定したスナップショットとこのオブジェクトの間で異なるページ範囲のコレクションを取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-211">Begins an asynchronous operation to return the collection of page ranges that differ between a specified snapshot and this object.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-212"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-212">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
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
        <param name="size"><span data-ttu-id="8d0f4-213">(バイト単位)、ページ blob のサイズ。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-213">The size of the page blob, in bytes.</span></span> <span data-ttu-id="8d0f4-214">サイズは 512 の倍数である必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-214">The size must be a multiple of 512.</span></span> <span data-ttu-id="8d0f4-215">場合<c>null</c>、ページ blob が既に存在する必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-215">If <c>null</c>, the page blob must already exist.</span></span></param>
        <param name="callback"><span data-ttu-id="8d0f4-216"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-216">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="8d0f4-217">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-217">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-218">Blob に書き込むためのストリームを開く非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-218">Begins an asynchronous operation to open a stream for writing to the blob.</span></span> <span data-ttu-id="8d0f4-219">Blob が既に存在する場合は、blob 内の既存のデータが上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-219">If the blob already exists, then existing data in the blob may be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-220"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-220">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="8d0f4-221">このメソッドへの呼び出しを常に、注意してください、<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginFetchAttributes(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />内部的メソッドです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-221">Note that this method always makes a call to the <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginFetchAttributes(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" /> method under the covers.</span></span></para>
          <para><span data-ttu-id="8d0f4-222">設定、<see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.StreamWriteSizeInBytes" />書き込み mb 包括的な 512 ~ 4 MB までの範囲の 512 バイトの倍数では、ページ サイズを指定するには、このメソッドを呼び出す前に、プロパティです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-222">Set the <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.StreamWriteSizeInBytes" /> property before calling this method to specify the page size to write, in multiples of 512 bytes, ranging from between 512 and 4 MB inclusive.</span></span></para>
          <para><span data-ttu-id="8d0f4-223">例外をスローする、上書きすることではなく、blob が存在する場合は、次を参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.BeginOpenWrite(System.Nullable{System.Int64},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />です。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-223">To throw an exception if the blob exists instead of overwriting it, see <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.BeginOpenWrite(System.Nullable{System.Int64},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />.</span></span></para>
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
        <param name="size"><span data-ttu-id="8d0f4-224">(バイト単位)、ページ blob のサイズ。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-224">The size of the page blob, in bytes.</span></span> <span data-ttu-id="8d0f4-225">サイズは 512 の倍数である必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-225">The size must be a multiple of 512.</span></span> <span data-ttu-id="8d0f4-226">場合<c>null</c>、ページ blob が既に存在する必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-226">If <c>null</c>, the page blob must already exist.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-227"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-227">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-228">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-228">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-229">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-229">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-230"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-230">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="8d0f4-231"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-231">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="8d0f4-232">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-232">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-233">Blob に書き込むためのストリームを開く非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-233">Begins an asynchronous operation to open a stream for writing to the blob.</span></span> <span data-ttu-id="8d0f4-234">Blob が既に存在する場合は、blob 内の既存のデータが上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-234">If the blob already exists, then existing data in the blob may be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-235"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-235">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="8d0f4-236">このメソッドへの呼び出しを常に、注意してください、<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginFetchAttributes(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />内部的メソッドです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-236">Note that this method always makes a call to the <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginFetchAttributes(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" /> method under the covers.</span></span></para>
          <para><span data-ttu-id="8d0f4-237">設定、<see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.StreamWriteSizeInBytes" />書き込み mb 包括的な 512 ~ 4 MB までの範囲の 512 バイトの倍数では、ページ サイズを指定するには、このメソッドを呼び出す前に、プロパティです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-237">Set the <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.StreamWriteSizeInBytes" /> property before calling this method to specify the page size to write, in multiples of 512 bytes, ranging from between 512 and 4 MB inclusive.</span></span></para>
          <para><span data-ttu-id="8d0f4-238">これを上書きする代わりに blob が存在する場合は、例外をスロー、渡す、<see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />オブジェクトを使用して生成<see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />です。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-238">To throw an exception if the blob exists instead of overwriting it, pass in an <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object generated using <see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />.</span></span></para>
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
        <param name="size"><span data-ttu-id="8d0f4-239">(バイト単位)、ページ blob のサイズ。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-239">The size of the page blob, in bytes.</span></span></param>
        <param name="callback"><span data-ttu-id="8d0f4-240"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-240">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="8d0f4-241">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-241">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-242">指定されたサイズにページ blob のサイズを変更する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-242">Begins an asynchronous operation to resize the page blob to the specified size.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-243"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-243">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
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
        <param name="size"><span data-ttu-id="8d0f4-244">(バイト単位)、blob のサイズ。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-244">The size of the blob, in bytes.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-245"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-245">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-246">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-246">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-247">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-247">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-248"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-248">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="8d0f4-249"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-249">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="8d0f4-250">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-250">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-251">指定されたサイズにページ blob のサイズを変更する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-251">Begins an asynchronous operation to resize the page blob to the specified size.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-252"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-252">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
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
        <param name="premiumPageBlobTier"><span data-ttu-id="8d0f4-253">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-253">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" /> representing the tier to set.</span></span></param>
        <param name="callback"><span data-ttu-id="8d0f4-254"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-254">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="8d0f4-255">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-255">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-256">Premium blob の層に設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-256">Begins an asynchronous operation to set the tier of the premium blob.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-257"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-257">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
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
        <param name="premiumPageBlobTier"><span data-ttu-id="8d0f4-258">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-258">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" /> representing the tier to set.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-259">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> 、要求の追加オプションを指定するオブジェクトまたは<c>null</c>です。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-259">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request, or <c>null</c>.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-260"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-260">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="8d0f4-261"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-261">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="8d0f4-262">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-262">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-263">Premium blob の層に設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-263">Begins an asynchronous operation to set the tier of the premium blob.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-264"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-264">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
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
        <param name="sequenceNumberAction"><span data-ttu-id="8d0f4-265">型の値<see cref="T:Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction" />、シーケンス番号に対して実行する操作を示すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-265">A value of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction" />, indicating the operation to perform on the sequence number.</span></span></param>
        <param name="sequenceNumber"><span data-ttu-id="8d0f4-266">シーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-266">The sequence number.</span></span> <span data-ttu-id="8d0f4-267">このパラメーターに設定<c>null</c>場合<paramref name="sequenceNumberAction" />と等しい<see cref="F:SequenceNumberAction.Increment" />です。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-267">Set this parameter to <c>null</c> if <paramref name="sequenceNumberAction" /> is equal to <see cref="F:SequenceNumberAction.Increment" />.</span></span></param>
        <param name="callback"><span data-ttu-id="8d0f4-268"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-268">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="8d0f4-269">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-269">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-270">ページ blob のシーケンス番号を設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-270">Begins an asynchronous operation to set the page blob's sequence number.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-271"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-271">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
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
        <param name="sequenceNumberAction"><span data-ttu-id="8d0f4-272">型の値<see cref="T:Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction" />、シーケンス番号に対して実行する操作を示すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-272">A value of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction" />, indicating the operation to perform on the sequence number.</span></span></param>
        <param name="sequenceNumber"><span data-ttu-id="8d0f4-273">シーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-273">The sequence number.</span></span> <span data-ttu-id="8d0f4-274">このパラメーターに設定<c>null</c>場合<paramref name="sequenceNumberAction" />と等しい<see cref="F:SequenceNumberAction.Increment" />です。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-274">Set this parameter to <c>null</c> if <paramref name="sequenceNumberAction" /> is equal to <see cref="F:SequenceNumberAction.Increment" />.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-275"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-275">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-276">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-276">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-277">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-277">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-278"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-278">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="8d0f4-279"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-279">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="8d0f4-280">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-280">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-281">ページ blob のシーケンス番号を設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-281">Begins an asynchronous operation to set the page blob's sequence number.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-282"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-282">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
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
        <param name="source"><span data-ttu-id="8d0f4-283"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />コピー元 blob はします。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-283">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" /> that is the source blob.</span></span></param>
        <param name="callback"><span data-ttu-id="8d0f4-284"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-284">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="8d0f4-285">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-285">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-286">このページ blob に別のページ blob の内容、プロパティ、およびメタデータのコピーを開始する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-286">Begins an asynchronous operation to start copying another page blob's contents, properties, and metadata to this page blob.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-287"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-287">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
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
        <param name="source"><span data-ttu-id="8d0f4-288"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />コピー元 blob はします。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-288">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" /> that is the source blob.</span></span></param>
        <param name="sourceAccessCondition"><span data-ttu-id="8d0f4-289"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー元 blob のアクセス条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-289">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the source blob.</span></span> <span data-ttu-id="8d0f4-290">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-290">If <c>null</c>, no condition is used.</span></span></param>
        <param name="destAccessCondition"><span data-ttu-id="8d0f4-291"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー先 blob のアクセス条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-291">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the destination blob.</span></span> <span data-ttu-id="8d0f4-292">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-292">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-293">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-293">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-294"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-294">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="8d0f4-295"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-295">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="8d0f4-296">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-296">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-297">このページ blob に別のページ blob の内容、プロパティ、およびメタデータのコピーを開始する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-297">Begins an asynchronous operation to start copying another page blob's contents, properties, and metadata to this page blob.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-298"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-298">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
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
        <param name="source"><span data-ttu-id="8d0f4-299"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />コピー元 blob はします。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-299">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" /> that is the source blob.</span></span></param>
        <param name="premiumPageBlobTier"><span data-ttu-id="8d0f4-300">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-300">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" /> representing the tier to set.</span></span></param>
        <param name="sourceAccessCondition"><span data-ttu-id="8d0f4-301"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー元 blob のアクセス条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-301">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the source blob.</span></span> <span data-ttu-id="8d0f4-302">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-302">If <c>null</c>, no condition is used.</span></span></param>
        <param name="destAccessCondition"><span data-ttu-id="8d0f4-303"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー先 blob のアクセス条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-303">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the destination blob.</span></span> <span data-ttu-id="8d0f4-304">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-304">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-305">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-305">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-306"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-306">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="8d0f4-307"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-307">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="8d0f4-308">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-308">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-309">このページ blob に別のページ blob の内容、プロパティ、およびメタデータのコピーを開始する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-309">Begins an asynchronous operation to start copying another page blob's contents, properties, and metadata to this page blob.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-310"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-310">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
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
        <param name="sourceSnapshot"><span data-ttu-id="8d0f4-311"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />コピー元 blob がスナップショットである必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-311">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" /> that is the source blob which must be a snapshot.</span></span></param>
        <param name="callback"><span data-ttu-id="8d0f4-312"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-312">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="8d0f4-313">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-313">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-314">別のページ blob の内容、プロパティ、およびページ blob のメタデータの増分のコピーを開始する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-314">Begins an asynchronous operation to start an incremental copy of another page blob's contents, properties, and metadata to this page blob.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-315"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-315">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
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
        <param name="sourceSnapshot"><span data-ttu-id="8d0f4-316"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />コピー元 blob がスナップショットである必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-316">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" /> that is the source blob which must be a snapshot.</span></span></param>
        <param name="destAccessCondition"><span data-ttu-id="8d0f4-317"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー先 blob のアクセス条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-317">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the destination blob.</span></span> <span data-ttu-id="8d0f4-318">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-318">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-319">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-319">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-320"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-320">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="8d0f4-321"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-321">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="8d0f4-322">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-322">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-323">別のページ blob の内容、プロパティ、およびページ blob のメタデータの増分のコピーを開始する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-323">Begins an asynchronous operation to start an incremental copy of another page blob's contents, properties, and metadata to this page blob.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-324"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-324">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
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
        <param name="sourceSnapshot"><span data-ttu-id="8d0f4-325"><see cref="T:System.Uri" />のコピー元 blob スナップショットをする必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-325">The <see cref="T:System.Uri" /> of the source blob which must be a snapshot.</span></span></param>
        <param name="destAccessCondition"><span data-ttu-id="8d0f4-326"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー先 blob のアクセス条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-326">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the destination blob.</span></span> <span data-ttu-id="8d0f4-327">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-327">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-328">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-328">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-329"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-329">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="8d0f4-330"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-330">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="8d0f4-331">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-331">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-332">この blob を別の blob の内容、プロパティ、およびメタデータのコピーを開始する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-332">Begins an asynchronous operation to start copying another blob's contents, properties, and metadata to this blob.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-333"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-333">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
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
        <param name="buffer"><span data-ttu-id="8d0f4-334">バイト配列。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-334">An array of bytes.</span></span></param>
        <param name="index"><span data-ttu-id="8d0f4-335">Blob のバイトのアップロードを開始位置を示すバッファー内の 0 から始まるバイト オフセット。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-335">The zero-based byte offset in buffer at which to begin uploading bytes to the blob.</span></span></param>
        <param name="count"><span data-ttu-id="8d0f4-336">Blob に書き込まれるバイト数。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-336">The number of bytes to be written to the blob.</span></span></param>
        <param name="callback"><span data-ttu-id="8d0f4-337"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-337">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="8d0f4-338">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-338">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-339">バイト配列の内容をページ blob にアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-339">Begins an asynchronous operation to upload the contents of a byte array to a page blob.</span></span> <span data-ttu-id="8d0f4-340">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-340">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-341"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-341">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
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
        <param name="buffer"><span data-ttu-id="8d0f4-342">バイト配列。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-342">An array of bytes.</span></span></param>
        <param name="index"><span data-ttu-id="8d0f4-343">Blob のバイトのアップロードを開始位置を示すバッファー内の 0 から始まるバイト オフセット。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-343">The zero-based byte offset in buffer at which to begin uploading bytes to the blob.</span></span></param>
        <param name="count"><span data-ttu-id="8d0f4-344">Blob に書き込まれるバイト数。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-344">The number of bytes to be written to the blob.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-345"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-345">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-346">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-346">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-347"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-347">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="8d0f4-348"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-348">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="8d0f4-349">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-349">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-350">バイト配列の内容をページ blob にアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-350">Begins an asynchronous operation to upload the contents of a byte array to a page blob.</span></span> <span data-ttu-id="8d0f4-351">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-351">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-352"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-352">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
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
        <param name="buffer"><span data-ttu-id="8d0f4-353">バイト配列。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-353">An array of bytes.</span></span></param>
        <param name="index"><span data-ttu-id="8d0f4-354">Blob のバイトのアップロードを開始位置を示すバッファー内の 0 から始まるバイト オフセット。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-354">The zero-based byte offset in buffer at which to begin uploading bytes to the blob.</span></span></param>
        <param name="count"><span data-ttu-id="8d0f4-355">Blob に書き込まれるバイト数。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-355">The number of bytes to be written to the blob.</span></span></param>
        <param name="premiumPageBlobTier"><span data-ttu-id="8d0f4-356">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-356">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" /> representing the tier to set.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-357"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-357">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-358">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-358">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-359"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-359">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="8d0f4-360"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-360">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="8d0f4-361">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-361">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-362">バイト配列の内容をページ blob にアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-362">Begins an asynchronous operation to upload the contents of a byte array to a page blob.</span></span> <span data-ttu-id="8d0f4-363">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-363">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-364"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-364">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
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
        <param name="path"><span data-ttu-id="8d0f4-365">Blob コンテンツを提供するファイルのパスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-365">A string containing the file path providing the blob content.</span></span></param>
        <param name="callback"><span data-ttu-id="8d0f4-366"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-366">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="8d0f4-367">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-367">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-368">ページ blob にファイルをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-368">Begins an asynchronous operation to upload a file to a page blob.</span></span> <span data-ttu-id="8d0f4-369">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-369">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-370"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-370">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
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
        <param name="path"><span data-ttu-id="8d0f4-371">Blob コンテンツを提供するファイルのパスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-371">A string containing the file path providing the blob content.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-372"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-372">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-373">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-373">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-374"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-374">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="8d0f4-375"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-375">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="8d0f4-376">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-376">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-377">ページ blob にファイルをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-377">Begins an asynchronous operation to upload a file to a page blob.</span></span> <span data-ttu-id="8d0f4-378">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-378">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-379"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-379">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
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
        <param name="path"><span data-ttu-id="8d0f4-380">Blob コンテンツを提供するファイルのパスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-380">A string containing the file path providing the blob content.</span></span></param>
        <param name="premiumPageBlobTier"><span data-ttu-id="8d0f4-381">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-381">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" /> representing the tier to set.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-382"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-382">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-383">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-383">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-384"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-384">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="8d0f4-385"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-385">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="8d0f4-386">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-386">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-387">ページ blob にファイルをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-387">Begins an asynchronous operation to upload a file to a page blob.</span></span> <span data-ttu-id="8d0f4-388">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-388">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-389"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-389">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
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
        <param name="source"><span data-ttu-id="8d0f4-390">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-390">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="callback"><span data-ttu-id="8d0f4-391"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-391">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="8d0f4-392">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-392">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-393">ページ blob にストリームをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-393">Begins an asynchronous operation to upload a stream to a page blob.</span></span> <span data-ttu-id="8d0f4-394">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-394">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-395"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-395">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
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
        <param name="source"><span data-ttu-id="8d0f4-396">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-396">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="length"><span data-ttu-id="8d0f4-397">開始位置からアップロードするストリームのソースからのバイト数を指定します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-397">Specifies the number of bytes from the Stream source to upload from the start position.</span></span></param>
        <param name="callback"><span data-ttu-id="8d0f4-398"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-398">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="8d0f4-399">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-399">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-400">ページ blob にストリームをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-400">Begins an asynchronous operation to upload a stream to a page blob.</span></span> <span data-ttu-id="8d0f4-401">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-401">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-402"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-402">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
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
        <param name="source"><span data-ttu-id="8d0f4-403">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-403">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-404"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-404">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-405">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-405">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-406">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-406">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-407"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-407">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="8d0f4-408"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-408">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="8d0f4-409">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-409">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-410">ページ blob にストリームをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-410">Begins an asynchronous operation to upload a stream to a page blob.</span></span> <span data-ttu-id="8d0f4-411">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-411">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-412"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-412">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
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
        <param name="source"><span data-ttu-id="8d0f4-413">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-413">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="length"><span data-ttu-id="8d0f4-414">開始位置からアップロードするストリームのソースからのバイト数を指定します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-414">Specifies the number of bytes from the Stream source to upload from the start position.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-415"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-415">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-416">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-416">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-417">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-417">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-418"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-418">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="8d0f4-419"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-419">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="8d0f4-420">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-420">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-421">ページ blob にストリームをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-421">Begins an asynchronous operation to upload a stream to a page blob.</span></span> <span data-ttu-id="8d0f4-422">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-422">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-423"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-423">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
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
        <param name="source"><span data-ttu-id="8d0f4-424">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-424">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="premiumPageBlobTier"><span data-ttu-id="8d0f4-425">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-425">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" /> representing the tier to set.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-426"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-426">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-427">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-427">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-428">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-428">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-429"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-429">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="8d0f4-430"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-430">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="8d0f4-431">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-431">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-432">ページ blob にストリームをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-432">Begins an asynchronous operation to upload a stream to a page blob.</span></span> <span data-ttu-id="8d0f4-433">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-433">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-434"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-434">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
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
        <param name="source"><span data-ttu-id="8d0f4-435">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-435">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="length"><span data-ttu-id="8d0f4-436">開始位置からアップロードするストリームのソースからのバイト数を指定します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-436">Specifies the number of bytes from the Stream source to upload from the start position.</span></span></param>
        <param name="premiumPageBlobTier"><span data-ttu-id="8d0f4-437">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-437">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" /> representing the tier to set.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-438"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-438">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-439">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-439">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-440">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-440">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-441"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-441">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="8d0f4-442"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-442">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="8d0f4-443">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-443">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-444">ページ blob にストリームをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-444">Begins an asynchronous operation to upload a stream to a page blob.</span></span> <span data-ttu-id="8d0f4-445">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-445">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-446"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-446">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
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
        <param name="pageData"><span data-ttu-id="8d0f4-447">A<see cref="T:System.IO.Stream" />ページ データを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-447">A <see cref="T:System.IO.Stream" /> object providing the page data.</span></span></param>
        <param name="startOffset"><span data-ttu-id="8d0f4-448">バイト単位での書き込みを開始するオフセットです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-448">The offset at which to begin writing, in bytes.</span></span> <span data-ttu-id="8d0f4-449">オフセットは 512 の倍数である必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-449">The offset must be a multiple of 512.</span></span></param>
        <param name="contentMD5"><span data-ttu-id="8d0f4-450">ページのトランザクションの整合性を確保するために使用する省略可能なハッシュ値です。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-450">An optional hash value used to ensure transactional integrity for the page.</span></span> <span data-ttu-id="8d0f4-451">あります<c>null</c>または空の文字列。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-451">May be <c>null</c> or an empty string.</span></span></param>
        <param name="callback"><span data-ttu-id="8d0f4-452"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-452">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="8d0f4-453">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-453">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-454">ページ blob にページを書き込む非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-454">Begins an asynchronous operation to write pages to a page blob.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-455"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-455">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="8d0f4-456">クライアントは、ネットワーク上でトランザクションの整合性を確保するための手段として特定のページの書き込み操作の content-md5 ヘッダーを送信できます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-456">Clients may send the Content-MD5 header for a given Write Pages operation as a means to ensure transactional integrity over the wire.</span></span> <span data-ttu-id="8d0f4-457"><paramref name="contentMD5" />パラメーターにより、クライアントは、指定したバイトの範囲に提供することを事前に計算された MD5 値へのアクセスを既に持っています。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-457">The <paramref name="contentMD5" /> parameter permits clients who already have access to a pre-computed MD5 value for a given byte range to provide it.</span></span>
            <span data-ttu-id="8d0f4-458">場合、<see cref="P:BlobRequestOptions.UseTransactionalMd5" />プロパティに設定されている<c>true</c>と<paramref name="contentMD5" />にパラメーターが設定されている<c>null</c>、クライアント ライブラリが MD5 値を内部で計算し、します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-458">If the <see cref="P:BlobRequestOptions.UseTransactionalMd5" /> property is set to <c>true</c> and the <paramref name="contentMD5" /> parameter is set to <c>null</c>, then the client library will calculate the MD5 value internally.</span></span>
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
        <param name="pageData"><span data-ttu-id="8d0f4-459">A<see cref="T:System.IO.Stream" />ページ データを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-459">A <see cref="T:System.IO.Stream" /> object providing the page data.</span></span></param>
        <param name="startOffset"><span data-ttu-id="8d0f4-460">バイト単位での書き込みを開始するオフセットです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-460">The offset at which to begin writing, in bytes.</span></span> <span data-ttu-id="8d0f4-461">オフセットは 512 の倍数である必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-461">The offset must be a multiple of 512.</span></span></param>
        <param name="contentMD5"><span data-ttu-id="8d0f4-462">ページのトランザクションの整合性を確保するために使用する省略可能なハッシュ値です。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-462">An optional hash value used to ensure transactional integrity for the page.</span></span> <span data-ttu-id="8d0f4-463">あります<c>null</c>または空の文字列。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-463">May be <c>null</c> or an empty string.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-464"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-464">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-465">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-465">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-466">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-466">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-467"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-467">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="8d0f4-468"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-468">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="8d0f4-469">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-469">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-470">ページ blob にページを書き込む非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-470">Begins an asynchronous operation to write pages to a page blob.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-471"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-471">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="8d0f4-472">クライアントは、ネットワーク上でトランザクションの整合性を確保するための手段として特定のページの書き込み操作の content-md5 ヘッダーを送信できます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-472">Clients may send the Content-MD5 header for a given Write Pages operation as a means to ensure transactional integrity over the wire.</span></span> <span data-ttu-id="8d0f4-473"><paramref name="contentMD5" />パラメーターにより、クライアントは、指定したバイトの範囲に提供することを事前に計算された MD5 値へのアクセスを既に持っています。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-473">The <paramref name="contentMD5" /> parameter permits clients who already have access to a pre-computed MD5 value for a given byte range to provide it.</span></span>
            <span data-ttu-id="8d0f4-474">場合、<see cref="P:BlobRequestOptions.UseTransactionalMd5" />プロパティに設定されている<c>true</c>と<paramref name="contentMD5" />にパラメーターが設定されている<c>null</c>、クライアント ライブラリが MD5 値を内部で計算し、します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-474">If the <see cref="P:BlobRequestOptions.UseTransactionalMd5" /> property is set to <c>true</c> and the <paramref name="contentMD5" /> parameter is set to <c>null</c>, then the client library will calculate the MD5 value internally.</span></span>
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
        <param name="startOffset"><span data-ttu-id="8d0f4-475">(バイト単位) のページの消去を開始するオフセットです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-475">The offset at which to begin clearing pages, in bytes.</span></span> <span data-ttu-id="8d0f4-476">オフセットは 512 の倍数である必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-476">The offset must be a multiple of 512.</span></span></param>
        <param name="length"><span data-ttu-id="8d0f4-477">(バイト単位) をクリアするデータ範囲の長さ。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-477">The length of the data range to be cleared, in bytes.</span></span> <span data-ttu-id="8d0f4-478">長さは 512 の倍数である必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-478">The length must be a multiple of 512.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-479"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-479">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-480">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-480">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-481">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-481">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="8d0f4-482">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-482">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-483"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-483">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-484">ページ blob からページを消去します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-484">Clears pages from a page blob.</span></span>
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
        <param name="startOffset"><span data-ttu-id="8d0f4-485">(バイト単位) のページの消去を開始するオフセットです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-485">The offset at which to begin clearing pages, in bytes.</span></span> <span data-ttu-id="8d0f4-486">オフセットは 512 の倍数である必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-486">The offset must be a multiple of 512.</span></span></param>
        <param name="length"><span data-ttu-id="8d0f4-487">(バイト単位) をクリアするデータ範囲の長さ。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-487">The length of the data range to be cleared, in bytes.</span></span> <span data-ttu-id="8d0f4-488">長さは 512 の倍数である必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-488">The length must be a multiple of 512.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-489">ページ blob からページを消去する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-489">Initiates an asynchronous operation to clear pages from a page blob.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-490">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-490">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
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
        <param name="startOffset"><span data-ttu-id="8d0f4-491">(バイト単位) のページの消去を開始するオフセットです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-491">The offset at which to begin clearing pages, in bytes.</span></span> <span data-ttu-id="8d0f4-492">オフセットは 512 の倍数である必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-492">The offset must be a multiple of 512.</span></span></param>
        <param name="length"><span data-ttu-id="8d0f4-493">(バイト単位) をクリアするデータ範囲の長さ。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-493">The length of the data range to be cleared, in bytes.</span></span> <span data-ttu-id="8d0f4-494">長さは 512 の倍数である必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-494">The length must be a multiple of 512.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8d0f4-495">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-495">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-496">ページ blob からページを消去する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-496">Initiates an asynchronous operation to clear pages from a page blob.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-497">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-497">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
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
        <param name="startOffset"><span data-ttu-id="8d0f4-498">(バイト単位) のページの消去を開始するオフセットです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-498">The offset at which to begin clearing pages, in bytes.</span></span> <span data-ttu-id="8d0f4-499">オフセットは 512 の倍数である必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-499">The offset must be a multiple of 512.</span></span></param>
        <param name="length"><span data-ttu-id="8d0f4-500">(バイト単位) をクリアするデータ範囲の長さ。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-500">The length of the data range to be cleared, in bytes.</span></span> <span data-ttu-id="8d0f4-501">長さは 512 の倍数である必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-501">The length must be a multiple of 512.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-502"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-502">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-503">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-503">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-504">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-504">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-505"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-505">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-506">ページ blob からページを消去する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-506">Initiates an asynchronous operation to clear pages from a page blob.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-507">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-507">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
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
        <param name="startOffset"><span data-ttu-id="8d0f4-508">(バイト単位) のページの消去を開始するオフセットです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-508">The offset at which to begin clearing pages, in bytes.</span></span> <span data-ttu-id="8d0f4-509">オフセットは 512 の倍数である必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-509">The offset must be a multiple of 512.</span></span></param>
        <param name="length"><span data-ttu-id="8d0f4-510">(バイト単位) をクリアするデータ範囲の長さ。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-510">The length of the data range to be cleared, in bytes.</span></span> <span data-ttu-id="8d0f4-511">長さは 512 の倍数である必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-511">The length must be a multiple of 512.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-512"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-512">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-513">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-513">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-514">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-514">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-515"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-515">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8d0f4-516">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-516">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-517">ページ blob からページを消去する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-517">Initiates an asynchronous operation to clear pages from a page blob.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-518">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-518">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
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
        <param name="size"><span data-ttu-id="8d0f4-519">(バイト単位)、ページ blob の最大サイズ。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-519">The maximum size of the page blob, in bytes.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-520"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-520">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-521">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-521">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-522">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-522">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="8d0f4-523">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-523">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-524"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-524">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-525">ページ blob を作成します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-525">Creates a page blob.</span></span> <span data-ttu-id="8d0f4-526">Blob が既に存在する場合はこの操作によって上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-526">If the blob already exists, this operation will overwrite it.</span></span> <span data-ttu-id="8d0f4-527">渡す、上書きする代わりに、blob が存在する場合に例外をスローする、<see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />オブジェクトを使用して生成<see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />です。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-527">To throw an exception if the blob exists, instead of overwriting, pass in an <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object generated using <see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />.</span></span>
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
        <param name="size"><span data-ttu-id="8d0f4-528">(バイト単位)、ページ blob の最大サイズ。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-528">The maximum size of the page blob, in bytes.</span></span></param>
        <param name="premiumPageBlobTier"><span data-ttu-id="8d0f4-529">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-529">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" /> representing the tier to set.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-530"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-530">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-531">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-531">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-532">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-532">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="8d0f4-533">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-533">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-534"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-534">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-535">ページ blob を作成します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-535">Creates a page blob.</span></span> <span data-ttu-id="8d0f4-536">Blob が既に存在する場合はこの操作によって上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-536">If the blob already exists, this operation will overwrite it.</span></span> <span data-ttu-id="8d0f4-537">渡す、上書きする代わりに、blob が存在する場合に例外をスローする、<see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />オブジェクトを使用して生成<see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />です。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-537">To throw an exception if the blob exists, instead of overwriting, pass in an <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object generated using <see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />.</span></span>
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
        <param name="size"><span data-ttu-id="8d0f4-538">(バイト単位)、blob の最大サイズ。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-538">The maximum size of the blob, in bytes.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-539">ページ blob を作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-539">Initiates an asynchronous operation to create a page blob.</span></span> <span data-ttu-id="8d0f4-540">Blob が既に存在する場合はこの操作によって上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-540">If the blob already exists, this operation will overwrite it.</span></span> <span data-ttu-id="8d0f4-541">使用して、上書きする代わりに、blob が存在する場合に例外をスローする<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.CreateAsync(System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />です。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-541">To throw an exception if the blob exists, instead of overwriting, use <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.CreateAsync(System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-542">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-542">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
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
        <param name="size"><span data-ttu-id="8d0f4-543">(バイト単位)、blob の最大サイズ。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-543">The maximum size of the blob, in bytes.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8d0f4-544">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-544">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-545">ページ blob を作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-545">Initiates an asynchronous operation to create a page blob.</span></span> <span data-ttu-id="8d0f4-546">Blob が既に存在する場合はこの操作によって上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-546">If the blob already exists, this operation will overwrite it.</span></span> <span data-ttu-id="8d0f4-547">使用して、上書きする代わりに、blob が存在する場合に例外をスローする<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.CreateAsync(System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-547">To throw an exception if the blob exists, instead of overwriting, use <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.CreateAsync(System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-548">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-548">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
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
        <param name="size"><span data-ttu-id="8d0f4-549">(バイト単位)、blob の最大サイズ。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-549">The maximum size of the blob, in bytes.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-550"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-550">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-551">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-551">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-552">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-552">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-553"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-553">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-554">ページ blob を作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-554">Initiates an asynchronous operation to create a page blob.</span></span> <span data-ttu-id="8d0f4-555">Blob が既に存在する場合はこの操作によって上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-555">If the blob already exists, this operation will overwrite it.</span></span> <span data-ttu-id="8d0f4-556">渡す、上書きする代わりに、blob が存在する場合に例外をスローする、<see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />オブジェクトを使用して生成<see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />です。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-556">To throw an exception if the blob exists, instead of overwriting, pass in an <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object generated using <see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-557">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-557">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
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
        <param name="size"><span data-ttu-id="8d0f4-558">(バイト単位)、blob の最大サイズ。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-558">The maximum size of the blob, in bytes.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-559"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-559">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-560">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-560">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-561">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-561">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-562"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-562">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8d0f4-563">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-563">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-564">ページ blob を作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-564">Initiates an asynchronous operation to create a page blob.</span></span> <span data-ttu-id="8d0f4-565">Blob が既に存在する場合はこの操作によって上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-565">If the blob already exists, this operation will overwrite it.</span></span> <span data-ttu-id="8d0f4-566">渡す、上書きする代わりに、blob が存在する場合に例外をスローする、<see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />オブジェクトを使用して生成<see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />です。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-566">To throw an exception if the blob exists, instead of overwriting, pass in an <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object generated using <see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-567">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-567">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
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
        <param name="size"><span data-ttu-id="8d0f4-568">(バイト単位)、blob の最大サイズ。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-568">The maximum size of the blob, in bytes.</span></span></param>
        <param name="premiumPageBlobTier"><span data-ttu-id="8d0f4-569">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-569">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" /> representing the tier to set.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-570"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-570">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-571">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-571">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-572">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-572">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-573"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-573">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8d0f4-574">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-574">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-575">ページ blob を作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-575">Initiates an asynchronous operation to create a page blob.</span></span> <span data-ttu-id="8d0f4-576">Blob が既に存在する場合はこの操作によって上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-576">If the blob already exists, this operation will overwrite it.</span></span> <span data-ttu-id="8d0f4-577">渡す、上書きする代わりに、blob が存在する場合に例外をスローする、<see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />オブジェクトを使用して生成<see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />です。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-577">To throw an exception if the blob exists, instead of overwriting, pass in an <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object generated using <see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-578">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-578">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
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
        <param name="metadata"><span data-ttu-id="8d0f4-579">スナップショットのメタデータを定義する名前と値のペアのコレクション。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-579">A collection of name-value pairs defining the metadata of the snapshot.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-580"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-580">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-581">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-581">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-582">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> 、要求の追加オプションを指定するオブジェクトまたは<c>null</c>です。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-582">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request, or <c>null</c>.</span></span> <span data-ttu-id="8d0f4-583">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-583">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-584"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-584">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-585">Blob のスナップショットを作成します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-585">Creates a snapshot of the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-586">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" /> blob のスナップショットであるオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-586">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" /> object that is a blob snapshot.</span></span></returns>
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
            <span data-ttu-id="8d0f4-587">Blob のスナップショットを作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-587">Initiates an asynchronous operation to create a snapshot of the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-588">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-588">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" /> that represents the asynchronous operation.</span></span></returns>
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
        <param name="cancellationToken"><span data-ttu-id="8d0f4-589">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-589">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-590">Blob のスナップショットを作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-590">Initiates an asynchronous operation to create a snapshot of the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-591">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-591">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" /> that represents the asynchronous operation.</span></span></returns>
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
        <param name="metadata"><span data-ttu-id="8d0f4-592">スナップショットのメタデータを定義する名前と値のペアのコレクション。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-592">A collection of name-value pairs defining the metadata of the snapshot.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-593"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-593">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-594">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-594">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-595">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-595">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-596"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-596">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-597">Blob のスナップショットを作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-597">Initiates an asynchronous operation to create a snapshot of the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-598">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-598">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" /> that represents the asynchronous operation.</span></span></returns>
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
        <param name="metadata"><span data-ttu-id="8d0f4-599">スナップショットのメタデータを定義する名前と値のペアのコレクション。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-599">A collection of name-value pairs defining the metadata of the snapshot.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-600"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-600">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-601">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-601">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-602">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-602">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-603"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-603">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8d0f4-604">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-604">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-605">Blob のスナップショットを作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-605">Initiates an asynchronous operation to create a snapshot of the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-606">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-606">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" /> that represents the asynchronous operation.</span></span></returns>
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
        <param name="asyncResult"><span data-ttu-id="8d0f4-607"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-607">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-608">ページ blob からページを消去する非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-608">Ends an asynchronous operation to clear pages from a page blob.</span></span>
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
        <param name="asyncResult"><span data-ttu-id="8d0f4-609"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-609">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-610">ページ blob を作成する非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-610">Ends an asynchronous operation to create a page blob.</span></span>
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
        <param name="asyncResult"><span data-ttu-id="8d0f4-611"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-611">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-612">Blob のスナップショットを作成する非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-612">Ends an asynchronous operation to create a snapshot of the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-613">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" /> blob のスナップショットであるオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-613">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" /> object that is a blob snapshot.</span></span></returns>
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
        <param name="asyncResult"><span data-ttu-id="8d0f4-614"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-614">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-615">有効なページ範囲の開始および終了バイトのコレクションを返す非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-615">Ends an asynchronous operation to return a collection of valid page ranges and their starting and ending bytes.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-616">ページ範囲の列挙可能なコレクション。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-616">An enumerable collection of page ranges.</span></span></returns>
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
        <param name="asyncResult"><span data-ttu-id="8d0f4-617"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-617">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-618">指定したスナップショットとこのオブジェクトの間で異なるページ範囲のコレクションを取得する非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-618">Ends an asynchronous operation to return the collection of page ranges that differ between a specified snapshot and this object.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-619">ページ範囲の列挙可能なコレクション。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-619">An enumerable collection of page ranges.</span></span></returns>
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
        <param name="asyncResult"><span data-ttu-id="8d0f4-620"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-620">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-621">Blob に書き込むためのストリームを開く非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-621">Ends an asynchronous operation to open a stream for writing to the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-622"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-622">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" /> object.</span></span></returns>
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
        <param name="asyncResult"><span data-ttu-id="8d0f4-623"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-623">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-624">ページ blob のサイズを変更する非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-624">Ends an asynchronous operation to resize the page blob.</span></span>
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
        <param name="asyncResult"><span data-ttu-id="8d0f4-625"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-625">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-626">Premium blob の層に設定する非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-626">Ends an asynchronous operation to set the tier of the premium blob.</span></span>
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
        <param name="asyncResult"><span data-ttu-id="8d0f4-627"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-627">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-628">ページ blob のシーケンス番号を設定する非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-628">Ends an asynchronous operation to set the page blob's sequence number.</span></span>
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
        <param name="asyncResult"><span data-ttu-id="8d0f4-629"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-629">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-630">別の blob の内容、プロパティ、および blob のメタデータの増分のコピーを開始する非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-630">Ends an asynchronous operation to start an incremental copy of another blob's contents, properties, and metadata to this blob.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-631">コピー操作に関連付けられたコピー ID を表す文字列。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-631">A string containing the copy ID associated with the copy operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="8d0f4-632">このメソッドは、blob の ETag、最終更新時刻、および一部のコピー状態をフェッチします。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-632">This method fetches the blob's ETag, last-modified time, and part of the copy state.</span></span>
            <span data-ttu-id="8d0f4-633">コピー ID とコピーのステータス フィールドがフェッチされ、残りのコピーの状態がクリアされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-633">The copy ID and copy status fields are fetched, and the rest of the copy state is cleared.</span></span>
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
        <param name="asyncResult"><span data-ttu-id="8d0f4-634"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-634">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-635">バイト配列の内容をページ blob にアップロードする非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-635">Ends an asynchronous operation to upload the contents of a byte array to a page blob.</span></span> <span data-ttu-id="8d0f4-636">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-636">If the blob already exists, it will be overwritten.</span></span>
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
        <param name="asyncResult"><span data-ttu-id="8d0f4-637"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-637">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-638">ページ blob にファイルをアップロードする非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-638">Ends an asynchronous operation to upload a file to a page blob.</span></span> 
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
        <param name="asyncResult"><span data-ttu-id="8d0f4-639"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-639">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-640">ページ blob にストリームをアップロードする非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-640">Ends an asynchronous operation to upload a stream to a page blob.</span></span> 
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
        <param name="asyncResult"><span data-ttu-id="8d0f4-641"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-641">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-642">ページ blob にページを書き込む非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-642">Ends an asynchronous operation to write pages to a page blob.</span></span>
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
        <param name="offset"><span data-ttu-id="8d0f4-643">するデータ範囲のリスト ページの範囲の開始オフセット (バイト単位)。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-643">The starting offset of the data range over which to list page ranges, in bytes.</span></span> <span data-ttu-id="8d0f4-644">512 の倍数である必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-644">Must be a multiple of 512.</span></span></param>
        <param name="length"><span data-ttu-id="8d0f4-645">リスト ページにどのデータ範囲の範囲の長さ (バイト単位)。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-645">The length of the data range over which to list page ranges, in bytes.</span></span> <span data-ttu-id="8d0f4-646">512 の倍数である必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-646">Must be a multiple of 512.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-647"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-647">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-648">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-648">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-649">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-649">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="8d0f4-650">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-650">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-651"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-651">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-652">有効なページ範囲の開始および終了バイトのコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-652">Gets a collection of valid page ranges and their starting and ending bytes.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-653">ページ範囲の列挙可能なコレクション。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-653">An enumerable collection of page ranges.</span></span></returns>
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
            <span data-ttu-id="8d0f4-654">ページ範囲の開始と終了バイトのコレクションを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-654">Initiates an asynchronous operation to return a collection of page ranges and their starting and ending bytes.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-655">A<see cref="T:System.Threading.Tasks.Task`1" />型の列挙可能なコレクションであるオブジェクトを<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PageRange" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-655">A <see cref="T:System.Threading.Tasks.Task`1" /> object that is an enumerable collection of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.PageRange" /> that represents the asynchronous operation.</span></span></returns>
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
        <param name="cancellationToken"><span data-ttu-id="8d0f4-656">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-656">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-657">ページ範囲の開始と終了バイトのコレクションを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-657">Initiates an asynchronous operation to return a collection of page ranges and their starting and ending bytes.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-658">A<see cref="T:System.Threading.Tasks.Task`1" />型の列挙可能なコレクションであるオブジェクトを<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PageRange" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-658">A <see cref="T:System.Threading.Tasks.Task`1" /> object that is an enumerable collection of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.PageRange" /> that represents the asynchronous operation.</span></span></returns>
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
        <param name="offset"><span data-ttu-id="8d0f4-659">(バイト単位)、データ範囲の開始オフセット。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-659">The starting offset of the data range, in bytes.</span></span> <span data-ttu-id="8d0f4-660">512 の倍数である必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-660">Must be a multiple of 512.</span></span></param>
        <param name="length"><span data-ttu-id="8d0f4-661">(バイト単位)、データ範囲の長さ。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-661">The length of the data range, in bytes.</span></span> <span data-ttu-id="8d0f4-662">512 の倍数である必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-662">Must be a multiple of 512.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-663"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-663">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-664">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-664">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-665">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-665">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-666"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-666">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-667">ページ範囲の開始と終了バイトのコレクションを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-667">Initiates an asynchronous operation to return a collection of page ranges and their starting and ending bytes.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-668">A<see cref="T:System.Threading.Tasks.Task`1" />型の列挙可能なコレクションであるオブジェクトを<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PageRange" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-668">A <see cref="T:System.Threading.Tasks.Task`1" /> object that is an enumerable collection of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.PageRange" /> that represents the asynchronous operation.</span></span></returns>
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
        <param name="offset"><span data-ttu-id="8d0f4-669">(バイト単位)、データ範囲の開始オフセット。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-669">The starting offset of the data range, in bytes.</span></span> <span data-ttu-id="8d0f4-670">512 の倍数である必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-670">Must be a multiple of 512.</span></span></param>
        <param name="length"><span data-ttu-id="8d0f4-671">(バイト単位)、データ範囲の長さ。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-671">The length of the data range, in bytes.</span></span> <span data-ttu-id="8d0f4-672">512 の倍数である必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-672">Must be a multiple of 512.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-673"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-673">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-674">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-674">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-675">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-675">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-676"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-676">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8d0f4-677">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-677">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-678">ページ範囲の開始と終了バイトのコレクションを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-678">Initiates an asynchronous operation to return a collection of page ranges and their starting and ending bytes.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-679">A<see cref="T:System.Threading.Tasks.Task`1" />型の列挙可能なコレクションであるオブジェクトを<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PageRange" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-679">A <see cref="T:System.Threading.Tasks.Task`1" /> object that is an enumerable collection of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.PageRange" /> that represents the asynchronous operation.</span></span></returns>
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
        <param name="previousSnapshotTime"><span data-ttu-id="8d0f4-680">A <see cref="T:System.DateTimeOffset" /> diff の開始点として使用する、スナップショットのタイムスタンプを表すこの CloudPageBlob を表す場合、スナップショット、previousSnapshotTime パラメーターは、現在のスナップショットのタイムスタンプより前でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-680">A <see cref="T:System.DateTimeOffset" /> representing the snapshot timestamp to use as the starting point for the diff. If this CloudPageBlob represents a snapshot, the previousSnapshotTime parameter must be prior to the current snapshot timestamp.</span></span></param>
        <param name="offset"><span data-ttu-id="8d0f4-681">するデータ範囲のリスト ページの範囲の開始オフセット (バイト単位)。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-681">The starting offset of the data range over which to list page ranges, in bytes.</span></span> <span data-ttu-id="8d0f4-682">512 の倍数である必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-682">Must be a multiple of 512.</span></span></param>
        <param name="length"><span data-ttu-id="8d0f4-683">リスト ページにどのデータ範囲の範囲の長さ (バイト単位)。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-683">The length of the data range over which to list page ranges, in bytes.</span></span> <span data-ttu-id="8d0f4-684">512 の倍数である必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-684">Must be a multiple of 512.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-685"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-685">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-686">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-686">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-687">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-687">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="8d0f4-688">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-688">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-689"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-689">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-690">このオブジェクトと指定したスナップショットの間で異なるページ範囲のコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-690">Gets the collection of page ranges that differ between a specified snapshot and this object.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-691">ページ範囲の列挙可能なコレクション。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-691">An enumerable collection of page ranges.</span></span></returns>
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
        <param name="previousSnapshotTime"><span data-ttu-id="8d0f4-692">A <see cref="T:System.DateTimeOffset" /> diff の開始点として使用する、スナップショットのタイムスタンプを表すこの CloudPageBlob を表す場合、スナップショット、previousSnapshotTime パラメーターは、現在のスナップショットのタイムスタンプより前でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-692">A <see cref="T:System.DateTimeOffset" /> representing the snapshot timestamp to use as the starting point for the diff. If this CloudPageBlob represents a snapshot, the previousSnapshotTime parameter must be prior to the current snapshot timestamp.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-693">指定したスナップショットとこのオブジェクトの間で異なるページ範囲のコレクションを取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-693">Initiates an asynchronous operation to return the collection of page ranges that differ between a specified snapshot and this object.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-694">A<see cref="T:System.Threading.Tasks.Task`1" />型の列挙可能なコレクションであるオブジェクトを<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PageRange" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-694">A <see cref="T:System.Threading.Tasks.Task`1" /> object that is an enumerable collection of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.PageRange" /> that represents the asynchronous operation.</span></span></returns>
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
        <param name="previousSnapshotTime"><span data-ttu-id="8d0f4-695">A <see cref="T:System.DateTimeOffset" /> diff の開始点として使用する、スナップショットのタイムスタンプを表すこの CloudPageBlob を表す場合、スナップショット、previousSnapshotTime パラメーターは、現在のスナップショットのタイムスタンプより前でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-695">A <see cref="T:System.DateTimeOffset" /> representing the snapshot timestamp to use as the starting point for the diff. If this CloudPageBlob represents a snapshot, the previousSnapshotTime parameter must be prior to the current snapshot timestamp.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8d0f4-696">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-696">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-697">指定したスナップショットとこのオブジェクトの間で異なるページ範囲のコレクションを取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-697">Initiates an asynchronous operation to return the collection of page ranges that differ between a specified snapshot and this object.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-698">A<see cref="T:System.Threading.Tasks.Task`1" />型の列挙可能なコレクションであるオブジェクトを<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PageRange" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-698">A <see cref="T:System.Threading.Tasks.Task`1" /> object that is an enumerable collection of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.PageRange" /> that represents the asynchronous operation.</span></span></returns>
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
        <param name="previousSnapshotTime"><span data-ttu-id="8d0f4-699">A <see cref="T:System.DateTimeOffset" /> diff の開始点として使用する、スナップショットのタイムスタンプを表すこの CloudPageBlob を表す場合、スナップショット、previousSnapshotTime パラメーターは、現在のスナップショットのタイムスタンプより前でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-699">A <see cref="T:System.DateTimeOffset" /> representing the snapshot timestamp to use as the starting point for the diff. If this CloudPageBlob represents a snapshot, the previousSnapshotTime parameter must be prior to the current snapshot timestamp.</span></span></param>
        <param name="offset"><span data-ttu-id="8d0f4-700">(バイト単位)、データ範囲の開始オフセット。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-700">The starting offset of the data range, in bytes.</span></span> <span data-ttu-id="8d0f4-701">512 の倍数である必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-701">Must be a multiple of 512.</span></span></param>
        <param name="length"><span data-ttu-id="8d0f4-702">(バイト単位)、データ範囲の長さ。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-702">The length of the data range, in bytes.</span></span> <span data-ttu-id="8d0f4-703">512 の倍数である必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-703">Must be a multiple of 512.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-704"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-704">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-705">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-705">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-706">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-706">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-707"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-707">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-708">指定したスナップショットとこのオブジェクトの間で異なるページ範囲のコレクションを取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-708">Initiates an asynchronous operation to return the collection of page ranges that differ between a specified snapshot and this object.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-709">A<see cref="T:System.Threading.Tasks.Task`1" />型の列挙可能なコレクションであるオブジェクトを<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PageRange" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-709">A <see cref="T:System.Threading.Tasks.Task`1" /> object that is an enumerable collection of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.PageRange" /> that represents the asynchronous operation.</span></span></returns>
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
        <param name="previousSnapshotTime"><span data-ttu-id="8d0f4-710">A <see cref="T:System.DateTimeOffset" /> diff の開始点として使用する、スナップショットのタイムスタンプを表すこの CloudPageBlob を表す場合、スナップショット、previousSnapshotTime パラメーターは、現在のスナップショットのタイムスタンプより前でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-710">A <see cref="T:System.DateTimeOffset" /> representing the snapshot timestamp to use as the starting point for the diff. If this CloudPageBlob represents a snapshot, the previousSnapshotTime parameter must be prior to the current snapshot timestamp.</span></span></param>
        <param name="offset"><span data-ttu-id="8d0f4-711">(バイト単位)、データ範囲の開始オフセット。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-711">The starting offset of the data range, in bytes.</span></span> <span data-ttu-id="8d0f4-712">512 の倍数である必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-712">Must be a multiple of 512.</span></span></param>
        <param name="length"><span data-ttu-id="8d0f4-713">(バイト単位)、データ範囲の長さ。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-713">The length of the data range, in bytes.</span></span> <span data-ttu-id="8d0f4-714">512 の倍数である必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-714">Must be a multiple of 512.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-715"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-715">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-716">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-716">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-717">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-717">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-718"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-718">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8d0f4-719">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-719">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-720">指定したスナップショットとこのオブジェクトの間で異なるページ範囲のコレクションを取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-720">Initiates an asynchronous operation to return the collection of page ranges that differ between a specified snapshot and this object.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-721">A<see cref="T:System.Threading.Tasks.Task`1" />型の列挙可能なコレクションであるオブジェクトを<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PageRange" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-721">A <see cref="T:System.Threading.Tasks.Task`1" /> object that is an enumerable collection of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.PageRange" /> that represents the asynchronous operation.</span></span></returns>
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
        <param name="size"><span data-ttu-id="8d0f4-722">(バイト単位)、ページ blob のサイズ。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-722">The size of the page blob, in bytes.</span></span> <span data-ttu-id="8d0f4-723">サイズは 512 の倍数である必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-723">The size must be a multiple of 512.</span></span> <span data-ttu-id="8d0f4-724">場合<c>null</c>、ページ blob が既に存在する必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-724">If <c>null</c>, the page blob must already exist.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-725"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-725">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-726">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-726">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-727">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-727">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="8d0f4-728">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-728">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-729"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-729">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-730">Blob に書き込むためのストリームを開きます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-730">Opens a stream for writing to the blob.</span></span> <span data-ttu-id="8d0f4-731">Blob が既に存在する場合は、blob 内の既存のデータが上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-731">If the blob already exists, then existing data in the blob may be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-732"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-732">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" /> object.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="8d0f4-733">このメソッドへの呼び出しを常に、注意してください、<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributes(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />内部的メソッドです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-733">Note that this method always makes a call to the <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributes(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" /> method under the covers.</span></span></para>
          <para><span data-ttu-id="8d0f4-734">設定、 <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.StreamWriteSizeInBytes" /> mb 16 KB と 4 MB までの範囲のバイトの書き込みは、ブロック サイズを指定するには、このメソッドを呼び出す前に、プロパティです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-734">Set the <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.StreamWriteSizeInBytes" /> property before calling this method to specify the block size to write, in bytes, ranging from between 16 KB and 4 MB inclusive.</span></span></para>
          <para><span data-ttu-id="8d0f4-735">これを上書きする代わりに blob が存在する場合は、例外をスロー、渡す、<see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />オブジェクトを使用して生成<see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />です。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-735">To throw an exception if the blob exists instead of overwriting it, pass in an <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object generated using <see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />.</span></span></para>
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
        <param name="size"><span data-ttu-id="8d0f4-736">(バイト単位)、ページ blob のサイズ。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-736">The size of the page blob, in bytes.</span></span> <span data-ttu-id="8d0f4-737">サイズは 512 の倍数である必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-737">The size must be a multiple of 512.</span></span> <span data-ttu-id="8d0f4-738">場合<c>null</c>、ページ blob が既に存在する必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-738">If <c>null</c>, the page blob must already exist.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-739">Blob に書き込むためのストリームを開く非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-739">Initiates an asynchronous operation to open a stream for writing to the blob.</span></span> <span data-ttu-id="8d0f4-740">Blob が既に存在する場合は、blob 内の既存のデータが上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-740">If the blob already exists, then existing data in the blob may be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-741">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-741">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="8d0f4-742">このメソッドへの呼び出しを常に、注意してください、<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributesAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />内部的メソッドです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-742">Note that this method always makes a call to the <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributesAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" /> method under the covers.</span></span></para>
          <para><span data-ttu-id="8d0f4-743">設定、<see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.StreamWriteSizeInBytes" />書き込み mb 包括的な 512 ~ 4 MB までの範囲の 512 バイトの倍数では、ページ サイズを指定するには、このメソッドを呼び出す前に、プロパティです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-743">Set the <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.StreamWriteSizeInBytes" /> property before calling this method to specify the page size to write, in multiples of 512 bytes, ranging from between 512 and 4 MB inclusive.</span></span></para>
          <para><span data-ttu-id="8d0f4-744">例外をスローする、上書きすることではなく、blob が存在する場合は、次を参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.OpenWriteAsync(System.Nullable{System.Int64},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />です。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-744">To throw an exception if the blob exists instead of overwriting it, see <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.OpenWriteAsync(System.Nullable{System.Int64},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />.</span></span></para>
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
        <param name="size"><span data-ttu-id="8d0f4-745">(バイト単位)、ページ blob のサイズ。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-745">The size of the page blob, in bytes.</span></span> <span data-ttu-id="8d0f4-746">サイズは 512 の倍数である必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-746">The size must be a multiple of 512.</span></span> <span data-ttu-id="8d0f4-747">場合<c>null</c>、ページ blob が既に存在する必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-747">If <c>null</c>, the page blob must already exist.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8d0f4-748">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-748">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-749">Blob に書き込むためのストリームを開く非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-749">Initiates an asynchronous operation to open a stream for writing to the blob.</span></span> <span data-ttu-id="8d0f4-750">Blob が既に存在する場合は、blob 内の既存のデータが上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-750">If the blob already exists, then existing data in the blob may be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-751">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-751">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="8d0f4-752">このメソッドへの呼び出しを常に、注意してください、<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributesAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />内部的メソッドです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-752">Note that this method always makes a call to the <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributesAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" /> method under the covers.</span></span></para>
          <para><span data-ttu-id="8d0f4-753">設定、<see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.StreamWriteSizeInBytes" />書き込み mb 包括的な 512 ~ 4 MB までの範囲の 512 バイトの倍数では、ページ サイズを指定するには、このメソッドを呼び出す前に、プロパティです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-753">Set the <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.StreamWriteSizeInBytes" /> property before calling this method to specify the page size to write, in multiples of 512 bytes, ranging from between 512 and 4 MB inclusive.</span></span></para>
          <para><span data-ttu-id="8d0f4-754">例外をスローする、上書きすることではなく、blob が存在する場合は、次を参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.OpenWriteAsync(System.Nullable{System.Int64},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-754">To throw an exception if the blob exists instead of overwriting it, see <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.OpenWriteAsync(System.Nullable{System.Int64},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />.</span></span></para>
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
        <param name="size"><span data-ttu-id="8d0f4-755">(バイト単位)、ページ blob のサイズ。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-755">The size of the page blob, in bytes.</span></span> <span data-ttu-id="8d0f4-756">サイズは 512 の倍数である必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-756">The size must be a multiple of 512.</span></span> <span data-ttu-id="8d0f4-757">場合<c>null</c>、ページ blob が既に存在する必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-757">If <c>null</c>, the page blob must already exist.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-758"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-758">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-759">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-759">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-760">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-760">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-761"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-761">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-762">Blob に書き込むためのストリームを開く非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-762">Initiates an asynchronous operation to open a stream for writing to the blob.</span></span> <span data-ttu-id="8d0f4-763">Blob が既に存在する場合は、blob 内の既存のデータが上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-763">If the blob already exists, then existing data in the blob may be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-764">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-764">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="8d0f4-765">このメソッドへの呼び出しを常に、注意してください、<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributesAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />内部的メソッドです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-765">Note that this method always makes a call to the <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributesAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" /> method under the covers.</span></span></para>
          <para><span data-ttu-id="8d0f4-766">設定、<see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.StreamWriteSizeInBytes" />書き込み mb 包括的な 512 ~ 4 MB までの範囲の 512 バイトの倍数では、ページ サイズを指定するには、このメソッドを呼び出す前に、プロパティです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-766">Set the <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.StreamWriteSizeInBytes" /> property before calling this method to specify the page size to write, in multiples of 512 bytes, ranging from between 512 and 4 MB inclusive.</span></span></para>
          <para><span data-ttu-id="8d0f4-767">これを上書きする代わりに blob が存在する場合は、例外をスロー、渡す、<see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />オブジェクトを使用して生成<see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />です。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-767">To throw an exception if the blob exists instead of overwriting it, pass in an <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object generated using <see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />.</span></span></para>
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
        <param name="size"><span data-ttu-id="8d0f4-768">(バイト単位)、ページ blob のサイズ。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-768">The size of the page blob, in bytes.</span></span> <span data-ttu-id="8d0f4-769">サイズは 512 の倍数である必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-769">The size must be a multiple of 512.</span></span> <span data-ttu-id="8d0f4-770">場合<c>null</c>、ページ blob が既に存在する必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-770">If <c>null</c>, the page blob must already exist.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-771"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-771">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-772">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-772">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-773">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-773">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-774"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-774">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8d0f4-775">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-775">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-776">Blob に書き込むためのストリームを開く非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-776">Initiates an asynchronous operation to open a stream for writing to the blob.</span></span> <span data-ttu-id="8d0f4-777">Blob が既に存在する場合は、blob 内の既存のデータが上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-777">If the blob already exists, then existing data in the blob may be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-778">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-778">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="8d0f4-779">このメソッドへの呼び出しを常に、注意してください、<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributesAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />内部的メソッドです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-779">Note that this method always makes a call to the <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributesAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" /> method under the covers.</span></span></para>
          <para><span data-ttu-id="8d0f4-780">設定、<see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.StreamWriteSizeInBytes" />書き込み mb 包括的な 512 ~ 4 MB までの範囲の 512 バイトの倍数では、ページ サイズを指定するには、このメソッドを呼び出す前に、プロパティです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-780">Set the <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob.StreamWriteSizeInBytes" /> property before calling this method to specify the page size to write, in multiples of 512 bytes, ranging from between 512 and 4 MB inclusive.</span></span></para>
          <para><span data-ttu-id="8d0f4-781">これを上書きする代わりに blob が存在する場合は、例外をスロー、渡す、<see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />オブジェクトを使用して生成<see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />です。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-781">To throw an exception if the blob exists instead of overwriting it, pass in an <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object generated using <see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />.</span></span></para>
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
        <param name="size"><span data-ttu-id="8d0f4-782">(バイト単位)、ページ blob のサイズ。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-782">The size of the page blob, in bytes.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-783"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-783">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-784">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-784">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-785">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-785">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="8d0f4-786">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-786">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-787"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-787">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-788">指定されたサイズにページ blob のサイズを変更します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-788">Resizes the page blob to the specified size.</span></span>
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
        <param name="size"><span data-ttu-id="8d0f4-789">(バイト単位)、blob のサイズ。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-789">The size of the blob, in bytes.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-790">指定されたサイズにページ blob のサイズを変更する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-790">Initiates an asynchronous operation to resize the page blob to the specified size.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-791">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-791">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
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
        <param name="size"><span data-ttu-id="8d0f4-792">(バイト単位)、blob のサイズ。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-792">The size of the blob, in bytes.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8d0f4-793">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-793">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-794">指定されたサイズにページ blob のサイズを変更する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-794">Initiates an asynchronous operation to resize the page blob to the specified size.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-795">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-795">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
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
        <param name="size"><span data-ttu-id="8d0f4-796">(バイト単位)、blob のサイズ。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-796">The size of the blob, in bytes.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-797"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-797">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-798">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-798">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-799">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-799">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-800"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-800">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-801">指定されたサイズにページ blob のサイズを変更する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-801">Initiates an asynchronous operation to resize the page blob to the specified size.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-802">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-802">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
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
        <param name="size"><span data-ttu-id="8d0f4-803">(バイト単位)、blob のサイズ。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-803">The size of the blob, in bytes.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-804"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-804">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-805">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-805">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-806">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-806">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-807"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-807">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8d0f4-808">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-808">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-809">指定されたサイズにページ blob のサイズを変更する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-809">Initiates an asynchronous operation to resize the page blob to the specified size.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-810">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-810">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
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
        <param name="premiumPageBlobTier"><span data-ttu-id="8d0f4-811">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-811">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" /> representing the tier to set.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-812">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> 、要求の追加オプションを指定するオブジェクトまたは<c>null</c>です。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-812">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request, or <c>null</c>.</span></span> <span data-ttu-id="8d0f4-813">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-813">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-814"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-814">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-815">Premium blob の層を設定します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-815">Sets the tier of the premium blob.</span></span>
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
        <param name="premiumPageBlobTier"><span data-ttu-id="8d0f4-816">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-816">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" /> representing the tier to set.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-817">Premium blob の層に設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-817">Initiates an asynchronous operation to set the tier of the premium blob.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-818">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-818">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
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
        <param name="premiumPageBlobTier"><span data-ttu-id="8d0f4-819">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-819">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" /> representing the tier to set.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8d0f4-820">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-820">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-821">Premium blob の層に設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-821">Initiates an asynchronous operation to set the tier of the premium blob.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-822">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-822">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
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
        <param name="premiumPageBlobTier"><span data-ttu-id="8d0f4-823">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-823">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" /> representing the tier to set.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-824">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-824">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-825"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-825">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-826">Premium blob の層に設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-826">Initiates an asynchronous operation to set the tier of the premium blob.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-827">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-827">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
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
        <param name="premiumPageBlobTier"><span data-ttu-id="8d0f4-828">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-828">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" /> representing the tier to set.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-829">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-829">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-830"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-830">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8d0f4-831">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-831">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-832">Blob の premium 階層を設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-832">Initiates an asynchronous operation to set the premium tier of the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-833">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-833">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
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
        <param name="sequenceNumberAction"><span data-ttu-id="8d0f4-834">型の値<see cref="T:Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction" />、シーケンス番号に対して実行する操作を示すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-834">A value of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction" />, indicating the operation to perform on the sequence number.</span></span></param>
        <param name="sequenceNumber"><span data-ttu-id="8d0f4-835">シーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-835">The sequence number.</span></span> <span data-ttu-id="8d0f4-836">このパラメーターに設定<c>null</c>場合<paramref name="sequenceNumberAction" />と等しい<see cref="F:SequenceNumberAction.Increment" />です。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-836">Set this parameter to <c>null</c> if <paramref name="sequenceNumberAction" /> is equal to <see cref="F:SequenceNumberAction.Increment" />.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-837"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-837">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-838">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-838">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-839">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-839">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="8d0f4-840">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-840">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-841"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-841">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-842">ページ blob のシーケンス番号を設定します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-842">Sets the page blob's sequence number.</span></span>
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
        <param name="sequenceNumberAction"><span data-ttu-id="8d0f4-843">型の値<see cref="T:Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction" />、シーケンス番号に対して実行する操作を示すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-843">A value of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction" />, indicating the operation to perform on the sequence number.</span></span></param>
        <param name="sequenceNumber"><span data-ttu-id="8d0f4-844">シーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-844">The sequence number.</span></span> <span data-ttu-id="8d0f4-845">このパラメーターに設定<c>null</c>場合<paramref name="sequenceNumberAction" />と等しい<see cref="F:SequenceNumberAction.Increment" />です。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-845">Set this parameter to <c>null</c> if <paramref name="sequenceNumberAction" /> is equal to <see cref="F:SequenceNumberAction.Increment" />.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-846">ページ blob のシーケンス番号を設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-846">Initiates an asynchronous operation to set the page blob's sequence number.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-847">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-847">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
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
        <param name="sequenceNumberAction"><span data-ttu-id="8d0f4-848">型の値<see cref="T:Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction" />、シーケンス番号に対して実行する操作を示すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-848">A value of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction" />, indicating the operation to perform on the sequence number.</span></span></param>
        <param name="sequenceNumber"><span data-ttu-id="8d0f4-849">シーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-849">The sequence number.</span></span> <span data-ttu-id="8d0f4-850">このパラメーターに設定<c>null</c>場合<paramref name="sequenceNumberAction" />と等しい<see cref="F:SequenceNumberAction.Increment" />です。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-850">Set this parameter to <c>null</c> if <paramref name="sequenceNumberAction" /> is equal to <see cref="F:SequenceNumberAction.Increment" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8d0f4-851">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-851">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-852">ページ blob のシーケンス番号を設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-852">Initiates an asynchronous operation to set the page blob's sequence number.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-853">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-853">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
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
        <param name="sequenceNumberAction"><span data-ttu-id="8d0f4-854">型の値<see cref="T:Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction" />、シーケンス番号に対して実行する操作を示すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-854">A value of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction" />, indicating the operation to perform on the sequence number.</span></span></param>
        <param name="sequenceNumber"><span data-ttu-id="8d0f4-855">シーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-855">The sequence number.</span></span> <span data-ttu-id="8d0f4-856">このパラメーターに設定<c>null</c>場合<paramref name="sequenceNumberAction" />と等しい<see cref="F:SequenceNumberAction.Increment" />です。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-856">Set this parameter to <c>null</c> if <paramref name="sequenceNumberAction" /> is equal to <see cref="F:SequenceNumberAction.Increment" />.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-857"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-857">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-858">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-858">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-859">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-859">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-860"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-860">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-861">ページ blob のシーケンス番号を設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-861">Initiates an asynchronous operation to set the page blob's sequence number.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-862">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-862">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
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
        <param name="sequenceNumberAction"><span data-ttu-id="8d0f4-863">型の値<see cref="T:Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction" />、シーケンス番号に対して実行する操作を示すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-863">A value of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction" />, indicating the operation to perform on the sequence number.</span></span></param>
        <param name="sequenceNumber"><span data-ttu-id="8d0f4-864">シーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-864">The sequence number.</span></span> <span data-ttu-id="8d0f4-865">このパラメーターに設定<c>null</c>場合<paramref name="sequenceNumberAction" />と等しい<see cref="F:SequenceNumberAction.Increment" />です。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-865">Set this parameter to <c>null</c> if <paramref name="sequenceNumberAction" /> is equal to <see cref="F:SequenceNumberAction.Increment" />.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-866"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-866">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-867">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-867">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-868">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-868">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-869"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-869">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8d0f4-870">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-870">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-871">ページ blob のシーケンス番号を設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-871">Initiates an asynchronous operation to set the page blob's sequence number.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-872">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-872">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
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
        <param name="source"><span data-ttu-id="8d0f4-873"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />コピー元 blob はします。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-873">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" /> that is the source blob.</span></span></param>
        <param name="sourceAccessCondition"><span data-ttu-id="8d0f4-874"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー元 blob のアクセス条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-874">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the source blob.</span></span> <span data-ttu-id="8d0f4-875">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-875">If <c>null</c>, no condition is used.</span></span></param>
        <param name="destAccessCondition"><span data-ttu-id="8d0f4-876"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー先 blob のアクセス条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-876">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the destination blob.</span></span> <span data-ttu-id="8d0f4-877">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-877">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-878">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-878">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="8d0f4-879">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-879">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-880"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-880">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-881">このページ blob に別のページ blob の内容、プロパティ、およびメタデータのコピーを開始するための操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-881">Begins an operation to start copying another page blob's contents, properties, and metadata to this page blob.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-882">コピー操作に関連付けられたコピー ID です。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-882">The copy ID associated with the copy operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="8d0f4-883">このメソッドは、blob の ETag、最終更新時刻、および一部のコピー状態をフェッチします。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-883">This method fetches the blob's ETag, last-modified time, and part of the copy state.</span></span>
            <span data-ttu-id="8d0f4-884">コピー ID とコピーのステータス フィールドがフェッチされ、残りのコピーの状態がクリアされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-884">The copy ID and copy status fields are fetched, and the rest of the copy state is cleared.</span></span>
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
        <param name="source"><span data-ttu-id="8d0f4-885"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />コピー元 blob はします。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-885">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" /> that is the source blob.</span></span></param>
        <param name="premiumPageBlobTier"><span data-ttu-id="8d0f4-886">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-886">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" /> representing the tier to set.</span></span></param>
        <param name="sourceAccessCondition"><span data-ttu-id="8d0f4-887"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー元 blob のアクセス条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-887">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the source blob.</span></span> <span data-ttu-id="8d0f4-888">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-888">If <c>null</c>, no condition is used.</span></span></param>
        <param name="destAccessCondition"><span data-ttu-id="8d0f4-889"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー先 blob のアクセス条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-889">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the destination blob.</span></span> <span data-ttu-id="8d0f4-890">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-890">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-891">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-891">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="8d0f4-892">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-892">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-893"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-893">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-894">このページ blob に別のページ blob の内容、プロパティ、およびメタデータのコピーを開始するための操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-894">Begins an operation to start copying another page blob's contents, properties, and metadata to this page blob.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-895">コピー操作に関連付けられたコピー ID です。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-895">The copy ID associated with the copy operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="8d0f4-896">このメソッドは、blob の ETag、最終更新時刻、および一部のコピー状態をフェッチします。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-896">This method fetches the blob's ETag, last-modified time, and part of the copy state.</span></span>
            <span data-ttu-id="8d0f4-897">コピー ID とコピーのステータス フィールドがフェッチされ、残りのコピーの状態がクリアされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-897">The copy ID and copy status fields are fetched, and the rest of the copy state is cleared.</span></span>
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
        <param name="source"><span data-ttu-id="8d0f4-898"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />コピー元 blob はします。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-898">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" /> that is the source blob.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-899">このページ blob に別の blob の内容、プロパティ、およびメタデータのコピーを開始する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-899">Initiates an asynchronous operation to start copying another blob's contents, properties, and metadata to this page blob.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-900">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>文字列</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-900">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>string</c> that represents the asynchronous operation.</span></span></returns>
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
        <param name="source"><span data-ttu-id="8d0f4-901"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />コピー元 blob はします。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-901">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" /> that is the source blob.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8d0f4-902">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-902">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-903">このページ blob に別の blob の内容、プロパティ、およびメタデータのコピーを開始する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-903">Initiates an asynchronous operation to start copying another blob's contents, properties, and metadata to this page blob.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-904">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>文字列</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-904">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>string</c> that represents the asynchronous operation.</span></span></returns>
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
        <param name="source"><span data-ttu-id="8d0f4-905"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />コピー元 blob はします。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-905">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" /> that is the source blob.</span></span></param>
        <param name="sourceAccessCondition"><span data-ttu-id="8d0f4-906"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー元 blob のアクセス条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-906">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the source blob.</span></span> <span data-ttu-id="8d0f4-907">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-907">If <c>null</c>, no condition is used.</span></span></param>
        <param name="destAccessCondition"><span data-ttu-id="8d0f4-908"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー先 blob のアクセス条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-908">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the destination blob.</span></span> <span data-ttu-id="8d0f4-909">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-909">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-910">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-910">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-911"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-911">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-912">このページ blob に別の blob の内容、プロパティ、およびメタデータのコピーを開始する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-912">Initiates an asynchronous operation to start copying another blob's contents, properties, and metadata to this page blob.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-913">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>文字列</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-913">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>string</c> that represents the asynchronous operation.</span></span></returns>
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
        <param name="source"><span data-ttu-id="8d0f4-914"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />コピー元 blob はします。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-914">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" /> that is the source blob.</span></span></param>
        <param name="sourceAccessCondition"><span data-ttu-id="8d0f4-915"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー元 blob のアクセス条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-915">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the source blob.</span></span> <span data-ttu-id="8d0f4-916">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-916">If <c>null</c>, no condition is used.</span></span></param>
        <param name="destAccessCondition"><span data-ttu-id="8d0f4-917"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー先 blob のアクセス条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-917">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the destination blob.</span></span> <span data-ttu-id="8d0f4-918">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-918">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-919">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-919">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-920"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-920">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8d0f4-921">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-921">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-922">このページ blob に別の blob の内容、プロパティ、およびメタデータのコピーを開始する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-922">Initiates an asynchronous operation to start copying another blob's contents, properties, and metadata to this page blob.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-923">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>文字列</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-923">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>string</c> that represents the asynchronous operation.</span></span></returns>
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
        <param name="source"><span data-ttu-id="8d0f4-924"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />コピー元 blob はします。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-924">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" /> that is the source blob.</span></span></param>
        <param name="premiumPageBlobTier"><span data-ttu-id="8d0f4-925">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-925">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" /> representing the tier to set.</span></span></param>
        <param name="sourceAccessCondition"><span data-ttu-id="8d0f4-926"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー元 blob のアクセス条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-926">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the source blob.</span></span> <span data-ttu-id="8d0f4-927">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-927">If <c>null</c>, no condition is used.</span></span></param>
        <param name="destAccessCondition"><span data-ttu-id="8d0f4-928"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー先 blob のアクセス条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-928">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the destination blob.</span></span> <span data-ttu-id="8d0f4-929">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-929">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-930">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-930">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-931"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-931">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8d0f4-932">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-932">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-933">このページ blob に別の blob の内容、プロパティ、およびメタデータのコピーを開始する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-933">Initiates an asynchronous operation to start copying another blob's contents, properties, and metadata to this page blob.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-934">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>文字列</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-934">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>string</c> that represents the asynchronous operation.</span></span></returns>
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
        <param name="sourceSnapshot"><span data-ttu-id="8d0f4-935"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />コピー元 blob がスナップショットである必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-935">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" /> that is the source blob which must be a snapshot.</span></span></param>
        <param name="destAccessCondition"><span data-ttu-id="8d0f4-936"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー先 blob のアクセス条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-936">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the destination blob.</span></span> <span data-ttu-id="8d0f4-937">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-937">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-938">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-938">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="8d0f4-939">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-939">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-940"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-940">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-941">別のページ blob の内容、プロパティ、およびページ blob のメタデータの増分のコピーを開始するための操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-941">Begins an operation to start an incremental copy of another page blob's contents, properties, and metadata to this page blob.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-942">コピー操作に関連付けられたコピー ID です。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-942">The copy ID associated with the copy operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="8d0f4-943">このメソッドは、blob の ETag、最終更新時刻、および一部のコピー状態をフェッチします。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-943">This method fetches the blob's ETag, last-modified time, and part of the copy state.</span></span>
            <span data-ttu-id="8d0f4-944">コピー ID とコピーのステータス フィールドがフェッチされ、残りのコピーの状態がクリアされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-944">The copy ID and copy status fields are fetched, and the rest of the copy state is cleared.</span></span>
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
        <param name="sourceSnapshotUri"><span data-ttu-id="8d0f4-945"><see cref="T:System.Uri" />のコピー元 blob スナップショットをする必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-945">The <see cref="T:System.Uri" /> of the source blob which must be a snapshot.</span></span></param>
        <param name="destAccessCondition"><span data-ttu-id="8d0f4-946"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー先 blob のアクセス条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-946">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the destination blob.</span></span> <span data-ttu-id="8d0f4-947">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-947">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-948">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-948">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="8d0f4-949">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-949">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-950"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-950">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-951">別のページ blob の内容、プロパティ、およびページ blob のメタデータの増分のコピーを開始するための操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-951">Begins an operation to start an incremental copy of another page blob's contents, properties, and metadata to this page blob.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-952">コピー操作に関連付けられたコピー ID です。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-952">The copy ID associated with the copy operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="8d0f4-953">このメソッドは、blob の ETag、最終更新時刻、および一部のコピー状態をフェッチします。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-953">This method fetches the blob's ETag, last-modified time, and part of the copy state.</span></span>
            <span data-ttu-id="8d0f4-954">コピー ID とコピーのステータス フィールドがフェッチされ、残りのコピーの状態がクリアされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-954">The copy ID and copy status fields are fetched, and the rest of the copy state is cleared.</span></span>
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
        <param name="source"><span data-ttu-id="8d0f4-955"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />コピー元 blob がスナップショットである必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-955">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" /> that is the source blob which must be a snapshot.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-956">別の blob の内容、プロパティ、およびページ blob のメタデータの増分のコピーを開始する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-956">Initiates an asynchronous operation to start an incremental copy of another blob's contents, properties, and metadata to this page blob.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-957">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>文字列</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-957">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>string</c> that represents the asynchronous operation.</span></span></returns>
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
        <param name="source"><span data-ttu-id="8d0f4-958"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />コピー元 blob がスナップショットである必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-958">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" /> that is the source blob which must be a snapshot.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8d0f4-959">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-959">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-960">別の blob の内容、プロパティ、およびページ blob のメタデータの増分のコピーを開始する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-960">Initiates an asynchronous operation to start an incremental copy of another blob's contents, properties, and metadata to this page blob.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-961">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>文字列</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-961">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>string</c> that represents the asynchronous operation.</span></span></returns>
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
        <param name="source"><span data-ttu-id="8d0f4-962"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />コピー元 blob がスナップショットである必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-962">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" /> that is the source blob which must be a snapshot.</span></span></param>
        <param name="destAccessCondition"><span data-ttu-id="8d0f4-963"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー先 blob のアクセス条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-963">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the destination blob.</span></span> <span data-ttu-id="8d0f4-964">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-964">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-965">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-965">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-966"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-966">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8d0f4-967">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-967">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-968">別の blob の内容、プロパティ、およびページ blob のメタデータの増分のコピーを開始する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-968">Initiates an asynchronous operation to start an incremental copy of another blob's contents, properties, and metadata to this page blob.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-969">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>文字列</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-969">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>string</c> that represents the asynchronous operation.</span></span></returns>
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
            <span data-ttu-id="8d0f4-970">取得またはページ blob ストリームに書き込むときにバッファーに書き込むバイト数を設定します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-970">Gets or sets the number of bytes to buffer when writing to a page blob stream.</span></span>
            </summary>
        <value><span data-ttu-id="8d0f4-971">バッファーに mb 512 バイトと 4 MB までのバイト数。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-971">The number of bytes to buffer, ranging from between 512 bytes and 4 MB inclusive.</span></span></value>
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
        <param name="buffer"><span data-ttu-id="8d0f4-972">バイト配列。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-972">An array of bytes.</span></span></param>
        <param name="index"><span data-ttu-id="8d0f4-973">Blob のバイトのアップロードを開始位置を示すバッファー内の 0 から始まるバイト オフセット。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-973">The zero-based byte offset in buffer at which to begin uploading bytes to the blob.</span></span></param>
        <param name="count"><span data-ttu-id="8d0f4-974">Blob に書き込まれるバイト数。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-974">The number of bytes to be written to the blob.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-975"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-975">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-976">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-976">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="8d0f4-977">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-977">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-978"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-978">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-979">バイト配列の内容をページ blob にアップロードします。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-979">Uploads the contents of a byte array to a page blob.</span></span> <span data-ttu-id="8d0f4-980">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-980">If the blob already exists, it will be overwritten.</span></span>
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
        <param name="buffer"><span data-ttu-id="8d0f4-981">バイト配列。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-981">An array of bytes.</span></span></param>
        <param name="index"><span data-ttu-id="8d0f4-982">Blob のバイトのアップロードを開始位置を示すバッファー内の 0 から始まるバイト オフセット。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-982">The zero-based byte offset in buffer at which to begin uploading bytes to the blob.</span></span></param>
        <param name="count"><span data-ttu-id="8d0f4-983">Blob に書き込まれるバイト数。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-983">The number of bytes to be written to the blob.</span></span></param>
        <param name="premiumPageBlobTier"><span data-ttu-id="8d0f4-984">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-984">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" /> representing the tier to set.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-985"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-985">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-986">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-986">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="8d0f4-987">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-987">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-988"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-988">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-989">バイト配列の内容をページ blob にアップロードします。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-989">Uploads the contents of a byte array to a page blob.</span></span> <span data-ttu-id="8d0f4-990">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-990">If the blob already exists, it will be overwritten.</span></span>
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
        <param name="buffer"><span data-ttu-id="8d0f4-991">バイト配列。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-991">An array of bytes.</span></span></param>
        <param name="index"><span data-ttu-id="8d0f4-992">Blob のバイトのアップロードを開始位置を示すバッファー内の 0 から始まるバイト オフセット。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-992">The zero-based byte offset in buffer at which to begin uploading bytes to the blob.</span></span></param>
        <param name="count"><span data-ttu-id="8d0f4-993">Blob に書き込まれるバイト数。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-993">The number of bytes to be written to the blob.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-994">バイト配列の内容をページ blob にアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-994">Initiates an asynchronous operation to upload the contents of a byte array to a page blob.</span></span> <span data-ttu-id="8d0f4-995">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-995">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-996">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-996">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
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
        <param name="buffer"><span data-ttu-id="8d0f4-997">バイト配列。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-997">An array of bytes.</span></span></param>
        <param name="index"><span data-ttu-id="8d0f4-998">Blob のバイトのアップロードを開始位置を示すバッファー内の 0 から始まるバイト オフセット。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-998">The zero-based byte offset in buffer at which to begin uploading bytes to the blob.</span></span></param>
        <param name="count"><span data-ttu-id="8d0f4-999">Blob に書き込まれるバイト数。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-999">The number of bytes to be written to the blob.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8d0f4-1000">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1000">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-1001">バイト配列の内容をページ blob にアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1001">Initiates an asynchronous operation to upload the contents of a byte array to a page blob.</span></span> <span data-ttu-id="8d0f4-1002">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1002">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-1003">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1003">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
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
        <param name="buffer"><span data-ttu-id="8d0f4-1004">バイト配列。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1004">An array of bytes.</span></span></param>
        <param name="index"><span data-ttu-id="8d0f4-1005">Blob のバイトのアップロードを開始位置を示すバッファー内の 0 から始まるバイト オフセット。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1005">The zero-based byte offset in buffer at which to begin uploading bytes to the blob.</span></span></param>
        <param name="count"><span data-ttu-id="8d0f4-1006">Blob に書き込まれるバイト数。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1006">The number of bytes to be written to the blob.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-1007"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1007">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-1008">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1008">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-1009"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1009">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-1010">バイト配列の内容をページ blob にアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1010">Initiates an asynchronous operation to upload the contents of a byte array to a page blob.</span></span> <span data-ttu-id="8d0f4-1011">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1011">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-1012">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1012">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
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
        <param name="buffer"><span data-ttu-id="8d0f4-1013">バイト配列。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1013">An array of bytes.</span></span></param>
        <param name="index"><span data-ttu-id="8d0f4-1014">Blob のバイトのアップロードを開始位置を示すバッファー内の 0 から始まるバイト オフセット。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1014">The zero-based byte offset in buffer at which to begin uploading bytes to the blob.</span></span></param>
        <param name="count"><span data-ttu-id="8d0f4-1015">Blob に書き込まれるバイト数。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1015">The number of bytes to be written to the blob.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-1016"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1016">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-1017">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1017">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-1018"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1018">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8d0f4-1019">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1019">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-1020">バイト配列の内容をページ blob にアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1020">Initiates an asynchronous operation to upload the contents of a byte array to a page blob.</span></span> <span data-ttu-id="8d0f4-1021">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1021">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-1022">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1022">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
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
        <param name="buffer"><span data-ttu-id="8d0f4-1023">バイト配列。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1023">An array of bytes.</span></span></param>
        <param name="index"><span data-ttu-id="8d0f4-1024">Blob のバイトのアップロードを開始位置を示すバッファー内の 0 から始まるバイト オフセット。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1024">The zero-based byte offset in buffer at which to begin uploading bytes to the blob.</span></span></param>
        <param name="count"><span data-ttu-id="8d0f4-1025">Blob に書き込まれるバイト数。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1025">The number of bytes to be written to the blob.</span></span></param>
        <param name="premiumPageBlobTier"><span data-ttu-id="8d0f4-1026">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1026">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" /> representing the tier to set.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-1027"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1027">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-1028">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1028">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-1029"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1029">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8d0f4-1030">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1030">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-1031">バイト配列の内容をページ blob にアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1031">Initiates an asynchronous operation to upload the contents of a byte array to a page blob.</span></span> <span data-ttu-id="8d0f4-1032">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1032">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-1033">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1033">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
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
        <param name="buffer"><span data-ttu-id="8d0f4-1034">バイト配列。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1034">An array of bytes.</span></span></param>
        <param name="index"><span data-ttu-id="8d0f4-1035">Blob のバイトのアップロードを開始位置を示すバッファー内の 0 から始まるバイト オフセット。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1035">The zero-based byte offset in buffer at which to begin uploading bytes to the blob.</span></span></param>
        <param name="count"><span data-ttu-id="8d0f4-1036">Blob に書き込まれるバイト数。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1036">The number of bytes to be written to the blob.</span></span></param>
        <param name="premiumPageBlobTier"><span data-ttu-id="8d0f4-1037">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1037">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" /> representing the tier to set.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-1038"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1038">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-1039">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1039">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-1040"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1040">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="progressHandler"> <span data-ttu-id="8d0f4-1041">A<see cref="T:System.IProgress`1" />を処理するオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" />メッセージ。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1041">A <see cref="T:System.IProgress`1" /> object to handle <see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" /> messages.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8d0f4-1042">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1042">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-1043">バイト配列の内容をページ blob にアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1043">Initiates an asynchronous operation to upload the contents of a byte array to a page blob.</span></span> <span data-ttu-id="8d0f4-1044">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1044">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-1045">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1045">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
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
        <param name="path"><span data-ttu-id="8d0f4-1046">Blob コンテンツを提供するファイルのパスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1046">A string containing the file path providing the blob content.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-1047"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1047">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-1048">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1048">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="8d0f4-1049">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1049">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-1050"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1050">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-1051">ページ blob にファイルをアップロードします。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1051">Uploads a file to a page blob.</span></span> <span data-ttu-id="8d0f4-1052">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1052">If the blob already exists, it will be overwritten.</span></span>
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
        <param name="path"><span data-ttu-id="8d0f4-1053">Blob コンテンツを提供するファイルのパスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1053">A string containing the file path providing the blob content.</span></span></param>
        <param name="premiumPageBlobTier"><span data-ttu-id="8d0f4-1054">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1054">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" /> representing the tier to set.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-1055"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1055">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-1056">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1056">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="8d0f4-1057">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1057">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-1058"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1058">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-1059">ページ blob にファイルをアップロードします。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1059">Uploads a file to a page blob.</span></span> <span data-ttu-id="8d0f4-1060">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1060">If the blob already exists, it will be overwritten.</span></span>
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
        <param name="path"><span data-ttu-id="8d0f4-1061">Blob コンテンツを提供するファイルのパスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1061">A string containing the file path providing the blob content.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-1062">ページ blob にファイルをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1062">Initiates an asynchronous operation to upload a file to a page blob.</span></span> <span data-ttu-id="8d0f4-1063">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1063">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-1064">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1064">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
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
        <param name="path"><span data-ttu-id="8d0f4-1065">Blob コンテンツを提供するファイルのパスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1065">A string containing the file path providing the blob content.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8d0f4-1066">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1066">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-1067">ページ blob にファイルをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1067">Initiates an asynchronous operation to upload a file to a page blob.</span></span> <span data-ttu-id="8d0f4-1068">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1068">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-1069">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1069">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
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
        <param name="path"><span data-ttu-id="8d0f4-1070">Blob コンテンツを提供するファイルのパスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1070">A string containing the file path providing the blob content.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-1071"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1071">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-1072">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1072">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-1073"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1073">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-1074">ページ blob にファイルをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1074">Initiates an asynchronous operation to upload a file to a page blob.</span></span> <span data-ttu-id="8d0f4-1075">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1075">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-1076">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1076">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
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
        <param name="path"><span data-ttu-id="8d0f4-1077">Blob コンテンツを提供するファイルのパスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1077">A string containing the file path providing the blob content.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-1078"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1078">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-1079">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1079">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-1080"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1080">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8d0f4-1081">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1081">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-1082">ページ blob にファイルをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1082">Initiates an asynchronous operation to upload a file to a page blob.</span></span> <span data-ttu-id="8d0f4-1083">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1083">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-1084">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1084">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
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
        <param name="path"><span data-ttu-id="8d0f4-1085">Blob コンテンツを提供するファイルのパスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1085">A string containing the file path providing the blob content.</span></span></param>
        <param name="premiumPageBlobTier"><span data-ttu-id="8d0f4-1086">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1086">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" /> representing the tier to set.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-1087"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1087">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-1088">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1088">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-1089"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1089">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8d0f4-1090">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1090">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-1091">ページ blob にファイルをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1091">Initiates an asynchronous operation to upload a file to a page blob.</span></span> <span data-ttu-id="8d0f4-1092">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1092">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-1093">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1093">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
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
        <param name="path"><span data-ttu-id="8d0f4-1094">Blob コンテンツを提供するファイルのパスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1094">A string containing the file path providing the blob content.</span></span></param>
        <param name="premiumPageBlobTier"><span data-ttu-id="8d0f4-1095">A<see cref="!:PageBlobTier" />を設定する層を表すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1095">A <see cref="!:PageBlobTier" /> representing the tier to set.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-1096"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1096">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-1097">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1097">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-1098"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1098">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="progressHandler"> <span data-ttu-id="8d0f4-1099">A<see cref="T:System.IProgress`1" />を処理するオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" />メッセージ。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1099">A <see cref="T:System.IProgress`1" /> object to handle <see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" /> messages.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8d0f4-1100">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1100">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-1101">ページ blob にファイルをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1101">Initiates an asynchronous operation to upload a file to a page blob.</span></span> <span data-ttu-id="8d0f4-1102">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1102">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-1103">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1103">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
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
        <param name="source"><span data-ttu-id="8d0f4-1104">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1104">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-1105"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1105">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-1106">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1106">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-1107">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1107">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="8d0f4-1108">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1108">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-1109"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1109">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-1110">ストリームをページ blob にアップロードします。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1110">Uploads a stream to a page blob.</span></span> <span data-ttu-id="8d0f4-1111">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1111">If the blob already exists, it will be overwritten.</span></span>
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
        <param name="source"><span data-ttu-id="8d0f4-1112">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1112">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="length"><span data-ttu-id="8d0f4-1113">現在の位置に、ソース ストリームから書き込むバイト数。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1113">The number of bytes to write from the source stream at its current position.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-1114"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1114">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-1115">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1115">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-1116">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1116">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="8d0f4-1117">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1117">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-1118"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1118">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-1119">ストリームをページ blob にアップロードします。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1119">Uploads a stream to a page blob.</span></span> <span data-ttu-id="8d0f4-1120">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1120">If the blob already exists, it will be overwritten.</span></span>
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
        <param name="source"><span data-ttu-id="8d0f4-1121">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1121">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="premiumPageBlobTier"><span data-ttu-id="8d0f4-1122">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1122">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" /> representing the tier to set.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-1123"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1123">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-1124">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1124">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-1125">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1125">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="8d0f4-1126">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1126">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-1127"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1127">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-1128">ストリームをページ blob にアップロードします。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1128">Uploads a stream to a page blob.</span></span> <span data-ttu-id="8d0f4-1129">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1129">If the blob already exists, it will be overwritten.</span></span>
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
        <param name="source"><span data-ttu-id="8d0f4-1130">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1130">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="length"><span data-ttu-id="8d0f4-1131">現在の位置に、ソース ストリームから書き込むバイト数。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1131">The number of bytes to write from the source stream at its current position.</span></span></param>
        <param name="premiumPageBlobTier"><span data-ttu-id="8d0f4-1132">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1132">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" /> representing the tier to set.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-1133"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1133">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-1134">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1134">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-1135">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1135">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="8d0f4-1136">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1136">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-1137"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1137">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-1138">ストリームをページ blob にアップロードします。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1138">Uploads a stream to a page blob.</span></span> <span data-ttu-id="8d0f4-1139">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1139">If the blob already exists, it will be overwritten.</span></span>
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
        <param name="source"><span data-ttu-id="8d0f4-1140">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1140">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-1141">ページ blob にストリームをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1141">Initiates an asynchronous operation to upload a stream to a page blob.</span></span> <span data-ttu-id="8d0f4-1142">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1142">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-1143">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1143">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
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
        <param name="source"><span data-ttu-id="8d0f4-1144">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1144">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="length"><span data-ttu-id="8d0f4-1145">現在の位置に、ソース ストリームから書き込むバイト数。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1145">The number of bytes to write from the source stream at its current position.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-1146">ページ blob にストリームをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1146">Initiates an asynchronous operation to upload a stream to a page blob.</span></span> <span data-ttu-id="8d0f4-1147">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1147">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-1148">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1148">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
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
        <param name="source"><span data-ttu-id="8d0f4-1149">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1149">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8d0f4-1150">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1150">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-1151">ページ blob にストリームをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1151">Initiates an asynchronous operation to upload a stream to a page blob.</span></span> <span data-ttu-id="8d0f4-1152">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1152">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-1153">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1153">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
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
        <param name="source"><span data-ttu-id="8d0f4-1154">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1154">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="length"><span data-ttu-id="8d0f4-1155">現在の位置に、ソース ストリームから書き込むバイト数。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1155">The number of bytes to write from the source stream at its current position.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8d0f4-1156">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1156">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-1157">ページ blob にストリームをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1157">Initiates an asynchronous operation to upload a stream to a page blob.</span></span> <span data-ttu-id="8d0f4-1158">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1158">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-1159">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1159">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
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
        <param name="source"><span data-ttu-id="8d0f4-1160">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1160">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-1161"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1161">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-1162">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1162">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-1163">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1163">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-1164"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1164">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-1165">ページ blob にストリームをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1165">Initiates an asynchronous operation to upload a stream to a page blob.</span></span> <span data-ttu-id="8d0f4-1166">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1166">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-1167">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1167">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
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
        <param name="source"><span data-ttu-id="8d0f4-1168">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1168">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-1169"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1169">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-1170">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1170">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-1171">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1171">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-1172"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1172">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8d0f4-1173">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1173">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-1174">ページ blob にストリームをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1174">Initiates an asynchronous operation to upload a stream to a page blob.</span></span> <span data-ttu-id="8d0f4-1175">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1175">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-1176">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1176">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
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
        <param name="source"><span data-ttu-id="8d0f4-1177">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1177">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="length"><span data-ttu-id="8d0f4-1178">現在の位置に、ソース ストリームから書き込むバイト数。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1178">The number of bytes to write from the source stream at its current position.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-1179"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1179">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-1180">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1180">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-1181">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1181">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-1182"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1182">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-1183">ページ blob にストリームをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1183">Initiates an asynchronous operation to upload a stream to a page blob.</span></span> <span data-ttu-id="8d0f4-1184">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1184">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-1185">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1185">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
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
        <param name="source"><span data-ttu-id="8d0f4-1186">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1186">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="length"><span data-ttu-id="8d0f4-1187">現在の位置に、ソース ストリームから書き込むバイト数。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1187">The number of bytes to write from the source stream at its current position.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-1188"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1188">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-1189">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1189">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-1190">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1190">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-1191"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1191">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8d0f4-1192">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1192">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-1193">ページ blob にストリームをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1193">Initiates an asynchronous operation to upload a stream to a page blob.</span></span> <span data-ttu-id="8d0f4-1194">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1194">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-1195">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1195">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
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
        <param name="source"><span data-ttu-id="8d0f4-1196">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1196">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="premiumPageBlobTier"><span data-ttu-id="8d0f4-1197">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1197">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" /> representing the tier to set.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-1198"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1198">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-1199">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1199">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-1200">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1200">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-1201"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1201">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8d0f4-1202">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1202">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-1203">ページ blob にストリームをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1203">Initiates an asynchronous operation to upload a stream to a page blob.</span></span> <span data-ttu-id="8d0f4-1204">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1204">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-1205">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1205">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
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
        <param name="source"><span data-ttu-id="8d0f4-1206">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1206">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="length"><span data-ttu-id="8d0f4-1207">現在の位置に、ソース ストリームから書き込むバイト数。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1207">The number of bytes to write from the source stream at its current position.</span></span></param>
        <param name="premiumPageBlobTier"><span data-ttu-id="8d0f4-1208">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1208">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" /> representing the tier to set.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-1209"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1209">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-1210">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1210">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-1211">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1211">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-1212"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1212">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8d0f4-1213">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1213">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-1214">ページ blob にストリームをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1214">Initiates an asynchronous operation to upload a stream to a page blob.</span></span> <span data-ttu-id="8d0f4-1215">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1215">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-1216">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1216">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
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
        <param name="source"><span data-ttu-id="8d0f4-1217">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1217">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="premiumPageBlobTier"><span data-ttu-id="8d0f4-1218">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1218">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" /> representing the tier to set.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-1219"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1219">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-1220">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1220">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-1221">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1221">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-1222"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1222">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="progressHandler"> <span data-ttu-id="8d0f4-1223">A<see cref="T:System.IProgress`1" />を処理するオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" />メッセージ。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1223">A <see cref="T:System.IProgress`1" /> object to handle <see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" /> messages.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8d0f4-1224">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1224">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-1225">ページ blob にストリームをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1225">Initiates an asynchronous operation to upload a stream to a page blob.</span></span> <span data-ttu-id="8d0f4-1226">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1226">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-1227">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1227">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
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
        <param name="source"><span data-ttu-id="8d0f4-1228">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1228">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="length"><span data-ttu-id="8d0f4-1229">現在の位置に、ソース ストリームから書き込むバイト数。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1229">The number of bytes to write from the source stream at its current position.</span></span></param>
        <param name="premiumPageBlobTier"><span data-ttu-id="8d0f4-1230">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1230">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" /> representing the tier to set.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-1231"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1231">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-1232">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1232">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-1233">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1233">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-1234"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1234">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="progressHandler"> <span data-ttu-id="8d0f4-1235">A<see cref="T:System.IProgress`1" />を処理するオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" />メッセージ。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1235">A <see cref="T:System.IProgress`1" /> object to handle <see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" /> messages.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8d0f4-1236">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1236">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-1237">ページ blob にストリームをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1237">Initiates an asynchronous operation to upload a stream to a page blob.</span></span> <span data-ttu-id="8d0f4-1238">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1238">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-1239">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1239">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
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
        <param name="pageData"><span data-ttu-id="8d0f4-1240">A<see cref="T:System.IO.Stream" />ページ データを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1240">A <see cref="T:System.IO.Stream" /> object providing the page data.</span></span></param>
        <param name="startOffset"><span data-ttu-id="8d0f4-1241">バイト単位での書き込みを開始するオフセットです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1241">The offset at which to begin writing, in bytes.</span></span> <span data-ttu-id="8d0f4-1242">オフセットは 512 の倍数である必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1242">The offset must be a multiple of 512.</span></span></param>
        <param name="contentMD5"><span data-ttu-id="8d0f4-1243">ページのトランザクションの整合性を確保するために使用する省略可能なハッシュ値です。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1243">An optional hash value used to ensure transactional integrity for the page.</span></span> <span data-ttu-id="8d0f4-1244">あります<c>null</c>または空の文字列。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1244">May be <c>null</c> or an empty string.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-1245"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1245">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-1246">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1246">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-1247">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1247">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="8d0f4-1248">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1248">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-1249"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1249">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-1250">ページ blob にページに書き込みます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1250">Writes pages to a page blob.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="8d0f4-1251">クライアントは、ネットワーク上でトランザクションの整合性を確保するための手段として特定のページの書き込み操作の content-md5 ヘッダーを送信できます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1251">Clients may send the Content-MD5 header for a given Write Pages operation as a means to ensure transactional integrity over the wire.</span></span> <span data-ttu-id="8d0f4-1252"><paramref name="contentMD5" />パラメーターにより、クライアントは、指定したバイトの範囲に提供することを事前に計算された MD5 値へのアクセスを既に持っています。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1252">The <paramref name="contentMD5" /> parameter permits clients who already have access to a pre-computed MD5 value for a given byte range to provide it.</span></span>
            <span data-ttu-id="8d0f4-1253">場合、<see cref="P:BlobRequestOptions.UseTransactionalMd5" />プロパティに設定されている<c>true</c>と<paramref name="contentMD5" />にパラメーターが設定されている<c>null</c>、クライアント ライブラリが MD5 値を内部で計算し、します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1253">If the <see cref="P:BlobRequestOptions.UseTransactionalMd5" /> property is set to <c>true</c> and the <paramref name="contentMD5" /> parameter is set to <c>null</c>, then the client library will calculate the MD5 value internally.</span></span>
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
        <param name="pageData"><span data-ttu-id="8d0f4-1254">A<see cref="T:System.IO.Stream" />ページ データを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1254">A <see cref="T:System.IO.Stream" /> object providing the page data.</span></span></param>
        <param name="startOffset"><span data-ttu-id="8d0f4-1255">バイト単位での書き込みを開始するオフセットです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1255">The offset at which to begin writing, in bytes.</span></span> <span data-ttu-id="8d0f4-1256">オフセットは 512 の倍数である必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1256">The offset must be a multiple of 512.</span></span></param>
        <param name="contentMD5"><span data-ttu-id="8d0f4-1257">ページのトランザクションの整合性を確保するために使用する省略可能なハッシュ値です。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1257">An optional hash value used to ensure transactional integrity for the page.</span></span> <span data-ttu-id="8d0f4-1258">あります<c>null</c>または空の文字列。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1258">May be <c>null</c> or an empty string.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-1259">ページ blob にページを書き込む非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1259">Initiates an asynchronous operation to write pages to a page blob.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-1260">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1260">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="8d0f4-1261">クライアントは、ネットワーク上でトランザクションの整合性を確保するための手段として特定のページの書き込み操作の content-md5 ヘッダーを送信できます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1261">Clients may send the Content-MD5 header for a given Write Pages operation as a means to ensure transactional integrity over the wire.</span></span> <span data-ttu-id="8d0f4-1262"><paramref name="contentMD5" />パラメーターにより、クライアントは、指定したバイトの範囲に提供することを事前に計算された MD5 値へのアクセスを既に持っています。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1262">The <paramref name="contentMD5" /> parameter permits clients who already have access to a pre-computed MD5 value for a given byte range to provide it.</span></span>
            <span data-ttu-id="8d0f4-1263">場合、<see cref="P:BlobRequestOptions.UseTransactionalMd5" />プロパティに設定されている<c>true</c>と<paramref name="contentMD5" />にパラメーターが設定されている<c>null</c>、クライアント ライブラリが MD5 値を内部で計算し、します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1263">If the <see cref="P:BlobRequestOptions.UseTransactionalMd5" /> property is set to <c>true</c> and the <paramref name="contentMD5" /> parameter is set to <c>null</c>, then the client library will calculate the MD5 value internally.</span></span>
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
        <param name="pageData"><span data-ttu-id="8d0f4-1264">A<see cref="T:System.IO.Stream" />ページ データを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1264">A <see cref="T:System.IO.Stream" /> object providing the page data.</span></span></param>
        <param name="startOffset"><span data-ttu-id="8d0f4-1265">バイト単位での書き込みを開始するオフセットです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1265">The offset at which to begin writing, in bytes.</span></span> <span data-ttu-id="8d0f4-1266">オフセットは 512 の倍数である必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1266">The offset must be a multiple of 512.</span></span></param>
        <param name="contentMD5"><span data-ttu-id="8d0f4-1267">ページのトランザクションの整合性を確保するために使用する省略可能なハッシュ値です。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1267">An optional hash value used to ensure transactional integrity for the page.</span></span> <span data-ttu-id="8d0f4-1268">あります<c>null</c>または空の文字列。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1268">May be <c>null</c> or an empty string.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8d0f4-1269">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1269">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-1270">ページ blob にページを書き込む非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1270">Initiates an asynchronous operation to write pages to a page blob.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-1271">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1271">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="8d0f4-1272">クライアントは、ネットワーク上でトランザクションの整合性を確保するための手段として特定のページの書き込み操作の content-md5 ヘッダーを送信できます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1272">Clients may send the Content-MD5 header for a given Write Pages operation as a means to ensure transactional integrity over the wire.</span></span> <span data-ttu-id="8d0f4-1273"><paramref name="contentMD5" />パラメーターにより、クライアントは、指定したバイトの範囲に提供することを事前に計算された MD5 値へのアクセスを既に持っています。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1273">The <paramref name="contentMD5" /> parameter permits clients who already have access to a pre-computed MD5 value for a given byte range to provide it.</span></span>
            <span data-ttu-id="8d0f4-1274">場合、<see cref="P:BlobRequestOptions.UseTransactionalMd5" />プロパティに設定されている<c>true</c>と<paramref name="contentMD5" />にパラメーターが設定されている<c>null</c>、クライアント ライブラリが MD5 値を内部で計算し、します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1274">If the <see cref="P:BlobRequestOptions.UseTransactionalMd5" /> property is set to <c>true</c> and the <paramref name="contentMD5" /> parameter is set to <c>null</c>, then the client library will calculate the MD5 value internally.</span></span>
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
        <param name="pageData"><span data-ttu-id="8d0f4-1275">A<see cref="T:System.IO.Stream" />ページ データを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1275">A <see cref="T:System.IO.Stream" /> object providing the page data.</span></span></param>
        <param name="startOffset"><span data-ttu-id="8d0f4-1276">バイト単位での書き込みを開始するオフセットです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1276">The offset at which to begin writing, in bytes.</span></span> <span data-ttu-id="8d0f4-1277">オフセットは 512 の倍数である必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1277">The offset must be a multiple of 512.</span></span></param>
        <param name="contentMD5"><span data-ttu-id="8d0f4-1278">ページのトランザクションの整合性を確保するために使用する省略可能なハッシュ値です。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1278">An optional hash value used to ensure transactional integrity for the page.</span></span> <span data-ttu-id="8d0f4-1279">あります<c>null</c>または空の文字列。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1279">May be <c>null</c> or an empty string.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-1280"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1280">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-1281">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1281">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-1282">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1282">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-1283"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1283">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-1284">ページ blob にページを書き込む非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1284">Initiates an asynchronous operation to write pages to a page blob.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-1285">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1285">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="8d0f4-1286">クライアントは、ネットワーク上でトランザクションの整合性を確保するための手段として特定のページの書き込み操作の content-md5 ヘッダーを送信できます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1286">Clients may send the Content-MD5 header for a given Write Pages operation as a means to ensure transactional integrity over the wire.</span></span> <span data-ttu-id="8d0f4-1287"><paramref name="contentMD5" />パラメーターにより、クライアントは、指定したバイトの範囲に提供することを事前に計算された MD5 値へのアクセスを既に持っています。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1287">The <paramref name="contentMD5" /> parameter permits clients who already have access to a pre-computed MD5 value for a given byte range to provide it.</span></span>
            <span data-ttu-id="8d0f4-1288">場合、<see cref="P:BlobRequestOptions.UseTransactionalMd5" />プロパティに設定されている<c>true</c>と<paramref name="contentMD5" />にパラメーターが設定されている<c>null</c>、クライアント ライブラリが MD5 値を内部で計算し、します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1288">If the <see cref="P:BlobRequestOptions.UseTransactionalMd5" /> property is set to <c>true</c> and the <paramref name="contentMD5" /> parameter is set to <c>null</c>, then the client library will calculate the MD5 value internally.</span></span>
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
        <param name="pageData"><span data-ttu-id="8d0f4-1289">A<see cref="T:System.IO.Stream" />ページ データを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1289">A <see cref="T:System.IO.Stream" /> object providing the page data.</span></span></param>
        <param name="startOffset"><span data-ttu-id="8d0f4-1290">バイト単位での書き込みを開始するオフセットです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1290">The offset at which to begin writing, in bytes.</span></span> <span data-ttu-id="8d0f4-1291">オフセットは 512 の倍数である必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1291">The offset must be a multiple of 512.</span></span></param>
        <param name="contentMD5"><span data-ttu-id="8d0f4-1292">ページのトランザクションの整合性を確保するために使用する省略可能なハッシュ値です。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1292">An optional hash value used to ensure transactional integrity for the page.</span></span> <span data-ttu-id="8d0f4-1293">あります<c>null</c>または空の文字列。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1293">May be <c>null</c> or an empty string.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-1294"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1294">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-1295">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1295">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-1296">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1296">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-1297"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1297">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8d0f4-1298">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1298">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-1299">ページ blob にページを書き込む非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1299">Initiates an asynchronous operation to write pages to a page blob.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-1300">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1300">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="8d0f4-1301">クライアントは、ネットワーク上でトランザクションの整合性を確保するための手段として特定のページの書き込み操作の content-md5 ヘッダーを送信できます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1301">Clients may send the Content-MD5 header for a given Write Pages operation as a means to ensure transactional integrity over the wire.</span></span> <span data-ttu-id="8d0f4-1302"><paramref name="contentMD5" />パラメーターにより、クライアントは、指定したバイトの範囲に提供することを事前に計算された MD5 値へのアクセスを既に持っています。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1302">The <paramref name="contentMD5" /> parameter permits clients who already have access to a pre-computed MD5 value for a given byte range to provide it.</span></span>
            <span data-ttu-id="8d0f4-1303">場合、<see cref="P:BlobRequestOptions.UseTransactionalMd5" />プロパティに設定されている<c>true</c>と<paramref name="contentMD5" />にパラメーターが設定されている<c>null</c>、クライアント ライブラリが MD5 値を内部で計算し、します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1303">If the <see cref="P:BlobRequestOptions.UseTransactionalMd5" /> property is set to <c>true</c> and the <paramref name="contentMD5" /> parameter is set to <c>null</c>, then the client library will calculate the MD5 value internally.</span></span>
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
        <param name="pageData"><span data-ttu-id="8d0f4-1304">A<see cref="T:System.IO.Stream" />ページ データを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1304">A <see cref="T:System.IO.Stream" /> object providing the page data.</span></span></param>
        <param name="startOffset"><span data-ttu-id="8d0f4-1305">バイト単位での書き込みを開始するオフセットです。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1305">The offset at which to begin writing, in bytes.</span></span> <span data-ttu-id="8d0f4-1306">オフセットは 512 の倍数である必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1306">The offset must be a multiple of 512.</span></span></param>
        <param name="contentMD5"><span data-ttu-id="8d0f4-1307">ページのトランザクションの整合性を確保するために使用する省略可能なハッシュ値です。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1307">An optional hash value used to ensure transactional integrity for the page.</span></span> <span data-ttu-id="8d0f4-1308">あります<c>null</c>または空の文字列。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1308">May be <c>null</c> or an empty string.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="8d0f4-1309"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1309">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="8d0f4-1310">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1310">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="8d0f4-1311">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1311">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8d0f4-1312"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1312">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="progressHandler"> <span data-ttu-id="8d0f4-1313">A<see cref="T:System.IProgress`1" />を処理するオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" />メッセージ。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1313">A <see cref="T:System.IProgress`1" /> object to handle <see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" /> messages.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8d0f4-1314">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1314">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="8d0f4-1315">ページ blob にページを書き込む非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1315">Initiates an asynchronous operation to write pages to a page blob.</span></span>
            </summary>
        <returns><span data-ttu-id="8d0f4-1316">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1316">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="8d0f4-1317">クライアントは、ネットワーク上でトランザクションの整合性を確保するための手段として特定のページの書き込み操作の content-md5 ヘッダーを送信できます。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1317">Clients may send the Content-MD5 header for a given Write Pages operation as a means to ensure transactional integrity over the wire.</span></span> <span data-ttu-id="8d0f4-1318"><paramref name="contentMD5" />パラメーターにより、クライアントは、指定したバイトの範囲に提供することを事前に計算された MD5 値へのアクセスを既に持っています。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1318">The <paramref name="contentMD5" /> parameter permits clients who already have access to a pre-computed MD5 value for a given byte range to provide it.</span></span>
            <span data-ttu-id="8d0f4-1319">場合、<see cref="P:BlobRequestOptions.UseTransactionalMd5" />プロパティに設定されている<c>true</c>と<paramref name="contentMD5" />にパラメーターが設定されている<c>null</c>、クライアント ライブラリが MD5 値を内部で計算し、します。</span><span class="sxs-lookup"><span data-stu-id="8d0f4-1319">If the <see cref="P:BlobRequestOptions.UseTransactionalMd5" /> property is set to <c>true</c> and the <paramref name="contentMD5" /> parameter is set to <c>null</c>, then the client library will calculate the MD5 value internally.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>