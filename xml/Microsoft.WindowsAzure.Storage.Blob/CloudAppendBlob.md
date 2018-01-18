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
            <span data-ttu-id="d8c39-101">追加 blob、ブロックのデータを常に、blob の最後にコミットする blob の種類を表します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-101">Represents an append blob, a type of blob where blocks of data are always committed to the end of the blob.</span></span>
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
        <param name="blobAbsoluteUri"><span data-ttu-id="d8c39-102">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-102">A <see cref="T:System.Uri" /> specifying the absolute URI to the blob.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-103">新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" />クラス blob への絶対 URI を使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-103">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" /> class using an absolute URI to the blob.</span></span>
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
        <param name="blobAbsoluteUri"><span data-ttu-id="d8c39-104">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-104">A <see cref="T:System.Uri" /> specifying the absolute URI to the blob.</span></span></param>
        <param name="credentials"><span data-ttu-id="d8c39-105"><see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-105">A <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-106">新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" />クラス blob への絶対 URI を使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-106">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" /> class using an absolute URI to the blob.</span></span>
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
        <param name="blobAbsoluteUri"><span data-ttu-id="d8c39-107">A<see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" />プライマリとセカンダリの両方の場所にある blob を絶対 URI を格納します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-107">A <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" /> containing the absolute URI to the blob at both the primary and secondary locations.</span></span></param>
        <param name="snapshotTime"><span data-ttu-id="d8c39-108">A <see cref="T:System.DateTimeOffset" /> blob がスナップショットの場合、スナップショットのタイムスタンプを指定します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-108">A <see cref="T:System.DateTimeOffset" /> specifying the snapshot timestamp, if the blob is a snapshot.</span></span></param>
        <param name="credentials"><span data-ttu-id="d8c39-109"><see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-109">A <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-110">新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" />クラス blob への絶対 URI を使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-110">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" /> class using an absolute URI to the blob.</span></span>
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
        <param name="blobAbsoluteUri"><span data-ttu-id="d8c39-111">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-111">A <see cref="T:System.Uri" /> specifying the absolute URI to the blob.</span></span></param>
        <param name="snapshotTime"><span data-ttu-id="d8c39-112">A <see cref="T:System.DateTimeOffset" /> blob がスナップショットの場合、スナップショットのタイムスタンプを指定します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-112">A <see cref="T:System.DateTimeOffset" /> specifying the snapshot timestamp, if the blob is a snapshot.</span></span></param>
        <param name="credentials"><span data-ttu-id="d8c39-113"><see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-113">A <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-114">新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" />クラス blob への絶対 URI を使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-114">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" /> class using an absolute URI to the blob.</span></span>
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
        <param name="blockData"><span data-ttu-id="d8c39-115">A<see cref="T:System.IO.Stream" />ブロックのデータを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-115">A <see cref="T:System.IO.Stream" /> object that provides the data for the block.</span></span></param>
        <param name="contentMD5"><span data-ttu-id="d8c39-116">ブロックのトランザクションの整合性を確保するために使用する省略可能なハッシュ値です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-116">An optional hash value used to ensure transactional integrity for the block.</span></span> <span data-ttu-id="d8c39-117">あります<c>null</c>または空の文字列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-117">May be <c>null</c> or an empty string.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-118"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-118">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="d8c39-119">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="d8c39-119">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-120">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-120">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="d8c39-121">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-121">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-122"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-122">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-123">Blob の末尾に新しいデータのブロックをコミットします。</span><span class="sxs-lookup"><span data-stu-id="d8c39-123">Commits a new block of data to the end of the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-124">オフセット、ブロックが追加されました。</span><span class="sxs-lookup"><span data-stu-id="d8c39-124">The offset at which the block was appended.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-125">クライアントは、ネットワーク上でトランザクションの整合性を確保するための手段として特定の Append Block 操作に関して content-md5 ヘッダーを送信できます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-125">Clients may send the Content-MD5 header for a given Append Block operation as a means to ensure transactional integrity over the wire.</span></span> <span data-ttu-id="d8c39-126"><paramref name="contentMD5" />パラメーターにより、クライアントは、指定したバイトの範囲に提供することを事前に計算された MD5 値へのアクセスを既に持っています。</span><span class="sxs-lookup"><span data-stu-id="d8c39-126">The <paramref name="contentMD5" /> parameter permits clients who already have access to a pre-computed MD5 value for a given byte range to provide it.</span></span>
            <span data-ttu-id="d8c39-127">場合、<see cref="P:BlobRequestOptions.UseTransactionalMd5" />プロパティに設定されている<c>true</c>と<paramref name="contentMD5" />にパラメーターが設定されている<c>null</c>、クライアント ライブラリが MD5 値を内部で計算し、します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-127">If the <see cref="P:BlobRequestOptions.UseTransactionalMd5" /> property is set to <c>true</c> and the <paramref name="contentMD5" /> parameter is set to <c>null</c>, then the client library will calculate the MD5 value internally.</span></span>
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
        <param name="blockData"><span data-ttu-id="d8c39-128">A<see cref="T:System.IO.Stream" />ブロックのデータを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-128">A <see cref="T:System.IO.Stream" /> object that provides the data for the block.</span></span></param>
        <param name="contentMD5"><span data-ttu-id="d8c39-129">ブロックのトランザクションの整合性を確保するために使用する省略可能なハッシュ値です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-129">An optional hash value used to ensure transactional integrity for the block.</span></span> <span data-ttu-id="d8c39-130">あります<c>null</c>または空の文字列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-130">May be <c>null</c> or an empty string.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-131">Blob の末尾に新しいデータのブロックをコミットする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-131">Initiates an asynchronous operation to commit a new block of data to the end of the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-132">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-132">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-133">クライアントは、ネットワーク上でトランザクションの整合性を確保するための手段として特定の Append Block 操作に関して content-md5 ヘッダーを送信できます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-133">Clients may send the Content-MD5 header for a given Append Block operation as a means to ensure transactional integrity over the wire.</span></span> <span data-ttu-id="d8c39-134"><paramref name="contentMD5" />パラメーターにより、クライアントは、指定したバイトの範囲に提供することを事前に計算された MD5 値へのアクセスを既に持っています。</span><span class="sxs-lookup"><span data-stu-id="d8c39-134">The <paramref name="contentMD5" /> parameter permits clients who already have access to a pre-computed MD5 value for a given byte range to provide it.</span></span>
            <span data-ttu-id="d8c39-135">場合、<see cref="P:BlobRequestOptions.UseTransactionalMd5" />プロパティに設定されている<c>true</c>と<paramref name="contentMD5" />にパラメーターが設定されている<c>null</c>、クライアント ライブラリが MD5 値を内部で計算し、します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-135">If the <see cref="P:BlobRequestOptions.UseTransactionalMd5" /> property is set to <c>true</c> and the <paramref name="contentMD5" /> parameter is set to <c>null</c>, then the client library will calculate the MD5 value internally.</span></span>
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
        <param name="blockData"><span data-ttu-id="d8c39-136">A<see cref="T:System.IO.Stream" />ブロックのデータを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-136">A <see cref="T:System.IO.Stream" /> object that provides the data for the block.</span></span></param>
        <param name="contentMD5"><span data-ttu-id="d8c39-137">ブロックのトランザクションの整合性を確保するために使用する省略可能なハッシュ値です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-137">An optional hash value used to ensure transactional integrity for the block.</span></span> <span data-ttu-id="d8c39-138">あります<c>null</c>または空の文字列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-138">May be <c>null</c> or an empty string.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d8c39-139">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="d8c39-139">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-140">Blob の末尾に新しいデータのブロックをコミットする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-140">Initiates an asynchronous operation to commit a new block of data to the end of the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-141">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-141">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-142">クライアントは、ネットワーク上でトランザクションの整合性を確保するための手段として特定のブロックの配置操作に関して content-md5 ヘッダーを送信することがあります。</span><span class="sxs-lookup"><span data-stu-id="d8c39-142">Clients may send the Content-MD5 header for a given Put Block operation as a means to ensure transactional integrity over the wire.</span></span> <span data-ttu-id="d8c39-143"><paramref name="contentMD5" />パラメーターにより、クライアントは、指定したバイトの範囲に提供することを事前に計算された MD5 値へのアクセスを既に持っています。</span><span class="sxs-lookup"><span data-stu-id="d8c39-143">The <paramref name="contentMD5" /> parameter permits clients who already have access to a pre-computed MD5 value for a given byte range to provide it.</span></span>
            <span data-ttu-id="d8c39-144">場合、<see cref="P:BlobRequestOptions.UseTransactionalMd5" />プロパティに設定されている<c>true</c>と<paramref name="contentMD5" />にパラメーターが設定されている<c>null</c>、クライアント ライブラリが MD5 値を内部で計算し、します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-144">If the <see cref="P:BlobRequestOptions.UseTransactionalMd5" /> property is set to <c>true</c> and the <paramref name="contentMD5" /> parameter is set to <c>null</c>, then the client library will calculate the MD5 value internally.</span></span>
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
        <param name="blockData"><span data-ttu-id="d8c39-145">A<see cref="T:System.IO.Stream" />ブロックのデータを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-145">A <see cref="T:System.IO.Stream" /> object that provides the data for the block.</span></span></param>
        <param name="contentMD5"><span data-ttu-id="d8c39-146">ブロックのトランザクションの整合性を確保するために使用する省略可能なハッシュ値です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-146">An optional hash value used to ensure transactional integrity for the block.</span></span> <span data-ttu-id="d8c39-147">あります<c>null</c>または空の文字列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-147">May be <c>null</c> or an empty string.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-148"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-148">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="d8c39-149">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="d8c39-149">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-150">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-150">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-151"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-151">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-152">Blob の末尾に新しいデータのブロックをコミットする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-152">Initiates an asynchronous operation to commit a new block of data to the end of the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-153">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-153">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-154">クライアントは、ネットワーク上でトランザクションの整合性を確保するための手段として特定の Append Block 操作に関して content-md5 ヘッダーを送信できます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-154">Clients may send the Content-MD5 header for a given Append Block operation as a means to ensure transactional integrity over the wire.</span></span> <span data-ttu-id="d8c39-155"><paramref name="contentMD5" />パラメーターにより、クライアントは、指定したバイトの範囲に提供することを事前に計算された MD5 値へのアクセスを既に持っています。</span><span class="sxs-lookup"><span data-stu-id="d8c39-155">The <paramref name="contentMD5" /> parameter permits clients who already have access to a pre-computed MD5 value for a given byte range to provide it.</span></span>
            <span data-ttu-id="d8c39-156">場合、<see cref="P:BlobRequestOptions.UseTransactionalMd5" />プロパティに設定されている<c>true</c>と<paramref name="contentMD5" />にパラメーターが設定されている<c>null</c>、クライアント ライブラリが MD5 値を内部で計算し、します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-156">If the <see cref="P:BlobRequestOptions.UseTransactionalMd5" /> property is set to <c>true</c> and the <paramref name="contentMD5" /> parameter is set to <c>null</c>, then the client library will calculate the MD5 value internally.</span></span>
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
        <param name="blockData"><span data-ttu-id="d8c39-157">A<see cref="T:System.IO.Stream" />ブロックのデータを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-157">A <see cref="T:System.IO.Stream" /> object that provides the data for the block.</span></span></param>
        <param name="contentMD5"><span data-ttu-id="d8c39-158">ブロックのトランザクションの整合性を確保するために使用する省略可能なハッシュ値です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-158">An optional hash value used to ensure transactional integrity for the block.</span></span> <span data-ttu-id="d8c39-159">あります<c>null</c>または空の文字列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-159">May be <c>null</c> or an empty string.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-160"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-160">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="d8c39-161">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="d8c39-161">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-162">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-162">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-163"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-163">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d8c39-164">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="d8c39-164">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-165">Blob の末尾に新しいデータのブロックをコミットする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-165">Initiates an asynchronous operation to commit a new block of data to the end of the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-166">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-166">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-167">クライアントは、ネットワーク上でトランザクションの整合性を確保するための手段として特定の Append Block 操作に関して content-md5 ヘッダーを送信できます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-167">Clients may send the Content-MD5 header for a given Append Block operation as a means to ensure transactional integrity over the wire.</span></span> <span data-ttu-id="d8c39-168"><paramref name="contentMD5" />パラメーターにより、クライアントは、指定したバイトの範囲に提供することを事前に計算された MD5 値へのアクセスを既に持っています。</span><span class="sxs-lookup"><span data-stu-id="d8c39-168">The <paramref name="contentMD5" /> parameter permits clients who already have access to a pre-computed MD5 value for a given byte range to provide it.</span></span>
            <span data-ttu-id="d8c39-169">場合、<see cref="P:BlobRequestOptions.UseTransactionalMd5" />プロパティに設定されている<c>true</c>と<paramref name="contentMD5" />にパラメーターが設定されている<c>null</c>、クライアント ライブラリが MD5 値を内部で計算し、します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-169">If the <see cref="P:BlobRequestOptions.UseTransactionalMd5" /> property is set to <c>true</c> and the <paramref name="contentMD5" /> parameter is set to <c>null</c>, then the client library will calculate the MD5 value internally.</span></span>
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
        <param name="blockData"><span data-ttu-id="d8c39-170">A<see cref="T:System.IO.Stream" />ブロックのデータを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-170">A <see cref="T:System.IO.Stream" /> object that provides the data for the block.</span></span></param>
        <param name="contentMD5"><span data-ttu-id="d8c39-171">ブロックのトランザクションの整合性を確保するために使用する省略可能なハッシュ値です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-171">An optional hash value used to ensure transactional integrity for the block.</span></span> <span data-ttu-id="d8c39-172">あります<c>null</c>または空の文字列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-172">May be <c>null</c> or an empty string.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-173"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-173">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="d8c39-174">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="d8c39-174">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-175">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-175">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-176"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-176">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="progressHandler"> <span data-ttu-id="d8c39-177">A<see cref="T:System.IProgress`1" />を処理するオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" />メッセージ。</span><span class="sxs-lookup"><span data-stu-id="d8c39-177">A <see cref="T:System.IProgress`1" /> object to handle <see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" /> messages.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d8c39-178">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="d8c39-178">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-179">Blob の末尾に新しいデータのブロックをコミットする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-179">Initiates an asynchronous operation to commit a new block of data to the end of the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-180">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-180">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-181">クライアントは、ネットワーク上でトランザクションの整合性を確保するための手段として特定の Append Block 操作に関して content-md5 ヘッダーを送信できます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-181">Clients may send the Content-MD5 header for a given Append Block operation as a means to ensure transactional integrity over the wire.</span></span> <span data-ttu-id="d8c39-182"><paramref name="contentMD5" />パラメーターにより、クライアントは、指定したバイトの範囲に提供することを事前に計算された MD5 値へのアクセスを既に持っています。</span><span class="sxs-lookup"><span data-stu-id="d8c39-182">The <paramref name="contentMD5" /> parameter permits clients who already have access to a pre-computed MD5 value for a given byte range to provide it.</span></span>
            <span data-ttu-id="d8c39-183">場合、<see cref="P:BlobRequestOptions.UseTransactionalMd5" />プロパティに設定されている<c>true</c>と<paramref name="contentMD5" />にパラメーターが設定されている<c>null</c>、クライアント ライブラリが MD5 値を内部で計算し、します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-183">If the <see cref="P:BlobRequestOptions.UseTransactionalMd5" /> property is set to <c>true</c> and the <paramref name="contentMD5" /> parameter is set to <c>null</c>, then the client library will calculate the MD5 value internally.</span></span>
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
        <param name="buffer"><span data-ttu-id="d8c39-184">バイト配列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-184">An array of bytes.</span></span></param>
        <param name="index"><span data-ttu-id="d8c39-185">Blob のバイトのアップロードを開始位置を示すバッファー内の 0 から始まるバイト オフセット。</span><span class="sxs-lookup"><span data-stu-id="d8c39-185">The zero-based byte offset in buffer at which to begin uploading bytes to the blob.</span></span></param>
        <param name="count"><span data-ttu-id="d8c39-186">Blob に書き込まれるバイト数。</span><span class="sxs-lookup"><span data-stu-id="d8c39-186">The number of bytes to be written to the blob.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-187"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-187">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-188">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-188">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="d8c39-189">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-189">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-190"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-190">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-191">追加 blob をバイト配列の内容を追加します。単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-191">Appends the contents of a byte array to an append blob.Recommended only for single-writer scenarios.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="d8c39-192">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-192">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-193">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-193">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>        
            <span data-ttu-id="d8c39-194">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-194">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
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
        <param name="buffer"><span data-ttu-id="d8c39-195">バイト配列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-195">An array of bytes.</span></span></param>
        <param name="index"><span data-ttu-id="d8c39-196">Blob のバイトのアップロードを開始位置を示すバッファー内の 0 から始まるバイト オフセット。</span><span class="sxs-lookup"><span data-stu-id="d8c39-196">The zero-based byte offset in buffer at which to begin uploading bytes to the blob.</span></span></param>
        <param name="count"><span data-ttu-id="d8c39-197">Blob に書き込まれるバイト数。</span><span class="sxs-lookup"><span data-stu-id="d8c39-197">The number of bytes to be written to the blob.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-198">追加 blob にバイト配列の内容を追加する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-198">Initiates an asynchronous operation to append the contents of a byte array to an append blob.</span></span> <span data-ttu-id="d8c39-199">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-199">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-200">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-200">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-201">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-201">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-202">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-202">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>        
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
        <param name="buffer"><span data-ttu-id="d8c39-203">バイト配列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-203">An array of bytes.</span></span></param>
        <param name="index"><span data-ttu-id="d8c39-204">Blob のバイトのアップロードを開始位置を示すバッファー内の 0 から始まるバイト オフセット。</span><span class="sxs-lookup"><span data-stu-id="d8c39-204">The zero-based byte offset in buffer at which to begin uploading bytes to the blob.</span></span></param>
        <param name="count"><span data-ttu-id="d8c39-205">Blob に書き込まれるバイト数。</span><span class="sxs-lookup"><span data-stu-id="d8c39-205">The number of bytes to be written to the blob.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d8c39-206">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="d8c39-206">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-207">追加 blob にバイト配列の内容を追加する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-207">Initiates an asynchronous operation to append the contents of a byte array to an append blob.</span></span> <span data-ttu-id="d8c39-208">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-208">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-209">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-209">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-210">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-210">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-211">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-211">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>        
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
        <param name="buffer"><span data-ttu-id="d8c39-212">バイト配列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-212">An array of bytes.</span></span></param>
        <param name="index"><span data-ttu-id="d8c39-213">Blob のバイトのアップロードを開始位置を示すバッファー内の 0 から始まるバイト オフセット。</span><span class="sxs-lookup"><span data-stu-id="d8c39-213">The zero-based byte offset in buffer at which to begin uploading bytes to the blob.</span></span></param>
        <param name="count"><span data-ttu-id="d8c39-214">Blob に書き込まれるバイト数。</span><span class="sxs-lookup"><span data-stu-id="d8c39-214">The number of bytes to be written to the blob.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-215"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-215">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-216">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-216">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-217"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-217">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-218">追加 blob にバイト配列の内容を追加する非同期操作を開始します。この API は、API は内部的に複数のライターのシナリオでは機能しませんが、重複するブロックを回避する追加オフセット条件ヘッダーを使用するため、単一ライターのシナリオで厳密に使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="d8c39-218">Initiates an asynchronous operation to append the contents of a byte array to an append blob.This API should be used strictly in a single writer scenario because the API internally uses the append-offset conditional header to avoid duplicate blocks which does not work in a multiple writer scenario.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-219">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-219">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-220">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-220">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
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
        <param name="buffer"><span data-ttu-id="d8c39-221">バイト配列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-221">An array of bytes.</span></span></param>
        <param name="index"><span data-ttu-id="d8c39-222">Blob のバイトのアップロードを開始位置を示すバッファー内の 0 から始まるバイト オフセット。</span><span class="sxs-lookup"><span data-stu-id="d8c39-222">The zero-based byte offset in buffer at which to begin uploading bytes to the blob.</span></span></param>
        <param name="count"><span data-ttu-id="d8c39-223">Blob に書き込まれるバイト数。</span><span class="sxs-lookup"><span data-stu-id="d8c39-223">The number of bytes to be written to the blob.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-224"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-224">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-225">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-225">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-226"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-226">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d8c39-227">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="d8c39-227">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-228">バイト配列の内容を追加 blob にアップロードする非同期操作を開始します。この API は、API は内部的に複数のライターのシナリオでは機能しませんが、重複するブロックを回避する追加オフセット条件ヘッダーを使用するため、単一ライターのシナリオで厳密に使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="d8c39-228">Initiates an asynchronous operation to upload the contents of a byte array to an append blob.This API should be used strictly in a single writer scenario because the API internally uses the append-offset conditional header to avoid duplicate blocks which does not work in a multiple writer scenario.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-229">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-229">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-230">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-230">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
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
        <param name="buffer"><span data-ttu-id="d8c39-231">バイト配列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-231">An array of bytes.</span></span></param>
        <param name="index"><span data-ttu-id="d8c39-232">Blob のバイトのアップロードを開始位置を示すバッファー内の 0 から始まるバイト オフセット。</span><span class="sxs-lookup"><span data-stu-id="d8c39-232">The zero-based byte offset in buffer at which to begin uploading bytes to the blob.</span></span></param>
        <param name="count"><span data-ttu-id="d8c39-233">Blob に書き込まれるバイト数。</span><span class="sxs-lookup"><span data-stu-id="d8c39-233">The number of bytes to be written to the blob.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-234"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-234">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-235">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-235">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-236"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-236">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="progressHandler"> <span data-ttu-id="d8c39-237">A<see cref="T:System.IProgress`1" />を処理するオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" />メッセージ。</span><span class="sxs-lookup"><span data-stu-id="d8c39-237">A <see cref="T:System.IProgress`1" /> object to handle <see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" /> messages.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d8c39-238">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="d8c39-238">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-239">バイト配列の内容を追加 blob にアップロードする非同期操作を開始します。この API は、API は内部的に複数のライターのシナリオでは機能しませんが、重複するブロックを回避する追加オフセット条件ヘッダーを使用するため、単一ライターのシナリオで厳密に使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="d8c39-239">Initiates an asynchronous operation to upload the contents of a byte array to an append blob.This API should be used strictly in a single writer scenario because the API internally uses the append-offset conditional header to avoid duplicate blocks which does not work in a multiple writer scenario.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-240">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-240">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-241">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-241">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
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
        <param name="path"><span data-ttu-id="d8c39-242">Blob コンテンツを提供するファイルのパスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-242">A string containing the file path providing the blob content.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-243"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-243">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-244">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-244">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="d8c39-245">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-245">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-246"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-246">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-247">追加 blob にファイルを追加します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-247">Appends a file to an append blob.</span></span> <span data-ttu-id="d8c39-248">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-248">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="d8c39-249">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-249">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-250">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-250">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>        
            <span data-ttu-id="d8c39-251">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-251">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
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
        <param name="path"><span data-ttu-id="d8c39-252">Blob コンテンツを提供するファイルのパスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-252">A string containing the file path providing the blob content.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-253">追加 blob にファイルを追加する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-253">Initiates an asynchronous operation to append a file to an append blob.</span></span> <span data-ttu-id="d8c39-254">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-254">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-255">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-255">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-256">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-256">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-257">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-257">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>        
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
        <param name="path"><span data-ttu-id="d8c39-258">Blob コンテンツを提供するファイルのパスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-258">A string containing the file path providing the blob content.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d8c39-259">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="d8c39-259">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-260">追加 blob にファイルを追加する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-260">Initiates an asynchronous operation to append a file to an append blob.</span></span> <span data-ttu-id="d8c39-261">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-261">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-262">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-262">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-263">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-263">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-264">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-264">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>        
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
        <param name="path"><span data-ttu-id="d8c39-265">Blob コンテンツを提供するファイルのパスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-265">A string containing the file path providing the blob content.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-266"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-266">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-267">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-267">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-268"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-268">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-269">追加 blob にファイルを追加する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-269">Initiates an asynchronous operation to append a file to an append blob.</span></span> <span data-ttu-id="d8c39-270">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-270">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-271">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-271">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-272">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-272">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-273">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-273">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>        
            <span data-ttu-id="d8c39-274">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-274">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
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
        <param name="path"><span data-ttu-id="d8c39-275">Blob コンテンツを提供するファイルのパスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-275">A string containing the file path providing the blob content.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-276"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-276">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-277">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-277">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-278"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-278">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d8c39-279">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="d8c39-279">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-280">追加 blob にファイルを追加する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-280">Initiates an asynchronous operation to append a file to an append blob.</span></span> <span data-ttu-id="d8c39-281">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-281">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-282">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-282">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-283">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-283">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-284">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-284">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>        
            <span data-ttu-id="d8c39-285">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-285">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
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
        <param name="path"><span data-ttu-id="d8c39-286">Blob コンテンツを提供するファイルのパスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-286">A string containing the file path providing the blob content.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-287"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-287">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-288">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-288">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-289"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-289">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="progressHandler"> <span data-ttu-id="d8c39-290">A<see cref="T:System.IProgress`1" />を処理するオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" />メッセージ。</span><span class="sxs-lookup"><span data-stu-id="d8c39-290">A <see cref="T:System.IProgress`1" /> object to handle <see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" /> messages.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d8c39-291">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="d8c39-291">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-292">追加 blob にファイルを追加する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-292">Initiates an asynchronous operation to append a file to an append blob.</span></span> <span data-ttu-id="d8c39-293">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-293">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-294">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-294">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-295">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-295">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-296">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-296">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>        
            <span data-ttu-id="d8c39-297">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-297">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
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
        <param name="source"><span data-ttu-id="d8c39-298">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-298">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-299"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-299">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="d8c39-300">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="d8c39-300">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-301">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-301">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="d8c39-302">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-302">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-303"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-303">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-304">追加 blob にストリームを追加します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-304">Appends a stream to an append blob.</span></span> <span data-ttu-id="d8c39-305">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-305">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="d8c39-306">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-306">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-307">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-307">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>        
            <span data-ttu-id="d8c39-308">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-308">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
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
        <param name="source"><span data-ttu-id="d8c39-309">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-309">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="length"><span data-ttu-id="d8c39-310">現在の位置に、ソース ストリームから書き込むバイト数。</span><span class="sxs-lookup"><span data-stu-id="d8c39-310">The number of bytes to write from the source stream at its current position.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-311"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-311">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="d8c39-312">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="d8c39-312">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-313">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-313">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="d8c39-314">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-314">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-315"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-315">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-316">追加 blob にストリームを追加します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-316">Appends a stream to an append blob.</span></span> <span data-ttu-id="d8c39-317">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-317">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="d8c39-318">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-318">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-319">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-319">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>        
            <span data-ttu-id="d8c39-320">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-320">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
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
        <param name="source"><span data-ttu-id="d8c39-321">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-321">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-322">追加 blob にストリームを追加する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-322">Initiates an asynchronous operation to append a stream to an append blob.</span></span> <span data-ttu-id="d8c39-323">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-323">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-324">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-324">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-325">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-325">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-326">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-326">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>        
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
        <param name="source"><span data-ttu-id="d8c39-327">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-327">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="length"><span data-ttu-id="d8c39-328">現在の位置に、ソース ストリームから書き込むバイト数。</span><span class="sxs-lookup"><span data-stu-id="d8c39-328">The number of bytes to write from the source stream at its current position.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-329">追加 blob にストリームを追加する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-329">Initiates an asynchronous operation to append a stream to an append blob.</span></span> <span data-ttu-id="d8c39-330">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-330">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-331">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-331">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-332">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-332">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-333">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-333">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>        
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
        <param name="source"><span data-ttu-id="d8c39-334">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-334">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d8c39-335">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="d8c39-335">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-336">追加 blob にストリームを追加する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-336">Initiates an asynchronous operation to append a stream to an append blob.</span></span> <span data-ttu-id="d8c39-337">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-337">Recommended only for single-writer scenarios.</span></span>        
            </summary>
        <returns><span data-ttu-id="d8c39-338">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-338">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-339">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-339">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-340">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-340">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>        
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
        <param name="source"><span data-ttu-id="d8c39-341">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-341">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="length"><span data-ttu-id="d8c39-342">現在の位置に、ソース ストリームから書き込むバイト数。</span><span class="sxs-lookup"><span data-stu-id="d8c39-342">The number of bytes to write from the source stream at its current position.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d8c39-343">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="d8c39-343">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-344">追加 blob にストリームを追加する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-344">Initiates an asynchronous operation to append a stream to an append blob.</span></span> <span data-ttu-id="d8c39-345">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-345">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-346">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-346">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-347">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-347">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-348">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-348">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>        
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
        <param name="source"><span data-ttu-id="d8c39-349">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-349">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-350"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-350">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="d8c39-351">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="d8c39-351">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-352">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-352">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-353"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-353">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-354">追加 blob にストリームを追加する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-354">Initiates an asynchronous operation to append a stream to an append blob.</span></span> <span data-ttu-id="d8c39-355">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-355">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-356">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-356">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-357">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-357">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-358">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-358">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>        
            <span data-ttu-id="d8c39-359">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-359">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
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
        <param name="source"><span data-ttu-id="d8c39-360">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-360">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-361"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-361">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="d8c39-362">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="d8c39-362">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-363">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-363">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-364"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-364">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d8c39-365">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="d8c39-365">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-366">追加 blob にストリームを追加する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-366">Initiates an asynchronous operation to append a stream to an append blob.</span></span> <span data-ttu-id="d8c39-367">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-367">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-368">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-368">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-369">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-369">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-370">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-370">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>        
            <span data-ttu-id="d8c39-371">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-371">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
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
        <param name="source"><span data-ttu-id="d8c39-372">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-372">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="length"><span data-ttu-id="d8c39-373">現在の位置に、ソース ストリームから書き込むバイト数。</span><span class="sxs-lookup"><span data-stu-id="d8c39-373">The number of bytes to write from the source stream at its current position.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-374"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-374">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="d8c39-375">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="d8c39-375">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-376">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-376">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-377"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-377">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-378">追加 blob にストリームを追加する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-378">Initiates an asynchronous operation to append a stream to an append blob.</span></span> <span data-ttu-id="d8c39-379">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-379">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-380">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-380">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-381">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-381">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-382">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-382">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>        
            <span data-ttu-id="d8c39-383">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-383">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
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
        <param name="source"><span data-ttu-id="d8c39-384">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-384">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-385"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-385">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="d8c39-386">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="d8c39-386">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-387">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-387">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-388"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-388">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="progressHandler"> <span data-ttu-id="d8c39-389">A<see cref="T:System.IProgress`1" />を処理するオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" />メッセージ。</span><span class="sxs-lookup"><span data-stu-id="d8c39-389">A <see cref="T:System.IProgress`1" /> object to handle <see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" /> messages.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d8c39-390">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="d8c39-390">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-391">追加 blob にストリームを追加する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-391">Initiates an asynchronous operation to append a stream to an append blob.</span></span> <span data-ttu-id="d8c39-392">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-392">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-393">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-393">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-394">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-394">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-395">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-395">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>        
            <span data-ttu-id="d8c39-396">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-396">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
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
        <param name="source"><span data-ttu-id="d8c39-397">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-397">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="length"><span data-ttu-id="d8c39-398">現在の位置に、ソース ストリームから書き込むバイト数。</span><span class="sxs-lookup"><span data-stu-id="d8c39-398">The number of bytes to write from the source stream at its current position.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-399"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-399">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="d8c39-400">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="d8c39-400">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-401">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-401">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-402"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-402">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d8c39-403">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="d8c39-403">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-404">追加 blob にストリームを追加する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-404">Initiates an asynchronous operation to append a stream to an append blob.</span></span> <span data-ttu-id="d8c39-405">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-405">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-406">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-406">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-407">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-407">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-408">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-408">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>        
            <span data-ttu-id="d8c39-409">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-409">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
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
        <param name="source"><span data-ttu-id="d8c39-410">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-410">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="length"><span data-ttu-id="d8c39-411">現在の位置に、ソース ストリームから書き込むバイト数。</span><span class="sxs-lookup"><span data-stu-id="d8c39-411">The number of bytes to write from the source stream at its current position.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-412"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-412">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="d8c39-413">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="d8c39-413">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-414">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-414">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-415"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-415">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="progressHandler"> <span data-ttu-id="d8c39-416">A<see cref="T:System.IProgress`1" />を処理するオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" />メッセージ。</span><span class="sxs-lookup"><span data-stu-id="d8c39-416">A <see cref="T:System.IProgress`1" /> object to handle <see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" /> messages.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d8c39-417">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="d8c39-417">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-418">追加 blob にストリームを追加する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-418">Initiates an asynchronous operation to append a stream to an append blob.</span></span> <span data-ttu-id="d8c39-419">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-419">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-420">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-420">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-421">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-421">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-422">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-422">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>        
            <span data-ttu-id="d8c39-423">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-423">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
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
        <param name="content"><span data-ttu-id="d8c39-424">アップロードするテキストを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-424">A string containing the text to upload.</span></span></param>
        <param name="encoding"><span data-ttu-id="d8c39-425">A<see cref="T:System.Text.Encoding" />を使用するテキスト エンコーディングを示すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-425">A <see cref="T:System.Text.Encoding" /> object that indicates the text encoding to use.</span></span> <span data-ttu-id="d8c39-426">場合<c>null</c>utf-8 が使用されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-426">If <c>null</c>, UTF-8 will be used.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-427"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-427">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-428">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-428">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="d8c39-429">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-429">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-430"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-430">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-431">追加 blob にテキスト文字列を追加します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-431">Appends a string of text to an append blob.</span></span> <span data-ttu-id="d8c39-432">この API は、API は内部的に複数のライターのシナリオでは機能しませんが、重複するブロックを回避する追加オフセット条件ヘッダーを使用するため、単一ライターのシナリオで厳密に使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="d8c39-432">This API should be used strictly in a single writer scenario because the API internally uses the append-offset conditional header to avoid duplicate blocks which does not work in a multiple writer scenario.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="d8c39-433">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-433">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
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
        <param name="content"><span data-ttu-id="d8c39-434">アップロードするテキストを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-434">A string containing the text to upload.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-435">追加 blob にテキストの文字列を追加する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-435">Initiates an asynchronous operation to append a string of text to an append blob.</span></span> <span data-ttu-id="d8c39-436">この API は、API は内部的に複数のライターのシナリオでは機能しませんが、重複するブロックを回避する追加オフセット条件ヘッダーを使用するため、単一ライターのシナリオで厳密に使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="d8c39-436">This API should be used strictly in a single writer scenario because the API internally uses the append-offset conditional header to avoid duplicate blocks which does not work in a multiple writer scenario.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-437">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-437">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
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
        <param name="content"><span data-ttu-id="d8c39-438">アップロードするテキストを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-438">A string containing the text to upload.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d8c39-439">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="d8c39-439">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-440">追加 blob にテキストの文字列を追加する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-440">Initiates an asynchronous operation to append a string of text to an append blob.</span></span> <span data-ttu-id="d8c39-441">この API は、API は内部的に複数のライターのシナリオでは機能しませんが、重複するブロックを回避する追加オフセット条件ヘッダーを使用するため、単一ライターのシナリオで厳密に使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="d8c39-441">This API should be used strictly in a single writer scenario because the API internally uses the append-offset conditional header to avoid duplicate blocks which does not work in a multiple writer scenario.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-442">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-442">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
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
        <param name="content"><span data-ttu-id="d8c39-443">アップロードするテキストを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-443">A string containing the text to upload.</span></span></param>
        <param name="encoding"><span data-ttu-id="d8c39-444">A<see cref="T:System.Text.Encoding" />を使用するテキスト エンコーディングを示すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-444">A <see cref="T:System.Text.Encoding" /> object that indicates the text encoding to use.</span></span> <span data-ttu-id="d8c39-445">場合<c>null</c>utf-8 が使用されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-445">If <c>null</c>, UTF-8 will be used.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-446"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-446">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-447">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-447">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-448"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-448">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-449">追加 blob にテキストの文字列を追加する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-449">Initiates an asynchronous operation to append a string of text to an append blob.</span></span> <span data-ttu-id="d8c39-450">この API は、API は内部的に複数のライターのシナリオでは機能しませんが、重複するブロックを回避する追加オフセット条件ヘッダーを使用するため、単一ライターのシナリオで厳密に使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="d8c39-450">This API should be used strictly in a single writer scenario because the API internally uses the append-offset conditional header to avoid duplicate blocks which does not work in a multiple writer scenario.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-451">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-451">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-452">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-452">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
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
        <param name="content"><span data-ttu-id="d8c39-453">アップロードするテキストを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-453">A string containing the text to upload.</span></span></param>
        <param name="encoding"><span data-ttu-id="d8c39-454">A<see cref="T:System.Text.Encoding" />を使用するテキスト エンコーディングを示すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-454">A <see cref="T:System.Text.Encoding" /> object that indicates the text encoding to use.</span></span> <span data-ttu-id="d8c39-455">場合<c>null</c>utf-8 が使用されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-455">If <c>null</c>, UTF-8 will be used.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-456"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-456">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-457">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-457">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-458"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-458">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d8c39-459">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="d8c39-459">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-460">追加 blob にテキストの文字列を追加する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-460">Initiates an asynchronous operation to append a string of text to an append blob.</span></span> <span data-ttu-id="d8c39-461">この API は、API は内部的に複数のライターのシナリオでは機能しませんが、重複するブロックを回避する追加オフセット条件ヘッダーを使用するため、単一ライターのシナリオで厳密に使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="d8c39-461">This API should be used strictly in a single writer scenario because the API internally uses the append-offset conditional header to avoid duplicate blocks which does not work in a multiple writer scenario.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-462">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-462">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-463">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-463">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
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
        <param name="content"><span data-ttu-id="d8c39-464">アップロードするテキストを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-464">A string containing the text to upload.</span></span></param>
        <param name="encoding"><span data-ttu-id="d8c39-465">A<see cref="T:System.Text.Encoding" />を使用するテキスト エンコーディングを示すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-465">A <see cref="T:System.Text.Encoding" /> object that indicates the text encoding to use.</span></span> <span data-ttu-id="d8c39-466">場合<c>null</c>utf-8 が使用されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-466">If <c>null</c>, UTF-8 will be used.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-467"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-467">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-468">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-468">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-469"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-469">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="progressHandler"> <span data-ttu-id="d8c39-470">A<see cref="T:System.IProgress`1" />を処理するオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" />メッセージ。</span><span class="sxs-lookup"><span data-stu-id="d8c39-470">A <see cref="T:System.IProgress`1" /> object to handle <see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" /> messages.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d8c39-471">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="d8c39-471">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-472">追加 blob にテキストの文字列を追加する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-472">Initiates an asynchronous operation to append a string of text to an append blob.</span></span> <span data-ttu-id="d8c39-473">この API は、API は内部的に複数のライターのシナリオでは機能しませんが、重複するブロックを回避する追加オフセット条件ヘッダーを使用するため、単一ライターのシナリオで厳密に使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="d8c39-473">This API should be used strictly in a single writer scenario because the API internally uses the append-offset conditional header to avoid duplicate blocks which does not work in a multiple writer scenario.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-474">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-474">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-475">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-475">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
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
        <param name="blockData"><span data-ttu-id="d8c39-476">A<see cref="T:System.IO.Stream" />ブロックのデータを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-476">A <see cref="T:System.IO.Stream" /> object that provides the data for the block.</span></span></param>
        <param name="callback"><span data-ttu-id="d8c39-477"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="d8c39-477">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="d8c39-478">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-478">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-479">Blob の末尾に新しいデータのブロックをコミットする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-479">Begins an asynchronous operation to commit a new block of data to the end of the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-480"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-480">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
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
        <param name="blockData"><span data-ttu-id="d8c39-481">A<see cref="T:System.IO.Stream" />ブロックのデータを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-481">A <see cref="T:System.IO.Stream" /> object that provides the data for the block.</span></span></param>
        <param name="contentMD5"><span data-ttu-id="d8c39-482">ブロックのトランザクションの整合性を確保するために使用する省略可能なハッシュ値です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-482">An optional hash value used to ensure transactional integrity for the block.</span></span> <span data-ttu-id="d8c39-483">あります<c>null</c>または空の文字列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-483">May be <c>null</c> or an empty string.</span></span></param>
        <param name="callback"><span data-ttu-id="d8c39-484"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="d8c39-484">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="d8c39-485">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-485">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-486">Blob の末尾に新しいデータのブロックをコミットする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-486">Begins an asynchronous operation to commit a new block of data to the end of the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-487"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-487">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-488">クライアントは、ネットワーク上でトランザクションの整合性を確保するための手段として特定の Append Block 操作に関して content-md5 ヘッダーを送信できます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-488">Clients may send the Content-MD5 header for a given Append Block operation as a means to ensure transactional integrity over the wire.</span></span> <span data-ttu-id="d8c39-489"><paramref name="contentMD5" />パラメーターにより、クライアントは、指定したバイトの範囲に提供することを事前に計算された MD5 値へのアクセスを既に持っています。</span><span class="sxs-lookup"><span data-stu-id="d8c39-489">The <paramref name="contentMD5" /> parameter permits clients who already have access to a pre-computed MD5 value for a given byte range to provide it.</span></span>
            <span data-ttu-id="d8c39-490">場合、<see cref="P:BlobRequestOptions.UseTransactionalMd5" />プロパティに設定されている<c>true</c>と<paramref name="contentMD5" />にパラメーターが設定されている<c>null</c>、クライアント ライブラリが MD5 値を内部で計算し、します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-490">If the <see cref="P:BlobRequestOptions.UseTransactionalMd5" /> property is set to <c>true</c> and the <paramref name="contentMD5" /> parameter is set to <c>null</c>, then the client library will calculate the MD5 value internally.</span></span>
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
        <param name="blockData"><span data-ttu-id="d8c39-491">A<see cref="T:System.IO.Stream" />ブロックのデータを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-491">A <see cref="T:System.IO.Stream" /> object that provides the data for the block.</span></span></param>
        <param name="contentMD5"><span data-ttu-id="d8c39-492">ブロックのトランザクションの整合性を確保するために使用する省略可能なハッシュ値です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-492">An optional hash value used to ensure transactional integrity for the block.</span></span> <span data-ttu-id="d8c39-493">あります<c>null</c>または空の文字列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-493">May be <c>null</c> or an empty string.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-494"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-494">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="d8c39-495">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="d8c39-495">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-496">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-496">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-497"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-497">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="d8c39-498"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="d8c39-498">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="d8c39-499">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-499">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-500">Blob の末尾に新しいデータのブロックをコミットする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-500">Begins an asynchronous operation to commit a new block of data to the end of the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-501"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-501">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-502">クライアントは、ネットワーク上でトランザクションの整合性を確保するための手段として特定の Append Block 操作に関して content-md5 ヘッダーを送信できます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-502">Clients may send the Content-MD5 header for a given Append Block operation as a means to ensure transactional integrity over the wire.</span></span> <span data-ttu-id="d8c39-503"><paramref name="contentMD5" />パラメーターにより、クライアントは、指定したバイトの範囲に提供することを事前に計算された MD5 値へのアクセスを既に持っています。</span><span class="sxs-lookup"><span data-stu-id="d8c39-503">The <paramref name="contentMD5" /> parameter permits clients who already have access to a pre-computed MD5 value for a given byte range to provide it.</span></span>
            <span data-ttu-id="d8c39-504">場合、<see cref="P:BlobRequestOptions.UseTransactionalMd5" />プロパティに設定されている<c>true</c>と<paramref name="contentMD5" />にパラメーターが設定されている<c>null</c>、クライアント ライブラリが MD5 値を内部で計算し、します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-504">If the <see cref="P:BlobRequestOptions.UseTransactionalMd5" /> property is set to <c>true</c> and the <paramref name="contentMD5" /> parameter is set to <c>null</c>, then the client library will calculate the MD5 value internally.</span></span>
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
        <param name="buffer"><span data-ttu-id="d8c39-505">バイト配列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-505">An array of bytes.</span></span></param>
        <param name="index"><span data-ttu-id="d8c39-506">Blob のバイトのアップロードを開始位置を示すバッファー内の 0 から始まるバイト オフセット。</span><span class="sxs-lookup"><span data-stu-id="d8c39-506">The zero-based byte offset in buffer at which to begin uploading bytes to the blob.</span></span></param>
        <param name="count"><span data-ttu-id="d8c39-507">Blob に書き込まれるバイト数。</span><span class="sxs-lookup"><span data-stu-id="d8c39-507">The number of bytes to be written to the blob.</span></span></param>
        <param name="callback"><span data-ttu-id="d8c39-508"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="d8c39-508">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="d8c39-509">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-509">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-510">追加 blob にバイト配列の内容を追加する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-510">Begins an asynchronous operation to append the contents of a byte array to an append blob.</span></span> <span data-ttu-id="d8c39-511">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-511">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-512"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-512">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-513">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-513">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-514">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-514">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>        
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
        <param name="buffer"><span data-ttu-id="d8c39-515">バイト配列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-515">An array of bytes.</span></span></param>
        <param name="index"><span data-ttu-id="d8c39-516">Blob のバイトのアップロードを開始位置を示すバッファー内の 0 から始まるバイト オフセット。</span><span class="sxs-lookup"><span data-stu-id="d8c39-516">The zero-based byte offset in buffer at which to begin uploading bytes to the blob.</span></span></param>
        <param name="count"><span data-ttu-id="d8c39-517">Blob に書き込まれるバイト数。</span><span class="sxs-lookup"><span data-stu-id="d8c39-517">The number of bytes to be written to the blob.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-518"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-518">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-519">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-519">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-520"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-520">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="d8c39-521"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="d8c39-521">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="d8c39-522">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-522">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-523">追加 blob にバイト配列の内容を追加する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-523">Begins an asynchronous operation to append the contents of a byte array to an append blob.</span></span> <span data-ttu-id="d8c39-524">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-524">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-525"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-525">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-526">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-526">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-527">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-527">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>        
            <span data-ttu-id="d8c39-528">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-528">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
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
        <param name="path"><span data-ttu-id="d8c39-529">Blob コンテンツを提供するファイルのパスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-529">A string containing the file path providing the blob content.</span></span></param>
        <param name="callback"><span data-ttu-id="d8c39-530"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="d8c39-530">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="d8c39-531">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-531">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-532">追加 blob にファイルを追加する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-532">Begins an asynchronous operation to append a file to an append blob.</span></span> <span data-ttu-id="d8c39-533">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-533">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-534"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-534">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-535">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-535">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-536">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-536">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>        
            <span data-ttu-id="d8c39-537">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-537">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
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
        <param name="path"><span data-ttu-id="d8c39-538">Blob コンテンツを提供するファイルのパスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-538">A string containing the file path providing the blob content.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-539"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-539">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-540">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-540">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-541"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-541">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="d8c39-542"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="d8c39-542">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="d8c39-543">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-543">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-544">追加 blob にファイルを追加する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-544">Begins an asynchronous operation to append a file to an append blob.</span></span> <span data-ttu-id="d8c39-545">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-545">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-546"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-546">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-547">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-547">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-548">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-548">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>        
            <span data-ttu-id="d8c39-549">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-549">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
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
        <param name="source"><span data-ttu-id="d8c39-550">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-550">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="callback"><span data-ttu-id="d8c39-551"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="d8c39-551">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="d8c39-552">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-552">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-553">追加 blob にストリームを追加する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-553">Begins an asynchronous operation to append a stream to an append blob.</span></span> <span data-ttu-id="d8c39-554">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-554">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-555"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-555">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-556">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-556">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-557">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-557">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>        
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
        <param name="source"><span data-ttu-id="d8c39-558">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-558">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="length"><span data-ttu-id="d8c39-559">開始位置からアップロードするストリームのソースからのバイト数を指定します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-559">Specifies the number of bytes from the Stream source to upload from the start position.</span></span></param>
        <param name="callback"><span data-ttu-id="d8c39-560"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="d8c39-560">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="d8c39-561">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-561">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-562">追加 blob にストリームを追加する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-562">Begins an asynchronous operation to append a stream to an append blob.</span></span> <span data-ttu-id="d8c39-563">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-563">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-564"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-564">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-565">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-565">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-566">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-566">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>        
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
        <param name="source"><span data-ttu-id="d8c39-567">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-567">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-568"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-568">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="d8c39-569">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="d8c39-569">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-570">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-570">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-571"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-571">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="d8c39-572"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="d8c39-572">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="d8c39-573">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-573">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-574">追加 blob にストリームを追加する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-574">Begins an asynchronous operation to append a stream to an append blob.</span></span> <span data-ttu-id="d8c39-575">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-575">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-576"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-576">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-577">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-577">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-578">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-578">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>        
            <span data-ttu-id="d8c39-579">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-579">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
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
        <param name="source"><span data-ttu-id="d8c39-580">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-580">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="length"><span data-ttu-id="d8c39-581">開始位置からアップロードするストリームのソースからのバイト数を指定します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-581">Specifies the number of bytes from the Stream source to upload from the start position.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-582"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-582">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="d8c39-583">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="d8c39-583">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-584">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-584">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-585"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-585">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="d8c39-586"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="d8c39-586">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="d8c39-587">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-587">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-588">追加 blob にストリームを追加する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-588">Begins an asynchronous operation to append a stream to an append blob.</span></span> <span data-ttu-id="d8c39-589">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-589">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-590"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-590">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-591">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-591">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-592">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-592">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>        
            <span data-ttu-id="d8c39-593">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-593">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
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
        <param name="content"><span data-ttu-id="d8c39-594">アップロードするテキストを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-594">A string containing the text to upload.</span></span></param>
        <param name="callback"><span data-ttu-id="d8c39-595"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="d8c39-595">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="d8c39-596">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-596">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-597">追加 blob にテキストの文字列を追加する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-597">Begins an asynchronous operation to append a string of text to an append blob.</span></span> <span data-ttu-id="d8c39-598">この API は、API は内部的に複数のライターのシナリオでは機能しませんが、重複するブロックを回避する追加オフセット条件ヘッダーを使用するため、単一ライターのシナリオで厳密に使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="d8c39-598">This API should be used strictly in a single writer scenario because the API internally uses the append-offset conditional header to avoid duplicate blocks which does not work in a multiple writer scenario.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-599"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-599">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
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
        <param name="content"><span data-ttu-id="d8c39-600">アップロードするテキストを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-600">A string containing the text to upload.</span></span></param>
        <param name="encoding"><span data-ttu-id="d8c39-601">A<see cref="T:System.Text.Encoding" />を使用するテキスト エンコーディングを示すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-601">A <see cref="T:System.Text.Encoding" /> object that indicates the text encoding to use.</span></span> <span data-ttu-id="d8c39-602">場合<c>null</c>utf-8 が使用されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-602">If <c>null</c>, UTF-8 will be used.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-603"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-603">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-604">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-604">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-605"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-605">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="d8c39-606"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="d8c39-606">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="d8c39-607">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-607">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-608">追加 blob にテキストの文字列を追加する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-608">Begins an asynchronous operation to append a string of text to an append blob.</span></span> <span data-ttu-id="d8c39-609">この API は、API は内部的に複数のライターのシナリオでは機能しませんが、重複するブロックを回避する追加オフセット条件ヘッダーを使用するため、単一ライターのシナリオで厳密に使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="d8c39-609">This API should be used strictly in a single writer scenario because the API internally uses the append-offset conditional header to avoid duplicate blocks which does not work in a multiple writer scenario.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-610"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-610">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-611">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-611">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
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
        <param name="callback"><span data-ttu-id="d8c39-612"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="d8c39-612">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="d8c39-613">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-613">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-614">空の追加 blob を作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-614">Begins an asynchronous operation to create an empty append blob.</span></span> <span data-ttu-id="d8c39-615">Blob が既に存在する場合はこの操作によって上書きされます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-615">If the blob already exists, this operation will overwrite it.</span></span> <span data-ttu-id="d8c39-616">使用して、上書きする代わりに、blob が存在する場合に例外をスローする<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginCreateOrReplace(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-616">To throw an exception if the blob exists, instead of overwriting, use <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginCreateOrReplace(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-617"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-617">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
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
        <param name="accessCondition"><span data-ttu-id="d8c39-618"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-618">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="d8c39-619">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="d8c39-619">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-620">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-620">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-621"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-621">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="d8c39-622"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="d8c39-622">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="d8c39-623">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-623">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-624">空の追加 blob を作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-624">Begins an asynchronous operation to create an empty append blob.</span></span> <span data-ttu-id="d8c39-625">Blob が既に存在する場合はこの操作によって上書きされます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-625">If the blob already exists, this operation will overwrite it.</span></span> <span data-ttu-id="d8c39-626">渡す、上書きする代わりに、blob が存在する場合に例外をスローする、<see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />オブジェクトを使用して生成<see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-626">To throw an exception if the blob exists, instead of overwriting, pass in an <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object generated using <see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-627"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-627">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
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
        <param name="callback"><span data-ttu-id="d8c39-628"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="d8c39-628">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="d8c39-629">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-629">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-630">Blob のスナップショットを作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-630">Begins an asynchronous operation to create a snapshot of the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-631"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-631">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
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
        <param name="metadata"><span data-ttu-id="d8c39-632">スナップショットのメタデータを定義する名前と値のペアのコレクション。</span><span class="sxs-lookup"><span data-stu-id="d8c39-632">A collection of name-value pairs defining the metadata of the snapshot.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-633"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-633">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="d8c39-634">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="d8c39-634">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-635">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> 、要求の追加オプションを指定するオブジェクトまたは<c>null</c>です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-635">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request, or <c>null</c>.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-636"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-636">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="d8c39-637"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="d8c39-637">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="d8c39-638">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-638">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-639">Blob のスナップショットを作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-639">Begins an asynchronous operation to create a snapshot of the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-640"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-640">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
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
        <param name="callback"><span data-ttu-id="d8c39-641"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="d8c39-641">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="d8c39-642">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-642">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-643">Blob の内容を文字列としてダウンロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-643">Begins an asynchronous operation to download the blob's contents as a string.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-644"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-644">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
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
        <param name="encoding"><span data-ttu-id="d8c39-645">使用するテキスト エンコーディングを示すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-645">An object that indicates the text encoding to use.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-646"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-646">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-647">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-647">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-648"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-648">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="d8c39-649"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="d8c39-649">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="d8c39-650">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-650">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-651">Blob の内容を文字列としてダウンロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-651">Begins an asynchronous operation to download the blob's contents as a string.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-652"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-652">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
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
        <param name="createNew"><span data-ttu-id="d8c39-653">使用して<c>true</c>追加して、新しい blob を作成または既存のものを上書きする<c>false</c>既存の blob に追加します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-653">Use <c>true</c> to create a new append blob or overwrite an existing one, <c>false</c> to append to an existing blob.</span></span></param>
        <param name="callback"><span data-ttu-id="d8c39-654"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="d8c39-654">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="d8c39-655">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-655">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-656">Blob に書き込むためのストリームを開く非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-656">Begins an asynchronous operation to open a stream for writing to the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-657"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-657">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-658">このメソッドへの呼び出しを常に、注意してください、<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginFetchAttributes(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />内部的メソッドです。</span><span class="sxs-lookup"><span data-stu-id="d8c39-658">Note that this method always makes a call to the <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginFetchAttributes(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" /> method under the covers.</span></span>
            <span data-ttu-id="d8c39-659">設定、 <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.StreamWriteSizeInBytes" /> mb 16 KB と 4 MB までの範囲のバイトの書き込みは、ブロック サイズを指定するには、このメソッドを呼び出す前に、プロパティです。</span><span class="sxs-lookup"><span data-stu-id="d8c39-659">Set the <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.StreamWriteSizeInBytes" /> property before calling this method to specify the block size to write, in bytes, ranging from between 16 KB and 4 MB inclusive.</span></span>
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
        <param name="createNew"><span data-ttu-id="d8c39-660">使用して<c>true</c>追加して、新しい blob を作成または既存のものを上書きする<c>false</c>既存の blob に追加します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-660">Use <c>true</c> to create a new append blob or overwrite an existing one, <c>false</c> to append to an existing blob.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-661"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-661">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="d8c39-662">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="d8c39-662">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-663">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-663">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-664"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-664">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="d8c39-665"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="d8c39-665">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="d8c39-666">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-666">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-667">Blob に書き込むためのストリームを開く非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-667">Begins an asynchronous operation to open a stream for writing to the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-668"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-668">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-669">このメソッドへの呼び出しを常に、注意してください、<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginFetchAttributes(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />内部的メソッドです。</span><span class="sxs-lookup"><span data-stu-id="d8c39-669">Note that this method always makes a call to the <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginFetchAttributes(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" /> method under the covers.</span></span>
            <span data-ttu-id="d8c39-670">設定、 <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.StreamWriteSizeInBytes" /> mb 16 KB と 4 MB までの範囲のバイトの書き込みは、ブロック サイズを指定するには、このメソッドを呼び出す前に、プロパティです。</span><span class="sxs-lookup"><span data-stu-id="d8c39-670">Set the <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.StreamWriteSizeInBytes" /> property before calling this method to specify the block size to write, in bytes, ranging from between 16 KB and 4 MB inclusive.</span></span>
            <span data-ttu-id="d8c39-671">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-671">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
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
        <param name="source"><span data-ttu-id="d8c39-672"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-672">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" /> object.</span></span></param>
        <param name="callback"><span data-ttu-id="d8c39-673"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="d8c39-673">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="d8c39-674">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-674">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-675">この追加 blob を別の追加 blob の内容、プロパティ、およびメタデータのコピーを開始する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-675">Begins an asynchronous operation to start copying another append blob's contents, properties, and metadata to this append blob.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-676"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-676">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
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
        <param name="source"><span data-ttu-id="d8c39-677"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-677">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" /> object.</span></span></param>
        <param name="sourceAccessCondition"><span data-ttu-id="d8c39-678"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー元 blob のアクセス条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-678">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the source blob.</span></span> <span data-ttu-id="d8c39-679">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="d8c39-679">If <c>null</c>, no condition is used.</span></span></param>
        <param name="destAccessCondition"><span data-ttu-id="d8c39-680"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー先 blob のアクセス条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-680">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the destination blob.</span></span> <span data-ttu-id="d8c39-681">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="d8c39-681">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-682">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-682">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-683"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-683">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="d8c39-684"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="d8c39-684">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="d8c39-685">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-685">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-686">この追加 blob を別の追加 blob の内容、プロパティ、およびメタデータのコピーを開始する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-686">Begins an asynchronous operation to start copying another append blob's contents, properties, and metadata to this append blob.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-687"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-687">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
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
        <param name="buffer"><span data-ttu-id="d8c39-688">バイト配列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-688">An array of bytes.</span></span></param>
        <param name="index"><span data-ttu-id="d8c39-689">Blob のバイトのアップロードを開始位置を示すバッファー内の 0 から始まるバイト オフセット。</span><span class="sxs-lookup"><span data-stu-id="d8c39-689">The zero-based byte offset in buffer at which to begin uploading bytes to the blob.</span></span></param>
        <param name="count"><span data-ttu-id="d8c39-690">Blob に書き込まれるバイト数。</span><span class="sxs-lookup"><span data-stu-id="d8c39-690">The number of bytes to be written to the blob.</span></span></param>
        <param name="callback"><span data-ttu-id="d8c39-691"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="d8c39-691">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="d8c39-692">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-692">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-693">バイト配列の内容を追加 blob にアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-693">Begins an asynchronous operation to upload the contents of a byte array to an append blob.</span></span> <span data-ttu-id="d8c39-694">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-694">If the blob already exists, it will be overwritten.</span></span> <span data-ttu-id="d8c39-695">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-695">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-696"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-696">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-697">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-697">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-698">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-698">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>
            <span data-ttu-id="d8c39-699">既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginAppendFromByteArray(System.Byte[],System.Int32,System.Int32,System.AsyncCallback,System.Object)" />です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-699">To append data to an append blob that already exists, see <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginAppendFromByteArray(System.Byte[],System.Int32,System.Int32,System.AsyncCallback,System.Object)" />.</span></span>
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
        <param name="buffer"><span data-ttu-id="d8c39-700">バイト配列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-700">An array of bytes.</span></span></param>
        <param name="index"><span data-ttu-id="d8c39-701">Blob のバイトのアップロードを開始位置を示すバッファー内の 0 から始まるバイト オフセット。</span><span class="sxs-lookup"><span data-stu-id="d8c39-701">The zero-based byte offset in buffer at which to begin uploading bytes to the blob.</span></span></param>
        <param name="count"><span data-ttu-id="d8c39-702">Blob に書き込まれるバイト数。</span><span class="sxs-lookup"><span data-stu-id="d8c39-702">The number of bytes to be written to the blob.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-703"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-703">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-704">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-704">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-705"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-705">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="d8c39-706"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="d8c39-706">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="d8c39-707">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-707">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-708">バイト配列の内容を追加 blob にアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-708">Begins an asynchronous operation to upload the contents of a byte array to an append blob.</span></span> <span data-ttu-id="d8c39-709">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-709">If the blob already exists, it will be overwritten.</span></span> <span data-ttu-id="d8c39-710">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-710">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-711"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-711">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-712">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-712">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-713">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-713">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>
            <span data-ttu-id="d8c39-714">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-714">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
            <span data-ttu-id="d8c39-715">既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginAppendFromByteArray(System.Byte[],System.Int32,System.Int32,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-715">To append data to an append blob that already exists, see <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginAppendFromByteArray(System.Byte[],System.Int32,System.Int32,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />.</span></span>
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
        <param name="path"><span data-ttu-id="d8c39-716">Blob コンテンツを提供するファイルのパスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-716">A string containing the file path providing the blob content.</span></span></param>
        <param name="callback"><span data-ttu-id="d8c39-717"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="d8c39-717">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="d8c39-718">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-718">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-719">追加 blob にファイルをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-719">Begins an asynchronous operation to upload a file to an append blob.</span></span> <span data-ttu-id="d8c39-720">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-720">If the blob already exists, it will be overwritten.</span></span> <span data-ttu-id="d8c39-721">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-721">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-722"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-722">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-723">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-723">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-724">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-724">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>        
            <span data-ttu-id="d8c39-725">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-725">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
            <span data-ttu-id="d8c39-726">既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginAppendFromFile(System.String,System.AsyncCallback,System.Object)" />です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-726">To append data to an append blob that already exists, see <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginAppendFromFile(System.String,System.AsyncCallback,System.Object)" />.</span></span>
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
        <param name="path"><span data-ttu-id="d8c39-727">Blob コンテンツを提供するファイルのパスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-727">A string containing the file path providing the blob content.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-728"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-728">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-729">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-729">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-730"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-730">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="d8c39-731"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="d8c39-731">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="d8c39-732">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-732">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-733">追加 blob にファイルをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-733">Begins an asynchronous operation to upload a file to an append blob.</span></span> <span data-ttu-id="d8c39-734">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-734">If the blob already exists, it will be overwritten.</span></span> <span data-ttu-id="d8c39-735">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-735">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-736"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-736">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-737">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-737">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-738">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-738">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>        
            <span data-ttu-id="d8c39-739">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-739">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
            <span data-ttu-id="d8c39-740">既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginAppendFromFile(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-740">To append data to an append blob that already exists, see <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginAppendFromFile(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />.</span></span>
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
        <param name="source"><span data-ttu-id="d8c39-741">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-741">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="callback"><span data-ttu-id="d8c39-742"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="d8c39-742">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="d8c39-743">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-743">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-744">追加 blob にストリームをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-744">Begins an asynchronous operation to upload a stream to an append blob.</span></span> <span data-ttu-id="d8c39-745">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-745">If the blob already exists, it will be overwritten.</span></span> <span data-ttu-id="d8c39-746">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-746">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-747"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-747">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-748">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-748">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-749">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-749">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>        
            <span data-ttu-id="d8c39-750">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-750">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
            <span data-ttu-id="d8c39-751">既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginAppendFromStream(System.IO.Stream,System.AsyncCallback,System.Object)" />です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-751">To append data to an append blob that already exists, see <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginAppendFromStream(System.IO.Stream,System.AsyncCallback,System.Object)" />.</span></span>
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
        <param name="source"><span data-ttu-id="d8c39-752">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-752">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="length"><span data-ttu-id="d8c39-753">開始位置からアップロードするストリームのソースからのバイト数を指定します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-753">Specifies the number of bytes from the Stream source to upload from the start position.</span></span></param>
        <param name="callback"><span data-ttu-id="d8c39-754"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="d8c39-754">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="d8c39-755">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-755">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-756">追加 blob にストリームをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-756">Begins an asynchronous operation to upload a stream to an append blob.</span></span> <span data-ttu-id="d8c39-757">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-757">If the blob already exists, it will be overwritten.</span></span> <span data-ttu-id="d8c39-758">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-758">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-759"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-759">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-760">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-760">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-761">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-761">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>        
            <span data-ttu-id="d8c39-762">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-762">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
            <span data-ttu-id="d8c39-763">既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginAppendFromStream(System.IO.Stream,System.Int64,System.AsyncCallback,System.Object)" />です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-763">To append data to an append blob that already exists, see <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginAppendFromStream(System.IO.Stream,System.Int64,System.AsyncCallback,System.Object)" />.</span></span>
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
        <param name="source"><span data-ttu-id="d8c39-764">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-764">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-765"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-765">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="d8c39-766">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="d8c39-766">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-767">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-767">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-768"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-768">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="d8c39-769"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="d8c39-769">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="d8c39-770">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-770">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-771">追加 blob にストリームをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-771">Begins an asynchronous operation to upload a stream to an append blob.</span></span> <span data-ttu-id="d8c39-772">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-772">If the blob already exists, it will be overwritten.</span></span> <span data-ttu-id="d8c39-773">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-773">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-774"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-774">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-775">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-775">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-776">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-776">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>        
            <span data-ttu-id="d8c39-777">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-777">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
            <span data-ttu-id="d8c39-778">既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginAppendFromStream(System.IO.Stream,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-778">To append data to an append blob that already exists, see <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginAppendFromStream(System.IO.Stream,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />.</span></span>
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
        <param name="source"><span data-ttu-id="d8c39-779">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-779">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="length"><span data-ttu-id="d8c39-780">開始位置からアップロードするストリームのソースからのバイト数を指定します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-780">Specifies the number of bytes from the Stream source to upload from the start position.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-781"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-781">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="d8c39-782">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="d8c39-782">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-783">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-783">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-784"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-784">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="d8c39-785"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="d8c39-785">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="d8c39-786">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-786">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-787">追加 blob にストリームをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-787">Begins an asynchronous operation to upload a stream to an append blob.</span></span> <span data-ttu-id="d8c39-788">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-788">If the blob already exists, it will be overwritten.</span></span> <span data-ttu-id="d8c39-789">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-789">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-790"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-790">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-791">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-791">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-792">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-792">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>        
            <span data-ttu-id="d8c39-793">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-793">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
            <span data-ttu-id="d8c39-794">既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginAppendFromStream(System.IO.Stream,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-794">To append data to an append blob that already exists, see <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginAppendFromStream(System.IO.Stream,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />.</span></span>
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
        <param name="content"><span data-ttu-id="d8c39-795">アップロードするテキストを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-795">A string containing the text to upload.</span></span></param>
        <param name="callback"><span data-ttu-id="d8c39-796"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="d8c39-796">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="d8c39-797">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-797">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-798">テキストの文字列を追加 blob にアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-798">Begins an asynchronous operation to upload a string of text to an append blob.</span></span> <span data-ttu-id="d8c39-799">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-799">If the blob already exists, it will be overwritten.</span></span> <span data-ttu-id="d8c39-800">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-800">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-801"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-801">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-802">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-802">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-803">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-803">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>
            <span data-ttu-id="d8c39-804">既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginAppendText(System.String,System.AsyncCallback,System.Object)" />です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-804">To append data to an append blob that already exists, see <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginAppendText(System.String,System.AsyncCallback,System.Object)" />.</span></span>
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
        <param name="content"><span data-ttu-id="d8c39-805">アップロードするテキストを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-805">A string containing the text to upload.</span></span></param>
        <param name="encoding"><span data-ttu-id="d8c39-806">A<see cref="T:System.Text.Encoding" />を使用するテキスト エンコーディングを示すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-806">A <see cref="T:System.Text.Encoding" /> object that indicates the text encoding to use.</span></span> <span data-ttu-id="d8c39-807">場合<c>null</c>utf-8 が使用されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-807">If <c>null</c>, UTF-8 will be used.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-808"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-808">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-809">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-809">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-810"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-810">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="d8c39-811"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="d8c39-811">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="d8c39-812">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-812">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-813">テキストの文字列を追加 blob にアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-813">Begins an asynchronous operation to upload a string of text to an append blob.</span></span> <span data-ttu-id="d8c39-814">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-814">If the blob already exists, it will be overwritten.</span></span> <span data-ttu-id="d8c39-815">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-815">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-816"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-816">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-817">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-817">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-818">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-818">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>
            <span data-ttu-id="d8c39-819">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-819">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
            <span data-ttu-id="d8c39-820">既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginAppendText(System.String,System.Text.Encoding,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-820">To append data to an append blob that already exists, see <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.BeginAppendText(System.String,System.Text.Encoding,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />.</span></span>
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
        <param name="accessCondition"><span data-ttu-id="d8c39-821"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-821">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="d8c39-822">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="d8c39-822">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-823">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-823">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="d8c39-824">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-824">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-825"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-825">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-826">空の追加 blob を作成します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-826">Creates an empty append blob.</span></span> <span data-ttu-id="d8c39-827">Blob が既に存在する場合はこの操作によって上書きされます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-827">If the blob already exists, this operation will overwrite it.</span></span> <span data-ttu-id="d8c39-828">渡す、上書きする代わりに、blob が存在する場合に例外をスローする、<see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />オブジェクトを使用して生成<see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-828">To throw an exception if the blob exists, instead of overwriting, pass in an <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object generated using <see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />.</span></span>
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
            <span data-ttu-id="d8c39-829">空の追加 blob を作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-829">Initiates an asynchronous operation to create an empty append blob.</span></span> <span data-ttu-id="d8c39-830">Blob が既に存在する場合はこの操作によって上書きされます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-830">If the blob already exists, this operation will overwrite it.</span></span> <span data-ttu-id="d8c39-831">使用して、上書きする代わりに、blob が存在する場合に例外をスローする<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.CreateOrReplaceAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-831">To throw an exception if the blob exists, instead of overwriting, use <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.CreateOrReplaceAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-832">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-832">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
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
        <param name="cancellationToken"><span data-ttu-id="d8c39-833">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="d8c39-833">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-834">追加 blob を作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-834">Initiates an asynchronous operation to create an append blob.</span></span> <span data-ttu-id="d8c39-835">Blob が既に存在する場合はこの操作によって上書きされます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-835">If the blob already exists, this operation will overwrite it.</span></span> <span data-ttu-id="d8c39-836">使用して、上書きする代わりに、blob が存在する場合に例外をスローする<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.CreateOrReplaceAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-836">To throw an exception if the blob exists, instead of overwriting, use <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.CreateOrReplaceAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-837">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-837">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
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
        <param name="accessCondition"><span data-ttu-id="d8c39-838"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-838">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="d8c39-839">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="d8c39-839">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-840">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-840">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-841"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-841">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-842">空の追加 blob を作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-842">Initiates an asynchronous operation to create an empty append blob.</span></span> <span data-ttu-id="d8c39-843">Blob が既に存在する場合はこの操作によって上書きされます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-843">If the blob already exists, this operation will overwrite it.</span></span> <span data-ttu-id="d8c39-844">渡す、上書きする代わりに、blob が存在する場合に例外をスローする、<see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />オブジェクトを使用して生成<see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-844">To throw an exception if the blob exists, instead of overwriting, pass in an <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object generated using <see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-845">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-845">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
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
        <param name="accessCondition"><span data-ttu-id="d8c39-846"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-846">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="d8c39-847">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="d8c39-847">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-848">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-848">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-849"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-849">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d8c39-850">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="d8c39-850">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-851">空の追加 blob を作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-851">Initiates an asynchronous operation to create an empty append blob.</span></span> <span data-ttu-id="d8c39-852">Blob が既に存在する場合はこの操作によって上書きされます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-852">If the blob already exists, this operation will overwrite it.</span></span> <span data-ttu-id="d8c39-853">渡す、上書きする代わりに、blob が存在する場合に例外をスローする、<see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />オブジェクトを使用して生成<see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-853">To throw an exception if the blob exists, instead of overwriting, pass in an <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object generated using <see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-854">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-854">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
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
        <param name="metadata"><span data-ttu-id="d8c39-855">スナップショットのメタデータを定義する名前と値のペアのコレクション。</span><span class="sxs-lookup"><span data-stu-id="d8c39-855">A collection of name-value pairs defining the metadata of the snapshot.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-856"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-856">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="d8c39-857">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="d8c39-857">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-858">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> 、要求の追加オプションを指定するオブジェクトまたは<c>null</c>です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-858">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request, or <c>null</c>.</span></span> <span data-ttu-id="d8c39-859">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-859">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-860"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-860">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-861">Blob のスナップショットを作成します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-861">Creates a snapshot of the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-862">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" /> blob のスナップショットであるオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-862">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" /> object that is a blob snapshot.</span></span></returns>
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
            <span data-ttu-id="d8c39-863">Blob のスナップショットを作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-863">Initiates an asynchronous operation to create a snapshot of the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-864">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="d8c39-864">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" /> that represents the asynchronous operation.</span></span></returns>
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
        <param name="cancellationToken"><span data-ttu-id="d8c39-865">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="d8c39-865">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-866">Blob のスナップショットを作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-866">Initiates an asynchronous operation to create a snapshot of the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-867">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="d8c39-867">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" /> that represents the asynchronous operation.</span></span></returns>
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
        <param name="metadata"><span data-ttu-id="d8c39-868">スナップショットのメタデータを定義する名前と値のペアのコレクション。</span><span class="sxs-lookup"><span data-stu-id="d8c39-868">A collection of name-value pairs defining the metadata of the snapshot.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-869"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-869">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="d8c39-870">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="d8c39-870">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-871">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-871">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-872"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-872">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-873">Blob のスナップショットを作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-873">Initiates an asynchronous operation to create a snapshot of the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-874">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="d8c39-874">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" /> that represents the asynchronous operation.</span></span></returns>
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
        <param name="metadata"><span data-ttu-id="d8c39-875">スナップショットのメタデータを定義する名前と値のペアのコレクション。</span><span class="sxs-lookup"><span data-stu-id="d8c39-875">A collection of name-value pairs defining the metadata of the snapshot.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-876"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-876">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="d8c39-877">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="d8c39-877">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-878">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-878">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-879"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-879">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d8c39-880">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="d8c39-880">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-881">Blob のスナップショットを作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-881">Initiates an asynchronous operation to create a snapshot of the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-882">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="d8c39-882">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" /> that represents the asynchronous operation.</span></span></returns>
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
        <param name="encoding"><span data-ttu-id="d8c39-883">使用するテキスト エンコーディングを示すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-883">An object that indicates the text encoding to use.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-884"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-884">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-885">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-885">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="d8c39-886">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-886">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-887"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-887">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-888">Blob の内容を文字列としてダウンロードします。</span><span class="sxs-lookup"><span data-stu-id="d8c39-888">Downloads the blob's contents as a string.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-889">文字列として、blob の内容。</span><span class="sxs-lookup"><span data-stu-id="d8c39-889">The contents of the blob, as a string.</span></span></returns>
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
            <span data-ttu-id="d8c39-890">Blob の内容を文字列としてダウンロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-890">Initiates an asynchronous operation to download the blob's contents as a string.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-891">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>文字列</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="d8c39-891">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>string</c> that represents the asynchronous operation.</span></span></returns>
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
        <param name="cancellationToken"><span data-ttu-id="d8c39-892">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="d8c39-892">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-893">Blob の内容を文字列としてダウンロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-893">Initiates an asynchronous operation to download the blob's contents as a string.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-894">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>文字列</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="d8c39-894">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>string</c> that represents the asynchronous operation.</span></span></returns>
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
        <param name="encoding"><span data-ttu-id="d8c39-895">使用するテキスト エンコーディングを示すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-895">An object that indicates the text encoding to use.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-896"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-896">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-897">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-897">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-898"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-898">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-899">Blob の内容を文字列としてダウンロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-899">Initiates an asynchronous operation to download the blob's contents as a string.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-900">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>文字列</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="d8c39-900">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>string</c> that represents the asynchronous operation.</span></span></returns>
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
        <param name="encoding"><span data-ttu-id="d8c39-901">使用するテキスト エンコーディングを示すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-901">An object that indicates the text encoding to use.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-902"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-902">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-903">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-903">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-904"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-904">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d8c39-905">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="d8c39-905">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-906">Blob の内容を文字列としてダウンロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-906">Initiates an asynchronous operation to download the blob's contents as a string.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-907">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>文字列</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="d8c39-907">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>string</c> that represents the asynchronous operation.</span></span></returns>
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
        <param name="encoding"><span data-ttu-id="d8c39-908">使用するテキスト エンコーディングを示すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-908">An object that indicates the text encoding to use.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-909"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-909">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-910">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-910">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-911"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-911">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="progressHandler"> <span data-ttu-id="d8c39-912">A<see cref="T:System.IProgress`1" />を処理するオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" />メッセージ。</span><span class="sxs-lookup"><span data-stu-id="d8c39-912">A <see cref="T:System.IProgress`1" /> object to handle <see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" /> messages.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d8c39-913">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="d8c39-913">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-914">Blob の内容を文字列としてダウンロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-914">Initiates an asynchronous operation to download the blob's contents as a string.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-915">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>文字列</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="d8c39-915">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>string</c> that represents the asynchronous operation.</span></span></returns>
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
        <param name="asyncResult"><span data-ttu-id="d8c39-916"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-916">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-917">Blob の末尾に新しいデータのブロックをコミットする非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-917">Ends an asynchronous operation to commit a new block of data to the end of the blob.</span></span>
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
        <param name="asyncResult"><span data-ttu-id="d8c39-918"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-918">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-919">追加 blob にバイト配列の内容を追加する非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-919">Ends an asynchronous operation to append the contents of a byte array to an append blob.</span></span> <span data-ttu-id="d8c39-920">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-920">Recommended only for single-writer scenarios.</span></span>
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
        <param name="asyncResult"><span data-ttu-id="d8c39-921"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-921">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-922">追加 blob にファイルをアップロードする非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-922">Ends an asynchronous operation to upload a file to an append blob.</span></span> <span data-ttu-id="d8c39-923">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-923">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="d8c39-924">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-924">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-925">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-925">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>        
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
        <param name="asyncResult"><span data-ttu-id="d8c39-926"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-926">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-927">追加 blob にストリームを追加する非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-927">Ends an asynchronous operation to append a stream to an append blob.</span></span> 
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
        <param name="asyncResult"><span data-ttu-id="d8c39-928"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-928">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-929">追加 blob にテキストの文字列を追加する非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-929">Ends an asynchronous operation to append a string of text to an append blob.</span></span> <span data-ttu-id="d8c39-930">この API は、API は内部的に複数のライターのシナリオでは機能しませんが、重複するブロックを回避する追加オフセット条件ヘッダーを使用するため、単一ライターのシナリオで厳密に使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="d8c39-930">This API should be used strictly in a single writer scenario because the API internally uses the append-offset conditional header to avoid duplicate blocks which does not work in a multiple writer scenario.</span></span>
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
        <param name="asyncResult"><span data-ttu-id="d8c39-931"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-931">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-932">追加 blob を作成する非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-932">Ends an asynchronous operation to create an append blob.</span></span>
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
        <param name="asyncResult"><span data-ttu-id="d8c39-933"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-933">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-934">Blob のスナップショットを作成する非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-934">Ends an asynchronous operation to create a snapshot of the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-935">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" /> blob のスナップショットであるオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-935">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" /> object that is a blob snapshot.</span></span></returns>
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
        <param name="asyncResult"><span data-ttu-id="d8c39-936"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-936">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-937">Blob の内容を文字列としてダウンロードする非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-937">Ends an asynchronous operation to download the blob's contents as a string.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-938">文字列として、blob の内容。</span><span class="sxs-lookup"><span data-stu-id="d8c39-938">The contents of the blob, as a string.</span></span></returns>
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
        <param name="asyncResult"><span data-ttu-id="d8c39-939"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-939">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-940">Blob に書き込むためのストリームを開く非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-940">Ends an asynchronous operation to open a stream for writing to the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-941"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-941">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" /> object.</span></span></returns>
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
        <param name="asyncResult"><span data-ttu-id="d8c39-942"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-942">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-943">バイト配列の内容を追加 blob にアップロードする非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-943">Ends an asynchronous operation to upload the contents of a byte array to an append blob.</span></span> <span data-ttu-id="d8c39-944">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-944">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="d8c39-945">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-945">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-946">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-946">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>        
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
        <param name="asyncResult"><span data-ttu-id="d8c39-947"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-947">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-948">追加 blob にファイルをアップロードする非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-948">Ends an asynchronous operation to upload a file to an append blob.</span></span> <span data-ttu-id="d8c39-949">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-949">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="d8c39-950">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-950">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-951">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-951">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>        
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
        <param name="asyncResult"><span data-ttu-id="d8c39-952"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-952">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-953">追加 blob にストリームをアップロードする非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-953">Ends an asynchronous operation to upload a stream to an append blob.</span></span> 
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
        <param name="asyncResult"><span data-ttu-id="d8c39-954"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-954">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-955">テキストの文字列を追加 blob にアップロードする非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-955">Ends an asynchronous operation to upload a string of text to an append blob.</span></span> <span data-ttu-id="d8c39-956">この API は、API は内部的に複数のライターのシナリオでは機能しませんが、重複するブロックを回避する追加オフセット条件ヘッダーを使用するため、単一ライターのシナリオで厳密に使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="d8c39-956">This API should be used strictly in a single writer scenario because the API internally uses the append-offset conditional header to avoid duplicate blocks which does not work in a multiple writer scenario.</span></span>
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
        <param name="createNew"><span data-ttu-id="d8c39-957">使用して<c>true</c>追加して、新しい blob を作成または既存のものを上書きする<c>false</c>既存の blob に追加します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-957">Use <c>true</c> to create a new append blob or overwrite an existing one, <c>false</c> to append to an existing blob.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-958"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-958">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="d8c39-959">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="d8c39-959">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-960">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-960">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="d8c39-961">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-961">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-962"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-962">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-963">Blob に書き込むためのストリームを開きます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-963">Opens a stream for writing to the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-964"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-964">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" /> object.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-965">このメソッドへの呼び出しを常に、注意してください、<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributes(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />内部的メソッドです。</span><span class="sxs-lookup"><span data-stu-id="d8c39-965">Note that this method always makes a call to the <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributes(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" /> method under the covers.</span></span>
            <span data-ttu-id="d8c39-966">設定、 <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.StreamWriteSizeInBytes" /> mb 16 KB と 4 MB までの範囲のバイトの書き込みは、ブロック サイズを指定するには、このメソッドを呼び出す前に、プロパティです。</span><span class="sxs-lookup"><span data-stu-id="d8c39-966">Set the <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.StreamWriteSizeInBytes" /> property before calling this method to specify the block size to write, in bytes, ranging from between 16 KB and 4 MB inclusive.</span></span>
            <span data-ttu-id="d8c39-967">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-967">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
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
        <param name="createNew"><span data-ttu-id="d8c39-968">使用して<c>true</c>追加して、新しい blob を作成または既存のものを上書きする<c>false</c>既存の blob に追加します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-968">Use <c>true</c> to create a new append blob or overwrite an existing one, <c>false</c> to append to an existing blob.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-969">Blob に書き込むためのストリームを開く非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-969">Initiates an asynchronous operation to open a stream for writing to the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-970">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="d8c39-970">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-971">このメソッドへの呼び出しを常に、注意してください、<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginFetchAttributes(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />内部的メソッドです。</span><span class="sxs-lookup"><span data-stu-id="d8c39-971">Note that this method always makes a call to the <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginFetchAttributes(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" /> method under the covers.</span></span>
            <span data-ttu-id="d8c39-972">設定、 <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.StreamWriteSizeInBytes" /> mb 16 KB と 4 MB までの範囲のバイトの書き込みは、ブロック サイズを指定するには、このメソッドを呼び出す前に、プロパティです。</span><span class="sxs-lookup"><span data-stu-id="d8c39-972">Set the <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.StreamWriteSizeInBytes" /> property before calling this method to specify the block size to write, in bytes, ranging from between 16 KB and 4 MB inclusive.</span></span>
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
        <param name="createNew"><span data-ttu-id="d8c39-973">使用して<c>true</c>追加して、新しい blob を作成または既存のものを上書きする<c>false</c>既存の blob に追加します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-973">Use <c>true</c> to create a new append blob or overwrite an existing one, <c>false</c> to append to an existing blob.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d8c39-974">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="d8c39-974">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-975">Blob に書き込むためのストリームを開く非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-975">Initiates an asynchronous operation to open a stream for writing to the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-976">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="d8c39-976">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-977">このメソッドへの呼び出しを常に、注意してください、<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributesAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />内部的メソッドです。</span><span class="sxs-lookup"><span data-stu-id="d8c39-977">Note that this method always makes a call to the <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributesAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" /> method under the covers.</span></span>
            <span data-ttu-id="d8c39-978">設定、 <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.StreamWriteSizeInBytes" /> mb 16 KB と 4 MB までの範囲のバイトの書き込みは、ブロック サイズを指定するには、このメソッドを呼び出す前に、プロパティです。</span><span class="sxs-lookup"><span data-stu-id="d8c39-978">Set the <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.StreamWriteSizeInBytes" /> property before calling this method to specify the block size to write, in bytes, ranging from between 16 KB and 4 MB inclusive.</span></span>
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
        <param name="createNew"><span data-ttu-id="d8c39-979">使用して<c>true</c>追加して、新しい blob を作成または既存のものを上書きする<c>false</c>既存の blob に追加します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-979">Use <c>true</c> to create a new append blob or overwrite an existing one, <c>false</c> to append to an existing blob.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-980"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-980">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="d8c39-981">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="d8c39-981">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-982">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-982">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-983"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-983">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-984">Blob に書き込むためのストリームを開く非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-984">Initiates an asynchronous operation to open a stream for writing to the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-985">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="d8c39-985">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-986">このメソッドへの呼び出しを常に、注意してください、<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributesAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />内部的メソッドです。</span><span class="sxs-lookup"><span data-stu-id="d8c39-986">Note that this method always makes a call to the <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributesAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" /> method under the covers.</span></span>
            <span data-ttu-id="d8c39-987">設定、 <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.StreamWriteSizeInBytes" /> mb 16 KB と 4 MB までの範囲のバイトの書き込みは、ブロック サイズを指定するには、このメソッドを呼び出す前に、プロパティです。</span><span class="sxs-lookup"><span data-stu-id="d8c39-987">Set the <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.StreamWriteSizeInBytes" /> property before calling this method to specify the block size to write, in bytes, ranging from between 16 KB and 4 MB inclusive.</span></span>
            <span data-ttu-id="d8c39-988">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-988">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
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
        <param name="createNew"><span data-ttu-id="d8c39-989">使用して<c>true</c>追加して、新しい blob を作成または既存のものを上書きする<c>false</c>既存の blob に追加します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-989">Use <c>true</c> to create a new append blob or overwrite an existing one, <c>false</c> to append to an existing blob.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-990"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-990">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="d8c39-991">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="d8c39-991">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-992">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-992">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-993"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-993">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d8c39-994">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="d8c39-994">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-995">Blob に書き込むためのストリームを開く非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-995">Initiates an asynchronous operation to open a stream for writing to the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-996">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="d8c39-996">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-997">このメソッドへの呼び出しを常に、注意してください、<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributesAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />内部的メソッドです。</span><span class="sxs-lookup"><span data-stu-id="d8c39-997">Note that this method always makes a call to the <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributesAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" /> method under the covers.</span></span>
            <span data-ttu-id="d8c39-998">設定、 <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.StreamWriteSizeInBytes" /> mb 16 KB と 4 MB までの範囲のバイトの書き込みは、ブロック サイズを指定するには、このメソッドを呼び出す前に、プロパティです。</span><span class="sxs-lookup"><span data-stu-id="d8c39-998">Set the <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.StreamWriteSizeInBytes" /> property before calling this method to specify the block size to write, in bytes, ranging from between 16 KB and 4 MB inclusive.</span></span>
            <span data-ttu-id="d8c39-999">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-999">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
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
        <param name="source"><span data-ttu-id="d8c39-1000"><see cref="T:System.Uri" />コピー元 blob のです。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1000">The <see cref="T:System.Uri" /> of the source blob.</span></span></param>
        <param name="sourceAccessCondition"><span data-ttu-id="d8c39-1001"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー元 blob のアクセス条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1001">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the source blob.</span></span> <span data-ttu-id="d8c39-1002">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1002">If <c>null</c>, no condition is used.</span></span></param>
        <param name="destAccessCondition"><span data-ttu-id="d8c39-1003"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー先 blob のアクセス条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1003">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the destination blob.</span></span> <span data-ttu-id="d8c39-1004">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1004">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-1005">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1005">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="d8c39-1006">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1006">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-1007"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1007">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-1008">この追加 blob を別の追加 blob の内容、プロパティ、およびメタデータのコピーを開始するための操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1008">Begins an operation to start copying another append blob's contents, properties, and metadata to this append blob.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-1009">コピー操作に関連付けられたコピー ID です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1009">The copy ID associated with the copy operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-1010">このメソッドは、blob の ETag、最終更新時刻、および一部のコピー状態をフェッチします。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1010">This method fetches the blob's ETag, last-modified time, and part of the copy state.</span></span>
            <span data-ttu-id="d8c39-1011">コピー ID とコピーのステータス フィールドがフェッチされ、残りのコピーの状態がクリアされます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1011">The copy ID and copy status fields are fetched, and the rest of the copy state is cleared.</span></span>
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
        <param name="source"><span data-ttu-id="d8c39-1012"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1012">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-1013">この追加 blob を別の追加 blob の内容、プロパティ、およびメタデータのコピーを開始する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1013">Initiates an asynchronous operation to start copying another append blob's contents, properties, and metadata to this append blob.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-1014">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>文字列</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1014">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>string</c> that represents the asynchronous operation.</span></span></returns>
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
        <param name="source"><span data-ttu-id="d8c39-1015"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1015">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" /> object.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d8c39-1016">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1016">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-1017">この追加 blob を別の追加 blob の内容、プロパティ、およびメタデータのコピーを開始する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1017">Initiates an asynchronous operation to start copying another append blob's contents, properties, and metadata to this append blob.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-1018">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>文字列</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1018">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>string</c> that represents the asynchronous operation.</span></span></returns>
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
        <param name="source"><span data-ttu-id="d8c39-1019"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1019">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" /> object.</span></span></param>
        <param name="sourceAccessCondition"><span data-ttu-id="d8c39-1020"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー元 blob のアクセス条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1020">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the source blob.</span></span> <span data-ttu-id="d8c39-1021">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1021">If <c>null</c>, no condition is used.</span></span></param>
        <param name="destAccessCondition"><span data-ttu-id="d8c39-1022"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー先 blob のアクセス条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1022">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the destination blob.</span></span> <span data-ttu-id="d8c39-1023">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1023">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-1024">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1024">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-1025"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1025">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-1026">この追加 blob を別の追加 blob の内容、プロパティ、およびメタデータのコピーを開始する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1026">Initiates an asynchronous operation to start copying another append blob's contents, properties, and metadata to this append blob.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-1027">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>文字列</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1027">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>string</c> that represents the asynchronous operation.</span></span></returns>
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
        <param name="source"><span data-ttu-id="d8c39-1028"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1028">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" /> object.</span></span></param>
        <param name="sourceAccessCondition"><span data-ttu-id="d8c39-1029"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー元 blob のアクセス条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1029">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the source blob.</span></span> <span data-ttu-id="d8c39-1030">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1030">If <c>null</c>, no condition is used.</span></span></param>
        <param name="destAccessCondition"><span data-ttu-id="d8c39-1031"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />コピー先 blob のアクセス条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1031">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the destination blob.</span></span> <span data-ttu-id="d8c39-1032">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1032">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-1033">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1033">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-1034"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1034">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d8c39-1035">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1035">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-1036">この追加 blob を別の追加 blob の内容、プロパティ、およびメタデータのコピーを開始する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1036">Initiates an asynchronous operation to start copying another append blob's contents, properties, and metadata to this append blob.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-1037">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>文字列</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1037">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>string</c> that represents the asynchronous operation.</span></span></returns>
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
            <span data-ttu-id="d8c39-1038">取得または追加 blob ストリームに書き込むときにバッファーに書き込むバイト数を設定します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1038">Gets or sets the number of bytes to buffer when writing to an append blob stream.</span></span>
            </summary>
        <value><span data-ttu-id="d8c39-1039">(バイト単位) mb 16 KB と 4 MB までの範囲内のブロックのサイズ。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1039">The size of a block, in bytes, ranging from between 16 KB and 4 MB inclusive.</span></span></value>
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
        <param name="buffer"><span data-ttu-id="d8c39-1040">バイト配列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1040">An array of bytes.</span></span></param>
        <param name="index"><span data-ttu-id="d8c39-1041">Blob のバイトのアップロードを開始位置を示すバッファー内の 0 から始まるバイト オフセット。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1041">The zero-based byte offset in buffer at which to begin uploading bytes to the blob.</span></span></param>
        <param name="count"><span data-ttu-id="d8c39-1042">Blob に書き込まれるバイト数。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1042">The number of bytes to be written to the blob.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-1043"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1043">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-1044">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1044">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="d8c39-1045">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1045">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-1046"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1046">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-1047">バイト配列の内容を追加 blob にアップロードします。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1047">Uploads the contents of a byte array to an append blob.</span></span> <span data-ttu-id="d8c39-1048">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1048">If the blob already exists, it will be overwritten.</span></span> <span data-ttu-id="d8c39-1049">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1049">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="d8c39-1050">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1050">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-1051">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1051">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>        
            <span data-ttu-id="d8c39-1052">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1052">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
            <span data-ttu-id="d8c39-1053">既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromByteArray(System.Byte[],System.Int32,System.Int32,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1053">To append data to an append blob that already exists, see <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromByteArray(System.Byte[],System.Int32,System.Int32,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />.</span></span>
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
        <param name="buffer"><span data-ttu-id="d8c39-1054">バイト配列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1054">An array of bytes.</span></span></param>
        <param name="index"><span data-ttu-id="d8c39-1055">Blob のバイトのアップロードを開始位置を示すバッファー内の 0 から始まるバイト オフセット。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1055">The zero-based byte offset in buffer at which to begin uploading bytes to the blob.</span></span></param>
        <param name="count"><span data-ttu-id="d8c39-1056">Blob に書き込まれるバイト数。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1056">The number of bytes to be written to the blob.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-1057">バイト配列の内容を追加 blob にアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1057">Initiates an asynchronous operation to upload the contents of a byte array to an append blob.</span></span> <span data-ttu-id="d8c39-1058">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1058">If the blob already exists, it will be overwritten.</span></span> <span data-ttu-id="d8c39-1059">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1059">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-1060">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1060">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-1061">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1061">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-1062">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1062">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>
            <span data-ttu-id="d8c39-1063">既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromByteArrayAsync(System.Byte[],System.Int32,System.Int32)" />です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1063">To append data to an append blob that already exists, see <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromByteArrayAsync(System.Byte[],System.Int32,System.Int32)" />.</span></span>
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
        <param name="buffer"><span data-ttu-id="d8c39-1064">バイト配列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1064">An array of bytes.</span></span></param>
        <param name="index"><span data-ttu-id="d8c39-1065">Blob のバイトのアップロードを開始位置を示すバッファー内の 0 から始まるバイト オフセット。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1065">The zero-based byte offset in buffer at which to begin uploading bytes to the blob.</span></span></param>
        <param name="count"><span data-ttu-id="d8c39-1066">Blob に書き込まれるバイト数。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1066">The number of bytes to be written to the blob.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d8c39-1067">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1067">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-1068">バイト配列の内容を追加 blob にアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1068">Initiates an asynchronous operation to upload the contents of a byte array to an append blob.</span></span> <span data-ttu-id="d8c39-1069">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1069">If the blob already exists, it will be overwritten.</span></span> <span data-ttu-id="d8c39-1070">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1070">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-1071">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1071">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-1072">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1072">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-1073">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1073">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>
            <span data-ttu-id="d8c39-1074">既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromByteArrayAsync(System.Byte[],System.Int32,System.Int32,System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1074">To append data to an append blob that already exists, see <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromByteArrayAsync(System.Byte[],System.Int32,System.Int32,System.Threading.CancellationToken)" />.</span></span>
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
        <param name="buffer"><span data-ttu-id="d8c39-1075">バイト配列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1075">An array of bytes.</span></span></param>
        <param name="index"><span data-ttu-id="d8c39-1076">Blob のバイトのアップロードを開始位置を示すバッファー内の 0 から始まるバイト オフセット。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1076">The zero-based byte offset in buffer at which to begin uploading bytes to the blob.</span></span></param>
        <param name="count"><span data-ttu-id="d8c39-1077">Blob に書き込まれるバイト数。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1077">The number of bytes to be written to the blob.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-1078"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1078">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-1079">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1079">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-1080"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1080">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-1081">バイト配列の内容を追加 blob にアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1081">Initiates an asynchronous operation to upload the contents of a byte array to an append blob.</span></span> <span data-ttu-id="d8c39-1082">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1082">If the blob already exists, it will be overwritten.</span></span> <span data-ttu-id="d8c39-1083">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1083">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-1084">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1084">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-1085">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1085">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-1086">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1086">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>
            <span data-ttu-id="d8c39-1087">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1087">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
            <span data-ttu-id="d8c39-1088">既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromByteArrayAsync(System.Byte[],System.Int32,System.Int32,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1088">To append data to an append blob that already exists, see <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromByteArrayAsync(System.Byte[],System.Int32,System.Int32,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />.</span></span>
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
        <param name="buffer"><span data-ttu-id="d8c39-1089">バイト配列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1089">An array of bytes.</span></span></param>
        <param name="index"><span data-ttu-id="d8c39-1090">Blob のバイトのアップロードを開始位置を示すバッファー内の 0 から始まるバイト オフセット。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1090">The zero-based byte offset in buffer at which to begin uploading bytes to the blob.</span></span></param>
        <param name="count"><span data-ttu-id="d8c39-1091">Blob に書き込まれるバイト数。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1091">The number of bytes to be written to the blob.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-1092"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1092">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-1093">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1093">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-1094"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1094">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d8c39-1095">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1095">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-1096">バイト配列の内容を追加 blob にアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1096">Initiates an asynchronous operation to upload the contents of a byte array to an append blob.</span></span> <span data-ttu-id="d8c39-1097">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1097">If the blob already exists, it will be overwritten.</span></span> <span data-ttu-id="d8c39-1098">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1098">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-1099">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1099">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-1100">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1100">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-1101">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1101">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>
            <span data-ttu-id="d8c39-1102">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1102">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
            <span data-ttu-id="d8c39-1103">既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromByteArrayAsync(System.Byte[],System.Int32,System.Int32,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1103">To append data to an append blob that already exists, see <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromByteArrayAsync(System.Byte[],System.Int32,System.Int32,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />.</span></span>
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
        <param name="buffer"><span data-ttu-id="d8c39-1104">バイト配列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1104">An array of bytes.</span></span></param>
        <param name="index"><span data-ttu-id="d8c39-1105">Blob のバイトのアップロードを開始位置を示すバッファー内の 0 から始まるバイト オフセット。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1105">The zero-based byte offset in buffer at which to begin uploading bytes to the blob.</span></span></param>
        <param name="count"><span data-ttu-id="d8c39-1106">Blob に書き込まれるバイト数。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1106">The number of bytes to be written to the blob.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-1107"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1107">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-1108">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1108">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-1109"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1109">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="progressHandler"> <span data-ttu-id="d8c39-1110">A<see cref="T:System.IProgress`1" />を処理するオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" />メッセージ。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1110">A <see cref="T:System.IProgress`1" /> object to handle <see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" /> messages.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d8c39-1111">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1111">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-1112">バイト配列の内容を追加 blob にアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1112">Initiates an asynchronous operation to upload the contents of a byte array to an append blob.</span></span> <span data-ttu-id="d8c39-1113">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1113">If the blob already exists, it will be overwritten.</span></span> <span data-ttu-id="d8c39-1114">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1114">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-1115">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1115">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-1116">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1116">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-1117">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1117">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>
            <span data-ttu-id="d8c39-1118">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1118">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
            <span data-ttu-id="d8c39-1119">既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromByteArrayAsync(System.Byte[],System.Int32,System.Int32,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1119">To append data to an append blob that already exists, see <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromByteArrayAsync(System.Byte[],System.Int32,System.Int32,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />.</span></span>
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
        <param name="path"><span data-ttu-id="d8c39-1120">Blob コンテンツを提供するファイルのパスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1120">A string containing the file path providing the blob content.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-1121"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1121">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-1122">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1122">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="d8c39-1123">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1123">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-1124"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1124">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-1125">追加 blob にファイルをアップロードします。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1125">Uploads a file to an append blob.</span></span> <span data-ttu-id="d8c39-1126">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1126">If the blob already exists, it will be overwritten.</span></span> <span data-ttu-id="d8c39-1127">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1127">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="d8c39-1128">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1128">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-1129">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1129">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>        
            <span data-ttu-id="d8c39-1130">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1130">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
            <span data-ttu-id="d8c39-1131">既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromFile(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1131">To append data to an append blob that already exists, see <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromFile(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />.</span></span>
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
        <param name="path"><span data-ttu-id="d8c39-1132">Blob コンテンツを提供するファイルのパスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1132">A string containing the file path providing the blob content.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-1133">追加 blob にファイルをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1133">Initiates an asynchronous operation to upload a file to an append blob.</span></span> <span data-ttu-id="d8c39-1134">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1134">If the blob already exists, it will be overwritten.</span></span> <span data-ttu-id="d8c39-1135">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1135">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-1136">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1136">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-1137">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1137">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-1138">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1138">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>        
            <span data-ttu-id="d8c39-1139">既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromFileAsync(System.String)" />です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1139">To append data to an append blob that already exists, see <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromFileAsync(System.String)" />.</span></span>
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
        <param name="path"><span data-ttu-id="d8c39-1140">Blob コンテンツを提供するファイルのパスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1140">A string containing the file path providing the blob content.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d8c39-1141">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1141">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-1142">追加 blob にファイルをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1142">Initiates an asynchronous operation to upload a file to an append blob.</span></span> <span data-ttu-id="d8c39-1143">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1143">If the blob already exists, it will be overwritten.</span></span> <span data-ttu-id="d8c39-1144">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1144">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-1145">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1145">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-1146">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1146">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-1147">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1147">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>        
            <span data-ttu-id="d8c39-1148">既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromFileAsync(System.String,System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1148">To append data to an append blob that already exists, see <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromFileAsync(System.String,System.Threading.CancellationToken)" />.</span></span>
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
        <param name="path"><span data-ttu-id="d8c39-1149">Blob コンテンツを提供するファイルのパスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1149">A string containing the file path providing the blob content.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-1150"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1150">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-1151">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1151">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-1152"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1152">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-1153">追加 blob にファイルをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1153">Initiates an asynchronous operation to upload a file to an append blob.</span></span> <span data-ttu-id="d8c39-1154">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1154">If the blob already exists, it will be overwritten.</span></span> <span data-ttu-id="d8c39-1155">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1155">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-1156">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1156">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-1157">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1157">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-1158">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1158">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>        
            <span data-ttu-id="d8c39-1159">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1159">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
            <span data-ttu-id="d8c39-1160">既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromFileAsync(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1160">To append data to an append blob that already exists, see <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromFileAsync(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />.</span></span>
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
        <param name="path"><span data-ttu-id="d8c39-1161">Blob コンテンツを提供するファイルのパスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1161">A string containing the file path providing the blob content.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-1162"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1162">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-1163">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1163">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-1164"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1164">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d8c39-1165">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1165">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-1166">追加 blob にファイルをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1166">Initiates an asynchronous operation to upload a file to an append blob.</span></span> <span data-ttu-id="d8c39-1167">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1167">If the blob already exists, it will be overwritten.</span></span> <span data-ttu-id="d8c39-1168">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1168">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-1169">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1169">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-1170">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1170">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-1171">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1171">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>        
            <span data-ttu-id="d8c39-1172">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1172">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
            <span data-ttu-id="d8c39-1173">既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromFileAsync(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1173">To append data to an append blob that already exists, see <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromFileAsync(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />.</span></span>
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
        <param name="path"><span data-ttu-id="d8c39-1174">Blob コンテンツを提供するファイルのパスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1174">A string containing the file path providing the blob content.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-1175"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1175">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-1176">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1176">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-1177"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1177">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="progressHandler"> <span data-ttu-id="d8c39-1178">A<see cref="T:System.IProgress`1" />を処理するオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" />メッセージ。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1178">A <see cref="T:System.IProgress`1" /> object to handle <see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" /> messages.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d8c39-1179">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1179">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-1180">追加 blob にファイルをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1180">Initiates an asynchronous operation to upload a file to an append blob.</span></span> <span data-ttu-id="d8c39-1181">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1181">If the blob already exists, it will be overwritten.</span></span> <span data-ttu-id="d8c39-1182">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1182">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-1183">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1183">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-1184">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1184">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-1185">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1185">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>        
            <span data-ttu-id="d8c39-1186">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1186">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
            <span data-ttu-id="d8c39-1187">既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromFileAsync(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1187">To append data to an append blob that already exists, see <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromFileAsync(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />.</span></span>
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
        <param name="source"><span data-ttu-id="d8c39-1188">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1188">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-1189"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1189">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="d8c39-1190">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1190">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-1191">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1191">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="d8c39-1192">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1192">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-1193"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1193">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-1194">追加 blob にストリームをアップロードします。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1194">Uploads a stream to an append blob.</span></span> <span data-ttu-id="d8c39-1195">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1195">If the blob already exists, it will be overwritten.</span></span> <span data-ttu-id="d8c39-1196">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1196">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="d8c39-1197">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1197">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-1198">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1198">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>        
            <span data-ttu-id="d8c39-1199">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1199">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
            <span data-ttu-id="d8c39-1200">既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromStream(System.IO.Stream,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1200">To append data to an append blob that already exists, see <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromStream(System.IO.Stream,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />.</span></span>
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
        <param name="source"><span data-ttu-id="d8c39-1201">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1201">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="length"><span data-ttu-id="d8c39-1202">現在の位置に、ソース ストリームから書き込むバイト数。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1202">The number of bytes to write from the source stream at its current position.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-1203"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1203">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="d8c39-1204">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1204">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-1205">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1205">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="d8c39-1206">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1206">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-1207"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1207">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-1208">追加 blob にストリームをアップロードします。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1208">Uploads a stream to an append blob.</span></span> <span data-ttu-id="d8c39-1209">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1209">If the blob already exists, it will be overwritten.</span></span> <span data-ttu-id="d8c39-1210">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1210">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="d8c39-1211">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1211">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-1212">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1212">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>        
            <span data-ttu-id="d8c39-1213">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1213">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
            <span data-ttu-id="d8c39-1214">既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromStream(System.IO.Stream,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1214">To append data to an append blob that already exists, see <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromStream(System.IO.Stream,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />.</span></span>
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
        <param name="source"><span data-ttu-id="d8c39-1215">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1215">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-1216">追加 blob にストリームをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1216">Initiates an asynchronous operation to upload a stream to an append blob.</span></span> <span data-ttu-id="d8c39-1217">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1217">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-1218">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1218">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-1219">既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromStreamAsync(System.IO.Stream)" />です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1219">To append data to an append blob that already exists, see <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromStreamAsync(System.IO.Stream)" />.</span></span>
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
        <param name="source"><span data-ttu-id="d8c39-1220">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1220">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="length"><span data-ttu-id="d8c39-1221">現在の位置に、ソース ストリームから書き込むバイト数。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1221">The number of bytes to write from the source stream at its current position.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-1222">追加 blob にストリームをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1222">Initiates an asynchronous operation to upload a stream to an append blob.</span></span> <span data-ttu-id="d8c39-1223">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1223">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-1224">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1224">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-1225">既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromStreamAsync(System.IO.Stream,System.Int64)" />です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1225">To append data to an append blob that already exists, see <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromStreamAsync(System.IO.Stream,System.Int64)" />.</span></span>
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
        <param name="source"><span data-ttu-id="d8c39-1226">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1226">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d8c39-1227">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1227">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-1228">追加 blob にストリームをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1228">Initiates an asynchronous operation to upload a stream to an append blob.</span></span> <span data-ttu-id="d8c39-1229">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1229">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-1230">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1230">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-1231">既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromStreamAsync(System.IO.Stream,System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1231">To append data to an append blob that already exists, see <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromStreamAsync(System.IO.Stream,System.Threading.CancellationToken)" />.</span></span>
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
        <param name="source"><span data-ttu-id="d8c39-1232">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1232">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="length"><span data-ttu-id="d8c39-1233">現在の位置に、ソース ストリームから書き込むバイト数。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1233">The number of bytes to write from the source stream at its current position.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d8c39-1234">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1234">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-1235">追加 blob にストリームをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1235">Initiates an asynchronous operation to upload a stream to an append blob.</span></span> <span data-ttu-id="d8c39-1236">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1236">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-1237">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1237">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-1238">既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromStreamAsync(System.IO.Stream,System.Int64,System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1238">To append data to an append blob that already exists, see <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromStreamAsync(System.IO.Stream,System.Int64,System.Threading.CancellationToken)" />.</span></span>
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
        <param name="source"><span data-ttu-id="d8c39-1239">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1239">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-1240"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1240">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="d8c39-1241">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1241">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-1242">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1242">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-1243"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1243">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-1244">追加 blob にストリームをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1244">Initiates an asynchronous operation to upload a stream to an append blob.</span></span> <span data-ttu-id="d8c39-1245">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1245">If the blob already exists, it will be overwritten.</span></span> <span data-ttu-id="d8c39-1246">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1246">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-1247">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1247">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-1248">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1248">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-1249">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1249">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>        
            <span data-ttu-id="d8c39-1250">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1250">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
            <span data-ttu-id="d8c39-1251">既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromStreamAsync(System.IO.Stream,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1251">To append data to an append blob that already exists, see <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromStreamAsync(System.IO.Stream,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />.</span></span>
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
        <param name="source"><span data-ttu-id="d8c39-1252">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1252">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-1253"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1253">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="d8c39-1254">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1254">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-1255">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1255">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-1256"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1256">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d8c39-1257">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1257">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-1258">追加 blob にストリームをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1258">Initiates an asynchronous operation to upload a stream to an append blob.</span></span> <span data-ttu-id="d8c39-1259">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1259">If the blob already exists, it will be overwritten.</span></span> <span data-ttu-id="d8c39-1260">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1260">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-1261">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1261">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-1262">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1262">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-1263">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1263">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>        
            <span data-ttu-id="d8c39-1264">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1264">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
            <span data-ttu-id="d8c39-1265">既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromStreamAsync(System.IO.Stream,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1265">To append data to an append blob that already exists, see <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromStreamAsync(System.IO.Stream,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />.</span></span>
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
        <param name="source"><span data-ttu-id="d8c39-1266">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1266">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="length"><span data-ttu-id="d8c39-1267">現在の位置に、ソース ストリームから書き込むバイト数。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1267">The number of bytes to write from the source stream at its current position.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-1268"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1268">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="d8c39-1269">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1269">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-1270">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1270">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-1271"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1271">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-1272">追加 blob にストリームをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1272">Initiates an asynchronous operation to upload a stream to an append blob.</span></span> <span data-ttu-id="d8c39-1273">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1273">If the blob already exists, it will be overwritten.</span></span> <span data-ttu-id="d8c39-1274">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1274">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-1275">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1275">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-1276">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1276">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-1277">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1277">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>        
            <span data-ttu-id="d8c39-1278">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1278">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
            <span data-ttu-id="d8c39-1279">既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromStreamAsync(System.IO.Stream,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1279">To append data to an append blob that already exists, see <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromStreamAsync(System.IO.Stream,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />.</span></span>
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
        <param name="source"><span data-ttu-id="d8c39-1280">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1280">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-1281"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1281">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="d8c39-1282">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1282">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-1283">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1283">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-1284"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1284">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="progressHandler"> <span data-ttu-id="d8c39-1285">A<see cref="T:System.IProgress`1" />を処理するオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" />メッセージ。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1285">A <see cref="T:System.IProgress`1" /> object to handle <see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" /> messages.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d8c39-1286">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1286">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-1287">追加 blob にストリームをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1287">Initiates an asynchronous operation to upload a stream to an append blob.</span></span> <span data-ttu-id="d8c39-1288">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1288">If the blob already exists, it will be overwritten.</span></span> <span data-ttu-id="d8c39-1289">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1289">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-1290">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1290">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-1291">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1291">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-1292">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1292">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>        
            <span data-ttu-id="d8c39-1293">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1293">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
            <span data-ttu-id="d8c39-1294">既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromStreamAsync(System.IO.Stream,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1294">To append data to an append blob that already exists, see <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromStreamAsync(System.IO.Stream,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />.</span></span>
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
        <param name="source"><span data-ttu-id="d8c39-1295">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1295">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="length"><span data-ttu-id="d8c39-1296">現在の位置に、ソース ストリームから書き込むバイト数。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1296">The number of bytes to write from the source stream at its current position.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-1297"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1297">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="d8c39-1298">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1298">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-1299">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1299">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-1300"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1300">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d8c39-1301">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1301">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-1302">追加 blob にストリームをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1302">Initiates an asynchronous operation to upload a stream to an append blob.</span></span> <span data-ttu-id="d8c39-1303">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1303">If the blob already exists, it will be overwritten.</span></span> <span data-ttu-id="d8c39-1304">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1304">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-1305">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1305">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-1306">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1306">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-1307">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1307">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>        
            <span data-ttu-id="d8c39-1308">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1308">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
            <span data-ttu-id="d8c39-1309">既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromStreamAsync(System.IO.Stream,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1309">To append data to an append blob that already exists, see <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromStreamAsync(System.IO.Stream,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />.</span></span>
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
        <param name="source"><span data-ttu-id="d8c39-1310">A <see cref="T:System.IO.Stream" /> blob コンテンツを提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1310">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="length"><span data-ttu-id="d8c39-1311">現在の位置に、ソース ストリームから書き込むバイト数。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1311">The number of bytes to write from the source stream at its current position.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-1312"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1312">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="d8c39-1313">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1313">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-1314">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1314">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-1315"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1315">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="progressHandler"> <span data-ttu-id="d8c39-1316">A<see cref="T:System.IProgress`1" />を処理するオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" />メッセージ。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1316">A <see cref="T:System.IProgress`1" /> object to handle <see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" /> messages.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d8c39-1317">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1317">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-1318">追加 blob にストリームをアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1318">Initiates an asynchronous operation to upload a stream to an append blob.</span></span> <span data-ttu-id="d8c39-1319">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1319">If the blob already exists, it will be overwritten.</span></span> <span data-ttu-id="d8c39-1320">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1320">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-1321">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1321">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-1322">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1322">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-1323">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1323">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>        
            <span data-ttu-id="d8c39-1324">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1324">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
            <span data-ttu-id="d8c39-1325">既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromStreamAsync(System.IO.Stream,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1325">To append data to an append blob that already exists, see <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromStreamAsync(System.IO.Stream,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />.</span></span>
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
        <param name="content"><span data-ttu-id="d8c39-1326">アップロードするテキストを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1326">A string containing the text to upload.</span></span></param>
        <param name="encoding"><span data-ttu-id="d8c39-1327">A<see cref="T:System.Text.Encoding" />を使用するテキスト エンコーディングを示すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1327">A <see cref="T:System.Text.Encoding" /> object that indicates the text encoding to use.</span></span> <span data-ttu-id="d8c39-1328">場合<c>null</c>utf-8 が使用されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1328">If <c>null</c>, UTF-8 will be used.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-1329"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1329">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-1330">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1330">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="d8c39-1331">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1331">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-1332"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1332">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-1333">テキストの文字列を追加 blob にアップロードします。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1333">Uploads a string of text to an append blob.</span></span> <span data-ttu-id="d8c39-1334">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1334">If the blob already exists, it will be overwritten.</span></span> <span data-ttu-id="d8c39-1335">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1335">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="d8c39-1336">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1336">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-1337">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1337">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>
            <span data-ttu-id="d8c39-1338">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1338">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
            <span data-ttu-id="d8c39-1339">既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendText(System.String,System.Text.Encoding,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1339">To append data to an append blob that already exists, see <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendText(System.String,System.Text.Encoding,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />.</span></span>
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
        <param name="content"><span data-ttu-id="d8c39-1340">アップロードするテキストを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1340">A string containing the text to upload.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-1341">テキストの文字列を追加 blob にアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1341">Initiates an asynchronous operation to upload a string of text to an append blob.</span></span> <span data-ttu-id="d8c39-1342">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1342">If the blob already exists, it will be overwritten.</span></span> <span data-ttu-id="d8c39-1343">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1343">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-1344">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1344">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-1345">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1345">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-1346">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1346">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>
            <span data-ttu-id="d8c39-1347">既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendTextAsync(System.String)" />です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1347">To append data to an append blob that already exists, see <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendTextAsync(System.String)" />.</span></span>
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
        <param name="content"><span data-ttu-id="d8c39-1348">アップロードするテキストを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1348">A string containing the text to upload.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d8c39-1349">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1349">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-1350">テキストの文字列を追加 blob にアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1350">Initiates an asynchronous operation to upload a string of text to an append blob.</span></span> <span data-ttu-id="d8c39-1351">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1351">If the blob already exists, it will be overwritten.</span></span> <span data-ttu-id="d8c39-1352">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1352">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-1353">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1353">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-1354">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1354">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-1355">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1355">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>
            <span data-ttu-id="d8c39-1356">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1356">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
            <span data-ttu-id="d8c39-1357">既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendTextAsync(System.String,System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1357">To append data to an append blob that already exists, see <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendTextAsync(System.String,System.Threading.CancellationToken)" />.</span></span>
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
        <param name="content"><span data-ttu-id="d8c39-1358">アップロードするテキストを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1358">A string containing the text to upload.</span></span></param>
        <param name="encoding"><span data-ttu-id="d8c39-1359">A<see cref="T:System.Text.Encoding" />を使用するテキスト エンコーディングを示すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1359">A <see cref="T:System.Text.Encoding" /> object that indicates the text encoding to use.</span></span> <span data-ttu-id="d8c39-1360">場合<c>null</c>utf-8 が使用されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1360">If <c>null</c>, UTF-8 will be used.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-1361"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1361">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-1362">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1362">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-1363"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1363">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-1364">テキストの文字列を追加 blob にアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1364">Initiates an asynchronous operation to upload a string of text to an append blob.</span></span> <span data-ttu-id="d8c39-1365">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1365">If the blob already exists, it will be overwritten.</span></span> <span data-ttu-id="d8c39-1366">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1366">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-1367">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1367">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-1368">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1368">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-1369">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1369">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>
            <span data-ttu-id="d8c39-1370">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1370">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
            <span data-ttu-id="d8c39-1371">既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendTextAsync(System.String,System.Text.Encoding,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1371">To append data to an append blob that already exists, see <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendTextAsync(System.String,System.Text.Encoding,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />.</span></span>
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
        <param name="content"><span data-ttu-id="d8c39-1372">アップロードするテキストを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1372">A string containing the text to upload.</span></span></param>
        <param name="encoding"><span data-ttu-id="d8c39-1373">A<see cref="T:System.Text.Encoding" />を使用するテキスト エンコーディングを示すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1373">A <see cref="T:System.Text.Encoding" /> object that indicates the text encoding to use.</span></span> <span data-ttu-id="d8c39-1374">場合<c>null</c>utf-8 が使用されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1374">If <c>null</c>, UTF-8 will be used.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-1375"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1375">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-1376">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1376">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-1377"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1377">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d8c39-1378">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1378">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-1379">テキストの文字列を追加 blob にアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1379">Initiates an asynchronous operation to upload a string of text to an append blob.</span></span> <span data-ttu-id="d8c39-1380">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1380">If the blob already exists, it will be overwritten.</span></span> <span data-ttu-id="d8c39-1381">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1381">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-1382">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1382">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-1383">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1383">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-1384">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1384">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>
            <span data-ttu-id="d8c39-1385">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1385">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
            <span data-ttu-id="d8c39-1386">既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendTextAsync(System.String,System.Text.Encoding,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1386">To append data to an append blob that already exists, see <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendTextAsync(System.String,System.Text.Encoding,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />.</span></span>
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
        <param name="content"><span data-ttu-id="d8c39-1387">アップロードするテキストを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1387">A string containing the text to upload.</span></span></param>
        <param name="encoding"><span data-ttu-id="d8c39-1388">A<see cref="T:System.Text.Encoding" />を使用するテキスト エンコーディングを示すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1388">A <see cref="T:System.Text.Encoding" /> object that indicates the text encoding to use.</span></span> <span data-ttu-id="d8c39-1389">場合<c>null</c>utf-8 が使用されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1389">If <c>null</c>, UTF-8 will be used.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d8c39-1390"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1390">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="d8c39-1391">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1391">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8c39-1392"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1392">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="progressHandler"> <span data-ttu-id="d8c39-1393">A<see cref="T:System.IProgress`1" />を処理するオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" />メッセージ。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1393">A <see cref="T:System.IProgress`1" /> object to handle <see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" /> messages.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d8c39-1394">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1394">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="d8c39-1395">テキストの文字列を追加 blob にアップロードする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1395">Initiates an asynchronous operation to upload a string of text to an append blob.</span></span> <span data-ttu-id="d8c39-1396">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1396">If the blob already exists, it will be overwritten.</span></span> <span data-ttu-id="d8c39-1397">単一ライターのシナリオでのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1397">Recommended only for single-writer scenarios.</span></span>
            </summary>
        <returns><span data-ttu-id="d8c39-1398">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1398">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="d8c39-1399">単一ライターのシナリオでのみ、このメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1399">Use this method only in single-writer scenarios.</span></span> <span data-ttu-id="d8c39-1400">内部的には、このメソッドは追加のオフセット値の条件ヘッダーを使用して複数ライターのシナリオで問題が発生する可能性がありますが、重複するブロックを回避します。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1400">Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.</span></span>
            <span data-ttu-id="d8c39-1401">単一ライターのシナリオがあればを参照してください。<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />このフラグを設定するかどうかを決定する<c>true</c>は自分のシナリオで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1401">If you have a single-writer scenario, see <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" /> to determine whether setting this flag to <c>true</c> is acceptable for your scenario.</span></span>
            <span data-ttu-id="d8c39-1402">既に存在する追加 blob にデータを追加するを参照してください。<see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendTextAsync(System.String,System.Text.Encoding,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="d8c39-1402">To append data to an append blob that already exists, see <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendTextAsync(System.String,System.Text.Encoding,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>