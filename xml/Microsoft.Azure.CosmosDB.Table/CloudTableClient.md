<Type Name="CloudTableClient" FullName="Microsoft.Azure.CosmosDB.Table.CloudTableClient">
  <TypeSignature Language="C#" Value="public class CloudTableClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CloudTableClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.CosmosDB.Table.CloudTableClient" />
  <TypeSignature Language="VB.NET" Value="Public Class CloudTableClient" />
  <TypeSignature Language="F#" Value="type CloudTableClient = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
    <AssemblyVersion>0.9.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d31f9-101">Microsoft Azure テーブル サービスのクライアント側の論理表現を提供します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-101">Provides a client-side logical representation of the Microsoft Azure Table service.</span></span> <span data-ttu-id="d31f9-102">このクライアントを使用してを構成およびテーブル サービスに対する要求を実行します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-102">This client is used to configure and execute requests against the Table service.</span></span>
            </summary>
    <remarks><span data-ttu-id="d31f9-103">サービス クライアントは、エンドポイントまたはテーブル サービスのエンドポイントをカプセル化します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-103">The service client encapsulates the endpoint or endpoints for the Table service.</span></span> <span data-ttu-id="d31f9-104">サービス クライアントを認証済みアクセスに使用する場合、ストレージ アカウントにアクセスするための資格情報もカプセル化します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-104">If the service client will be used for authenticated access, it also encapsulates the credentials for accessing the storage account.</span></span></remarks>
    <remarks><span data-ttu-id="d31f9-105">CloudTableClient オブジェクトは、テーブル サービスのベース URI をカプセル化します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-105">The CloudTableClient object encapsulates the base URI for the Table service.</span></span> <span data-ttu-id="d31f9-106">サービス クライアントを認証済みアクセスに使用する場合、ストレージ アカウントにアクセスするための資格情報もカプセル化します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-106">If the service client will be used for authenticated access, it also encapsulates the credentials for accessing the storage account.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudTableClient (Microsoft.Azure.Storage.StorageUri storageUri, Microsoft.Azure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Storage.StorageUri storageUri, class Microsoft.Azure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.#ctor(Microsoft.Azure.Storage.StorageUri,Microsoft.Azure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.CosmosDB.Table.CloudTableClient : Microsoft.Azure.Storage.StorageUri * Microsoft.Azure.Storage.Auth.StorageCredentials -&gt; Microsoft.Azure.CosmosDB.Table.CloudTableClient" Usage="new Microsoft.Azure.CosmosDB.Table.CloudTableClient (storageUri, credentials)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storageUri" Type="Microsoft.Azure.Storage.StorageUri" />
        <Parameter Name="credentials" Type="Microsoft.Azure.Storage.Auth.StorageCredentials" />
      </Parameters>
      <Docs>
        <param name="storageUri"><span data-ttu-id="d31f9-107">A<see cref="P:Microsoft.Azure.CosmosDB.Table.CloudTableClient.StorageUri" />を使用してクライアントを作成するテーブル サービスのエンドポイントを含むオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-107">A <see cref="P:Microsoft.Azure.CosmosDB.Table.CloudTableClient.StorageUri" /> object containing the Table service endpoint to use to create the client.</span></span></param>
        <param name="credentials"><span data-ttu-id="d31f9-108"><see cref="T:Microsoft.Azure.Storage.Auth.StorageCredentials" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-108">A <see cref="T:Microsoft.Azure.Storage.Auth.StorageCredentials" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="d31f9-109">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTableClient" />クラス、指定されたテーブル サービス エンドポイントとアカウントの資格情報を使用します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-109">Initializes a new instance of the <see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTableClient" /> class using the specified Table service endpoint and account credentials.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudTableClient (Uri baseUri, Microsoft.Azure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class Microsoft.Azure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.#ctor(System.Uri,Microsoft.Azure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (baseUri As Uri, credentials As StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.CosmosDB.Table.CloudTableClient : Uri * Microsoft.Azure.Storage.Auth.StorageCredentials -&gt; Microsoft.Azure.CosmosDB.Table.CloudTableClient" Usage="new Microsoft.Azure.CosmosDB.Table.CloudTableClient (baseUri, credentials)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="baseUri" Type="System.Uri" />
        <Parameter Name="credentials" Type="Microsoft.Azure.Storage.Auth.StorageCredentials" />
      </Parameters>
      <Docs>
        <param name="baseUri"><span data-ttu-id="d31f9-110">A<see cref="T:System.Uri" />を使用してクライアントを作成するテーブル サービスのエンドポイントを含むオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-110">A <see cref="T:System.Uri" /> object containing the Table service endpoint to use to create the client.</span></span></param>
        <param name="credentials"><span data-ttu-id="d31f9-111"><see cref="T:Microsoft.Azure.Storage.Auth.StorageCredentials" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-111">A <see cref="T:Microsoft.Azure.Storage.Auth.StorageCredentials" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="d31f9-112">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTableClient" />クラス、指定されたテーブル サービス エンドポイントとアカウントの資格情報を使用します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-112">Initializes a new instance of the <see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTableClient" /> class using the specified Table service endpoint and account credentials.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudTableClient (Microsoft.Azure.Storage.StorageUri storageUri, Microsoft.Azure.Storage.Auth.StorageCredentials credentials, Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy connectionPolicy = null, Nullable&lt;Microsoft.Azure.CosmosDB.ConsistencyLevel&gt; desiredConsistencyLevel = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Storage.StorageUri storageUri, class Microsoft.Azure.Storage.Auth.StorageCredentials credentials, class Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy connectionPolicy, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.CosmosDB.ConsistencyLevel&gt; desiredConsistencyLevel) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.#ctor(Microsoft.Azure.Storage.StorageUri,Microsoft.Azure.Storage.Auth.StorageCredentials,Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy,System.Nullable{Microsoft.Azure.CosmosDB.ConsistencyLevel})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.CosmosDB.Table.CloudTableClient : Microsoft.Azure.Storage.StorageUri * Microsoft.Azure.Storage.Auth.StorageCredentials * Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy * Nullable&lt;Microsoft.Azure.CosmosDB.ConsistencyLevel&gt; -&gt; Microsoft.Azure.CosmosDB.Table.CloudTableClient" Usage="new Microsoft.Azure.CosmosDB.Table.CloudTableClient (storageUri, credentials, connectionPolicy, desiredConsistencyLevel)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storageUri" Type="Microsoft.Azure.Storage.StorageUri" />
        <Parameter Name="credentials" Type="Microsoft.Azure.Storage.Auth.StorageCredentials" />
        <Parameter Name="connectionPolicy" Type="Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy" />
        <Parameter Name="desiredConsistencyLevel" Type="System.Nullable&lt;Microsoft.Azure.CosmosDB.ConsistencyLevel&gt;" />
      </Parameters>
      <Docs>
        <param name="storageUri"><span data-ttu-id="d31f9-113">A<see cref="P:Microsoft.Azure.CosmosDB.Table.CloudTableClient.StorageUri" />を使用してクライアントを作成するテーブル サービスのエンドポイントを含むオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-113">A <see cref="P:Microsoft.Azure.CosmosDB.Table.CloudTableClient.StorageUri" /> object containing the Table service endpoint to use to create the client.</span></span></param>
        <param name="credentials"><span data-ttu-id="d31f9-114"><see cref="T:Microsoft.Azure.Storage.Auth.StorageCredentials" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-114">A <see cref="T:Microsoft.Azure.Storage.Auth.StorageCredentials" /> object.</span></span></param>
        <param name="connectionPolicy">
            <span data-ttu-id="d31f9-115">(省略可能)Table クライアントの接続のポリシー。</span><span class="sxs-lookup"><span data-stu-id="d31f9-115">(Optional) The connection policy for the table client.</span></span> <span data-ttu-id="d31f9-116">既定値が使用される [なし] が渡された場合<see cref="T:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy" /></span><span class="sxs-lookup"><span data-stu-id="d31f9-116">If none is passed, the default is used <see cref="T:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy" /></span></span></param>
        <param name="desiredConsistencyLevel">
            <span data-ttu-id="d31f9-117">(省略可能)読み取り操作のためには、データベース アカウントの一貫性レベルを緩和するために使用できます。</span><span class="sxs-lookup"><span data-stu-id="d31f9-117">(Optional) This can be used to weaken the database account consistency level for read operations.</span></span> <span data-ttu-id="d31f9-118">これが設定されていない場合、データベース アカウント整合性レベルがすべての要求に対して使用されます。</span><span class="sxs-lookup"><span data-stu-id="d31f9-118">If this is not set the database account consistency level will be used for all requests.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d31f9-119">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTableClient" />クラス、指定されたテーブル サービス エンドポイントとアカウントの資格情報を使用します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-119">Initializes a new instance of the <see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTableClient" /> class using the specified Table service endpoint and account credentials.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationScheme">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Storage.AuthenticationScheme AuthenticationScheme { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Storage.AuthenticationScheme AuthenticationScheme" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.CloudTableClient.AuthenticationScheme" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationScheme As AuthenticationScheme" />
      <MemberSignature Language="F#" Value="member this.AuthenticationScheme : Microsoft.Azure.Storage.AuthenticationScheme with get, set" Usage="Microsoft.Azure.CosmosDB.Table.CloudTableClient.AuthenticationScheme" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.AuthenticationScheme</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d31f9-120">取得または HTTP 要求の署名に使用する認証スキームを設定します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-120">Gets or sets the authentication scheme to use to sign HTTP requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para><span data-ttu-id="d31f9-121">共有キーまたは共有キー Lite の資格情報が使用される場合にのみ、このプロパティを設定します。共有アクセス署名または匿名アクセス経由での認証には適用されません。</span><span class="sxs-lookup"><span data-stu-id="d31f9-121">This property is set only when Shared Key or Shared Key Lite credentials are used; it does not apply to authentication via a shared access signature or anonymous access.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.CloudTableClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri" Usage="Microsoft.Azure.CosmosDB.Table.CloudTableClient.BaseUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d31f9-122">プライマリの場所の Table サービス クライアントのベース URI を取得します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-122">Gets the base URI for the Table service client at the primary location.</span></span>
            </summary>
        <value><span data-ttu-id="d31f9-123">A<see cref="T:System.Uri" />プライマリの場所の Table サービス クライアントを構築するために使用されるベース URI を含むオブジェクトします。</span><span class="sxs-lookup"><span data-stu-id="d31f9-123">A <see cref="T:System.Uri" /> object containing the base URI used to construct the Table service client at the primary location.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginGetServiceProperties (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginGetServiceProperties(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.BeginGetServiceProperties(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginGetServiceProperties (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginGetServiceProperties : AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetServiceProperties : AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTableClient.BeginGetServiceProperties (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback"><span data-ttu-id="d31f9-124"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="d31f9-124">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="d31f9-125">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-125">A user-defined object to be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="d31f9-126">テーブル サービスのサービス プロパティを取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-126">Begins an asynchronous operation to get the service properties of the Table service.</span></span>
            </summary>
        <returns><span data-ttu-id="d31f9-127"><see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-127">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginGetServiceProperties (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginGetServiceProperties(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.BeginGetServiceProperties(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginGetServiceProperties : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetServiceProperties : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTableClient.BeginGetServiceProperties (requestOptions, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="d31f9-128">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-128">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d31f9-129"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-129">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="d31f9-130"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="d31f9-130">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="d31f9-131">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-131">A user-defined object to be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="d31f9-132">テーブル サービスのサービス プロパティを取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-132">Begins an asynchronous operation to get the service properties of the Table service.</span></span>
            </summary>
        <returns><span data-ttu-id="d31f9-133"><see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-133">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetServiceStats">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginGetServiceStats (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginGetServiceStats(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.BeginGetServiceStats(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginGetServiceStats (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginGetServiceStats : AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetServiceStats : AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTableClient.BeginGetServiceStats (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback"><span data-ttu-id="d31f9-134"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="d31f9-134">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="d31f9-135">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-135">A user-defined object to be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="d31f9-136">セカンダリ Table サービス エンドポイントのサービスの統計情報を取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-136">Begins an asynchronous operation to get service stats for the secondary Table service endpoint.</span></span>
            </summary>
        <returns><span data-ttu-id="d31f9-137"><see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-137">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetServiceStats">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginGetServiceStats (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginGetServiceStats(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.BeginGetServiceStats(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginGetServiceStats : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetServiceStats : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTableClient.BeginGetServiceStats (requestOptions, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="d31f9-138">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-138">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d31f9-139"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-139">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="d31f9-140"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="d31f9-140">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="d31f9-141">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-141">A user-defined object to be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="d31f9-142">セカンダリ Table サービス エンドポイントのサービスの統計情報を取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-142">Begins an asynchronous operation to get service stats for the secondary Table service endpoint.</span></span>
            </summary>
        <returns><span data-ttu-id="d31f9-143"><see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-143">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListTablesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginListTablesSegmented (Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginListTablesSegmented(class Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.BeginListTablesSegmented(Microsoft.Azure.CosmosDB.Table.TableContinuationToken,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginListTablesSegmented (currentToken As TableContinuationToken, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginListTablesSegmented : Microsoft.Azure.CosmosDB.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginListTablesSegmented : Microsoft.Azure.CosmosDB.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTableClient.BeginListTablesSegmented (currentToken, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="currentToken"><span data-ttu-id="d31f9-144">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />前の一覧作成操作によって返されます。</span><span class="sxs-lookup"><span data-stu-id="d31f9-144">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> returned by a previous listing operation.</span></span></param>
        <param name="callback"><span data-ttu-id="d31f9-145"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="d31f9-145">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="d31f9-146">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-146">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="d31f9-147">テーブルの結果セグメントを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-147">Begins an asynchronous operation to return a result segment of tables.</span></span>
            </summary>
        <returns><span data-ttu-id="d31f9-148"><see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-148">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListTablesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginListTablesSegmented (string prefix, Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginListTablesSegmented(string prefix, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.BeginListTablesSegmented(System.String,Microsoft.Azure.CosmosDB.Table.TableContinuationToken,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginListTablesSegmented (prefix As String, currentToken As TableContinuationToken, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginListTablesSegmented : string * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginListTablesSegmented : string * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTableClient.BeginListTablesSegmented (prefix, currentToken, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="currentToken" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="d31f9-149">テーブル名のプレフィックスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="d31f9-149">A string containing the table name prefix.</span></span></param>
        <param name="currentToken"><span data-ttu-id="d31f9-150">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />前の一覧作成操作によって返されます。</span><span class="sxs-lookup"><span data-stu-id="d31f9-150">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> returned by a previous listing operation.</span></span></param>
        <param name="callback"><span data-ttu-id="d31f9-151"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="d31f9-151">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="d31f9-152">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-152">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="d31f9-153">指定したプレフィックスで始まるテーブルの結果セグメントを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-153">Begins an asynchronous operation to return a result segment of tables that start with the specified prefix.</span></span>
            </summary>
        <returns><span data-ttu-id="d31f9-154"><see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-154">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListTablesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginListTablesSegmented (string prefix, Nullable&lt;int&gt; maxResults, Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginListTablesSegmented(string prefix, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.BeginListTablesSegmented(System.String,System.Nullable{System.Int32},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginListTablesSegmented : string * Nullable&lt;int&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginListTablesSegmented : string * Nullable&lt;int&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTableClient.BeginListTablesSegmented (prefix, maxResults, currentToken, requestOptions, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="d31f9-155">テーブル名のプレフィックスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="d31f9-155">A string containing the table name prefix.</span></span></param>
        <param name="maxResults"><span data-ttu-id="d31f9-156">5000 の操作あたりの上限に達するまで、一度に返される結果の最大数を示す正の整数値。</span><span class="sxs-lookup"><span data-stu-id="d31f9-156">A non-negative integer value that indicates the maximum number of results to be returned at a time, up to the per-operation limit of 5000.</span></span> <span data-ttu-id="d31f9-157">この値が場合<c>null</c>結果の最大数が返されます、最大 5000 です。</span><span class="sxs-lookup"><span data-stu-id="d31f9-157">If this value is <c>null</c>, the maximum possible number of results will be returned, up to 5000.</span></span></param>
        <param name="currentToken"><span data-ttu-id="d31f9-158">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />前の一覧作成操作によって返されます。</span><span class="sxs-lookup"><span data-stu-id="d31f9-158">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> returned by a previous listing operation.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="d31f9-159">サーバーのタイムアウト、最大実行時間、および操作の再試行ポリシーです。</span><span class="sxs-lookup"><span data-stu-id="d31f9-159">The server timeout, maximum execution time, and retry policies for the operation.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d31f9-160"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-160">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="d31f9-161"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="d31f9-161">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="d31f9-162">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-162">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="d31f9-163">指定したプレフィックスで始まるテーブルの結果セグメントを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-163">Begins an asynchronous operation to return a result segment of tables that start with the specified prefix.</span></span>
            </summary>
        <returns><span data-ttu-id="d31f9-164"><see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-164">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginSetServiceProperties (Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties properties, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginSetServiceProperties(class Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties properties, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.BeginSetServiceProperties(Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginSetServiceProperties (properties As ServiceProperties, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginSetServiceProperties : Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetServiceProperties : Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTableClient.BeginSetServiceProperties (properties, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="properties" Type="Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="d31f9-165"><see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-165">A <see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" /> object.</span></span></param>
        <param name="callback"><span data-ttu-id="d31f9-166"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="d31f9-166">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="d31f9-167">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-167">A user-defined object to be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="d31f9-168">テーブル サービスのサービス プロパティを設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-168">Begins an asynchronous operation to set the service properties of the Table service.</span></span>
            </summary>
        <returns><span data-ttu-id="d31f9-169"><see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-169">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginSetServiceProperties (Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties properties, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginSetServiceProperties(class Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties properties, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.BeginSetServiceProperties(Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginSetServiceProperties : Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetServiceProperties : Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTableClient.BeginSetServiceProperties (properties, requestOptions, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="properties" Type="Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="d31f9-170"><see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-170">A <see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" /> object.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="d31f9-171">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-171">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d31f9-172"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-172">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="d31f9-173"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="d31f9-173">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="d31f9-174">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-174">A user-defined object to be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="d31f9-175">テーブル サービスのサービス プロパティを設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-175">Begins an asynchronous operation to set the service properties of the Table service.</span></span>
            </summary>
        <returns><span data-ttu-id="d31f9-176"><see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-176">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BufferManager">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Storage.IBufferManager BufferManager { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Storage.IBufferManager BufferManager" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.CloudTableClient.BufferManager" />
      <MemberSignature Language="VB.NET" Value="Public Property BufferManager As IBufferManager" />
      <MemberSignature Language="F#" Value="member this.BufferManager : Microsoft.Azure.Storage.IBufferManager with get, set" Usage="Microsoft.Azure.CosmosDB.Table.CloudTableClient.BufferManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.IBufferManager</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d31f9-177">取得または設定を実装するバッファー マネージャー、<see cref="T:Microsoft.Azure.Storage.IBufferManager" />インターフェイス、Table サービス クライアントに対する操作で使用されるバッファー プールを指定します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-177">Gets or sets a buffer manager that implements the <see cref="T:Microsoft.Azure.Storage.IBufferManager" /> interface, specifying a buffer pool for use with operations against the Table service client.</span></span>
            </summary>
        <value><span data-ttu-id="d31f9-178"><see cref="T:Microsoft.Azure.Storage.IBufferManager" /> 型のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-178">An object of type <see cref="T:Microsoft.Azure.Storage.IBufferManager" />.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy ConnectionPolicy { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy ConnectionPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.CloudTableClient.ConnectionPolicy" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConnectionPolicy As TableConnectionPolicy" />
      <MemberSignature Language="F#" Value="member this.ConnectionPolicy : Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy" Usage="Microsoft.Azure.CosmosDB.Table.CloudTableClient.ConnectionPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d31f9-179">Table クライアントの接続のポリシー</span><span class="sxs-lookup"><span data-stu-id="d31f9-179">The connection policy for the table client</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConsistencyLevel">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.CosmosDB.ConsistencyLevel&gt; ConsistencyLevel { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.CosmosDB.ConsistencyLevel&gt; ConsistencyLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.CloudTableClient.ConsistencyLevel" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConsistencyLevel As Nullable(Of ConsistencyLevel)" />
      <MemberSignature Language="F#" Value="member this.ConsistencyLevel : Nullable&lt;Microsoft.Azure.CosmosDB.ConsistencyLevel&gt;" Usage="Microsoft.Azure.CosmosDB.Table.CloudTableClient.ConsistencyLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.CosmosDB.ConsistencyLevel&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d31f9-180">整合性レベルの読み取り操作の使用</span><span class="sxs-lookup"><span data-stu-id="d31f9-180">Consistency level used for read operations</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Storage.Auth.StorageCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Storage.Auth.StorageCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.CloudTableClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As StorageCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Azure.Storage.Auth.StorageCredentials" Usage="Microsoft.Azure.CosmosDB.Table.CloudTableClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.Auth.StorageCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d31f9-181">Table サービス クライアントを作成するために使用するアカウントの資格情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-181">Gets the account credentials used to create the Table service client.</span></span>
            </summary>
        <value><span data-ttu-id="d31f9-182"><see cref="T:Microsoft.Azure.Storage.Auth.StorageCredentials" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-182">A <see cref="T:Microsoft.Azure.Storage.Auth.StorageCredentials" /> object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultRequestOptions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.CosmosDB.Table.TableRequestOptions DefaultRequestOptions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.CosmosDB.Table.TableRequestOptions DefaultRequestOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.CloudTableClient.DefaultRequestOptions" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultRequestOptions As TableRequestOptions" />
      <MemberSignature Language="F#" Value="member this.DefaultRequestOptions : Microsoft.Azure.CosmosDB.Table.TableRequestOptions with get, set" Usage="Microsoft.Azure.CosmosDB.Table.CloudTableClient.DefaultRequestOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableRequestOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d31f9-183">取得または Table サービス クライアントを介して行われる要求の要求オプションを既定値に設定します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-183">Gets or sets the default request options for requests made via the Table service client.</span></span>
            </summary>
        <value><span data-ttu-id="d31f9-184"><see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-184">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndGetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties EndGetServiceProperties (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties EndGetServiceProperties(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.EndGetServiceProperties(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndGetServiceProperties (asyncResult As IAsyncResult) As ServiceProperties" />
      <MemberSignature Language="F#" Value="abstract member EndGetServiceProperties : IAsyncResult -&gt; Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties&#xA;override this.EndGetServiceProperties : IAsyncResult -&gt; Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" Usage="cloudTableClient.EndGetServiceProperties asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="d31f9-185">前回の呼び出しから返された結果<see cref="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.BeginGetServiceProperties(System.AsyncCallback,System.Object)" />です。</span><span class="sxs-lookup"><span data-stu-id="d31f9-185">The result returned from a prior call to <see cref="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.BeginGetServiceProperties(System.AsyncCallback,System.Object)" />.</span></span></param>
        <summary>
            <span data-ttu-id="d31f9-186">テーブル サービスのサービス プロパティを取得する非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-186">Ends an asynchronous operation to get the service properties of the Table service.</span></span>
            </summary>
        <returns><span data-ttu-id="d31f9-187"><see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-187">A <see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndGetServiceStats">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.Shared.Protocol.ServiceStats EndGetServiceStats (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.Shared.Protocol.ServiceStats EndGetServiceStats(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.EndGetServiceStats(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndGetServiceStats (asyncResult As IAsyncResult) As ServiceStats" />
      <MemberSignature Language="F#" Value="abstract member EndGetServiceStats : IAsyncResult -&gt; Microsoft.Azure.Storage.Shared.Protocol.ServiceStats&#xA;override this.EndGetServiceStats : IAsyncResult -&gt; Microsoft.Azure.Storage.Shared.Protocol.ServiceStats" Usage="cloudTableClient.EndGetServiceStats asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.Shared.Protocol.ServiceStats</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="d31f9-188"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-188">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="d31f9-189">セカンダリ Table サービス エンドポイントのサービスの統計情報を取得する非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-189">Ends an asynchronous operation to get service stats for the secondary Table service endpoint.</span></span>
            </summary>
        <returns><span data-ttu-id="d31f9-190"><see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceStats" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-190">A <see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceStats" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndListTablesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.TableResultSegment EndListTablesSegmented (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.TableResultSegment EndListTablesSegmented(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.EndListTablesSegmented(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndListTablesSegmented (asyncResult As IAsyncResult) As TableResultSegment" />
      <MemberSignature Language="F#" Value="abstract member EndListTablesSegmented : IAsyncResult -&gt; Microsoft.Azure.CosmosDB.Table.TableResultSegment&#xA;override this.EndListTablesSegmented : IAsyncResult -&gt; Microsoft.Azure.CosmosDB.Table.TableResultSegment" Usage="cloudTableClient.EndListTablesSegmented asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableResultSegment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="d31f9-191"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-191">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="d31f9-192">テーブルの結果セグメントを返す非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-192">Ends an asynchronous operation to return a result segment of tables.</span></span> 
            </summary>
        <returns><span data-ttu-id="d31f9-193"><see cref="T:Microsoft.Azure.CosmosDB.Table.TableResultSegment" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-193">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResultSegment" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndSetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual void EndSetServiceProperties (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndSetServiceProperties(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.EndSetServiceProperties(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndSetServiceProperties (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndSetServiceProperties : IAsyncResult -&gt; unit&#xA;override this.EndSetServiceProperties : IAsyncResult -&gt; unit" Usage="cloudTableClient.EndSetServiceProperties asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="d31f9-194">前回の呼び出しから返される結果<see cref="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.BeginSetServiceProperties(Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties,System.AsyncCallback,System.Object)" /></span><span class="sxs-lookup"><span data-stu-id="d31f9-194">The result returned from a prior call to <see cref="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.BeginSetServiceProperties(Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties,System.AsyncCallback,System.Object)" /></span></span></param>
        <summary>
            <span data-ttu-id="d31f9-195">テーブル サービスのサービス プロパティを設定する非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-195">Ends an asynchronous operation to set the service properties of the Table service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties GetServiceProperties (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties GetServiceProperties(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.GetServiceProperties(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceProperties : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties&#xA;override this.GetServiceProperties : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" Usage="cloudTableClient.GetServiceProperties (requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="d31f9-196">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-196">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d31f9-197"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-197">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d31f9-198">テーブル サービスのサービスのプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-198">Gets the service properties for the Table service.</span></span>
            </summary>
        <returns><span data-ttu-id="d31f9-199"><see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-199">A <see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.GetServicePropertiesAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetServicePropertiesAsync () As Task(Of ServiceProperties)" />
      <MemberSignature Language="F#" Value="abstract member GetServicePropertiesAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties&gt;&#xA;override this.GetServicePropertiesAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties&gt;" Usage="cloudTableClient.GetServicePropertiesAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d31f9-200">テーブル サービスのサービス プロパティを取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-200">Initiates an asynchronous operation to get the service properties of the Table service.</span></span>
            </summary>
        <returns><span data-ttu-id="d31f9-201">非同期操作を表す <see cref="T:System.Threading.Tasks.Task`1" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-201">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.GetServicePropertiesAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetServicePropertiesAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties&gt;&#xA;override this.GetServicePropertiesAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties&gt;" Usage="cloudTableClient.GetServicePropertiesAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="d31f9-202">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="d31f9-202">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="d31f9-203">テーブル サービスのサービス プロパティを取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-203">Initiates an asynchronous operation to get the service properties of the Table service.</span></span>
            </summary>
        <returns><span data-ttu-id="d31f9-204">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="d31f9-204">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.GetServicePropertiesAsync(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetServicePropertiesAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties&gt;&#xA;override this.GetServicePropertiesAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties&gt;" Usage="cloudTableClient.GetServicePropertiesAsync (requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="d31f9-205">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-205">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d31f9-206"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-206">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d31f9-207">テーブル サービスのサービス プロパティを取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-207">Initiates an asynchronous operation to get the service properties of the Table service.</span></span>
            </summary>
        <returns><span data-ttu-id="d31f9-208">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="d31f9-208">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.GetServicePropertiesAsync(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetServicePropertiesAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties&gt;&#xA;override this.GetServicePropertiesAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties&gt;" Usage="cloudTableClient.GetServicePropertiesAsync (requestOptions, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="d31f9-209">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-209">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d31f9-210"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-210">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d31f9-211">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="d31f9-211">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="d31f9-212">テーブル サービスのサービス プロパティを取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-212">Initiates an asynchronous operation to get the service properties of the Table service.</span></span>
            </summary>
        <returns><span data-ttu-id="d31f9-213">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="d31f9-213">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceStats">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.Shared.Protocol.ServiceStats GetServiceStats (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.Shared.Protocol.ServiceStats GetServiceStats(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.GetServiceStats(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceStats : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.Storage.Shared.Protocol.ServiceStats&#xA;override this.GetServiceStats : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.Storage.Shared.Protocol.ServiceStats" Usage="cloudTableClient.GetServiceStats (requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.Shared.Protocol.ServiceStats</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="d31f9-214">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-214">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d31f9-215"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-215">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d31f9-216">セカンダリ Table サービス エンドポイントのサービスの統計情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-216">Gets service stats for the secondary Table service endpoint.</span></span>
            </summary>
        <returns><span data-ttu-id="d31f9-217"><see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceStats" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-217">A <see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceStats" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceStatsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.GetServiceStatsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetServiceStatsAsync () As Task(Of ServiceStats)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceStatsAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceStats&gt;&#xA;override this.GetServiceStatsAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceStats&gt;" Usage="cloudTableClient.GetServiceStatsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceStats&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d31f9-218">セカンダリ Table サービス エンドポイントのサービスの統計情報を取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-218">Initiates an asynchronous operation to get service stats for the secondary Table service endpoint.</span></span>
            </summary>
        <returns><span data-ttu-id="d31f9-219">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceStats" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="d31f9-219">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceStats" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceStatsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.GetServiceStatsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceStatsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceStats&gt;&#xA;override this.GetServiceStatsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceStats&gt;" Usage="cloudTableClient.GetServiceStatsAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceStats&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="d31f9-220">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="d31f9-220">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="d31f9-221">セカンダリ Table サービス エンドポイントのサービスの統計情報を取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-221">Initiates an asynchronous operation to get service stats for the secondary Table service endpoint.</span></span>
            </summary>
        <returns><span data-ttu-id="d31f9-222">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceStats" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="d31f9-222">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceStats" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceStatsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.GetServiceStatsAsync(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceStatsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceStats&gt;&#xA;override this.GetServiceStatsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceStats&gt;" Usage="cloudTableClient.GetServiceStatsAsync (requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceStats&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="d31f9-223">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-223">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d31f9-224"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-224">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d31f9-225">セカンダリ Table サービス エンドポイントのサービスの統計情報を取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-225">Initiates an asynchronous operation to get service stats for the secondary Table service endpoint.</span></span>
            </summary>
        <returns><span data-ttu-id="d31f9-226">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceStats" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="d31f9-226">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceStats" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceStatsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.GetServiceStatsAsync(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceStatsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceStats&gt;&#xA;override this.GetServiceStatsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceStats&gt;" Usage="cloudTableClient.GetServiceStatsAsync (requestOptions, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceStats&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="d31f9-227">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-227">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d31f9-228"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-228">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d31f9-229">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="d31f9-229">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="d31f9-230">セカンダリ Table サービス エンドポイントのサービスの統計情報を取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-230">Initiates an asynchronous operation to get service stats for the secondary Table service endpoint.</span></span>
            </summary>
        <returns><span data-ttu-id="d31f9-231">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceStats" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="d31f9-231">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceStats" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTableReference">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.CloudTable GetTableReference (string tableName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.CloudTable GetTableReference(string tableName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.GetTableReference(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetTableReference (tableName As String) As CloudTable" />
      <MemberSignature Language="F#" Value="abstract member GetTableReference : string -&gt; Microsoft.Azure.CosmosDB.Table.CloudTable&#xA;override this.GetTableReference : string -&gt; Microsoft.Azure.CosmosDB.Table.CloudTable" Usage="cloudTableClient.GetTableReference tableName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.CloudTable</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tableName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="tableName"><span data-ttu-id="d31f9-232">テーブルの名前を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="d31f9-232">A string containing the name of the table.</span></span></param>
        <summary>
            <span data-ttu-id="d31f9-233">指定されたテーブルへの参照を取得します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-233">Gets a reference to the specified table.</span></span>
            </summary>
        <returns><span data-ttu-id="d31f9-234"><see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTable" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-234">A <see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTable" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTables">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.CosmosDB.Table.CloudTable&gt; ListTables (string prefix = null, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.CosmosDB.Table.CloudTable&gt; ListTables(string prefix, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.ListTables(System.String,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ListTables : string * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; seq&lt;Microsoft.Azure.CosmosDB.Table.CloudTable&gt;&#xA;override this.ListTables : string * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; seq&lt;Microsoft.Azure.CosmosDB.Table.CloudTable&gt;" Usage="cloudTableClient.ListTables (prefix, requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.CosmosDB.Table.CloudTable&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="d31f9-235">テーブル名のプレフィックスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="d31f9-235">A string containing the table name prefix.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="d31f9-236">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-236">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d31f9-237"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-237">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d31f9-238">テーブル、遅延、取得した指定したプレフィックスで始まるの列挙可能なコレクションを返します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-238">Returns an enumerable collection of tables, retrieved lazily, that start with the specified prefix.</span></span>
            </summary>
        <returns><span data-ttu-id="d31f9-239">列挙可能なコレクション<see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTable" />遅れて取得されるオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-239">An enumerable collection of <see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTable" /> objects that are retrieved lazily.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.TableResultSegment ListTablesSegmented (Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.TableResultSegment ListTablesSegmented(class Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.ListTablesSegmented(Microsoft.Azure.CosmosDB.Table.TableContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ListTablesSegmented (currentToken As TableContinuationToken) As TableResultSegment" />
      <MemberSignature Language="F#" Value="abstract member ListTablesSegmented : Microsoft.Azure.CosmosDB.Table.TableContinuationToken -&gt; Microsoft.Azure.CosmosDB.Table.TableResultSegment&#xA;override this.ListTablesSegmented : Microsoft.Azure.CosmosDB.Table.TableContinuationToken -&gt; Microsoft.Azure.CosmosDB.Table.TableResultSegment" Usage="cloudTableClient.ListTablesSegmented currentToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableResultSegment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
      </Parameters>
      <Docs>
        <param name="currentToken"><span data-ttu-id="d31f9-240">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />前の一覧作成操作によって返されます。</span><span class="sxs-lookup"><span data-stu-id="d31f9-240">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> returned by a previous listing operation.</span></span></param>
        <summary>
            <span data-ttu-id="d31f9-241">テーブルの結果セグメントを返します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-241">Returns a result segment of tables.</span></span>
            </summary>
        <returns><span data-ttu-id="d31f9-242"><see cref="T:Microsoft.Azure.CosmosDB.Table.TableResultSegment" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-242">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResultSegment" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.TableResultSegment ListTablesSegmented (string prefix, Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.TableResultSegment ListTablesSegmented(string prefix, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.ListTablesSegmented(System.String,Microsoft.Azure.CosmosDB.Table.TableContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ListTablesSegmented (prefix As String, currentToken As TableContinuationToken) As TableResultSegment" />
      <MemberSignature Language="F#" Value="abstract member ListTablesSegmented : string * Microsoft.Azure.CosmosDB.Table.TableContinuationToken -&gt; Microsoft.Azure.CosmosDB.Table.TableResultSegment&#xA;override this.ListTablesSegmented : string * Microsoft.Azure.CosmosDB.Table.TableContinuationToken -&gt; Microsoft.Azure.CosmosDB.Table.TableResultSegment" Usage="cloudTableClient.ListTablesSegmented (prefix, currentToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableResultSegment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="currentToken" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="d31f9-243">テーブル名のプレフィックスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="d31f9-243">A string containing the table name prefix.</span></span></param>
        <param name="currentToken"><span data-ttu-id="d31f9-244">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />前の一覧作成操作によって返されます。</span><span class="sxs-lookup"><span data-stu-id="d31f9-244">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> returned by a previous listing operation.</span></span></param>
        <summary>
            <span data-ttu-id="d31f9-245">テーブルの遅延、取得した指定したプレフィックスで始まる結果セグメントを返します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-245">Returns a result segment of tables, retrieved lazily, that start with the specified prefix.</span></span>
            </summary>
        <returns><span data-ttu-id="d31f9-246"><see cref="T:Microsoft.Azure.CosmosDB.Table.TableResultSegment" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-246">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResultSegment" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.TableResultSegment ListTablesSegmented (string prefix, Nullable&lt;int&gt; maxResults, Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.TableResultSegment ListTablesSegmented(string prefix, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.ListTablesSegmented(System.String,System.Nullable{System.Int32},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ListTablesSegmented : string * Nullable&lt;int&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.CosmosDB.Table.TableResultSegment&#xA;override this.ListTablesSegmented : string * Nullable&lt;int&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.CosmosDB.Table.TableResultSegment" Usage="cloudTableClient.ListTablesSegmented (prefix, maxResults, currentToken, requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableResultSegment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="d31f9-247">テーブル名のプレフィックスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="d31f9-247">A string containing the table name prefix.</span></span></param>
        <param name="maxResults"><span data-ttu-id="d31f9-248">5000 の操作あたりの上限に達するまで、一度に返される結果の最大数を示す正の整数値。</span><span class="sxs-lookup"><span data-stu-id="d31f9-248">A non-negative integer value that indicates the maximum number of results to be returned at a time, up to the per-operation limit of 5000.</span></span> <span data-ttu-id="d31f9-249">この値が場合<c>null</c>結果の最大数が返されます、最大 5000 です。</span><span class="sxs-lookup"><span data-stu-id="d31f9-249">If this value is <c>null</c>, the maximum possible number of results will be returned, up to 5000.</span></span></param>
        <param name="currentToken"><span data-ttu-id="d31f9-250">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />前の一覧作成操作によって返されます。</span><span class="sxs-lookup"><span data-stu-id="d31f9-250">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> returned by a previous listing operation.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="d31f9-251">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-251">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d31f9-252"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-252">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d31f9-253">テーブルの遅延、取得した指定したプレフィックスで始まる結果セグメントを返します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-253">Returns a result segment of tables, retrieved lazily, that start with the specified prefix.</span></span>
            </summary>
        <returns><span data-ttu-id="d31f9-254"><see cref="T:Microsoft.Azure.CosmosDB.Table.TableResultSegment" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-254">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResultSegment" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt; ListTablesSegmentedAsync (Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt; ListTablesSegmentedAsync(class Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.ListTablesSegmentedAsync(Microsoft.Azure.CosmosDB.Table.TableContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ListTablesSegmentedAsync (currentToken As TableContinuationToken) As Task(Of TableResultSegment)" />
      <MemberSignature Language="F#" Value="abstract member ListTablesSegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt;&#xA;override this.ListTablesSegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt;" Usage="cloudTableClient.ListTablesSegmentedAsync currentToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
      </Parameters>
      <Docs>
        <param name="currentToken"><span data-ttu-id="d31f9-255">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />前の一覧作成操作によって返されます。</span><span class="sxs-lookup"><span data-stu-id="d31f9-255">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> returned by a previous listing operation.</span></span></param>
        <summary>
            <span data-ttu-id="d31f9-256">テーブルの結果セグメントを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-256">Initiates an asynchronous operation to return a result segment of tables.</span></span>
            </summary>
        <returns><span data-ttu-id="d31f9-257">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.Azure.CosmosDB.Table.TableResultSegment" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="d31f9-257">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResultSegment" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt; ListTablesSegmentedAsync (Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt; ListTablesSegmentedAsync(class Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.ListTablesSegmentedAsync(Microsoft.Azure.CosmosDB.Table.TableContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListTablesSegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt;&#xA;override this.ListTablesSegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt;" Usage="cloudTableClient.ListTablesSegmentedAsync (currentToken, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="currentToken"><span data-ttu-id="d31f9-258">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />前の一覧作成操作によって返されます。</span><span class="sxs-lookup"><span data-stu-id="d31f9-258">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> returned by a previous listing operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d31f9-259">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="d31f9-259">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="d31f9-260">テーブルの結果セグメントを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-260">Initiates an asynchronous operation to return a result segment of tables.</span></span>
            </summary>
        <returns><span data-ttu-id="d31f9-261">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.Azure.CosmosDB.Table.TableResultSegment" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="d31f9-261">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResultSegment" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt; ListTablesSegmentedAsync (string prefix, Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt; ListTablesSegmentedAsync(string prefix, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.ListTablesSegmentedAsync(System.String,Microsoft.Azure.CosmosDB.Table.TableContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ListTablesSegmentedAsync (prefix As String, currentToken As TableContinuationToken) As Task(Of TableResultSegment)" />
      <MemberSignature Language="F#" Value="abstract member ListTablesSegmentedAsync : string * Microsoft.Azure.CosmosDB.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt;&#xA;override this.ListTablesSegmentedAsync : string * Microsoft.Azure.CosmosDB.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt;" Usage="cloudTableClient.ListTablesSegmentedAsync (prefix, currentToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="currentToken" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="d31f9-262">テーブル名のプレフィックスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="d31f9-262">A string containing the table name prefix.</span></span></param>
        <param name="currentToken"><span data-ttu-id="d31f9-263">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />前の一覧作成操作によって返されます。</span><span class="sxs-lookup"><span data-stu-id="d31f9-263">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> returned by a previous listing operation.</span></span></param>
        <summary>
            <span data-ttu-id="d31f9-264">指定したプレフィックスで始まるテーブルの結果セグメントを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-264">Initiates an asynchronous operation to return a result segment of tables that start with the specified prefix.</span></span>
            </summary>
        <returns><span data-ttu-id="d31f9-265">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.Azure.CosmosDB.Table.TableResultSegment" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="d31f9-265">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResultSegment" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt; ListTablesSegmentedAsync (string prefix, Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt; ListTablesSegmentedAsync(string prefix, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.ListTablesSegmentedAsync(System.String,Microsoft.Azure.CosmosDB.Table.TableContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListTablesSegmentedAsync : string * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt;&#xA;override this.ListTablesSegmentedAsync : string * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt;" Usage="cloudTableClient.ListTablesSegmentedAsync (prefix, currentToken, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="currentToken" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="d31f9-266">テーブル名のプレフィックスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="d31f9-266">A string containing the table name prefix.</span></span></param>
        <param name="currentToken"><span data-ttu-id="d31f9-267">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />前の一覧作成操作によって返されます。</span><span class="sxs-lookup"><span data-stu-id="d31f9-267">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> returned by a previous listing operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d31f9-268">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="d31f9-268">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="d31f9-269">指定したプレフィックスで始まるテーブルの結果セグメントを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-269">Initiates an asynchronous operation to return a result segment of tables that start with the specified prefix.</span></span>
            </summary>
        <returns><span data-ttu-id="d31f9-270">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.Azure.CosmosDB.Table.TableResultSegment" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="d31f9-270">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResultSegment" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt; ListTablesSegmentedAsync (string prefix, Nullable&lt;int&gt; maxResults, Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt; ListTablesSegmentedAsync(string prefix, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.ListTablesSegmentedAsync(System.String,System.Nullable{System.Int32},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ListTablesSegmentedAsync : string * Nullable&lt;int&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt;&#xA;override this.ListTablesSegmentedAsync : string * Nullable&lt;int&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt;" Usage="cloudTableClient.ListTablesSegmentedAsync (prefix, maxResults, currentToken, requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="d31f9-271">テーブル名のプレフィックスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="d31f9-271">A string containing the table name prefix.</span></span></param>
        <param name="maxResults"><span data-ttu-id="d31f9-272">5000 の操作あたりの上限に達するまで、一度に返される結果の最大数を示す正の整数値。</span><span class="sxs-lookup"><span data-stu-id="d31f9-272">A non-negative integer value that indicates the maximum number of results to be returned at a time, up to the per-operation limit of 5000.</span></span> <span data-ttu-id="d31f9-273">この値が場合<c>null</c>結果の最大数が返されます、最大 5000 です。</span><span class="sxs-lookup"><span data-stu-id="d31f9-273">If this value is <c>null</c>, the maximum possible number of results will be returned, up to 5000.</span></span></param>
        <param name="currentToken"><span data-ttu-id="d31f9-274">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />前の一覧作成操作によって返されます。</span><span class="sxs-lookup"><span data-stu-id="d31f9-274">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> returned by a previous listing operation.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="d31f9-275">サーバーのタイムアウト、最大実行時間、および操作の再試行ポリシーです。</span><span class="sxs-lookup"><span data-stu-id="d31f9-275">The server timeout, maximum execution time, and retry policies for the operation.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d31f9-276"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-276">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d31f9-277">指定したプレフィックスで始まるテーブルの結果セグメントを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-277">Initiates an asynchronous operation to return a result segment of tables that start with the specified prefix.</span></span>
            </summary>
        <returns><span data-ttu-id="d31f9-278">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.Azure.CosmosDB.Table.TableResultSegment" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="d31f9-278">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResultSegment" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt; ListTablesSegmentedAsync (string prefix, Nullable&lt;int&gt; maxResults, Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt; ListTablesSegmentedAsync(string prefix, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.ListTablesSegmentedAsync(System.String,System.Nullable{System.Int32},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListTablesSegmentedAsync : string * Nullable&lt;int&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt;&#xA;override this.ListTablesSegmentedAsync : string * Nullable&lt;int&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt;" Usage="cloudTableClient.ListTablesSegmentedAsync (prefix, maxResults, currentToken, requestOptions, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="d31f9-279">テーブル名のプレフィックスを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="d31f9-279">A string containing the table name prefix.</span></span></param>
        <param name="maxResults"><span data-ttu-id="d31f9-280">5000 の操作あたりの上限に達するまで、一度に返される結果の最大数を示す正の整数値。</span><span class="sxs-lookup"><span data-stu-id="d31f9-280">A non-negative integer value that indicates the maximum number of results to be returned at a time, up to the per-operation limit of 5000.</span></span> <span data-ttu-id="d31f9-281">この値が場合<c>null</c>結果の最大数が返されます、最大 5000 です。</span><span class="sxs-lookup"><span data-stu-id="d31f9-281">If this value is <c>null</c>, the maximum possible number of results will be returned, up to 5000.</span></span></param>
        <param name="currentToken"><span data-ttu-id="d31f9-282">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />前の一覧作成操作によって返されます。</span><span class="sxs-lookup"><span data-stu-id="d31f9-282">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> returned by a previous listing operation.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="d31f9-283">サーバーのタイムアウト、最大実行時間、および操作の再試行ポリシーです。</span><span class="sxs-lookup"><span data-stu-id="d31f9-283">The server timeout, maximum execution time, and retry policies for the operation.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d31f9-284"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-284">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d31f9-285">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="d31f9-285">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="d31f9-286">指定したプレフィックスで始まるテーブルの結果セグメントを返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-286">Initiates an asynchronous operation to return a result segment of tables that start with the specified prefix.</span></span>
            </summary>
        <returns><span data-ttu-id="d31f9-287">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.Azure.CosmosDB.Table.TableResultSegment" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="d31f9-287">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResultSegment" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual void SetServiceProperties (Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties properties, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SetServiceProperties(class Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties properties, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.SetServiceProperties(Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetServiceProperties : Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; unit&#xA;override this.SetServiceProperties : Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; unit" Usage="cloudTableClient.SetServiceProperties (properties, requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="properties" Type="Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="d31f9-288"><see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-288">A <see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" /> object.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="d31f9-289">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-289">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d31f9-290"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-290">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d31f9-291">テーブル サービスのサービスのプロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-291">Sets the service properties of the Table service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetServicePropertiesAsync (Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties properties);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetServicePropertiesAsync(class Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.SetServicePropertiesAsync(Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function SetServicePropertiesAsync (properties As ServiceProperties) As Task" />
      <MemberSignature Language="F#" Value="abstract member SetServicePropertiesAsync : Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties -&gt; System.Threading.Tasks.Task&#xA;override this.SetServicePropertiesAsync : Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties -&gt; System.Threading.Tasks.Task" Usage="cloudTableClient.SetServicePropertiesAsync properties" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="properties" Type="Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="d31f9-292"><see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-292">A <see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="d31f9-293">テーブル サービスのサービス プロパティを設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-293">Initiates an asynchronous operation to set the service properties of the Table service.</span></span>
            </summary>
        <returns><span data-ttu-id="d31f9-294">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-294">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetServicePropertiesAsync (Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties properties, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetServicePropertiesAsync(class Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties properties, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.SetServicePropertiesAsync(Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetServicePropertiesAsync : Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetServicePropertiesAsync : Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudTableClient.SetServicePropertiesAsync (properties, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="properties" Type="Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="d31f9-295"><see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-295">A <see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" /> object.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d31f9-296">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="d31f9-296">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="d31f9-297">テーブル サービスのサービス プロパティを設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-297">Initiates an asynchronous operation to set the service properties of the Table service.</span></span>
            </summary>
        <returns><span data-ttu-id="d31f9-298">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-298">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetServicePropertiesAsync (Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties properties, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetServicePropertiesAsync(class Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties properties, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.SetServicePropertiesAsync(Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetServicePropertiesAsync : Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.SetServicePropertiesAsync : Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudTableClient.SetServicePropertiesAsync (properties, requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="properties" Type="Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="d31f9-299"><see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-299">A <see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" /> object.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="d31f9-300">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-300">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d31f9-301"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-301">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d31f9-302">テーブル サービスのサービス プロパティを設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-302">Initiates an asynchronous operation to set the service properties of the Table service.</span></span>
            </summary>
        <returns><span data-ttu-id="d31f9-303">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-303">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetServicePropertiesAsync (Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties properties, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetServicePropertiesAsync(class Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties properties, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.SetServicePropertiesAsync(Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetServicePropertiesAsync : Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetServicePropertiesAsync : Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudTableClient.SetServicePropertiesAsync (properties, requestOptions, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="properties" Type="Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="d31f9-304"><see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-304">A <see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" /> object.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="d31f9-305">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-305">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d31f9-306"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-306">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d31f9-307">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="d31f9-307">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="d31f9-308">テーブル サービスのサービス プロパティを設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-308">Initiates an asynchronous operation to set the service properties of the Table service.</span></span>
            </summary>
        <returns><span data-ttu-id="d31f9-309">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d31f9-309">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageUri">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Storage.StorageUri StorageUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Storage.StorageUri StorageUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.CloudTableClient.StorageUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StorageUri As StorageUri" />
      <MemberSignature Language="F#" Value="member this.StorageUri : Microsoft.Azure.Storage.StorageUri" Usage="Microsoft.Azure.CosmosDB.Table.CloudTableClient.StorageUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.StorageUri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d31f9-310">プライマリとセカンダリの両方の場所の Table サービスのエンドポイントを取得します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-310">Gets the Table service endpoints for both the primary and secondary locations.</span></span>
            </summary>
        <value><span data-ttu-id="d31f9-311">型のオブジェクト<see cref="P:Microsoft.Azure.CosmosDB.Table.CloudTableClient.StorageUri" />プライマリとセカンダリの両方の場所のサービスの Uri をテーブルを格納します。</span><span class="sxs-lookup"><span data-stu-id="d31f9-311">An object of type <see cref="P:Microsoft.Azure.CosmosDB.Table.CloudTableClient.StorageUri" /> containing Table service URIs for both the primary and secondary locations.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>