<Type Name="CloudBlobClient" FullName="Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient">
  <TypeSignature Language="C#" Value="public class CloudBlobClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CloudBlobClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient" />
  <TypeSignature Language="VB.NET" Value="Public Class CloudBlobClient" />
  <TypeSignature Language="F#" Value="type CloudBlobClient = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c2151-101">Microsoft Azure Blob ストレージのクライアント側の論理表現を提供します。</span><span class="sxs-lookup"><span data-stu-id="c2151-101">Provides a client-side logical representation of Microsoft Azure Blob storage.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudBlobClient (Uri baseUri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.#ctor(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (baseUri As Uri)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient : Uri -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient" Usage="new Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient baseUri" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="baseUri" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="baseUri"><span data-ttu-id="c2151-102">A<see cref="T:System.Uri" />を使用してクライアントを作成する Blob サービス エンドポイントを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-102">A <see cref="T:System.Uri" /> object containing the Blob service endpoint to use to create the client.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-103">新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient" />クラスの指定された Blob サービス エンドポイントと匿名の資格情報を使用します。</span><span class="sxs-lookup"><span data-stu-id="c2151-103">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient" /> class using the specified Blob service endpoint and anonymous credentials.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudBlobClient (Microsoft.WindowsAzure.Storage.StorageUri storageUri, Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.StorageUri storageUri, class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.#ctor(Microsoft.WindowsAzure.Storage.StorageUri,Microsoft.WindowsAzure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient : Microsoft.WindowsAzure.Storage.StorageUri * Microsoft.WindowsAzure.Storage.Auth.StorageCredentials -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient" Usage="new Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient (storageUri, credentials)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storageUri" Type="Microsoft.WindowsAzure.Storage.StorageUri" />
        <Parameter Name="credentials" Type="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />
      </Parameters>
      <Docs>
        <param name="storageUri"><span data-ttu-id="c2151-104">A<see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.StorageUri" />を使用してクライアントを作成する Blob サービス エンドポイントを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-104">A <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.StorageUri" /> object containing the Blob service endpoint to use to create the client.</span></span></param>
        <param name="credentials"><span data-ttu-id="c2151-105"><see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-105">A <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-106">新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient" />クラス、指定された Blob サービス エンドポイントとアカウントの資格情報を使用します。</span><span class="sxs-lookup"><span data-stu-id="c2151-106">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient" /> class using the specified Blob service endpoint and account credentials.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudBlobClient (Uri baseUri, Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.#ctor(System.Uri,Microsoft.WindowsAzure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (baseUri As Uri, credentials As StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient : Uri * Microsoft.WindowsAzure.Storage.Auth.StorageCredentials -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient" Usage="new Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient (baseUri, credentials)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="baseUri" Type="System.Uri" />
        <Parameter Name="credentials" Type="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />
      </Parameters>
      <Docs>
        <param name="baseUri"><span data-ttu-id="c2151-107">A<see cref="T:System.Uri" />を使用してクライアントを作成する Blob サービス エンドポイントを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-107">A <see cref="T:System.Uri" /> object containing the Blob service endpoint to use to create the client.</span></span></param>
        <param name="credentials"><span data-ttu-id="c2151-108"><see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-108">A <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-109">新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient" />クラス、指定された Blob サービス エンドポイントとアカウントの資格情報を使用します。</span><span class="sxs-lookup"><span data-stu-id="c2151-109">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient" /> class using the specified Blob service endpoint and account credentials.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationScheme">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.AuthenticationScheme AuthenticationScheme { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.AuthenticationScheme AuthenticationScheme" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.AuthenticationScheme" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationScheme As AuthenticationScheme" />
      <MemberSignature Language="F#" Value="member this.AuthenticationScheme : Microsoft.WindowsAzure.Storage.AuthenticationScheme with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.AuthenticationScheme" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.AuthenticationScheme</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c2151-110">取得または HTTP 要求の署名に使用する認証スキームを設定します。</span><span class="sxs-lookup"><span data-stu-id="c2151-110">Gets or sets the authentication scheme to use to sign HTTP requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="c2151-111">共有キーまたは共有キー Lite の資格情報が使用される場合にのみ、このプロパティを設定します。共有アクセス署名または匿名アクセス経由での認証には適用されません。</span><span class="sxs-lookup"><span data-stu-id="c2151-111">This property is set only when Shared Key or Shared Key Lite credentials are used; it does not apply to authentication via a shared access signature or anonymous access.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri" Usage="Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.BaseUri" />
      <MemberType>Property</MemberType>
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
            <span data-ttu-id="c2151-112">プライマリの場所の Blob サービス クライアントのベース URI を取得します。</span><span class="sxs-lookup"><span data-stu-id="c2151-112">Gets the base URI for the Blob service client at the primary location.</span></span>
            </summary>
        <value><span data-ttu-id="c2151-113">A<see cref="T:System.Uri" />プライマリの場所の Blob サービス クライアントを構築するために使用されるベース URI を含むオブジェクトします。</span><span class="sxs-lookup"><span data-stu-id="c2151-113">A <see cref="T:System.Uri" /> object containing the base URI used to construct the Blob service client at the primary location.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetBlobReferenceFromServer">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetBlobReferenceFromServer (Uri blobUri, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetBlobReferenceFromServer(class System.Uri blobUri, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.BeginGetBlobReferenceFromServer(System.Uri,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginGetBlobReferenceFromServer (blobUri As Uri, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginGetBlobReferenceFromServer : Uri * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetBlobReferenceFromServer : Uri * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobClient.BeginGetBlobReferenceFromServer (blobUri, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <Parameter Name="blobUri" Type="System.Uri" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="blobUri"><span data-ttu-id="c2151-114">A <see cref="T:System.Uri" /> blob の URI を格納します。</span><span class="sxs-lookup"><span data-stu-id="c2151-114">A <see cref="T:System.Uri" /> containing the URI of the blob.</span></span> <span data-ttu-id="c2151-115">サービスでは、プライマリの場所にある blob の URI は、この前提としています。</span><span class="sxs-lookup"><span data-stu-id="c2151-115">The service assumes this is the URI for the blob at the primary location.</span></span></param>
        <param name="callback"><span data-ttu-id="c2151-116"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="c2151-116">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="c2151-117">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-117">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-118">Blob への参照を取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="c2151-118">Begins an asynchronous operation to get a reference to a blob.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-119"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="c2151-119">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetBlobReferenceFromServer">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetBlobReferenceFromServer (Microsoft.WindowsAzure.Storage.StorageUri blobUri, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetBlobReferenceFromServer(class Microsoft.WindowsAzure.Storage.StorageUri blobUri, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.BeginGetBlobReferenceFromServer(Microsoft.WindowsAzure.Storage.StorageUri,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginGetBlobReferenceFromServer : Microsoft.WindowsAzure.Storage.StorageUri * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetBlobReferenceFromServer : Microsoft.WindowsAzure.Storage.StorageUri * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobClient.BeginGetBlobReferenceFromServer (blobUri, accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <Parameter Name="blobUri" Type="Microsoft.WindowsAzure.Storage.StorageUri" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="blobUri"><span data-ttu-id="c2151-120">A <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.StorageUri" /> blob の URI を格納します。</span><span class="sxs-lookup"><span data-stu-id="c2151-120">A <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.StorageUri" /> containing the URI of the blob.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="c2151-121"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-121">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="c2151-122">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="c2151-122">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="c2151-123">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の他のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-123">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies any additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="c2151-124"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-124">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="c2151-125"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="c2151-125">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="c2151-126">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-126">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-127">Blob への参照を取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="c2151-127">Begins an asynchronous operation to get a reference to a blob.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-128"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="c2151-128">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetBlobReferenceFromServer">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetBlobReferenceFromServer (Uri blobUri, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetBlobReferenceFromServer(class System.Uri blobUri, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.BeginGetBlobReferenceFromServer(System.Uri,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginGetBlobReferenceFromServer : Uri * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetBlobReferenceFromServer : Uri * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobClient.BeginGetBlobReferenceFromServer (blobUri, accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <Parameter Name="blobUri" Type="System.Uri" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="blobUri"><span data-ttu-id="c2151-129">A <see cref="T:System.Uri" /> blob の URI を格納します。</span><span class="sxs-lookup"><span data-stu-id="c2151-129">A <see cref="T:System.Uri" /> containing the URI of the blob.</span></span> <span data-ttu-id="c2151-130">サービスでは、プライマリの場所にある blob の URI は、この前提としています。</span><span class="sxs-lookup"><span data-stu-id="c2151-130">The service assumes this is the URI for the blob at the primary location.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="c2151-131"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-131">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="c2151-132">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="c2151-132">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="c2151-133">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-133">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="c2151-134"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-134">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="c2151-135"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="c2151-135">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="c2151-136">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-136">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-137">Blob への参照を取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="c2151-137">Begins an asynchronous operation to get a reference to a blob.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-138"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="c2151-138">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceProperties (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceProperties(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.BeginGetServiceProperties(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginGetServiceProperties (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginGetServiceProperties : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetServiceProperties : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobClient.BeginGetServiceProperties (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <param name="callback"><span data-ttu-id="c2151-139"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="c2151-139">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="c2151-140">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-140">A user-defined object to be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-141">Blob サービスのサービス プロパティを取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="c2151-141">Begins an asynchronous operation to get service properties for the Blob service.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-142"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="c2151-142">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceProperties (Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceProperties(class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.BeginGetServiceProperties(Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginGetServiceProperties : Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetServiceProperties : Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobClient.BeginGetServiceProperties (requestOptions, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="c2151-143">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-143">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="c2151-144"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-144">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="c2151-145"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="c2151-145">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="c2151-146">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-146">A user-defined object to be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-147">Blob サービスのサービス プロパティを取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="c2151-147">Begins an asynchronous operation to get service properties for the Blob service.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-148"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="c2151-148">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetServiceStats">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceStats (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceStats(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.BeginGetServiceStats(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginGetServiceStats (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginGetServiceStats : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetServiceStats : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobClient.BeginGetServiceStats (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <param name="callback"><span data-ttu-id="c2151-149"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="c2151-149">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="c2151-150">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-150">A user-defined object to be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-151">セカンダリ Blob サービス エンドポイントのサービスの統計情報を取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="c2151-151">Begins an asynchronous operation to get service stats for the secondary Blob service endpoint.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-152"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="c2151-152">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetServiceStats">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceStats (Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceStats(class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.BeginGetServiceStats(Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginGetServiceStats : Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetServiceStats : Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobClient.BeginGetServiceStats (requestOptions, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="c2151-153">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-153">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="c2151-154"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-154">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="c2151-155"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="c2151-155">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="c2151-156">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-156">A user-defined object to be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-157">セカンダリ Blob サービス エンドポイントのサービスの統計情報を取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="c2151-157">Begins an asynchronous operation to get service stats for the secondary Blob service endpoint.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-158"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="c2151-158">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListBlobsSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListBlobsSegmented (string prefix, Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListBlobsSegmented(string prefix, class Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.BeginListBlobsSegmented(System.String,Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginListBlobsSegmented (prefix As String, currentToken As BlobContinuationToken, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginListBlobsSegmented : string * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginListBlobsSegmented : string * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobClient.BeginListBlobsSegmented (prefix, currentToken, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="c2151-159">コンテナー名を含む blob 名のプレフィックスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="c2151-159">A string containing the blob name prefix, including the container name.</span></span></param>
        <param name="currentToken"><span data-ttu-id="c2151-160">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />前の一覧作成操作によって返されるオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-160">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" /> object returned by a previous listing operation.</span></span></param>
        <param name="callback"><span data-ttu-id="c2151-161"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="c2151-161">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="c2151-162">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-162">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-163">コンテナー内の blob 項目のコレクションを含む結果セグメントを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="c2151-163">Begins an asynchronous operation to return a result segment containing a collection of blob items in the container.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-164"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="c2151-164">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListBlobsSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListBlobsSegmented (string prefix, bool useFlatBlobListing, Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails blobListingDetails, Nullable&lt;int&gt; maxResults, Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListBlobsSegmented(string prefix, bool useFlatBlobListing, valuetype Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails blobListingDetails, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.BeginListBlobsSegmented(System.String,System.Boolean,Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginListBlobsSegmented : string * bool * Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginListBlobsSegmented : string * bool * Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobClient.BeginListBlobsSegmented (prefix, useFlatBlobListing, blobListingDetails, maxResults, currentToken, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <Parameter Name="prefix" Type="System.String" />
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
        <param name="prefix"><span data-ttu-id="c2151-165">コンテナー名を含む blob 名のプレフィックスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="c2151-165">A string containing the blob name prefix, including the container name.</span></span></param>
        <param name="useFlatBlobListing"><span data-ttu-id="c2151-166">フラット リスト内の blob を一覧表示するかどうか、または仮想ディレクトリで階層的に、blob を一覧表示するかどうかを指定するブール値。</span><span class="sxs-lookup"><span data-stu-id="c2151-166">A boolean value that specifies whether to list blobs in a flat listing, or whether to list blobs hierarchically, by virtual directory.</span></span></param>
        <param name="blobListingDetails"><span data-ttu-id="c2151-167">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" />一覧に含める項目を記述する列挙です。</span><span class="sxs-lookup"><span data-stu-id="c2151-167">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" /> enumeration describing which items to include in the listing.</span></span></param>
        <param name="maxResults"><span data-ttu-id="c2151-168">5000 の操作あたりの上限に達するまで、一度に返される結果の最大数を示す正の整数値。</span><span class="sxs-lookup"><span data-stu-id="c2151-168">A non-negative integer value that indicates the maximum number of results to be returned at a time, up to the per-operation limit of 5000.</span></span> <span data-ttu-id="c2151-169">この値が場合<c>null</c>結果の最大数が返されます、最大 5000 です。</span><span class="sxs-lookup"><span data-stu-id="c2151-169">If this value is <c>null</c>, the maximum possible number of results will be returned, up to 5000.</span></span></param>
        <param name="currentToken"><span data-ttu-id="c2151-170">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />前の一覧作成操作によって返されるオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-170">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" /> object returned by a previous listing operation.</span></span></param>
        <param name="options"><span data-ttu-id="c2151-171">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-171">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="c2151-172"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-172">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="c2151-173"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="c2151-173">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="c2151-174">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-174">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-175">コンテナー内の blob 項目のコレクションを含む結果セグメントを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="c2151-175">Begins an asynchronous operation to return a result segment containing a collection of blob items in the container.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-176"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="c2151-176">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListContainersSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListContainersSegmented (Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken continuationToken, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListContainersSegmented(class Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken continuationToken, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.BeginListContainersSegmented(Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginListContainersSegmented (continuationToken As BlobContinuationToken, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginListContainersSegmented : Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginListContainersSegmented : Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobClient.BeginListContainersSegmented (continuationToken, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <Parameter Name="continuationToken" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="continuationToken"><span data-ttu-id="c2151-177">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />前の一覧作成操作によって返されるオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-177">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" /> object returned by a previous listing operation.</span></span></param>
        <param name="callback"><span data-ttu-id="c2151-178"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="c2151-178">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="c2151-179">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-179">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-180">コンテナーのコレクションを含む結果セグメントを返す非同期要求を開始します。</span><span class="sxs-lookup"><span data-stu-id="c2151-180">Begins an asynchronous request to return a result segment containing a collection of containers.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-181"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="c2151-181">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListContainersSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListContainersSegmented (string prefix, Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken continuationToken, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListContainersSegmented(string prefix, class Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken continuationToken, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.BeginListContainersSegmented(System.String,Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginListContainersSegmented (prefix As String, continuationToken As BlobContinuationToken, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginListContainersSegmented : string * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginListContainersSegmented : string * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobClient.BeginListContainersSegmented (prefix, continuationToken, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="continuationToken" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="c2151-182">コンテナー名のプレフィックスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="c2151-182">A string containing the container name prefix.</span></span></param>
        <param name="continuationToken"><span data-ttu-id="c2151-183">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />前の一覧作成操作によって返されるオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-183">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" /> object returned by a previous listing operation.</span></span></param>
        <param name="callback"><span data-ttu-id="c2151-184"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="c2151-184">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="c2151-185">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-185">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-186">コンテナーのコレクションを含む結果セグメントを返す非同期要求を開始します。</span><span class="sxs-lookup"><span data-stu-id="c2151-186">Begins an asynchronous request to return a result segment containing a collection of containers.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-187"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="c2151-187">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListContainersSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListContainersSegmented (string prefix, Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails detailsIncluded, Nullable&lt;int&gt; maxResults, Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken continuationToken, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListContainersSegmented(string prefix, valuetype Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails detailsIncluded, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken continuationToken, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.BeginListContainersSegmented(System.String,Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginListContainersSegmented : string * Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginListContainersSegmented : string * Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobClient.BeginListContainersSegmented (prefix, detailsIncluded, maxResults, continuationToken, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="detailsIncluded" Type="Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="continuationToken" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="c2151-188">コンテナー名のプレフィックスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="c2151-188">A string containing the container name prefix.</span></span></param>
        <param name="detailsIncluded"><span data-ttu-id="c2151-189">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails" />一覧にコンテナーのメタデータを返すかどうかを示す列挙値。</span><span class="sxs-lookup"><span data-stu-id="c2151-189">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails" /> enumeration value that indicates whether to return container metadata with the listing.</span></span></param>
        <param name="maxResults"><span data-ttu-id="c2151-190">5000 の操作あたりの上限に達するまで、結果のセグメントに返される結果の最大数を示す正の整数値。</span><span class="sxs-lookup"><span data-stu-id="c2151-190">A non-negative integer value that indicates the maximum number of results to be returned in the result segment, up to the per-operation limit of 5000.</span></span> <span data-ttu-id="c2151-191">この値が場合<c>null</c>結果の最大数が返されます、最大 5000 です。</span><span class="sxs-lookup"><span data-stu-id="c2151-191">If this value is <c>null</c>, the maximum possible number of results will be returned, up to 5000.</span></span></param>
        <param name="continuationToken"><span data-ttu-id="c2151-192">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />前の一覧作成操作によって返されるオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-192">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" /> object returned by a previous listing operation.</span></span></param>
        <param name="options"><span data-ttu-id="c2151-193">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-193">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="c2151-194"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-194">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="c2151-195"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="c2151-195">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="c2151-196">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-196">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-197">名前が指定したプレフィックスで始まるコンテナーのコレクションを含む結果セグメントを返す非同期要求を開始します。</span><span class="sxs-lookup"><span data-stu-id="c2151-197">Begins an asynchronous request to return a result segment containing a collection of containers whose names begin with the specified prefix.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-198"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="c2151-198">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetServiceProperties (Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetServiceProperties(class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.BeginSetServiceProperties(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginSetServiceProperties (properties As ServiceProperties, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginSetServiceProperties : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetServiceProperties : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobClient.BeginSetServiceProperties (properties, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="c2151-199"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-199">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> object.</span></span></param>
        <param name="callback"><span data-ttu-id="c2151-200"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="c2151-200">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="c2151-201">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-201">A user-defined object to be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-202">Blob サービスのサービス プロパティを設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="c2151-202">Begins an asynchronous operation to set service properties for the Blob service.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-203"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="c2151-203">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetServiceProperties (Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetServiceProperties(class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.BeginSetServiceProperties(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginSetServiceProperties : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetServiceProperties : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobClient.BeginSetServiceProperties (properties, requestOptions, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="c2151-204"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-204">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> object.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="c2151-205">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-205">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="c2151-206"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-206">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="c2151-207"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="c2151-207">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="c2151-208">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-208">A user-defined object to be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-209">Blob サービスのサービス プロパティを設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="c2151-209">Begins an asynchronous operation to set service properties for the Blob service.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-210"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="c2151-210">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BufferManager">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.IBufferManager BufferManager { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.IBufferManager BufferManager" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.BufferManager" />
      <MemberSignature Language="VB.NET" Value="Public Property BufferManager As IBufferManager" />
      <MemberSignature Language="F#" Value="member this.BufferManager : Microsoft.WindowsAzure.Storage.IBufferManager with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.BufferManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.IBufferManager</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c2151-211">取得または設定を実装するバッファー マネージャー、<see cref="T:Microsoft.WindowsAzure.Storage.IBufferManager" />インターフェイス、Blob サービス クライアントに対する操作で使用されるバッファー プールを指定します。</span><span class="sxs-lookup"><span data-stu-id="c2151-211">Gets or sets a buffer manager that implements the <see cref="T:Microsoft.WindowsAzure.Storage.IBufferManager" /> interface, specifying a buffer pool for use with operations against the Blob service client.</span></span>
            </summary>
        <value><span data-ttu-id="c2151-212"><see cref="T:Microsoft.WindowsAzure.Storage.IBufferManager" /> 型のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-212">An object of type <see cref="T:Microsoft.WindowsAzure.Storage.IBufferManager" />.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Auth.StorageCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As StorageCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" Usage="Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Auth.StorageCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c2151-213">Blob サービス クライアントを作成するために使用するアカウントの資格情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="c2151-213">Gets the account credentials used to create the Blob service client.</span></span>
            </summary>
        <value><span data-ttu-id="c2151-214"><see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-214">A <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultDelimiter">
      <MemberSignature Language="C#" Value="public string DefaultDelimiter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DefaultDelimiter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.DefaultDelimiter" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultDelimiter As String" />
      <MemberSignature Language="F#" Value="member this.DefaultDelimiter : string with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.DefaultDelimiter" />
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
            <span data-ttu-id="c2151-215">取得または blob の仮想ディレクトリ構造を作成するために使用する既定の区切り記号を設定します。</span><span class="sxs-lookup"><span data-stu-id="c2151-215">Gets or sets the default delimiter that may be used to create a virtual directory structure of blobs.</span></span>
            </summary>
        <value><span data-ttu-id="c2151-216">Blob サービスの既定の区切り記号を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="c2151-216">A string containing the default delimiter for the Blob service.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultRequestOptions">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions DefaultRequestOptions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions DefaultRequestOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.DefaultRequestOptions" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultRequestOptions As BlobRequestOptions" />
      <MemberSignature Language="F#" Value="member this.DefaultRequestOptions : Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.DefaultRequestOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c2151-217">取得または、Blob サービス クライアントを介して行われる要求の要求オプションを既定値に設定します。</span><span class="sxs-lookup"><span data-stu-id="c2151-217">Gets or sets the default request options for requests made via the Blob service client.</span></span>
            </summary>
        <value><span data-ttu-id="c2151-218"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-218">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndGetBlobReferenceFromServer">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.ICloudBlob EndGetBlobReferenceFromServer (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.ICloudBlob EndGetBlobReferenceFromServer(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.EndGetBlobReferenceFromServer(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndGetBlobReferenceFromServer (asyncResult As IAsyncResult) As ICloudBlob" />
      <MemberSignature Language="F#" Value="abstract member EndGetBlobReferenceFromServer : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&#xA;override this.EndGetBlobReferenceFromServer : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" Usage="cloudBlobClient.EndGetBlobReferenceFromServer asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.ICloudBlob</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="c2151-219"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="c2151-219">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-220">Blob への参照を取得する非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="c2151-220">Ends an asynchronous operation to get a reference to a blob.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-221"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-221">An <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndGetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties EndGetServiceProperties (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties EndGetServiceProperties(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.EndGetServiceProperties(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndGetServiceProperties (asyncResult As IAsyncResult) As ServiceProperties" />
      <MemberSignature Language="F#" Value="abstract member EndGetServiceProperties : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&#xA;override this.EndGetServiceProperties : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" Usage="cloudBlobClient.EndGetServiceProperties asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="c2151-222"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="c2151-222">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-223">Blob サービスのサービス プロパティを取得する非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="c2151-223">Ends an asynchronous operation to get service properties for the Blob service.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-224"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-224">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndGetServiceStats">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats EndGetServiceStats (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats EndGetServiceStats(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.EndGetServiceStats(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndGetServiceStats (asyncResult As IAsyncResult) As ServiceStats" />
      <MemberSignature Language="F#" Value="abstract member EndGetServiceStats : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&#xA;override this.EndGetServiceStats : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" Usage="cloudBlobClient.EndGetServiceStats asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="c2151-225"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="c2151-225">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-226">セカンダリ Blob サービス エンドポイントのサービスの統計情報を取得する非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="c2151-226">Ends an asynchronous operation to get service stats for the secondary Blob service endpoint.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-227"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-227">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndListBlobsSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment EndListBlobsSegmented (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment EndListBlobsSegmented(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.EndListBlobsSegmented(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndListBlobsSegmented (asyncResult As IAsyncResult) As BlobResultSegment" />
      <MemberSignature Language="F#" Value="abstract member EndListBlobsSegmented : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&#xA;override this.EndListBlobsSegmented : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment" Usage="cloudBlobClient.EndListBlobsSegmented asyncResult" />
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
        <param name="asyncResult"><span data-ttu-id="c2151-228"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="c2151-228">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-229">コンテナー内の blob 項目のコレクションを含む結果セグメントを返す非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="c2151-229">Ends an asynchronous operation to return a result segment containing a collection of blob items in the container.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-230"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-230">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndListContainersSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment EndListContainersSegmented (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment EndListContainersSegmented(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.EndListContainersSegmented(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndListContainersSegmented (asyncResult As IAsyncResult) As ContainerResultSegment" />
      <MemberSignature Language="F#" Value="abstract member EndListContainersSegmented : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment&#xA;override this.EndListContainersSegmented : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment" Usage="cloudBlobClient.EndListContainersSegmented asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="c2151-231"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="c2151-231">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-232">コンテナーのコレクションを含む結果セグメントを返す非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="c2151-232">Ends an asynchronous operation to return a result segment containing a collection of containers.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-233"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-233">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndSetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual void EndSetServiceProperties (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndSetServiceProperties(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.EndSetServiceProperties(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndSetServiceProperties (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndSetServiceProperties : IAsyncResult -&gt; unit&#xA;override this.EndSetServiceProperties : IAsyncResult -&gt; unit" Usage="cloudBlobClient.EndSetServiceProperties asyncResult" />
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
        <param name="asyncResult"><span data-ttu-id="c2151-234"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="c2151-234">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-235">Blob サービスのサービス プロパティを設定する非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="c2151-235">Ends an asynchronous operation to set service properties for the Blob service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBlobReferenceFromServer">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.ICloudBlob GetBlobReferenceFromServer (Microsoft.WindowsAzure.Storage.StorageUri blobUri, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.ICloudBlob GetBlobReferenceFromServer(class Microsoft.WindowsAzure.Storage.StorageUri blobUri, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.GetBlobReferenceFromServer(Microsoft.WindowsAzure.Storage.StorageUri,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetBlobReferenceFromServer : Microsoft.WindowsAzure.Storage.StorageUri * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&#xA;override this.GetBlobReferenceFromServer : Microsoft.WindowsAzure.Storage.StorageUri * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" Usage="cloudBlobClient.GetBlobReferenceFromServer (blobUri, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.ICloudBlob</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blobUri" Type="Microsoft.WindowsAzure.Storage.StorageUri" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="blobUri"><span data-ttu-id="c2151-236">A <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.StorageUri" /> blob の URI を格納します。</span><span class="sxs-lookup"><span data-stu-id="c2151-236">A <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.StorageUri" /> containing the URI of the blob.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="c2151-237"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-237">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="c2151-238">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="c2151-238">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="c2151-239">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の他のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-239">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies any additional options for the request.</span></span> <span data-ttu-id="c2151-240">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="c2151-240">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="c2151-241"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-241">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-242">Blob への参照を取得します。</span><span class="sxs-lookup"><span data-stu-id="c2151-242">Gets a reference to a blob.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-243"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-243">An <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBlobReferenceFromServer">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.ICloudBlob GetBlobReferenceFromServer (Uri blobUri, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.ICloudBlob GetBlobReferenceFromServer(class System.Uri blobUri, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.GetBlobReferenceFromServer(System.Uri,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetBlobReferenceFromServer : Uri * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&#xA;override this.GetBlobReferenceFromServer : Uri * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" Usage="cloudBlobClient.GetBlobReferenceFromServer (blobUri, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.ICloudBlob</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blobUri" Type="System.Uri" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="blobUri"><span data-ttu-id="c2151-244">A <see cref="T:System.Uri" /> blob の URI を格納します。</span><span class="sxs-lookup"><span data-stu-id="c2151-244">A <see cref="T:System.Uri" /> containing the URI of the blob.</span></span> <span data-ttu-id="c2151-245">サービスでは、プライマリの場所にある blob の URI は、この前提としています。</span><span class="sxs-lookup"><span data-stu-id="c2151-245">The service assumes this is the URI for the blob at the primary location.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="c2151-246"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-246">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="c2151-247">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="c2151-247">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="c2151-248">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-248">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="c2151-249">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="c2151-249">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="c2151-250"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-250">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-251">Blob への参照を取得します。</span><span class="sxs-lookup"><span data-stu-id="c2151-251">Gets a reference to a blob.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-252"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-252">An <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBlobReferenceFromServerAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; GetBlobReferenceFromServerAsync (Uri blobUri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; GetBlobReferenceFromServerAsync(class System.Uri blobUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.GetBlobReferenceFromServerAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetBlobReferenceFromServerAsync (blobUri As Uri) As Task(Of ICloudBlob)" />
      <MemberSignature Language="F#" Value="abstract member GetBlobReferenceFromServerAsync : Uri -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;&#xA;override this.GetBlobReferenceFromServerAsync : Uri -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;" Usage="cloudBlobClient.GetBlobReferenceFromServerAsync blobUri" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blobUri" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="blobUri"><span data-ttu-id="c2151-253">A <see cref="T:System.Uri" /> blob の URI を格納します。</span><span class="sxs-lookup"><span data-stu-id="c2151-253">A <see cref="T:System.Uri" /> containing the URI of the blob.</span></span> <span data-ttu-id="c2151-254">サービスでは、プライマリの場所にある blob の URI は、この前提としています。</span><span class="sxs-lookup"><span data-stu-id="c2151-254">The service assumes this is the URI for the blob at the primary location.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-255">Blob への参照を取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="c2151-255">Initiates an asynchronous operation that gets a reference to a blob.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-256">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="c2151-256">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBlobReferenceFromServerAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; GetBlobReferenceFromServerAsync (Uri blobUri, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; GetBlobReferenceFromServerAsync(class System.Uri blobUri, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.GetBlobReferenceFromServerAsync(System.Uri,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetBlobReferenceFromServerAsync : Uri * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;&#xA;override this.GetBlobReferenceFromServerAsync : Uri * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;" Usage="cloudBlobClient.GetBlobReferenceFromServerAsync (blobUri, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blobUri" Type="System.Uri" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="blobUri"><span data-ttu-id="c2151-257">A <see cref="T:System.Uri" /> blob の URI を格納します。</span><span class="sxs-lookup"><span data-stu-id="c2151-257">A <see cref="T:System.Uri" /> containing the URI of the blob.</span></span> <span data-ttu-id="c2151-258">サービスでは、プライマリの場所にある blob の URI は、この前提としています。</span><span class="sxs-lookup"><span data-stu-id="c2151-258">The service assumes this is the URI for the blob at the primary location.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c2151-259">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="c2151-259">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-260">Blob への参照を取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="c2151-260">Initiates an asynchronous operation that gets a reference to a blob.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-261">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="c2151-261">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBlobReferenceFromServerAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; GetBlobReferenceFromServerAsync (Microsoft.WindowsAzure.Storage.StorageUri blobUri, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; GetBlobReferenceFromServerAsync(class Microsoft.WindowsAzure.Storage.StorageUri blobUri, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.GetBlobReferenceFromServerAsync(Microsoft.WindowsAzure.Storage.StorageUri,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetBlobReferenceFromServerAsync : Microsoft.WindowsAzure.Storage.StorageUri * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;&#xA;override this.GetBlobReferenceFromServerAsync : Microsoft.WindowsAzure.Storage.StorageUri * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;" Usage="cloudBlobClient.GetBlobReferenceFromServerAsync (blobUri, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blobUri" Type="Microsoft.WindowsAzure.Storage.StorageUri" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="blobUri"><span data-ttu-id="c2151-262">A <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.StorageUri" /> blob の URI を格納します。</span><span class="sxs-lookup"><span data-stu-id="c2151-262">A <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.StorageUri" /> containing the URI of the blob.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="c2151-263"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-263">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="c2151-264">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="c2151-264">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="c2151-265"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の他のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-265">An <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies any additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="c2151-266"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-266">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-267">Blob への参照を取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="c2151-267">Initiates an asynchronous operation that gets a reference to a blob.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-268">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="c2151-268">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBlobReferenceFromServerAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; GetBlobReferenceFromServerAsync (Uri blobUri, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; GetBlobReferenceFromServerAsync(class System.Uri blobUri, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.GetBlobReferenceFromServerAsync(System.Uri,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetBlobReferenceFromServerAsync : Uri * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;&#xA;override this.GetBlobReferenceFromServerAsync : Uri * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;" Usage="cloudBlobClient.GetBlobReferenceFromServerAsync (blobUri, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blobUri" Type="System.Uri" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="blobUri"><span data-ttu-id="c2151-269">A <see cref="T:System.Uri" /> blob の URI を格納します。</span><span class="sxs-lookup"><span data-stu-id="c2151-269">A <see cref="T:System.Uri" /> containing the URI of the blob.</span></span> <span data-ttu-id="c2151-270">サービスでは、プライマリの場所にある blob の URI は、この前提としています。</span><span class="sxs-lookup"><span data-stu-id="c2151-270">The service assumes this is the URI for the blob at the primary location.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="c2151-271"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-271">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="c2151-272">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="c2151-272">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="c2151-273">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-273">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="c2151-274"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-274">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-275">返します、 <see cref="T:System.Threading.Tasks.Task`1" /> blob への参照を取得するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-275">Returns a <see cref="T:System.Threading.Tasks.Task`1" /> object that gets a reference to a blob.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-276">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="c2151-276">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBlobReferenceFromServerAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; GetBlobReferenceFromServerAsync (Microsoft.WindowsAzure.Storage.StorageUri blobUri, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; GetBlobReferenceFromServerAsync(class Microsoft.WindowsAzure.Storage.StorageUri blobUri, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.GetBlobReferenceFromServerAsync(Microsoft.WindowsAzure.Storage.StorageUri,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetBlobReferenceFromServerAsync : Microsoft.WindowsAzure.Storage.StorageUri * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;&#xA;override this.GetBlobReferenceFromServerAsync : Microsoft.WindowsAzure.Storage.StorageUri * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;" Usage="cloudBlobClient.GetBlobReferenceFromServerAsync (blobUri, accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blobUri" Type="Microsoft.WindowsAzure.Storage.StorageUri" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="blobUri"><span data-ttu-id="c2151-277">A <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.StorageUri" /> blob の URI を格納します。</span><span class="sxs-lookup"><span data-stu-id="c2151-277">A <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.StorageUri" /> containing the URI of the blob.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="c2151-278"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-278">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="c2151-279">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="c2151-279">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="c2151-280"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の他のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-280">An <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies any additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="c2151-281"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-281">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c2151-282">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="c2151-282">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-283">Blob への参照を取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="c2151-283">Initiates an asynchronous operation that gets a reference to a blob.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-284">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="c2151-284">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBlobReferenceFromServerAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; GetBlobReferenceFromServerAsync (Uri blobUri, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; GetBlobReferenceFromServerAsync(class System.Uri blobUri, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.GetBlobReferenceFromServerAsync(System.Uri,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetBlobReferenceFromServerAsync : Uri * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;&#xA;override this.GetBlobReferenceFromServerAsync : Uri * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;" Usage="cloudBlobClient.GetBlobReferenceFromServerAsync (blobUri, accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blobUri" Type="System.Uri" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="blobUri"><span data-ttu-id="c2151-285">A <see cref="T:System.Uri" /> blob の URI を格納します。</span><span class="sxs-lookup"><span data-stu-id="c2151-285">A <see cref="T:System.Uri" /> containing the URI of the blob.</span></span> <span data-ttu-id="c2151-286">サービスでは、プライマリの場所にある blob の URI は、この前提としています。</span><span class="sxs-lookup"><span data-stu-id="c2151-286">The service assumes this is the URI for the blob at the primary location.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="c2151-287"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-287">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="c2151-288">場合<c>null</c>条件は使用されません。</span><span class="sxs-lookup"><span data-stu-id="c2151-288">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="c2151-289">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-289">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="c2151-290"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-290">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c2151-291">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="c2151-291">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-292">Blob への参照を取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="c2151-292">Initiates an asynchronous operation that gets a reference to a blob.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-293">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="c2151-293">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetContainerReference">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer GetContainerReference (string containerName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer GetContainerReference(string containerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.GetContainerReference(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetContainerReference (containerName As String) As CloudBlobContainer" />
      <MemberSignature Language="F#" Value="abstract member GetContainerReference : string -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer&#xA;override this.GetContainerReference : string -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer" Usage="cloudBlobClient.GetContainerReference containerName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="containerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="containerName"><span data-ttu-id="c2151-294">コンテナーの名前を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="c2151-294">A string containing the name of the container.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-295">参照を返します、<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer" />指定の名前を持つオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-295">Returns a reference to a <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer" /> object with the specified name.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-296"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-296">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRootContainerReference">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer GetRootContainerReference ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer GetRootContainerReference() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.GetRootContainerReference" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetRootContainerReference () As CloudBlobContainer" />
      <MemberSignature Language="F#" Value="abstract member GetRootContainerReference : unit -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer&#xA;override this.GetRootContainerReference : unit -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer" Usage="cloudBlobClient.GetRootContainerReference " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c2151-297">ルート コンテナーへの参照を返します。</span><span class="sxs-lookup"><span data-stu-id="c2151-297">Returns a reference to the root container.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-298"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-298">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer" /> object.</span></span></returns>
        <remarks><span data-ttu-id="c2151-299">既にがない場合からの読み取りまたは書き込みをするには、ルート コンテナーを明示的に作成する必要があります、注意してください。</span><span class="sxs-lookup"><span data-stu-id="c2151-299">Note that the root container must be explicitly created, if it does not already exist, before you can read from it or write to it.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties GetServiceProperties (Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties GetServiceProperties(class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.GetServiceProperties(Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceProperties : Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&#xA;override this.GetServiceProperties : Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" Usage="cloudBlobClient.GetServiceProperties (requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="c2151-300">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-300">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="c2151-301"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-301">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-302">Blob サービスのサービスのプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="c2151-302">Gets service properties for the Blob service.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-303"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-303">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.GetServicePropertiesAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetServicePropertiesAsync () As Task(Of ServiceProperties)" />
      <MemberSignature Language="F#" Value="abstract member GetServicePropertiesAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;&#xA;override this.GetServicePropertiesAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;" Usage="cloudBlobClient.GetServicePropertiesAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c2151-304">Blob サービスのサービス プロパティを取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="c2151-304">Initiates an asynchronous operation to get service properties for the Blob service.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-305">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="c2151-305">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.GetServicePropertiesAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetServicePropertiesAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;&#xA;override this.GetServicePropertiesAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;" Usage="cloudBlobClient.GetServicePropertiesAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="c2151-306">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="c2151-306">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-307">Blob サービスのサービス プロパティを取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="c2151-307">Initiates an asynchronous operation to get service properties for the Blob service.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-308">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="c2151-308">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync (Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync(class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.GetServicePropertiesAsync(Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;&#xA;override this.GetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;" Usage="cloudBlobClient.GetServicePropertiesAsync (requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="c2151-309">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-309">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="c2151-310"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-310">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-311">Blob サービスのサービス プロパティを取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="c2151-311">Initiates an asynchronous operation to get service properties for the Blob service.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-312">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="c2151-312">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync (Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync(class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.GetServicePropertiesAsync(Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;&#xA;override this.GetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;" Usage="cloudBlobClient.GetServicePropertiesAsync (requestOptions, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="c2151-313">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-313">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="c2151-314"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-314">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c2151-315">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="c2151-315">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-316">Blob サービスのサービス プロパティを取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="c2151-316">Initiates an asynchronous operation to get service properties for the Blob service.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-317">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="c2151-317">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceStats">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats GetServiceStats (Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats GetServiceStats(class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.GetServiceStats(Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceStats : Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&#xA;override this.GetServiceStats : Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" Usage="cloudBlobClient.GetServiceStats (requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="c2151-318">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-318">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="c2151-319"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-319">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-320">セカンダリ Blob サービスのエンドポイントのサービスの統計情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="c2151-320">Gets service stats for the secondary Blob service endpoint.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-321"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-321">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceStatsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.GetServiceStatsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetServiceStatsAsync () As Task(Of ServiceStats)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceStatsAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;&#xA;override this.GetServiceStatsAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;" Usage="cloudBlobClient.GetServiceStatsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c2151-322">セカンダリ Blob サービス エンドポイントのサービスの統計情報を取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="c2151-322">Initiates an asynchronous operation to get service stats for the secondary Blob service endpoint.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-323">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="c2151-323">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceStatsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.GetServiceStatsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceStatsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;&#xA;override this.GetServiceStatsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;" Usage="cloudBlobClient.GetServiceStatsAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="c2151-324">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="c2151-324">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-325">セカンダリ Blob サービス エンドポイントのサービスの統計情報を取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="c2151-325">Initiates an asynchronous operation to get service stats for the secondary Blob service endpoint.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-326">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="c2151-326">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceStatsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync (Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync(class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.GetServiceStatsAsync(Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceStatsAsync : Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;&#xA;override this.GetServiceStatsAsync : Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;" Usage="cloudBlobClient.GetServiceStatsAsync (requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="c2151-327">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-327">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="c2151-328"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-328">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-329">セカンダリ Blob サービス エンドポイントのサービスの統計情報を取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="c2151-329">Initiates an asynchronous operation to get service stats for the secondary Blob service endpoint.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-330">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="c2151-330">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceStatsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync (Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync(class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.GetServiceStatsAsync(Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceStatsAsync : Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;&#xA;override this.GetServiceStatsAsync : Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;" Usage="cloudBlobClient.GetServiceStatsAsync (requestOptions, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="c2151-331">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-331">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="c2151-332"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-332">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c2151-333">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="c2151-333">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-334">セカンダリ Blob サービス エンドポイントのサービスの統計情報を取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="c2151-334">Initiates an asynchronous operation to get service stats for the secondary Blob service endpoint.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-335">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="c2151-335">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBlobs">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.IListBlobItem&gt; ListBlobs (string prefix, bool useFlatBlobListing = false, Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails blobListingDetails = Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails.None, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.IListBlobItem&gt; ListBlobs(string prefix, bool useFlatBlobListing, valuetype Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails blobListingDetails, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.ListBlobs(System.String,System.Boolean,Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ListBlobs : string * bool * Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Blob.IListBlobItem&gt;&#xA;override this.ListBlobs : string * bool * Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Blob.IListBlobItem&gt;" Usage="cloudBlobClient.ListBlobs (prefix, useFlatBlobListing, blobListingDetails, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="useFlatBlobListing" Type="System.Boolean" />
        <Parameter Name="blobListingDetails" Type="Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="c2151-336">Blob 名のプレフィックスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="c2151-336">A string containing the blob name prefix.</span></span></param>
        <param name="useFlatBlobListing"><span data-ttu-id="c2151-337">フラット リスト内の blob を一覧表示するかどうか、または仮想ディレクトリで階層的に、blob を一覧表示するかどうかを指定するブール値。</span><span class="sxs-lookup"><span data-stu-id="c2151-337">A boolean value that specifies whether to list blobs in a flat listing, or whether to list blobs hierarchically, by virtual directory.</span></span></param>
        <param name="blobListingDetails"><span data-ttu-id="c2151-338">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" />一覧に含める項目を記述する列挙です。</span><span class="sxs-lookup"><span data-stu-id="c2151-338">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" /> enumeration describing which items to include in the listing.</span></span></param>
        <param name="options"><span data-ttu-id="c2151-339">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-339">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="c2151-340">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="c2151-340">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="c2151-341"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-341">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-342">遅延を取得、コンテナー内の blob の列挙可能なコレクションを返します。</span><span class="sxs-lookup"><span data-stu-id="c2151-342">Returns an enumerable collection of blobs in the container, retrieved lazily.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-343">実装するオブジェクトの列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.Blob.IListBlobItem" />遅れてが取得されます。</span><span class="sxs-lookup"><span data-stu-id="c2151-343">An enumerable collection of objects that implement <see cref="T:Microsoft.WindowsAzure.Storage.Blob.IListBlobItem" /> and are retrieved lazily.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBlobsSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment ListBlobsSegmented (string prefix, Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment ListBlobsSegmented(string prefix, class Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.ListBlobsSegmented(System.String,Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ListBlobsSegmented (prefix As String, currentToken As BlobContinuationToken) As BlobResultSegment" />
      <MemberSignature Language="F#" Value="abstract member ListBlobsSegmented : string * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken -&gt; Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&#xA;override this.ListBlobsSegmented : string * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken -&gt; Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment" Usage="cloudBlobClient.ListBlobsSegmented (prefix, currentToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="c2151-344">コンテナー名を含む blob 名のプレフィックスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="c2151-344">A string containing the blob name prefix, including the container name.</span></span></param>
        <param name="currentToken"><span data-ttu-id="c2151-345">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />前の一覧作成操作によって返されるオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-345">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" /> object returned by a previous listing operation.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-346">コンテナー内の blob 項目のコレクションを含む結果セグメントを返します。</span><span class="sxs-lookup"><span data-stu-id="c2151-346">Returns a result segment containing a collection of blob items in the container.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-347"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-347">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBlobsSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment ListBlobsSegmented (string prefix, bool useFlatBlobListing, Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails blobListingDetails, Nullable&lt;int&gt; maxResults, Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment ListBlobsSegmented(string prefix, bool useFlatBlobListing, valuetype Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails blobListingDetails, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.ListBlobsSegmented(System.String,System.Boolean,Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ListBlobsSegmented : string * bool * Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&#xA;override this.ListBlobsSegmented : string * bool * Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment" Usage="cloudBlobClient.ListBlobsSegmented (prefix, useFlatBlobListing, blobListingDetails, maxResults, currentToken, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="useFlatBlobListing" Type="System.Boolean" />
        <Parameter Name="blobListingDetails" Type="Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="c2151-348">コンテナー名を含む blob 名のプレフィックスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="c2151-348">A string containing the blob name prefix, including the container name.</span></span></param>
        <param name="useFlatBlobListing"><span data-ttu-id="c2151-349">フラット リスト内の blob を一覧表示するかどうか、または仮想ディレクトリで階層的に、blob を一覧表示するかどうかを指定するブール値。</span><span class="sxs-lookup"><span data-stu-id="c2151-349">A boolean value that specifies whether to list blobs in a flat listing, or whether to list blobs hierarchically, by virtual directory.</span></span></param>
        <param name="blobListingDetails"><span data-ttu-id="c2151-350">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" />一覧に含める項目を記述する列挙です。</span><span class="sxs-lookup"><span data-stu-id="c2151-350">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" /> enumeration describing which items to include in the listing.</span></span></param>
        <param name="maxResults"><span data-ttu-id="c2151-351">5000 の操作あたりの上限に達するまで、一度に返される結果の最大数を示す正の整数値。</span><span class="sxs-lookup"><span data-stu-id="c2151-351">A non-negative integer value that indicates the maximum number of results to be returned at a time, up to the per-operation limit of 5000.</span></span> <span data-ttu-id="c2151-352">この値が場合<c>null</c>結果の最大数が返されます、最大 5000 です。</span><span class="sxs-lookup"><span data-stu-id="c2151-352">If this value is <c>null</c>, the maximum possible number of results will be returned, up to 5000.</span></span></param>
        <param name="currentToken"><span data-ttu-id="c2151-353">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />前の一覧作成操作によって返されるオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-353">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" /> object returned by a previous listing operation.</span></span></param>
        <param name="options"><span data-ttu-id="c2151-354">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-354">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="c2151-355"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-355">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-356">コンテナー内の blob 項目のコレクションを含む結果セグメントを返します。</span><span class="sxs-lookup"><span data-stu-id="c2151-356">Returns a result segment containing a collection of blob items in the container.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-357"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-357">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBlobsSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt; ListBlobsSegmentedAsync (string prefix, Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt; ListBlobsSegmentedAsync(string prefix, class Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.ListBlobsSegmentedAsync(System.String,Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ListBlobsSegmentedAsync (prefix As String, currentToken As BlobContinuationToken) As Task(Of BlobResultSegment)" />
      <MemberSignature Language="F#" Value="abstract member ListBlobsSegmentedAsync : string * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt;&#xA;override this.ListBlobsSegmentedAsync : string * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt;" Usage="cloudBlobClient.ListBlobsSegmentedAsync (prefix, currentToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="c2151-358">コンテナー名を含む blob 名のプレフィックスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="c2151-358">A string containing the blob name prefix, including the container name.</span></span></param>
        <param name="currentToken"><span data-ttu-id="c2151-359">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />前の一覧作成操作によって返されるオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-359">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" /> object returned by a previous listing operation.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-360">コンテナー内の blob 項目のコレクションを含む結果セグメントを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="c2151-360">Initiates an asynchronous operation to return a result segment containing a collection of blob items in the container.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-361">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="c2151-361">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBlobsSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt; ListBlobsSegmentedAsync (string prefix, Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt; ListBlobsSegmentedAsync(string prefix, class Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.ListBlobsSegmentedAsync(System.String,Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListBlobsSegmentedAsync : string * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt;&#xA;override this.ListBlobsSegmentedAsync : string * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt;" Usage="cloudBlobClient.ListBlobsSegmentedAsync (prefix, currentToken, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="c2151-362">Blob 名のプレフィックスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="c2151-362">A string containing the blob name prefix.</span></span></param>
        <param name="currentToken"><span data-ttu-id="c2151-363">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />前の一覧作成操作によって返されるオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-363">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" /> object returned by a previous listing operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c2151-364">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="c2151-364">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-365">コンテナー内の blob 項目のコレクションを含む結果セグメントを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="c2151-365">Initiates an asynchronous operation to return a result segment containing a collection of blob items in the container.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-366">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="c2151-366">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBlobsSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt; ListBlobsSegmentedAsync (string prefix, bool useFlatBlobListing, Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails blobListingDetails, Nullable&lt;int&gt; maxResults, Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt; ListBlobsSegmentedAsync(string prefix, bool useFlatBlobListing, valuetype Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails blobListingDetails, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.ListBlobsSegmentedAsync(System.String,System.Boolean,Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ListBlobsSegmentedAsync : string * bool * Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt;&#xA;override this.ListBlobsSegmentedAsync : string * bool * Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt;" Usage="cloudBlobClient.ListBlobsSegmentedAsync (prefix, useFlatBlobListing, blobListingDetails, maxResults, currentToken, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="useFlatBlobListing" Type="System.Boolean" />
        <Parameter Name="blobListingDetails" Type="Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="c2151-367">Blob 名のプレフィックスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="c2151-367">A string containing the blob name prefix.</span></span></param>
        <param name="useFlatBlobListing"><span data-ttu-id="c2151-368">フラット リスト内の blob を一覧表示するかどうか、または仮想ディレクトリで階層的に、blob を一覧表示するかどうかを指定するブール値。</span><span class="sxs-lookup"><span data-stu-id="c2151-368">A boolean value that specifies whether to list blobs in a flat listing, or whether to list blobs hierarchically, by virtual directory.</span></span></param>
        <param name="blobListingDetails"><span data-ttu-id="c2151-369">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" />一覧に含める項目を記述する列挙です。</span><span class="sxs-lookup"><span data-stu-id="c2151-369">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" /> enumeration describing which items to include in the listing.</span></span></param>
        <param name="maxResults"><span data-ttu-id="c2151-370">5000 の操作あたりの上限に達するまで、一度に返される結果の最大数を示す正の整数値。</span><span class="sxs-lookup"><span data-stu-id="c2151-370">A non-negative integer value that indicates the maximum number of results to be returned at a time, up to the per-operation limit of 5000.</span></span> <span data-ttu-id="c2151-371">この値が場合<c>null</c>結果の最大数が返されます、最大 5000 です。</span><span class="sxs-lookup"><span data-stu-id="c2151-371">If this value is <c>null</c>, the maximum possible number of results will be returned, up to 5000.</span></span></param>
        <param name="currentToken"><span data-ttu-id="c2151-372">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />前の一覧作成操作によって返されるオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-372">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" /> object returned by a previous listing operation.</span></span></param>
        <param name="options"><span data-ttu-id="c2151-373">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-373">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="c2151-374"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-374">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-375">コンテナー内の blob 項目のコレクションを含む結果セグメントを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="c2151-375">Initiates an asynchronous operation to return a result segment containing a collection of blob items in the container.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-376">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="c2151-376">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBlobsSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt; ListBlobsSegmentedAsync (string prefix, bool useFlatBlobListing, Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails blobListingDetails, Nullable&lt;int&gt; maxResults, Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt; ListBlobsSegmentedAsync(string prefix, bool useFlatBlobListing, valuetype Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails blobListingDetails, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.ListBlobsSegmentedAsync(System.String,System.Boolean,Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListBlobsSegmentedAsync : string * bool * Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt;&#xA;override this.ListBlobsSegmentedAsync : string * bool * Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt;" Usage="cloudBlobClient.ListBlobsSegmentedAsync (prefix, useFlatBlobListing, blobListingDetails, maxResults, currentToken, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="useFlatBlobListing" Type="System.Boolean" />
        <Parameter Name="blobListingDetails" Type="Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="c2151-377">Blob 名のプレフィックスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="c2151-377">A string containing the blob name prefix.</span></span></param>
        <param name="useFlatBlobListing"><span data-ttu-id="c2151-378">フラット リスト内の blob を一覧表示するかどうか、または仮想ディレクトリで階層的に、blob を一覧表示するかどうかを指定するブール値。</span><span class="sxs-lookup"><span data-stu-id="c2151-378">A boolean value that specifies whether to list blobs in a flat listing, or whether to list blobs hierarchically, by virtual directory.</span></span></param>
        <param name="blobListingDetails"><span data-ttu-id="c2151-379">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" />一覧に含める項目を記述する列挙です。</span><span class="sxs-lookup"><span data-stu-id="c2151-379">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" /> enumeration describing which items to include in the listing.</span></span></param>
        <param name="maxResults"><span data-ttu-id="c2151-380">5000 の操作あたりの上限に達するまで、一度に返される結果の最大数を示す正の整数値。</span><span class="sxs-lookup"><span data-stu-id="c2151-380">A non-negative integer value that indicates the maximum number of results to be returned at a time, up to the per-operation limit of 5000.</span></span> <span data-ttu-id="c2151-381">この値が場合<c>null</c>結果の最大数が返されます、最大 5000 です。</span><span class="sxs-lookup"><span data-stu-id="c2151-381">If this value is <c>null</c>, the maximum possible number of results will be returned, up to 5000.</span></span></param>
        <param name="currentToken"><span data-ttu-id="c2151-382">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />前の一覧作成操作によって返されるオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-382">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" /> object returned by a previous listing operation.</span></span></param>
        <param name="options"><span data-ttu-id="c2151-383">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-383">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="c2151-384"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-384">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c2151-385">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="c2151-385">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-386">コンテナー内の blob 項目のコレクションを含む結果セグメントを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="c2151-386">Initiates an asynchronous operation to return a result segment containing a collection of blob items in the container.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-387">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="c2151-387">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListContainers">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer&gt; ListContainers (string prefix = null, Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails detailsIncluded = Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails.None, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer&gt; ListContainers(string prefix, valuetype Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails detailsIncluded, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.ListContainers(System.String,Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ListContainers : string * Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer&gt;&#xA;override this.ListContainers : string * Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer&gt;" Usage="cloudBlobClient.ListContainers (prefix, detailsIncluded, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="detailsIncluded" Type="Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="c2151-388">コンテナー名のプレフィックスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="c2151-388">A string containing the container name prefix.</span></span></param>
        <param name="detailsIncluded"><span data-ttu-id="c2151-389">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails" />一覧にコンテナーのメタデータを返すかどうかを示す列挙値。</span><span class="sxs-lookup"><span data-stu-id="c2151-389">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails" /> enumeration value that indicates whether to return container metadata with the listing.</span></span></param>
        <param name="options"><span data-ttu-id="c2151-390">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-390">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="c2151-391">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="c2151-391">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="c2151-392"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-392">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-393">指定したプレフィックスで名前が始まるし、遅延を取得するコンテナーの列挙可能なコレクションを返します。</span><span class="sxs-lookup"><span data-stu-id="c2151-393">Returns an enumerable collection of containers whose names begin with the specified prefix and that are retrieved lazily.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-394">列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer" />遅れて取得されるオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-394">An enumerable collection of <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer" /> objects that are retrieved lazily.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListContainersSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment ListContainersSegmented (Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment ListContainersSegmented(class Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.ListContainersSegmented(Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ListContainersSegmented (currentToken As BlobContinuationToken) As ContainerResultSegment" />
      <MemberSignature Language="F#" Value="abstract member ListContainersSegmented : Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken -&gt; Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment&#xA;override this.ListContainersSegmented : Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken -&gt; Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment" Usage="cloudBlobClient.ListContainersSegmented currentToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />
      </Parameters>
      <Docs>
        <param name="currentToken"><span data-ttu-id="c2151-395">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />前の一覧作成操作によって返されるオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-395">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" /> object returned by a previous listing operation.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-396">コレクションを含む結果セグメントを返します<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-396">Returns a result segment containing a collection of <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer" /> objects.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-397"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-397">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListContainersSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment ListContainersSegmented (string prefix, Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment ListContainersSegmented(string prefix, class Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.ListContainersSegmented(System.String,Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ListContainersSegmented (prefix As String, currentToken As BlobContinuationToken) As ContainerResultSegment" />
      <MemberSignature Language="F#" Value="abstract member ListContainersSegmented : string * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken -&gt; Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment&#xA;override this.ListContainersSegmented : string * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken -&gt; Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment" Usage="cloudBlobClient.ListContainersSegmented (prefix, currentToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="c2151-398">コンテナー名のプレフィックスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="c2151-398">A string containing the container name prefix.</span></span></param>
        <param name="currentToken"><span data-ttu-id="c2151-399">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />前の一覧作成操作によって返されるオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-399">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" /> object returned by a previous listing operation.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-400">コレクションを含む結果セグメントを返します<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-400">Returns a result segment containing a collection of <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer" /> objects.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-401"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-401">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListContainersSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment ListContainersSegmented (string prefix, Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails detailsIncluded, Nullable&lt;int&gt; maxResults, Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment ListContainersSegmented(string prefix, valuetype Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails detailsIncluded, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.ListContainersSegmented(System.String,Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ListContainersSegmented : string * Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment&#xA;override this.ListContainersSegmented : string * Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment" Usage="cloudBlobClient.ListContainersSegmented (prefix, detailsIncluded, maxResults, currentToken, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="detailsIncluded" Type="Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="c2151-402">コンテナー名のプレフィックスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="c2151-402">A string containing the container name prefix.</span></span></param>
        <param name="detailsIncluded"><span data-ttu-id="c2151-403">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails" />一覧にコンテナーのメタデータを返すかどうかを示す列挙値。</span><span class="sxs-lookup"><span data-stu-id="c2151-403">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails" /> enumeration value that indicates whether to return container metadata with the listing.</span></span></param>
        <param name="maxResults"><span data-ttu-id="c2151-404">5000 の操作あたりの上限に達するまで、結果のセグメントに返される結果の最大数を示す正の整数値。</span><span class="sxs-lookup"><span data-stu-id="c2151-404">A non-negative integer value that indicates the maximum number of results to be returned in the result segment, up to the per-operation limit of 5000.</span></span> <span data-ttu-id="c2151-405">この値が場合<c>null</c>結果の最大数が返されます、最大 5000 です。</span><span class="sxs-lookup"><span data-stu-id="c2151-405">If this value is <c>null</c>, the maximum possible number of results will be returned, up to 5000.</span></span></param>
        <param name="currentToken"><span data-ttu-id="c2151-406">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />前の一覧作成操作によって返されるオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-406">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" /> object returned by a previous listing operation.</span></span></param>
        <param name="options"><span data-ttu-id="c2151-407">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-407">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="c2151-408">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="c2151-408">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="c2151-409"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-409">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-410">名前が指定したプレフィックスで始まるコンテナーのコレクションを含む結果セグメントを返します。</span><span class="sxs-lookup"><span data-stu-id="c2151-410">Returns a result segment containing a collection of containers whose names begin with the specified prefix.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-411"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-411">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListContainersSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment&gt; ListContainersSegmentedAsync (Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken continuationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment&gt; ListContainersSegmentedAsync(class Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken continuationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.ListContainersSegmentedAsync(Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ListContainersSegmentedAsync (continuationToken As BlobContinuationToken) As Task(Of ContainerResultSegment)" />
      <MemberSignature Language="F#" Value="abstract member ListContainersSegmentedAsync : Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment&gt;&#xA;override this.ListContainersSegmentedAsync : Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment&gt;" Usage="cloudBlobClient.ListContainersSegmentedAsync continuationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="continuationToken" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />
      </Parameters>
      <Docs>
        <param name="continuationToken"><span data-ttu-id="c2151-412">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />前の一覧作成操作によって返されるオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-412">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" /> object returned by a previous listing operation.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-413">コンテナーのコレクションを含む結果セグメントを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="c2151-413">Initiates an asynchronous operation to return a result segment containing a collection of containers.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-414">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="c2151-414">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListContainersSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment&gt; ListContainersSegmentedAsync (Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken continuationToken, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment&gt; ListContainersSegmentedAsync(class Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken continuationToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.ListContainersSegmentedAsync(Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListContainersSegmentedAsync : Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment&gt;&#xA;override this.ListContainersSegmentedAsync : Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment&gt;" Usage="cloudBlobClient.ListContainersSegmentedAsync (continuationToken, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="continuationToken" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="continuationToken"><span data-ttu-id="c2151-415">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />前の一覧作成操作によって返されるオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-415">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" /> object returned by a previous listing operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c2151-416">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="c2151-416">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-417">コンテナーのコレクションを含む結果セグメントを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="c2151-417">Initiates an asynchronous operation to return a result segment containing a collection of containers.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-418">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="c2151-418">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListContainersSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment&gt; ListContainersSegmentedAsync (string prefix, Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken continuationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment&gt; ListContainersSegmentedAsync(string prefix, class Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken continuationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.ListContainersSegmentedAsync(System.String,Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ListContainersSegmentedAsync (prefix As String, continuationToken As BlobContinuationToken) As Task(Of ContainerResultSegment)" />
      <MemberSignature Language="F#" Value="abstract member ListContainersSegmentedAsync : string * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment&gt;&#xA;override this.ListContainersSegmentedAsync : string * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment&gt;" Usage="cloudBlobClient.ListContainersSegmentedAsync (prefix, continuationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="continuationToken" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="c2151-419">コンテナー名のプレフィックスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="c2151-419">A string containing the container name prefix.</span></span></param>
        <param name="continuationToken"><span data-ttu-id="c2151-420">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />前の一覧作成操作によって返されるオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-420">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" /> object returned by a previous listing operation.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-421">コンテナーのコレクションを含む結果セグメントを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="c2151-421">Initiates an asynchronous operation to return a result segment containing a collection of containers.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-422">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="c2151-422">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListContainersSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment&gt; ListContainersSegmentedAsync (string prefix, Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken continuationToken, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment&gt; ListContainersSegmentedAsync(string prefix, class Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken continuationToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.ListContainersSegmentedAsync(System.String,Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListContainersSegmentedAsync : string * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment&gt;&#xA;override this.ListContainersSegmentedAsync : string * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment&gt;" Usage="cloudBlobClient.ListContainersSegmentedAsync (prefix, continuationToken, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="continuationToken" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="c2151-423">コンテナー名のプレフィックスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="c2151-423">A string containing the container name prefix.</span></span></param>
        <param name="continuationToken"><span data-ttu-id="c2151-424">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />前の一覧作成操作によって返されるオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-424">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" /> object returned by a previous listing operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c2151-425">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="c2151-425">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-426">コンテナーのコレクションを含む結果セグメントを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="c2151-426">Initiates an asynchronous operation to return a result segment containing a collection of containers.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-427">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="c2151-427">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListContainersSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment&gt; ListContainersSegmentedAsync (string prefix, Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails detailsIncluded, Nullable&lt;int&gt; maxResults, Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken continuationToken, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment&gt; ListContainersSegmentedAsync(string prefix, valuetype Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails detailsIncluded, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken continuationToken, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.ListContainersSegmentedAsync(System.String,Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ListContainersSegmentedAsync : string * Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment&gt;&#xA;override this.ListContainersSegmentedAsync : string * Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment&gt;" Usage="cloudBlobClient.ListContainersSegmentedAsync (prefix, detailsIncluded, maxResults, continuationToken, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="detailsIncluded" Type="Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="continuationToken" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="c2151-428">コンテナー名のプレフィックスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="c2151-428">A string containing the container name prefix.</span></span></param>
        <param name="detailsIncluded"><span data-ttu-id="c2151-429">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails" />一覧にコンテナーのメタデータを返すかどうかを示す列挙値。</span><span class="sxs-lookup"><span data-stu-id="c2151-429">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails" /> enumeration value that indicates whether to return container metadata with the listing.</span></span></param>
        <param name="maxResults"><span data-ttu-id="c2151-430">5000 の操作あたりの上限に達するまで、結果のセグメントに返される結果の最大数を示す正の整数値。</span><span class="sxs-lookup"><span data-stu-id="c2151-430">A non-negative integer value that indicates the maximum number of results to be returned in the result segment, up to the per-operation limit of 5000.</span></span> <span data-ttu-id="c2151-431">この値が場合<c>null</c>結果の最大数が返されます、最大 5000 です。</span><span class="sxs-lookup"><span data-stu-id="c2151-431">If this value is <c>null</c>, the maximum possible number of results will be returned, up to 5000.</span></span></param>
        <param name="continuationToken"><span data-ttu-id="c2151-432">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />前の一覧作成操作によって返されるオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-432">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" /> object returned by a previous listing operation.</span></span></param>
        <param name="options"><span data-ttu-id="c2151-433">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-433">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="c2151-434"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-434">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-435">コンテナーのコレクションを含む結果セグメントを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="c2151-435">Initiates an asynchronous operation to return a result segment containing a collection of containers.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-436">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="c2151-436">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListContainersSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment&gt; ListContainersSegmentedAsync (string prefix, Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails detailsIncluded, Nullable&lt;int&gt; maxResults, Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken continuationToken, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment&gt; ListContainersSegmentedAsync(string prefix, valuetype Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails detailsIncluded, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken continuationToken, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.ListContainersSegmentedAsync(System.String,Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListContainersSegmentedAsync : string * Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment&gt;&#xA;override this.ListContainersSegmentedAsync : string * Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment&gt;" Usage="cloudBlobClient.ListContainersSegmentedAsync (prefix, detailsIncluded, maxResults, continuationToken, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="detailsIncluded" Type="Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="continuationToken" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="c2151-437">コンテナー名のプレフィックスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="c2151-437">A string containing the container name prefix.</span></span></param>
        <param name="detailsIncluded"><span data-ttu-id="c2151-438">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails" />一覧にコンテナーのメタデータを返すかどうかを示す列挙値。</span><span class="sxs-lookup"><span data-stu-id="c2151-438">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails" /> enumeration value that indicates whether to return container metadata with the listing.</span></span></param>
        <param name="maxResults"><span data-ttu-id="c2151-439">5000 の操作あたりの上限に達するまで、結果のセグメントに返される結果の最大数を示す正の整数値。</span><span class="sxs-lookup"><span data-stu-id="c2151-439">A non-negative integer value that indicates the maximum number of results to be returned in the result segment, up to the per-operation limit of 5000.</span></span> <span data-ttu-id="c2151-440">この値が場合<c>null</c>結果の最大数が返されます、最大 5000 です。</span><span class="sxs-lookup"><span data-stu-id="c2151-440">If this value is <c>null</c>, the maximum possible number of results will be returned, up to 5000.</span></span></param>
        <param name="continuationToken"><span data-ttu-id="c2151-441">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />前の一覧作成操作によって返されるオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-441">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" /> object returned by a previous listing operation.</span></span></param>
        <param name="options"><span data-ttu-id="c2151-442">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-442">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="c2151-443"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-443">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c2151-444">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="c2151-444">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-445">コンテナーのコレクションを含む結果セグメントを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="c2151-445">Initiates an asynchronous operation to return a result segment containing a collection of containers.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-446">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="c2151-446">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy RetryPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy RetryPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.RetryPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryPolicy As IRetryPolicy" />
      <MemberSignature Language="F#" Value="member this.RetryPolicy : Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.RetryPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use DefaultRequestOptions.RetryPolicy.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c2151-447">取得または Blob サービス クライアントを介して行われる要求の既定の再試行ポリシーを設定します。</span><span class="sxs-lookup"><span data-stu-id="c2151-447">Gets or sets the default retry policy for requests made via the Blob service client.</span></span>
            </summary>
        <value><span data-ttu-id="c2151-448"><see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" /> 型のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-448">An object of type <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" />.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual void SetServiceProperties (Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SetServiceProperties(class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.SetServiceProperties(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetServiceProperties : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.SetServiceProperties : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudBlobClient.SetServiceProperties (properties, requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="c2151-449"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-449">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> object.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="c2151-450">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-450">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="c2151-451"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-451">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-452">セットは、Blob サービスのプロパティをサービスします。</span><span class="sxs-lookup"><span data-stu-id="c2151-452">Sets service properties for the Blob service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetServicePropertiesAsync (Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetServicePropertiesAsync(class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.SetServicePropertiesAsync(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function SetServicePropertiesAsync (properties As ServiceProperties) As Task" />
      <MemberSignature Language="F#" Value="abstract member SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties -&gt; System.Threading.Tasks.Task&#xA;override this.SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties -&gt; System.Threading.Tasks.Task" Usage="cloudBlobClient.SetServicePropertiesAsync properties" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="c2151-453"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-453">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-454">Blob サービスのサービス プロパティを設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="c2151-454">Initiates an asynchronous operation that sets service properties for the Blob service.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-455">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-455">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetServicePropertiesAsync (Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetServicePropertiesAsync(class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.SetServicePropertiesAsync(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlobClient.SetServicePropertiesAsync (properties, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="c2151-456"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-456">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> object.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c2151-457">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="c2151-457">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-458">Blob サービスのサービス プロパティを設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="c2151-458">Initiates an asynchronous operation that sets service properties for the Blob service.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-459">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-459">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetServicePropertiesAsync (Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetServicePropertiesAsync(class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.SetServicePropertiesAsync(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudBlobClient.SetServicePropertiesAsync (properties, requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="c2151-460"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-460">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> object.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="c2151-461">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-461">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="c2151-462"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-462">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-463">Blob サービスのサービス プロパティを設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="c2151-463">Initiates an asynchronous operation that sets service properties for the Blob service.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-464">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-464">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetServicePropertiesAsync (Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetServicePropertiesAsync(class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.SetServicePropertiesAsync(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlobClient.SetServicePropertiesAsync (properties, requestOptions, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="c2151-465"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-465">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> object.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="c2151-466">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-466">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="c2151-467"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-467">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c2151-468">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="c2151-468">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="c2151-469">Blob サービスのサービス プロパティを設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="c2151-469">Initiates an asynchronous operation that sets service properties for the Blob service.</span></span>
            </summary>
        <returns><span data-ttu-id="c2151-470">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2151-470">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageUri">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.StorageUri StorageUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.StorageUri StorageUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.StorageUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StorageUri As StorageUri" />
      <MemberSignature Language="F#" Value="member this.StorageUri : Microsoft.WindowsAzure.Storage.StorageUri" Usage="Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.StorageUri" />
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
            <span data-ttu-id="c2151-471">プライマリとセカンダリの両方の場所の Blob サービスのエンドポイントを取得します。</span><span class="sxs-lookup"><span data-stu-id="c2151-471">Gets the Blob service endpoints for both the primary and secondary locations.</span></span>
            </summary>
        <value><span data-ttu-id="c2151-472">型のオブジェクト<see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.StorageUri" />プライマリとセカンダリの両方の場所のサービスの Uri を Blob を格納します。</span><span class="sxs-lookup"><span data-stu-id="c2151-472">An object of type <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient.StorageUri" /> containing Blob service URIs for both the primary and secondary locations.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>