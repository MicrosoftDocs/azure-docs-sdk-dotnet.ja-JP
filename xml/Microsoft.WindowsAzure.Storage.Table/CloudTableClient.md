<Type Name="CloudTableClient" FullName="Microsoft.WindowsAzure.Storage.Table.CloudTableClient">
  <TypeSignature Language="C#" Value="public class CloudTableClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CloudTableClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Table.CloudTableClient" />
  <TypeSignature Language="VB.NET" Value="Public Class CloudTableClient" />
  <TypeSignature Language="F#" Value="type CloudTableClient = class" />
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
            <span data-ttu-id="098b0-101">Microsoft Azure Table サービスのクライアント側の論理表現を提供します。</span><span class="sxs-lookup"><span data-stu-id="098b0-101">Provides a client-side logical representation of the Microsoft Azure Table Service.</span></span> <span data-ttu-id="098b0-102">このクライアントを使用してを構成およびテーブル サービスに対する要求を実行します。</span><span class="sxs-lookup"><span data-stu-id="098b0-102">This client is used to configure and execute requests against the Table Service.</span></span>
            </summary>
    <remarks><span data-ttu-id="098b0-103">サービス クライアントは、エンドポイントまたはテーブル サービスのエンドポイントをカプセル化します。</span><span class="sxs-lookup"><span data-stu-id="098b0-103">The service client encapsulates the endpoint or endpoints for the Table service.</span></span> <span data-ttu-id="098b0-104">サービス クライアントを認証済みアクセスに使用する場合、ストレージ アカウントにアクセスするための資格情報もカプセル化します。</span><span class="sxs-lookup"><span data-stu-id="098b0-104">If the service client will be used for authenticated access, it also encapsulates the credentials for accessing the storage account.</span></span></remarks>
    <remarks><span data-ttu-id="098b0-105">CloudTableClient オブジェクトは、テーブル サービスのベース URI をカプセル化します。</span><span class="sxs-lookup"><span data-stu-id="098b0-105">The CloudTableClient object encapsulates the base URI for the Table service.</span></span> <span data-ttu-id="098b0-106">サービス クライアントを認証済みアクセスに使用する場合、ストレージ アカウントにアクセスするための資格情報もカプセル化します。</span><span class="sxs-lookup"><span data-stu-id="098b0-106">If the service client will be used for authenticated access, it also encapsulates the credentials for accessing the storage account.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudTableClient (Microsoft.WindowsAzure.Storage.StorageUri storageUri, Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.StorageUri storageUri, class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.#ctor(Microsoft.WindowsAzure.Storage.StorageUri,Microsoft.WindowsAzure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Table.CloudTableClient : Microsoft.WindowsAzure.Storage.StorageUri * Microsoft.WindowsAzure.Storage.Auth.StorageCredentials -&gt; Microsoft.WindowsAzure.Storage.Table.CloudTableClient" Usage="new Microsoft.WindowsAzure.Storage.Table.CloudTableClient (storageUri, credentials)" />
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
        <param name="storageUri"><span data-ttu-id="098b0-107">A<see cref="P:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.StorageUri" />を使用してクライアントを作成するテーブル サービスのエンドポイントを含むオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-107">A <see cref="P:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.StorageUri" /> object containing the Table service endpoint to use to create the client.</span></span></param>
        <param name="credentials"><span data-ttu-id="098b0-108"><see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-108">A <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="098b0-109">新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTableClient" />クラス、指定されたテーブル サービス エンドポイントとアカウントの資格情報を使用します。</span><span class="sxs-lookup"><span data-stu-id="098b0-109">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTableClient" /> class using the specified Table service endpoint and account credentials.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudTableClient (Uri baseUri, Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.#ctor(System.Uri,Microsoft.WindowsAzure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (baseUri As Uri, credentials As StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Table.CloudTableClient : Uri * Microsoft.WindowsAzure.Storage.Auth.StorageCredentials -&gt; Microsoft.WindowsAzure.Storage.Table.CloudTableClient" Usage="new Microsoft.WindowsAzure.Storage.Table.CloudTableClient (baseUri, credentials)" />
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
        <param name="baseUri"><span data-ttu-id="098b0-110">A<see cref="T:System.Uri" />を使用してクライアントを作成するテーブル サービスのエンドポイントを含むオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-110">A <see cref="T:System.Uri" /> object containing the Table service endpoint to use to create the client.</span></span></param>
        <param name="credentials"><span data-ttu-id="098b0-111"><see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-111">A <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="098b0-112">新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTableClient" />クラス、指定されたテーブル サービス エンドポイントとアカウントの資格情報を使用します。</span><span class="sxs-lookup"><span data-stu-id="098b0-112">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTableClient" /> class using the specified Table service endpoint and account credentials.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationScheme">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.AuthenticationScheme AuthenticationScheme { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.AuthenticationScheme AuthenticationScheme" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.AuthenticationScheme" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationScheme As AuthenticationScheme" />
      <MemberSignature Language="F#" Value="member this.AuthenticationScheme : Microsoft.WindowsAzure.Storage.AuthenticationScheme with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.CloudTableClient.AuthenticationScheme" />
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
            <span data-ttu-id="098b0-113">取得または HTTP 要求の署名に使用する認証スキームを設定します。</span><span class="sxs-lookup"><span data-stu-id="098b0-113">Gets or sets the authentication scheme to use to sign HTTP requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para><span data-ttu-id="098b0-114">共有キーまたは共有キー Lite の資格情報が使用される場合にのみ、このプロパティを設定します。共有アクセス署名または匿名アクセス経由での認証には適用されません。</span><span class="sxs-lookup"><span data-stu-id="098b0-114">This property is set only when Shared Key or Shared Key Lite credentials are used; it does not apply to authentication via a shared access signature or anonymous access.</span></span></para>
          <para><span data-ttu-id="098b0-115">WCF Data Services に基づく、従来のテーブル サービス API を使用している場合で、認証方式が使用に注意してください、<see cref="T:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext" />オブジェクトは常に共有キー Lite、このプロパティの値に関係なく。</span><span class="sxs-lookup"><span data-stu-id="098b0-115">Note that if you are using the legacy Table service API, which is based on WCF Data Services, the authentication scheme used by the <see cref="T:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext" /> object will always be Shared Key Lite, regardless of the value of this property.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri" Usage="Microsoft.WindowsAzure.Storage.Table.CloudTableClient.BaseUri" />
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
            <span data-ttu-id="098b0-116">プライマリの場所の Table サービス クライアントのベース URI を取得します。</span><span class="sxs-lookup"><span data-stu-id="098b0-116">Gets the base URI for the Table service client at the primary location.</span></span>
            </summary>
        <value><span data-ttu-id="098b0-117">A<see cref="T:System.Uri" />プライマリの場所の Table サービス クライアントを構築するために使用されるベース URI を含むオブジェクトします。</span><span class="sxs-lookup"><span data-stu-id="098b0-117">A <see cref="T:System.Uri" /> object containing the base URI used to construct the Table service client at the primary location.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceProperties (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceProperties(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.BeginGetServiceProperties(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginGetServiceProperties (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginGetServiceProperties : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetServiceProperties : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudTableClient.BeginGetServiceProperties (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <param name="callback"><span data-ttu-id="098b0-118"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="098b0-118">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="098b0-119">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-119">A user-defined object to be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="098b0-120">テーブル サービスのサービス プロパティを取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="098b0-120">Begins an asynchronous operation to get the service properties of the Table service.</span></span>
            </summary>
        <returns><span data-ttu-id="098b0-121"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="098b0-121">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceProperties (Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceProperties(class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.BeginGetServiceProperties(Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginGetServiceProperties : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetServiceProperties : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudTableClient.BeginGetServiceProperties (requestOptions, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="098b0-122">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-122">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="098b0-123"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-123">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="098b0-124"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="098b0-124">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="098b0-125">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-125">A user-defined object to be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="098b0-126">テーブル サービスのサービス プロパティを取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="098b0-126">Begins an asynchronous operation to get the service properties of the Table service.</span></span>
            </summary>
        <returns><span data-ttu-id="098b0-127"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="098b0-127">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetServiceStats">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceStats (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceStats(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.BeginGetServiceStats(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginGetServiceStats (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginGetServiceStats : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetServiceStats : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudTableClient.BeginGetServiceStats (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <param name="callback"><span data-ttu-id="098b0-128"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="098b0-128">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="098b0-129">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-129">A user-defined object to be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="098b0-130">セカンダリ Table サービス エンドポイントのサービスの統計情報を取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="098b0-130">Begins an asynchronous operation to get service stats for the secondary Table service endpoint.</span></span>
            </summary>
        <returns><span data-ttu-id="098b0-131"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="098b0-131">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetServiceStats">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceStats (Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceStats(class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.BeginGetServiceStats(Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginGetServiceStats : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetServiceStats : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudTableClient.BeginGetServiceStats (requestOptions, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="098b0-132">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-132">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="098b0-133"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-133">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="098b0-134"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="098b0-134">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="098b0-135">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-135">A user-defined object to be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="098b0-136">セカンダリ Table サービス エンドポイントのサービスの統計情報を取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="098b0-136">Begins an asynchronous operation to get service stats for the secondary Table service endpoint.</span></span>
            </summary>
        <returns><span data-ttu-id="098b0-137"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="098b0-137">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListTablesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListTablesSegmented (Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListTablesSegmented(class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.BeginListTablesSegmented(Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginListTablesSegmented (currentToken As TableContinuationToken, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginListTablesSegmented : Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginListTablesSegmented : Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudTableClient.BeginListTablesSegmented (currentToken, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="currentToken"><span data-ttu-id="098b0-138">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />前の一覧作成操作によって返されます。</span><span class="sxs-lookup"><span data-stu-id="098b0-138">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" /> returned by a previous listing operation.</span></span></param>
        <param name="callback"><span data-ttu-id="098b0-139"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="098b0-139">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="098b0-140">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-140">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="098b0-141">テーブルの結果セグメントを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="098b0-141">Begins an asynchronous operation to return a result segment of tables.</span></span>
            </summary>
        <returns><span data-ttu-id="098b0-142"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="098b0-142">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListTablesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListTablesSegmented (string prefix, Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListTablesSegmented(string prefix, class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.BeginListTablesSegmented(System.String,Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginListTablesSegmented (prefix As String, currentToken As TableContinuationToken, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginListTablesSegmented : string * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginListTablesSegmented : string * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudTableClient.BeginListTablesSegmented (prefix, currentToken, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="098b0-143">テーブル名のプレフィックスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="098b0-143">A string containing the table name prefix.</span></span></param>
        <param name="currentToken"><span data-ttu-id="098b0-144">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />前の一覧作成操作によって返されます。</span><span class="sxs-lookup"><span data-stu-id="098b0-144">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" /> returned by a previous listing operation.</span></span></param>
        <param name="callback"><span data-ttu-id="098b0-145"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="098b0-145">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="098b0-146">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-146">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="098b0-147">指定したプレフィックスで始まるテーブルの結果セグメントを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="098b0-147">Begins an asynchronous operation to return a result segment of tables that start with the specified prefix.</span></span>
            </summary>
        <returns><span data-ttu-id="098b0-148"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="098b0-148">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListTablesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListTablesSegmented (string prefix, Nullable&lt;int&gt; maxResults, Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListTablesSegmented(string prefix, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.BeginListTablesSegmented(System.String,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginListTablesSegmented : string * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginListTablesSegmented : string * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudTableClient.BeginListTablesSegmented (prefix, maxResults, currentToken, requestOptions, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="098b0-149">テーブル名のプレフィックスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="098b0-149">A string containing the table name prefix.</span></span></param>
        <param name="maxResults"><span data-ttu-id="098b0-150">5000 の操作あたりの上限に達するまで、一度に返される結果の最大数を示す正の整数値。</span><span class="sxs-lookup"><span data-stu-id="098b0-150">A non-negative integer value that indicates the maximum number of results to be returned at a time, up to the per-operation limit of 5000.</span></span> <span data-ttu-id="098b0-151">この値が場合<c>null</c>結果の最大数が返されます、最大 5000 です。</span><span class="sxs-lookup"><span data-stu-id="098b0-151">If this value is <c>null</c>, the maximum possible number of results will be returned, up to 5000.</span></span></param>
        <param name="currentToken"><span data-ttu-id="098b0-152">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />前の一覧作成操作によって返されます。</span><span class="sxs-lookup"><span data-stu-id="098b0-152">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" /> returned by a previous listing operation.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="098b0-153">サーバーのタイムアウト、最大実行時間、および操作の再試行ポリシーです。</span><span class="sxs-lookup"><span data-stu-id="098b0-153">The server timeout, maximum execution time, and retry policies for the operation.</span></span></param>
        <param name="operationContext"><span data-ttu-id="098b0-154"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-154">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="098b0-155"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="098b0-155">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="098b0-156">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-156">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="098b0-157">指定したプレフィックスで始まるテーブルの結果セグメントを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="098b0-157">Begins an asynchronous operation to return a result segment of tables that start with the specified prefix.</span></span>
            </summary>
        <returns><span data-ttu-id="098b0-158"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="098b0-158">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetServiceProperties (Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetServiceProperties(class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.BeginSetServiceProperties(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginSetServiceProperties (properties As ServiceProperties, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginSetServiceProperties : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetServiceProperties : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudTableClient.BeginSetServiceProperties (properties, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <param name="properties"><span data-ttu-id="098b0-159"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-159">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> object.</span></span></param>
        <param name="callback"><span data-ttu-id="098b0-160"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="098b0-160">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="098b0-161">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-161">A user-defined object to be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="098b0-162">テーブル サービスのサービス プロパティを設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="098b0-162">Begins an asynchronous operation to set the service properties of the Table service.</span></span>
            </summary>
        <returns><span data-ttu-id="098b0-163"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="098b0-163">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetServiceProperties (Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetServiceProperties(class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.BeginSetServiceProperties(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginSetServiceProperties : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetServiceProperties : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudTableClient.BeginSetServiceProperties (properties, requestOptions, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="098b0-164"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-164">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> object.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="098b0-165">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-165">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="098b0-166"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-166">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="098b0-167"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="098b0-167">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="098b0-168">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-168">A user-defined object to be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="098b0-169">テーブル サービスのサービス プロパティを設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="098b0-169">Begins an asynchronous operation to set the service properties of the Table service.</span></span>
            </summary>
        <returns><span data-ttu-id="098b0-170"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="098b0-170">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BufferManager">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.IBufferManager BufferManager { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.IBufferManager BufferManager" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.BufferManager" />
      <MemberSignature Language="VB.NET" Value="Public Property BufferManager As IBufferManager" />
      <MemberSignature Language="F#" Value="member this.BufferManager : Microsoft.WindowsAzure.Storage.IBufferManager with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.CloudTableClient.BufferManager" />
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
            <span data-ttu-id="098b0-171">取得または設定を実装するバッファー マネージャー、<see cref="T:Microsoft.WindowsAzure.Storage.IBufferManager" />インターフェイス、Table サービス クライアントに対する操作で使用されるバッファー プールを指定します。</span><span class="sxs-lookup"><span data-stu-id="098b0-171">Gets or sets a buffer manager that implements the <see cref="T:Microsoft.WindowsAzure.Storage.IBufferManager" /> interface, specifying a buffer pool for use with operations against the Table service client.</span></span>
            </summary>
        <value><span data-ttu-id="098b0-172"><see cref="T:Microsoft.WindowsAzure.Storage.IBufferManager" /> 型のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-172">An object of type <see cref="T:Microsoft.WindowsAzure.Storage.IBufferManager" />.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Auth.StorageCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As StorageCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" Usage="Microsoft.WindowsAzure.Storage.Table.CloudTableClient.Credentials" />
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
            <span data-ttu-id="098b0-173">Table サービス クライアントを作成するために使用するアカウントの資格情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="098b0-173">Gets the account credentials used to create the Table service client.</span></span>
            </summary>
        <value><span data-ttu-id="098b0-174"><see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-174">A <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultRequestOptions">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.TableRequestOptions DefaultRequestOptions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions DefaultRequestOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.DefaultRequestOptions" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultRequestOptions As TableRequestOptions" />
      <MemberSignature Language="F#" Value="member this.DefaultRequestOptions : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.CloudTableClient.DefaultRequestOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableRequestOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="098b0-175">取得または Table サービス クライアントを介して行われる要求の要求オプションを既定値に設定します。</span><span class="sxs-lookup"><span data-stu-id="098b0-175">Gets or sets the default request options for requests made via the Table service client.</span></span>
            </summary>
        <value><span data-ttu-id="098b0-176"><see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-176">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" /> object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndGetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties EndGetServiceProperties (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties EndGetServiceProperties(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.EndGetServiceProperties(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndGetServiceProperties (asyncResult As IAsyncResult) As ServiceProperties" />
      <MemberSignature Language="F#" Value="abstract member EndGetServiceProperties : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&#xA;override this.EndGetServiceProperties : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" Usage="cloudTableClient.EndGetServiceProperties asyncResult" />
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
        <param name="asyncResult"><span data-ttu-id="098b0-177">前回の呼び出しから返された結果<see cref="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.BeginGetServiceProperties(System.AsyncCallback,System.Object)" />です。</span><span class="sxs-lookup"><span data-stu-id="098b0-177">The result returned from a prior call to <see cref="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.BeginGetServiceProperties(System.AsyncCallback,System.Object)" />.</span></span></param>
        <summary>
            <span data-ttu-id="098b0-178">テーブル サービスのサービス プロパティを取得する非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="098b0-178">Ends an asynchronous operation to get the service properties of the Table service.</span></span>
            </summary>
        <returns><span data-ttu-id="098b0-179"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-179">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndGetServiceStats">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats EndGetServiceStats (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats EndGetServiceStats(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.EndGetServiceStats(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndGetServiceStats (asyncResult As IAsyncResult) As ServiceStats" />
      <MemberSignature Language="F#" Value="abstract member EndGetServiceStats : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&#xA;override this.EndGetServiceStats : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" Usage="cloudTableClient.EndGetServiceStats asyncResult" />
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
        <param name="asyncResult"><span data-ttu-id="098b0-180"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="098b0-180">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="098b0-181">セカンダリ Table サービス エンドポイントのサービスの統計情報を取得する非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="098b0-181">Ends an asynchronous operation to get service stats for the secondary Table service endpoint.</span></span>
            </summary>
        <returns><span data-ttu-id="098b0-182"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-182">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndListTablesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Table.TableResultSegment EndListTablesSegmented (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Table.TableResultSegment EndListTablesSegmented(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.EndListTablesSegmented(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndListTablesSegmented (asyncResult As IAsyncResult) As TableResultSegment" />
      <MemberSignature Language="F#" Value="abstract member EndListTablesSegmented : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Table.TableResultSegment&#xA;override this.EndListTablesSegmented : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Table.TableResultSegment" Usage="cloudTableClient.EndListTablesSegmented asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableResultSegment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="098b0-183"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="098b0-183">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="098b0-184">テーブルの結果セグメントを返す非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="098b0-184">Ends an asynchronous operation to return a result segment of tables.</span></span> 
            </summary>
        <returns><span data-ttu-id="098b0-185"><see cref="T:Microsoft.WindowsAzure.Storage.Table.TableResultSegment" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-185">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableResultSegment" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndSetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual void EndSetServiceProperties (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndSetServiceProperties(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.EndSetServiceProperties(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndSetServiceProperties (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndSetServiceProperties : IAsyncResult -&gt; unit&#xA;override this.EndSetServiceProperties : IAsyncResult -&gt; unit" Usage="cloudTableClient.EndSetServiceProperties asyncResult" />
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
        <param name="asyncResult"><span data-ttu-id="098b0-186">前回の呼び出しから返される結果<see cref="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.BeginSetServiceProperties(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties,System.AsyncCallback,System.Object)" /></span><span class="sxs-lookup"><span data-stu-id="098b0-186">The result returned from a prior call to <see cref="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.BeginSetServiceProperties(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties,System.AsyncCallback,System.Object)" /></span></span></param>
        <summary>
            <span data-ttu-id="098b0-187">テーブル サービスのサービス プロパティを設定する非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="098b0-187">Ends an asynchronous operation to set the service properties of the Table service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties GetServiceProperties (Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties GetServiceProperties(class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.GetServiceProperties(Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceProperties : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&#xA;override this.GetServiceProperties : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" Usage="cloudTableClient.GetServiceProperties (requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="098b0-188">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-188">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="098b0-189"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-189">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="098b0-190">テーブル サービスのサービスのプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="098b0-190">Gets the service properties for the Table service.</span></span>
            </summary>
        <returns><span data-ttu-id="098b0-191"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-191">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.GetServicePropertiesAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetServicePropertiesAsync () As Task(Of ServiceProperties)" />
      <MemberSignature Language="F#" Value="abstract member GetServicePropertiesAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;&#xA;override this.GetServicePropertiesAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;" Usage="cloudTableClient.GetServicePropertiesAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
            <span data-ttu-id="098b0-192">テーブル サービスのサービス プロパティを取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="098b0-192">Initiates an asynchronous operation to get the service properties of the Table service.</span></span>
            </summary>
        <returns><span data-ttu-id="098b0-193">非同期操作を表す <see cref="T:System.Threading.Tasks.Task`1" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-193">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.GetServicePropertiesAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetServicePropertiesAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;&#xA;override this.GetServicePropertiesAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;" Usage="cloudTableClient.GetServicePropertiesAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <param name="cancellationToken"><span data-ttu-id="098b0-194">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="098b0-194">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="098b0-195">テーブル サービスのサービス プロパティを取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="098b0-195">Initiates an asynchronous operation to get the service properties of the Table service.</span></span>
            </summary>
        <returns><span data-ttu-id="098b0-196">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="098b0-196">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync (Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync(class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.GetServicePropertiesAsync(Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;&#xA;override this.GetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;" Usage="cloudTableClient.GetServicePropertiesAsync (requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="098b0-197">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-197">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="098b0-198"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-198">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="098b0-199">テーブル サービスのサービス プロパティを取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="098b0-199">Initiates an asynchronous operation to get the service properties of the Table service.</span></span>
            </summary>
        <returns><span data-ttu-id="098b0-200">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="098b0-200">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync (Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync(class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.GetServicePropertiesAsync(Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;&#xA;override this.GetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;" Usage="cloudTableClient.GetServicePropertiesAsync (requestOptions, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="098b0-201">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-201">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="098b0-202"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-202">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="098b0-203">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="098b0-203">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="098b0-204">テーブル サービスのサービス プロパティを取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="098b0-204">Initiates an asynchronous operation to get the service properties of the Table service.</span></span>
            </summary>
        <returns><span data-ttu-id="098b0-205">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="098b0-205">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceStats">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats GetServiceStats (Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats GetServiceStats(class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.GetServiceStats(Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceStats : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&#xA;override this.GetServiceStats : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" Usage="cloudTableClient.GetServiceStats (requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="098b0-206">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-206">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="098b0-207"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-207">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="098b0-208">セカンダリ Table サービス エンドポイントのサービスの統計情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="098b0-208">Gets service stats for the secondary Table service endpoint.</span></span>
            </summary>
        <returns><span data-ttu-id="098b0-209"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-209">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceStatsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.GetServiceStatsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetServiceStatsAsync () As Task(Of ServiceStats)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceStatsAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;&#xA;override this.GetServiceStatsAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;" Usage="cloudTableClient.GetServiceStatsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
            <span data-ttu-id="098b0-210">セカンダリ Table サービス エンドポイントのサービスの統計情報を取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="098b0-210">Initiates an asynchronous operation to get service stats for the secondary Table service endpoint.</span></span>
            </summary>
        <returns><span data-ttu-id="098b0-211">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="098b0-211">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceStatsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.GetServiceStatsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceStatsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;&#xA;override this.GetServiceStatsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;" Usage="cloudTableClient.GetServiceStatsAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <param name="cancellationToken"><span data-ttu-id="098b0-212">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="098b0-212">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="098b0-213">セカンダリ Table サービス エンドポイントのサービスの統計情報を取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="098b0-213">Initiates an asynchronous operation to get service stats for the secondary Table service endpoint.</span></span>
            </summary>
        <returns><span data-ttu-id="098b0-214">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="098b0-214">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceStatsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync (Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync(class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.GetServiceStatsAsync(Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceStatsAsync : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;&#xA;override this.GetServiceStatsAsync : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;" Usage="cloudTableClient.GetServiceStatsAsync (requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="098b0-215">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-215">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="098b0-216"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-216">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="098b0-217">セカンダリ Table サービス エンドポイントのサービスの統計情報を取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="098b0-217">Initiates an asynchronous operation to get service stats for the secondary Table service endpoint.</span></span>
            </summary>
        <returns><span data-ttu-id="098b0-218">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="098b0-218">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceStatsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync (Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync(class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.GetServiceStatsAsync(Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceStatsAsync : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;&#xA;override this.GetServiceStatsAsync : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;" Usage="cloudTableClient.GetServiceStatsAsync (requestOptions, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="098b0-219">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-219">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="098b0-220"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-220">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="098b0-221">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="098b0-221">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="098b0-222">セカンダリ Table サービス エンドポイントのサービスの統計情報を取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="098b0-222">Initiates an asynchronous operation to get service stats for the secondary Table service endpoint.</span></span>
            </summary>
        <returns><span data-ttu-id="098b0-223">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="098b0-223">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTableReference">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Table.CloudTable GetTableReference (string tableName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Table.CloudTable GetTableReference(string tableName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.GetTableReference(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetTableReference (tableName As String) As CloudTable" />
      <MemberSignature Language="F#" Value="abstract member GetTableReference : string -&gt; Microsoft.WindowsAzure.Storage.Table.CloudTable&#xA;override this.GetTableReference : string -&gt; Microsoft.WindowsAzure.Storage.Table.CloudTable" Usage="cloudTableClient.GetTableReference tableName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.CloudTable</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tableName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="tableName"><span data-ttu-id="098b0-224">テーブルの名前を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="098b0-224">A string containing the name of the table.</span></span></param>
        <summary>
            <span data-ttu-id="098b0-225">指定されたテーブルへの参照を取得します。</span><span class="sxs-lookup"><span data-stu-id="098b0-225">Gets a reference to the specified table.</span></span>
            </summary>
        <returns><span data-ttu-id="098b0-226"><see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTable" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-226">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTable" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTableServiceContext">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext GetTableServiceContext ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext GetTableServiceContext() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.GetTableServiceContext" />
      <MemberSignature Language="VB.NET" Value="Public Function GetTableServiceContext () As TableServiceContext" />
      <MemberSignature Language="F#" Value="member this.GetTableServiceContext : unit -&gt; Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext" Usage="cloudTableClient.GetTableServiceContext " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="098b0-227">新たに作成<see cref="T:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext" />テーブル サービスに対する操作を実行するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-227">Creates a new <see cref="T:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext" /> object for performing operations against the Table service.</span></span>
            </summary>
        <returns><span data-ttu-id="098b0-228">テーブル サービスに対する操作を実行するのに使用するサービス コンテキスト。</span><span class="sxs-lookup"><span data-stu-id="098b0-228">A service context to use for performing operations against the Table service.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTables">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Table.CloudTable&gt; ListTables (string prefix = null, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Table.CloudTable&gt; ListTables(string prefix, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.ListTables(System.String,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ListTables : string * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Table.CloudTable&gt;&#xA;override this.ListTables : string * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Table.CloudTable&gt;" Usage="cloudTableClient.ListTables (prefix, requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Table.CloudTable&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="098b0-229">テーブル名のプレフィックスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="098b0-229">A string containing the table name prefix.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="098b0-230">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-230">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="098b0-231"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-231">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="098b0-232">テーブル、遅延、取得した指定したプレフィックスで始まるの列挙可能なコレクションを返します。</span><span class="sxs-lookup"><span data-stu-id="098b0-232">Returns an enumerable collection of tables, retrieved lazily, that start with the specified prefix.</span></span>
            </summary>
        <returns><span data-ttu-id="098b0-233">列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTable" />遅れて取得されるオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-233">An enumerable collection of <see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTable" /> objects that are retrieved lazily.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Table.TableResultSegment ListTablesSegmented (Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Table.TableResultSegment ListTablesSegmented(class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.ListTablesSegmented(Microsoft.WindowsAzure.Storage.Table.TableContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ListTablesSegmented (currentToken As TableContinuationToken) As TableResultSegment" />
      <MemberSignature Language="F#" Value="abstract member ListTablesSegmented : Microsoft.WindowsAzure.Storage.Table.TableContinuationToken -&gt; Microsoft.WindowsAzure.Storage.Table.TableResultSegment&#xA;override this.ListTablesSegmented : Microsoft.WindowsAzure.Storage.Table.TableContinuationToken -&gt; Microsoft.WindowsAzure.Storage.Table.TableResultSegment" Usage="cloudTableClient.ListTablesSegmented currentToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableResultSegment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
      </Parameters>
      <Docs>
        <param name="currentToken"><span data-ttu-id="098b0-234">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />前の一覧作成操作によって返されます。</span><span class="sxs-lookup"><span data-stu-id="098b0-234">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" /> returned by a previous listing operation.</span></span></param>
        <summary>
            <span data-ttu-id="098b0-235">テーブルの結果セグメントを返します。</span><span class="sxs-lookup"><span data-stu-id="098b0-235">Returns a result segment of tables.</span></span>
            </summary>
        <returns><span data-ttu-id="098b0-236"><see cref="T:Microsoft.WindowsAzure.Storage.Table.TableResultSegment" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-236">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableResultSegment" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Table.TableResultSegment ListTablesSegmented (string prefix, Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Table.TableResultSegment ListTablesSegmented(string prefix, class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.ListTablesSegmented(System.String,Microsoft.WindowsAzure.Storage.Table.TableContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ListTablesSegmented (prefix As String, currentToken As TableContinuationToken) As TableResultSegment" />
      <MemberSignature Language="F#" Value="abstract member ListTablesSegmented : string * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken -&gt; Microsoft.WindowsAzure.Storage.Table.TableResultSegment&#xA;override this.ListTablesSegmented : string * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken -&gt; Microsoft.WindowsAzure.Storage.Table.TableResultSegment" Usage="cloudTableClient.ListTablesSegmented (prefix, currentToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableResultSegment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="098b0-237">テーブル名のプレフィックスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="098b0-237">A string containing the table name prefix.</span></span></param>
        <param name="currentToken"><span data-ttu-id="098b0-238">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />前の一覧作成操作によって返されます。</span><span class="sxs-lookup"><span data-stu-id="098b0-238">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" /> returned by a previous listing operation.</span></span></param>
        <summary>
            <span data-ttu-id="098b0-239">テーブルの遅延、取得した指定したプレフィックスで始まる結果セグメントを返します。</span><span class="sxs-lookup"><span data-stu-id="098b0-239">Returns a result segment of tables, retrieved lazily, that start with the specified prefix.</span></span>
            </summary>
        <returns><span data-ttu-id="098b0-240"><see cref="T:Microsoft.WindowsAzure.Storage.Table.TableResultSegment" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-240">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableResultSegment" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Table.TableResultSegment ListTablesSegmented (string prefix, Nullable&lt;int&gt; maxResults, Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Table.TableResultSegment ListTablesSegmented(string prefix, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.ListTablesSegmented(System.String,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ListTablesSegmented : string * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Table.TableResultSegment&#xA;override this.ListTablesSegmented : string * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Table.TableResultSegment" Usage="cloudTableClient.ListTablesSegmented (prefix, maxResults, currentToken, requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableResultSegment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="098b0-241">テーブル名のプレフィックスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="098b0-241">A string containing the table name prefix.</span></span></param>
        <param name="maxResults"><span data-ttu-id="098b0-242">5000 の操作あたりの上限に達するまで、一度に返される結果の最大数を示す正の整数値。</span><span class="sxs-lookup"><span data-stu-id="098b0-242">A non-negative integer value that indicates the maximum number of results to be returned at a time, up to the per-operation limit of 5000.</span></span> <span data-ttu-id="098b0-243">この値が場合<c>null</c>結果の最大数が返されます、最大 5000 です。</span><span class="sxs-lookup"><span data-stu-id="098b0-243">If this value is <c>null</c>, the maximum possible number of results will be returned, up to 5000.</span></span></param>
        <param name="currentToken"><span data-ttu-id="098b0-244">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />前の一覧作成操作によって返されます。</span><span class="sxs-lookup"><span data-stu-id="098b0-244">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" /> returned by a previous listing operation.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="098b0-245">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-245">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="098b0-246"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-246">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="098b0-247">テーブルの遅延、取得した指定したプレフィックスで始まる結果セグメントを返します。</span><span class="sxs-lookup"><span data-stu-id="098b0-247">Returns a result segment of tables, retrieved lazily, that start with the specified prefix.</span></span>
            </summary>
        <returns><span data-ttu-id="098b0-248"><see cref="T:Microsoft.WindowsAzure.Storage.Table.TableResultSegment" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-248">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableResultSegment" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt; ListTablesSegmentedAsync (Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt; ListTablesSegmentedAsync(class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.ListTablesSegmentedAsync(Microsoft.WindowsAzure.Storage.Table.TableContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ListTablesSegmentedAsync (currentToken As TableContinuationToken) As Task(Of TableResultSegment)" />
      <MemberSignature Language="F#" Value="abstract member ListTablesSegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt;&#xA;override this.ListTablesSegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt;" Usage="cloudTableClient.ListTablesSegmentedAsync currentToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
      </Parameters>
      <Docs>
        <param name="currentToken"><span data-ttu-id="098b0-249">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />前の一覧作成操作によって返されます。</span><span class="sxs-lookup"><span data-stu-id="098b0-249">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" /> returned by a previous listing operation.</span></span></param>
        <summary>
            <span data-ttu-id="098b0-250">テーブルの結果セグメントを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="098b0-250">Initiates an asynchronous operation to return a result segment of tables.</span></span>
            </summary>
        <returns><span data-ttu-id="098b0-251">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableResultSegment" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="098b0-251">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableResultSegment" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt; ListTablesSegmentedAsync (Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt; ListTablesSegmentedAsync(class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.ListTablesSegmentedAsync(Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListTablesSegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt;&#xA;override this.ListTablesSegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt;" Usage="cloudTableClient.ListTablesSegmentedAsync (currentToken, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="currentToken"><span data-ttu-id="098b0-252">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />前の一覧作成操作によって返されます。</span><span class="sxs-lookup"><span data-stu-id="098b0-252">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" /> returned by a previous listing operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="098b0-253">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="098b0-253">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="098b0-254">テーブルの結果セグメントを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="098b0-254">Initiates an asynchronous operation to return a result segment of tables.</span></span>
            </summary>
        <returns><span data-ttu-id="098b0-255">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableResultSegment" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="098b0-255">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableResultSegment" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt; ListTablesSegmentedAsync (string prefix, Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt; ListTablesSegmentedAsync(string prefix, class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.ListTablesSegmentedAsync(System.String,Microsoft.WindowsAzure.Storage.Table.TableContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ListTablesSegmentedAsync (prefix As String, currentToken As TableContinuationToken) As Task(Of TableResultSegment)" />
      <MemberSignature Language="F#" Value="abstract member ListTablesSegmentedAsync : string * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt;&#xA;override this.ListTablesSegmentedAsync : string * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt;" Usage="cloudTableClient.ListTablesSegmentedAsync (prefix, currentToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="098b0-256">テーブル名のプレフィックスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="098b0-256">A string containing the table name prefix.</span></span></param>
        <param name="currentToken"><span data-ttu-id="098b0-257">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />前の一覧作成操作によって返されます。</span><span class="sxs-lookup"><span data-stu-id="098b0-257">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" /> returned by a previous listing operation.</span></span></param>
        <summary>
            <span data-ttu-id="098b0-258">指定したプレフィックスで始まるテーブルの結果セグメントを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="098b0-258">Initiates an asynchronous operation to return a result segment of tables that start with the specified prefix.</span></span>
            </summary>
        <returns><span data-ttu-id="098b0-259">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableResultSegment" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="098b0-259">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableResultSegment" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt; ListTablesSegmentedAsync (string prefix, Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt; ListTablesSegmentedAsync(string prefix, class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.ListTablesSegmentedAsync(System.String,Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListTablesSegmentedAsync : string * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt;&#xA;override this.ListTablesSegmentedAsync : string * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt;" Usage="cloudTableClient.ListTablesSegmentedAsync (prefix, currentToken, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="098b0-260">テーブル名のプレフィックスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="098b0-260">A string containing the table name prefix.</span></span></param>
        <param name="currentToken"><span data-ttu-id="098b0-261">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />前の一覧作成操作によって返されます。</span><span class="sxs-lookup"><span data-stu-id="098b0-261">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" /> returned by a previous listing operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="098b0-262">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="098b0-262">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="098b0-263">指定したプレフィックスで始まるテーブルの結果セグメントを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="098b0-263">Initiates an asynchronous operation to return a result segment of tables that start with the specified prefix.</span></span>
            </summary>
        <returns><span data-ttu-id="098b0-264">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableResultSegment" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="098b0-264">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableResultSegment" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt; ListTablesSegmentedAsync (string prefix, Nullable&lt;int&gt; maxResults, Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt; ListTablesSegmentedAsync(string prefix, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.ListTablesSegmentedAsync(System.String,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ListTablesSegmentedAsync : string * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt;&#xA;override this.ListTablesSegmentedAsync : string * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt;" Usage="cloudTableClient.ListTablesSegmentedAsync (prefix, maxResults, currentToken, requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="098b0-265">テーブル名のプレフィックスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="098b0-265">A string containing the table name prefix.</span></span></param>
        <param name="maxResults"><span data-ttu-id="098b0-266">5000 の操作あたりの上限に達するまで、一度に返される結果の最大数を示す正の整数値。</span><span class="sxs-lookup"><span data-stu-id="098b0-266">A non-negative integer value that indicates the maximum number of results to be returned at a time, up to the per-operation limit of 5000.</span></span> <span data-ttu-id="098b0-267">この値が場合<c>null</c>結果の最大数が返されます、最大 5000 です。</span><span class="sxs-lookup"><span data-stu-id="098b0-267">If this value is <c>null</c>, the maximum possible number of results will be returned, up to 5000.</span></span></param>
        <param name="currentToken"><span data-ttu-id="098b0-268">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />前の一覧作成操作によって返されます。</span><span class="sxs-lookup"><span data-stu-id="098b0-268">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" /> returned by a previous listing operation.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="098b0-269">サーバーのタイムアウト、最大実行時間、および操作の再試行ポリシーです。</span><span class="sxs-lookup"><span data-stu-id="098b0-269">The server timeout, maximum execution time, and retry policies for the operation.</span></span></param>
        <param name="operationContext"><span data-ttu-id="098b0-270"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-270">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="098b0-271">指定したプレフィックスで始まるテーブルの結果セグメントを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="098b0-271">Initiates an asynchronous operation to return a result segment of tables that start with the specified prefix.</span></span>
            </summary>
        <returns><span data-ttu-id="098b0-272">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableResultSegment" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="098b0-272">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableResultSegment" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt; ListTablesSegmentedAsync (string prefix, Nullable&lt;int&gt; maxResults, Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt; ListTablesSegmentedAsync(string prefix, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.ListTablesSegmentedAsync(System.String,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListTablesSegmentedAsync : string * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt;&#xA;override this.ListTablesSegmentedAsync : string * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt;" Usage="cloudTableClient.ListTablesSegmentedAsync (prefix, maxResults, currentToken, requestOptions, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="098b0-273">テーブル名のプレフィックスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="098b0-273">A string containing the table name prefix.</span></span></param>
        <param name="maxResults"><span data-ttu-id="098b0-274">5000 の操作あたりの上限に達するまで、一度に返される結果の最大数を示す正の整数値。</span><span class="sxs-lookup"><span data-stu-id="098b0-274">A non-negative integer value that indicates the maximum number of results to be returned at a time, up to the per-operation limit of 5000.</span></span> <span data-ttu-id="098b0-275">この値が場合<c>null</c>結果の最大数が返されます、最大 5000 です。</span><span class="sxs-lookup"><span data-stu-id="098b0-275">If this value is <c>null</c>, the maximum possible number of results will be returned, up to 5000.</span></span></param>
        <param name="currentToken"><span data-ttu-id="098b0-276">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />前の一覧作成操作によって返されます。</span><span class="sxs-lookup"><span data-stu-id="098b0-276">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" /> returned by a previous listing operation.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="098b0-277">サーバーのタイムアウト、最大実行時間、および操作の再試行ポリシーです。</span><span class="sxs-lookup"><span data-stu-id="098b0-277">The server timeout, maximum execution time, and retry policies for the operation.</span></span></param>
        <param name="operationContext"><span data-ttu-id="098b0-278"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-278">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="098b0-279">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="098b0-279">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="098b0-280">指定したプレフィックスで始まるテーブルの結果セグメントを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="098b0-280">Initiates an asynchronous operation to return a result segment of tables that start with the specified prefix.</span></span>
            </summary>
        <returns><span data-ttu-id="098b0-281">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableResultSegment" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="098b0-281">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableResultSegment" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual void SetServiceProperties (Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SetServiceProperties(class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.SetServiceProperties(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetServiceProperties : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.SetServiceProperties : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudTableClient.SetServiceProperties (properties, requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="098b0-282"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-282">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> object.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="098b0-283">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-283">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="098b0-284"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-284">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="098b0-285">テーブル サービスのサービスのプロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="098b0-285">Sets the service properties of the Table service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetServicePropertiesAsync (Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetServicePropertiesAsync(class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.SetServicePropertiesAsync(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function SetServicePropertiesAsync (properties As ServiceProperties) As Task" />
      <MemberSignature Language="F#" Value="abstract member SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties -&gt; System.Threading.Tasks.Task&#xA;override this.SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties -&gt; System.Threading.Tasks.Task" Usage="cloudTableClient.SetServicePropertiesAsync properties" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <param name="properties"><span data-ttu-id="098b0-286"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-286">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="098b0-287">テーブル サービスのサービス プロパティを設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="098b0-287">Initiates an asynchronous operation to set the service properties of the Table service.</span></span>
            </summary>
        <returns><span data-ttu-id="098b0-288">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-288">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetServicePropertiesAsync (Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetServicePropertiesAsync(class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.SetServicePropertiesAsync(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudTableClient.SetServicePropertiesAsync (properties, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <param name="properties"><span data-ttu-id="098b0-289"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-289">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> object.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="098b0-290">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="098b0-290">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="098b0-291">テーブル サービスのサービス プロパティを設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="098b0-291">Initiates an asynchronous operation to set the service properties of the Table service.</span></span>
            </summary>
        <returns><span data-ttu-id="098b0-292">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-292">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetServicePropertiesAsync (Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetServicePropertiesAsync(class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.SetServicePropertiesAsync(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudTableClient.SetServicePropertiesAsync (properties, requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="098b0-293"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-293">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> object.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="098b0-294">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-294">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="098b0-295"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-295">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="098b0-296">テーブル サービスのサービス プロパティを設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="098b0-296">Initiates an asynchronous operation to set the service properties of the Table service.</span></span>
            </summary>
        <returns><span data-ttu-id="098b0-297">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-297">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetServicePropertiesAsync (Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetServicePropertiesAsync(class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.SetServicePropertiesAsync(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudTableClient.SetServicePropertiesAsync (properties, requestOptions, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
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
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="098b0-298"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-298">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> object.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="098b0-299">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-299">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="098b0-300"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-300">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="098b0-301">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="098b0-301">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="098b0-302">テーブル サービスのサービス プロパティを設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="098b0-302">Initiates an asynchronous operation to set the service properties of the Table service.</span></span>
            </summary>
        <returns><span data-ttu-id="098b0-303">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="098b0-303">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageUri">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.StorageUri StorageUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.StorageUri StorageUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.StorageUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StorageUri As StorageUri" />
      <MemberSignature Language="F#" Value="member this.StorageUri : Microsoft.WindowsAzure.Storage.StorageUri" Usage="Microsoft.WindowsAzure.Storage.Table.CloudTableClient.StorageUri" />
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
            <span data-ttu-id="098b0-304">プライマリとセカンダリの両方の場所の Table サービスのエンドポイントを取得します。</span><span class="sxs-lookup"><span data-stu-id="098b0-304">Gets the Table service endpoints for both the primary and secondary locations.</span></span>
            </summary>
        <value><span data-ttu-id="098b0-305">型のオブジェクト<see cref="P:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.StorageUri" />プライマリとセカンダリの両方の場所のサービスの Uri をテーブルを格納します。</span><span class="sxs-lookup"><span data-stu-id="098b0-305">An object of type <see cref="P:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.StorageUri" /> containing Table service URIs for both the primary and secondary locations.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>