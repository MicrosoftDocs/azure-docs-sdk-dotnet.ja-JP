<Type Name="CloudQueueClient" FullName="Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient">
  <TypeSignature Language="C#" Value="public class CloudQueueClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CloudQueueClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient" />
  <TypeSignature Language="VB.NET" Value="Public Class CloudQueueClient" />
  <TypeSignature Language="F#" Value="type CloudQueueClient = class" />
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
            <span data-ttu-id="02a0f-101">Microsoft Azure Queue サービスのクライアント側の論理表現を提供します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-101">Provides a client-side logical representation of the Microsoft Azure Queue service.</span></span> <span data-ttu-id="02a0f-102">このクライアントを使用してを構成およびキュー サービスに対して要求を実行します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-102">This client is used to configure and execute requests against the Queue service.</span></span>
            </summary>
    <remarks><span data-ttu-id="02a0f-103">サービス クライアントは、エンドポイントまたはキュー サービスのエンドポイントをカプセル化します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-103">The service client encapsulates the endpoint or endpoints for the Queue service.</span></span> <span data-ttu-id="02a0f-104">サービス クライアントを認証済みアクセスに使用する場合、ストレージ アカウントにアクセスするための資格情報もカプセル化します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-104">If the service client will be used for authenticated access, it also encapsulates the credentials for accessing the storage account.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudQueueClient (Microsoft.WindowsAzure.Storage.StorageUri storageUri, Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.StorageUri storageUri, class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.#ctor(Microsoft.WindowsAzure.Storage.StorageUri,Microsoft.WindowsAzure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient : Microsoft.WindowsAzure.Storage.StorageUri * Microsoft.WindowsAzure.Storage.Auth.StorageCredentials -&gt; Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient" Usage="new Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient (storageUri, credentials)" />
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
        <param name="storageUri"><span data-ttu-id="02a0f-105">A<see cref="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.StorageUri" />クライアントの作成に使用するキュー サービス エンドポイントを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-105">A <see cref="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.StorageUri" /> object containing the Queue service endpoint to use to create the client.</span></span></param>
        <param name="credentials"><span data-ttu-id="02a0f-106"><see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-106">A <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="02a0f-107">新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient" />クラス、指定したキュー サービス エンドポイントとアカウントの資格情報を使用します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-107">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient" /> class using the specified Queue service endpoint and account credentials.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudQueueClient (Uri baseUri, Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.#ctor(System.Uri,Microsoft.WindowsAzure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (baseUri As Uri, credentials As StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient : Uri * Microsoft.WindowsAzure.Storage.Auth.StorageCredentials -&gt; Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient" Usage="new Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient (baseUri, credentials)" />
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
        <param name="baseUri"><span data-ttu-id="02a0f-108"><see cref="T:System.Uri" />エンドポイントを含む、キュー サービスを使用してクライアントを作成します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-108">The <see cref="T:System.Uri" /> containing the Queue service endpoint to use to create the client.</span></span></param>
        <param name="credentials"><span data-ttu-id="02a0f-109"><see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-109">A <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="02a0f-110">新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient" />クラス、指定したキュー サービス エンドポイントとアカウントの資格情報を使用します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-110">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient" /> class using the specified Queue service endpoint and account credentials.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationScheme">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.AuthenticationScheme AuthenticationScheme { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.AuthenticationScheme AuthenticationScheme" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.AuthenticationScheme" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationScheme As AuthenticationScheme" />
      <MemberSignature Language="F#" Value="member this.AuthenticationScheme : Microsoft.WindowsAzure.Storage.AuthenticationScheme with get, set" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.AuthenticationScheme" />
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
            <span data-ttu-id="02a0f-111">取得または HTTP 要求の署名に使用する認証スキームを設定します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-111">Gets or sets the authentication scheme to use to sign HTTP requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="02a0f-112">共有キーまたは共有キー Lite の資格情報が使用される場合にのみ、このプロパティを設定します。共有アクセス署名または匿名アクセス経由での認証には適用されません。</span><span class="sxs-lookup"><span data-stu-id="02a0f-112">This property is set only when Shared Key or Shared Key Lite credentials are used; it does not apply to authentication via a shared access signature or anonymous access.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.BaseUri" />
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
            <span data-ttu-id="02a0f-113">プライマリの場所の Queue サービス クライアントのベース URI を取得します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-113">Gets the base URI for the Queue service client, at the primary location.</span></span>
            </summary>
        <value><span data-ttu-id="02a0f-114">A<see cref="T:System.Uri" />プライマリの場所の Queue サービスのクライアントのオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-114">A <see cref="T:System.Uri" /> object for the Queue service client, at the primary location.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceProperties (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceProperties(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.BeginGetServiceProperties(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginGetServiceProperties (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginGetServiceProperties : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetServiceProperties : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueueClient.BeginGetServiceProperties (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <param name="callback"><span data-ttu-id="02a0f-115"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="02a0f-115">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="02a0f-116">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-116">A user-defined object to be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="02a0f-117">キュー サービスのサービス プロパティを取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-117">Begins an asynchronous operation to get service properties for the Queue service.</span></span>
            </summary>
        <returns><span data-ttu-id="02a0f-118"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-118">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceProperties (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceProperties(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.BeginGetServiceProperties(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginGetServiceProperties : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetServiceProperties : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueueClient.BeginGetServiceProperties (requestOptions, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="02a0f-119">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-119">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="02a0f-120"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-120">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="02a0f-121"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="02a0f-121">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="02a0f-122">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-122">A user-defined object to be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="02a0f-123">キュー サービスのサービス プロパティを取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-123">Begins an asynchronous operation to get service properties for the Queue service.</span></span>
            </summary>
        <returns><span data-ttu-id="02a0f-124"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-124">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetServiceStats">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceStats (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceStats(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.BeginGetServiceStats(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginGetServiceStats (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginGetServiceStats : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetServiceStats : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueueClient.BeginGetServiceStats (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <param name="callback"><span data-ttu-id="02a0f-125"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="02a0f-125">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="02a0f-126">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-126">A user-defined object to be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="02a0f-127">セカンダリ Queue サービス エンドポイントのサービスの統計情報を取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-127">Begins an asynchronous operation to get service stats for the secondary Queue service endpoint.</span></span>
            </summary>
        <returns><span data-ttu-id="02a0f-128"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-128">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetServiceStats">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceStats (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceStats(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.BeginGetServiceStats(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginGetServiceStats : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetServiceStats : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueueClient.BeginGetServiceStats (requestOptions, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="02a0f-129">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-129">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="02a0f-130"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-130">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="02a0f-131"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="02a0f-131">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="02a0f-132">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-132">A user-defined object to be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="02a0f-133">セカンダリ Queue サービス エンドポイントのサービスの統計情報を取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-133">Begins an asynchronous operation to get service stats for the secondary Queue service endpoint.</span></span>
            </summary>
        <returns><span data-ttu-id="02a0f-134"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-134">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListQueuesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListQueuesSegmented (Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListQueuesSegmented(class Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.BeginListQueuesSegmented(Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginListQueuesSegmented (currentToken As QueueContinuationToken, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginListQueuesSegmented : Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginListQueuesSegmented : Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueueClient.BeginListQueuesSegmented (currentToken, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="currentToken"><span data-ttu-id="02a0f-135">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" />前の一覧作成操作によって返されます。</span><span class="sxs-lookup"><span data-stu-id="02a0f-135">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" /> returned by a previous listing operation.</span></span></param>
        <param name="callback"><span data-ttu-id="02a0f-136"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="02a0f-136">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="02a0f-137">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-137">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="02a0f-138">キューのコレクションを含む結果セグメントを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-138">Begins an asynchronous operation to return a result segment containing a collection of queues.</span></span>
            </summary>
        <returns><span data-ttu-id="02a0f-139"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-139">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListQueuesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListQueuesSegmented (string prefix, Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListQueuesSegmented(string prefix, class Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.BeginListQueuesSegmented(System.String,Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginListQueuesSegmented (prefix As String, currentToken As QueueContinuationToken, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginListQueuesSegmented : string * Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginListQueuesSegmented : string * Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueueClient.BeginListQueuesSegmented (prefix, currentToken, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="02a0f-140">キュー名のプレフィックスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="02a0f-140">A string containing the queue name prefix.</span></span></param>
        <param name="currentToken"><span data-ttu-id="02a0f-141">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" />前の一覧作成操作によって返されます。</span><span class="sxs-lookup"><span data-stu-id="02a0f-141">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" /> returned by a previous listing operation.</span></span></param>
        <param name="callback"><span data-ttu-id="02a0f-142"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="02a0f-142">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="02a0f-143">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-143">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="02a0f-144">キューのコレクションを含む結果セグメントを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-144">Begins an asynchronous operation to return a result segment containing a collection of queues.</span></span>
            </summary>
        <returns><span data-ttu-id="02a0f-145"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-145">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListQueuesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListQueuesSegmented (string prefix, Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails queueListingDetails, Nullable&lt;int&gt; maxResults, Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListQueuesSegmented(string prefix, valuetype Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails queueListingDetails, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.BeginListQueuesSegmented(System.String,Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginListQueuesSegmented : string * Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginListQueuesSegmented : string * Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueueClient.BeginListQueuesSegmented (prefix, queueListingDetails, maxResults, currentToken, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="queueListingDetails" Type="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="02a0f-146">キュー名のプレフィックスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="02a0f-146">A string containing the queue name prefix.</span></span></param>
        <param name="queueListingDetails"><span data-ttu-id="02a0f-147">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" />一覧に含める項目を記述する列挙です。</span><span class="sxs-lookup"><span data-stu-id="02a0f-147">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" /> enumeration describing which items to include in the listing.</span></span></param>
        <param name="maxResults"><span data-ttu-id="02a0f-148">5000 の操作あたりの上限に達するまで、一度に返される結果の最大数を示す正の整数値。</span><span class="sxs-lookup"><span data-stu-id="02a0f-148">A non-negative integer value that indicates the maximum number of results to be returned at a time, up to the per-operation limit of 5000.</span></span> <span data-ttu-id="02a0f-149">この値が場合<c>null</c>結果の最大数が返されます、最大 5000 です。</span><span class="sxs-lookup"><span data-stu-id="02a0f-149">If this value is <c>null</c>, the maximum possible number of results will be returned, up to 5000.</span></span></param>
        <param name="currentToken"><span data-ttu-id="02a0f-150">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" />前の一覧作成操作によって返されます。</span><span class="sxs-lookup"><span data-stu-id="02a0f-150">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" /> returned by a previous listing operation.</span></span></param>
        <param name="options"><span data-ttu-id="02a0f-151">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-151">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="02a0f-152"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-152">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="02a0f-153"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="02a0f-153">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="02a0f-154">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-154">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="02a0f-155">キューのコレクションを含む結果セグメントを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-155">Begins an asynchronous operation to return a result segment containing a collection of queues.</span></span>
            </summary>
        <returns><span data-ttu-id="02a0f-156"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-156">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetServiceProperties (Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetServiceProperties(class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.BeginSetServiceProperties(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginSetServiceProperties (properties As ServiceProperties, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginSetServiceProperties : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetServiceProperties : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueueClient.BeginSetServiceProperties (properties, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <param name="properties"><span data-ttu-id="02a0f-157"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-157">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> object.</span></span></param>
        <param name="callback"><span data-ttu-id="02a0f-158"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="02a0f-158">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="02a0f-159">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-159">A user-defined object to be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="02a0f-160">キュー サービスのサービス プロパティを設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-160">Begins an asynchronous operation to set service properties for the Queue service.</span></span>
            </summary>
        <returns><span data-ttu-id="02a0f-161"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-161">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetServiceProperties (Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetServiceProperties(class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.BeginSetServiceProperties(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginSetServiceProperties : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetServiceProperties : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueueClient.BeginSetServiceProperties (properties, requestOptions, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="02a0f-162"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-162">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> object.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="02a0f-163">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-163">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="02a0f-164"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-164">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="02a0f-165"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="02a0f-165">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="02a0f-166">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-166">A user-defined object to be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="02a0f-167">キュー サービスのサービス プロパティを設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-167">Begins an asynchronous operation to set service properties for the Queue service.</span></span>
            </summary>
        <returns><span data-ttu-id="02a0f-168"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-168">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BufferManager">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.IBufferManager BufferManager { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.IBufferManager BufferManager" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.BufferManager" />
      <MemberSignature Language="VB.NET" Value="Public Property BufferManager As IBufferManager" />
      <MemberSignature Language="F#" Value="member this.BufferManager : Microsoft.WindowsAzure.Storage.IBufferManager with get, set" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.BufferManager" />
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
            <span data-ttu-id="02a0f-169">取得または設定を実装するバッファー マネージャー、<see cref="T:Microsoft.WindowsAzure.Storage.IBufferManager" />インターフェイス、Queue サービス クライアントに対する操作で使用されるバッファー プールを指定します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-169">Gets or sets a buffer manager that implements the <see cref="T:Microsoft.WindowsAzure.Storage.IBufferManager" /> interface, specifying a buffer pool for use with operations against the Queue service client.</span></span>
            </summary>
        <value><span data-ttu-id="02a0f-170"><see cref="T:Microsoft.WindowsAzure.Storage.IBufferManager" /> 型のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-170">An object of type <see cref="T:Microsoft.WindowsAzure.Storage.IBufferManager" />.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Auth.StorageCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As StorageCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.Credentials" />
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
            <span data-ttu-id="02a0f-171">Queue サービス クライアントを作成するために使用するアカウントの資格情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-171">Gets the account credentials used to create the Queue service client.</span></span>
            </summary>
        <value><span data-ttu-id="02a0f-172"><see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-172">A <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultRequestOptions">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions DefaultRequestOptions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions DefaultRequestOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.DefaultRequestOptions" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultRequestOptions As QueueRequestOptions" />
      <MemberSignature Language="F#" Value="member this.DefaultRequestOptions : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions with get, set" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.DefaultRequestOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="02a0f-173">取得し、キュー サービス クライアントを介して行われる要求の要求オプションを既定値に設定します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-173">Gets and sets the default request options for requests made via the Queue service client.</span></span>
            </summary>
        <value><span data-ttu-id="02a0f-174"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-174">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndGetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties EndGetServiceProperties (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties EndGetServiceProperties(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.EndGetServiceProperties(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndGetServiceProperties (asyncResult As IAsyncResult) As ServiceProperties" />
      <MemberSignature Language="F#" Value="abstract member EndGetServiceProperties : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&#xA;override this.EndGetServiceProperties : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" Usage="cloudQueueClient.EndGetServiceProperties asyncResult" />
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
        <param name="asyncResult"><span data-ttu-id="02a0f-175">前回の呼び出しから返された結果<see cref="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.BeginGetServiceProperties(System.AsyncCallback,System.Object)" />です。</span><span class="sxs-lookup"><span data-stu-id="02a0f-175">The result returned from a prior call to <see cref="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.BeginGetServiceProperties(System.AsyncCallback,System.Object)" />.</span></span></param>
        <summary>
            <span data-ttu-id="02a0f-176">キュー サービスのサービス プロパティを取得する非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-176">Ends an asynchronous operation to get service properties for the Queue service.</span></span>
            </summary>
        <returns><span data-ttu-id="02a0f-177"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-177">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndGetServiceStats">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats EndGetServiceStats (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats EndGetServiceStats(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.EndGetServiceStats(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndGetServiceStats (asyncResult As IAsyncResult) As ServiceStats" />
      <MemberSignature Language="F#" Value="abstract member EndGetServiceStats : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&#xA;override this.EndGetServiceStats : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" Usage="cloudQueueClient.EndGetServiceStats asyncResult" />
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
        <param name="asyncResult"><span data-ttu-id="02a0f-178"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-178">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="02a0f-179">セカンダリ Queue サービス エンドポイントのサービスの統計情報を取得する非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-179">Ends an asynchronous operation to get service stats for the secondary Queue service endpoint.</span></span>
            </summary>
        <returns><span data-ttu-id="02a0f-180"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-180">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndListQueuesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment EndListQueuesSegmented (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment EndListQueuesSegmented(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.EndListQueuesSegmented(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndListQueuesSegmented (asyncResult As IAsyncResult) As QueueResultSegment" />
      <MemberSignature Language="F#" Value="abstract member EndListQueuesSegmented : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&#xA;override this.EndListQueuesSegmented : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" Usage="cloudQueueClient.EndListQueuesSegmented asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="02a0f-181"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-181">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="02a0f-182">キューのコレクションを含む結果セグメントを返す非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-182">Ends an asynchronous operation to return a result segment containing a collection of queues.</span></span>
            </summary>
        <returns><span data-ttu-id="02a0f-183"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-183">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndSetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual void EndSetServiceProperties (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndSetServiceProperties(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.EndSetServiceProperties(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndSetServiceProperties (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndSetServiceProperties : IAsyncResult -&gt; unit&#xA;override this.EndSetServiceProperties : IAsyncResult -&gt; unit" Usage="cloudQueueClient.EndSetServiceProperties asyncResult" />
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
        <param name="asyncResult"><span data-ttu-id="02a0f-184"><see cref="T:System.IAsyncResult" />前回の呼び出しから返された<see cref="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.BeginSetServiceProperties(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties,System.AsyncCallback,System.Object)" />です。</span><span class="sxs-lookup"><span data-stu-id="02a0f-184">The <see cref="T:System.IAsyncResult" /> returned from a prior call to <see cref="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.BeginSetServiceProperties(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties,System.AsyncCallback,System.Object)" />.</span></span></param>
        <summary>
            <span data-ttu-id="02a0f-185">キュー サービスのサービス プロパティを設定する非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-185">Ends an asynchronous operation to set service properties for the Queue service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetQueueReference">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Queue.CloudQueue GetQueueReference (string queueName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Queue.CloudQueue GetQueueReference(string queueName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.GetQueueReference(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetQueueReference (queueName As String) As CloudQueue" />
      <MemberSignature Language="F#" Value="abstract member GetQueueReference : string -&gt; Microsoft.WindowsAzure.Storage.Queue.CloudQueue&#xA;override this.GetQueueReference : string -&gt; Microsoft.WindowsAzure.Storage.Queue.CloudQueue" Usage="cloudQueueClient.GetQueueReference queueName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Queue.CloudQueue</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queueName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="queueName"><span data-ttu-id="02a0f-186">キューの名前を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="02a0f-186">A string containing the name of the queue.</span></span></param>
        <summary>
            <span data-ttu-id="02a0f-187">参照を返します、<see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueue" />指定の名前を持つオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-187">Returns a reference to a <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueue" /> object with the specified name.</span></span>
            </summary>
        <returns><span data-ttu-id="02a0f-188"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueue" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-188">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueue" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties GetServiceProperties (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties GetServiceProperties(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.GetServiceProperties(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceProperties : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&#xA;override this.GetServiceProperties : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" Usage="cloudQueueClient.GetServiceProperties (requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="02a0f-189">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-189">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="02a0f-190"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-190">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="02a0f-191">キュー サービスのサービスのプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-191">Gets service properties for the Queue service.</span></span>
            </summary>
        <returns><span data-ttu-id="02a0f-192">A<see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />キュー サービス プロパティを含むです。</span><span class="sxs-lookup"><span data-stu-id="02a0f-192">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> containing the Queue service properties.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.GetServicePropertiesAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetServicePropertiesAsync () As Task(Of ServiceProperties)" />
      <MemberSignature Language="F#" Value="abstract member GetServicePropertiesAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;&#xA;override this.GetServicePropertiesAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;" Usage="cloudQueueClient.GetServicePropertiesAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
            <span data-ttu-id="02a0f-193">キュー サービスのサービス プロパティを取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-193">Initiates an asynchronous operation to get service properties for the Queue service.</span></span>
            </summary>
        <returns><span data-ttu-id="02a0f-194">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="02a0f-194">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.GetServicePropertiesAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetServicePropertiesAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;&#xA;override this.GetServicePropertiesAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;" Usage="cloudQueueClient.GetServicePropertiesAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <param name="cancellationToken"><span data-ttu-id="02a0f-195">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="02a0f-195">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="02a0f-196">キュー サービスのサービス プロパティを取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-196">Initiates an asynchronous operation to get service properties for the Queue service.</span></span>
            </summary>
        <returns><span data-ttu-id="02a0f-197">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="02a0f-197">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.GetServicePropertiesAsync(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;&#xA;override this.GetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;" Usage="cloudQueueClient.GetServicePropertiesAsync (requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="02a0f-198">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-198">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="02a0f-199"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-199">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="02a0f-200">キュー サービスのサービス プロパティを取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-200">Initiates an asynchronous operation to get service properties for the Queue service.</span></span>
            </summary>
        <returns><span data-ttu-id="02a0f-201">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="02a0f-201">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.GetServicePropertiesAsync(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;&#xA;override this.GetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;" Usage="cloudQueueClient.GetServicePropertiesAsync (requestOptions, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="02a0f-202">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-202">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="02a0f-203"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-203">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="02a0f-204">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="02a0f-204">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="02a0f-205">キュー サービスのサービス プロパティを取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-205">Initiates an asynchronous operation to get service properties for the Queue service.</span></span>
            </summary>
        <returns><span data-ttu-id="02a0f-206">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="02a0f-206">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceStats">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats GetServiceStats (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats GetServiceStats(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.GetServiceStats(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceStats : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&#xA;override this.GetServiceStats : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" Usage="cloudQueueClient.GetServiceStats (requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="02a0f-207">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-207">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="02a0f-208"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-208">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="02a0f-209">セカンダリ Queue サービス エンドポイントのサービスの統計情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-209">Gets service stats for the secondary Queue service endpoint.</span></span>
            </summary>
        <returns><span data-ttu-id="02a0f-210"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-210">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceStatsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.GetServiceStatsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetServiceStatsAsync () As Task(Of ServiceStats)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceStatsAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;&#xA;override this.GetServiceStatsAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;" Usage="cloudQueueClient.GetServiceStatsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
            <span data-ttu-id="02a0f-211">セカンダリ Queue サービス エンドポイントのサービスの統計情報を取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-211">Initiates an asynchronous operation to get service stats for the secondary Queue service endpoint.</span></span>
            </summary>
        <returns><span data-ttu-id="02a0f-212">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="02a0f-212">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceStatsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.GetServiceStatsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceStatsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;&#xA;override this.GetServiceStatsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;" Usage="cloudQueueClient.GetServiceStatsAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <param name="cancellationToken"><span data-ttu-id="02a0f-213">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="02a0f-213">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="02a0f-214">セカンダリ Queue サービス エンドポイントのサービスの統計情報を取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-214">Initiates an asynchronous operation to get service stats for the secondary Queue service endpoint.</span></span>
            </summary>
        <returns><span data-ttu-id="02a0f-215">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="02a0f-215">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceStatsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.GetServiceStatsAsync(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceStatsAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;&#xA;override this.GetServiceStatsAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;" Usage="cloudQueueClient.GetServiceStatsAsync (requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="02a0f-216">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-216">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="02a0f-217"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-217">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="02a0f-218">セカンダリ Queue サービス エンドポイントのサービスの統計情報を取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-218">Initiates an asynchronous operation to get service stats for the secondary Queue service endpoint.</span></span>
            </summary>
        <returns><span data-ttu-id="02a0f-219">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="02a0f-219">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceStatsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.GetServiceStatsAsync(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceStatsAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;&#xA;override this.GetServiceStatsAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;" Usage="cloudQueueClient.GetServiceStatsAsync (requestOptions, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="02a0f-220">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-220">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="02a0f-221"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-221">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="02a0f-222">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="02a0f-222">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="02a0f-223">セカンダリ Queue サービス エンドポイントのサービスの統計情報を取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-223">Initiates an asynchronous operation to get service stats for the secondary Queue service endpoint.</span></span>
            </summary>
        <returns><span data-ttu-id="02a0f-224">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="02a0f-224">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListQueues">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueue&gt; ListQueues (string prefix = null, Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails queueListingDetails = Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails.None, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Queue.CloudQueue&gt; ListQueues(string prefix, valuetype Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails queueListingDetails, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.ListQueues(System.String,Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ListQueues : string * Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueue&gt;&#xA;override this.ListQueues : string * Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueue&gt;" Usage="cloudQueueClient.ListQueues (prefix, queueListingDetails, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueue&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="queueListingDetails" Type="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="02a0f-225">キュー名のプレフィックスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="02a0f-225">A string containing the queue name prefix.</span></span></param>
        <param name="queueListingDetails"><span data-ttu-id="02a0f-226">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" />を一覧に含める詳細を示す列挙値。</span><span class="sxs-lookup"><span data-stu-id="02a0f-226">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" /> enumeration value that indicates which details to include in the listing.</span></span></param>
        <param name="options"><span data-ttu-id="02a0f-227">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-227">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="02a0f-228">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="02a0f-228">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="02a0f-229"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-229">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="02a0f-230">指定したプレフィックスで名前が始まるし、遅延を取得するストレージ アカウント内のキューの列挙可能なコレクションを返します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-230">Returns an enumerable collection of the queues in the storage account whose names begin with the specified prefix and that are retrieved lazily.</span></span>
            </summary>
        <returns><span data-ttu-id="02a0f-231">型のオブジェクトの列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueue" />遅れてを取得します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-231">An enumerable collection of objects of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueue" /> that are retrieved lazily.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListQueuesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment ListQueuesSegmented (Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment ListQueuesSegmented(class Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.ListQueuesSegmented(Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ListQueuesSegmented (currentToken As QueueContinuationToken) As QueueResultSegment" />
      <MemberSignature Language="F#" Value="abstract member ListQueuesSegmented : Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken -&gt; Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&#xA;override this.ListQueuesSegmented : Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken -&gt; Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" Usage="cloudQueueClient.ListQueuesSegmented currentToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" />
      </Parameters>
      <Docs>
        <param name="currentToken"><span data-ttu-id="02a0f-232">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" />前の一覧作成操作によって返された継続トークンです。</span><span class="sxs-lookup"><span data-stu-id="02a0f-232">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" /> continuation token returned by a previous listing operation.</span></span></param>
        <summary>
            <span data-ttu-id="02a0f-233">キューのコレクションを含む結果セグメントを返します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-233">Returns a result segment containing a collection of queues.</span></span>
            </summary>
        <returns><span data-ttu-id="02a0f-234"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-234">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListQueuesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment ListQueuesSegmented (string prefix, Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment ListQueuesSegmented(string prefix, class Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.ListQueuesSegmented(System.String,Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ListQueuesSegmented (prefix As String, currentToken As QueueContinuationToken) As QueueResultSegment" />
      <MemberSignature Language="F#" Value="abstract member ListQueuesSegmented : string * Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken -&gt; Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&#xA;override this.ListQueuesSegmented : string * Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken -&gt; Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" Usage="cloudQueueClient.ListQueuesSegmented (prefix, currentToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="02a0f-235">キュー名のプレフィックスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="02a0f-235">A string containing the queue name prefix.</span></span></param>
        <param name="currentToken"><span data-ttu-id="02a0f-236">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" />前の一覧作成操作によって返された継続トークンです。</span><span class="sxs-lookup"><span data-stu-id="02a0f-236">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" /> continuation token returned by a previous listing operation.</span></span></param>
        <summary>
            <span data-ttu-id="02a0f-237">キューのコレクションを含む結果セグメントを返します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-237">Returns a result segment containing a collection of queues.</span></span>
            </summary>
        <returns><span data-ttu-id="02a0f-238"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-238">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListQueuesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment ListQueuesSegmented (string prefix, Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails queueListingDetails, Nullable&lt;int&gt; maxResults, Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment ListQueuesSegmented(string prefix, valuetype Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails queueListingDetails, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.ListQueuesSegmented(System.String,Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ListQueuesSegmented : string * Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&#xA;override this.ListQueuesSegmented : string * Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" Usage="cloudQueueClient.ListQueuesSegmented (prefix, queueListingDetails, maxResults, currentToken, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="queueListingDetails" Type="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="02a0f-239">キュー名のプレフィックスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="02a0f-239">A string containing the queue name prefix.</span></span></param>
        <param name="queueListingDetails"><span data-ttu-id="02a0f-240">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" />一覧に含める項目を記述する列挙です。</span><span class="sxs-lookup"><span data-stu-id="02a0f-240">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" /> enumeration describing which items to include in the listing.</span></span></param>
        <param name="maxResults"><span data-ttu-id="02a0f-241">5000 の操作あたりの上限に達するまで、一度に返される結果の最大数を示す正の整数値。</span><span class="sxs-lookup"><span data-stu-id="02a0f-241">A non-negative integer value that indicates the maximum number of results to be returned at a time, up to the per-operation limit of 5000.</span></span> <span data-ttu-id="02a0f-242">この値が場合<c>null</c>結果の最大数が返されます、最大 5000 です。</span><span class="sxs-lookup"><span data-stu-id="02a0f-242">If this value is <c>null</c>, the maximum possible number of results will be returned, up to 5000.</span></span></param>
        <param name="currentToken"><span data-ttu-id="02a0f-243">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" />前の一覧作成操作によって返されます。</span><span class="sxs-lookup"><span data-stu-id="02a0f-243">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" /> returned by a previous listing operation.</span></span></param>
        <param name="options"><span data-ttu-id="02a0f-244">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-244">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="02a0f-245">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="02a0f-245">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="02a0f-246"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-246">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="02a0f-247">キューのコレクションを含む結果セグメントを返します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-247">Returns a result segment containing a collection of queues.</span></span>
            </summary>
        <returns><span data-ttu-id="02a0f-248"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-248">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListQueuesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt; ListQueuesSegmentedAsync (Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt; ListQueuesSegmentedAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.ListQueuesSegmentedAsync(Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ListQueuesSegmentedAsync (currentToken As QueueContinuationToken) As Task(Of QueueResultSegment)" />
      <MemberSignature Language="F#" Value="abstract member ListQueuesSegmentedAsync : Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;&#xA;override this.ListQueuesSegmentedAsync : Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;" Usage="cloudQueueClient.ListQueuesSegmentedAsync currentToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" />
      </Parameters>
      <Docs>
        <param name="currentToken"><span data-ttu-id="02a0f-249">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" />前の一覧作成操作によって返されます。</span><span class="sxs-lookup"><span data-stu-id="02a0f-249">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" /> returned by a previous listing operation.</span></span></param>
        <summary>
            <span data-ttu-id="02a0f-250">キューのコレクションを含む結果セグメントを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-250">Initiates an asynchronous operation to return a result segment containing a collection of queues.</span></span>
            </summary>
        <returns><span data-ttu-id="02a0f-251">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="02a0f-251">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListQueuesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt; ListQueuesSegmentedAsync (Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt; ListQueuesSegmentedAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.ListQueuesSegmentedAsync(Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListQueuesSegmentedAsync : Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;&#xA;override this.ListQueuesSegmentedAsync : Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;" Usage="cloudQueueClient.ListQueuesSegmentedAsync (currentToken, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="currentToken"><span data-ttu-id="02a0f-252">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" />前の一覧作成操作によって返されます。</span><span class="sxs-lookup"><span data-stu-id="02a0f-252">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" /> returned by a previous listing operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="02a0f-253">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="02a0f-253">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="02a0f-254">キューのコレクションを含む結果セグメントを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-254">Initiates an asynchronous operation to return a result segment containing a collection of queues.</span></span>
            </summary>
        <returns><span data-ttu-id="02a0f-255">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="02a0f-255">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListQueuesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt; ListQueuesSegmentedAsync (string prefix, Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt; ListQueuesSegmentedAsync(string prefix, class Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.ListQueuesSegmentedAsync(System.String,Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ListQueuesSegmentedAsync (prefix As String, currentToken As QueueContinuationToken) As Task(Of QueueResultSegment)" />
      <MemberSignature Language="F#" Value="abstract member ListQueuesSegmentedAsync : string * Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;&#xA;override this.ListQueuesSegmentedAsync : string * Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;" Usage="cloudQueueClient.ListQueuesSegmentedAsync (prefix, currentToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="02a0f-256">キュー名のプレフィックスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="02a0f-256">A string containing the queue name prefix.</span></span></param>
        <param name="currentToken"><span data-ttu-id="02a0f-257">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" />前の一覧作成操作によって返されます。</span><span class="sxs-lookup"><span data-stu-id="02a0f-257">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" /> returned by a previous listing operation.</span></span></param>
        <summary>
            <span data-ttu-id="02a0f-258">キューのコレクションを含む結果セグメントを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-258">Initiates an asynchronous operation to return a result segment containing a collection of queues.</span></span>
            </summary>
        <returns><span data-ttu-id="02a0f-259">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="02a0f-259">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListQueuesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt; ListQueuesSegmentedAsync (string prefix, Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt; ListQueuesSegmentedAsync(string prefix, class Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.ListQueuesSegmentedAsync(System.String,Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListQueuesSegmentedAsync : string * Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;&#xA;override this.ListQueuesSegmentedAsync : string * Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;" Usage="cloudQueueClient.ListQueuesSegmentedAsync (prefix, currentToken, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="02a0f-260">キュー名のプレフィックスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="02a0f-260">A string containing the queue name prefix.</span></span></param>
        <param name="currentToken"><span data-ttu-id="02a0f-261">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" />前の一覧作成操作によって返されます。</span><span class="sxs-lookup"><span data-stu-id="02a0f-261">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" /> returned by a previous listing operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="02a0f-262">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="02a0f-262">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="02a0f-263">キューのコレクションを含む結果セグメントを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-263">Initiates an asynchronous operation to return a result segment containing a collection of queues.</span></span>
            </summary>
        <returns><span data-ttu-id="02a0f-264">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="02a0f-264">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListQueuesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt; ListQueuesSegmentedAsync (string prefix, Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails queueListingDetails, Nullable&lt;int&gt; maxResults, Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt; ListQueuesSegmentedAsync(string prefix, valuetype Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails queueListingDetails, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.ListQueuesSegmentedAsync(System.String,Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ListQueuesSegmentedAsync : string * Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;&#xA;override this.ListQueuesSegmentedAsync : string * Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;" Usage="cloudQueueClient.ListQueuesSegmentedAsync (prefix, queueListingDetails, maxResults, currentToken, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="queueListingDetails" Type="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="02a0f-265">キュー名のプレフィックスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="02a0f-265">A string containing the queue name prefix.</span></span></param>
        <param name="queueListingDetails"><span data-ttu-id="02a0f-266">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" />一覧に含める項目を記述する列挙です。</span><span class="sxs-lookup"><span data-stu-id="02a0f-266">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" /> enumeration describing which items to include in the listing.</span></span></param>
        <param name="maxResults"><span data-ttu-id="02a0f-267">5000 の操作あたりの上限に達するまで、一度に返される結果の最大数を示す正の整数値。</span><span class="sxs-lookup"><span data-stu-id="02a0f-267">A non-negative integer value that indicates the maximum number of results to be returned at a time, up to the per-operation limit of 5000.</span></span> <span data-ttu-id="02a0f-268">この値が場合<c>null</c>結果の最大数が返されます、最大 5000 です。</span><span class="sxs-lookup"><span data-stu-id="02a0f-268">If this value is <c>null</c>, the maximum possible number of results will be returned, up to 5000.</span></span></param>
        <param name="currentToken"><span data-ttu-id="02a0f-269">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" />前の一覧作成操作によって返されます。</span><span class="sxs-lookup"><span data-stu-id="02a0f-269">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" /> returned by a previous listing operation.</span></span></param>
        <param name="options"><span data-ttu-id="02a0f-270">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-270">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="02a0f-271"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-271">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="02a0f-272">キューのコレクションを含む結果セグメントを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-272">Initiates an asynchronous operation to return a result segment containing a collection of queues.</span></span>
            </summary>
        <returns><span data-ttu-id="02a0f-273">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="02a0f-273">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListQueuesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt; ListQueuesSegmentedAsync (string prefix, Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails queueListingDetails, Nullable&lt;int&gt; maxResults, Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt; ListQueuesSegmentedAsync(string prefix, valuetype Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails queueListingDetails, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.ListQueuesSegmentedAsync(System.String,Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListQueuesSegmentedAsync : string * Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;&#xA;override this.ListQueuesSegmentedAsync : string * Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;" Usage="cloudQueueClient.ListQueuesSegmentedAsync (prefix, queueListingDetails, maxResults, currentToken, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="queueListingDetails" Type="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="02a0f-274">キュー名のプレフィックスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="02a0f-274">A string containing the queue name prefix.</span></span></param>
        <param name="queueListingDetails"><span data-ttu-id="02a0f-275">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" />一覧に含める項目を記述する列挙です。</span><span class="sxs-lookup"><span data-stu-id="02a0f-275">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" /> enumeration describing which items to include in the listing.</span></span></param>
        <param name="maxResults"><span data-ttu-id="02a0f-276">5000 の操作あたりの上限に達するまで、一度に返される結果の最大数を示す正の整数値。</span><span class="sxs-lookup"><span data-stu-id="02a0f-276">A non-negative integer value that indicates the maximum number of results to be returned at a time, up to the per-operation limit of 5000.</span></span> <span data-ttu-id="02a0f-277">この値が null の場合、最大数の結果が返されます、最大 5000 です。</span><span class="sxs-lookup"><span data-stu-id="02a0f-277">If this value is null, the maximum possible number of results will be returned, up to 5000.</span></span></param>
        <param name="currentToken"><span data-ttu-id="02a0f-278">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" />前の一覧作成操作によって返されます。</span><span class="sxs-lookup"><span data-stu-id="02a0f-278">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" /> returned by a previous listing operation.</span></span></param>
        <param name="options"><span data-ttu-id="02a0f-279">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-279">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="02a0f-280"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-280">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="02a0f-281">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="02a0f-281">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="02a0f-282">キューのコレクションを含む結果セグメントを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-282">Initiates an asynchronous operation to return a result segment containing a collection of queues.</span></span>
            </summary>
        <returns><span data-ttu-id="02a0f-283">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="02a0f-283">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual void SetServiceProperties (Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SetServiceProperties(class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.SetServiceProperties(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetServiceProperties : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.SetServiceProperties : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudQueueClient.SetServiceProperties (properties, requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="02a0f-284"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-284">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> object.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="02a0f-285">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-285">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="02a0f-286"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-286">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="02a0f-287">サービスのキュー サービスのプロパティのセット。</span><span class="sxs-lookup"><span data-stu-id="02a0f-287">Sets service properties for the Queue service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetServicePropertiesAsync (Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetServicePropertiesAsync(class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.SetServicePropertiesAsync(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function SetServicePropertiesAsync (properties As ServiceProperties) As Task" />
      <MemberSignature Language="F#" Value="abstract member SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties -&gt; System.Threading.Tasks.Task&#xA;override this.SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties -&gt; System.Threading.Tasks.Task" Usage="cloudQueueClient.SetServicePropertiesAsync properties" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <param name="properties"><span data-ttu-id="02a0f-288"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-288">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="02a0f-289">キュー サービスのサービス プロパティを設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-289">Initiates an asynchronous operation to set service properties for the Queue service.</span></span>
            </summary>
        <returns><span data-ttu-id="02a0f-290">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-290">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetServicePropertiesAsync (Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetServicePropertiesAsync(class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.SetServicePropertiesAsync(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudQueueClient.SetServicePropertiesAsync (properties, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <param name="properties"><span data-ttu-id="02a0f-291"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-291">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> object.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="02a0f-292">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="02a0f-292">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="02a0f-293">キュー サービスのサービス プロパティを設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-293">Initiates an asynchronous operation to set service properties for the Queue service.</span></span>
            </summary>
        <returns><span data-ttu-id="02a0f-294">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-294">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetServicePropertiesAsync (Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetServicePropertiesAsync(class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.SetServicePropertiesAsync(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudQueueClient.SetServicePropertiesAsync (properties, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="02a0f-295"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-295">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> object.</span></span></param>
        <param name="options"><span data-ttu-id="02a0f-296">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-296">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="02a0f-297"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-297">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="02a0f-298">キュー サービスのサービス プロパティを設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-298">Initiates an asynchronous operation to set service properties for the Queue service.</span></span>
            </summary>
        <returns><span data-ttu-id="02a0f-299">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-299">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetServicePropertiesAsync (Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetServicePropertiesAsync(class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.SetServicePropertiesAsync(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudQueueClient.SetServicePropertiesAsync (properties, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="02a0f-300"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-300">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> object.</span></span></param>
        <param name="options"><span data-ttu-id="02a0f-301">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-301">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="02a0f-302"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-302">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="02a0f-303">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="02a0f-303">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="02a0f-304">キュー サービスのサービス プロパティを設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-304">Initiates an asynchronous operation to set service properties for the Queue service.</span></span>
            </summary>
        <returns><span data-ttu-id="02a0f-305">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="02a0f-305">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageUri">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.StorageUri StorageUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.StorageUri StorageUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.StorageUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StorageUri As StorageUri" />
      <MemberSignature Language="F#" Value="member this.StorageUri : Microsoft.WindowsAzure.Storage.StorageUri" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.StorageUri" />
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
            <span data-ttu-id="02a0f-306">プライマリとセカンダリの両方の場所の Queue サービスのエンドポイントを取得します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-306">Gets the Queue service endpoints for both the primary and secondary locations.</span></span>
            </summary>
        <value><span data-ttu-id="02a0f-307">型のオブジェクト<see cref="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.StorageUri" />プライマリとセカンダリの両方の場所の Uri をサービス キューを格納します。</span><span class="sxs-lookup"><span data-stu-id="02a0f-307">An object of type <see cref="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.StorageUri" /> containing Queue service URIs for both the primary and secondary locations.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>